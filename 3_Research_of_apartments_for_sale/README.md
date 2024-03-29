# Исследование объявлений о продаже квартир

Цель проекта: научиться определять рыночную стоимость объектов недвижимости. Установить параметры, позволяющие построить автоматизированную систему, способную отследить аномалии и мошенническую деятельность.

Используемые библиотеки: pandas, plotly.

Ход работы: 

Шаг 1. Изучение общей информации.

Шаг 2. Предобработка данных.
- Определение, изучение и заполнение пропущенных значений.
- Замена типа данных.

Шаг 3. Расчёт дополнительных параметров.
- Расчет цены квадратного метра.
- Определение дня недели, месяца и года публикации объявления.
- Категоризация этажа квартиры.
- Определение соотношения жилой и общей площади, а также отношения площади кухни к общей.

Шаг 4. Исследовательский анализ данных.
- Изучение площади, цен, числа комнат, высоты потолков. Построение гистограмм для каждого параметра.
- Изучение времени продажи квартиры. Построение гистограмм. 
- Отсечение редких и выбивающихся значений. Описание обнаруженных особенностей
- Поиск и исследование факторов больше всего влияющих на стоимость квартиры. Изучение зависимости цены от площади, числа комнат, удалённости от центра. Изучение зависимости цены от этажа квартиры, от даты размещения: дня недели, месяца и года.
- Расчёт средней цены квадратного метра в 10 населённых пунктов с наибольшим числом объявлений. Определение населённых пунктов с самой высокой и низкой стоимостью жилья.
- Изучение информации о расстоянии до центра. Подсчёт средней цены для каждого километра. Построение графика зависимости цены от удалённости от центра.
- Анализ и изучение параметров квартир, расположенных в центре. Выделение факторов, которые влияют на стоимость квартир в центре.

Шаг 5. Общий вывод.

Результаты:
1. Данные предообработаны: выделены пропуски, заменены соответствующими значениями, данные приведены к нужным типам, выявлены аномалии и выбросы, заполены пропущенные значения.
2. Рассчитаны и категоризованы искомые параметры.
3. Изучены площади, цены, число комнат, высоты потолков. Визуализировано среднее количество, минимумы, максимумы, медиана и размах выборки. Описано распределение, дисперсия и стандартное отклонение.
4. Определены и визуализированы факторы в наибольшей степени влияющие на стоимость квартиры. Сделаны соответствующие выводы по проекту.






