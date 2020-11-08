# Исследование надежности заемщиков

Для этого проекта были использованы: 
- Python;
- Pandas;
- предобработка данных;
- лемматизация средствами PyMystem3.

Проведено исследование влияния семейного положения заемщика и количества его детей на факт возврата кредита в срок на основании статистики о платежеспособности клиентов за предыдуший период

В ходе исследования определены и обработаны пропуски, заменены типы данных на соответствующие хранящимся данным, проверено наличие дубликатов. Затем были выделены леммы в значениях столбца с целями кредита, данные были категоризированы по целям, а в последствии выявлены зависимости возврата кредита в срок от семейного положения и количества детей.

В 8.83% случаев кредит не возвращался вовремя

Заемщики, не имеющие детей более надежны в отношении погашения платежа по кредиту в срок почти на 1% по сравнению с общим количеством должников. С появлением первого и второго ребенка надежность снижается. А в многодетных семьях надежность заемщиков уменьшается на 2% по отношению к среднему уровню надежности.

Надежными плательщиками кредитов являются вдовцы и вдовы, среди них должников почти на 2% меньше, чем в среднем, а незамужние и неженатые должники на 2% превышают средний процент должников.

Заемщики со средними доходами чаще остальных имеют задолженность по кредитам, а люди с доходами выше среднего выплачивают займы стабильнее.
