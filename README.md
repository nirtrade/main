<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MirMind - מוצרים לוולנס</title>
  <style>
    body {
      margin: 0;
      font-family: 'Assistant', sans-serif;
      background: #f5f5f5;
      color: #333;
      direction: rtl;
      text-align: center;
    }
    header {
      background: linear-gradient(to left, #a8edea, #fed6e3);
      padding: 60px 20px;
    }
    header h1 {
      margin: 0;
      font-size: 48px;
      color: #2c3e50;
    }
    header p {
      font-size: 20px;
      margin-top: 10px;
      color: #34495e;
    }
    .cta-button {
      margin-top: 30px;
      padding: 15px 30px;
      font-size: 18px;
      background-color: #27ae60;
      color: white;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    .cta-button:hover {
      background-color: #219150;
    }
    section {
      padding: 40px 20px;
    }
    .features {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 30px;
      margin-top: 30px;
    }
    .feature {
      background: white;
      padding: 20px;
      border-radius: 16px;
      width: 250px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .feature h3 {
      margin-top: 0;
      color: #2c3e50;
    }
    form {
      margin-top: 40px;
      background-color: #ffffff;
      padding: 30px;
      border-radius: 16px;
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    form input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 8px;
    }
    form button {
      padding: 12px 20px;
      background-color: #27ae60;
      color: white;
      border: none;
      border-radius: 30px;
      cursor: pointer;
    }
    form button:hover {
      background-color: #219150;
    }
    footer {
      background-color: #2c3e50;
      color: white;
      padding: 20px;
      font-size: 14px;
    }
    .contact-email {
      margin-top: 20px;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <header>
    <h1>MirMind</h1>
    <p>מוצרים לוולנס וחיים מודעים יותר</p>
    <button class="cta-button" onclick="location.href='https://yourshoplink.com'">בקרו בחנות שלנו</button>
  </header>

  <section>
    <h2>למה MirMind?</h2>
    <div class="features">
      <div class="feature">
        <h3>🌿 טבעי</h3>
        <p>מוצרים ידידותיים לסביבה באיכות גבוהה</p>
      </div>
      <div class="feature">
        <h3>🧘 מדיטטיבי</h3>
        <p>תמיכה בנשימה מודעת ורוגע יומיומי</p>
      </div>
      <div class="feature">
        <h3>✨ מעוצב</h3>
        <p>סטייל אלגנטי שילווה אותך כל יום</p>
      </div>
    </div>

    <form action="mailto:trade.nir2025@gmail.com" method="post" enctype="text/plain">
      <h3>רוצים לשמוע מאיתנו? השאירו פרטים:</h3>
      <input type="text" name="first_name" placeholder="שם פרטי" required>
      <input type="text" name="last_name" placeholder="שם משפחה" required>
      <input type="email" name="email" placeholder="כתובת מייל" required>
      <button type="submit">שלח</button>
    </form>
  </section>

  <footer>
    &copy; 2025 MirMind. כל הזכויות שמורות.<br>
    <div class="contact-email">יצירת קשר: <a href="mailto:trade.nir2025@gmail.com" style="color: #a8edea;">trade.nir2025@gmail.com</a></div>
  </footer>
</body>
</html>
