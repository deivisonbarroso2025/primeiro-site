<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>DOOM no Navegador</title>
<style>
body{
    margin:0;
    background:black;
    color:white;
    font-family:Arial;
    text-align:center;
}

#game{
    width:640px;
    height:400px;
    margin:auto;
    margin-top:20px;
    border:3px solid red;
}

canvas{
    width:100%;
    height:100%;
}
</style>
</head>

<body>

<h1>DOOM - HTML5</h1>
<p>Use WASD para andar e mouse para mirar</p>

<div id="game">
<canvas id="doomcanvas"></canvas>
</div>

<script src="https://js-dos.com/v8/js-dos.js"></script>

<script>
Dos(document.getElementById("game"), {
    wdosboxUrl: "https://js-dos.com/v8/wdosbox.js"
}).run("https://js-dos.com/cdn/upload/DOOM-@evilution.zip");
</script>

</body>
</html>
