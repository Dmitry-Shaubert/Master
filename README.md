<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Мастер на час — быстрый и профессиональный ремонт сантехники, электромонтажные работы, сборка мебели и другие бытовые услуги.">
    <meta name="keywords" content="мастер на час, ремонт сантехники, электромонтажные работы, сборка мебели, услуги сварки, плотницкие работы">
    <meta name="author" content="Мастер на час">
    <link rel="icon" type="image/png" href="images/favicon.png">
    <title>Мастер на час</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
            scroll-behavior: smooth; /* Плавная прокрутка */
        }
        header {
            background-color: #ffffff;
            color: #333;
            padding: 20px 0;
            text-align: center;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .logo img {
            width: 300px;
            height: auto;
            margin-right: 20px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #e0e0e0;
        }
        nav a {
            color: #333;
            padding: 14px 20px;
            text-decoration: none;
            display: block;
            transition: background-color 0.3s ease;
        }
        nav a:hover {
            background-color: #d0d0d0;
        }
        .container {
            padding: 20px;
            background-color: #e0e0e0;
            max-width: 900px;
            margin: 0 auto;
        }
        footer {
            background-color: #c0c0c0;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            width: 100%;
        }
        section {
            margin-bottom: 40px;
            background-color: #ffffff;
            padding: 20px;
            border-radius: 5px;
        }
        h1, h2 {
            color: #333;
            font-weight: bold;
            margin-bottom: 20px;
        }
        h2 {
            font-size: 1.8em;
        }
        p {
            font-size: 1em;
            line-height: 1.8;
        }
        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
        li {
            margin-bottom: 10px;
            line-height: 1.6;
        }
        .service-image img {
            max-width: 35%;
            height: auto;
            margin-top: 10px;
            border-radius: 5px;
        }
        .contact-phone, .contact-email {
            font-size: 1.2em;
            font-weight: bold;
            margin-top: 20px;
        }
        .contact-links {
            margin-top: 10px;
        }
        .contact-links a {
            display: inline-block;
            margin-right: 10px;
            color: #333;
            text-decoration: none;
            font-weight: bold;
        }
        .contact-links a:hover {
            text-decoration: underline;
        }
        #scrollToTop {
            position: fixed;
            bottom: 20px;
            right: 20px;
            padding: 10px;
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
            display: none;
        }
        .feedback-form {
            margin-top: 20px;
        }
        .feedback-form input, .feedback-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .feedback-form button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .feedback-form button:hover {
            background-color: #555;
        }

        /* Адаптивность для мобильных устройств */
        @media (max-width: 768px) {
            header {
                flex-direction: column;
                align-items: flex-start;
            }
            .logo img {
                width: 150px;
                margin-right: 0;
                margin-bottom: 10px;
            }
            nav {
                flex-direction: column;
                align-items: center;
            }
            nav a {
                width: 100%;
                text-align: center;
                padding: 10px 0;
            }
            .container {
                padding: 10px;
            }
            h1 {
                font-size: 1.5em;
            }
            h2 {
                font-size: 1.3em;
            }
            p {
                font-size: 0.9em;
            }
        }
    </style>
</head>
<body>

<header>
    <div class="logo">
        <img src="images/logo.png" alt="Логотип мастера на час" width="300" height="auto">
    </div>
    <h1>Мастер на час</h1>
</header>

<nav>
    <a href="#home" aria-label="Перейти на главную страницу">Главная</a>
    <a href="#services" aria-label="Перейти к списку услуг">Услуги</a>
    <a href="#about" aria-label="Перейти к информации о нас">О нас</a>
    <a href="#contacts" aria-label="Перейти к контактной информации">Контакты</a>
    <a href="#feedback" aria-label="Перейти к форме обратной связи">Обратная связь</a>
</nav>

<div class="container">
    <section id="home">
        <h2>"Мастер на час: быстрое решение всех ваших бытовых проблем!"</h2>
        <p>Ваш дом — это ваше убежище, но иногда даже самые незначительные проблемы могут вызвать стресс. Не беспокойтесь! Наша услуга "Мастер на час" поможет вам справиться с любыми мелкими бытовыми задачами быстро и профессионально.</p>
    </section>

    <section id="services">
        <h2>Что мы делаем?</h2>
        <p>Наш мастер может выполнить огромный спектр работ:</p>
        <ul>
            <li><strong>Ремонт сантехники:</strong> Устранение протечек, замена смесителей, установка раковин и ванных принадлежностей. Прокладка различных трубопроводов. Установка дополнительного сантехнического оборудования
                <div class="service-image">
                    <img src="images/repair_plumbing.png" alt="Ремонт сантехники" width="300" height="auto">
                </div>
            </li>
            <li><strong>Электромонтажные работы:</strong> Замена розеток, выключателей, лампочек, а также установка осветительных приборов и других электрических устройств. Монтаж проводки.
                <div class="service-image">
                    <img src="images/electrical_works.png" alt="Электромонтажные работы" width="300" height="auto">
                </div>
            </li>
            <li><strong>Мебельный ремонт:</strong> Ремонт сломанных деталей мебели, замена фурнитуры, восстановление повреждённых поверхностей.
                <div class="service-image">
                    <img src="images/furniture_repair.png" alt="Мебельный ремонт" width="300" height="auto">
                </div>
            </li>
            <li><strong>Сборка мебели:</strong> Быстрая и качественная сборка новой мебели, будь то шкафы, столы или кровати. Монтаж.
                <div class="service-image">
                    <img src="images/assembly_furniture.png" alt="Сборка мебели" width="300" height="auto">
                </div>
            </li>
            <li><strong>Услуги сварки:</strong> Выполнение различных сварочных работ, таких как ремонт металлических конструкций, изготовление кованых изделий, сварка труб и многое другое.
                <div class="service-image">
                    <img src="images/welding_services.png" alt="Услуги сварки" width="300" height="auto">
                </div>
            </li>
            <li><strong>Плотницкие работы:</strong> Изготовление и ремонт деревянных конструкций, напольных покрытий и многое другое.
                <div class="service-image">
                    <img src="images/carpentry_works.png" alt="Плотницкие работы" width="300" height="auto">
                </div>
            </li>
        </ul>
        <p>Если у вас возникла проблема, которая не входит в наш перечень услуг, но вам всё равно нужна помощь, просто сообщите нам об этом, и мы постараемся её решить!</p>
    </section>

    <section id="about">
        <h2>Почему выбирают нас?</h2>
        <ul>
            <li><strong>Быстро:</strong> Мы приедем к вам в течение 1-2 часов после вашего звонка.</li>
            <li><strong>Профессионально:</strong> Наши мастера имеют большой опыт и знают, как решать любые бытовые задачи.</li>
            <li><strong>Универсально:</strong> Один мастер может выполнить множество разных работ.</li>
            <li><strong>Прозрачные цены:</strong> Вы платите только за конкретную работу, никаких скрытых дополнительных расходов.</li>
            <li><strong>Комфортно:</strong> Вам не нужно думать о инструментах — наш мастер привезёт всё необходимое с собой.</li>
            <li><strong>Для организаций:</strong> Мы также предоставляем наши услуги для коммерческих и государственных учреждений, обеспечивая высокий уровень обслуживания и оперативное решение задач любой сложности.</li>
        </ul>
    </section>

    <section id="process">
        <h2>Как работает наш сервис?</h2>
        <ol>
            <li>Звоните или отправляйте заявку через Whatsapp и Telegram.</li>
            <li>Сообщаете, что именно нужно сделать.</li>
            <li>Мастер приезжает в удобное для вас время.</li>
            <li>Выполняет работу качественно и быстро.</li>
            <li>Вы оплачиваете только то, что было сделано.</li>
        </ol>
        <p>Не откладывайте! Легче всего исправить проблему сразу, чем ждать, пока она станет серьёзной. С нашей помощью ваш дом снова станет уютным и комфортным.</p>
    </section>

    <section id="contacts">
        <h2>Наши контакты</h2>
        <div class="contact-phone">
            <p>Телефон: <span id="contact-number">+7 (912) 255-70-88</span></p>
        </div>
        <div class="contact-links">
            <a href="https://wa.me/79122557088" aria-label="Написать в WhatsApp">WhatsApp</a>
            <a href="https://t.me/+79122557088" aria-label="Написать в Telegram">Telegram</a>
        </div>
        <div class="contact-email">
            <p>Email: <span id="contact-email">dv9122557088@yandex.ru</span></p>
        </div>
    </section>

    <section id="feedback">
        <h2>Обратная связь</h2>
        <form class="feedback-form" action="#" method="post">
            <input type="text" name="name" placeholder="Ваше имя" required>
            <input type="tel" name="phone" placeholder="Ваш телефон" required>
            <textarea name="message" placeholder="Ваше сообщение" rows="5" required></textarea>
            <button type="submit">Отправить</button>
        </form>
    </section>
</div>

<footer>
    <p>&copy; 2023 Мастер на час. Все права защищены.</p>
    <div class="social-links">
        <a href="https://wa.me/79122557088" aria-label="Написать в WhatsApp">WhatsApp</a>
        <a href="https://t.me/+79122557088" aria-label="Написать в Telegram">Telegram</a>
    </div>
</footer>

<button id="scrollToTop" aria-label="Вернуться наверх">↑ Наверх</button>

<script>
    document.getElementById('scrollToTop').addEventListener('click', () => {
        window.scrollTo({ top: 0, behavior: 'smooth' });
    });

    window.addEventListener('scroll', () => {
        const scrollToTopButton = document.getElementById('scrollToTop');
        if (window.scrollY > 300) {
            scrollToTopButton.style.display = 'block';
        } else {
            scrollToTopButton.style.display = 'none';
        }
    });
</script>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "LocalBusiness",
  "name": "Мастер на час",
  "image": "https://вашсайт.ru/images/logo.png",
  "telephone": "+7 (912) 255-70-88",
  "email": "dv9122557088@yandex.ru",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "Ваш адрес",
    "addressLocality": "Ваш город",
    "postalCode": "123456",
    "addressCountry": "RU"
  }
}
</script>

</body>
</html>
