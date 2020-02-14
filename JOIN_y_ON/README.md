<h1><b>Operador JOIN</b></h1>
Este operador permite combinar dos o más tablas en una base de datos. Hay distintos tipos de JOIN:<br/>
• <b>INNER JOIN</b>: Devuelven únicamente aquellos registros/filas que tienen valores idénticos en los dos campos que se comparan para unir ambas tablas.<br/>
• <b>OUTER JOIN</b>: Nos permite seleccionar algunas filas de una tabla aunque éstas no tengan correspondencia con las filas de la otra tabla.<br/>
• <b>LEFT JOIN</b>: Se obtienen todas las filas de la tabla colocada a la izquierda, aunque no tengan correspondencia en la tabla de la derecha.<br/>
• <b>RIGHT JOIN</b>:Se obtienen todas las filas de la tabla de la derecha, aunque no tengan correspondencia en la tabla de la izquierda.<br/>
• <b>FULL JOIN</b>: Se obtienen todas las filas en ambas tablas, aunque no tengan correspondencia en la otra tabla.<br/>
Se escribe así: FROM <i>tabla1</i> JOIN <i>tabla2</i> ON <i>tabla1.campo1</i>=<i>tabla2.campo1</i><br/>
<br/>
<br/>
<h1><b>Operador ON</b></h1>
Este operador se usa para enlazar dos tablas.<br/>
Se escrobe así. FROM <i>tabla1</i> JOIN <i>tabla2</i> ON <i>tabla1.campo1</i>=<i>tabla2.campo1</i>; <b>(Siempre y cuando sean los mismo el campo 1 de una tabla y otra)</b><br/>
