Векторизация текста и кластеризация слов

**Цель:** проанализировать роман М.А. Булгакова "Мастер и Маргарита", визуализировать векторное пространство слов, провести кластеризацию самых частотных слов.

**Вывод:**

Для наших целей более эффективным методом оказался метод PCA. После него лучше всего визуализировались вектора слов.

Мы видим, что модель хорошо захватывает семантические связи у наиболее часто встречающихся слов.

Например, близко располагаются слова:
- говорить, спросить, сказать, ответить;
- Пилат и прокуратор;
- голос и слово;
- глаз, голова, лицо;
- Маргарита, кот, Коровьев, Воланд.

По итогам использования разных комбинаций количества кластрев и количества слов, наиболее интересными показались:
- кластеризация 30 самых частотных слов на 2 кластера:
здесь действующие лица отделились от других слов;
- кластеризация 100 самых частотных слов на 3 кластера: здесь в кластеры выделились действующие лица (кластер 3), люди и предметы (кластер 1), преимущественно действия (кластер 2).