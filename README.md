<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#1A2A44">
  <meta name="description" content="Свадебное приглашение Егора и Виктории — 13 февраля 2027 года">
  <title>Егор & Виктория — свадебное приглашение</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@300;400;500;600&family=Manrope:wght@300;400;500;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --navy: #1A2A44;
      --slate: #6B7D94;
      --silver: #B7BCC2;
      --sage: #A5B3A1;
      --champagne: #E6DCC6;
      --paper: #F5F1E9;
      --ink: #172238;
      --muted: #b9c2d0;
      --line: rgba(230,220,198,.24);
    }
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0; background: var(--navy); color: var(--paper);
      font-family: 'Manrope', sans-serif; font-weight: 300;
      background-image: radial-gradient(ellipse at 15% 15%, rgba(107,125,148,.18), transparent 34%),
                        radial-gradient(ellipse at 90% 45%, rgba(14,91,164,.2), transparent 34%);
    }
    a { color: inherit; }
    .page { width: min(100%, 760px); margin: 0 auto; overflow: hidden; }
    .hero {
      min-height: 94svh; display: flex; flex-direction: column; align-items: center; justify-content: center;
      text-align: center; padding: 54px 24px 64px; position: relative;
      border-bottom: 1px solid var(--line);
    }
    .eyebrow { letter-spacing: .22em; text-transform: uppercase; font-size: 12px; color: var(--champagne); }
    h1, h2, .script, .time { font-family: 'Cormorant Garamond', serif; font-weight: 300; }
    h1 { font-size: clamp(56px, 12vw, 100px); line-height: .86; margin: 34px 0 28px; letter-spacing: -.045em; }
    h1 span { display: block; font-style: italic; font-size: .66em; margin: 12px 0; color: var(--champagne); }
    .hero-date { font-family: 'Cormorant Garamond', serif; font-size: 24px; letter-spacing: .12em; }
    .hero-note { max-width: 320px; font-size: 14px; line-height: 1.9; color: var(--muted); margin-top: 30px; }
    .ornament { width: 150px; height: 1px; background: linear-gradient(90deg, transparent, var(--champagne), transparent); margin: 24px auto; position: relative; }
    .ornament:after { content: '✦'; position: absolute; left: 50%; top: 50%; transform: translate(-50%,-50%); background: var(--navy); padding: 0 10px; color: var(--champagne); font-size: 11px; }
    .scroll-cue { position: absolute; bottom: 22px; font-size: 9px; letter-spacing: .18em; color: var(--muted); text-transform: uppercase; }
    section { padding: 70px 24px; border-bottom: 1px solid var(--line); }
    .section-number { color: var(--champagne); font-size: 12px; letter-spacing: .2em; }
    h2 { font-size: clamp(39px, 9vw, 58px); line-height: .95; margin: 14px 0 26px; font-style: italic; }
    .intro { max-width: 510px; margin: 0 auto; text-align: center; }
    .intro p, .body-copy { color: #d5dbe3; font-size: 15px; line-height: 2; }
    .center { text-align: center; }
    .date-card {
      border: 1px solid rgba(230,220,198,.42); padding: 34px 22px; text-align: center; position: relative;
      max-width: 460px; margin: 32px auto 0;
      background: linear-gradient(145deg, rgba(255,255,255,.025), transparent 55%);
    }
    .date-big { font-family: 'Cormorant Garamond', serif; font-size: clamp(42px, 10vw, 68px); letter-spacing: .04em; }
    .date-sub { color: var(--champagne); font-size: 12px; letter-spacing: .2em; text-transform: uppercase; margin: 10px 0 24px; }
    .address { font-size: 14px; line-height: 1.9; color: #d5dbe3; }
    .button {
      display: inline-flex; justify-content: center; align-items: center; gap: 8px;
      padding: 13px 22px; border: 1px solid var(--champagne); border-radius: 99px;
      color: var(--paper); background: transparent; font: 500 12px 'Manrope', sans-serif;
      letter-spacing: .08em; text-decoration: none; cursor: pointer; transition: .25s ease;
    }
    .button:hover { background: var(--champagne); color: var(--navy); }
    .timeline { max-width: 460px; margin: 34px auto 0; }
    .event { display: grid; grid-template-columns: 90px 18px 1fr; gap: 12px; align-items: start; padding: 18px 0; }
    .time { font-size: 31px; color: var(--champagne); line-height: 1; }
    .event-dot { width: 8px; height: 8px; border: 1px solid var(--champagne); border-radius: 50%; margin-top: 8px; position: relative; }
    .event:not(:last-child) .event-dot:after { content: ''; position: absolute; top: 8px; left: 3px; height: 50px; width: 1px; background: var(--line); }
    .event-title { font-size: 14px; letter-spacing: .04em; }
    .event-desc { color: var(--muted); font-size: 12px; margin-top: 6px; line-height: 1.6; }
    .palette { display: grid; grid-template-columns: repeat(5, minmax(0, 1fr)); gap: 10px; margin: 32px auto 14px; max-width: 600px; }
    .swatch-wrap { text-align: center; }
    .swatch {
      width: min(18vw, 100px); height: min(18vw, 100px); border-radius: 50%; margin: 0 auto 12px;
      box-shadow: inset 0 0 0 1px rgba(255,255,255,.16), 0 8px 24px rgba(0,0,0,.16);
      position: relative; overflow: hidden;
    }
    /* Silk-like highlights layered over the requested palette colors */
    .swatch:before {
      content: ''; position: absolute; inset: -20%;
      background: linear-gradient(115deg, transparent 15%, rgba(255,255,255,.32) 27%, transparent 39%, rgba(255,255,255,.13) 52%, transparent 65%),
                  radial-gradient(ellipse at 28% 18%, rgba(255,255,255,.23), transparent 42%);
      transform: rotate(-18deg); filter: blur(2px);
    }
    .swatch:after { content: ''; position: absolute; inset: 0; border-radius: inherit; background: linear-gradient(155deg, rgba(255,255,255,.13), transparent 45%, rgba(0,0,0,.18)); }
    .navy { background: #1A2A44; }
    .slate { background: #6B7D94; }
    .silver { background: #B7BCC2; }
    .champagne { background: #E6DCC6; }
    .sage { background: #A5B3A1; }
    .swatch-name { font-size: 9px; letter-spacing: .03em; text-transform: uppercase; color: var(--muted); white-space: nowrap; }
    .swatch-code { margin-top: 5px; font-size: 8px; letter-spacing: .01em; color: var(--muted); }
    .wishes { max-width: 520px; margin: 42px auto 0; padding-top: 32px; border-top: 1px solid var(--line); }
    .wishes h3 { font-family: 'Cormorant Garamond', serif; font-size: 29px; font-weight: 300; font-style: italic; margin: 0 0 12px; color: var(--champagne); }
    .wishes p { color: #d5dbe3; font-size: 12px; line-height: 1.9; }
    .countdown-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px; max-width: 460px; margin: 34px auto 0; }
    .count-box { border: 1px solid var(--line); padding: 18px 5px 14px; text-align: center; }
    .count-num { font-family: 'Cormorant Garamond', serif; font-size: clamp(28px, 7vw, 44px); line-height: 1; color: var(--champagne); }
    .count-label { font-size: 8px; letter-spacing: .12em; color: var(--muted); text-transform: uppercase; margin-top: 10px; }
    .form-wrap { max-width: 520px; margin: 30px auto 0; }
    .field { margin: 0 0 24px; }
    label, .field-title { display: block; color: var(--champagne); font-size: 12px; letter-spacing: .08em; margin-bottom: 10px; }
    input[type="text"], textarea {
      width: 100%; border: 0; border-bottom: 1px solid rgba(230,220,198,.45); background: transparent;
      color: var(--paper); font: 300 15px 'Manrope', sans-serif; padding: 12px 2px; border-radius: 0; outline: none;
    }
    input:focus, textarea:focus { border-color: var(--champagne); }
    textarea { min-height: 86px; resize: vertical; }
    .options { display: flex; flex-wrap: wrap; gap: 9px; }
    .option { display: inline-flex; align-items: center; gap: 7px; padding: 9px 11px; border: 1px solid var(--line); border-radius: 99px; color: #d5dbe3; font-size: 12px; cursor: pointer; }
    .option input { accent-color: var(--champagne); margin: 0; }
    .form-status { font-size: 14px; line-height: 1.7; text-align: center; margin-top: 18px; color: var(--champagne); min-height: 24px; }
    .form-note { color: var(--muted); font-size: 11px; line-height: 1.7; margin-top: 16px; }
    footer { padding: 44px 24px 56px; text-align: center; }
    footer .names { font: italic 37px 'Cormorant Garamond', serif; color: var(--champagne); }
    footer p { font-size: 9px; color: var(--muted); letter-spacing: .12em; }

    .hero:before, .hero:after {
      content: '❧'; position: absolute; color: rgba(230,220,198,.34);
      font-family: 'Cormorant Garamond', serif; font-size: 56px; line-height: 1;
      pointer-events: none;
    }
    .hero:before { top: 26px; left: 22px; transform: rotate(-42deg); }
    .hero:after { bottom: 42px; right: 22px; transform: rotate(138deg); }
    .date-card:before, .date-card:after {
      content: '✦  ❦  ✦'; display: block; color: rgba(230,220,198,.62);
      font-size: 13px; letter-spacing: .4em; margin: -12px auto 20px;
    }
    .date-card:after { margin: 22px auto -12px; }
    section { position: relative; }
    section:before {
      content: '❧'; position: absolute; top: 18px; right: 22px;
      color: rgba(230,220,198,.18); font-family: 'Cormorant Garamond', serif;
      font-size: 34px; transform: rotate(18deg); pointer-events: none;
    }
    .wishes { position: relative; }
    .wishes:after {
      content: '✧'; display: block; text-align: center; color: rgba(230,220,198,.55);
      font-size: 17px; margin-top: 22px;
    }
    .count-box { position: relative; }
    .count-box:before {
      content: ''; position: absolute; inset: 4px; border: 1px solid rgba(230,220,198,.08); pointer-events: none;
    }

    @media (min-width: 650px) {
      .hero { min-height: 820px; }
      section { padding: 86px 54px; }
      .swatch { width: 100px; height: 100px; }
    }
    @media (max-width: 360px) {
      .event { grid-template-columns: 72px 12px 1fr; gap: 9px; }
      .time { font-size: 27px; }
      .palette { gap: 4px; }
      .swatch { width: 16vw; height: 16vw; }
      .swatch-name { font-size: 7px; letter-spacing: 0; }
      .swatch-code { font-size: 6px; }
    }
  </style>
</head>
<body>
  <main class="page">
    <header class="hero" id="top">
      <div class="eyebrow">Свадебное приглашение</div>
      <div class="ornament"></div>
      <h1>Егор <span>&</span> Виктория</h1>
      <div class="hero-date">13 · 02 · 2027</div>
      <p class="hero-note">С радостью приглашаем вас разделить с нами один из самых важных и счастливых дней нашей жизни.</p>
      <div class="ornament"></div>
      <a class="button" href="#rsvp">Ответить на приглашение ↓</a>
      <div class="scroll-cue">Листайте ниже</div>
    </header>

    <section id="about">
      <div class="intro">
        <div class="section-number">01 / О НАС</div>
        <h2>День, который<br>мы разделим</h2>
        <p>Есть моменты, которые становятся особенно дорогими, когда рядом самые близкие. Мы начинаем новую главу нашей истории и будем счастливы провести этот день с вами — в объятиях, улыбках, тёплых словах и воспоминаниях, к которым захочется возвращаться.</p>
        <div class="ornament"></div>
      </div>
    </section>

    <section id="place">
      <div class="center">
        <div class="section-number">02 / ДАТА И МЕСТО</div>
      </div>
      <div class="date-card">
        <div class="date-big">13.02.2027</div>
        <div class="date-sub">Суббота · Великие Луки</div>
        <div class="address">г. Великие Луки,<br>пр. Октябрьский, 74/2</div>
        <div style="margin-top:24px">
          <a class="button" href="https://yandex.ru/maps/?text=%D0%92%D0%B5%D0%BB%D0%B8%D0%BA%D0%B8%D0%B5%20%D0%9B%D1%83%D0%BA%D0%B8%2C%20%D0%BF%D1%80%D0%BE%D1%81%D0%BF%D0%B5%D0%BA%D1%82%20%D0%9E%D0%BA%D1%82%D1%8F%D0%B1%D1%80%D1%8C%D1%81%D0%BA%D0%B8%D0%B9%2074%2F2" target="_blank" rel="noopener">Открыть карту ↗</a>
        </div>
      </div>
    </section>

    <section id="schedule">
      <div class="center">
        <div class="section-number">03 / ПРОГРАММА ДНЯ</div>
        <h2>Важные моменты</h2>
        <p class="body-copy">Пожалуйста, сохраните время, чтобы провести этот день вместе с нами от самого начала.</p>
      </div>
      <div class="timeline">
        <div class="event">
          <div class="time">14:20</div><div class="event-dot"></div>
          <div><div class="event-title">Сбор гостей</div><div class="event-desc">Обнимаемся, знакомимся и настраиваемся на праздник</div></div>
        </div>
        <div class="event">
          <div class="time">15:00</div><div class="event-dot"></div>
          <div><div class="event-title">Начало церемонии</div><div class="event-desc">Самый трогательный момент этого дня</div></div>
        </div>
        <div class="event">
          <div class="time">16:00</div><div class="event-dot"></div>
          <div><div class="event-title">Начало банкета</div><div class="event-desc">Тёплые тосты, вкусная еда и танцы</div></div>
        </div>
      </div>
    </section>

    <section id="dresscode">
      <div class="center">
        <div class="section-number">04 / ДРЕСС-КОД</div>
        <h2>Оттенки праздника</h2>
        <p class="body-copy">Будем благодарны, если в своих образах вы поддержите нашу палитру. Выбирайте тот оттенок, в котором вам комфортно.</p>
      </div>
      <div class="palette" aria-label="Цветовая палитра дресс-кода">
        <div class="swatch-wrap"><div class="swatch navy"></div><div class="swatch-name">NAVY</div><div class="swatch-code">#1A2A44</div></div>
        <div class="swatch-wrap"><div class="swatch slate"></div><div class="swatch-name">SLATE BLUE</div><div class="swatch-code">#6B7D94</div></div>
        <div class="swatch-wrap"><div class="swatch silver"></div><div class="swatch-name">SILVER</div><div class="swatch-code">#B7BCC2</div></div>
        <div class="swatch-wrap"><div class="swatch sage"></div><div class="swatch-name">SAGE</div><div class="swatch-code">#A5B3A1</div></div>
        <div class="swatch-wrap"><div class="swatch champagne"></div><div class="swatch-name">CHAMPAGNE</div><div class="swatch-code">#E6DCC6</div></div>
      </div>
      <div class="wishes">
        <h3>Вместо цветов</h3>
        <p>Ваше присутствие — уже самый ценный подарок. А если вы захотите порадовать нас цветами, будем особенно рады пачке любимого кофе, хорошему чаю или чему-то вкусному к нашим будущим уютным вечерам. Так от каждого из вас у нас останется частичка тепла, которой мы сможем наслаждаться ещё долго.</p>
      </div>
      <div class="wishes">
        <h3>Небольшое пожелание</h3>
        <p>Если вы планировали сделать нам подарок, будем благодарны за вклад в нашу общую историю в конверте. Это поможет нам приблизить наши совместные мечты. Спасибо за ваше понимание и заботу!</p>
      </div>
    </section>

    <section id="countdown">
      <div class="center">
        <div class="section-number">05 / СЧИТАЕМ ДНИ</div>
        <h2>До нашей встречи</h2>
        <p class="body-copy">Каждый день приближает нас к этому моменту ♥</p>
      </div>
      <div class="countdown-grid" aria-label="Обратный отсчёт до свадьбы">
        <div class="count-box"><div class="count-num" id="days">000</div><div class="count-label">Дней</div></div>
        <div class="count-box"><div class="count-num" id="hours">00</div><div class="count-label">Часов</div></div>
        <div class="count-box"><div class="count-num" id="minutes">00</div><div class="count-label">Минут</div></div>
        <div class="count-box"><div class="count-num" id="seconds">00</div><div class="count-label">Секунд</div></div>
      </div>
    </section>

    <section id="rsvp">
      <div class="center">
        <div class="section-number">06 / АНКЕТА ГОСТЯ</div>
        <h2>Вы с нами?</h2>
        <p class="body-copy">Пожалуйста, заполните анкету до 13 января 2027 года — так нам будет проще всё подготовить.</p>
      </div>
      <form class="form-wrap" id="rsvpForm">
        <div class="field">
          <label for="guestName">Ваше имя и фамилия *</label>
          <input id="guestName" name="name" type="text" placeholder="Как к вам обращаться?" required autocomplete="name">
        </div>
        <div class="field">
          <div class="field-title">Планируете ли вы присутствовать? *</div>
          <div class="options">
            <label class="option"><input type="radio" name="attendance" value="Да, буду" required> Да, буду</label>
            <label class="option"><input type="radio" name="attendance" value="К сожалению, не смогу"> К сожалению, не смогу</label>
          </div>
        </div>
        <div class="field">
          <div class="field-title">Предпочтения по напиткам</div>
          <div class="options">
            <label class="option"><input type="checkbox" name="drinks" value="Шампанское"> Шампанское</label>
            <label class="option"><input type="checkbox" name="drinks" value="Белое вино"> Белое вино</label>
            <label class="option"><input type="checkbox" name="drinks" value="Красное вино"> Красное вино</label>
            <label class="option"><input type="checkbox" name="drinks" value="Водка"> Водка</label>
            <label class="option"><input type="checkbox" name="drinks" value="Безалкогольные напитки"> Безалкогольные напитки</label>
          </div>
        </div>
        <div class="field">
          <div class="field-title">Предпочтения по блюдам</div>
          <div class="options">
            <label class="option"><input type="checkbox" name="food" value="Блюда из мяса"> Мясо</label>
            <label class="option"><input type="checkbox" name="food" value="Блюда из рыбы"> Рыба</label>
            <label class="option"><input type="checkbox" name="food" value="Блюда из птицы"> Птица</label>
          </div>
        </div>
        <div class="field">
          <label for="comments">Комментарии, пожелания или вопросы</label>
          <textarea id="comments" name="comments" placeholder="Если есть что-то, что нам стоит учесть, напишите здесь…"></textarea>
        </div>
        <button class="button" type="submit" style="width:100%">Отправить ответ ✦</button>
        <div class="form-status" id="formStatus" role="status" aria-live="polite"></div>
        <p class="form-note">Ваш ответ поможет нам подготовить праздник с заботой о каждом госте.</p>
      </form>
    </section>

    <footer>
      <div class="ornament"></div>
      <div class="names">Егор & Виктория</div>
      <p>С ЛЮБОВЬЮ ЖДЁМ ВАС · 13.02.2027</p>
    </footer>
  </main>

  <script>
    // Вставьте сюда URL развёрнутого Google Apps Script Web App, чтобы ответы записывались в Google Таблицу.
    const GOOGLE_SCRIPT_URL = "https://script.google.com/macros/s/AKfycby1pNCrUzergHV_Um2053_B0E0hypvh6h4ezuhzWHjRfKtqkgW9TRBC1uZiYyMyv7z_jg/exec";

    const weddingDate = new Date("2027-02-13T14:20:00+03:00").getTime();
    function updateCountdown() {
      const distance = weddingDate - Date.now();
      if (distance <= 0) {
        ["days", "hours", "minutes", "seconds"].forEach(id => document.getElementById(id).textContent = "00");
        return;
      }
      document.getElementById("days").textContent = String(Math.floor(distance / 86400000)).padStart(3, "0");
      document.getElementById("hours").textContent = String(Math.floor((distance % 86400000) / 3600000)).padStart(2, "0");
      document.getElementById("minutes").textContent = String(Math.floor((distance % 3600000) / 60000)).padStart(2, "0");
      document.getElementById("seconds").textContent = String(Math.floor((distance % 60000) / 1000)).padStart(2, "0");
    }
    updateCountdown();
    setInterval(updateCountdown, 1000);

    const form = document.getElementById("rsvpForm");
    const status = document.getElementById("formStatus");
    form.addEventListener("submit", async (event) => {
      event.preventDefault();
      const submitButton = form.querySelector('button[type="submit"]');
      const data = new FormData(form);
      const payload = {
        timestamp: new Date().toISOString(),
        name: data.get("name") || "",
        attendance: data.get("attendance") || "",
        drinks: data.getAll("drinks").join(", "),
        food: data.getAll("food").join(", "),
        comments: data.get("comments") || ""
      };

      if (GOOGLE_SCRIPT_URL === "PASTE_GOOGLE_APPS_SCRIPT_WEB_APP_URL_HERE") {
        status.textContent = "Дизайн готов! Чтобы ответы сохранялись в таблице, сначала подключите Google Sheets по инструкции в README.";
        return;
      }

      submitButton.disabled = true;
      submitButton.textContent = "Отправляем…";
      status.textContent = "";
      try {
        await fetch(GOOGLE_SCRIPT_URL, {
          method: "POST",
          mode: "no-cors",
          headers: { "Content-Type": "text/plain;charset=utf-8" },
          body: JSON.stringify(payload)
        });
        form.reset();
        status.textContent = "Спасибо! Мы получили ваш ответ 💌";
      } catch (error) {
        status.textContent = "Не удалось отправить ответ. Пожалуйста, попробуйте ещё раз чуть позже.";
      } finally {
        submitButton.disabled = false;
        submitButton.textContent = "Отправить ответ ✦";
      }
    });
  </script>
</body>
</html>
