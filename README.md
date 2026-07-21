## Добрый день! 👋

<!--
**irinastu78-bot/irinastu78-bot** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


Меня зовут Ирина, я занимаюсь разработкой AI-инструментов, автоматизацией и экспериментальными проектами на Python.  
Интересуюсь prompt engineering, генеративными моделями, AI automation и созданием прикладных сервисов на базе нейросетей.

**Основной фокус:**
- AI integrations
- Python backend development
- automation workflows
- prompt engineering
- AI-powered tools
- генерация изображений и видео

---

## 🚀 Основные проекты

### 📚 [WordIndexer](https://github.com/irinastu78-bot/WordIndexer)
Система для автоматической обработки и индексирования больших Word-документов со сложной структурой.

Проект разрабатывался для реального сборника научных статей объемом около 450 страниц.

**Что реализовано:**
- генерация предметных указателей
- генерация авторских указателей
- построение оглавления
- обработка русских и английских секций
- работа со сложным форматированием Word, включая обработку ошибок форматирования в исходном документе
- автоматическая обработка подстрочных индексов
- сохранение структуры исходного документа
- пайплайн обработки через промежуточные артефакты и debug-данные
- сбор списка e-mail авторов

**Технологии:**
`Python` `pywin32` `Word COM` `CSV` `Git`

**Screenshots:** <br>
<a href="images/wordindexer/article_example.png" target="_blank">
  <img src="images/wordindexer/article_example.png" alt="Пример исходного текста статьи" title="Пример исходного текста статьи" height="100">
</a>
<a href="images/wordindexer/author_index_ru.png">
  <img src="images/wordindexer/author_index_ru.png" alt="Авторский указатель" title="Авторский указатель" height="100">
</a>
<a href="images/wordindexer/author_index_en.png" target="_blank">
  <img src="images/wordindexer/author_index_en.png" alt="Author Index" title="Author Index" height="100">
</a>
<a href="images/wordindexer/kw_index_ru.png" target="_blank">
  <img src="images/wordindexer/kw_index_ru.png" alt="Предметный указатель" title="Предметный указатель" height="100">
</a><br>

<a href="images/wordindexer/kw_index_en.png" target="_blank">
  <img src="images/wordindexer/kw_index_en.png" alt="Keyword Index" title="Keyword Index" height="100">
</a>
<a href="images/wordindexer/toc_ru.png" target="_blank">
  <img src="images/wordindexer/toc_ru.png" alt="Оглавление на русском" title="Оглавление на русском" height="100">
</a>
<a href="images/wordindexer/toc_en.png" target="_blank">
  <img src="images/wordindexer/toc_en.png" alt="Оглавление на английском" title="Оглавление на английском" height="100">
</a>
<a href="images/wordindexer/toc_ru_last.png" target="_blank">
  <img src="images/wordindexer/toc_ru_last.png" alt="Последняя страница оглавления" title="Последняя страница оглавления" height="100">
</a>

---

### 📚 [Podcast Content Planner](https://github.com/irinastu78-bot/podcast-content-planner)
ИИ-ассистент для автоматизации производства подкастов.

**Задача:** автоматизировать подготовку выпусков подкаста — от идеи
до готового сценария для озвучки — с использованием нейросетевых
моделей и работы с базой знаний.

**Реализовано:**
- Пятиэтапный конвейер генерации контента на базе OpenAI API.
- Работа с источниками: загрузка файлов разных форматов и статей по URL.
- Поддержка диалоговых и сольных форматов, включая детский «сказочный».
- Финальная ИИ-редактура текста и автокоррекция смешанного алфавита.
- Многопользовательский режим с авторизацией и сохранением проектов.
- Экспорт в Word и JSON. Развёртывание в облаке.

**Технологии:** 
`Python` `Streamlit` `OpenAI API` (gpt-5.4-mini) `SQLite` `python-docx` `pypdf` `python-pptx` `openpyxl` `trafilatura` 

**Результат:** работающее веб-приложение, готовое к практическому
использованию; сокращает время подготовки выпуска в несколько раз.


**Screenshots:** <br>
<a href="images/podcast_planner/gen_ideas.png" target="_blank">
  <img src="images/podcast_planner/gen_ideas.png" alt="Главный экран приложения с заполненными параметрами подкаста: название, длительность, аудитория, формат, стиль, имя собеседника" title="Главный экран приложения с заполненными параметрами подкаста: название, длительность, аудитория, формат, стиль, имя собеседника" height="100">
</a>
<a href="images/podcast_planner/menu1.png" target="_blank">
  <img src="images/podcast_planner/menu1.png" alt="Меню параметров для подкаста из научной статьи" title="Меню параметров для подкаста из научной статьи" height="100">
</a>
<a href="images/podcast_planner/menu2.png" target="_blank">
  <img src="images/podcast_planner/menu2.png" alt="Параметры меню для подкаста из научной статьи (часть 2)" title="Параметры меню для подкаста из научной статьи (часть 2)" height="100">
</a>
<a href="images/podcast_planner/menu3.png" target="_blank">
  <img src="images/podcast_planner/menu3.png" alt="Загрузка файла-источника (книга в PDF/DOCX)" title="Загрузка файла-источника (книга в PDF/DOCX)" height="100">
</a>
<a href="images/podcast_planner/menu4.png" target="_blank">
  <img src="images/podcast_planner/menu4.png" alt="Добавление ссылки на статью как источника" title="Добавление ссылки на статью как источника" height="100">
</a>
<a href="images/podcast_planner/conspect.png" target="_blank">
  <img src="images/podcast_planner/conspect.png" alt="Готовый конспект статьи, который можно подключить как источник для подкаста" title="Готовый конспект статьи, который можно подключить как источник для подкаста" height="100">
</a>
<a href="images/podcast_planner/ideas_chem.png" target="_blank">
  <img src="images/podcast_planner/ideas_chem.png" alt="Сгенерированные идеи выпусков" title="Сгенерированные идеи выпусков" height="100">
</a>
<a href="images/podcast_planner/content_chem.png" target="_blank">
  <img src="images/podcast_planner/content_chem.png" alt="Контент-план на несколько выпусков" title="Контент-план на несколько выпусков" height="100">
</a>
<a href="images/podcast_planner/struc_chem.png" target="_blank">
  <img src="images/podcast_planner/struc_chem.png" alt="Структура выпуска с блоками и хронометражем" title="Структура выпуска с блоками и хронометражем" height="100">
</a>
<a href="images/podcast_planner/tts_screen.png" target="_blank">
  <img src="images/podcast_planner/tts_screen.png" alt="Текст для озвучки с разбивкой по ролям и индикатором прогресса генерации" title="Текст для озвучки с разбивкой по ролям и индикатором прогресса генерации" height="100">
</a>
<a href="images/podcast_planner/tts_rec.png" target="_blank">
  <img src="images/podcast_planner/tts_rec.png" alt="Рекомендации по голосам для синтеза речи" title="Рекомендации по голосам для синтеза речи" height="100">
</a>
<a href="images/podcast_planner/tts_word.png" target="_blank">
  <img src="images/podcast_planner/tts_word.png" alt="Готовый Word-файл с технической шапкой: название подкаста, длительность, аудитория, стиль, участники" title="Готовый Word-файл с технической шапкой: название подкаста, длительность, аудитория, стиль, участники" height="100">
</a>
<a href="images/podcast_planner/ideas_tale.png" target="_blank">
  <img src="images/podcast_planner/ideas_tale.png" alt="Пример использования формата и стиля «сказка»: идеи выпусков" title="Пример использования формата и стиля «сказка»: идеи выпусков" height="100">
</a>
<a href="images/podcast_planner/tts_tale.png" target="_blank">
  <img src="images/podcast_planner/tts_tale.png" alt="Пример использования формата и стиля «сказка»: текст для озвучки" title="Пример использования формата и стиля «сказка»: текст для озвучки" height="100">
</a>

---

### 📚 [Vaska-Openclaw-Assistant](https://github.com/irinastu78-bot/Vaska-Openclaw-Assistant)
AI-ассистент на OpenClaw (Telegram + веб-чат с общей историей): pipeline обезличивания ПДн, генерация презентаций, инфографики и гистограмм.

**Платформа:**OpenClaw на выделенном VPS · Каналы: Telegram и веб-чат (свой домен) · Модель: ChatGPT Codex по подписке (gpt-5.4), платный OpenAI API — только по явной команде владельца.

**Что реализовано:**
- Круглосуточный персональный ассистент на выделенном сервере с **единым опытом в Telegram и браузере**.
- Ассистент может работать для нескольких пользователей с рабочим и личным контуром для каждого.
- Возможно подключение бота в группу Телеграм.
- Конфиденциальные `.docx` обрабатываются по сценарию «маска → анализ в LLM → сборка → восстановление». Персональные данные в LLM не попадают.
- Презентации, инфографика и гистограммы — по запросу, без обязательного платного image API.
- Уведомления, напоминания по расписанию (Телеграм-чат, веб-пуши).
- Управляемая стоимость: Codex по подписке, API — только когда нужно.
  
**Технологии:**
`OpenClaw` `Python` (Presidio, python-docx, python-pptx, matplotlib) `Node.js` (Satori, resvg) `nginx` `Telegram Bot API` `WebSocket` `systemd`.

**Screenshots:** <br>
<a href="images/vaska/tg_vs_web_chat.png" target="_blank">
  <img src="images/vaska/tg_vs_web_chat.png" alt="Общий вид телеграм- и веб-чата" title="Общий вид телеграм- и веб-чата" height="100">
</a>
<a href="images/vaska/tg_api_balance.png" target="_blank">
  <img src="images/vaska/tg_api_balance.png" alt="Проверка баланса" title="Проверка баланса" height="100">
</a>
<a href="images/vaska/stt.png" target="_blank">
  <img src="images/vaska/stt.png" alt="Распознавание голоса" title="Распознавание голоса" height="100">
</a>
<a href="images/vaska/anonimized_doc.png" target="_blank">
  <img src="images/vaska/anonimized_doc.png" alt="Удаление персональных данных из документов перед отправкой в LLM" title="Удаление персональных данных из документов перед отправкой в LLM" height="100">
</a>
<a href="images/vaska/web_push.png" target="_blank">
  <img src="images/vaska/web_push.png" alt="Веб-пуш уведомления" title="Веб-пуш уведомления" height="100">
</a><br>
<a href="images/vaska/histogram.png" target="_blank">
  <img src="images/vaska/histogram.png" alt="Создание гистограмм по данным" title="Создание гистограмм по данным" height="100">
</a>
<a href="images/vaska/image_gen.png" target="_blank">
  <img src="images/vaska/image_gen.png" alt="Генерация изображений" title="Генерация изображений" height="100">
</a>
<a href="images/vaska/web_chat_pres_gen.png" target="_blank">
  <img src="images/vaska/web_chat_pres_gen.png" alt="Генерация презентации через веб-чат" title="Генерация презентации через веб-чат" height="100">
</a>
<a href="images/vaska/tg_pres_gen.png" target="_blank">
  <img src="images/vaska/tg_pres_gen.png" alt="Генерация презентации в Телеграм" title="Генерация презентации в Телеграм" height="100">
</a>
<a href="images/vaska/pres_example.png" target="_blank">
  <img src="images/vaska/pres_example.png" alt="Пример сгенерированной презентации" title="Пример сгенерированной презентации" height="100">
</a>

---

### 📚 [ArtistPortfolio](https://github.com/irinastu78-bot/ArtistPortfolio)
Веб-приложение на Django для онлайн-портфолио художника или другого творческого представителя. Проект объединяет публичную галерею работ, детальные страницы произведений и удобную админ-панель для управления каталогом без ручного редактирования кода.

Фронтенд выполнен без тяжелых фреймворков: адаптивная сетка карточек, фильтры, детальные страницы, лайтбокс, zoom-просмотр и аккуратная галерейная визуальная стилистика.

**Что реализовано:**
- Галерея художественных работ с настраиваемыми разделами, например: Живопись, Графика, ДПИ, Цифровое искусство.
- Фильтрация работ по видам и стилям.
- Детальная страница работы с описанием, техникой, размерами, статусом, ценой, выставками и похожими работами.
- Блок «Выбор автора» на главной странице.
- Загрузка основных и дополнительных изображений, поддержка видео.
- Автоматическая генерация миниатюр через `easy-thumbnails`.
- Лайтбокс и zoom-просмотр изображений на странице работы.
- Редактируемые текстовые страницы, например: «Об авторе», «Контакты», «Политика конфиденциальности».
- Cookie-баннер и подключение Яндекс.Метрики только после согласия пользователя.
- Импорт и экспорт каталога работ через CSV.
- Идемпотентный импорт: повторный запуск обновляет существующие записи, а не создает дубликаты.
- Резервное копирование базы, данных приложения и медиафайлов отдельной management-командой.
- Production-конфигурация через Docker Compose, Gunicorn, nginx и Let's Encrypt.

**Технологии:**
`Python` `Django 6` `SQLite` `Django Admin` `Pillow` `easy-thumbnails` `django-admin-sortable2` `Vanilla JavaScript` `CSS` `Docker` `Gunicorn` `nginx` `Certbot / Let's Encrypt`

**Screenshots:** <br>
<a href="images/artistportfolio/home.png" target="_blank">
  <img src="images/artistportfolio/home.png" alt="Главная страница" title="Главная страница" height="100">
</a>
<a href="images/artistportfolio/settings.png" target="_blank">
  <img src="images/artistportfolio/settings.png" alt="Настройки сайта" title="Настройки сайта" height="100">
 </a>
<a href="images/artistportfolio/policy.png" target="_blank">
  <img src="images/artistportfolio/policy.png" alt="Запрос на согласие с политикой" title="Запрос на согласие с политикой" height="100">
</a>
<a href="images/artistportfolio/styles.png" target="_blank">
  <img src="images/artistportfolio/styles.png" alt="Настройка списка стилей" title="Настройка списка стилей" height="100">
</a>
<br>

<a href="images/artistportfolio/admin_works.png" target="_blank">
  <img src="images/artistportfolio/admin_works.png" alt="Управление карточками работ" title="Управление карточками работ" height="100">
</a>
<a href="images/artistportfolio/workcard_view.png">
  <img src="images/artistportfolio/workcard_view.png" alt="Карточка работы" title="Карточка работы" height="100">
</a>
<a href="images/artistportfolio/workcard1.png" target="_blank">
  <img src="images/artistportfolio/workcard1.png" alt="Редактирование карточки работы" title="Редактирование карточки работы" height="100">
</a>
<a href="images/artistportfolio/workcard2.png" target="_blank">
  <img src="images/artistportfolio/workcard2.png" alt="Редактирование карточки работы, продолжение" title="Редактирование карточки работы, продолжение" height="100">
</a>


---

### 🎬 [ZeroVideo](https://github.com/irinastu78-bot/ZeroVideo)
Экспериментальный AI-сервис генерации видео с двумя независимыми интерфейсами:
- web application
- Telegram bot

**Архитектура проекта:**
- Flask backend
- SPA frontend
- Telegram bot на pyTelegramBotAPI
- отдельные Docker-контейнеры
- файловое хранилище вместо БД для упрощения отладки и развертывания

**Особенности:**
- разные сценарии обработки задач для web и Telegram
- автоматическая отправка результатов пользователю
- асинхронная обработка генерации
- разделение frontend/backend логики

**Технологии:**
`Python` `Flask` `Docker` `Gunicorn` `Telegram Bot API` `HTML` `CSS` `JavaScript`

**Screenshots:** <br>
<a href="images/zerovideo/telegram_gen_video.png" target="_blank">
  <img src="images/zerovideo/telegram_gen_video.png" alt="Пример чата в телеграм боте с генерацией видео" title="Пример чата в телеграм боте с генерацией видео" height="100">
</a>
<a href="images/zerovideo/web_video_gen.png" target="_blank">
  <img src="images/zerovideo/web_video_gen.png" alt="Пример генерации видео на сайте" title="Пример генерации видео на сайте" height="100">
</a>

---

### 🤖 [Multi-channel AI Booking Assistant](https://github.com/Irsmile/Multi-channel-AI-Booking-Assistant)
Экспериментальный AI-ассистент для записи клиентов с multi-channel архитектурой: Telegram-бот + веб-чат + интеграция с OpenAI и Google Sheets.
В репозитории реализован пример для салона красоты. Бот консультирует клиента и записывает его на услугу, держит в памяти 20-30 сообщений чата, умеет определять из произвольного текста контактные данные, время записи и пожелания клиента, записывает лиды в аналог CRM в Google таблицах. 

**Возможности:**
- Telegram bot + website chat
- conversational booking flow
- Google Sheets CRM integration
- session memory
- structured lead extraction
- fallback architecture

**Технологии:**
`Python` `Flask` `OpenAI API` `Google Sheets API` `Telegram Bot API`

**Screenshots:** <br>
<a href="images/multichannel_ai_booking_assistant/Telegram_conversation.png" target="_blank">
  <img src="images/multichannel_ai_booking_assistant/Telegram_conversation.png" alt="Телеграм бот для записи клиента" title="Телеграм бот для записи клиента" height="100">
</a>
<a href="images/multichannel_ai_booking_assistant/Website_chat_UI.png" target="_blank">
  <img src="images/multichannel_ai_booking_assistant/Website_chat_UI.png" alt="Чат бот на сайте" title="Чат бот на сайте" height="100">
</a>
<a href="images/multichannel_ai_booking_assistant/Google_Sheets_lead_storage.png" target="_blank">
  <img src="images/multichannel_ai_booking_assistant/Google_Sheets_lead_storage.png" alt="Размещение собранных данных в Google таблицах" title="Размещение собранных данных в Google таблицах" height="100">
</a>


---

### 🎨[ZeroYandex](https://github.com/irinastu78-bot/ZeroYandex)
Экспериментальный AI-проект для генерации логотипов через YandexART API.

**Проект создавался как исследование:**
- prompt engineering
- AI API integration
- seed-based generation
- refinement workflows

**Особенности:**
- Flask backend
- SPA frontend
- preset styles
- refinement pipeline
- async generation polling

**Технологии:**
`Python` `Flask` `REST API` `Yandex Cloud API`

**Screenshots:** <br>
<a href="images/zeroyandex/redis_server.png" target="_blank">
  <img src="images/zeroyandex/redis_server.png" title="Пример генерации логотипа на сайте" height="100">
</a>


---
<!--
### 🎤 Realtime Audio Transcriber *(WIP)*
Система realtime-транскрибации аудио с локальным ASR и диагностическим pipeline.

**Текущий фокус:**
- realtime audio processing
- queue-based architecture
- WASAPI loopback capture
- local ASR backends
- diagnostics and debugging tools

**Технологии:**
`Python` `Vosk` `PyAudio` `WASAPI`

---
-->
# 🛠 Технологии

### Backend
`Python` `Flask` `REST API`

### AI / Automation
`Prompt Engineering` `LLM` `OpenAI API` `Conversational AI`

### Integrations
`Telegram Bot API` `Google Sheets API`

### Dev Tools
`Git` `GitHub` `Docker` `PyCharm`

### Frontend
`HTML` `CSS` `JavaScript`

---

# 🔬 Сейчас изучаю

- AI automation systems
- advanced prompt engineering
- web development
- model fine-tuning
- AI-assisted applications
- multimedia processing

---

## 📫 Контакты

Email: `irina.stu78@gmail.com`

---

## 📌 Дополнительно

Некоторые репозитории в профиле являются экспериментальными или исследовательскими проектами.  
Основной интерес — создание практических AI-инструментов, автоматизация процессов и интеграция нейросетевых сервисов в реальные сценарии использования.
