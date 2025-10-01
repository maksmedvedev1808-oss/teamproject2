<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Сторінка з меню навігації</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.5;
      padding: 20px;
    }

    header, nav, main, footer, section {
      margin-bottom: 20px;
      padding: 12px;
      border: 1px solid #ec1111ff;
      border-radius: 8px;
    }

    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      gap: 12px;
    }

    nav a {
      text-decoration: none;
      padding: 6px 12px;
      background: #f5f5f5;
      border-radius: 6px;
    }

    a:focus, button:focus, input:focus, [tabindex]:focus {
      outline: 3px solid #0077ff;
      outline-offset: 3px;
      background: #e0f0ff;
    }

    .skip-link {
      position: absolute;
      left: -999px;
      top: auto;
      width: 1px;
      height: 1px;
      overflow: hidden;
    }

    .skip-link:focus {
      left: 10px;
      top: 10px;
      width: auto;
      height: auto;
      padding: 8px 12px;
      background: #0077ff;
      color: #fff;
      border-radius: 6px;
      z-index: 1000;
    }

    form label {
      display: block;
      margin-top: 8px;
    }
  </style>
</head>
<body>
  <a href="#main" class="skip-link">Перейти до контенту</a>

  <header>
    <h1>Hero Working</h1>
    <nav aria-label="Головне меню">
      <ul>
        <li><a href="#main">Головна</a></li>
        <li><a href="#about">Про нас</a></li>
        <li><a href="#services">Послуги</a></li>
        <li><a href="#contact">Контакти</a></li>
      </ul>
    </nav>
  </header>

  <main id="main">
    <h2>Основний контент</h2>
    <p>Спробуйте переміщатись клавішею Tab. Фокус буде видно завжди.</p>

    <section id="general-form">
      <h3>Форма зворотного зв’язку</h3>
      <form>
        <label>Ім'я:
          <input type="text" name="name">
        </label>

        <label>Email:
          <input type="email" name="email">
        </label>

        <button type="submit">Надіслати</button>
      </form>
    </section>

    <section id="links">
      <h3>Додаткові посилання</h3>
      <p><a href="#extra" tabindex="0">Додаткове посилання (tabindex=0)</a></p>
      <p><a href="#hidden" tabindex="-1">Цей лінк пропускається в Tab (tabindex=-1)</a></p>
    </section>

    <section id="about">
      <h2>Про нас</h2>
      <p>Тут буде інформація про компанію.</p>
    </section>

    <section id="services">
      <h2>Послуги</h2>
      <p>Опис послуг.</p>
    </section>

    <section id="contact">
      <h2>Контакти</h2>
      <form>
        <label for="name-contact">Ваше ім’я:</label>
        <input type="text" id="name-contact" name="name" required>

        <label for="email-contact">Ваш Email:</label>
        <input type="email" id="email-contact" name="email" required>

        <button type="submit">Надіслати</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Мій сайт</p>
  </footer>
</body>
</html>
