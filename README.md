<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой Сайт</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #74ebe5 0%, #4a00e0 100%);
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        h1 { margin-0; font-size: 2.5rem; }
        p { font-size: 1.2rem; opacity: 0.9; }
        .btn {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background: white;
            color: #4a00e0;
            text-decoration: none;
            border-radius: 25px;
            font-weight: bold;
            transition: 0.3s;
        }
        .btn:hover { transform: scale(1.05); }
    </style>
</head>
<body>

    <div class="card">
        <h1>Привет, мир!</h1>
        <p>Это мой первый прокачанный сайт на GitHub Pages ✨</p>
        <a href="https://github.com" class="btn">Мой профиль</a>
    </div>

</body>
</html>
