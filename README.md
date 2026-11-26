# Medical Device IFU: EN → RU Translation Editing & LQA Case Study

**Author:** Catherine Pleshkova (`@catherinepleshkova`)  
**Domain:** Medical Devices (Class IIb/III), Intensive Care Equipment, Regulatory Documentation  
**Language Pair:** English (EN) → Russian (RU)  
**Focus:** Linguistic Quality Assurance (LQA), Terminology Management (ISO 13485 / ГОСТ Р ИСО 15223-1), Stylistic & Technical Editing  

---

## Project Overview

This repository demonstrates a full cycle of **medical device translation editing and Linguistic Quality Assurance (LQA)** on an authentic excerpt from an **Instructions for Use (IFU)** manual for a critical care **Mechanical Ventilator** (sections: *Intended Use, Contraindications, Warnings & Cautions, Pre-Use Calibration*).

The workflow addresses critical risks typical of raw machine translation (MT) or non-specialized medical translation:
* **Modality & Safety Signal Words:** Strict adherence to regulatory risk levels (*DANGER / WARNING / CAUTION* and *must / shall / may*).
* **Regulatory Terminology:** Alignment with Roszdravnadzor / EAEU registration dossiers and Russian state standards (**ГОСТ Р ИСО 15223-1**, **ГОСТ Р 50444**).
* **Technical Accuracy:** Prevention of false friends (e.g., *calibration* vs. *verification*, *disposable* vs. *single-use*), unit consistency (SI), and clinical naturalness in Russian.

---

## 1. Comparative Editing & LQA Table (EN → RU)

| # | Source Text (EN) | Raw / Unedited Draft (RU) | Edited & QA-Approved Text (RU) | Editor’s LQA Rationale & Error Category |
|---|---|---|---|---|
| **1** | **INTENDED USE**<br>The AeroVent Pro ICU Ventilator is intended to provide continuous or intermittent positive-pressure mechanical ventilation support for adult and pediatric patients (weighing at least 5 kg) in intensive care units and during intra-hospital transport. | **НАЗНАЧЕНИЕ ИСПОЛЬЗОВАНИЯ**<br>Аппарат ИВЛ AeroVent Pro ICU предназначен для обеспечения непрерывной или прерывистой механической вентиляционной поддержки с положительным давлением для взрослых и педиатрических пациентов (весом минимум 5 кг) в отделениях интенсивной терапии и во время внутрибольничного транспорта. | **НАЗНАЧЕНИЕ**<br>Аппарат ИВЛ реанимационный AeroVent Pro предназначен для проведения непрерывной или перемежающейся искусственной вентиляции легких (ИВЛ) с положительным давлением у взрослых пациентов и детей с массой тела не менее 5 кг в отделениях реанимации и интенсивной терапии (ОРИТ), а также при внутрибольничной транспортировке. | **Terminology & Style:**<br>• *Intended Use* → «Назначение» (standard EAEU/Roszdravnadzor dossier heading).<br>• *Intermittent ventilation* → «перемежающаяся» (accepted clinical term, not «прерывистая»).<br>• *Pediatric patients* → «дети» (GOST style).<br>• *Weighing* → «с массой тела» (medical accuracy).<br>• *Intra-hospital transport* → «внутрибольничная транспортировка» (eliminated literal «транспорт»). |
| **2** | **CONTRAINDICATIONS**<br>Non-invasive ventilation (NIV) is contraindicated in patients with severe facial trauma, untreated pneumothorax, or inability to protect the airway. | **ПРОТИВОПОКАЗАНИЯ**<br>Неинвазивная вентиляция (НИВ) противопоказана пациентам с тяжелой лицевой травмой, нелеченным пневмотораксом или неспособностью защитить дыхательные пути. | **ПРОТИВОПОКАЗАНИЯ**<br>Неинвазивная вентиляция легких (НИВЛ) противопоказана пациентам с тяжелыми травмами лицевого скелета, недренированным пневмотораксом или отсутствием защитных рефлексов верхних дыхательных путей. | **Clinical Precision:**<br>• Expanded acronym to standard Russian *НИВЛ*.<br>• *Untreated pneumothorax* in ICU context specifically refers to *недренированный* (undrained) pneumothorax.<br>• *Inability to protect the airway* → idiomatic clinical Russian phrasing. |
| **3** | **WARNING**<br>Explosion Hazard: Do not operate the ventilator in the presence of flammable anesthetics. Failure to comply may result in death or serious injury. | **ПРЕДУПРЕЖДЕНИЕ**<br>Опасность взрыва: Не используйте вентилятор в присутствии легковоспламеняющихся анестетиков. Несоблюдение может привести к смерти или серьезной травме. | **ОСТОРОЖНО! ОПАСНОСТЬ ВЗРЫВА**<br>Запрещается эксплуатировать аппарат ИВЛ в среде, содержащей легковоспламеняющиеся анестетики. Несоблюдение данного требования может привести к летальному исходу или причинению тяжкого вреда здоровью. | **Regulatory & Safety Standards:**<br>• Aligned warning block with Russian medical device labeling conventions.<br>• Replaced Anglicism *вентилятор* with *аппарат ИВЛ*.<br>• *Death or serious injury* → standard regulatory formula («летальный исход или тяжкий вред здоровью»). |
| **4** | **CAUTION**<br>Single-use bacterial/viral filters must be replaced every 24 hours or immediately if visibly soiled. Do not re-sterilize disposable breathing circuits. | **ОСТОРОЖНО**<br>Одноразовые бактериально-вирусные фильтры должны заменяться каждые 24 часа или немедленно, если они видимо загрязнены. Не стерилизуйте повторно одноразовые дыхательные контуры. | **ВНИМАНИЕ**<br>Бактериально-вирусные фильтры однократного применения подлежат замене каждые 24 часа либо незамедлительно при наличии видимых загрязнений. Повторная стерилизация дыхательных контуров однократного применения запрещена. | **Modality & GOST Compliance:**<br>• Differentiated *CAUTION* («ВНИМАНИЕ» — equipment/consumable rule) from *WARNING*.<br>• *Single-use / disposable* → «однократного применения» (per **ГОСТ Р ИСО 15223-1**).<br>• Converted passive voice («должны заменяться») into crisp imperative regulatory Russian. |
| **5** | **PRE-USE CHECK**<br>Perform an automated leak and compliance test prior to connecting the patient. Ensure the inspiratory pressure sensor reading is within ±2 cmH₂O of the reference gauge. | **ПРОВЕРКА ПЕРЕД ИСПОЛЬЗОВАНИЕМ**<br>Выполните автоматический тест на утечку и комплаенс перед подключением пациента. Убедитесь, что показания датчика давления вдоха находятся в пределах ±2 см вод. ст. от эталонного манометра. | **ПРОВЕРКА ПЕРЕД НАЧАЛОМ ЭКСПЛУАТАЦИИ**<br>Перед подключением пациента выполните автоматический тест на герметичность и растяжимость (комплайнс) дыхательного контура. Убедитесь, что показания датчика давления на вдохе отклоняются от показаний контрольного манометра не более чем на ±2 см вод. ст. | **Technical Accuracy & Punctuation:**<br>• *Leak test* → «тест на герметичность» (standard engineering term).<br>• *Compliance* → clarified as «растяжимость (комплайнс) дыхательного контура» to avoid ambiguity.<br>• Fixed logical phrasing («отклоняются... не более чем на ±2 см вод. ст.»). |

---

## 2. Quality Metrics & Automated QA

Before final sign-off, the Russian target file was verified using a custom Python QA pipeline ([Localization_QA_Checker](https://github.com/catherinepleshkova/Localization_QA_Checker)) alongside standard CAT QA checks:

* **Zero critical errors:** 100% match on numerical values (`5 kg`, `24 hours`, `±2 cmH₂O`), SI units, and non-translatable model identifiers (`AeroVent Pro`).
* **Terminology consistency:** 100% adherence to the approved project termbase (`glossary_en_ru.csv`).
* **Style & Register:** Eliminated calques, passive constructions, and inconsistent acronyms across all sections.

---

## Repository Structure

* `README.md` — Project overview, comparative LQA table, and editorial rationale.
* `glossary_en_ru.csv` — Bilingual medical device termbase (30 core ICU & regulatory terms) ready for import into Trados Studio / Smartcat / memoQ.
* `lqa_checklist_medtech.md` — 10-point Linguistic Quality Assurance checklist for medical device documentation.
