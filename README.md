<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Поздравительная открытка для Даши</title>
    <style>
        body {
            background-color: #fff0f5; /* пастельно-розовый фон */
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .card {
            background-color: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
            text-align: center;
            max-width: 600px;
            width: 100%;
            margin: 20px;
        }
        h1 {
            color: #ff69b4; /* нежно-розовый заголовок */
            font-size: 36px;
            margin-bottom: 15px;
        }
        p {
            font-size: 18px;
            color: #444;
            margin: 10px 0;
        }
        .signature {
            margin-top: 20px;
            font-style: italic;
            color: #666;
        }
        .heart {
            font-size: 40px;
            color: #ff69b4;
            margin: 20px 0;
        }
        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #ffb6c1;
            color: white;
            border: none;
            border-radius: 25px;
            text-decoration: none;
            font-size: 18px;
            transition: background-color 0.3s ease;
        }
        .button:hover {
            background-color: #ff69b4;
        }
        .phrases {
            margin-top: 30px;
        }
        .phrase {
            font-size: 20px;
            color: #ff69b4;
            opacity: 0;
            transition: opacity 1s ease-in-out;
        }
        @media (max-width: 600px) {
            h1 {
                font-size: 30px;
            }
            p {
                font-size: 16px;
            }
            .button {
                font-size: 16px;
            }
            .card {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Дорогая Даша,</h1>
        <p>С Днем Рождения!</p>
        <p>Этот день особенный, ведь он принадлежит тебе! Хочу поздравить тебя с днём рождения и пожелать море радости, смеха и тепла. Пусть твои мечты сбываются, каждый день будет наполнен новыми победами и яркими моментами.</p>
        <p>Ты — удивительный человек, который приносит свет в жизнь всех вокруг. Никогда не переставай мечтать, ведь у тебя всегда получится всё, за что ты возьмёшься! Оставайся такой же искренней, доброй и лучезарной, какой ты есть.</p>
        <p>Пусть в твоей жизни всегда будут рядом верные друзья, уютные вечера и моменты счастья, которые хочется запомнить навсегда. А все трудности пусть остаются позади, ведь впереди только лучшее!</p>
        <div class="heart">❤️</div>
        <p class="signature">Твой личный программист, MAESTRO!</p>
        <a href="#" class="button" onclick="showPhrases()">Обнять виртуально</a>

        <!-- Блок для фраз -->
        <div id="phrases" class="phrases">
            <div class="phrase" id="phrase1">Ты особенная!</div>
            <div class="phrase" id="phrase2">Ты невероятно добрая!</div>
            <div class="phrase" id="phrase3">Ты всегда поддерживаешь!</div>
            <div class="phrase" id="phrase4">Твоя улыбка — это лучик солнца!</div>
            <div class="phrase" id="phrase5">Ты талантлива!</div>
            <div class="phrase" id="phrase6">Ты придаёшь смысл каждому дню!</div>
            <div class="phrase" id="phrase7">Ты умеешь удивлять!</div>
            <div class="phrase" id="phrase8">С тобой всегда интересно!</div>
            <div class="phrase" id="phrase9">Ты — вдохновение!</div>
            <div class="phrase" id="phrase10">Ты сильная и смелая!</div>
            <div class="phrase" id="phrase11">Ты заслуживаешь только лучшего!</div>
            <div class="phrase" id="phrase12">Ты искренняя и честная!</div>
            <div class="phrase" id="phrase13">Ты красива не только снаружи, но и внутри!</div>
            <div class="phrase" id="phrase14">Ты умеешь слушать и понимать!</div>
            <div class="phrase" id="phrase15">Ты делаешь этот мир лучше!</div>
            <div class="phrase" id="phrase16">Ты всегда даришь радость!</div>
            <div class="phrase" id="phrase17">Ты — настоящий друг!</div>
            <div class="phrase" id="phrase18">Ты уникальна!</div>
            <div class="phrase" id="phrase19">Ты — счастье для всех вокруг!</div>
        </div>
    </div>

    <script>
        // Функция для последовательного показа фраз
        function showPhrases() {
            var phrases = document.querySelectorAll('.phrase');
            phrases.forEach(function(phrase, index) {
                setTimeout(function() {
                    phrase.style.opacity = 1;
                }, index * 1000); // Появление фраз с интервалом в 1 секунду
            });
        }
    </script>
</body>
</html>
