# Определение закономерности успешных игр для интернет-магазина
## Описание проекта.
### Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.
### В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».
## Подготовил данные
- Заменил названия столбцов (привел к нижнему регистру);
- Преобразовал данные в нужные типы. Описал, в каких столбцах заменили тип данных и почему;
- Обработал пропуски при необходимости:
  - Объяснил, почему заполнил пропуски определённым образом или почему не стал это делать;
  - Описал причины, которые могли привести к пропускам;
  - Обратил внимание на аббревиатуру 'tbd' в столбцах с рейтингом. Отдельно разобрал это значение и описал, как его обработать;
- Посчитал суммарные продажи во всех регионах и записал их в отдельный столбец.
## Провел исследовательский анализ данных
- Посмотрел, сколько игр выпускалось в разные годы.
- Посмотрел, как менялись продажи по платформам. Выберал платформы с наибольшими суммарными продажами и построил распределение по годам.
- Взял данные за соответствующий актуальный период. Актуальный период определил самостоятельно в результате исследования предыдущих вопросов.
- Выберите несколько потенциально прибыльных платформ.
- Построил график «ящик с усами» по глобальным продажам каждой игры и разбивкой по платформам.
- Посмотрел, как влияют на продажи внутри одной популярной платформы отзывы пользователей и критиков. Построил диаграмму ра
- Соотнесите выводы с продажами игр на других платформах.ссеяния и посчитал корреляцию между отзывами и продажами.
- Посмотрел на общее распределение игр по жанрам.
## Проверил гипотезы
- Средние пользовательские рейтинги платформ Xbox One и PC одинаковые;
- Средние пользовательские рейтинги жанров Action (англ. «действие») и Sports (англ. «виды спорта») разные.
## Библиотеки:
1. pandas
2. matplotlib.pyplot
3. scipy
4. numpy
