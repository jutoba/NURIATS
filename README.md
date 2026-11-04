# NURIATS

Reparto automático de horas del CATS para todo el equipo, por quincenas.

- Jornada: 9 h de lunes a jueves, 7 h los viernes; fines de semana y festivos, 0.
- Prioridad: proyectos propios (externo → interno → promoción), luego proyectos de otros.
- Cada proyecto tiene un tope mensual en € y un WOFF (% de descuento). El WOFF se aplica a cada hora: coste = horas × fee × (1 − WOFF), y la suma de todo el equipo no puede pasar del tope. Ej.: 22,5 h × 187 × 0,24 + 163 h × 149 × 0,24 = 6.838,68 € ≤ 6.850 €.
- Calculadora para probar cuántas horas caben en un proyecto sin pasarse.
- Cada hoja se puede editar a mano; avisa por quincena si te pasas o te faltan horas respecto a las horas estándar, y si un proyecto se pasa de tope.
- Genera la hoja de cada persona día a día y permite copiar las filas para pegarlas en el CATS.

Es una página estática: abre `index.html` en el navegador o publícala con GitHub Pages. Los datos se guardan en el navegador (localStorage) y se pueden exportar/importar como texto.
