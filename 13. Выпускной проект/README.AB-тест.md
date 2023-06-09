**A/B-тест**

**Описание проекта:**
Провести оценку результатов A/B-теста. В вашем распоряжении есть датасет с действиями пользователей, техническое задание и несколько вспомогательных датасетов.

**Задачи проекта:**
Выявить недостатки проведенного A/B-теста и подготовить рекомендации для корректного проведения A/B-тестов в будущем.

**Выводы:**
В ходе сопоставления данных с ТЗ был выявлен ряд проблем:
1. Утеря части данных (дата окончания теста - 4 января 2021 года, у нас есть данные только до конца 2020 года).
2. Присутствует пересечение с конкурирующим тестом (есть пользователи, участвующие в двух группах теста одновременно, т.е. один тест может влиять на результаты другого).
3. Участники теста распределены по группам неравномерно (как и количество событий на пользователя), что так же может исказить результаты исследования.

Ожидаемый эффект: за 14 дней с момента регистрации пользователи покажут улучшение каждой метрики не менее, чем на 10% - не достигнут. Тест признать неуспешным.

В будущем, при проведении тестов необходимо, чтобы данные четко соответствовали ТЗ и исследование проводилось более изолированно, чтобы исключить различные нежелательные явления.

**Сферы деятельности:** интернет-сервисы.

**Стек, навыки:** Python, Pandas, Matplotlib, SciPy, A/B-тестирование, проверка статистических гипотез.

