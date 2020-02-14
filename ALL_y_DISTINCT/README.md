<h1><b>Operador ALL</b></h1>
Este operador indica que una condicion se cumple para todos los elementos de la tabla<br/>
Se escribe así: WHERE <i>campo</i> <= ALL (<br/>
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspSELECT <i>campo</i><br/>
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspFROM <i>tabla</i><br/>
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspWHERE <i>???</i><br/>
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp)<br/>
<br/>
Ejemplo:<br/>
SELECT campo1, campo2<br/>
FROM tabla1<br/>
WHERE campo2< ALL(<br/>
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspSELECT campo2<br/>
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspFROM tabla1<br/>
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspWHERE campo1= ‘valor1’<br/>
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp)
<br/>
<br/>
<h1><b>Operador DISTINCT</b></h1>
Este operador permite eliminar duplicados en la consulta<br/>
Se escribe así: SELECT DISTINCT <i>campo</i><br/>
Ejemplo: SELECT DISTINCT campo4<br/>
FROM tabla1
