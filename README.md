<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Revolución Verde: Las 7R</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: 'Montserrat', sans-serif;
            background-color: #121212;
            color: #f0f0f0;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #00e676, #00b0ff);
            color: #121212;
            text-align: center;
            padding: 50px 20px;
            box-shadow: 0 0 20px #00e676;
        }

        header h1 {
            font-size: 2.8em;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2em;
            font-style: italic;
        }

        .container {
            max-width: 1100px;
            margin: auto;
            padding: 40px 20px;
        }

        .r-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .r-item {
            background-color: #1f1f1f;
            border-left: 5px solid #00e676;
            padding: 20px;
            border-radius: 10px;
            transition: transform 0.3s ease, border-left-color 0.3s ease;
        }

        .r-item:hover {
            transform: translateY(-5px);
            border-left-color: #00b0ff;
        }

        .r-item h2 {
            margin-top: 0;
            color: #00e676;
        }

        .media-section {
            margin-top: 60px;
        }

        .media-section h2 {
            border-bottom: 2px solid #00b0ff;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        img, video {
            width: 100%;
            border-radius: 10px;
            margin-top: 15px;
        }

        audio {
            width: 100%;
            margin-top: 10px;
        }

        a {
            color: #00e5ff;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        ul {
            list-style: none;
            padding-left: 0;
        }

        ul li {
            margin-bottom: 10px;
        }

        footer {
            text-align: center;
            background-color: #1b1b1b;
            color: #bbb;
            padding: 30px 10px;
            margin-top: 60px;
            font-size: 0.95em;
        }
    </style>
</head>
<body>

<header>
    <h1>Revolución Verde: Las 7R</h1>
    <p>Redefiniendo el futuro del planeta con acción consciente 🌍</p>
</header>


    <section class="media-section">
        <h2>Infografía ilustrativa</h2>
        <img src="C:\Users\ALUMNO\Downloads\otroooo.png" alt="Infografía 7R">
    </section>

    <section class="media-section">
 
        <section>
  <h2>Video educativo</h2>
  <iframe width="560" height="315" src="https://www.youtube.com/embed/YGMeO5L_LAs" 
    title="Video sobre reciclaje" frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
  </iframe>
</section>



    <section class="media-section">
        <h2>Audio ambiental</h2>
        <audio controls>
            <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
            Tu navegador no soporta el elemento de audio.
        </audio>
    </section>

   <li> <a href="C:/Users/ALUMNO/Downloads/informqcion.html"> REGRESAR A LA PÁGINA PRINCIPAL </a></li> 

</main>

<footer>
    Hecho con conciencia ecológica 💚 - Vive, educa y transforma.
</footer>

</body>
</html> 
