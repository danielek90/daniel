<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Interior Concept - Daniel Woźniak</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #2c3e50;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    nav {
      text-align: center;
      background-color: #34495e;
      padding: 10px 0;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: 0 auto;
    }
    h2 {
      color: #2c3e50;
    }
    .gallery img {
      width: 30%;
      margin: 1.5%;
      border-radius: 8px;
    }
    form input, form textarea {
      display: block;
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
    }
    form button {
      padding: 10px 20px;
      background-color: #2c3e50;
      color: white;
      border: none;
      cursor: pointer;
    }
    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Interior Concept - Daniel Woźniak</h1>
    <p>Stolarstwo z pasją i precyzją</p>
  </header>

  <nav>
    <a href="#o-nas">O nas</a>
    <a href="#uslugi">Usługi</a>
    <a href="#galeria">Galeria</a>
    <a href="#kontakt">Kontakt</a>
  </nav>

  <section id="o-nas">
    <h2>O nas</h2>
    <p>
      Jesteśmy firmą stolarską z wieloletnim doświadczeniem w projektowaniu i wykonywaniu mebli na wymiar. Specjalizujemy się w aranżacjach wnętrz, kuchniach, szafach wnękowych, schodach i elementach dekoracyjnych.
    </p>
  </section>

  <section id="uslugi">
    <h2>Nasze usługi</h2>
    <ul>
      <li>Meble kuchenne na wymiar</li>
      <li>Szafy wnękowe i garderoby</li>
      <li>Schody drewniane</li>
      <li>Panele ścienne, zabudowy i dekoracje</li>
      <li>Doradztwo i projektowanie wnętrz</li>
    </ul>
  </section>

  <section id="galeria">
    <h2>Galeria realizacji</h2>
    <div class="gallery">
      <img src="example1.jpg" alt="Projekt 1" />
      <img src="example2.jpg" alt="Projekt 2" />
      <img src="example3.jpg" alt="Projekt 3" />
    </div>
  </section>

  <section id="kontakt">
    <h2>Kontakt</h2>
    <p>Masz pytania? Skontaktuj się z nami!</p>
    <form>
      <input type="text" name="name" placeholder="Twoje imię" required />
      <input type="email" name="email" placeholder="Twój email" required />
      <textarea name="message" placeholder="Wiadomość" rows="5" required></textarea>
      <button type="submit">Wyślij</button>
    </form>
    <p><strong>Telefon:</strong> 123-456-789</p>
    <p><strong>Email:</strong> kontakt@interiorconcept.pl</p>
    <p><strong>Adres:</strong> ul. Przykładowa 10, 00-000 Miasto</p>
  </section>

  <footer>
    <p>&copy; 2025 Interior Concept - Daniel Woźniak. Wszelkie prawa zastrzeżone.</p>
  </footer>
</body>
</html>
