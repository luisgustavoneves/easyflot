easyflot
========

Utilitários desenvolvidos em cima da biblioteca FlotCharts <http://www.flotcharts.org/>

Um novo gráfico é criado a partir da EasyFlot da seguinte forma:

ef = new EasyFlot("#placeholder", {});

Opções relacionadas ao gráfico, como as da grid podem ser passadas nesse comando:

ef = new EasyFlot("#placeholder", {grid: {backgroundColor: color/gradient or null});

Novas séries podem ser adicionadas através do método addplot. 
Os gráficos podem ser criados com listas de valores separados:

ef.addplot([1,2,3,4,5], [1,2,3,2,1], {});

Também é possível fornecer apenas os valores do eixo Y:

ef.addplot(null, [1,2,3,2,1], {});

Ou pares de pontos:

ef.addplot([(1,1),(2,2),(3,3),(4,2),(5,1)], null, {});

Opções relacionadas às séries podem ser especificadas nesse comando:

var ef = new EasyFlot([1,2,3,4,5], [1,2,3,2,1], {symbol: "^"});


