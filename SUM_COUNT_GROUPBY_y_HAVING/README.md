<h1><b>Operador SUM</b></h1>
Este operador permite obetener la suma total de una columna directa.<br/>
Se escribe así: SUM(<i>campo</i>)<br/>
<br/>
Ejemplo: SELECT SUM(campo2) AS Suma<br/>
FROM tabla1;
<br/>
<br/>
<h1><b>Operador COUNT</b></h1>
Este operador se utiliza para contar cuantas filas/ tuplas cumplen la condición.<br/>
Se escribe así: COUNT(<i>campo</i>)<br/>
<br/>
Ejemplo: SELECT COUNT (campo2)<br/>
FROM tabla1<br/>
WHERE campo2>=55;
<br/>
<br/>
<h1><b>Operador GROUP BY</h1></b>
Este operador se utiliza para agrupar las filas (cuando sumas o cuentas) según la columna<br/>
Se escribe así: GROUP BY <i>campo</i><br/>
<br/>
Ejemplo: SELECT COUNT(campo2), campo4<br/>
FROM tabla1<br/>
WHERE campo2>=12<br/>
GROUP BY campo4;
<br/>
<br/>
<h1><b>Operador HAVING</b></h1>
Este operador se utiliza para hacer una condición que necesita sumar (SUM) o contar (COUNT).<br/>
Se escribe así: HAVING COUNT (<i>campo</i>) > <i>???</i>;<br/>
<br/>
Ejemplo: SELECT campo4<br/>
FROM tabla1<br/>
WHERE campo4 = 'Ejemplo'<br/>
HAVING COUNT (campo4) >= 3;
