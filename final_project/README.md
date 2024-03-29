# Анализ и сегментация клиентов «Метанпромбанка» по потреблению

 **Задача проекта:**
 
 
 Ранее в банке было проведено исследование оттока, составлены дэшборды и выделены сегменты, но клиентская база поменялась и текущие решения не работают. Необходимо выявить признаки потребления наиболее отточных клиентов и сегментировать клиентскую базу.
 
 **Инструменты:** 


Python, Pandas, Plotly, SciPy, проверка статистических гипотез.

 **Результаты работы:** 
- Изучена общая информация об имеющихся данных.
- Проведена проверка и подготовка данных.
- Проведен исследовательский анализ данных.
- Осуществлена постановка и проверка статистических гипотез.
- Составлены промежуточные итоги для сегментации клиентов.
- Проведена сегментация клиентов на основе выделенных показателей.
- Подготовлена презентация.

**Вывод:**


**В сегмент A входят:** 544 клиента, средний возраст 43 года, большинство - мужчины из Ярославля, в большинстве не имеют кредитной карты, медианное значенние остатка на балансе 986723, используют 3 продукта и имеют 5 объектов в собственности.

**В сегмент B входят:** 820 клиентов, средний возраст 45 лет, большинство - женщины из Ярославля, не имеют кредитной карты, медианное значенние остатка на балансе 741203, используют 3 продукта и имеют 4 объекта в собственности.

**В сегмент C входят:** 901 клиент, средний возраст 44 года, большинство - женщины из Ярославля, не имеют кредитной карты, медианное значенние остатка на балансе 931691, используют 2 продукта и имеют 5 объектов в собственности.

Все 3 выделенных сегмента значительно более склонны к оттоку, чем средний клиент банка. Наибольшее значение оттока у сегмента A, где он составляет 48.7%, что на 30 п.п выше, чем в среднем по банку. Затем следует сегмент C, где доля оттока занимает 38.8%, и сегмент B c оттоком на уровне 32.3%.

**Рекомендации для сегмента A:**

Чтобы остановить отток клиентов, отделу маркетинга «Метанпромбанка», в первую очередь, стоит обратить внимание на потребности клиентов из сегмента A. Поскольку была выявлена связь между оттоком и количеством продуктов, стоит оценить действительно ли клиентам нужно так много продуктов, каковы условия обслуживания и удовлетворяют ли они все потребности клиента. Судя по медианному значению остатка на балансе клиентам могут быть интересны банковские вклады на выгодных условиях - это позволит удержать данных клиентов на большее время.

**Рекомендации для сегмента B:**

Поскольку в данный сегмент входят женщины со средним доходом, у которых нет кредитной карты - возможно стоит попробовать повысить активность данных клиентов, предложив кредитные карты с кешбэком в виде бонусов за покупки.

**Рекомендации для сегмента C:**

У сегментов данного сегмента более 4 объектов собственности и нет кредитной карты. Вероятно, клиент заинтересован в приобретении объектов недвижимости - можно предложить выгодные программы ипотечного кредитования.

