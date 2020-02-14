<h1>Operador LIKE</h1>
Este operador devuelve aquellos registros que coincidan con un modelo de expresión de SQL<br/>
Se escribe así: <i>campo</i> LIKE <i>modelo</i><br/>
<br/>
Ejemplo:<br/>
SELECT campo1, campo2<br/>
FROM tabla1<br/>
WHERE campo1 LIKE ‘%#’; <b>(Termina con un digito)</b>
<br/>
<h3>Patrones para LIKE</h3>

<br/>
<br/>
<h1>Operador CONCAT</h1>
Este operador combina o junta dos o más cadenas.<br/>
Se escribe así: CONCAT (<i>valor1, valor2</i>[<i>,valorN</i>])<br/>
<br/>
Ejemplo:<br/>
SELECT campo1, campo3<br/>
FROM tabla 1<br/>
WHERE campo3 = CONCAT (campo1, ‘ es un’, ‘ ejemplo’);
<br/>
<br/>
<h1>Operador AS</h1>
Este operador renombra el campo.<br/>
Se escribe así: AS <i>‘nuevoNombre’</i><br/>
<br/>
Ejemplo:<br/>
SELECT campo2, campo1 AS ‘ejemplo’<br/>
FROM tabla1<br/>
WHERE campo1 LIKE ‘%’;
