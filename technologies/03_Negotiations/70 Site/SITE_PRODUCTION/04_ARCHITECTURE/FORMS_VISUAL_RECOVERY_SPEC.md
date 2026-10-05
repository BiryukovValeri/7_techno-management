# FORMS VISUAL RECOVERY SPEC — FORMS 17–23
Status: SOURCE-RECOVERED / LOCK FOR FINAL CORRECTION
Date: 2026-10-05

## Principle
The site must SHOW the real working instruments, not only name them. These previews are Tool Previews, not decorative Image Slots and not Technology Visualizations.

Source: actual XLSX templates from the Negotiations documentation corpus. Public preview must preserve real column/field structure while removing confidential/example client data. Do not redraw into fake SaaS dashboards.

## Shared presentation pattern
For each Form:
- left/upper: legible crop/reconstruction of the actual XLSX structure;
- right/lower: Для чего / Что заполняется / Какое решение помогает принять / Где в цикле;
- one sentence: Что ломается без этой формы;
- label: «Фрагмент рабочего инструмента»;
- no download unless separately approved.

Desktop: tool preview and explanation side-by-side where width permits.
Tablet/Mobile: preview first, explanation second; horizontal table must not be shrunk to illegibility—use a faithful responsive reconstruction of the selected fields.

## TP-17 — Чек-лист подготовки
Source XLSX: Шаблон_17_Чек_лист_подготовки.
Public crop: header + columns Этап подготовки / Что проверить / Статус / Приоритет / Ответственный / Срок / Риск если не выполнено / Комментарий-доказательство and 5–7 representative rows.
Prefer rows demonstrating: цель; жёсткие/гибкие параметры; BATNA/ZOPA; сценарии; уступки; роли; финальная проверка.
Function: determines whether the team is actually ready to enter the next round.
Decision supported: proceed / complete preparation / request evidence / pause.
Cycle: primarily Step 1 and readiness across the cycle.
Without it: preparation is declared verbally without an auditable readiness trace.

## TP-18 — Карта целей, BATNA и ZOPA
Actual XLSX has four meaningful blocks; public preview should make that visible.
18.1 Goals/thresholds: Основная цель / Жёсткие параметры / Гибкие параметры / Минимально приемлемый результат / Идеальный результат / Механизм остановки / Критерии успеха.
18.2 BATNA: Альтернатива / Что даёт / Доступность / Ценность / Затраты / Риск / Срок запуска / Итоговый балл / Решение.
18.3 ZOPA: Параметр / Наша нижняя граница / Наша цель / Наша верхняя граница / Прогноз границ контрагента / Возможная зона соглашения / Красная линия.
18.4 Summary: Цели / BATNA / ZOPA / Защита позиции / Расширение диапазона / Переход к альтернативам / Решение руководителя.
Function: separates desired outcome, exit alternative and possible agreement range.
Decision supported: go / strengthen BATNA / clarify ZOPA / change scenario / stop.
Cycle: Steps 2, 5, 6 and supports 7/9.
Without it: the team can confuse “we want this” with “we should accept this”.

## TP-19 — Профиль участника и карта влияния
Source XLSX: Шаблон_19_Профиль_контрагента_и_карта_влияния.
Public crop: Контур / Ситуация / Сторона-участник / Роль / Формальная позиция / Предполагаемые цели / Интересы-критерии / Ограничения / Полномочия / влияние / статус факта-гипотезы.
Function: maps the decision system rather than psychologically profiling people.
Decision supported: whom to involve, what must be verified, where authority/influence actually sits.
Cycle: Steps 3–4.
Without it: the company negotiates with visible speakers while missing actual decision influence.

## TP-20 — Сценарии и ролевая карта команды
Source XLSX: Шаблон_20_Сценарии_и_ролевая_карта_команды.
Public crop: сценарий / следующий шаг / роль / владелец решения / право на паузу / кто говорит / кто фиксирует / условие переключения сценария, using exact available source fields.
Function: converts position into an executable round plan.
Decision supported: who does what and when the team changes/pauses the scenario.
Cycle: Steps 4, 7, 9.
Without it: even an agreed position fragments at the table.

## TP-21 — Матрица уступок и встречных шагов
Source XLSX: Шаблон_21_Матрица_уступок_и_встречных_шагов.
Public crop: Запрошенная уступка / Цена-влияние / Условие / Встречный шаг / Порядок раскрытия / Полномочие / решение, using exact available source fields.
Function: turns concession from loss into controlled exchange.
Decision supported: concede / exchange / package / refuse / escalate for authority.
Cycle: Steps 5–7 and 9.
Without it: concessions accumulate independently and their total price becomes invisible.

## TP-22 — Карта когнитивных рисков решения
Source XLSX: Шаблон_22_Карта_когнитивных_рисков_решения.
Public crop: actual source fields covering якорь / страх потерь / групповое мышление / давление срока / инерция / неполные данные / проверка / пауза / владелец проверки where present.
Function: checks quality of the management decision, not personality.
Decision supported: continue / verify / pause / reframe.
Cycle: Step 8 and supports Step 9.
Without it: a formally rational package may be accepted under decision distortion.

## TP-23 — Постпереговорный отчёт, показатели и журнал улучшений
Source XLSX: Шаблон_23_Пост_переговорный_отчет_показатели_и_журнал_улучшений.
Public preview should show three fragments:
1. План/факт и показатели — a short selected set, not the entire indicator bank.
2. Журнал улучшений PDCA — Наблюдение/проблема / Причина / Действие / Что обновить в Forms 17–22 / Ответственный / Срок / Критерий проверки / Статус.
3. Решение о следующем цикле — Итог / Главное отклонение / Что изменить / Решение по циклу / Что нельзя делать до обновления / Владелец следующего шага.
Function: converts one round into evidence for the next.
Decision supported: close / continue / strengthen preparation / rebuild conditions / align internally / strengthen BATNA / exit.
Cycle: Step 10.
Without it: the organization repeats negotiations but does not accumulate negotiation capability.

## Placement
- /tools/: all 7 Tool Previews, primary location.
- /technology/: TP-18 once in BATNA/ZOPA block; TP-21 in concessions block.
- Product pages: compact “used forms” references linking to /tools/, not full duplicates.
- Cases: forms trace as text/chips; no spreadsheet screenshot overload.

## Visual integrity
Preserve Warm Paper / Deep Navy / Copper / Muted Teal around the preview. Spreadsheet itself should look like a real working document, not glossy SaaS UI. Sensitive/example-specific values blank/neutral. No fabricated numbers. Do not expose internal source-line references publicly.
