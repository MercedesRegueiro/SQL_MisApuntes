<h1><b>Operador ORDER BY</b></h1>
Este operador se encarga de ordenar de manera ascendiente o descendiente los resultados de una columna especifica. ASC ordena de menor a mayor y DESC de mayor a menor.<br/>
Se escribe así: ORDER BY <i>campo</i> ASC (Se puede poner ASC o DESC o nada de esta forma sera de forma predeterminada)<br/>
<br/>
Ejemplo:<br/>
SELECT campo1, campo2<br/>
FROM tabla1<br/>
ORDER BY campo2 ASC;
<br/>
<br/>
<h1><b>Operador SELECT dentro de un WHERE</b></h1>
Este operador se usa para poder comparador los datos de una tabla con una en concreto de la misma tabla.<br/>
Se escribe igual que la estructura basica pero detro del where.<br/>
<br/>
Ejemplo:<br/>
SELECT campo1, campo2<br/>
FROM tabla1<br/>
WHERE campo2=(<br/>
SELECT campo2<br/>
FROM tabla1<br/>
WHERE campo1= ‘valor1’<br/>
)
