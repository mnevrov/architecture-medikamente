# Task1 — Анализ безопасности системы

Этот набор файлов подготовлен для загрузки в репозиторий `architecture-medikamente` в директорию `Task1` в рамках PR.

## Состав

- `DFD-Registration.md` — DFD: регистрация пациента и запись на приём (As-Is).
- `DFD-Payments.md` — DFD: приём оплаты и учёт платежей (As-Is).
- `DFD-Lab.md` — DFD: обработка анализов и обмен с лабораторией (As-Is).
- `DFD-MedicalRecords.md` — DFD: ведение медкарт и файлов пациентов (As-Is).
- `DFD-Inventory.md` — DFD: учёт ТМЦ и закупок (As-Is).
- `Confidential-Data-Inventory.csv` — реестр конфиденциальных данных и PII.
- `Problems.md` — список проблемных зон (gap analysis) и риски.
- `Security-Mapping.md` — сопоставление процессов с требованиями и практиками (Privacy by Design, Data Minimization, Data Lineage и др.).
- `Data-Tagging-Design.md` — механизм тегирования данных и политика меток.
- `Controls-and-Tools.md` — инструменты/меры защиты и указание, где внедрять в потоках данных.
- `NEXT-Steps.md` — что улучшить и как перейти к To‑Be + пометки на диаграммах.

## Как проверить локально

Откройте `*.md` прямо в GitHub (рендерится Mermaid), либо в VS Code с расширением Mermaid.
CSV можно открыть в Excel.

## Примечание

Диаграммы отражают текущее состояние (As-Is) согласно описанию и файлу `project10-landscape.drawio.xml`.
