
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой сайт с кодами</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #333;
            text-align: center;
        }
        .code-block {
            background: #eee;
            border-left: 4px solid #007BFF;
            padding: 15px;
            margin: 20px 0;
            overflow-x: auto;
        }
        .code-lang {
            font-weight: bold;
            color: #555;
            margin-bottom: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Сайт с готовыми кодами HTML/CSS</h1>

        <div class="code-block">
            <div class="code-lang">HTML-каркас</div>
            <pre>&lt;!DOCTYPE html&gt;
&lt;html lang="ru"&gt;
&lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;title&gt;Заголовок&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;h1&gt;Привет, мир!&lt;/h1&gt;
&lt;/body&gt;
&lt;/html&gt;</pre>
        </div>

        <div class="code-block">
            <div class="code-lang">Простой CSS-стиль</div>
            <pre>body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
}

h1 {
    color: #333;
    text-align: center;
}</pre>
        </div>

        <div class="code-block">
            <div class="code-lang">Кнопка с эффектом наведения</div>
            <pre>.btn {
    display: inline-block;
    padding: 10px 20px;
    background-color: #007BFF;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.btn:hover {
    background-color: #0056b3;
}</pre>
        </div>
    </div>
</body>
</html>
