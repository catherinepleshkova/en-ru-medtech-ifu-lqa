# 10-Point LQA Checklist for Medical Device Documentation (EN → RU)

1. **Regulatory Headers & Section Structure:** Verify alignment with Roszdravnadzor / EAEU technical file structure (*Назначение, Показания, Противопоказания, Побочные действия, Меры предосторожности, Технические характеристики*).
2. **Safety Signal Words & Modality:** Ensure strict hierarchy (*ОПАСНО / ОСТОРОЖНО / ВНИМАНИЕ*) and accurate rendering of modal verbs (*shall/must* → обязательное требование; *should* → рекомендация; *may* → допустимость).
3. **GOST / ISO Symbol Terminology:** Cross-check packaging and labeling terms against **ГОСТ Р ИСО 15223-1** (*однократного применения*, *изготовитель*, *код партии*, *дата изготовления*).
4. **Numerical & SI Unit Integrity:** Audit 100% of dosages, pressure/flow values, tolerances (`±`), temperatures, and convert/format decimal separators according to Russian typography (comma `,` instead of dot `.` in prose/tables where applicable).
5. **Hardware UI & Software Strings:** Verify that on-screen button names, alarm messages, and error codes match the localized device UI (or remain untranslated in brackets if the device UI is English-only).
6. **Metrology & Maintenance Terms:** Distinguish *calibration* (калибровка), *verification* (поверка), *validation* (валидация), and *preventive maintenance* (техническое обслуживание).
7. **Elimination of Calques & Anglicisms:** Replace word-for-word translations (*пациентский контур* → контур пациента; *вентилятор* → аппарат ИВЛ; *процедура* → методика/порядок действий).
8. **Acronym Consistency:** Expand clinical/technical acronyms upon first mention in Russian (*искусственная вентиляция легких (ИВЛ)*) and maintain consistency throughout the document.
9. **Omissions & Additions:** Run bilingual segment-by-segment check to confirm zero skipped warnings, footnotes, or table cells.
10. **Automated QA Pass:** Run Xbench / Verifika / Python QA script to catch double spaces, broken tags, inconsistent terminology, and punctuation errors.