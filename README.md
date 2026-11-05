<!-- <!DOCTYPE html> -->
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Врач-эндокринолог Камышанова Е.С. — онлайн-приём</title>
    <style>
        :root {
            --primary: #4a90e2;
            --dark: #2c3e50;
            --light: #f4f7f6;
            --white: #ffffff;
            --radius: 12px;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: var(--dark);
            line-height: 1.6;
            background: var(--light);
        }

        /* Header */
        header {
            background: var(--white);
            padding: 1rem 1.5rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 6px rgba(0,0,0,0.06);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .logo {
            font-weight: 700;
            font-size: 1.25rem;
            color: var(--primary);
        }
        nav a {
            margin-left: 1rem;
            text-decoration: none;
            color: var(--dark);
            font-weight: 500;
            display: none; /* скрываем ссылки на мобильных */
        }
        @media (min-width: 768px) {
            nav a { display: inline-block; }
        }
        .btn {
            background: var(--primary);
            color: var(--white);
            padding: 0.7rem 1.4rem;
            border-radius: var(--radius);
            text-decoration: none;
            font-weight: 600;
            transition: background 0.2s;
            display: inline-block;
        }
        .btn:hover { background: #357abd; }

        /* Hero */
        .hero {
            padding: 3rem 1.5rem;
            text-align: center;
            background: linear-gradient(135deg, #eef2f5, #ffffff);
        }
        .hero h1 {
            font-size: 2.2rem;
            margin-bottom: 1rem;
            color: var(--dark);
        }
        .doctor-img-wrapper {
            display: inline-block;
            max-width: 100%;
            margin-bottom: 1.5rem;
        }
        .doctor-img {
            width: 100%;
            max-width: 240px;
            height: auto;
            border-radius: var(--radius);
            object-fit: cover;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        .hero p {
            font-size: 1.1rem;
            color: #555;
            max-width: 600px;
            margin: 0 auto 2rem auto;
        }

        section { padding: 3rem 1.5rem; }
        h2 {
            text-align: center;
            font-size: 1.8rem;
            margin-bottom: 2rem;
            color: var(--dark);
        }

        /* Grid cards */
        .grid-3 {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
            gap: 1.5rem;
        }
        .card {
            background: var(--white);
            padding: 1.5rem;
            border-radius: var(--radius);
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }
        .card h3 { margin-top: 0; color: var(--primary); }

        /* About */
        .about-container {
            max-width: 900px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 3rem;
            align-items: start;
        }
        .certs-img {
            width: 100%;
            border-radius: var(--radius);
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }
        @media (max-width: 768px) {
            .about-container { grid-template-columns: 1fr; }
            .hero h1 { font-size: 1.9rem; }
        }

        /* Form */
        form {
            max-width: 600px;
            margin: 0 auto;
            background: var(--white);
            padding: 2rem;
            border-radius: var(--radius);
            box-shadow: 0 6px 20px rgba(0,0,0,0.08);
        }
        .form-group { margin-bottom: 1rem; }
        label {
            display: block;
            margin-bottom: 0.4rem;
            font-weight: 500;
        }
        input, textarea, select {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ccc;
            border-radius: 8px;
            font: inherit;
            box-sizing: border-box;
        }
        textarea { resize: vertical; min-height: 100px; }

        footer {
            background: var(--dark);
            color: var(--white);
            padding: 2rem 1.5rem;
            text-align: center;
        }
        .legal {
            font-size: 0.85rem;
            opacity: 0.8;
            margin-top: 1.5rem;
        }

        /* Mobile CTA button (sticky at bottom on mobile) */
        @media (max-width: 768px) {
            .mobile-cta {
                position: fixed;
                bottom: 0;
                left: 0;
                width: 100%;
                padding: 1rem;
                background: var(--white);
                border-top: 1px solid #eee;
                text-align: center;
                box-shadow: 0 -4px 16px rgba(0,0,0,0.04);
                z-index: 999;
            }
            .mobile-cta .btn {
                width: 100%;
                text-align: center;
            }
        }
    </style>
</head>
<body>

<header>
    <div class="logo">Камышанова Е.С.</div>
    <nav>
        <a href="#services">Услуги</a>
        <a href="#about">Обо мне</a>
        <a href="#faq">FAQ</a>
    </nav>
    <!-- Кнопка в шапке (видна на ПК) -->
    <a href="#contact" class="btn">Записаться</a>
</header>

<!-- Мобильная кнопка внизу экрана -->
<div class="mobile-cta">
    <a href="#contact" class="btn">Записаться на приём</a>
</div>

<section class="hero">
    <div class="doctor-img-wrapper">
        <!-- Замените src на путь к фото: images/doctor.jpg -->
        <img src="doctor.jpg" alt="Камышанова Елизавета Сергеевна, врач-эндокринолог" class="doctor-img">
    </div>
    <h1>Камышанова Елизавета Сергеевна<br>Врач-эндокринолог</h1>
    <p>Онлайн-консультации по вопросам щитовидной железы, диабета, коррекции веса и гормонального фона. Приём с разбором анализов и персональными рекомендациями.</p>
    <a href="#contact" class="btn" style="padding: 1rem 2rem; font-size: 1.1rem;">Записаться на приём</a>
</section>

<section id="services">
    <h2>Услуги</h2>
    <div class="grid-3">
        <div class="card">
            <h3>Консультация по щитовидной железе</h3>
            <p>Оценка состояния, интерпретация анализов, подбор плана наблюдения и коррекции.</p>
        </div>
        <div class="card">
            <h3>Диабетология и инсулинорезистентность</h3>
            <p>Разбор углеводного обмена, рекомендации по питанию и образу жизни, контроль показателей.</p>
        </div>
        <div class="card">
            <h3>Коррекция веса и метаболизма</h3>
            <p>Анализ гормональных причин набора веса, индивидуальный план коррекции и контроля.</p>
        </div>
        <div class="card">
            <h3>Разбор анализов и динамики</h3>
            <p>Интерпретация лабораторных данных, оценка динамики и прогноз изменений.</p>
        </div>
        <div class="card">
            <h3>Повторные приёмы и сопровождение</h3>
            <p>Контроль терапии, коррекция дозировок, ответы на вопросы в динамике.</p>
        </div>
        <div class="card">
            <h3>Рекомендации по образу жизни</h3>
            <p>Индивидуальные советы по питанию, физической нагрузке и режиму дня.</p>
        </div>
    </div>
</section>

<section id="about">
    <h2>О враче</h2>
    <div class="about-container">
        <div>
            <p><strong>Камышанова Елизавета Сергеевна</strong> — врач-эндокринолог с клиническим опытом более 8 лет. Специализируется на диагностике и терапии заболеваний эндокринной системы, коррекции метаболических нарушений и сопровождении пациентов в долгосрочной динамике.</p>
            <p>Регулярно повышает квалификацию, участвует в профильных конференциях, ориентируется на доказательную медицину и индивидуальный подход к каждому пациенту.</p>
            <ul style="margin-top: 1rem;">
                <li>✅ Стаж: более 8 лет</li>
                <li>✅ Более 1 200 консультаций</li>
                <li>✅ Специализация: щитовидная железа, диабет, вес, гормоны</li>
            </ul>
        </div>
        <div>
            <!-- Замените src на путь к сертификатам: images/certs.jpg -->
            <img src="diplom.jpg" alt="Сертификаты и дипломы Камышановой Е.С." class="certs-img">
        </div>
    </div>
</section>

<section id="faq">
    <h2>Часто задаваемые вопросы</h2>
    <details style="max-width: 600px; margin: 0 auto;">
        <summary style="cursor: pointer; font-weight: 600; padding: 1rem 0;">Как проходит онлайн-приём?</summary>
        <p style="padding: 0 1rem 1rem 1rem;">Приём проходит по видеосвязи (Telegram/WhatsApp/Zoom). Перед консультацией вы отправляете анализы и жалобы, на приёме врач задаёт уточняющие вопросы, даёт рекомендации и при необходимости назначает дополнительные исследования.</p>
    </details>
    <details style="max-width: 600px; margin: 1rem auto;">
        <summary style="cursor: pointer; font-weight: 600; padding: 1rem 0;">Нужна ли подготовка к консультации?</summary>
        <p style="padding: 0 1rem 1rem 1rem;">Да: желательно прислать результаты анализов (ТТГ, Т4, глюкоза, инсулин и др.) и список жалоб. Это сэкономит время на приёме и сделает консультацию более точной.</p>
    </details>
    <details style="max-width: 600px; margin: 1rem auto;">
        <summary style="cursor: pointer; font-weight: 600; padding: 1rem 0;">Можно ли получить заключение и назначения?</summary>
        <p style="padding: 0 1rem 1rem 1rem;">По итогам приёма вы получаете письменное заключение с рекомендациями. Назначение лекарств и коррекция терапии возможны только при наличии показаний и после оценки состояния.</p>
    </details>
</section>

<section id="contact">
    <h2>Записаться на онлайн-приём</h2>
    <form id="appointment-form">
        <div class="form-group">
            <label for="name">Ваше имя</label>
            <input type="text" id="name" name="name" required placeholder="Иван Иванов">
        </div>
        <div class="form-group">
            <label for="phone">Телефон</label>
            <input type="tel" id="phone" name="phone" required placeholder="+7 (999) 000-00-00">
        </div>
        <div class="form-group">
            <label for="topic">Тема обращения</label>
            <select id="topic" name="topic">
                <option value="щитовидная железа">Щитовидная железа</option>
                <option value="диабет">Диабет / инсулинорезистентность</option>
                <option value="вес">Коррекция веса / метаболизм</option>
                <option value="анализы">Разбор анализов</option>
                <option value="другое">Другое</option>
            </select>
        </div>
        <div class="form-group">
            <label for="time">Удобное время</label>
            <input type="text" id="time" name="time" placeholder="Например: пн, 18:00">
        </div>
        <div class="form-group">
            <label for="comment">Комментарий / анализы</label>
            <textarea id="comment" name="comment" placeholder="Кратко опишите жалобы и прикрепите список анализов"></textarea>
        </div>
        <button type="submit" class="btn" style="width: 100%;">Отправить заявку</button>
        <p style="font-size: 0.85rem; text-align: center; margin-top: 0.8rem;">Нажимая кнопку, вы соглашаетесь с политикой обработки персональных данных.</p>
    </form>
</section>

<footer>
    <p>Камышанова Елизавета Сергеевна, врач-эндокринолог</p>
    <p>Контакты: +7 (XXX) XXX-XX-XX | email@example.com</p>
    <p class="legal">
        Консультация носит информационный характер и не является медицинской помощью. Для постановки диагноза и назначения лечения необходима очная консультация врача. Имеются противопоказания. Необходима консультация специалиста.
    </p>
</footer>

<script>
    document.getElementById('appointment-form').addEventListener('submit', function (e) {
        e.preventDefault();
        alert('Спасибо! Ваша заявка на приём к Камышановой Елизавете Сергеевне принята. Мы свяжемся с вами в ближайшее время.');
        this.reset();
    });
</script>

</body>
</html>
