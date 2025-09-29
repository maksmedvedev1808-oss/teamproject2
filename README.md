 <!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Сторінка з меню навігації</title>
</head>
<body>
  <header>
    <h1>hero working </h1>
    <nav aria-label="Головне меню">
      <ul>
        <li><a href="#home">Головна</a></li>
        <li><a href="#about">Про нас</a></li>
        <li><a href="#services">Послуги</a></li>
        <li><a href="#contact">Контакти</a></li>
      </ul>
    </nav>
  </header>

  <main id="home">
    <section id="about">
      <h2>Про нас</h2>
      <p>Тут буде інформація про компанію</p>
    </section>

    <section id="services">
      <h2>Послуги</h2>
      <p>Опис послуг</p>
    </section>

    <section id="contact">
      <h2>Контакти</h2>
      <form>
        <label for="name">Ваше ім’я:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Ваш Email:</label>
        <input type="email" id="email" name="email" required>

        <button type="submit">Надіслати</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Мій сайт</p>
  </footer>
</body>
</html>


