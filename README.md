<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моя страница-визитка</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Иванов Иван Иванович</h1>
            <p class="group">Группа: ПИ-201</p>
        </header>

        <main>
            <!-- Фото -->
            <div class="photo">
                <img src="img/photo.jpg" alt="Мое фото" width="200">
                <!-- Если нет фото, используйте заглушку:
                <div class="photo-placeholder">Фото</div>
                -->
            </div>

            <!-- Раздел "Обо мне" -->
            <section class="about">
                <h2>Обо мне</h2>
                <p>Меня зовут Иван. Я учусь на программиста и увлекаюсь веб-разработкой. В свободное время люблю читать книги и заниматься спортом. Мечтаю стать профессиональным frontend-разработчиком.</p>
            </section>

            <!-- Навыки (список) -->
            <section class="skills">
                <h2>Мои навыки</h2>
                <ul>
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>JavaScript (начальный уровень)</li>
                    <li>Git</li>
                </ul>
            </section>

            <!-- Контакты -->
            <section class="contacts">
                <h2>Контакты</h2>
                <p>Email: <a href="mailto:ivanov@example.com">ivanov@example.com</a></p>
                <p>Телефон: <a href="tel:+79991234567">+7 (999) 123-45-67</a></p>
            </section>
        </main>

        <footer>
            <p>&copy; 2026 Иванов Иван</p>
        </footer>
    </div>
</body>
</html>