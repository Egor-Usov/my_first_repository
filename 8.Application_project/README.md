# 8. Анализ бизнес показателей
## Описание проекта
Необходимо проанализировать расходы на рекламу и поведение пользователей за период с 2019-05-01 по 2019-10-27, чтобы выяснить по какой причине бизнес несет убытки.
## Задачи проекта
Нужно оценить:
- когда пользователь начинает покупать.
- сколько времени пользователь проводит в приложении.
- сколько денег в среднем приносит пользователь.
- эффективность рекламных кампаний (оценить конверсию и окупаемость).
## Описание данных
Таблица visits содержит:

- User Id — уникальный идентификатор пользователя,
- Region — страна пользователя,
- Device — тип устройства пользователя,
- Channel — идентификатор источника перехода,
- Session Start — дата и время начала сессии,
- Session End — дата и время окончания сессии.

Таблица orders содержит:
- User Id — уникальный идентификатор пользователя,
- Event Dt — дата и время покупки,
- Revenue — сумма заказа.

Таблица costs:
- Channel — идентификатор рекламного источника,
- Dt — дата проведения рекламной кампании,
- Costs — расходы на эту кампанию.