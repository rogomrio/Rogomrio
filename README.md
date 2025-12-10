<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fotoweb</title>

    <style>
        body {
            margin: 0;
            padding: 0;
            background: url("URL_TVEHO_OBRAZKU") no-repeat center center fixed;
            background-size: cover;
            background-color: #000;
            font-family: Arial, sans-serif;
            color: #fff;
        }

        /* lehké stmavení pozadí kvůli čitelnosti */
        .overlay {
            background: rgba(0, 0, 0, 0.45);
            min-height: 100vh;
            padding: 40px;
        }

        h1 {
            text-align: center;
            font-size: 48px;
            margin-bottom: 30px;
        }

        p {
            text-align: center;
            max-width: 700px;
            margin: 0 auto 40px auto;
            font-size: 20px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            max-width: 1100px;
            margin: 0 auto;
        }

        .photo {
            background: #111;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 0 10px rgba(0,0,0,0.5);
        }

        .photo img {
            width: 100%;
            display: block;
        }

        footer {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            color: #ccc;
        }
    </style>

</head>
<body>
    <div class="overlay">

        <h1>Můj fotoweb</h1>
        <p>Vítej na místě, kde házím fotky, nápady a cokoliv, co mě zrovna napadne.</p>

        <div class="gallery">
            <div class="photo"><img src="https://via.placeholder.com/400x300" alt=""></div>
            <div class="photo"><img src="https://via.placeholder.com/400x300" alt=""></div>
            <div class="photo"><img src="https://via.placeholder.com/400x300" alt=""></div>
            <div class="photo"><img src="https://via.placeholder.com/400x300" alt=""></div>
        </div>

        <footer>
            © 2025 – Tvoje stránka
        </footer>

    </div>
</body>
</html>
