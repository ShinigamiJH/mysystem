<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой сайт</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Навигация -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Главная</a></li>
                <li><a href="#about">О нас</a></li>
                <li><a href="#contact">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <!-- Главная страница -->
    <section id="home">
        <h1>Добро пожаловать на мой сайт!</h1>
        <p>Здесь будет информация о проекте или услуге.</p>
    </section>

    <!-- О нас -->
    <section id="about">
        <h2>О нас</h2>
        <p>Мы — команда профессионалов, предоставляющая качественные услуги в сфере...</p>
    </section>

    <!-- Контакты -->
    <section id="contact">
        <h2>Контакты</h2>
        <form action="#" method="POST">
            <label for="name">Имя:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Сообщение:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Отправить</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Мой сайт. Все права защищены.</p>
    </footer>

</body>
</html>
