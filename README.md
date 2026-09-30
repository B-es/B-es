<!-- README для профильного репозитория https://github.com/B-es/B-es (файл README.md, ветка main) -->

<h1 align="center">Иван Васильев</h1>

<p align="center">
  <b>Backend / Fullstack разработчик · Python + интеграции · Vue 3 / TypeScript на фронтенде</b><br>
  Магистрант ВолгГТУ (САПР-2.1) · проектирую REST-сервисы, подключаю внешние API и автоматизирую рутину
</p>

<p align="center">
  <a href="https://github.com/B-es?tab=repositories"><img alt="Public repositories" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FB-es&query=%24.public_repos&label=repositories&logo=github&color=181717&style=flat-square"></a>
  <img alt="Python" src="https://img.shields.io/badge/Python-backend-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
  <img alt="Django" src="https://img.shields.io/badge/Django%20%2B%20DRF-092E20?style=flat-square&logo=django&logoColor=white">
  <img alt="Vue 3 + TypeScript" src="https://img.shields.io/badge/Vue%203%20%2B%20TS-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white">
  <img alt="Flutter / Dart" src="https://img.shields.io/badge/Flutter%20%2F%20Dart-02569B?style=flat-square&logo=flutter&logoColor=white">
</p>

---

## 🧭 Чем занимаюсь

- **Бэкенд и API.** Проектирую REST-сервисы на **FastAPI** и **Django + DRF**: роутеры, схемы, ORM-слой, авторизация по **JWT**, фоновые задачи по расписанию (**APScheduler**), интеграция с БД (**PostgreSQL**, SQLite).
- **Интеграции — основная специализация.** Платёжные шлюзы и обработка вебхуков (**Epoint**, **SSLCcommerce / Privat24**), LLM-провайдеры (**Mistral**, **OpenAI**, Hugging Face), боты **VK** и **Telegram**, обёртки сторонних REST API.
- **Парсинг и автоматизация.** Selenium, requests + BeautifulSoup, асинхронные сборщики, регулярный обход источников с выдачей результата в бота или в БД.
- **Фронтенд и мобильные.** **Vue 3 + TypeScript** (Vite, Pinia), Nuxt 3, **Flutter / Dart** — обычно закрываю задачу целиком: от API до интерфейса.
- **MVP под задачу.** Собираю рабочую версию быстро: сервис + интерфейс + парсер/бот + запуск через docker-compose.

## 🛠 Стек

| Область | Технологии |
|---|---|
| Бэкенд | Python, FastAPI, Django + DRF, Flask, SQLAlchemy, Pydantic, JWT, APScheduler |
| Данные | PostgreSQL, SQLite, MySQL, pandas, numpy, PySpark |
| Парсинг и скрапинг | Selenium, requests, BeautifulSoup, asyncio, работа с прокси |
| Интеграции | REST и вебхуки, платёжные API (Epoint, SSLCcommerce / Privat24), LLM (Mistral, OpenAI, HF), VK API, Telegram Bot API |
| Фронтенд | Vue 3 + TypeScript, Vite, Pinia, Nuxt 3, React (MUI, Recharts, Cytoscape), REST, WebSocket |
| Мобильные и десктоп | Flutter / Dart, Flet, Tkinter, PHP (WordPress + Tutor LMS), C# / Unity, Kotlin (базовый уровень) |
| Инфраструктура | Docker, docker-compose, GitHub Actions, uvicorn / gunicorn, Linux, Git |

---

## 🚀 Избранные проекты

### Интеграции, API и боты

| Проект | Что это | Стек |
|---|---|---|
| **[Zm_server](https://github.com/B-es/Zm_server)** + **[Zm-Web](https://github.com/B-es/Zm-Web)** | Пара «сервис + интерфейс»: API для хранения карточек по категориям и веб-клиент к нему | FastAPI · Vue 3 |
| **[Parse_RIAC_Tg_Bot](https://github.com/B-es/Parse_RIAC_Tg_Bot)** | Сбор данных с сайта и выдача их пользователю через Telegram-бота | Python · парсинг · Telegram Bot API |
| **[Digital-Farming-Dictionary-Bot](https://github.com/B-es/Digital-Farming-Dictionary-Bot)** | Telegram-бот-словарь терминов цифрового сельского хозяйства | Python · Telegram Bot API |
| **[tutor-epoint](https://github.com/B-es/tutor-epoint)** | Интеграция платёжного шлюза Epoint в Tutor LMS (WordPress): оплата и обработка вебхуков | PHP · платёжные вебхуки |
| **[FluentWeatherOpenMeteo](https://github.com/B-es/FluentWeatherOpenMeteo)** | Замена погодного API на Open-Meteo в существующем Flutter-приложении | Dart · REST API |

### Сервисы и веб

| Проект | Что это | Стек |
|---|---|---|
| **[ScieJournalVSTU](https://github.com/B-es/ScieJournalVSTU)** | «Научный журнал ВСТУ»: роли пользователей, JWT-авторизация, полный жизненный цикл статьи (подача → рецензирование → публикация) | Django + DRF · JWT · Vue/Nuxt |
| **[book-viewer-server](https://github.com/B-es/book-viewer-server)** + **[book-viewer](https://github.com/B-es/book-viewer)** | Клиент-серверное приложение для чтения и хранения библиотеки книг | Python (сервер) · JS/CSS (клиент) |
| **[Drevo](https://github.com/B-es/Drevo)** | Родовое древо: интерактивное представление связей и родственных узлов | TypeScript |
| **[FastReader](https://github.com/B-es/FastReader)** | Тренажёр скорочтения с постепенным ускорением подачи текста | Python |
| **[SaveWatched](https://github.com/B-es/SaveWatched)** | Библиотека просмотренного: учёт и хранение списка материалов | Python |
| **[ExceptNetwork](https://github.com/B-es/ExceptNetwork)** | Windows-утилита: добавление адресов в исключения прокси-сервера | Python · Windows API |
| **[BrowserKeyCleaner](https://github.com/B-es/BrowserKeyCleaner)** | Windows-утилита: удаление сохранённых паролей из установленных браузеров | Python · Windows API |

### Мобильные приложения

| Проект | Что это | Стек |
|---|---|---|
| **[RewardMobileApp](https://github.com/B-es/RewardMobileApp)** | Коммерческое мобильное приложение для языкового центра «Reward» | Flutter · Dart |
| **[Sked](https://github.com/B-es/Sked)** | Приложение для просмотра расписания ВолгГТУ | Flutter · Dart |
| **[Desk](https://github.com/B-es/Desk)** | Приложение в духе Avito: объявления, категории, карточки товаров (учебный проект) | Flutter · Dart |
| **[Gesundes](https://github.com/B-es/Gesundes)** | Приложение по технологии разработки человеко-машинных интерфейсов | Flutter · Dart |

### Данные и исследования

| Проект | Что это | Стек |
|---|---|---|
| **[DynamicPriceDiplom](https://github.com/B-es/DynamicPriceDiplom)** | Реализация метода динамического ценообразования на маркетплейсе | Jupyter · Python · pandas |
| **[LoanDiplom](https://github.com/B-es/LoanDiplom)** | Анализ и модель кредитного скоринга | Jupyter · Python · ML |
| **[NeuroLabs](https://github.com/B-es/NeuroLabs)** | Лабораторные по нейронным сетям | Jupyter · Python |
| **[home_control_system](https://github.com/B-es/home_control_system)** | Курсовая: система управления устройствами умного дома | Python |

<details>
<summary><b>Учебные работы и лабораторные (АСОИУ / ВолгГТУ)</b></summary>

| Проект | Дисциплина / тема | Стек |
|---|---|---|
| [SOBD1](https://github.com/B-es/SOBD1) | Большие данные: обработка датасета на PySpark | Jupyter · PySpark |
| [PTLab1](https://github.com/B-es/PTLab1) · [PTLab4](https://github.com/B-es/PTLab4) | Технологии программирования | Python · Jupyter |
| [Victorina](https://github.com/B-es/Victorina) | Викторина на ASP.NET | C# · ASP.NET |
| [DrivingSimulator](https://github.com/B-es/DrivingSimulator) | Интеграция симуляции SUMO в игру на Unity | C# · Unity · SUMO |
| [Plumbing-shop](https://github.com/B-es/Plumbing-shop) | Учебный веб-проект магазина | C# |
| [PC_Tab](https://github.com/B-es/PC_Tab) | Базы данных | Python |
| [SUBD_1](https://github.com/B-es/SUBD_1) | СУБД | Python |
| [Lab2_Reestr](https://github.com/B-es/Lab2_Reestr) | Технология распределённого реестра | JavaScript |
| [cifro_gid](https://github.com/B-es/cifro_gid) | НИР по цифровому гиду | Dart |
| [Gliridae](https://github.com/B-es/Gliridae) | «Соня» — туристический гид | HTML · CSS |
| [ShavermaVibe](https://github.com/B-es/ShavermaVibe) | Учебный веб-проект | HTML |
| [Rustam_GTag](https://github.com/B-es/Rustam_GTag) | Небольшая веб-страница (GitHub Pages) | HTML |

Часть рабочих проектов — коммерческая разработка и внутренние сервисы — находится в приватных репозиториях.
</details>

---

## 🎯 Чем могу помочь

- **Поднять REST API** — FastAPI или Django + DRF: модели, схемы, авторизация, фоновые задачи, документация.
- **Интегрировать внешний сервис** — платёжный шлюз с вебхуками, LLM-провайдер, карты, чужие REST API.
- **Спарсить сайт** — регулярный сбор данных, обход капч и прокси, выгрузка в БД, Excel или Google Sheets.
- **Написать бота** — Telegram или VK: меню, сценарии, связка с бэкендом и БД.
- **Сделать интерфейс** — Vue 3 + TypeScript или Flutter: от макета до рабочего приложения, включая связку с API.
- **Автоматизировать процесс** — утилиты и скрипты, которые убирают ручную рутину.

## 📈 Куда развиваюсь

Уже сейчас закрываю полный цикл задачи — от API до интерфейса. Планомерно усиливаю то,
что отличает рабочий прототип от продукта:

- **Качество кода:** pytest, httpx, покрытие тестами критичных сценариев.
- **Инфраструктура:** Docker в продакшене, Nginx + gunicorn/uvicorn, GitHub Actions (CI/CD), Sentry и логирование.
- **Данные:** PostgreSQL + Alembic (миграции), Pydantic v2, Redis + Celery/ARQ для фоновых задач.

---

## 📫 Контакты

- **GitHub:** [github.com/B-es](https://github.com/B-es)
<!-- Раскомментируй и заполни — эти контакты увидят первыми:

- **Telegram:** @ваш_ник
- **Email:** your@mail.ru
- **Резюме:** ссылка на hh.ru или PDF

-->

<p align="center"><i>Открыт к предложениям по backend-разработке, интеграциям и автоматизации.</i></p>
