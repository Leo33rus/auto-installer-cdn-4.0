<div class="readme-shell">
  <style>
    .readme-shell {
      --bg: #021526;
      --bg-2: #071d31;
      --bg-3: #0b2444;
      --panel: rgba(11, 31, 50, 0.9);
      --panel-2: rgba(14, 39, 64, 0.8);
      --line: rgba(74, 151, 255, 0.5);
      --cyan: #44d7ff;
      --cyan-2: #6ce7ff;
      --blue: #1a8fff;
      --blue-2: #3f7bff;
      --purple: #7566ff;
      --green: #2ae0c3;
      --red: #ff4b6f;
      --yellow: #ffc857;
      --text: #eaf8ff;
      --muted: #96bfd9;
      --shadow: 0 0 18px rgba(68, 215, 255, 0.45);
      color: var(--text);
      background: radial-gradient(circle at 50% 5%, rgba(30, 102, 185, 0.25), transparent 35%),
                  linear-gradient(180deg, #020b18 0%, #031a2d 20%, #020f1e 100%);
      border-radius: 20px;
      padding: 20px 18px 10px;
      box-sizing: border-box;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
      border: 1px solid rgba(135, 207, 255, 0.25);
      box-shadow: inset 0 0 0 1px rgba(90, 169, 255, 0.1), 0 20px 50px rgba(0, 0, 0, 0.35);
      margin: 20px 0;
    }

    .readme-shell * { box-sizing: border-box; }

    .readme-shell a { color: inherit; text-decoration: none; }

    .readme-shell .hero {
      position: relative;
      display: grid;
      grid-template-columns: 1.2fr 0.8fr;
      align-items: center;
      min-height: 230px;
      padding: 18px 18px 10px;
      border-radius: 18px;
      background: linear-gradient(135deg, rgba(1, 14, 27, 0.92), rgba(5, 28, 43, 0.85));
      border: 1px solid rgba(73, 163, 255, 0.42);
      box-shadow: inset 0 0 35px rgba(33, 126, 194, 0.22);
      overflow: hidden;
    }

    .readme-shell .hero::before {
      content: "";
      position: absolute;
      inset: 0;
      background: radial-gradient(circle at 64% 32%, rgba(79, 210, 255, 0.2), transparent 24%),
                  radial-gradient(circle at 83% 22%, rgba(100, 140, 255, 0.18), transparent 26%);
      pointer-events: none;
    }

    .readme-shell .brand-wrap {
      position: relative;
      z-index: 1;
      display: flex;
      align-items: center;
      gap: 20px;
      padding-left: 8px;
    }

    .readme-shell .shield {
      width: 92px;
      height: 92px;
      border-radius: 22px;
      background: linear-gradient(180deg, rgba(10, 19, 33, 0.9), rgba(14, 32, 50, 0.9));
      border: 2px solid rgba(98, 210, 255, 0.9);
      box-shadow: 0 0 18px rgba(68, 215, 255, 0.5), inset 0 0 18px rgba(80, 210, 255, 0.18);
      display: grid;
      place-items: center;
      color: var(--cyan-2);
      font-size: 42px;
      text-shadow: 0 0 14px rgba(68, 215, 255, 0.7);
    }

    .readme-shell .title-block {
      display: flex;
      flex-direction: column;
      gap: 6px;
    }

    .readme-shell .title {
      font-size: clamp(2.1rem, 3vw, 3.3rem);
      line-height: 1.1;
      font-weight: 900;
      letter-spacing: -0.04em;
      color: var(--text);
      text-shadow: 0 0 10px rgba(90, 196, 255, 0.5), 0 0 18px rgba(58, 126, 255, 0.3);
    }

    .readme-shell .title .accent {
      color: #7fe7ff;
      text-shadow: 0 0 12px rgba(110, 240, 255, 0.8);
    }

    .readme-shell .subtitle {
      font-size: 1.05rem;
      color: var(--muted);
      line-height: 1.4;
      max-width: 540px;
    }

    .readme-shell .hero-actions {
      position: relative;
      z-index: 1;
      display: flex;
      justify-content: flex-end;
      align-items: center;
      gap: 14px;
    }

    .readme-shell .security-badge {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      background: rgba(8, 25, 44, 0.75);
      border: 1px solid rgba(79, 197, 255, 0.52);
      border-radius: 15px;
      color: var(--cyan-2);
      padding: 9px 12px;
      box-shadow: inset 0 0 10px rgba(66, 180, 255, 0.12), 0 0 16px rgba(68, 215, 255, 0.18);
      transform: translateY(-12px);
      font-weight: 700;
    }

    .readme-shell .hero-graphic {
      position: absolute;
      right: 26px;
      bottom: -10px;
      width: 300px;
      height: 220px;
      border-radius: 50%;
      background: radial-gradient(circle at 50% 20%, rgba(43, 97, 255, 0.18), transparent 40%);
      z-index: 0;
      overflow: hidden;
      opacity: 0.9;
    }

    .readme-shell .hero-graphic::before {
      content: "";
      position: absolute;
      inset: 20px 16px 10px 8px;
      background: linear-gradient(180deg, rgba(19,47,76,0.8), rgba(2,17,30,0.14));
      border-radius: 42% 42% 18% 18% / 26% 26% 10% 10%;
      border: 1px solid rgba(143, 222, 255, 0.35);
      box-shadow: 0 0 25px rgba(60, 164, 255, 0.18), inset 0 0 25px rgba(0,0,0,0.22);
    }

    .readme-shell .hero-graphic::after {
      content: "";
      position: absolute;
      inset: 42px 50px 18px 52px;
      background: radial-gradient(circle at center, rgba(72, 180, 255, 0.7), rgba(17, 65, 107, 0.2) 30%, transparent 72%);
      filter: blur(12px);
      opacity: 0.75;
    }

    .readme-shell .mini-grid {
      display: grid;
      grid-template-columns: repeat(5, minmax(0, 1fr));
      gap: 18px;
      margin-top: 18px;
      padding: 0 6px;
    }

    .readme-shell .mini-card {
      position: relative;
      padding: 18px 12px 14px;
      min-height: 142px;
      text-align: center;
      border-radius: 18px;
      background: linear-gradient(180deg, rgba(5, 31, 52, 0.75), rgba(5, 18, 30, 0.75));
      border: 1px solid rgba(83, 190, 255, 0.38);
      box-shadow: inset 0 0 16px rgba(83, 190, 255, 0.12);
      overflow: hidden;
    }

    .readme-shell .mini-card .icon {
      width: 46px;
      height: 46px;
      border-radius: 50%;
      margin: 0 auto 12px;
      display: grid;
      place-items: center;
      border: 1px solid rgba(126, 216, 255, 0.7);
      box-shadow: 0 0 18px rgba(77, 162, 255, 0.2);
      font-size: 20px;
      background: rgba(8, 24, 38, 0.75);
    }

    .readme-shell .mini-card h3 {
      margin: 0 0 8px;
      font-size: 1rem;
      font-weight: 700;
      line-height: 1.25;
      color: #effcff;
    }

    .readme-shell .mini-card p {
      margin: 0;
      font-size: 0.8rem;
      line-height: 1.45;
      color: var(--muted);
    }

    .readme-shell .content-grid {
      display: grid;
      grid-template-columns: 1.05fr 1.15fr;
      gap: 18px;
      margin-top: 18px;
      padding: 6px 6px 0;
    }

    .readme-shell .panel {
      background: linear-gradient(180deg, rgba(7, 25, 42, 0.82), rgba(5, 18, 30, 0.8));
      border: 1px solid rgba(80, 177, 255, 0.34);
      border-radius: 18px;
      padding: 18px 20px 16px;
      box-shadow: inset 0 0 18px rgba(75, 171, 255, 0.08);
    }

    .readme-shell .panel-header {
      display: flex;
      align-items: center;
      gap: 12px;
      margin-bottom: 12px;
      color: var(--text);
    }

    .readme-shell .panel-header .mark {
      width: 30px;
      height: 30px;
      border-radius: 50%;
      display: grid;
      place-items: center;
      background: rgba(18, 43, 66, 0.8);
      color: var(--cyan-2);
      border: 1px solid rgba(97, 214, 255, 0.55);
      box-shadow: 0 0 14px rgba(65, 160, 255, 0.18);
      font-size: 17px;
    }

    .readme-shell .panel-header h2 {
      margin: 0;
      font-size: clamp(1.2rem, 1.9vw, 2rem);
      font-weight: 800;
      letter-spacing: -0.03em;
    }

    .readme-shell .check-list {
      list-style: none;
      padding: 0;
      margin: 0;
      display: grid;
      gap: 10px;
    }

    .readme-shell .check-list li {
      position: relative;
      padding-left: 28px;
      color: var(--text);
      font-size: 1rem;
      line-height: 1.45;
    }

    .readme-shell .check-list li::before {
      content: "✓";
      position: absolute;
      left: 0;
      top: 0;
      color: #67f0d8;
      font-weight: 800;
      text-shadow: 0 0 12px rgba(103, 240, 216, 0.5);
    }

    .readme-shell .info-note {
      margin-top: 14px;
      display: flex;
      align-items: center;
      gap: 10px;
      background: rgba(20, 62, 90, 0.72);
      border: 1px solid rgba(95, 180, 255, 0.3);
      border-radius: 12px;
      padding: 13px 14px;
      color: #d5ecff;
      font-size: 0.86rem;
      line-height: 1.4;
    }

    .readme-shell .info-note .i {
      display: grid;
      place-items: center;
      width: 22px;
      height: 22px;
      border-radius: 50%;
      background: rgba(44, 135, 255, 0.18);
      color: var(--cyan-2);
      font-weight: 900;
      flex-shrink: 0;
    }

    .readme-shell .quick-start {
      display: grid;
      gap: 12px;
    }

    .readme-shell .quick-start .command-box {
      background: rgba(13, 33, 52, 0.9);
      border: 1px solid rgba(80, 175, 255, 0.32);
      border-radius: 12px;
      padding: 16px 16px 14px;
      overflow: auto;
      box-shadow: inset 0 0 0 1px rgba(120, 208, 255, 0.06);
    }

    .readme-shell pre {
      margin: 0;
      color: #dffaff;
      font-size: 0.92rem;
      line-height: 1.5;
      white-space: pre-wrap;
      word-break: break-word;
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
    }

    .readme-shell .platforms {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 4px;
    }

    .readme-shell .platforms span {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      min-width: 98px;
      padding: 9px 12px;
      border-radius: 10px;
      border: 1px solid rgba(110, 198, 255, 0.5);
      background: linear-gradient(180deg, rgba(21, 40, 58, 0.85), rgba(12, 29, 42, 0.85));
      color: var(--text);
      font-weight: 600;
      box-shadow: inset 0 0 10px rgba(84, 156, 255, 0.12);
    }

    .readme-shell .flow-grid {
      display: grid;
      grid-template-columns: repeat(5, minmax(0, 1fr));
      gap: 14px;
      margin-top: 18px;
      padding: 0 6px;
    }

    .readme-shell .flow-item {
      min-height: 128px;
      background: linear-gradient(180deg, rgba(12, 33, 50, 0.8), rgba(8, 20, 32, 0.8));
      border: 1px solid rgba(92, 186, 255, 0.28);
      border-radius: 14px;
      padding: 12px 10px 10px;
      text-align: center;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 8px;
    }

    .readme-shell .flow-item .flow-icon {
      width: 44px;
      height: 44px;
      border-radius: 12px;
      display: grid;
      place-items: center;
      border: 1px solid rgba(105, 204, 255, 0.48);
      background: rgba(7, 24, 38, 0.7);
      color: var(--cyan-2);
      font-size: 20px;
      box-shadow: 0 0 18px rgba(58, 160, 255, 0.18);
    }

    .readme-shell .flow-item strong {
      font-size: 0.92rem;
      line-height: 1.35;
      color: var(--text);
    }

    .readme-shell .flow-item span {
      font-size: 0.72rem;
      color: var(--muted);
      line-height: 1.35;
    }

    .readme-shell .bottom-grid {
      display: grid;
      grid-template-columns: 1.12fr 1fr 1fr;
      gap: 18px;
      margin-top: 18px;
      padding: 0 6px 8px;
    }

    .readme-shell .support-box,
    .readme-shell .content-box,
    .readme-shell .links-box {
      background: linear-gradient(180deg, rgba(7, 24, 40, 0.8), rgba(7, 19, 32, 0.8));
      border-radius: 18px;
      border: 1px solid rgba(80, 176, 255, 0.28);
      padding: 16px 18px;
    }

    .readme-shell .support-box .inner,
    .readme-shell .content-box .inner,
    .readme-shell .links-box .inner {
      display: grid;
      gap: 12px;
    }

    .readme-shell .support-list {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 12px;
    }

    .readme-shell .support-list .item {
      min-height: 86px;
      padding: 12px 10px 10px;
      border-radius: 12px;
      background: rgba(12, 30, 46, 0.8);
      border: 1px solid rgba(88, 183, 255, 0.22);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 7px;
      text-align: center;
      font-weight: 700;
      color: var(--text);
    }

    .readme-shell .support-list .item .small-icon {
      font-size: 24px;
      color: var(--cyan-2);
    }

    .readme-shell .content-list,
    .readme-shell .link-list {
      list-style: none;
      margin: 0;
      padding: 0;
      display: grid;
      gap: 12px;
    }

    .readme-shell .content-list li,
    .readme-shell .link-list li {
      display: flex;
      align-items: center;
      gap: 10px;
      font-size: 1rem;
      color: var(--text);
      padding: 0 2px;
    }

    .readme-shell .content-list li .num,
    .readme-shell .link-list li .arrow {
      width: 24px;
      height: 24px;
      border-radius: 8px;
      display: grid;
      place-items: center;
      background: rgba(13, 34, 52, 0.8);
      border: 1px solid rgba(98, 195, 255, 0.38);
      color: var(--cyan-2);
      font-size: 0.8rem;
      font-weight: 700;
    }

    .readme-shell .footer-bar {
      margin-top: 18px;
      display: grid;
      grid-template-columns: 1.2fr 0.8fr;
      gap: 18px;
      align-items: stretch;
      padding: 0 6px 8px;
    }

    .readme-shell .footer-left,
    .readme-shell .footer-right {
      background: linear-gradient(180deg, rgba(8, 26, 41, 0.78), rgba(6, 18, 30, 0.78));
      border: 1px solid rgba(76, 177, 255, 0.32);
      border-radius: 18px;
      padding: 16px 18px;
    }

    .readme-shell .footer-brand {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 14px;
      min-height: 72px;
    }

    .readme-shell .label {
      display: flex;
      align-items: center;
      gap: 12px;
      color: var(--text);
      font-weight: 800;
      font-size: clamp(1.5rem, 2vw, 2.2rem);
      letter-spacing: -0.04em;
    }

    .readme-shell .label small {
      display: block;
      font-size: 0.7rem;
      line-height: 1.2;
      color: var(--muted);
      font-weight: 600;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      margin-top: 4px;
    }

    .readme-shell .stars {
      display: flex;
      gap: 20px;
      color: var(--muted);
      font-size: 0.88rem;
      padding-right: 12px;
    }

    .readme-shell .stars span { display: inline-flex; align-items: center; gap: 6px; }

    .readme-shell .thanks {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
      min-height: 72px;
      font-weight: 700;
      color: var(--text);
    }

    .readme-shell .thanks .script {
      font-size: 2.2rem;
      line-height: 1;
      color: #77dfff;
      font-style: italic;
      text-shadow: 0 0 14px rgba(93, 214, 255, 0.5);
      white-space: nowrap;
    }

    .readme-shell .thanks a {
      color: #aef0ff;
      text-decoration: none;
    }

    @media (max-width: 1024px) {
      .readme-shell .hero { grid-template-columns: 1fr; }
      .readme-shell .hero-actions { justify-content: flex-start; padding-left: 8px; }
      .readme-shell .hero-graphic { right: -30px; opacity: 0.5; }
      .readme-shell .mini-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); }
      .readme-shell .content-grid { grid-template-columns: 1fr; }
      .readme-shell .bottom-grid { grid-template-columns: 1fr; }
      .readme-shell .flow-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); }
      .readme-shell .footer-bar { grid-template-columns: 1fr; }
    }

    @media (max-width: 600px) {
      .readme-shell .brand-wrap { flex-direction: column; align-items: flex-start; }
      .readme-shell .mini-grid,
      .readme-shell .flow-grid,
      .readme-shell .support-list { grid-template-columns: 1fr; }
      .readme-shell .shield { width: 72px; height: 72px; }
      .readme-shell .title { font-size: 2.1rem; }
      .readme-shell .platforms { gap: 8px; }
      .readme-shell .platforms span { flex: 1 1 42%; }
    }
  </style>

  <section class="hero">
    <div class="brand-wrap">
      <div class="shield">🛡️</div>
      <div class="title-block">
        <div class="title"><span class="accent">cdn-installer-4.0</span></div>
        <div class="subtitle">Автоматизированный установщик VPN/CDN<br>с защитой и привязкой к лицензии</div>
      </div>
    </div>

    <div class="hero-actions">
      <div class="security-badge">🔒 Security</div>
    </div>

    <div class="hero-graphic" aria-hidden="true"></div>
  </section>

  <div class="mini-grid">
    <div class="mini-card">
      <div class="icon">⚡</div>
      <h3>Быстрая установка</h3>
      <p>Автоматическая настройка и запуск сервисов</p>
    </div>
    <div class="mini-card">
      <div class="icon">🛡️</div>
      <h3>Защита лицензии</h3>
      <p>Проверка ключа, HWID и IP-адреса</p>
    </div>
    <div class="mini-card">
      <div class="icon">🌐</div>
      <h3>Привязка к IP и HWID</h3>
      <p>Контроль доступа и поддержка доменов</p>
    </div>
    <div class="mini-card">
      <div class="icon">☁️</div>
      <h3>Поддержка X-RAY и Remnawave</h3>
      <p>Гибкая конфигурация и обновления</p>
    </div>
    <div class="mini-card">
      <div class="icon">📄</div>
      <h3>Понятная структура</h3>
      <p>Документация, логи и инструкции</p>
    </div>
  </div>

  <div class="content-grid">
    <div class="panel">
      <div class="panel-header">
        <div class="mark">▣</div>
        <h2>О проекте</h2>
      </div>
      <ul class="check-list">
        <li>Автоматическая установка и настройка VPN/CDN для вашего сервера</li>
        <li>Защита от несанкционированного доступа</li>
        <li>Привязка к HWID и IP-адресу</li>
        <li>Поддержка X-Ray и Remnawave</li>
        <li>Работа через российский CDN (Яндекс Cloud)</li>
        <li>Лёгкое обновление и управление</li>
      </ul>
      <div class="info-note"><span class="i">i</span> Проект предназначен для делового использования. Все действия выполняются только при наличии действующей лицензии.</div>
    </div>

    <div class="panel quick-start">
      <div class="panel-header">
        <div class="mark">⚡</div>
        <h2>Быстрый старт</h2>
      </div>
      <div class="command-box">
        <pre>git clone https://github.com/Leo33rus/cdn-installer-4.0
cd cdn-installer-4.0
python3 installer.py</pre>
      </div>
      <div class="platforms">
        <span>🐧 Linux</span>
        <span>🟣 Ubuntu</span>
        <span>🟠 Debian</span>
        <span>🐍 Python</span>
      </div>
    </div>
  </div>

  <div class="flow-grid">
    <div class="flow-item">
      <div class="flow-icon">👤</div>
      <strong>Пользователь</strong>
      <span>Запускает установку</span>
    </div>
    <div class="flow-item">
      <div class="flow-icon">⚙️</div>
      <strong>Ваш сервер</strong>
      <span>Настройка и деплой</span>
    </div>
    <div class="flow-item">
      <div class="flow-icon">☁️</div>
      <strong>Яндекс Cloud</strong>
      <span>CDN / DNS / SSL</span>
    </div>
    <div class="flow-item">
      <div class="flow-icon">🧩</div>
      <strong>Клиенты</strong>
      <span>Подключение по VLESS</span>
    </div>
    <div class="flow-item">
      <div class="flow-icon">🌍</div>
      <strong>Интернет</strong>
      <span>Публичный доступ</span>
    </div>
  </div>

  <div class="bottom-grid">
    <div class="support-box">
      <div class="panel-header">
        <div class="mark">⬢</div>
        <h2>Поддерживаемые сервисы</h2>
      </div>
      <div class="support-list">
        <div class="item"><div class="small-icon">×</div><div>X-RAY</div></div>
        <div class="item"><div class="small-icon">◉</div><div>Remnawave</div></div>
        <div class="item"><div class="small-icon">☁</div><div>Яндекс Cloud</div></div>
        <div class="item"><div class="small-icon">⟡</div><div>CDN</div></div>
      </div>
    </div>

    <div class="content-box">
      <div class="panel-header">
        <div class="mark">☰</div>
        <h2>Содержание</h2>
      </div>
      <ul class="content-list">
        <li><span class="num">1</span> Возможности</li>
        <li><span class="num">2</span> Быстрый старт</li>
        <li><span class="num">3</span> Установка и настройка</li>
        <li><span class="num">4</span> Конфигурация</li>
        <li><span class="num">5</span> Обновления</li>
        <li><span class="num">6</span> FAQ</li>
      </ul>
    </div>

    <div class="links-box">
      <div class="panel-header">
        <div class="mark">🔗</div>
        <h2>Полезные ссылки</h2>
      </div>
      <ul class="link-list">
        <li><span class="arrow">→</span> Документация</li>
        <li><span class="arrow">→</span> Поддержка (Telegram)</li>
        <li><span class="arrow">→</span> Репозитории и релизы</li>
        <li><span class="arrow">→</span> Ответы и вопросы</li>
      </ul>
    </div>
  </div>

  <div class="footer-bar">
    <div class="footer-left">
      <div class="footer-brand">
        <div class="label">
          <div class="shield" style="width:52px;height:52px;font-size:25px;border-radius:16px;">🛡️</div>
          <div>
            cdn-installer-4.0
            <small>VPN / CDN / X-RAY / REMNAWAVE</small>
          </div>
        </div>
        <div class="stars">
          <span>⭐ 0 stars</span>
          <span>⎇ 0 forks</span>
        </div>
      </div>
    </div>

    <div class="footer-right">
      <div class="thanks">
        <div class="script">Спасибо,</div>
        <div>что выбрали проект!</div>
      </div>
      <div style="margin-top: 10px; color: var(--muted); font-size: 0.88rem; line-height: 1.5;">
        Разработчик: <a href="https://github.com/Leo33rus">Leo33rus</a><br>
        <a href="https://github.com/Leo33rus/cdn-installer-4.0">github.com/Leo33rus/cdn-installer-4.0</a>
      </div>
    </div>
  </div>
</div>


# 🚀 Auto-installer-cdn-4.0

<p align="center">
  <img src="https://img.shields.io/badge/Version-v4.0-blue" alt="Version v4.0" />
  <img src="https://img.shields.io/badge/OS-Ubuntu%2022.04%20%7C%2024.04-lightgrey" alt="Ubuntu 22.04 | 24.04" />
  <img src="https://img.shields.io/badge/Panel-Remnawave%20%7C%203x-ui-blueviolet" alt="Remnawave | 3x-ui" />
  <img src="https://img.shields.io/badge/CDN-VK%20Cloud%20%7C%20Yandex%20Cloud%20%7C%20TurboFlare-orange" alt="CDN providers" />
</p>

Автоматическое развёртывание VLESS XHTTP Packet-Up через CDN.

Remnawave · 3x-ui · VK Cloud · Yandex Cloud · TurboFlare · Beeline CDNvideo · Timeweb CDN · Selectel CDN

VPN CDN Installer автоматизирует подготовку сервера и развёртывание инфраструктуры для передачи VLESS-трафика через CDN.

## ✨ Возможности

VPN CDN Installer собирает конфигурацию под выбранную архитектуру и провайдера. Установщик позволяет быстро подготовить сервер и запустить рабочую инфраструктуру для доступа по VLESS XHTTP Packet-Up.

### Что умеет установщик

- Панель управления: Remnawave или 3x-ui.
- Xray Core: VLESS inbound с транспортом XHTTP Packet-Up.
- Веб-серверы: Nginx и Caddy — там, где это предусмотрено схемой.
- TLS: сертификаты для используемых доменов.
- CDN: отдельный профиль конфигурации для выбранного провайдера.
- Сеть: параметры Linux, BBR и настройки TCP.
- Firewall: правила сетевого доступа, необходимые выбранной схеме.
- Маршрутизация: geo-файлы и правила Xray.
- Подписки: ссылки и конфигурации для клиентских приложений, если поддерживается выбранной панелью.
- Веб-заглушка: обработка обычных HTTP-запросов.
- Проверка установки: диагностика служб, портов, Nginx, health endpoint и доступности панели.
- Подготовка окружения: Docker и Docker Compose, где это требуется выбранной панелью.

Конкретный набор действий зависит от режима установки, существующей конфигурации сервера и возможностей панели.

---

## 🏗️ Как работает схема

### Стандартная схема

```text
Клиент
  │
  ▼
CDN-провайдер
  │
  ▼
Nginx / Caddy (origin)
  │
  ▼
Xray (VLESS XHTTP Packet-Up)
  │
  ▼
Интернет
```

Клиент подключается к CDN-домену. CDN пересылает запросы на origin, где веб-сервер направляет их к Xray. После этого трафик проходит в интернет.

### Каскадная схема

```text
Клиент
  │
  ▼
CDN-провайдер
  │
  ▼
Relay-нода
  │
  ▼
Exit-нода
  │
  ▼
Интернет
```

Каскад добавляет промежуточный relay-сервер. Такой режим подходит для более сложных архитектур и зависит от доступной инфраструктуры.

---

## ⚙️ Режимы установки

### 1. Панель и нода на одном сервере

Панель управления, Xray, CDN origin и компоненты подписок размещаются на одном VPS.

Подходит для:
- первого запуска;
- компактной инфраструктуры;
- быстрого развёртывания в тестовом окружении.

### 2. Панель и удалённая нода

Панель остаётся на основном сервере, а origin и Xray-нода разворачиваются на отдельном VPS.

Подходит для:
- нескольких локаций;
- разделения управления и пользовательского трафика;
- более гибкой архитектуры.

### 3. CDN для существующей панели

Установщик добавляет CDN inbound и необходимые веб-конфигурации к существующей инфраструктуре.

> Перед внесением изменений в работающую систему обязательно сделайте резервную копию конфигураций и данных.

---

## 🖥️ Поддерживаемые панели

| Панель | Способ развёртывания | Что настраивается |
| --- | --- | --- |
| Remnawave | Docker Compose | Backend, нода, домены, сертификаты, подписки и подключение CDN inbound |
| 3x-ui 3.7.0 | Нативная служба | Панель, база SQLite, Xray inbound, web base path, сертификаты и подписки |

Дополнительные варианты Hysteria2 и gRPC доступны только там, где они совместимы с выбранной архитектурой.

---

## 🌐 Поддерживаемые CDN

### VK Cloud
- Origin работает по HTTP.
- Поддерживаются обычная и каскадная схемы.
- Установщик создаёт XHTTP inbound и конфигурацию Nginx.
- Подходит для пользователей с готовым аккаунтом VK Cloud CDN.

### Yandex Cloud
- Поддерживается HTTPS-соединение до origin.
- Настраиваются домен источника и TLS.
- Возможна работа через отдельную ноду.
- TLS позволяет шифровать участок CDN → origin.

### TurboFlare CDN
- Origin работает по HTTPS на порту 443.
- Используется отдельный XHTTP-путь.
- Важна делегированная DNS-зона и управление edge-сертификатом.
- Предусмотрен отдельный режим для переноса существующего домена и проверки делегирования NS.

### Beeline CDNvideo
- Используется домен, выданный CDNvideo.
- Поддерживаются сценарии Remnawave и 3x-ui.
- Установщик выводит параметры, которые должны быть перенесены в личный кабинет CDNvideo.

### Timeweb CDN
- Origin задаётся IP-адресом сервера на порту 80.
- HTTPS до origin отключается.
- Есть технический домен вида `xxxx.cdn.twcstorage.ru`.
- Пользовательский CDN-домен направляется через CNAME.

### Selectel CDN
- Создаётся ресурс типа «Статика» с HTTPS origin на порту 443.
- Есть технический домен вида `xxxx.selcdn.net`.
- Увеличиваются таймауты для длительных XHTTP-потоков.
- Отключаются cache/brotli/gzip и дополнительные оптимизации.

---

## 📊 Сравнение CDN

| Провайдер | Соединение до origin | Источник | Особенности |
| --- | --- | --- | --- |
| VK Cloud | HTTP | Домен origin | Поддержка каскадной схемы |
| Yandex Cloud | HTTPS | Домен origin | TLS между CDN и сервером |
| TurboFlare CDN | HTTPS :443 | Домен с делегированием NS | Управление DNS-зоной и edge-сертификатом |
| Beeline CDNvideo | HTTP/HTTPS | Домен, выданный CDNvideo | Отдельный профиль провайдера |
| Timeweb CDN | HTTP :80 | IP-адрес сервера | Технический домен и CNAME |
| Selectel CDN | HTTPS :443 | Домен origin | Технический домен *.selcdn.net, таймауты и методы DELETE/POST |

Выбор зависит от доступных функций CDN, требований к соединению с origin и архитектуры вашей инфраструктуры.

---

## 📥 Как получить установщик

Установщик выдаётся через Telegram-бота.

### Получить VPN CDN Installer

Бот показывает актуальную команду запуска. После запуска установщик предлагает выбрать режим, панель и CDN-провайдера.

> Команда запуска намеренно не указывается в этом README: используйте актуальную команду, которую выдаёт бот, перед запуском на сервере.

---

## ✅ Результат установки

После успешного завершения установщик выводит:

- адрес панели управления;
- учётные данные администратора и путь панели, если он используется;
- origin-домен и CDN-домен;
- параметры VLESS XHTTP inbound;
- ссылку подписки и JSON-конфигурацию, если их поддерживает панель;
- инструкцию по настройке выбранного CDN;
- результаты итоговой проверки компонентов.

Некоторые параметры CDN необходимо вручную перенести в личный кабинет провайдера.

---

## 🧰 Системные требования

- Операционная система: Ubuntu 22.04 или Ubuntu 24.04
- Доступ: root
- Процессор: от 1 CPU
- Оперативная память: от 1 GB RAM
- Домен: доступ к управлению DNS-записями
- CDN-ресурс: аккаунт одного из поддерживаемых провайдеров
- Удалённая нода: второй VPS и SSH-доступ
- Каскад: дополнительный relay-сервер

Фактические требования зависят от панели, числа подключений и нагрузки.

---

## 🔐 Безопасность и важные замечания

- Запускайте установщик только на серверах, которыми вы управляете и на которых имеете право выполнять системные изменения.
- Перед установкой на рабочий сервер создайте резервную копию или снимок VPS.
- Установщик может устанавливать системные компоненты, изменять сетевые настройки, firewall и конфигурации веб-серверов.
- Проверьте правила firewall и доступность SSH до и после установки, чтобы не потерять доступ к серверу.
- Не публикуйте в репозитории пароли, токены, приватные ключи, ссылки подписок и другие секреты.
- Перед сменой NS-серверов сохраните текущую DNS-зону и перенесите необходимые записи.
- После установки проверьте состояние служб, сертификатов, inbound и доступность панели.
- Возможности CDN и условия предоставления услуг определяются соответствующим провайдером.

---

## 📝 История изменений

### v4.0
- Обновлён сценарий установки 3x-ui 3.7.0.
- Актуализированы сценарии Remnawave.
- Добавлены отдельные пошаговые инструкции для Timeweb, TurboFlare и Selectel CDN.
- Улучшены XHTTP Packet-Up профили провайдеров.
- Поддержаны установка на одном сервере, удалённая нода и работа с существующей панелью.
- Добавлена автоматическая настройка подписок для Remnawave и 3x-ui.
- Улучшены проверки Xray-порта, Nginx, health endpoint и доступности панели.
- Повышена устойчивость скачивания компонентов при медленном соединении.
- Улучшены повторный запуск, диагностика и сообщения об ошибках.

---

## 💬 Поддержка

По вопросам установки и диагностики:

- Telegram: `@cyberlock_support`

При обращении укажите:
- версию установщика;
- ОС;
- выбранную панель;
- CDN-провайдера;
- текст ошибки.

Перед отправкой запроса подготовьте вывод команды и логи диагностики.

---

<p align="center">
  <img src="https://img.shields.io/badge/Project-Status%20Stable-success" alt="Status Stable" />
  <img src="https://img.shields.io/badge/Verified-Used%20by%20thousands-success" alt="Verified by thousands" />
</p>

<p align="center">
  <a href="https://github.com/Leo33rus/cdn-installer-4.0">GitHub</a>
  ·
  <a href="https://t.me/cyberlock_support">Telegram Support</a>
</p>

© 2025–2026 cyberlock. Все права защищены.
