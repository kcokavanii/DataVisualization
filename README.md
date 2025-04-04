# Pandas, SQL and Data Visualization


### Инструкции

* База данных и файл с данными расположены в подпапке src/data/

### Ex00 : Line chart

Директория : ex00/

Посмотрим как часто посещаются страницы в определенное время.


### Ex01 : Line chart with styles

Директория : ex01/

Используемые библиотеки: pandas, sqlite3

Посмотрим некоторые закономерности между коммитами и просмотрами. Нарисуем оба показателя во времени на одном графике.


### Ex02 : Bar

Директория : ex02/

Используемые библиотеки: pandas, sqlite3

Посмотрим, когда пользователи обычно коммитят лабораторные: ночью, утром, днем или вечером, как это изменяется с течением времени.


### Exercise 03 : Bar charts

Директория : ex03/

Используемые библиотеки: pandas, sqlite3

Посмотрим различия между средним количеством коммитов в будние и выходные дни, построим график и наглядно сравним.


### Exercise 04 : Histogram

Директория : ex04/

Используемые библиотеки: pandas, sqlite3, matplotlib.pyplot

Сравним не средние значения, а абсолютное число коммитов в выходные и будние дни.


### Exercise 05 : Boxplot

Директория : ex05/

Используемые библиотеки: pandas, sqlite3, matplotlib.pyplot

Построим боксплот.

### Exercise 06 : Scatter Matrix

Директория : ex06/

Используемые библиотеки: pandas, sqlite3, from pandas.plotting import scatter_matrix

Посмотрим с помощью графика есть ли линейная связь между переменными. 

### Exercise 07 : Heatmap

Директория : ex07/

Используемые библиотеки: pandas, sqlite3, matplotlib.pyplot, from mpl_toolkits.axes_grid1 import make_axes_locatable

Выясним, существуют ли различные закономерности для пользователей между разными днями и между различными часами.

### Exercise 08 : Seaborn

Директория : ex08/

Используемые библиотеки: pandas, sqlite3, matplotlib.pyplot, seaborn

В предыдущих упражнениях игнорировался project_1, так как проект был соревнованием и имел более длительные сроки и намного больше обязательств, чем обычные лабораторные. Теперь посмотрим на динамику коммитов в этом проекте для каждого пользователя. На этот раз используем другую библиотеку для визуализации данных в Python - Seaborn.
