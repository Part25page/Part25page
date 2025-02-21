<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Música</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f3f3f3;
            color: #333;
        }

        header {
            background-color: #800080;
            color: white;
            text-align: center;
            padding: 1em 0;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            padding: 2em 0;
        }

        .music-player, .music-store {
            background-color: #fff;
            padding: 1em;
            margin-bottom: 2em;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #800080;
        }

        .btn {
            background-color: #800080;
            color: white;
            padding: 0.5em 1em;
            text-decoration: none;
            display: inline-block;
            border-radius: 5px;
        }

        .btn:hover {
            background-color: #5a005a;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a la Tienda de Música</h1>
    </header>
    <div class="container">
        <div class="music-player">
            <h2>Reproductor Musical</h2>
            <audio controls>
                <source src="tu-cancion.mp3" type="audio/mp3">
                Tu navegador no soporta el elemento de audio.
            </audio>
        </div>
        <div class="music-store">
            <h2>Tienda de Música</h2>
            <ul>
                <li>
                    <span>Álbum 1 - Artista 1</span>
                    <a href="#" class="btn">Comprar</a>
                </li>
                <li>
                    <span>Álbum 2 - Artista 2</span>
                    <a href="#" class="btn">Comprar</a>
                </li>
                <li>
                    <span>Álbum 3 - Artista 3</span>
                    <a href="#" class="btn">Comprar</a>
                </li>
            </ul>
        </div>
    </div>
</body>
</html>
