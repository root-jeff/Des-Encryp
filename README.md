<!DOCTYPE html>
<html>
<head>
    <title>Des-Encriptador</title>
    <script type="text/javascript" src="code.js"></script>
    <link rel="stile.css" href="/css/stile.css">
    <meta charset="utf-8">
    <link rel="stylesheet" href="css/stile.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Georama:wght@100;400;700&family=STIX+Two+Text:ital@1&display=swap" rel="stylesheet">
</head>
<body>
        <div class="textos-header">
            <h1>Welcome To The Des-Encryptor</h1>
            <p>Usalo con total normalidad</p>
        </div>
<nav>
    <div class="videos">
        <p>Mini Tutuorial de uso</p>
        <video src="videos/20210810_160618.mp4" type= "mp4" controls autoplay muted></video>
    </div>
    <div class="ejecutor">
        <input type="text" size="25"/>
    <button type="submit" onclick="encriptar(this)">Encriptar</button>
    <button type="submit" onclick="desencriptar(this)">Desencriptar</button>
    <h4 id="resultado">Des-Encripatación:</h4>
    </div>
</nav>
</body>
</html>  
