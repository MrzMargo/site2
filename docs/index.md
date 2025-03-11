# Добро пожаловать на мой сайт

Здесь будет информация обо мне и моих проектах.

Но это не точно
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }}</title>
    <link rel="stylesheet" href="{{ base_url }}/css/main.css">
</head>
<body>
    <header>
        <h1>{{ site.title }}</h1>
    </header>
    <main>
        {{ page.content }}
    </main>
    <footer>
        <p>© 2025 Мой сайт</p>
    </footer>
</body>
</html>