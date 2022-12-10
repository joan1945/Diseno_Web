<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/estilos.css">
    <link rel="stylesheet" href="">
    
</head>
<body>
    <header> 
        <H1>ENCABEZADO NIVEL 1</H1>
        <nav>
            <ul>
                
                <LI>ENLACE 1</LI>
                <LI>ENLACE 2</LI>
                <LI>ENLACE 3</LI>
                <LI>ENLACE 4</LI>
            </ul>
        </nav>
    </header>
    <main>
        <div class="contenedor"></div>
        <section>
            <h2>Encabezado nivel 2</h2>
            <p>Aqui va el primer parrafo</p><br>
            <p>Aqui va el segundo el parrafo</p>
        </section>
        <aside>
            <h2>APARTADO</h2>
            <p>ELIGE UNA OPCION</p>
            <form action="">
                <input type="checkbox" name="opcion">Opcion 1 <br>
                <input type="checkbox" name="opcion">Opcion 2 <br>
                <input type="checkbox" name="opcion">Opcion 3 <br>
                <input type="checkbox" name="enviar" value="enviar">Opcion 1 <br>
            </form>
        </aside>
    </main>
    <footer>
        <p>Seccion de informacion de contacto, derechos de autor et,</p>
    </footer>
    ![image](https://user-images.githubusercontent.com/115374130/206879973-8f460ae5-f727-4a02-b0ef-26b60418736a.png)

  *{
    margin: 0;
    padding: 0;
}
body{
    font-family: ;
    font-family: Roboto , sans-serif;
}
header{
    background-color: black(45 45 45)
    padding-top: 30px;
}
h1{
    color: aqua;
    text-align: center;
    font-size: 3em;
    letter-spacing: 3px; 
}
nav{
    background-color: aquamarine;
    padding: 25px 0;
    margin-top: 30px;
}
nav ul {
    display: flex;
    justify-content: space-around;
}
nav li{
    list-style: none;
}
section{
    background-color: blueviolet;
    width: 80%;
}
aside{
    background-color: brown;
    width: 20%;
}
footer{
    background-color: beige;
    height: 20vh;
}
.contenedor{
    display: flex;
    width: 100%;
    height: 40vh;
}
  ![image](https://user-images.githubusercontent.com/115374130/206879995-32d7a804-6ff1-401e-afa3-702552c41381.png)
