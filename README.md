<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Неділя без рафінованого цукру</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Експеримент: Неділя без рафінованого цукру</h1>
        <nav>
            <ul class="nav">
                <li><a href="index.html">Головна</a></li>
                <li><a href="motivation.html">Мотивація</a></li>
                <li><a href="results.html">Результати</a></li>
                <li><a href="gallery.html">Галерея</a></li>
                <li><a href="feedback.html">Зворотній зв'язок</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="intro">
            <h2>Чому варто відмовитись від цукру на тиждень?</h2>
            <ul>
                <li>Покращення сну</li>
                <li>Зменшення втоми</li>
                <li>Краще самопочуття</li>
            </ul>
            <img src="nosugar.jpg" alt="No Sugar" class="responsive-img">
        </section>

        <section class="table-section">
            <h2>Продукти-заміни цукру</h2>
            <table>
                <thead>
                    <tr>
                        <th>Продукт</th>
                        <th>Альтернатива</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Цукерки</td>
                        <td>Фрукти, сухофрукти</td>
                    </tr>
                    <tr>
                        <td>Газовані напої</td>
                        <td>Трав'яний чай, вода з лимоном</td>
                    </tr>
                    <tr>
                        <td>Випічка</td>
                        <td>Хліб з цільного зерна, фрукти</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section>
            <h2>Мапа сайту</h2>
            <img src="sitemap.gif" alt="Карта сайту">
        </section>

        <section>
            <h2>Натхнення</h2>
            <video width="320" height="240" controls>
                <source src="nosugar_motivation.mp4" type="video/mp4">
                Ваш браузер не підтримує відео.
            </video>
        </section>

        <section>
            <h2>Слухайте поради</h2>
            <audio controls>
                <source src="advice.mp3" type="audio/mpeg">
                Ваш браузер не підтримує аудіо елемент.
            </audio>
        </section>

        <section>
            <h2>Форма участі</h2>
            <form id="signupForm">
                <label for="name">Ім'я:</label>
                <input type="text" id="name" name="name" required><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br>

                <input type="submit" value="Долучитись">
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Експеримент "Без цукру"</p>
    </footer>

    <script>
        document.getElementById('signupForm').addEventListener('submit', function(event) {
            event.preventDefault();
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            alert(`Дякуємо, ${name}! Ви зареєстровані з email: ${email}`);
        });
    </script>
</body>
</html>
