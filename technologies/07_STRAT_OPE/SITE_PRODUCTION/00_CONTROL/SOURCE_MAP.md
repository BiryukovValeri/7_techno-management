# SOURCE_MAP — S00
| Path / source group | Class | Role | Read status | Canonical/current | Notes |
|---|---|---|---|---|---|
| 30 Документация/proSTRANSTVO_Операционная_Система_v1.0.docx | A | P1B main source of truth; route, 4 products, verdicts, stop-lines | READ | YES | Extracted from DOCX XML |
| 30 Документация/proSTRANSTVO_Матрица_Доказательности_v1.0.xlsx | B | evidence model, diagnostic scale, working-set controls | READ | YES | 5 sheets extracted |
| 30 Документация/proSTRANSTVO_Реестр_Артефактов_И_Переходов_v1.0.xlsx | B | artifacts, transitions, quality gates | READ | YES | 5 sheets extracted |
| 30 Документация/proSTRANSTVO_Справочник_Инструментов_И_Карточек_Знания_v1.0.xlsx | B | current instrument/model knowledge register and release counters | READ | YES | v1.0; 214 records; core 115 accepted |
| 30 Документация/proSTRANSTVO_Руководство_По_Технологии_v0.2.docx | A/E-lineage | recovery guide | READ | NO, lineage | Explicit Recovery Build |
| 30 Документация/proSTRANSTVO_Changelog_v1.0.docx | B | release lineage | READ | YES | P1B establishes main source of truth |
| 30 Документация/proSTRANSTVO_Аудит_Закрытия_Релиза_v1.0.xlsx | B | release closure | READ | YES | 38/38 closed; no partial/open release artifacts |
| 30 Документация/10 Диагностика/*Клиентская_Версия_v0.3.docx | B | product layer | READ | current product layer with conflicts | Older diagnostic math conflicts with P1B |
| 30 Документация/20 Сессия/*Клиентская_Версия_v0.3.docx | B | product layer | READ | current product layer | Session boundaries and outputs checked |
| 30 Документация/30 Спринт/*Клиентская_Версия_v0.3.docx | B | product layer | READ | current product layer | 30/60/90, owners, metrics, stop rules checked |
| 30 Документация/40 Сопровождение/*Клиентская_Версия_v0.3.docx | B | product layer | READ | current product layer | active-contour gate and exit logic checked |
| 30 Документация/proSTRANSTVO_Квалификация_Клиента_Перед_Диагностикой_v1.0.docx | C/B | paid-entry qualification | READ | YES | P3, does not rewrite core |
| 30 Документация/proSTRANSTVO_Продукты_Сроки_И_Цены_v0.3.docx | C | commercial/product packaging | READ | DERIVED / conflict-sensitive | Older three-status wording conflicts with P1B four-status system |
| 30 Документация/proSTRANSTVO_FAQ_По_Аудиториям_v1.0.docx | C | audience language / anti-category | READ | YES derived | Diagnostics first; no catalog/menu |
| 30 Документация/proSTRANSTVO_Языковой_Стандарт_v1.0.docx | C | public language | READ | YES | Public name confirmed |
| 50 Кейсы/proSTRANSTVO_Кейс_00_Каталог_12_кейсов.docx | C | case inventory | READ | YES derived | 12 generalized cases; 10 success, 1 Hold, 1 Stop |
| 50 Кейсы/cases 01–12 | C | case detail | INDEXED | current derived | Catalog read; individual files non-governing for S00 truth |
| 80 Визуализация/проSTRAнство_Визуализации_01_12_Описание_и_Self_QA.md | C | visualization semantics / anti-category | READ | derived | 12 visual concepts inventoried |
| 30 Документация/proSTRANSTVO_Коммерция_Презентация_v1.0.pptx.inspect.ndjson | C | extracted PPTX text/structure | READ | derived | Commercial route cross-checked |
| 10 Первоисточники/Книга_01/02/06/07 DOCX | A-foundation | source provenance for STR/OPE/FIN/customer libraries | TECHNICAL HOLD | foundational, not current process controller | >1 MB GitHub Contents gives empty content; blob reader UTF-8 fails |
| 10 Первоисточники/proSTRANSTVO_Первоисточник_Стратегические_Модели.xlsx | A-foundation | strategic-model source table | INDEXED | foundational | current v1.0 knowledge register provides accepted navigation; direct source remains to read before any claim needing row-level provenance |
| 70 Site/** | D | legacy site/design package | INDEXED | NO | evaluated only after truth; cannot validate itself |
| 99 Архив/_QUARANTINE_2026-09-27/** | E | superseded lineage | INDEXED | NO | v0.2 OS and older semantic model quarantined |
