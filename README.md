<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Game Tebak Angka</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Game Tebak Angka</h1>
        <p>Masukkan angka antara 1 dan 100:</p>
        <input type="number" id="guess" min="1" max="100">
        <button onclick="checkGuess()">Tebak</button>
        <p id="message"></p>
        <p id="attempts"></p>
    </div>
    <script src="script.js"></script>
</body>
</html>


