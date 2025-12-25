<!-- Анимированный заголовок -->
<h1 align="center" style="
    font-size: 2.5em;
    background: linear-gradient(45deg, #FF6B6B, #4ECDC4, #45B7D1, #96CEB4, #FFEAA7);
    background-size: 400% 400%;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: gradient 8s ease infinite;
    margin-bottom: 20px;
">✨ Профессиональная вёрстка сайтов ✨</h1>

<!-- Анимированные иконки технологий -->
<div align="center" style="margin: 30px 0;">
  <div class="tech-icons" style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap;">
    <img src="https://img.icons8.com/color/96/000000/html-5.png" title="HTML5" 
         style="transition: transform 0.3s; filter: drop-shadow(0 4px 6px rgba(0,0,0,0.1));"
         onmouseover="this.style.transform='scale(1.2) rotate(5deg)'"
         onmouseout="this.style.transform='scale(1) rotate(0deg)'">
    <img src="https://img.icons8.com/color/96/000000/css3.png" title="CSS3"
         style="transition: transform 0.3s; filter: drop-shadow(0 4px 6px rgba(0,0,0,0.1));"
         onmouseover="this.style.transform='scale(1.2) rotate(-5deg)'"
         onmouseout="this.style.transform='scale(1) rotate(0deg)'">
    <img src="https://img.icons8.com/color/96/000000/javascript.png" title="JavaScript"
         style="transition: transform 0.3s; filter: drop-shadow(0 4px 6px rgba(0,0,0,0.1));"
         onmouseover="this.style.transform='scale(1.2) translateY(-10px)'"
         onmouseout="this.style.transform='scale(1) translateY(0)'">
    <img src="https://img.icons8.com/color/96/000000/react-native.png" title="React"
         style="transition: transform 0.3s; filter: drop-shadow(0 4px 6px rgba(0,0,0,0.1));"
         onmouseover="this.style.transform='scale(1.2) rotate(360deg)'; this.style.transition='transform 0.6s'"
         onmouseout="this.style.transform='scale(1) rotate(0deg)'; this.style.transition='transform 0.3s'">
    <img src="https://img.icons8.com/color/96/000000/vue-js.png" title="Vue.js"
         style="transition: transform 0.3s; filter: drop-shadow(0 4px 6px rgba(0,0,0,0.1));"
         onmouseover="this.style.transform='scale(1.2)'"
         onmouseout="this.style.transform='scale(1)'">
  </div>
</div>

<!-- Анимированная карточка с текстом -->
<div align="center" style="
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    padding: 30px;
    border-radius: 15px;
    margin: 30px auto;
    max-width: 800px;
    box-shadow: 0 20px 40px rgba(102, 126, 234, 0.3);
    transition: all 0.4s ease;
    position: relative;
    overflow: hidden;
" 
onmouseover="this.style.transform='translateY(-5px)'; this.style.boxShadow='0 25px 50px rgba(102, 126, 234, 0.4)'"
onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 20px 40px rgba(102, 126, 234, 0.3)'">
  
  <div style="
      position: absolute;
      top: -50%;
      left: -50%;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle, rgba(255,255,255,0.1) 1%, transparent 1%);
      background-size: 50px 50px;
      animation: moveBackground 20s linear infinite;
  "></div>
  
  <h2 style="color: white; font-size: 1.8em; margin-bottom: 15px; position: relative;">
    🚀 Превращаю дизайн в код
  </h2>
  <p style="color: rgba(255,255,255,0.9); font-size: 1.1em; line-height: 1.5; position: relative;">
    Создаю <strong style="color: #FFD700;">адаптивные</strong>, 
    <strong style="color: #FFD700;">кросс-браузерные</strong> и 
    <strong style="color: #FFD700;">быстрые</strong> интерфейсы.<br>
    Pixel-perfect вёрстка по макетам Figma/Photoshop с анимациями и интерактивом.
  </p>
</div>

<!-- Анимированные карточки услуг с 3D эффектом -->
<div align="center">
  <h2 style="
      font-size: 2em;
      color: #333;
      margin: 40px 0 30px;
      position: relative;
      display: inline-block;
  ">
    💼 Мои услуги
    <div style="
        position: absolute;
        bottom: -10px;
        left: 0;
        width: 100%;
        height: 3px;
        background: linear-gradient(90deg, transparent, #667eea, transparent);
        animation: underline 3s ease-in-out infinite;
    "></div>
  </h2>
</div>

<div style="
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
    margin: 30px 0;
">

<!-- Карточка 1 -->
<div style="
    background: white;
    border-radius: 15px;
    padding: 25px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    border: 2px solid transparent;
    position: relative;
    overflow: hidden;
"
onmouseover="
    this.style.transform='translateY(-10px) scale(1.02)';
    this.style.boxShadow='0 20px 40px rgba(102, 126, 234, 0.2)';
    this.style.borderColor='#667eea';
"
onmouseout="
    this.style.transform='translateY(0) scale(1)';
    this.style.boxShadow='0 10px 30px rgba(0,0,0,0.1)';
    this.style.borderColor='transparent';
">
  <div style="
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 4px;
      background: linear-gradient(90deg, #FF6B6B, #4ECDC4);
  "></div>
  
  <h3 style="color: #2c3e50; margin-bottom: 15px; display: flex; align-items: center; gap: 10px;">
    <span style="
        background: linear-gradient(135deg, #FF6B6B, #FF8E53);
        width: 40px;
        height: 40px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        color: white;
        font-size: 1.2em;
    ">🎨</span>
    Pixel Perfect вёрстка
  </h3>
  <p style="color: #666; line-height: 1.6;">
    Точное соответствие макету, семантическая разметка, валидный код.
  </p>
  <div style="margin-top: 20px; padding-top: 20px; border-top: 1px dashed #eee;">
    <span style="
        display: inline-block;
        background: linear-gradient(135deg, #FF6B6B, #FF8E53);
        color: white;
        padding: 8px 20px;
        border-radius: 25px;
        font-weight: bold;
        font-size: 1.1em;
    ">от 10 000 ₽</span>
  </div>
</div>

<!-- Карточка 2 -->
<div style="
    background: white;
    border-radius: 15px;
    padding: 25px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    border: 2px solid transparent;
    position: relative;
    overflow: hidden;
"
onmouseover="
    this.style.transform='translateY(-10px) scale(1.02)';
    this.style.boxShadow='0 20px 40px rgba(52, 152, 219, 0.2)';
    this.style.borderColor='#3498db';
"
onmouseout="
    this.style.transform='translateY(0) scale(1)';
    this.style.boxShadow='0 10px 30px rgba(0,0,0,0.1)';
    this.style.borderColor='transparent';
">
  <div style="
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 4px;
      background: linear-gradient(90deg, #3498db, #2ecc71);
  "></div>
  
  <h3 style="color: #2c3e50; margin-bottom: 15px; display: flex; align-items: center; gap: 10px;">
    <span style="
        background: linear-gradient(135deg, #3498db, #2ecc71);
        width: 40px;
        height: 40px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        color: white;
        font-size: 1.2em;
    ">📱</span>
    Адаптивный дизайн
  </h3>
  <p style="color: #666; line-height: 1.6;">
    Идеальное отображение на всех устройствах от смартфона до 4K монитора.
  </p>
  <div style="margin-top: 20px; padding-top: 20px; border-top: 1px dashed #eee;">
    <span style="
        display: inline-block;
        background: linear-gradient(135deg, #3498db, #2ecc71);
        color: white;
        padding: 8px 20px;
        border-radius: 25px;
        font-weight: bold;
        font-size: 1.1em;
    ">от 15 000 ₽</span>
  </div>
</div>

<!-- Карточка 3 -->
<div style="
    background: white;
    border-radius: 15px;
    padding: 25px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    border: 2px solid transparent;
    position: relative;
    overflow: hidden;
"
onmouseover="
    this.style.transform='translateY(-10px) scale(1.02)';
    this.style.boxShadow='0 20px 40px rgba(155, 89, 182, 0.2)';
    this.style.borderColor='#9b59b6';
"
onmouseout="
    this.style.transform='translateY(0) scale(1)';
    this.style.boxShadow='0 10px 30px rgba(0,0,0,0.1)';
    this.style.borderColor='transparent';
">
  <div style="
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 4px;
      background: linear-gradient(90deg, #9b59b6, #e74c3c);
  "></div>
  
  <h3 style="color: #2c3e50; margin-bottom: 15px; display: flex; align-items: center; gap: 10px;">
    <span style="
        background: linear-gradient(135deg, #9b59b6, #e74c3c);
        width: 40px;
        height: 40px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        color: white;
        font-size: 1.2em;
    ">⚡</span>
    Интерактив + анимации
  </h3>
  <p style="color: #666; line-height: 1.6;">
    Современные анимации, параллакс-эффекты, плавные переходы.
  </p>
  <div style="margin-top: 20px; padding-top: 20px; border-top: 1px dashed #eee;">
    <span style="
        display: inline-block;
        background: linear-gradient(135deg, #9b59b6, #e74c3c);
        color: white;
        padding: 8px 20px;
        border-radius: 25px;
        font-weight: bold;
        font-size: 1.1em;
    ">от 20 000 ₽</span>
  </div>
</div>

</div>

<!-- Анимированный прайс-лист -->
<div align="center" style="margin: 50px 0;">
  <h2 style="
      font-size: 2em;
      color: #333;
      margin-bottom: 40px;
      position: relative;
      display: inline-block;
  ">
    💰 Прайс-лист
    <span style="
        position: absolute;
        right: -30px;
        top: -10px;
        background: #e74c3c;
        color: white;
        padding: 5px 10px;
        border-radius: 15px;
        font-size: 0.5em;
        animation: pulse 2s infinite;
    ">HOT</span>
  </h2>
</div>

<div style="
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    perspective: 1000px;
">

<!-- Тариф 1 -->
<div style="
    background: linear-gradient(145deg, #ffffff, #f8f9fa);
    border-radius: 20px;
    padding: 30px;
    box-shadow: 20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff;
    transition: all 0.5s ease;
    position: relative;
    transform-style: preserve-3d;
    transform: rotateY(0deg);
"
onmouseover="
    this.style.transform='rotateY(10deg) translateY(-20px)';
    this.querySelector('.price-tag').style.transform='scale(1.1)';
"
onmouseout="
    this.style.transform='rotateY(0deg) translateY(0)';
    this.querySelector('.price-tag').style.transform='scale(1)';
">
  <div class="price-tag" style="
      background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
      color: white;
      padding: 15px;
      border-radius: 15px;
      font-size: 2em;
      font-weight: bold;
      text-align: center;
      margin-bottom: 20px;
      transition: transform 0.3s;
  ">
    Лендинг
  </div>
  
  <h3 style="color: #333; text-align: center; margin-bottom: 20px;">Одностраничный сайт</h3>
  
  <ul style="color: #666; padding-left: 20px; margin-bottom: 30px;">
    <li style="margin-bottom: 10px; transition: all 0.3s;" 
        onmouseover="this.style.color='#f5576c'; this.style.paddingLeft='10px'"
        onmouseout="this.style.color='#666'; this.style.paddingLeft='0'">✅ Адаптивная вёрстка</li>
    <li style="margin-bottom: 10px; transition: all 0.3s;"
        onmouseover="this.style.color='#f5576c'; this.style.paddingLeft='10px'"
        onmouseout="this.style.color='#666'; this.style.paddingLeft='0'">✅ Базовые анимации</li>
    <li style="margin-bottom: 10px; transition: all 0.3s;"
        onmouseover="this.style.color='#f5576c'; this.style.paddingLeft='10px'"
        onmouseout="this.style.color='#666'; this.style.paddingLeft='0'">✅ Оптимизация скорости</li>
    <li style="transition: all 0.3s;"
        onmouseover="this.style.color='#f5576c'; this.style.paddingLeft='10px'"
        onmouseout="this.style.color='#666'; this.style.paddingLeft='0'">✅ Форма обратной связи</li>
  </ul>
  
  <div style="text-align: center;">
    <div style="
        background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
        color: white;
        display: inline-block;
        padding: 12px 40px;
        border-radius: 50px;
        font-weight: bold;
        font-size: 1.2em;
        cursor: pointer;
        transition: all 0.3s;
        box-shadow: 0 10px 20px rgba(245, 87, 108, 0.3);
    "
    onmouseover="this.style.transform='translateY(-3px)'; this.style.boxShadow='0 15px 30px rgba(245, 87, 108, 0.4)'"
    onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 10px 20px rgba(245, 87, 108, 0.3)'"
    onclick="alert('Заказ лендинга от 10 000 ₽')">
      от 10 000 ₽
    </div>
    <p style="color: #999; margin-top: 10px; font-size: 0.9em;">⏱ Срок: 3-5 дней</p>
  </div>
</div>

<!-- Тариф 2 (выделенный) -->
<div style="
    background: linear-gradient(145deg, #667eea, #764ba2);
    border-radius: 20px;
    padding: 30px;
    box-shadow: 0 25px 50px rgba(102, 126, 234, 0.4);
    transition: all 0.5s ease;
    position: relative;
    transform: scale(1.05);
    color: white;
"
onmouseover="
    this.style.transform='scale(1.08) translateY(-10px)';
    this.style.boxShadow='0 35px 70px rgba(102, 126, 234, 0.6)';
"
onmouseout="
    this.style.transform='scale(1.05) translateY(0)';
    this.style.boxShadow='0 25px 50px rgba(102, 126, 234, 0.4)';
">
  <div style="
      position: absolute;
      top: -15px;
      left: 50%;
      transform: translateX(-50%);
      background: #FFD700;
      color: #333;
      padding: 8px 25px;
      border-radius: 25px;
      font-weight: bold;
      font-size: 0.9em;
      animation: bounce 2s infinite;
  ">
    🏆 ПОПУЛЯРНЫЙ
  </div>
  
  <div style="
      background: rgba(255,255,255,0.15);
      color: white;
      padding: 15px;
      border-radius: 15px;
      font-size: 2em;
      font-weight: bold;
      text-align: center;
      margin: 20px 0;
      backdrop-filter: blur(10px);
  ">
    Интернет-магазин
  </div>
  
  <h3 style="color: white; text-align: center; margin-bottom: 20px;">Полноценный e-commerce</h3>
  
  <ul style="color: rgba(255,255,255,0.9); padding-left: 20px; margin-bottom: 30px;">
    <li style="margin-bottom: 10px;">✅ Каталог товаров с фильтрами</li>
    <li style="margin-bottom: 10px;">✅ Корзина и оформление заказа</li>
    <li style="margin-bottom: 10px;">✅ Личный кабинет пользователя</li>
    <li>✅ Интеграция с платежными системами</li>
  </ul>
  
  <div style="text-align: center;">
    <div style="
        background: white;
        color: #667eea;
        display: inline-block;
        padding: 12px 40px;
        border-radius: 50px;
        font-weight: bold;
        font-size: 1.2em;
        cursor: pointer;
        transition: all 0.3s;
        box-shadow: 0 10px 20px rgba(255,255,255,0.2);
    "
    onmouseover="this.style.transform='translateY(-3px) scale(1.1)'; this.style.boxShadow='0 15px 30px rgba(255,255,255,0.3)'"
    onmouseout="this.style.transform='translateY(0) scale(1)'; this.style.boxShadow='0 10px 20px rgba(255,255,255,0.2)'"
    onclick="alert('Заказ интернет-магазина от 40 000 ₽')">
      от 40 000 ₽
    </div>
    <p style="color: rgba(255,255,255,0.7); margin-top: 10px; font-size: 0.9em;">⏱ Срок: 10-15 дней</p>
  </div>
</div>

<!-- Тариф 3 -->
<div style="
    background: linear-gradient(145deg, #ffffff, #f8f9fa);
    border-radius: 20px;
    padding: 30px;
    box-shadow: 20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff;
    transition: all 0.5s ease;
    position: relative;
    transform-style: preserve-3d;
    transform: rotateY(0deg);
"
onmouseover="
    this.style.transform='rotateY(-10deg) translateY(-20px)';
    this.querySelector('.price-tag').style.transform='scale(1.1)';
"
onmouseout="
    this.style.transform='rotateY(0deg) translateY(0)';
    this.querySelector('.price-tag').style.transform='scale(1)';
">
  <div class="price-tag" style="
      background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
      color: white;
      padding: 15px;
      border-radius: 15px;
      font-size: 2em;
      font-weight: bold;
      text-align: center;
      margin-bottom: 20px;
      transition: transform 0.3s;
  ">
    SPA Приложение
  </div>
  
  <h3 style="color: #333; text-align: center; margin-bottom: 20px;">React/Vue приложение</h3>
  
  <ul style="color: #666; padding-left: 20px; margin-bottom: 30px;">
    <li style="margin-bottom: 10px; transition: all 0.3s;"
        onmouseover="this.style.color='#00f2fe'; this.style.paddingLeft='10px'"
        onmouseout="this.style.color='#666'; this.style.paddingLeft='0'">✅ Современный фреймворк</li>
    <li style="margin-bottom: 10px; transition: all 0.3s;"
        onmouseover="this.style.color='#00f2fe'; this.style.paddingLeft='10px'"
        onmouseout="this.style.color='#666'; this.style.paddingLeft='0'">✅ Интеграция с API</li>
    <li style="margin-bottom: 10px; transition: all 0.3s;"
        onmouseover="this.style.color='#00f2fe'; this.style.paddingLeft='10px'"
        onmouseout="this.style.color='#666'; this.style.paddingLeft='0'">✅ Админ-панель</li>
    <li style="transition: all 0.3s;"
        onmouseover="this.style.color='#00f2fe'; this.style.paddingLeft='10px'"
        onmouseout="this.style.color='#666'; this.style.paddingLeft='0'">✅ Аутентификация</li>
  </ul>
  
  <div style="text-align: center;">
    <div style="
        background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
        color: white;
        display: inline-block;
        padding: 12px 40px;
        border-radius: 50px;
        font-weight: bold;
        font-size: 1.2em;
        cursor: pointer;
        transition: all 0.3s;
        box-shadow: 0 10px 20px rgba(0, 242, 254, 0.3);
    "
    onmouseover="this.style.transform='translateY(-3px)'; this.style.boxShadow='0 15px 30px rgba(0, 242, 254, 0.4)'"
    onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 10px 20px rgba(0, 242, 254, 0.3)'"
    onclick="alert('Заказ SPA приложения от 60 000 ₽')">
      от 60 000 ₽
    </div>
    <p style="color: #999; margin-top: 10px; font-size: 0.9em;">⏱ Срок: 15-25 дней</p>
  </div>
</div>

</div>

<!-- Анимированная кнопка заказа -->
<div align="center" style="margin: 60px 0;">
  <div style="
      position: relative;
      display: inline-block;
      cursor: pointer;
  "
  onclick="
      this.style.transform='scale(0.95)';
      setTimeout(() => this.style.transform='scale(1)', 200);
      setTimeout(() => alert('Спасибо за интерес! Свяжусь с вами в ближайшее время!'), 300);
  ">
    <div style="
        background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
        color: white;
        padding: 20px 60px;
        border-radius: 60px;
        font-size: 1.5em;
        font-weight: bold;
        box-shadow: 0 20px 40px rgba(245, 87, 108, 0.4);
        transition: all 0.3s;
        position: relative;
        z-index: 2;
        border: none;
    "
    onmouseover="
        this.style.transform='translateY(-5px)';
        this.style.boxShadow='0 25px 50px rgba(245, 87, 108, 0.6)';
    "
    onmouseout="
        this.style.transform='translateY(0)';
        this.style.boxShadow='0 20px 40px rgba(245, 87, 108, 0.4)';
    ">
      🚀 Заказать вёрстку прямо сейчас!
    </div>
    
    <div style="
        position: absolute;
        top: 10px;
        left: 10px;
        right: 10px;
        bottom: -10px;
        background: rgba(245, 87, 108, 0.2);
        border-radius: 60px;
        filter: blur(10px);
        z-index: 1;
        animation: pulseGlow 2s infinite;
    "></div>
  </div>
</div>

<!-- Анимированный блок контактов -->
<div align="center" style="
    background: linear-gradient(135deg, #1a2a6c, #2c3e50);
    padding: 50px 30px;
    border-radius: 25px;
    margin: 50px auto;
    max-width: 900px;
    color: white;
    position: relative;
    overflow: hidden;
">
  <!-- Анимированные частицы -->
  <div style="
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
  ">
    <div style="
        position: absolute;
        width: 3px;
        height: 3px;
        background: rgba(255,255,255,0.5);
        border-radius: 50%;
        animation: particles 15s infinite linear;
        top: 20%;
        left: 10%;
    "></div>
    <div style="
        position: absolute;
        width: 2px;
        height: 2px;
        background: rgba(255,255,255,0.3);
        border-radius: 50%;
        animation: particles 20s infinite linear;
        animation-delay: 2s;
        top: 40%;
        left: 80%;
    "></div>
    <div style="
        position: absolute;
        width: 4px;
        height: 4px;
        background: rgba(255,255,255,0.4);
        border-radius: 50%;
        animation: particles 12s infinite linear;
        animation-delay: 5s;
        top: 70%;
        left: 30%;
    "></div>
  </div>
  
  <h2 style="font-size: 2.2em; margin-bottom: 30px; position: relative;">
    📞 Связаться со мной
  </h2>
  
  <div style="
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 30px;
      margin-bottom: 40px;
  ">
    
    <div style="
        background: rgba(255,255,255,0.1);
        padding: 25px;
        border-radius: 15px;
        backdrop-filter: blur(10px);
        transition: all 0.3s;
        cursor: pointer;
    "
    onmouseover="
        this.style.transform='translateY(-10px)';
        this.style.background='rgba(255,255,255,0.2)';
    "
    onmouseout="
        this.style.transform='translateY(0)';
        this.style.background='rgba(255,255,255,0.1)';
    "
    onclick="window.open('mailto:hello@frontend.dev', '_blank')">
      <div style="font-size: 3em; margin-bottom: 15px;">📧</div>
      <h3 style="margin-bottom: 10px;">Email</h3>
      <p style="color: rgba(255,255,255,0.8);">hello@frontend.dev</p>
    </div>
    
    <div style="
        background: rgba(255,255,255,0.1);
        padding: 25px;
        border-radius: 15px;
        backdrop-filter: blur(10px);
        transition: all 0.3s;
        cursor: pointer;
    "
    onmouseover="
        this.style.transform='translateY(-10px)';
        this.style.background='rgba(255,255,255,0.2)';
    "
    onmouseout="
        this.style.transform='translateY(0)';
        this.style.background='rgba(255,255,255,0.1)';
    "
    onclick="window.open('https://t.me/frontend_dev', '_blank')">
      <div style="font-size: 3em; margin-bottom: 15px;">📱</div>
      <h3 style="margin-bottom: 10px;">Telegram</h3>
      <p style="color: rgba(255,255,255,0.8);">@frontend_dev</p>
    </div>
    
    <div style="
        background: rgba(255,255,255,0.1);
        padding: 25px;
        border-radius: 15px;
        backdrop-filter: blur(10px);
        transition: all 0.3s;
        cursor: pointer;
    "
    onmouseover="
        this.style.transform='translateY(-10px)';
        this.style.background='rgba(255,255,255,0.2)';
    "
    onmouseout="
        this.style.transform='translateY(0)';
        this.style.background='rgba(255,255,255,0.1)';
    "
    onclick="window.open('https://github.com/frontend-dev', '_blank')">
      <div style="font-size: 3em; margin-bottom: 15px;">💻</div>
      <h3 style="margin-bottom: 10px;">GitHub</h3>
      <p style="color: rgba(255,255,255,0.8);">frontend-dev</p>
    </div>
    
  </div>
  
  <p style="
      color: rgba(255,255,255,0.7);
      font-style: italic;
      margin-top: 30px;
      font-size: 0.9em;
  ">
    Работаю с 10:00 до 19:00 по МСК • Ответ в течение 2 часов
  </p>
</div>

<!-- CSS анимации -->
<style>
@keyframes gradient {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

@keyframes moveBackground {
  0% { transform: translate(0, 0) rotate(0deg); }
  100% { transform: translate(-50px, -50px) rotate(360deg); }
}

@keyframes underline {
  0%, 100% { width: 0; left: 50%; }
  50% { width: 100%; left: 0; }
}

@keyframes pulse {
  0%, 100% { transform: scale(1); opacity: 1; }
  50% { transform: scale(1.1); opacity: 0.8; }
}

@keyframes bounce {
  0%, 100% { transform: translateX(-50%) translateY(0); }
  50% { transform: translateX(-50%) translateY(-5px); }
}

@keyframes pulseGlow {
  0%, 100% { opacity: 0.5; transform: scale(1); }
  50% { opacity: 0.8; transform: scale(1.05); }
}

@keyframes particles {
  0% { transform: translateY(0) translateX(0); opacity: 1; }
  100% { transform: translateY(-100px) translateX(100px); opacity: 0; }
}

/* Для плавного скролла к якорям */
html {
  scroll-behavior: smooth;
}

/* Анимация появления при скролле */
.fade-in {
  opacity: 0;
  transform: translateY(30px);
  transition: all 0.6s ease-out;
}

.fade-in.visible {
  opacity: 1;
  transform: translateY(0);
}
</style>

<!-- JavaScript для анимаций при скролле -->
<script>
// Анимация появления при скролле
document.addEventListener('DOMContentLoaded', function() {
  const fadeElements = document.querySelectorAll('.fade-in');
  
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  }, { threshold: 0.1 });
  
  fadeElements.forEach(el => observer.observe(el));
  
  // Добавляем класс fade-in ко всем основным блокам
  const blocks = document.querySelectorAll('div[style*="background"]');
  blocks.forEach((block, index) => {
    if (!block.classList.contains('fade-in')) {
      block.classList.add('fade-in');
      block.style.animationDelay = `${index * 0.1}s`;
    }
  });
});

// Функция для имитации чата
function startChat() {
  const messages = [
    "👋 Привет! Готов обсудить ваш проект?",
    "📝 Расскажите о вашей задаче...",
    "💬 Отправлю оценку в течение часа!",
    "🚀 Начнем работу сразу после договоренности!"
  ];
  
  let current = 0;
  const chatBox = document.createElement('div');
  chatBox.style.cssText = `
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: white;
    border-radius: 15px;
    padding: 15px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.2);
    z-index: 1000;
    max-width: 300px;
    animation: slideIn 0.5s ease;
  `;
  
  chatBox.innerHTML = `
    <div style="font-weight: bold; margin-bottom: 10px;">💬 Онлайн-чат</div>
    <div id="chat-message">${messages[current]}</div>
    <button onclick="nextMessage()" style="
      background: #667eea;
      color: white;
      border: none;
      padding: 8px 20px;
      border-radius: 20px;
      margin-top: 10px;
      cursor: pointer;
    ">Далее</button>
  `;
  
  document.body.appendChild(chatBox);
  
  window.nextMessage = function() {
    current = (current + 1) % messages.length;
    document.getElementById('chat-message').textContent = messages[current];
    
    if (current === messages.length - 1) {
      setTimeout(() => {
        chatBox.style.animation = 'slideOut 0.5s ease';
        setTimeout(() => chatBox.remove(), 500);
      }, 3000);
    }
  };
}

// Запуск чата при клике на кнопку (можно добавить кнопку)
</script>

<div align="center" style="margin-top: 50px; padding: 20px; border-top: 1px solid #eee;">
  <p style="color: #666; font-size: 0.9em;">
    💡 <strong>Совет:</strong> Наведи курсор на элементы, чтобы увидеть анимации!
  </p>
  <p style="color: #999; margin-top: 10px;">
    🚀 Frontend Developer • Верстка с 2018 года • 100+ успешных проектов
  </p>
</div>
