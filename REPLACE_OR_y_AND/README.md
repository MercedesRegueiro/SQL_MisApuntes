<h1><b>Operador REPLACE</b></h1><br/>
Este operador sustitute un valor o un digito de un campo por otro que demos nosotros.<br/>
Se escribe así: REPLACE ( <i>campo</i> , <i>‘?’</i> , <i>‘?’</i> ) <b>(La ? Significa carácter)</b><br/>
<br/>
Ejemplo:<br/>
SELECT campo2, REPLACE (campo1, ‘alo’, ‘e’) AS ‘ejemplo’<br/>
FROM tabla1<br/>
WHERE campo1 LIKE ‘%’;
<br/>
<br/>
<h1><b>Operador OR</b></h1><br/>
Este operador se utiliza para poner otra condición a parte del WHERE y de esta manera sea o una o otro.<br/>
Se escribe así: OR <i>campo</i> operador <i>valor</i><br/>
<br/>
Ejemplo:<br/>
SELECT campo1, campo2<br/>
FROM tabla1<br/>
WHERE campo2 >50<br/>
OR campo2=25;
<br/>
<br/>
<h1><b>Operador AND</b></h1><br/>
Este operador se utiliza para poner otra condición a parte del WHERE y de esta manera debe cumplirse las dos condiciones.<br/>
Se escribe así: AND <i>campo</i> operador <i>valor</i><br/>
<br/>
Ejemplo:<br/>
SELECT campo1, campo2<br/>
FROM tabla1<br/>
WHERE campo2> 50<br/>
AND campo1 = ”valor3”;
