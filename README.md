easyflot
========

Utilitários desenvolvidos em cima da biblioteca FlotCharts <http://www.flotcharts.org/>

Os gráficos podem ser criados com listas de valores separados da seguinte forma:

var ef = new EasyFlot([1,2,3,4,5], [1,2,3,2,1], "#placeholder");

Também é possível fornecer apenas os valores do eixo Y:

var ef = new EasyFlot(null, [1,2,3,2,1], "#placeholder");

Ou com o pares de pontos:

var ef = new EasyFlot( [(1,1),(2,2),(3,3),(4,2),(5,1)], null, "#placeholder");

Novas séries podem ser adicionadas através do método addplot:

ef.addplot([1,2,3,4,5], [2,1,3,4,1]);

Opções do gráfico podem ser especificadas por parametros nomeados na criação do gráfico:

var ef = new EasyFlot([1,2,3,4,5], [1,2,3,2,1], "#placeholder", {});


