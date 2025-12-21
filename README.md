<!doctype html>
<html lang="he" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>VTM</title>
  <style>
    body{margin:0;font-family:Arial,Helvetica,sans-serif;background:#f6f7fb;color:#111}
    .wrap{max-width:900px;margin:0 auto;padding:28px 16px}
    .hero{background:#fff;border:1px solid #eee;border-radius:18px;padding:22px}
    .tag{display:inline-block;background:#eef2ff;border:1px solid #e3e8ff;padding:6px 10px;border-radius:999px;font-size:14px}
    h1{margin:12px 0 6px}
    p{margin:8px 0;line-height:1.8;color:#333}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:12px;margin-top:14px}
    .card{background:#fff;border:1px solid #eee;border-radius:16px;padding:16px}
    .btns{display:flex;gap:10px;flex-wrap:wrap;margin-top:14px}
    .btn{display:inline-block;text-decoration:none;border-radius:12px;padding:10px 14px;border:1px solid #ddd;background:#fff;color:#111}
    .btn.primary{border-color:#111;background:#111;color:#fff}
    footer{opacity:.7;margin-top:18px;font-size:13px}
  </style>
</head>
<body>
  <div class="wrap">
    <div class="hero">
      <span class="tag">משקיעים יקרים</span>
      <h1>VTM</h1>
      <p>האתר שלי כרגע בשיפוצים — אבל הוא כבר באוויר. כאן יופיעו פרויקטים, קישורים ועדכונים.</p>

      <div class="btns">
        <a class="btn primary" href="#projects">לפרויקטים</a>
        <a class="btn" href="#contact">צור קשר</a>
      </div>
    </div>

    <div class="grid" id="projects">
      <div class="card">
        <h2>📌 פרויקט 1</h2>
        <p>תיאור קצר (שורה-שתיים) על מה עשית.</p>
        <a class="btn" href="#" onclick="return false;">קישור (עוד מעט)</a>
      </div>

      <div class="card">
        <h2>📌 פרויקט 2</h2>
        <p>תיאור קצר נוסף.</p>
        <a class="btn" href="#" onclick="return false;">קישור (עוד מעט)</a>
      </div>

      <div class="card" id="contact">
        <h2>✉️ יצירת קשר</h2>
        <p>אפשר לשים כאן מייל / אינסטגראם / דיסקורד.</p>
        <p><a class="btn" href="mailto:your@email.com">שלחו לי מייל</a></p>
      </div>
    </div>

    <footer>נבנה עם GitHub Pages • © <span id="y"></span></footer>
  </div>

  <script>
    document.getElementById('y').textContent = new Date().getFullYear();
  </script>
</body>
</html>
