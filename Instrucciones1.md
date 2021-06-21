Parece que el error estuvo ocasionado a que faltaba 
indicarle a nuestro archivo que el codigo a correr era php
Hay que recordar que nuestro navegador es un interprete
que puede correr diferentes lenguajes (javascript, php, html....)
por lo tanto el error se resuelve agregando el siguiente encabezado

<?php
print("holamundo");
print("Pedro_Galvez");
print("soy un archivo php");
?>

Finalmente muevete al branch Release