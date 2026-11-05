
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Камышанова Елизавета Сергеевна — врач-эндокринолог | Онлайн-приём</title>
<meta name="description" content="Консультация врача-эндокринолога онлайн. Лечение диабета, заболеваний щитовидной железы, коррекция веса. Запись на приём за 1 минуту.">
<style>
  :root{
    --accent:#0e7c66;
    --accent-dark:#0a5c4c;
    --accent-light:#e6f4f0;
    --text:#1d2b28;
    --muted:#5f6f6b;
    --bg:#ffffff;
    --radius:16px;
  }
  *{margin:0;padding:0;box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{font-family:'Segoe UI',Arial,sans-serif;color:var(--text);background:var(--bg);line-height:1.6;}
  .container{max-width:1100px;margin:0 auto;padding:0 20px;}

  /* ---------- Header ---------- */
  header{position:sticky;top:0;background:rgba(255,255,255,.95);backdrop-filter:blur(8px);border-bottom:1px solid #eef2f1;z-index:50;}
  .header-inner{display:flex;align-items:center;justify-content:space-between;padding:14px 0;}
  .logo{font-weight:700;font-size:1.15rem;color:var(--accent);text-decoration:none;}
  nav a{margin-left:24px;color:var(--text);text-decoration:none;font-size:.95rem;}
  nav a:hover{color:var(--accent);}
  .btn{display:inline-block;padding:12px 28px;border-radius:40px;font-weight:600;text-decoration:none;transition:.2s;cursor:pointer;border:none;font-size:1rem;}
  .btn-primary{background:var(--accent);color:#fff;}
  .btn-primary:hover{background:var(--accent-dark);}
  .btn-outline{border:2px solid var(--accent);color:var(--accent);background:transparent;}
  .btn-outline:hover{background:var(--accent-light);}
  @media(max-width:760px){nav{display:none;}}

  /* ---------- Hero ---------- */
  .hero{background:linear-gradient(135deg,#e6f4f0 0%,#f7fbf9 100%);padding:70px 0;}
  .hero-inner{display:flex;align-items:center;gap:40px;flex-wrap:wrap;}
  .hero-text{flex:1 1 420px;}
  .hero h1{font-size:2.4rem;line-height:1.2;margin-bottom:16px;}
  .hero p{color:var(--muted);font-size:1.1rem;margin-bottom:28px;max-width:520px;}
  .hero-badges{display:flex;gap:12px;flex-wrap:wrap;margin-bottom:28px;}
  .badge{background:#fff;border:1px solid #dcebe6;border-radius:30px;padding:6px 14px;font-size:.85rem;color:var(--accent-dark);}
  .hero-photo{flex:0 1 320px;text-align:center;}
  .photo-placeholder{width:280px;height:340px;border-radius:var(--radius);background:linear-gradient(160deg,#bfe3d8,#e9f5f1);display:flex;align-items:center;justify-content:center;color:var(--accent-dark);font-size:.95rem;text-align:center;padding:20px;margin:0 auto;}

  /* ---------- Sections ---------- */
  section{padding:70px 0;}
  .section-title{font-size:1.8rem;margin-bottom:8px;text-align:center;}
  .section-sub{color:var(--muted);text-align:center;margin-bottom:44px;}

  .cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px;}
  .card{background:#f8fbfa;border:1px solid #eaf1ef;border-radius:var(--radius);padding:26px;}
  .card h3{margin-bottom:10px;color:var(--accent-dark);font-size:1.1rem;}
  .card p{color:var(--muted);font-size:.95rem;}

  /* ---------- About ---------- */
  .about{background:var(--accent-light);}
  .about-inner{display:flex;gap:40px;align-items:center;flex-wrap:wrap;}
  .about-text{flex:1 1 420px;}
  .about-text ul{list-style:none;margin-top:16px;}
  .about-text li{padding-left:28px;position:relative;margin-bottom:10px;}
  .about-text li::before{content:"✔";position:absolute;left:0;color:var(--accent);}
  .about-stats{display:flex;gap:30px;margin-top:24px;flex-wrap:wrap;}
  .stat b{display:block;font-size:1.6rem;color:var(--accent);}

  /* ---------- Steps ---------- */
  .steps{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:20px;counter-reset:step;}
  .step{background:#fff;border:1px solid #eaf1ef;border-radius:var(--radius);padding:26px;position:relative;counter-increment:step;}
  .step::before{content:counter(step);display:inline-flex;align-items:center;justify-content:center;width:36px;height:36px;border-radius:50%;background:var(--accent);color:#fff;font-weight:700;margin-bottom:14px;}

  /* ---------- FAQ ---------- */
  details{background:#f8fbfa;border:1px solid #eaf1ef;border-radius:var(--radius);padding:18px 22px;margin-bottom:12px;}
  summary{font-weight:600;cursor:pointer;}
  details p{margin-top:10px;color:var(--muted);}

  /* ---------- Form ---------- */
  .booking{background:linear-gradient(135deg,#0e7c66,#0a5c4c);color:#fff;}
  .booking .section-title,.booking .section-sub{color:#fff;}
  .form-card{background:#fff;color:var(--text);border-radius:var(--radius);padding:34px;max-width:560px;margin:0 auto;box-shadow:0 20px 50px rgba(0,0,0,.15);}
  .form-grid{display:grid;grid-template-columns:1fr 1fr;gap:16px;}
  .form-grid .full{grid-column:1/-1;}
  label{display:block;font-size:.85rem;font-weight:600;margin-bottom:6px;}
  input,select,textarea{width:100%;padding:12px 14px;border:1px solid #d8e4e0;border-radius:10px;font-size:1rem;font-family:inherit;background:#fbfdfc;}
  input:focus,select:focus,textarea:focus{outline:2px solid var(--accent);border-color:var(--accent);}
  .form-card .btn{width:100%;margin-top:20px;}
  .form-note{font-size:.8rem;color:var(--muted);margin-top:14px;text-align:center;}
  .form-success{display:none;text-align:center;padding:20px 0;color:var(--accent-dark);font-weight:600;}
  @media(max-width:560px){.form-grid{grid-template-columns:1fr;}}

  /* ---------- Footer ---------- */
  footer{background:#12241f;color:#cfe3dc;padding:40px 0;font-size:.9rem;}
  footer a{color:#9fd8c6;}
  .footer-inner{display:flex;justify-content:space-between;gap:20px;flex-wrap:wrap;}
</style>
</head>
<body>

<header>
  <div class="container header-inner">
    <a href="#" class="logo">Камышанова Елизавета · эндокринолог</a>
    <nav>
      <a href="#services">Услуги</a>
      <a href="#about">Обо мне</a>
      <a href="#steps">Как всё проходит</a>
      <a href="#faq">Вопросы</a>
    </nav>
    <a href="#booking" class="btn btn-primary">Записаться</a>
  </div>
</header>

<!-- HERO -->
<section class="hero">
  <div class="container hero-inner">
    <div class="hero-text">
      <h1>Забота о гормонах —<br>из любой точки мира</h1>
      <p>Врач-эндокринолог. Онлайн-консультации по диабету, щитовидной железе, весу и гормональному здоровью. Разбор анализов и понятный план действий.</p>
      <div class="hero-badges">
        <span class="badge">Стаж 8 лет</span>
        <span class="badge">Приём в МАХ / WhatsApp</span>
      </div>
      <a href="#booking" class="btn btn-primary">Записаться на приём</a>
    </div>
    <div class="hero-photo">
      <!-- Замените этот блок на <img src="ваше-фото.jpg"> с портретом врача -->
      <div class="photo-placeholder">Здесь будет фото врача<br>(рекомендуется 3:4, 600×800 px)</div>
    </div>
  </div>
</section>

<!-- SERVICES -->
<section id="services">
  <div class="container">
    <h2 class="section-title">С чем я помогаю</h2>
    <p class="section-sub">Первичный приём — 40 минут. Повторный — 25 минут.</p>
    <div class="cards">
      <div class="card"><h3>Диабет 1 и 2 типа</h3><p>Подбор и коррекция терапии, обучение самоконтролю, разбор гликемического профиля.</p></div>
      <div class="card"><h3>Щитовидная железа</h3><p>Тиреоидиты, гипо- и гипертиреоз, узлы, интерпретация УЗИ и гормональных анализов.</p></div>
      <div class="card"><h3>Коррекция веса</h3><p>Метаболический синдром, инсулинорезистентность, современная фармакотерапия ожирения.</p></div>
      <div class="card"><h3>Анализы «под ключ»</h3><p>Составлю список нужных исследований до приёма и подробно расшифрую результаты после.</p></div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section class="about" id="about">
  <div class="container about-inner">
    <div class="about-text">
      <h2 class="section-title" style="text-align:left">Обо мне</h2>
      <p>Окончила университет, 8 лет практики в эндокринологии. Регулярно прохожу усовершенствование по диабетологии и тиреоидологии.</p>
      <ul>
        <li>Специалист по непрерывному мониторингу глюкозы</li>
        <li>Веду пациентов онлайн с 2020 года — из 40+ городов</li>
      </ul>
      <div class="about-stats">
        <div class="stat"><b>3 500+</b>консультаций</div>
        <div class="stat"><b>8 лет</b>стажа</div>
        <div class="stat"><b>4.9 / 5</b>средняя оценка</div>
      </div>
    </div>
  </div>
</section>

<!-- STEPS -->
<section id="steps">
  <div class="container">
    <h2 class="section-title">Как проходит приём</h2>
    <p class="section-sub">Всё занимает от записи до плана лечения — один день</p>
    <div class="steps">
      <div class="step"><h3>Запись</h3><p>Оставляете заявку — я или ассистент подтверждаю время в течение часа в рабочее время.</p></div>
      <div class="step"><h3>Подготовка</h3><p>Присылаю ссылку на видеозвонок и перечень анализов, если они нужны для консультации.</p></div>
      <div class="step"><h3>Консультация</h3><p>40 минут онлайн: разбираем жалобы, анализы, историю. Вы получаете письменное заключение.</p></div>
      <div class="step"><h3>Сопровождение</h3><p>Неделя переписки по лечению включена в стоимость. Повторный приём — по графику.</p></div>
    </div>
  </div>
</section>

<!-- FAQ -->
<section id="faq">
  <div class="container">
    <h2 class="section-title">Частые вопросы</h2>
    <p class="section-sub">Не нашли ответ? Напишите мне — отвечу до записи.</p>
    <details><summary>Нужны ли анализы до первой консультации?</summary><p>Желательно иметь свежие результаты (за 1–3 месяца): ТТГ, свободный Т4, глюкозу или HbA1c. Если анализов нет — подберу минимальный список на приёме.</p></details>
    <details><summary>Как проходит оплата?</summary><p>Предоплата онлайн по ссылке после подтверждения записи. Чек приходит на электронную почту.</p></details>
    <details><summary>Можно ли по моим документам получить вычет НДФЛ?</summary><p>Да, предоставляю справку об оплате медуслуг для налогового вычета.</p></details>
    <details><summary>Что если опоздать или отменить запись?</summary><p>Бесплатная отмена и перенос — не позднее чем за 12 часов до приёма.</p></details>
  </div>
</section>

<!-- BOOKING -->
<section class="booking" id="booking">
  <div class="container">
    <h2 class="section-title">Запись на онлайн-приём</h2>
    <p class="section-sub">Заполните форму — свяжусь с вами в течение рабочего дня</p>
    <div class="form-card">
      <form id="bookingForm" novalidate>
        <div class="form-grid">
          <div class="full">
            <label for="name">Имя *</label>
            <input type="text" id="name" name="name" required placeholder="Как к вам обращаться">
          </div>
          <div>
            <label for="phone">Телефон *</label>
            <input type="tel" id="phone" name="phone" required placeholder="+7 (___) ___-__-__">
          </div>
          <div>
            <label for="topic">Тема обращения</label>
            <select id="topic" name="topic">
              <option>Диабет</option>
              <option>Щитовидная железа</option>
              <option>Коррекция веса</option>
              <option>Другое / разбор анализов</option>
            </select>
          </div>
          <div class="full">
            <label for="when">Удобное время</label>
            <input type="text" id="when" name="when" placeholder="Например: будни после 18:00">
          </div>
          <div class="full">
            <label for="comment">Комментарий</label>
            <textarea id="comment" name="comment" rows="3" placeholder="Кратко опишите ситуацию"></textarea>
          </div>
        </div>
        <button type="submit" class="btn btn-primary">Отправить заявку</button>
        <p class="form-note">Отправляя форму, вы соглашаетесь с политикой обработки персональных данных.</p>
        <p class="form-success" id="formSuccess">Спасибо! Заявка отправлена — скоро с вами свяжусь. 💚</p>
      </form>
    </div>
  </div>
</section>

<footer>
  <div class="container footer-inner">
    <div>
      <div class="logo" style="color:#9fd8c6;margin-bottom:8px;">Камышанова Елизавета · эндокринолог</div>
      <p>ИП Камышанова Е.С. · ИНН 000000000000 (замените на свои реквизиты)</p>
    </div>
    <div>
      <p>Тел: <a href="tel:+79000000000">+7 953 088-24-77</a></p>
      <p>Почта: <a href="mailto:doctor@example.ru">doctor@example.ru</a></p>
      <p>Telegram / WhatsApp (добавьте свои ссылки)</p>
    </div>
  </div>
</footer>

<script>
// ---- Демо-обработчик формы ----
// Чтобы заявки приходили вам, замените этот блок на один из вариантов:
// 1) <form action="https://formspree.io/f/ВАШ_ID" method="POST"> — simplest, без кода
// 2) отправка на ваш backend / Telegram-бот
// 3) готовый виджет записи (YCLIENTS, DIKIDI) — вставляется одной строкой вместо этой формы
document.getElementById('bookingForm').addEventListener('submit', function(e){
  e.preventDefault();
  const name  = document.getElementById('name');
  const phone = document.getElementById('phone');
  let ok = true;
  [name, phone].forEach(f => {
    if(!f.value.trim()){ f.style.borderColor = '#d9534f'; ok = false; }
    else f.style.borderColor = '#d8e4e0';
  });
  if(!ok) return;
  // Здесь можно отправить данные: fetch('ваш-endpoint', {method:'POST', body:new FormData(this)})
  console.log('Заявка:', Object.fromEntries(new FormData(this)));
  this.querySelectorAll('.form-grid, .btn, .form-note').forEach(el => el.style.display='none');
  document.getElementById('formSuccess').style.display = 'block';
});
</script>

</body>
</html>
