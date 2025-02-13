<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aku Sayang Nurfa</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffcccb;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        h1 {
            font-size: 3rem;
            color: #d63384;
            animation: pulse 1.5s infinite;
        }
        .emoji-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            font-size: 3rem;
            cursor: pointer;
        }
        p {
            font-size: 1.5rem;
            color: #333;
        }
        .hidden-message {
            display: none;
            font-size: 2rem;
            color: #d63384;
            margin-top: 20px;
        }
        .letter-container {
            display: none;
            flex-direction: column;
            align-items: center;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
    </style>
    <script>
        function openLetter() {
            document.getElementById("letter").style.display = "flex";
        }
    </script>
</head>
<body>
    <h1>Aku Sayang Nurfa ❤️</h1>
    <p>Kamu adalah orang yang hebat di dunia!</p>
    <div class="emoji-container">
        ❤️ 🏡 😊 ☀️ ⭐ 💌
    </div>
    <div class="emoji-container" onclick="openLetter()">
        ✉️ (Klik untuk membuka surat)
    </div>
    <div id="letter" class="letter-container">
        <h2>Happy Valentine Sayangku! ❤️</h2>
        <p>Semoga hari ini penuh cinta dan kebahagiaan untukmu! 💕</p>
    </div>
</body>
</html>
