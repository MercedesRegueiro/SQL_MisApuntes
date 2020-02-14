<h1><b>Operador ROUND</b></h1>
Este operador se utiliza para redondear un número a unos decimales.<br/>
Se escribe así: ROUND(<i>numero,nº de decimales</i>)<br/>
<br/>
Ejemplo:<br/>
SELECT campo1,,ROUND(campo2, 1) AS ‘Redondeo’<br/>
FROM tabla1<br/>
WHERE campo2>50;
<br/>
<br/>
<h1><b>Operador LENGTH</b></h1>
Este operador devuelve la longitud de una cadena.<br/>
Se escribe así: LENGTH(<i>cadena</i>)<br/>
<br/>
Ejemplo:<br/>
SELECT campo1, LENGTH(campo1) AS ‘Longitud’<br/>
FROM tabla1<br/>
WHERE campo2=25;
<br/>
<br/>
<h1><b>Operador LEFT</b></h1>
Este operador permite sacar n caracteres hacia la izquiera de una cadena.<br/>
Se escribe así: LEFT(<i>cadena, n.º de caracteres</i>)<br/>
<br/>
Ejemplo:<br/>
SELECT campo1, LEFT (campo1, 4) AS ‘Left’<br/>
FROM tabla1<br/>
WHERE campo2=25;
