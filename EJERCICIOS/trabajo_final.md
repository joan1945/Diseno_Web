css css css css css

		*{
            padding: 0%;
            margin: 0%;
        }

        body{
            font-family: 'Montserrat', sans-serif;
            font-family: 'Radio Canada', sans-serif;
        }

        nav{
            align-items: center;
            justify-content: space-between;
            display: flex;
            margin-left: 4%;
            margin-right: 4%;
            padding-top: 1em;
            padding-bottom: 2em;
        }

        .boton_registro{
            text-decoration: none;
        }

        ul{
            align-items: center;
            justify-content: space-between;
            display: flex;
        }

        li{
            margin-left: 2em;
            margin-right: 2em;
            list-style: none;
            font-size: 16pt;
        }

        .menu{
            font-weight: bold;
        }

        .boton_menu{
            text-decoration: none;
            color: black;
        }

        .boton_menu :hover{
            color: rgb(1, 98, 65);
            font-size: 18pt;
        }

        #ingreso{
            border: 2px solid black;
            border-radius: 15em;
            color: black;
            padding-left: 2em;
            padding-right: 2em;
            padding-top: 1em;
            padding-bottom: 1em;
        }

        #ingreso2 :hover{
            background-color: rgb(207, 206, 206);
        }

        #registrarse{
            border: 2px solid black;
            background-color: black;
            color: white;
            border-radius: 15em;
            padding-left: 2em;
            padding-right: 2em;
            padding-top: 1em;
            padding-bottom: 1em;
        }

        .boton_registro :hover{
            font-size: 18pt;
        }

        main{
            padding-bottom: 3em;
        }

        #caja1{
            background-color: rgb(1, 98, 65);
            color: white;
            text-align: center;
            margin-left: 3em;
            margin-right: 3em;
            padding: 2em;
        }

        #aprende{
            color: white;
        }

        #aprende :hover{
            color: black;
        }

        #caja2{
            background-color: rgb(206, 4, 47);
            color: white;
            margin-left: 3em;
            margin-right: 3em;
            align-items: center;
            justify-content: space-between;
            display: flex;
            text-align: center;
        }

        #estructura1{
            padding-right: 11em;
        }

        #caja3{
            background-color:  rgb(206, 4, 47);
            color: white;
            margin-left: 3em;
            margin-right: 3em;
            align-items: center;
            justify-content: space-between;
            display: flex;
            text-align: center;
        }

        .titulos{
            font-size: 60pt;
            letter-spacing: .2em;
        }
        .parrafos{
            font-size: 30pt;
        }

        .boton_pequeño{
            color: white;
            border: 2px solid white;
            border-radius: 15em;
            text-decoration: none;
            border-radius: 15em;
            padding-left: 2em;
            padding-right: 2em;
            padding-top: 1em;
            padding-bottom: 1em;
        }

        .boton_pequeño :hover{
            font-size: 35pt;
        }

        hr{
            margin-left: 3em;
            margin-right: 3em;
        }

        .iconos{
            margin-left: 2em;
        }

        #pie{
            margin-left: 2em;
        }
        
        footer{
            margin-left: 3em;
            margin-right: 3em;
            padding-top: 1em;
        }
        <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/estilos.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100&family=Radio+Canada:wght@300&display=swap" rel="stylesheet">
    <title>Alebrijes proyecto</title>
	<style>
    <body>
            
            <header>
                <nav>
                    <a href=""><img src="img/icono_maya.png" width="80px"></a>
                    <ul>
                        <a class="boton_menu" href=""><li class="menu">ARTE</li></a>
                        <a class="boton_menu" href=""><li class="menu">COLECCIONES</li></a>
                        <a class="boton_menu" href=""><li class="menu">CONOCENOS</li></a>
                    </ul>
                    <ul id="registro">
                        <a id="ingreso2" class="boton_registro" href=""><li id="ingreso">Iniciar seción</li></a>
                        <a class="boton_registro" href=""><li id="registrarse">Registrarse</li></a>
                    </ul>
                </nav>
            </header>
        
            <main>
                <article>
                    <div id="caja1">
                        <p><h1 class="titulos">UNA EXPERIENCIA <br>
                            TOTALMENTE NUEVA <br>
                            EN EL ARTE</h1></p> <br>
                        <p class="parrafos">Una tradición milenaria nos ha acompañado a través de todo <br>
                        este tiempo. <a id="aprende" href="">Aprende mas...</a></p>
                    </div>
                    <br>
                    <div id="caja2">
                        <img src="img/alebrije.jpg" width="800px">
                        <div id="estructura1">
                            <p class="parrafos"><h1 class="titulos">ALEBRIJES <br>
                                MEXICANOS</h1></p>
                            <P class="parrafos">Tallados en madera cumplen con las mas <br>
                            altas exigencias en diseño.</P> <br>
                            <br>
                            <br>
                        <a class="boton_pequeño" href=""> Has tu pedido</a>
                        </div>
                    </div>
                    <br>
                    <div id="caja3">
                        <div id="estructura2">
                            <p></p><h1 class="titulos">CREATIVIDAD E IMAGINACIÓN</h1></p>
                            <p class="parrafos">Un sueño hecho realidad.</p> <br>
                            <br>
                            <br>
                            <a class="boton_pequeño" href="">Has tu pedido</a>
                        </div>
                        <img src="img/alebrije 2.png" width="900px">
                    </div>
                </article>
            </main>
                <hr>
            <footer>
                <br>
                <a href=""><img class="iconos" src="img/fb.png" width="50px"></a>
                <a href=""><img class="iconos" src="img/twitter.png" width="50px"></a>
                <a href=""><img class="iconos" src="img/insta.png" width="50px"></a>
                <a href=""><img class="iconos" src="img/pint.png" width="50px"></a>
                <a href=""><img class="iconos" src="img/youtube.png" width="50px"></a>
                <a href=""><img class="iconos" src="img/spoti.png" width="50px"></a>
                <br>
                <br>
                <p id="pie">2022 Todos los derechos reselvados al arte popular</p>
                <br>
            </footer>
        </body>
        </html>
