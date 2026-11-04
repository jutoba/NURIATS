# NURIATS

Reparto automático de horas del CATS para todo el equipo, por quincenas.

- Jornada: 9 h de lunes a jueves, 7 h los viernes; fines de semana y festivos, 0.
- Prioridad: proyectos propios (externo → interno → promoción), luego proyectos de otros.
- Cada proyecto tiene un tope mensual en € y un WOFF (% de descuento sobre el fee). Horas = tope ÷ (fee × (1 − WOFF)); p. ej. 6.850 € con WOFF 76 % y fee 187 € → 152,6 h. El tope se comparte entre quienes cargan en el proyecto.
- Cada hoja se puede editar a mano; avisa por quincena si te pasas o te faltan horas respecto a las horas estándar, y si un proyecto se pasa de tope.
- Genera la hoja de cada persona día a día y permite copiar las filas para pegarlas en el CATS.

Es una página estática: abre `index.html` en el navegador o publícala con GitHub Pages. Los datos se guardan en el navegador (localStorage) y se pueden exportar/importar como texto.
