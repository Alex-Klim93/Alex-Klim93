# 🚀 Веб-разработка и вёрстка сайтов на Tilda 

<div align="center">
  <img src="https://img.icons8.com/color/96/000000/html-5--v1.png" alt="HTML5" width="60"/>
  <img src="https://img.icons8.com/color/96/000000/css3.png" alt="CSS3" width="60"/>
  <img src="https://img.icons8.com/ios-filled/100/000000/tilda.png" alt="Tilda" width="60"/>
</div>

Профессиональная вёрстка и разработка сайтов на платформе Tilda с индивидуальным подходом к каждому проекту.

---

## 💎 Наши услуги

<div class="services-grid" markdown="1">

- ✔️ Разработка сайтов на Tilda "под ключ"
- ✔️ Адаптивная и кросс-браузерная вёрстка
- ✔️ Кастомизация Zero-блоков
- ✔️ Создание сложных анимаций
- ✔️ Оптимизация скорости загрузки
- ✔️ SEO-базовая настройка
- ✔️ Интеграция с CRM и сервисами
- ✔️ Обучение работе с Tilda

</div>

---

## 💵 Прайс-лист

<div class="price-cards" markdown="1">

<div class="price-card" markdown="1">
![Лендинг](https://via.placeholder.com/300x200/4CAF50/FFFFFF?text=Лендинг)
### Лендинг
**От 15 000 ₽**  
⏳ Срок: 3-5 дней  
Идеальное решение для презентации продукта или услуги с высокой конверсией.
</div>

<div class="price-card" markdown="1">
![Корпоративный сайт](https://via.placeholder.com/300x200/2196F3/FFFFFF?text=Корпоративный)
### Корпоративный сайт
**От 30 000 ₽**  
⏳ Срок: 7-14 дней  
Профессиональный имидж компании с удобной структурой и функционалом.
</div>

<div class="price-card" markdown="1">
![Интернет-магазин](https://via.placeholder.com/300x200/FF5722/FFFFFF?text=Магазин)
### Интернет-магазин
**От 50 000 ₽**  
⏳ Срок: 14-21 день  
Полнофункциональный магазин с корзиной, оплатой и личным кабинетом.
</div>

</div>

---

## 🏆 Примеры работ

<div class="portfolio-grid" markdown="1">

<div class="portfolio-card" markdown="1">
[![Проект 1](https://via.placeholder.com/300x200/9C27B0/FFFFFF?text=Салон+красоты)](https://example.com)
### Салон красоты "Элегант"
Лендинг для салона премиум-класса с онлайн-записью и галереей работ.
</div>

<div class="portfolio-card" markdown="1">
[![Проект 2](https://via.placeholder.com/300x200/3F51B5/FFFFFF?text=Строительная+компания)](https://example.com)
### Строительная компания "Профит"
Корпоративный сайт с каталогом услуг и калькулятором стоимости.
</div>

<div class="portfolio-card" markdown="1">
[![Проект 3](https://via.placeholder.com/300x200/009688/FFFFFF?text=Кофейня)](https://example.com)
### Кофейня "Aroma"
Интернет-магазин с возможностью онлайн-заказа и доставки.
</div>

</div>

---

## 📞 Контакты

<div class="contacts" markdown="1">

📧 **Email**: [dev@example.com](mailto:dev@example.com)  
📱 **Telegram**: [@tilda_dev](https://t.me/tilda_dev)  
💼 **Behance**: [behance.net/tilda_projects](https://behance.net/tilda_projects)  

📍 **Режим работы**: Пн-Пт, 10:00-18:00  

</div>

<style>
/* Анимации и стили */
.price-cards, .portfolio-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  margin: 30px 0;
}

.price-card, .portfolio-card {
  background: white;
  border-radius: 10px;
  padding: 15px;
  width: 300px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s, box-shadow 0.3s;
}

.price-card:hover, .portfolio-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.15);
}

.price-card img, .portfolio-card img {
  border-radius: 8px;
  margin-bottom: 10px;
  width: 100%;
}

.services-grid {
  background: #f8f9fa;
  padding: 20px;
  border-radius: 10px;
  margin: 20px 0;
}

.services-grid ul {
  columns: 2;
  list-style-type: none;
  padding: 0;
}

.services-grid li {
  padding: 8px 0;
  position: relative;
  padding-left: 25px;
}

.services-grid li:before {
  content: "→";
  position: absolute;
  left: 0;
  color: #4CAF50;
}

.contacts {
  background: #4CAF50;
  color: white;
  padding: 20px;
  border-radius: 10px;
  text-align: center;
}

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

.price-card, .portfolio-card {
  animation: fadeIn 0.5s ease-in-out;
}

.price-card:nth-child(1) { animation-delay: 0.1s; }
.price-card:nth-child(2) { animation-delay: 0.3s; }
.price-card:nth-child(3) { animation-delay: 0.5s; }

@media (max-width: 768px) {
  .price-cards, .portfolio-grid {
    flex-direction: column;
    align-items: center;
  }
  
  .services-grid ul {
    columns: 1;
  }
}
</style>
