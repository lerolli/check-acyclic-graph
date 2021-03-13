# Определить, является ли данный граф ацикличным.

Метод решения: Поиск в глубину.
Файл исходных данных :
Граф, заданный матрицей смежности.
N - количество вершин в графе.
Далее построчно расположена матрица смежности размерности N x N.
Пример. Для графа
1 ---- 2      4
|      |      |
+----- 3 -----+

файл данных должен быть следующим:
4
0 1 1 0
1 0 1 0
1 1 0 1
0 0 1 0
Файл результатов :
Если граф ацикличен, то в файл результатов необходимо записать
"A"(латинское), иначе "N" и далее вершины входящие в первый найденный
цикл. Вершины в цикле должны быть упорядочены по возрастанию номеров.
