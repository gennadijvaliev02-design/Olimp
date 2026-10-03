# 🏆 Спортивный комплекс «Олимп»

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Online-success?style=for-the-badge&logo=githubpages&logoColor=white)](https://gennadijvaliev02-design.github.io/Olimp/)
[![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile--First-blueviolet?style=for-the-badge)](https://gennadijvaliev02-design.github.io/Olimp/)

> Официальный интерактивный портал и сервис онлайн-бронирования тренировок для многофункционального спортивного комплекса «Олимп».  
> Проект сочетает динамичную спортивную типографику, интерактивную 3D-графику на **Three.js**, плавные бесконечные карусели и продуманную систему онлайн-записи.

🔗 **Рабочий сайт**: [https://gennadijvaliev02-design.github.io/Olimp/](https://gennadijvaliev02-design.github.io/Olimp/)

---

## ⚡ Ключевые возможности (Key Highlights)

- **Интерактивная 3D-витрина «Символы победы»**:
  - Реализована на **Three.js** с процедурным освещением и материалами.
  - Интерактивный олимпийский факел с динамическим пульсирующим пламенем, кубок, медаль и почетная грамота.
  - Реагирует на движение курсора, скролл и сенсорные жесты (свайпы) на смартфонах.
  - Предусмотрен элегантный fallback на случай отсутствия поддержки WebGL.
- **Бесконечная карусель направлений подготовки**:
  - 8 ключевых видов спорта: *Бокс, Плавание, Штанга, Армрестлинг, Гимнастика, Лёгкая атлетика, Тренажёрный зал, Вольная борьба*.
  - Автоматическая плавная прокрутка с возможностью ручного управления стрелками и паузы при взаимодействии.
  - Каждая карточка позволяет в один клик открыть запись с уже предустановленным направлением.
- **Галерея чемпионов и резидентов**:
  - Карточки великих спортсменов и наставников комплекса.
  - Плавное переключение через табы на десктопе и горизонтальный нативный свайп на смартфонах.
- **Многоэтапная онлайн-запись**:
  - Модальное окно с валидацией контактных данных.
  - Маска телефонного номера `+7 (___) ___-__-__`.
  - Динамический календарь с блокировкой прошедших дат.
  - Экран успешной заявки с персональным электронным подтверждением.
- **Интерактивная навигация и карта**:
  - Стилизованная векторная интерактивная карта расположения спорткомплекса на Олимпийском проспекте.
  - Прямые ссылки на построение маршрута в Яндекс Картах, быстрый набор телефона и отправку email.
- **Мобильная оптимизация & PWA-ready**:
  - Оптимизированные ассеты в формате **WebP** с низким весом и приоритетной загрузкой hero-секции.
  - Настроен `site.webmanifest`, иконки 192x192, 512x512 и `apple-touch-icon`.

---

## 📂 Структура проекта

```text
Olimp/
├── .github/
│   └── workflows/
│       └── deploy-pages.yml        # CI/CD автоматический деплой на GitHub Pages
├── vendor/
│   ├── three.core.min.js           # Three.js 3D-библиотека
│   ├── three.module.min.js
│   └── three-LICENSE.txt
├── index.html                      # Основная семантическая разметка и логика приложения
├── hero-olimp-concept.webp         # Главный баннер (WebP)
├── logotip-transparent.webp        # Прозрачный логотип комплекса
├── og-olimp.jpg                    # Превью для соцсетей (Open Graph 1200x630)
├── site.webmanifest                # Манифест PWA для мобильных
├── favicon.ico / favicon-32.png    # Иконки сайта
└── README.md                       # Документация проекта
```

---

## 🚀 Локальный запуск

Сайт работает автономно и не требует сборки. Для запуска интерактивной 3D-сцены рекомендуется локальный HTTP-сервер:

```bash
# 1. Клонирование репозитория
git clone https://github.com/gennadijvaliev02-design/Olimp.git

# 2. Переход в каталог
cd Olimp

# 3. Запуск локального веб-сервера
python3 -m http.server 3000
# или
npx serve .
```

Открыть в браузере: `http://localhost:3000`.

---

## 🛠 Технологический стек

- **Frontend**: HTML5 (семантика, доступность WAI-ARIA), CSS3 (Custom Variables, Flexbox, Grid, CSS Animations, Media Queries).
- **3D & Canvas**: Three.js (WebGL, шейдеры, динамический свет, 3D-меши).
- **Core Scripting**: Vanilla JavaScript (ES6+ modular architecture, Touch Events, ResizeObserver).
- **CI/CD**: GitHub Actions (автоматический деплой в GitHub Pages при пуше в `main`).

---

## 📬 Контакты и авторство

- **Разработчик**: [@gennadijvaliev02-design](https://github.com/gennadijvaliev02-design)
