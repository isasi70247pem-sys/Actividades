# Actividades
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Práctica Individual HTML</title>
    <style>
        table { border-collapse: collapse; margin-bottom: 20px; width: 50%; }
        th, td { border: 1px solid black; padding: 8px; text-align: left; }
        .center { text-align: center; }
        .category-cell { vertical-align: middle; font-weight: bold; color: purple; }
        .nested-list { list-style-type: disc; }
        .nested-list ul { list-style-type: square; }
        .nested-list ul ul { list-style-type: circle; }
    </style>
</head>
<body>

    <table>
        <tr>
            <th>ALUMNO</th>
            <th>NOTA</th> 
        </tr>
        <tr>
            <td>Pepe</td> 
            <td>7,65</td> 
        </tr>
        <tr>
            <td>María</td> 
            <td>8,54</td> 
        </tr>
        <tr>
            <td>Jordi</td>
            <td>5,55</td> 
        </tr>
        <tr>
            <td><strong>MEDIA</strong></td> 
            <td><strong>7,25</strong></td> 
        </tr>
        <tr>
            <td><strong>DESV. TÍPICA</strong></td> 
            <td><strong>7,35</strong></td> 
        </tr>
    </table>

    <div>
        <a href="https://www.amazon.com">amazon.com</a> 
        <a href="https://www.youtube.com">►YouTube</a> 
        <p>Arriba está Amazon Arriba está Youtube</p> 
    </div>

    <hr>

    <table>
        <tr>
            <td rowspan="5" class="category-cell">Gastronomía</td> 
            <td>Restaurantes</td> 
            <td rowspan="2"><img src="https://img.freepik.com/foto-gratis/primer-plano-carne-asada-salsa-verduras-patatas-fritas-plato-sobre-mesa_181624-35847.jpg?semt=ais_hybrid&w=740&q=80" alt="Gastronomía 1" width="150"></td>
        </tr>
        <tr>
            <td>Sidrerías y asadores</td> 
        </tr>
        <tr>
            <td>Bodegas de vino y txakoli</td>
            <td rowspan="3"><img src="https://f.rpp-noticias.io/2024/10/09/415341_1652816.jpg?width=1020&quality=80" alt="Gastronomía 2" width="150"></td>
        </tr>
        <tr>
            <td>Productos típicos</td> 
        </tr>
        <tr>
            <td>Escuelas de hostelería</td> 
        </tr>

        <tr>
            <td rowspan="4" class="category-cell">Cultura</td> 
            <td>archivos y bibliotecas</td> 
            <td rowspan="4"><img src="https://static.guruexplorers.com/uploads/S2DOucR2gTZbvLfr5ii2pmdZVp81T6J2qRLn1Hmt.jpg" alt="Cultura" width="150"></td>
        </tr>
        <tr>
            <td>museos</td> 
        </tr>
        <tr>
            <td>palacios de congresos</td> 
        </tr>
        <tr>
            <td>ferias de muestras</td> 
        </tr>

        <tr>
            <td rowspan="3" class="category-cell">Ocio</td> 
            <td>Entretenimiento y diversión</td> 
            <td rowspan="3"><img src="https://haycanal.com/uploads/noticias/16153/El_entretenimiento.jpg" alt="Ocio" width="150"></td>
        </tr>
        <tr>
            <td>Ocio cultural</td> 
        </tr>
        <tr>
            <td>Excursiones y deporte</td> 
        </tr>
    </table>

    <hr>

    <table>
        <tr>
            <td>
                <h2>Jugadores de fútbol de leyenda</h2> 
                <ul class="nested-list">
                    <li>España 
                        <ul>
                            <li>Casillas</li> 
                            <li>Xavi</li> 
                            <li>Iniesta</li> 
                        </ul>
                    </li>
                    <li>Francia 
                        <ul style="list-style-type: disc;">
                            <li>Zidane</li> 
                            <li>Henry</li> 
                            <li>Barthez</li> 
                        </ul>
                    </li>
                    <li>Brasil 
                        <ul style="list-style-type: circle;">
                            <li>Ronaldo</li> 
                            <li>Pelé</li> 
                            <li>Ronaldinho</li> 
                        </ul>
                    </li>
                </ul>
            </td>
        </tr>
    </table>
 </body>
</html>
