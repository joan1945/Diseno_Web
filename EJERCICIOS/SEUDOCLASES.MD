<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="estilos.css">
</head>
<body>
    <h1>seudoclases y seudoelementos</h1>
    <h2> Seudoelemento</h2>
    <p>Una seudoclase es una palabra clave que se combina con un selector y define un estado especial de los elementos</p>
    <h3>Seudoclase de enlaces</h3>
   <p> <a href=""> este</a> es un ejemplo de seudoclase de enlace</p>
   <h3>Seudoclases de raton</h3>
   <p class=" boton">click aqui</p>
   <h3>Seudoclase de interaccion</h3>
   <input type="text" value="Introduce tu nombre" >
   <form action=""><label > genero</label><br>
    <input type="radio" name="genero"value="hombre">
    <span> </span>

    
    
                
 </form>
    
</body>
</html>

a:link {
    color: green;
    font-weight: bold;
}

a:visited {
    color: orange;
    font-weight: bold;
}
.boton{
    color: white;
    background-color: blue;
    padding: 10px;
    border-radius:5;
}
.boton:hover{
    background-color: rgb(4, 77, 77);
    color: rgb(98, 224, 182);
}
.boton:active{
    color: rgb(14, 241, 135);
}
input:focus{
    border: 5px solid lightblue;
    box-shadow: 10px 10px 10px black;
    color: rgb(255, 59, 167);
    width: 300px;
}
input:checked + span{
    color:;
}
input[
    Tipe=radio]:checked {
        box-shadow:0 0 0 3px orange;

    }
