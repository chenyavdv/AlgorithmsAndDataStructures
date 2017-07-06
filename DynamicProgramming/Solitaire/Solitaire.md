<h1>Пасьянс
<h4>Имя входного файла: input.txt
<h4>Имя выходного файла: output.txt
<h6>Как известно, одной из важнейших программ в составе любой операционной системы является пасьянс. В состав операционной системы OSX входит следующая разновидность пасьянса. Колода карт из N карт, пронумерованных от 1 до N. На столе имеется N ячеек, расположенных в один ряд. Все ячейки также пронумерованы от 1 до N. Каждая ячейка в начале игры содержит ровно одну карту. Необходимо сложить все карты в колоду на произвольной ячейке таким образом, чтобы внизу лежала карта N, на ней — карта с номером N − 1, а на самом верху колоды — карта с номером 1. Таким образом, вся колода карт окажется сложенной в одной ячейке, а все остальные ячейки будут пустыми. При раскладывании пасьянса разрешается только одна операция: можно перенести карту с номером M и лежащие на ней карты (если они имеются) на карту с номером M + 1. За каждую такую операцию переноса игроку начисляется штраф, равный расстоянию, на которое переносится стопка карт, т. е. разности в номерах мест ячеек. Вам необходимо определить минимальный суммарный штраф, который может быть получен при складывании пасьянса из заданной конфигурации.
<h3>Формат входного файла
<h6>В первой строке задаётся число N карт пасьянса (1 ≤ N ≤ 500). В следующей строке N чисел — номера карт, выложенных в ячейках, в начале игры. Карты задаются в порядке возрастания номеров ячеек, в которых они выложены.
<h3>Формат выходного файла
<h6>Выведите одно число — минимально возможную суммарную величину штрафа.
<h3>Примеры
<h4>input.txt
<h6>73
<h6>1 24 57 62 68 36 2 72 31 8 37 48 9 14 23 16 43 64 38 35 27 3 70 56 15 71 22 13 29 30 41 39 26 34 11 6 20 18 59 45 12 42 40 44 32 25 46 17 49 50 61 4 53 54 55 19 21 58 51 5 47 63 52 7 65 73 10 60 69 66 33 67 28
<h4>output.txt
<h6>880