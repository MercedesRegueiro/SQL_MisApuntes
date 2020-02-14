<h1><b>Operador IN</b></h1>
Este operador devuelve aquellos registros que coincida con la lista que hayamos puesto en IN.<br/>
Se escribe así: <i>expresión</i> [NOT] IN(<i>valor1, valor2, . . .</i>)<br/>
<b>La condición Not es opcional. Si se utiliza el NOT aparecerá todos los valores que no esten en la lista.</b><br/>
<br/>
Ejemplo:<br/>
SELECT campo1, campo2, campo3, campo4<br/>
FROM tabla1<br/>
WHERE campo1 IN (valor1, valor2, valor3);
<br/>
<br/>
<h1><b>Operador BETWEEN</b></h1><br/>
Este operador devuelve aquellos registros que esten entre los valores que hayamos puesto en BETWEEN.<br/>
Se escribe así: <i>campo</i> [NOT] BETWEEN <i>valor1</i> AND <i>valor2</i><br/>
<br/>
Ejemplo:<br/>
SELECT campo1, campo2, campo3, campo4<br/>
FROM tabla1<br/>
WHERE campo1 BETWEEN valor3 AND valor5;
