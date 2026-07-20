<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Шоукейс Анимаций и Фишек</title>
  <style>
    :root {
      --bg: #0f172a;
      --card-bg: #1e293b;
      --accent: #8b5cf6;
      --text: #f8fafc;
    }

    body {
      margin: 0;
      padding: 2rem;
      font-family: system-ui, -apple-system, sans-serif;
      background-color: var(--bg);
      color: var(--text);
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 2rem;
    }

    h1 {
      text-align: center;
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
      width: 100%;
      max-width: 1000px;
    }

    .card {
      background: var(--card-bg);
      border-radius: 12px;
      padding: 1.5rem;
      box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.3);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 180px;
      position: relative;
      overflow: hidden;
    }

    .card h3 {
      position: absolute;
      top: 10px;
      left: 15px;
      font-size: 0.85rem;
      color: #94a3b8;
      text-transform: uppercase;
      letter-spacing: 1px;
      margin: 0;
    }

    /* --- 1. ТЕКСТОВЫЕ АНИМАЦИИ --- */

    /* Градиентный текст */
    .gradient-text {
      font-size: 1.8rem;
      font-weight: bold;
      background: linear-gradient(90deg, #ff007f, #7928ca, #00dfd8, #ff007f);
      background-size: 300% 100%;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: gradientShift 4s linear infinite;
    }

    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      100% { background-position: 300% 50%; }
    }

    /* Эффект печатания */
    .typing-text {
      font-family: monospace;
      font-size: 1.2rem;
      white-space: nowrap;
      overflow: hidden;
      border-right: 3px solid var(--accent);
      width: 0;
      animation: typing 3.5s steps(22) infinite alternate, blink 0.75s step-end infinite;
    }

    @keyframes typing {
      from { width: 0; }
      to { width: 22ch; }
    }

    @keyframes blink {
      50% { border-color: transparent; }
    }

    /* Всплывающие буквы */
    .wobbly-text span {
      display: inline-block;
      font-size: 1.8rem;
      font-weight: bold;
      animation: wave 1.2s ease-in-out infinite;
    }

    .wobbly-text span:nth-child(1) { animation-delay: 0.0s; }
    .wobbly-text span:nth-child(2) { animation-delay: 0.1s; }
    .wobbly-text span:nth-child(3) { animation-delay: 0.2s; }
    .wobbly-text span:nth-child(4) { animation-delay: 0.3s; }
    .wobbly-text span:nth-child(5) { animation-delay: 0.4s; }

    @keyframes wave {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-12px); color: var(--accent); }
    }

    /* --- 2. АНИМАЦИИ ИКОНОК И ЭЛЕМЕНТОВ --- */

    .icon {
      font-size: 3rem;
      cursor: pointer;
      user-select: none;
    }

    /* Пульсация */
    .pulse-icon {
      animation: pulse 1.5s ease-in-out infinite;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.25); filter: drop-shadow(0 0 10px #ef4444); }
      100% { transform: scale(1); }
    }

    /* Вращение при наведении */
    .spin-icon {
      transition: transform 0.6s cubic-bezier(0.34, 1.56, 0.64, 1);
    }

    .spin-icon:hover {
      transform: rotate(360deg) scale(1.2);
    }

    /* Покачивание (Bell) */
    .shake-icon:hover {
      animation: shake 0.5s ease-in-out;
    }

    @keyframes shake {
      0%, 100% { transform: rotate(0deg); }
      20% { transform: rotate(-15deg); }
      40% { transform: rotate(15deg); }
      60% { transform: rotate(-10deg); }
      80% { transform: rotate(10deg); }
    }

    /* --- 3. ИНТЕРАКТИВ И ПРИКОЛЫ --- */

    /* Следящие глазки */
    .eyes-container {
      display: flex;
      gap: 15px;
    }

    .eye {
      width: 45px;
      height: 45px;
      background: white;
      border-radius: 50%;
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .pupil {
      width: 18px;
      height: 18px;
      background: #0f172a;
      border-radius: 50%;
      position: absolute;
      transition: transform 0.1s ease-out;
    }

    /* Динамическая кнопка */
    .fun-btn {
      padding: 0.8rem 1.5rem;
      font-size: 1rem;
      font-weight: bold;
      color: white;
      background: linear-gradient(135deg, #6366f1, #a855f7);
      border: none;
      border-radius: 8px;
      cursor: pointer;
      position: relative;
      box-shadow: 0 4px 12px rgba(168, 85, 247, 0.4);
      transition: transform 0.1s, box-shadow 0.2s;
    }

    .fun-btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 20px rgba(168, 85, 247, 0.6);
    }

    .fun-btn:active {
      transform: translateY(1px);
    }

    /* Карточка с подсветкой мышью */
    .glow-card {
      background: radial-gradient(circle at var(--mouse-x, 50%) var(--mouse-y, 50%), rgba(139, 92, 246, 0.3) 0%, transparent 60%), var(--card-bg);
    }
  </style>
</head>
<body>

  <h1>✨ Анимации & Фишки HTML/CSS</h1>

  <div class="grid">
    
    <!-- 1. Бегущий градиент -->
    <div class="card">
      <h3>Текст / Градиент</h3>
      <div class="gradient-text">Живой Текст</div>
    </div>

    <!-- 2. Печатающийся текст -->
    <div class="card">
      <h3>Текст / Печать</h3>
      <div class="typing-text">console.log("Hello!");</div>
    </div>

    <!-- 3. Волна из букв -->
    <div class="card">
      <h3>Текст / Волна</h3>
      <div class="wobbly-text">
        <span>В</span><span>А</span><span>У</span><span>!</span><span>!</span>
      </div>
    </div>

    <!-- 4. Пульсация -->
    <div class="card">
      <h3>Иконка / Пульсация</h3>
      <div class="icon pulse-icon">❤️</div>
    </div>

    <!-- 5. Вращение -->
    <div class="card">
      <h3>Иконка / Наведение</h3>
      <div class="icon spin-icon">⚙️</div>
    </div>

    <!-- 6. Покачивание -->
    <div class="card">
      <h3>Иконка / Наведение</h3>
      <div class="icon shake-icon">🔔</div>
    </div>

    <!-- 7. Следящие глаза -->
    <div class="card">
      <h3>Интерактив / Глаза</h3>
      <div class="eyes-container">
        <div class="eye"><div class="pupil"></div></div>
        <div class="eye"><div class="pupil"></div></div>
      </div>
    </div>

    <!-- 8. Кликер-прикол -->
    <div class="card">
      <h3>Прикол / Клик</h3>
      <button class="fun-btn" onclick="popEmoji(event)">Нажми меня!</button>
    </div>

    <!-- 9. Подсветка карточки курсором -->
    <div class="card glow-card" id="glowCard">
      <h3>Интерактив / Свет</h3>
      <p style="text-align: center; color: #94a3b8; margin: 0;">Поводи курсором по этой карточке</p>
    </div>

  </div>

  <script>
    // --- 1. Логика для следящих глаз ---
    document.addEventListener('mousemove', (e) => {
      const pupils = document.querySelectorAll('.pupil');
      pupils.forEach(pupil => {
        const eye = pupil.parentElement;
        const rect = eye.getBoundingClientRect();
        const eyeX = rect.left + rect.width / 2;
        const eyeY = rect.top + rect.height / 2;
        
        const angle = Math.atan2(e.clientY - eyeY, e.clientX - eyeX);
        const distance = Math.min(rect.width / 4, Math.hypot(e.clientX - eyeX, e.clientY - eyeY));
        
        const x = Math.cos(angle) * distance;
        const y = Math.sin(angle) * distance;
        
        pupil.style.transform = `translate(${x}px, ${y}px)`;
      });
    });

    // --- 2. Логика подлетающего эмодзи при клике ---
    function popEmoji(event) {
      const emojis = ['🎉', '🚀', '🔥', '✨', '💥', '🎈'];
      const emoji = document.createElement('div');
      emoji.innerText = emojis[Math.floor(Math.random() * emojis.length)];
      
      emoji.style.position = 'fixed';
      emoji.style.left = `${event.clientX}px`;
      emoji.style.top = `${event.clientY}px`;
      emoji.style.fontSize = '2rem';
      emoji.style.pointerEvents = 'none';
      emoji.style.transition = 'all 0.8s ease-out';
      
      document.body.appendChild(emoji);

      requestAnimationFrame(() => {
        emoji.style.transform = `translate(${(Math.random() - 0.5) * 100}px, -100px) scale(1.5)`;
        emoji.style.opacity = '0';
      });

      setTimeout(() => emoji.remove(), 800);
    }

    // --- 3. Подсветка карточки следом от мыши ---
    const glowCard = document.getElementById('glowCard');
    glowCard.addEventListener('mousemove', (e) => {
      const rect = glowCard.getBoundingClientRect();
      const x = ((e.clientX - rect.left) / rect.width) * 100;
      const y = ((e.clientY - rect.top) / rect.height) * 100;
      glowCard.style.setProperty('--mouse-x', `${x}%`);
      glowCard.style.setProperty('--mouse-y', `${y}%`);
    });
  </script>
</body>
</html>
