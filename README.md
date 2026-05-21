<!DOCTYPE html>
<html lang="es">

<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>TIC'S - Submódulos</title>

    <link href="https://fonts.googleapis.com/css2?family=Roboto&family=Pacifico&display=swap" rel="stylesheet">

    <style>

        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            scroll-behavior:smooth;
        }

        body{
            background: linear-gradient(to right, #141e30, #243b55);
            font-family:'Roboto', sans-serif;
            color:white;
        }

        .banner{

            width:100%;
            height:100vh;

            background:
            linear-gradient(rgba(0,0,0,0.7),
            rgba(0,0,0,0.7)),

            url('https://images.unsplash.com/photo-1518770660439-4636190af475?q=80&w=1400&auto=format&fit=crop');

            background-size:cover;
            background-position:center;

            display:flex;
            justify-content:center;
            align-items:center;

            text-align:center;
        }

        .contenido-banner h1{

            font-size:70px;

            font-family:'Pacifico', cursive;

            background: linear-gradient(to right, #00f2fe, #4facfe, #43e97b);

            -webkit-background-clip:text;
            -webkit-text-fill-color: transparent;

            margin-bottom:20px;
        }

        .contenido-banner p{

            font-size:30px;
            margin-bottom:30px;
        }

        .boton{

            text-decoration:none;

            background: linear-gradient(to right, #fc466b, #3f5efb);

            color:white;

            padding:15px 35px;

            border-radius:40px;

            font-size:22px;

            transition:0.5s;
        }

        .boton:hover{

            background: linear-gradient(to right, #43e97b, #38f9d7);

            transform:scale(1.1);
        }

        h1{

            text-align:center;

            font-family:'Pacifico', cursive;

            color:white;

            padding:30px;

            font-size:50px;
        }

        .contenedor{

            width:90%;

            margin:auto;
        }

        table{

            width:100%;

            border-collapse:collapse;

            margin:30px 0;

            background:white;

            color:black;

            border-radius:15px;

            overflow:hidden;

            box-shadow:0px 0px 15px black;
        }

        th{

            background:#00b4db;

            color:white;

            padding:15px;
        }

        td{

            padding:15px;

            text-align:center;

            border:1px solid #ddd;
        }

        .submodulo{

            background: rgba(255,255,255,0.1);

            margin:35px 0;

            padding:25px;

            border-radius:20px;

            box-shadow:0px 0px 20px black;

            transition:0.5s;
        }

        .submodulo:hover{

            transform:scale(1.02);
        }

        .submodulo h2{

            color:#ffd700;

            text-align:center;

            margin-bottom:20px;

            font-size:38px;
        }

        .fila{

            display:flex;

            gap:20px;

            align-items:flex-start;

            flex-wrap:wrap;
        }

        .texto{

            flex:1;
        }

        .texto ul{

            margin-top:15px;
        }

        .texto li{

            margin-bottom:12px;

            font-size:20px;
        }

        .imagen-profesor{

            flex:0 0 auto;
        }

        .imagen-profesor img{

            width:220px;

            height:220px;

            object-fit:cover;

            border-radius:20px;

            border:5px solid #00d2ff;

            box-shadow:0px 0px 15px black;
        }

        .slider{

            position:relative;

            width:100%;

            overflow:hidden;

            margin-top:25px;
        }

        .contenedor-imagenes{

            display:flex;

            transition:transform 0.5s ease;
        }

        .contenedor-imagenes img{

            min-width:100%;

            height:420px;

            object-fit:cover;

            border-radius:20px;

            border:4px solid white;
        }

        /* VIDEOS NORMALES */

        .video-slider{

            margin-top:25px;
        }

        .contenedor-videos video{

            width:100%;

            height:420px;

            border-radius:20px;

            border:4px solid white;
        }

        .flecha{

            position:absolute;

            top:50%;

            transform:translateY(-50%);

            background:rgba(0,0,0,0.6);

            color:white;

            border:none;

            padding:15px;

            cursor:pointer;

            font-size:35px;

            border-radius:50%;

            z-index:10;

            transition:0.3s;
        }

        .flecha:hover{

            background:#00d2ff;
        }

        .izquierda{

            left:10px;
        }

        .derecha{

            right:10px;
        }

        @media(max-width:768px){

            .fila{

                flex-direction:column;
            }

            .imagen-profesor{

                display:flex;

                justify-content:center;

                width:100%;
            }

            .contenido-banner h1{

                font-size:45px;
            }

            .contenido-banner p{

                font-size:22px;
            }
        }

    </style>

</head>

<body>

    <!-- BANNER -->

    <div class="banner">

        <div class="contenido-banner">

            <h1>Capacitación TIC'S</h1>

            <p>
                Proyecto Final de los Submódulos
            </p>

            <a href="#contenido" class="boton">
                Ver Proyecto
            </a>

        </div>

    </div>

    <!-- TITULO -->

    <h1 id="contenido">
        Capacitación TIC'S (3° a 6° Semestre)
    </h1>

    <div class="contenedor">

        <!-- TABLA -->

        <div class="submodulo">

            <h2>Resumen del Ciclo Escolar</h2>

            <table>

                <tr>
                    <th>Semestre</th>
                    <th>Profesor</th>
                    <th>Aprendizaje</th>
                </tr>

                <tr>
                    <td>3°</td>
                    <td>Arturo Alejandro Rodas Burguete</td>
                    <td>Excel y Word</td>
                </tr>

                <tr>
                    <td>4°</td>
                    <td>Rodiver Silva Vidal</td>
                    <td>Comunidades Virtuales</td>
                </tr>

                <tr>
                    <td>5°</td>
                    <td>Monica Cruz Delgado</td>
                    <td>Access</td>
                </tr>

                <tr>
                    <td>6°</td>
                    <td>Monica Cruz Delgado</td>
                    <td>HTML y Páginas Web</td>
                </tr>

            </table>

        </div>

        <!-- 3° SEMESTRE -->

        <div class="submodulo">

            <h2>3° Semestre - Excel y Word</h2>

            <p><strong>Profesor:</strong> Arturo Alejandro Rodas Burguete</p>

            <div class="fila">

                <div class="texto">

                    <ul>
                        <li>Creación de documentos en Word</li>
                        <li>Formato de texto</li>
                        <li>Tablas e imágenes</li>
                        <li>Enlace Word-Excel</li>
                        <li>Fórmulas</li>
                        <li>Gráficas</li>
                        <li>Macros</li>
                    </ul>

                </div>

                <div class="imagen-profesor">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\WhatsApp Image 2026-04-21 at 11.17.03.jpeg">

                </div>

            </div>

            <div class="slider">

                <button class="flecha izquierda" onclick="mover(-1,0)">❮</button>

                <div class="contenedor-imagenes" id="slider0">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\3ER SEMESTRE.jpeg">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\Captura de pantalla 2026-05-19 123409.png">

                </div>

                <button class="flecha derecha" onclick="mover(1,0)">❯</button>

            </div>

            <div class="video-slider">

                <div class="contenedor-videos">

                    <video controls>
                        <source src="C:\Users\HP\Desktop\VIDEOS\3RO.mp4" type="video/mp4">
                    </video>

                </div>

            </div>

        </div>

        <!-- 4° SEMESTRE -->

        <div class="submodulo">

            <h2>4° Semestre - Comunidades Virtuales</h2>

            <p><strong>Profesor:</strong> Rodiver Silva Vidal</p>

            <div class="fila">

                <div class="texto">

                    <ul>
                        <li>Comunidades virtuales</li>
                        <li>Redes sociales</li>
                        <li>Interacción digital</li>
                        <li>Netiqueta</li>
                        <li>Perfiles digitales</li>
                        <li>Chamilo</li>
                        <li>Trabajo colaborativo</li>
                    </ul>

                </div>

                <div class="imagen-profesor">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\WhatsApp Image 2026-04-21 at 11.52.11.jpeg">

                </div>

            </div>

            <div class="slider">

                <button class="flecha izquierda" onclick="mover(-1,1)">❮</button>

                <div class="contenedor-imagenes" id="slider1">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\4to semestre 2da imagen .jpeg">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\4to semetre.jpeg">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\WhatsApp Image 2026-04-21 at 11.17.15.jpeg">

                </div>

                <button class="flecha derecha" onclick="mover(1,1)">❯</button>

            </div>

            <div class="video-slider">

                <div class="contenedor-videos">

                    <video controls>
                        <source src="C:\Users\HP\Desktop\VIDEOS\Protocolos de Comunicación 4TO.mp4" type="video/mp4">
                    </video>

                </div>

            </div>

        </div>

        <!-- 5° SEMESTRE -->

        <div class="submodulo">

            <h2>5° Semestre - Access</h2>

            <p><strong>Profesor:</strong> Monica Cruz Delgado</p>

            <div class="fila">

                <div class="texto">

                    <ul>
                        <li>Base de datos</li>
                        <li>Tablas</li>
                        <li>Relaciones</li>
                        <li>Consultas</li>
                        <li>Formularios</li>
                        <li>Reportes</li>
                        <li>Negocios</li>
                    </ul>

                </div>

                <div class="imagen-profesor">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\WhatsApp Image 2026-04-21 at 11.54.43.jpeg">

                </div>

            </div>

            <div class="slider">

                <button class="flecha izquierda" onclick="mover(-1,2)">❮</button>

                <div class="contenedor-imagenes" id="slider2">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\5to semestre.jpeg">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\EDITORES DE PAGINAS WEB.jpg">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\5to.jpeg">

                </div>

                <button class="flecha derecha" onclick="mover(1,2)">❯</button>

            </div>

            <div class="video-slider">

                <div class="contenedor-videos">

                    <video controls>
                        <source src="C:\Users\HP\Desktop\VIDEOS\5TO.mp4" type="video/mp4">
                    </video>

                </div>

            </div>

        </div>

        <!-- 6° SEMESTRE -->

        <div class="submodulo">

            <h2>6° Semestre - HTML</h2>

            <p><strong>Profesor:</strong> Monica Cruz Delgado</p>

            <div class="fila">

                <div class="texto">

                    <ul>
                        <li>Estructura HTML</li>
                        <li>Etiqueta div</li>
                        <li>Multimedia</li>
                        <li>CSS</li>
                        <li>Tablas</li>
                        <li>Diseño web</li>
                        <li>Publicación</li>
                    </ul>

                </div>

                <div class="imagen-profesor">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\WhatsApp Image 2026-04-21 at 11.54.43.jpeg">

                </div>

            </div>

            <div class="slider">

                <button class="flecha izquierda" onclick="mover(-1,3)">❮</button>

                <div class="contenedor-imagenes" id="slider3">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\EDITORES DE PAGINAS WEB.jpg">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\Captura de pantalla 2026-05-19 123919.png">

                    <img src="C:\Users\HP\Desktop\imagenes .JPEG\Captura de pantalla 2026-05-19 124035.png">

                </div>

                <button class="flecha derecha" onclick="mover(1,3)">❯</button>

            </div>

            <div class="video-slider">

                <div class="contenedor-videos">

                    <video controls>
                        <source src="C:\Users\HP\Desktop\VIDEOS\WhatsApp Video 2026-04-21 at 13.17.02.mp4" type="video/mp4">
                    </video>

                </div>

            </div>

        </div>

    </div>

    <!-- JAVASCRIPT -->

    <script>

        let posiciones = [0,0,0,0];

        function mover(direccion, slider){

            const contenedor =
            document.getElementById("slider" + slider);

            const total =
            contenedor.children.length;

            posiciones[slider] += direccion;

            if(posiciones[slider] < 0){

                posiciones[slider] = total - 1;
            }

            if(posiciones[slider] >= total){

                posiciones[slider] = 0;
            }

            contenedor.style.transform =
            `translateX(-${posiciones[slider] * 100}%)`;
        }

    </script>

</body>
</html>
