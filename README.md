<div align="center">
  <img src="https://img.shields.io/badge/Version-v4.0-0ea5e9?style=for-the-badge&logo=github&logoColor=white" alt="Version v4.0" />
  <img src="https://img.shields.io/badge/Status-Active-22c55e?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/Platform-Linux%20%7C%20Ubuntu%20%7C%20Debian-38bdf8?style=for-the-badge" alt="Platform" />
</div>

<h1 align="center" style="font-size:52px; letter-spacing:1px; color:#00d9ff; text-shadow:0 0 18px rgba(0,217,255,0.9);">
  <span style="display:inline-block; vertical-align:middle;">🛡️</span>
  auto-installer-cdn-4.0
</h1>

<p align="center" style="font-size:23px; color:#dffbff; margin-top:-8px; font-weight:600;">
  Автоматизированный установщик VPN/CDN для Linux
</p>

<div align="center" style="margin:24px 0 30px 0;">
  <img src="https://img.shields.io/badge/Безопасность-✅-00d4ff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Linux-✅-00d4ff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/X-Ray-✅-00d4ff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Remnawave-✅-00d4ff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/CDN%20%2F%20DNS-✅-00d4ff?style=for-the-badge" />
</div>

<div style="
  background: linear-gradient(135deg, rgba(7,20,36,0.95), rgba(9,38,66,0.92));
  border: 1px solid rgba(0,212,255,0.7);
  border-radius: 24px;
  padding: 28px;
  box-shadow: 0 0 32px rgba(0,212,255,0.18), inset 0 0 22px rgba(0,212,255,0.06);
  margin: 26px 0;
">
  <table width="100%" cellpadding="0" cellspacing="0" border="0">
    <tr>
      <td valign="top" width="58%">
        <h2 style="margin:0 0 18px 0; color:#00d6ff; font-size:32px;">🚀 О проекте</h2>
        <p style="color:#dfeeff; font-size:17px; line-height:1.75; margin:0;">
          <b>auto-installer-cdn-4.0</b> — это современный автоматизированный установщик для развёртывания VPN/CDN инфраструктуры на Linux-серверах. Проект позволяет быстро подготовить окружение, настроить зависимости, подключить X-Ray и Remnawave, а также упростить работу с CDN и DNS без ручного перебора конфигураций.
        </p>

        <div style="margin-top:22px;">
          <p style="margin:8px 0; color:#cfefff;"><span style="color:#00ffbf;">✓</span> Автоматическая установка и базовая настройка</p>
          <p style="margin:8px 0; color:#cfefff;"><span style="color:#00ffbf;">✓</span> Поддержка X-Ray и Remnawave</p>
          <p style="margin:8px 0; color:#cfefff;"><span style="color:#00ffbf;">✓</span> Подготовка окружения под CDN/DNS</p>
          <p style="margin:8px 0; color:#cfefff;"><span style="color:#00ffbf;">✓</span> Упрощённый процесс развёртывания на Ubuntu/Debian</p>
          <p style="margin:8px 0; color:#cfefff;"><span style="color:#00ffbf;">✓</span> Поддержка нескольких сценариев установки</p>
        </div>
      </td>

      <td valign="top" width="42%" style="padding-left: 28px;">
        <div style="
          background: rgba(11,26,45,0.9);
          border: 1px solid rgba(0,212,255,0.5);
          border-radius: 18px;
          padding: 18px 20px;
          box-shadow: inset 0 0 18px rgba(0,212,255,0.08);
        ">
          <h3 style="margin:0 0 12px 0; color:#7be7ff; font-size:20px;">⚡ Быстрый старт</h3>
          <p style="margin:0 0 12px 0; color:#d7f6ff; font-size:14px;">Запуск установки одной командой:</p>
          <pre style="
            margin:0;
            overflow:auto;
            padding:14px 16px;
            border-radius:10px;
            background:#071827;
            border:1px solid rgba(0,212,255,0.4);
            color:#aafaff;
            font-size:13px;
            line-height:1.6;
          "><code>wget -O installer.py https://raw.githubusercontent.com/Leo33rus/auto-installer-cdn-4.0/main/installer.py && python3 installer.py</code></pre>
        </div>

        <div align="center" style="margin-top:18px;">
          <img src="https://img.shields.io/badge/Linux-00d4ff?style=for-the-badge&logo=linux&logoColor=white" />
          <img src="https://img.shields.io/badge/Ubuntu-00d4ff?style=for-the-badge&logo=ubuntu&logoColor=white" />
          <img src="https://img.shields.io/badge/Debian-00d4ff?style=for-the-badge&logo=debian&logoColor=white" />
          <img src="https://img.shields.io/badge/Python-00d4ff?style=for-the-badge&logo=python&logoColor=white" />
        </div>
      </td>
    </tr>
  </table>
</div>

<div style="
  background: linear-gradient(135deg, rgba(5,18,33,0.9), rgba(13,39,72,0.9));
  border: 1px solid rgba(0,212,255,0.7);
  border-radius: 20px;
  padding: 26px 28px;
  box-shadow: 0 0 28px rgba(0,212,255,0.14);
  margin: 26px 0;
">
  <h2 style="margin:0 0 20px 0; color:#00d6ff; font-size:30px;">🧭 Схема работы</h2>

  <div align="center">
    <img src="https://img.shields.io/badge/Пользователь-0ea5e9?style=for-the-badge" />
    <span style="color:#7be7ff; font-size:28px;">→</span>
    <img src="https://img.shields.io/badge/Запуск%20установки-38bdf8?style=for-the-badge" />
    <span style="color:#7be7ff; font-size:28px;">→</span>
    <img src="https://img.shields.io/badge/Ваш%20сервер-22d3ee?style=for-the-badge" />
    <span style="color:#7be7ff; font-size:28px;">→</span>
    <img src="https://img.shields.io/badge/CDN%20%2F%20DNS-0ea5e9?style=for-the-badge" />
    <span style="color:#7be7ff; font-size:28px;">→</span>
    <img src="https://img.shields.io/badge/Клиенты-38bdf8?style=for-the-badge" />
  </div>
</div>

<div style="
  display:flex;
  gap:18px;
  flex-wrap:wrap;
  margin: 28px 0;
">
  <div style="
    flex: 1 1 260px;
    background: rgba(5,18,33,0.9);
    border: 1px solid rgba(0,212,255,0.7);
    border-radius: 18px;
    padding: 20px;
    box-shadow: 0 0 24px rgba(0,212,255,0.12);
  ">
    <h3 style="margin:0 0 12px 0; color:#00d6ff;">✨ Преимущества</h3>
    <p style="margin:0; color:#d9f8ff; line-height:1.9;">
      • Автоматизация установки<br>
      • Упрощённая настройка<br>
      • Поддержка популярных сценариев<br>
      • Быстрая адаптация под Linux<br>
      • Готовая работа с CDN/DNS
    </p>
  </div>

  <div style="
    flex: 1 1 260px;
    background: rgba(5,18,33,0.9);
    border: 1px solid rgba(0,212,255,0.7);
    border-radius: 18px;
    padding: 20px;
    box-shadow: 0 0 24px rgba(0,212,255,0.12);
  ">
    <h3 style="margin:0 0 12px 0; color:#00d6ff;">🧩 Поддерживаемые сервисы</h3>
    <p style="margin:0; color:#d9f8ff; line-height:1.9;">
      X-Ray<br>
      Remnawave<br>
      Yandex Cloud<br>
      CDN<br>
      DNS
    </p>
  </div>

  <div style="
    flex: 1 1 260px;
    background: rgba(5,18,33,0.9);
    border: 1px solid rgba(0,212,255,0.7);
    border-radius: 18px;
    padding: 20px;
    box-shadow: 0 0 24px rgba(0,212,255,0.12);
  ">
    <h3 style="margin:0 0 12px 0; color:#00d6ff;">🔗 Полезные ссылки</h3>
    <p style="margin:0; color:#d9f8ff; line-height:1.9;">
      <a href="https://github.com/Leo33rus/auto-installer-cdn-4.0/wiki" style="color:#7be7ff; text-decoration:none;">Документация</a><br>
      <a href="https://t.me/cyberlock_support" style="color:#7be7ff; text-decoration:none;">Поддержка в Telegram</a><br>
      <a href="https://github.com/Leo33rus/auto-installer-cdn-4.0/issues" style="color:#7be7ff; text-decoration:none;">Вопросы и проблемы</a><br>
      <a href="https://github.com/Leo33rus/auto-installer-cdn-4.0/releases" style="color:#7be7ff; text-decoration:none;">Релизы</a>
    </p>
  </div>
</div>

<div style="
  background: rgba(8,22,38,0.9);
  border: 1px solid rgba(0,212,255,0.5);
  border-radius: 18px;
  padding: 18px 20px;
  margin: 20px 0;
  box-shadow: inset 0 0 18px rgba(0,212,255,0.06);
">
  <strong style="color:#7be7ff;">ℹ️ Важно:</strong>
  <span style="color:#d9f8ff;">Используйте проект только в рамках законных и согласованных условий эксплуатации. Перед установкой убедитесь, что вы имеете право управлять сервером, доменами и связанными сервисами.</span>
</div>

<div align="center" style="margin:36px 0 20px 0;">
  <p style="font-size:20px; color:#d7f6ff; font-weight:bold; text-shadow:0 0 12px rgba(0,212,255,0.5);">
    Спасибо, что выбираете проект для автоматизации развёртывания!
  </p>
</div>

<div align="center" style="padding-bottom:18px;">
  <img src="https://img.shields.io/badge/VPN-00d4ff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/CDN-00d4ff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/X-Ray-00d4ff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Remnawave-00d4ff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/v4.0-00d4ff?style=for-the-badge" />
</div>

<p align="center" style="color:#a9d7ff; font-size:14px;">
  GitHub: <a href="https://github.com/Leo33rus/auto-installer-cdn-4.0" style="color:#7be7ff;">github.com/Leo33rus/auto-installer-cdn-4.0</a>
</p>
