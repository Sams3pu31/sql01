1) Какое ключевое слово используется для сортировки строк в таблице?

Для сортировки строк в таблице используется ключевое слово ORDER BY.

2) Как PostgreSQL сортирует строки по умолчанию?

PostgreSQL сортирует строки по возрастанию по умолчанию.

3) Как можно указать направление сортировки по убыванию?

Для указания направления сортировки по убыванию используется ключевое слово DESC после поля сортировки в выражении ORDER BY.

4) Как должно высчитываться значение для OFFSET, если мы хотим выводить строки в таблице по страницам?

Значение для OFFSET вычисляется как количество строк на странице умноженное на номер страницы минус один.

5) Как можно посчитать количество строк в таблице?

Для подсчета количества строк в таблице используется запрос: SELECT COUNT(*) FROM table_name;

6) Как найти максимальное значение в столбце?

Для нахождения максимального значения в столбце используется запрос: SELECT MAX(column_name) FROM table_name;

7) Как найти минимальное значение в столбце?

Для нахождения минимального значения в столбце используется запрос: SELECT MIN(column_name) FROM table_name;

8) Как найти среднее значение в столбце?

Для нахождения среднего значения в столбце используется запрос: SELECT AVG(column_name) FROM table_name;

9) Как найти сумму значений в столбце?

Для нахождения суммы значений в столбце используется запрос: SELECT SUM(column_name) FROM table_name;

10) Какие типы объединений вы знаете?

Существует четыре типа объединений: INNER JOIN, LEFT JOIN (или LEFT OUTER JOIN), RIGHT JOIN (или RIGHT OUTER JOIN), и FULL JOIN (или FULL OUTER JOIN).

11) Как вывести строки из двух таблиц, для которых существует связь?

Для этого используется INNER JOIN. Пример: SELECT * FROM table1 INNER JOIN table2 ON table1.column_name = table2.column_name;

12) Как вывести строки из двух таблиц, для которых существует связь, и все оставшиеся строки из таблицы 1?

Используется LEFT JOIN. Пример: SELECT * FROM table1 LEFT JOIN table2 ON table1.column_name = table2.column_name;

13) Как вывести строки из двух таблиц, для которых существует связь, и все оставшиеся строки из таблицы 2?

Используется RIGHT JOIN. Пример: SELECT * FROM table1 RIGHT JOIN table2 ON table1.column_name = table2.column_name;

14) Как вывести строки из двух таблиц, для которых существует связь, и все оставшиеся строки из таблиц 1 и 2?

Используется FULL JOIN. Пример: SELECT * FROM table1 FULL JOIN table2 ON table1.column_name = table2.column_name;

15) Для каких задач нужен subselect?

Subselect используется, когда необходимо выполнить вложенный запрос внутри основного запроса. Это может быть полезно, например, для подсчета значений, фильтрации данных и других операций внутри запроса.

16) Как составить запрос с группировкой данных?

Запрос с группировкой данных выглядит так: SELECT column_name, COUNT(*) FROM table_name GROUP BY column_name;

17) Для чего используется ключевое слово HAVING?

Ключевое слово HAVING используется для фильтрации результатов запроса с группировкой данных. Он позволяет применять условия к результатам группировки.
