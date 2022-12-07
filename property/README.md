# Data-Analytics-Projects

**Название проекта:** Исследование объявлений о продаже квартир

**Статус проекта:** завершенный

**Цель проекта:** установить параметры, влияющие на рыночную стоимость объектов недвижимости.

**Задачи проекта:**
1. Осуществить предобработку данных
2. Добавить расчетные показатели, необходимые для анализа
3. Оценить скорость продажи недвижимости;
4. Проанализировать факторы, влияющие на стоимость квартиры;
5. Выделить населенные пункты с наибольшей и наименьшей ценой квадратного метра.

**Описание данных:**
В качестве исходных данных выступает архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Часть данных была заполнена пользователем, часть - формируется автоматически на основе картографических данных.

**Показатели:**
- airports_nearest — расстояние до ближайшего аэропорта в метрах;
- balcony — число балконов;
- ceiling_height — высота потолков;
- cityCenters_nearest — расстояние до центра города;
- days_exposition — сколько дней было размещено объявление;
- first_day_exposition — дата публикации;
- floor — этаж;
- floors_total — всего этажей в доме;
- is_apartment — апартаменты (булев тип);
- kitchen_area — площадь кухни в квадратных метрах;
- last_price — цена на момент снятия с публикации;
- living_area — жилая площадь в квадратных метрах;
- locality_name — название населённого пункта;
- open_plan — свободная планировка (булев тип);
- parks_around3000 — число парков в радиусе 3 км;
- parks_nearest — расстояние до ближайшего парка;
- ponds_around3000 — число водоёмов в радиусе 3 км;
- ponds_nearest — расстояние до ближайшего водоёма;
- rooms — число комнат;
- studio — квартира-студия (булев тип);
- total_area — общая площадь квартиры в квадратных метрах;)
- total_images — число фотографий квартиры в объявлении.

**Выводы:**

***В результате предобработки были выявлены следующие особенности данных:***

1. В данных имелись пропуски, которые могли возникнуть в результате целенаправленного или случайного не заполнения сведений продавцом, а также ввиду ошибки в системе, предоставляющей картографические сведения (по большинству населенных пунктов информация не была предоставлена).


2. По отдельным показателям имелись аномальные значения, которые могли возникнуть либо из-за ошибки пользователя при введении данных, либо ввиду продажи действительно нестандартных объектов недвижимости.


3. Отсутствовало единообразие в указании названий населенных пунктов. При доработке системы данный раздел можно было бы унифицировать.


***В результате исследовательского анализа были сделаны следующие выводы:***

1. В изучаемом периоде в Санкт-Петербурге и Ленинградской области чаще всего пользователи продавали квартиры со стандартными характеристиками:
- 1 или 2 комнаты;
- общая площадь 30-60 м², жилая площадь 16-20 м² или 30-40 м²;
- высота потолка 2,55 м или 2,7 м;
- размер кухни 8-10 м²;
- расположенные в 5- или 9-этажных домах;
- с наличием парка в радиусе 1 км;
- удаленные от центра города на расстоянии 8-20 км и 15-35 км от аэропорта;
- в ценовом диапазоне 3-5 млн рублей.


2. Наибольшая активность по размещению объявлений о продаже объектов недвижимости зафиксирована в феврале-марте, в будние дни. Скорее всего, это может быть связано с рабочими днями агентств недвижимости.


3. 75% квартир в Санкт-Петербурге и Ленинградской области продавались в первые полгода после размещения объявления. В среднем для того, чтобы найти покупателя, требовалось до 83 дней.


4. Наибольшее количество объявлений приходится на город Санкт-Петербург. В этом городе зафиксирована самая высокая средняя цена одного квадратного метра жилья, составившая в изучаемом периоде 108,2 тысячи рублей. Вторая по величине цена квадратного метра зафиксирована в городе Пушкин (101,9 тысяч рублей за квадратный метр). Среди населенных пунктов с наибольшим числом объявлений самая низкая цена квадратного метра в городе Выборг - 57,9 тысяч рублей.


5. Наибольшее прямое влияние на стоимость объекта оказывают общая площадь, жилая площадь, площадь кухни. Связь стоимости объекта с количеством комнат прямая, средней силы. Этаж расположения объекта также оказывает влияние: среди дорогостоящих объектов гораздо реже встречаются квартиры на первом этаже.


6. Между ценой квадратного метра и удаленностью от центра города существует нелинейная зависимость: цена квадратного метра жилья увеличивается до 6 км, далее при увеличении удаленности от центра города цена снижается.
