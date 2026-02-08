# fnaf
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Five Nights - Fan Game</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div id="game">
    <div id="office">
        <img id="animatronic" src="assets/animatronic.png">
    </div>

    <div id="ui">
        <p>Heure : <span id="hour">0</span>h</p>
        <p>Énergie : <span id="energy">100</span>%</p>
        <button onclick="toggleDoor()">🚪 Porte</button>
        <button onclick="toggleCamera()">📷 Caméra</button>
    </div>
</div>

<script src="script.js"></script>
</body>
</html>
