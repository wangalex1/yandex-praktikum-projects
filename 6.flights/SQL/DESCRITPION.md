# Описание SQL запросов
## query_1
### Модели  самолетов,на которых было совершено больше всего рейсов в сентябре 2018 года.
## query_2
### Количество рейсов по всем моделям самолетов Boeing и Airbus в сентябре.
## query_3
### Среднее количество прибывающих рейсов в день для каждого города за август 2018 года.
## query_4
### Фестивали, которые проходили с 23 июля по 30 сентября 2018 года в Москве, и номер недели, в которую они проходили.
## query_last
### Для каждой недели с 23 июля по 30 сентября 2018 года посчитал количество билетов, купленных на рейсы в Москву. Получил таблицу, в которой будет информация о количестве купленных за неделю билетов, отметка, проходил ли в эту неделю фестиваль, название фестиваля. 
# Описание данных
## База данных об авиаперевозках:
### Таблица airports — информация об аэропортах:
### airport_code — трёхбуквенный код аэропорта
### airport_name — название аэропорта
### city — город
### timezone — временная зона

## Таблица aircrafts — информация об самолётах:
### aircraft_code — код модели самолёта
### model — модель самолёта
## range — количество самолётов

## Таблица tickets — информация о билетах:
### ticket_no — уникальный номер билета
### passenger_id — персональный идентификатор пассажира
### passenger_name — имя и фамилия пассажира

## Таблица flights — информация о рейсах:
### flight_id — уникальный идентификатор рейса
### departure_airport — аэропорт вылета
### departure_time — дата и время вылета
### arrival_airport — аэропорт прилёта
### arrival_time — дата и время прилёта
### aircraft_code – id самолёта
