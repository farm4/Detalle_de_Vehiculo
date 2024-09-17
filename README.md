<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documento con Marca de Agua</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            position: relative;
            font-family: Arial, sans-serif;
            color: black;
            text-align: center;
        }
        .watermark {
            position: absolute;
            bottom: 10px;
            right: 10px;
            opacity: 0.3; /* Ajusta la opacidad según sea necesario */
            z-index: -1; /* Asegúrate de que la marca de agua esté detrás del contenido */
            pointer-events: none; /* Asegura que la imagen no interfiera con la interacción del contenido */
            width: 150px; /* Ajusta el tamaño de la marca de agua según sea necesario */
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <div class="content">
        <h1 style="font-size: 20px; font-weight: bold; color: black;">
            ☁️ ERROR 502 BAD GATEWAY
        </h1>
        <p style="font-size: 20px; font-weight: bold; color: black;">
            🔄 Vuelva a intentar más tarde
        </p>
    </div>
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/14/Logo_SAT_Guatemala.svg" alt="Marca de Agua" class="watermark">
</body>
</html>

