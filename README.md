# Ant
Муравьиный алгоритм для задачи коммивояжера Решение задачи коммивояжера муравьиным алгоритмом.

Решение представляет собой цикл итераций или "поколений" муравьейника, со вложенными в него циклами обхода муравьями графа с определением длины маршрута и нахождением лучшего маршрута и цикла распределения феромона маршрутах (дугах графа) по которым прошли муравьи для реализации положительной обратной связи между муравьями с предварительным высыханием этого феромона для реализации отрицательной обратной связи.

В решении присутствует эффект высыхания феромона. В решении не используются "элитные" муравьи, хотя блок кода присутствует и закомментирован. Возможны три варианта начального расположения муравьев в графе. Используется равномерное расположение, но случайное и "все-из-одного" присутствуют в коде и закомментированы. В решении используется глобальное распределение феромона (после прохождения всех муравьев). Присутствует эффект локального распределения феромона (после прохождения каждого муравья) в коде, но он закомментирован. Есть возможность вывода графика зависимости полученного решения от числа итераций, присутствует в коде и закомментировано.
