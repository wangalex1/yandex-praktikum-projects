# Аналитика в авиакомпании
## Описание проекта.
### Понять предпочтения пользователей, покупающих билеты на те или иные направления.
### Изучить базу данных и проанализировать спрос пассажиров на рейсы в города, где проходят крупнейшие фестивали.
## Написал парсер для сбора с сайта данных о 10 крупнейших фестивалях 2018 года
## Исследовательский анализ данных
- Нашел количество рейсов с вылетом в сентябре 2018 года на каждой модели самолёта.
- Посчитал количество рейсов по всем моделям самолетов Boeing и Airbus в сентябре. 
- Посчитал среднее количество прибывающих рейсов в день для каждого города за август 2018 года. 
## Проверил гипотезу, что количество рейсов во время фестивалей увеличивается
- Установил фестивали, которые проходили с 23 июля по 30 сентября 2018 года в Москве, и номер недели, в которую они проходили.
- Для каждой недели с 23 июля по 30 сентября 2018 года посчитал количество билетов, купленных на рейсы в Москву.
## Аналитика средствами Python
- изучил данные;
- проверил типы данных на корректность;
- выбрать топ-10 городов по количеству рейсов;
- построил графики: модели самолетов и количество рейсов, города и количество рейсов, топ-10 городов и количество рейсов;
- сделал выводы по каждому из графиков, пояснил результат.
## Проверка гипотезы средствами Python
### Средний спрос на билеты во время фестивалей не отличается от среднего спроса на билеты в обычное время
## Библиотеки
1. pandas
2. scipy
3. requests
