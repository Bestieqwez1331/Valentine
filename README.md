<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>День Святого Валентина</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8d7da; /* серо-розовый фон */
            background-image: url('https://avatanplus.com/files/resources/original/5abf6185c0e1a1627b94f29e.png'); /* изображение сердец */
            background-repeat: repeat;
            background-size: 200px; /* уменьшение размера изображения */
            background-position: center;
            background-attachment: fixed;
        }
        .container {
            max-width: 800px;
            margin: 10% auto;
            padding: 20px;
            text-align: center;
            background-color: #ffffff; /* белый фон контейнера */
            border-radius: 10px;
        }
        h1, p {
            color: #333;
            font-weight: bold; /* жирный текст */
        }
        button {
            background-color: #808080; /* серый цвет кнопки */
            color: #ff69b4; /* розовый текст кнопки */
            font-weight: bold; /* жирный текст кнопки */
            padding: 15px 25px; /* увеличение размера кнопки */
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease; /* анимация при наведении на кнопку */
        }
        button:hover {
            background-color: #555; /* изменение цвета при наведении на кнопку */
        }
        button:focus {
            outline: none; /* убираем рамку при фокусировке */
        }
        p span {
            transition: color 0.3s ease; /* анимация подсветки слов */
            cursor: pointer;
        }
        p span:hover {
            color: #ff69b4; /* подсветка розовым цветом */
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Здравствуй солнышко!</h1>
        <p>
            <span>Поздравляем</span> 
            <span>вас</span> 
            <span>с</span> 
            <span>Днем</span> 
            <span>Святого</span> 
            <span>Валентина!</span> 
            <span>Этот</span> 
            <span>день</span> 
            <span>наполнен</span> 
            <span>любовью,</span> 
            <span>романтикой</span> 
            <span>и</span> 
            <span>нежностью.</span> 
            <span>Давайте</span> 
            <span>вместе</span> 
            <span>отметим</span> 
            <span>этот</span> 
            <span>замечательный</span> 
            <span>праздник,</span> 
            <span>который</span> 
            <span>напоминает</span> 
            <span>нам</span> 
            <span>о</span> 
            <span>важности</span> 
            <span>любви</span> 
            <span>в</span> 
            <span>нашей</span> 
            <span>жизни.</span>
        </p>
        <button onclick="window.location.href='valentine2.html'">Продолжить</button>
    </div>
</body>
</html>
