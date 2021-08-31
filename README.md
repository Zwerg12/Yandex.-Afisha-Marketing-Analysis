### Исследование пользовательской статитистики Яндекс. Афиша

### Описание проекта:

Есть данные Яндекс.Афиши:

- лог сервера с данными о посещениях сайта Яндекс.Афиши,
- выгрузка всех заказов за этот период,
- статистика рекламных расходов.

Предстоит изучить:
- как клиенты пользуются сервисом,
- когда делают первые покупки на сайте,
- сколько денег приносит компании каждый клиент,
- когда расходы на привлечение клиента окупаются

### Цель проекта:

- снизить расходы — отказаться от невыгодных источников трафика и перераспределить бюджет

Для этого рассчитать:

- DAU, WAU и MAU;
- Определить, сколько раз за день пользователи в среднем заходят на сайт;
- Исследовать, сколько времени пользователи проводят на сайте. Узнать продолжительность типичной пользовательской сессии за весь период;
- Рассчитать Retention Rate, применяя когортный анализ;
- 
Изучить метрики электронной коммерции:

- Исследовать, сколько времени в среднем проходит с момента первого посещения сайта до совершения покупки;
- Рассчитать средний чек, применяя группировку по времени совершения покупки;
- Выяснить, как меняется LTV на покупателя по когортам;

Изучить маркетинговые метрики:

- Посчитать и отобразить на графиках, как маркетинговые метрики различаются по рекламным источникам.
- Посчитать общую сумму расходов на маркетинг. Выяснить, как траты распределены по источникам. Визуализировать изменения метрик во времени;
- Рассчитать средний CAC на одного покупателя для всего проекта и для каждого источника трафика;
- Рассчитайте ROMI по когортам в разрезе источников. Сравните окупаемость за одинаковые периоды жизни когорт.

### Описание данных

Есть 3 источника данных:

1. лог сервера с информацией о посещениях сайта; 
2. информациz о заказах;
3. информация о расходах на маркетинг.

### Структура логf сервера с информацией о посещениях сайта:

— уникальный идентификатор пользователя,
— категория устройства пользователя,
— дата и время начала сессии,
— дата и время окончания сессии,
— идентификатор источника перехода на сайт.

### Структура данных о заказах:

— уникальный идентификатор пользователя,
— дата и время заказа,
— сумма заказа.

### Структура данных о расходах на маркетинг:

— идентификатор рекламного источника,
— дата проведения рекламной кампании,
— расходы на эту кампанию.
