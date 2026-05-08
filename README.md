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

Сейчас фокусируюсь на:
- AI-интеграциях и автоматизации
- Python backend разработке
- prompt engineering
- генерации изображений и видео
- AI-assisted workflows
- инструментах для обработки и структурирования данных

---

## 🚀 Основные проекты

### 📚 WordIndexer
Система для автоматической обработки и индексирования больших Word-документов со сложной структурой.

Проект разрабатывался для реального сборника научных статей объемом около 450 страниц.

Что реализовано:
- генерация предметных указателей
- генерация авторских указателей
- построение оглавления
- обработка русских и английских секций
- работа со сложным форматированием Word, включая обработку ошибок форматирования в исходном документе
- автоматическая обработка подстрочных индексов
- сохранение структуры исходного документа
- пайплайн обработки через промежуточные артефакты и debug-данные

Технологии:
`Python` `pywin32` `Word COM` `CSV` `Git`

---

### 🎬 ZeroVideo
Экспериментальный AI-сервис генерации видео с двумя независимыми интерфейсами:
- web application
- Telegram bot

Архитектура проекта:
- Flask backend
- SPA frontend
- Telegram bot на pyTelegramBotAPI
- отдельные Docker-контейнеры
- файловое хранилище вместо БД для упрощения отладки и развертывания

Особенности:
- разные сценарии обработки задач для web и Telegram
- автоматическая отправка результатов пользователю
- асинхронная обработка генерации
- разделение frontend/backend логики

Технологии:
`Python` `Flask` `Docker` `Gunicorn` `Telegram Bot API` `HTML` `CSS` `JavaScript`

---

### 🎨 ZeroYandex
Экспериментальный AI-проект для генерации логотипов через YandexART API.

Проект создавался как исследование:
- prompt engineering
- управляемой генерации через seed
- refinement pipeline
- интеграции AI API в web-приложение

Что реализовано:
- Flask backend
- SPA frontend
- preset styles
- refinement существующего результата
- async polling генерации
- конфигурация через `.env`
- обработка ошибок и timeout

⚠️ Качество генерации зависит от возможностей модели и может быть нестабильным для сложных запросов.

Технологии:
`Python` `Flask` `REST API` `Yandex Cloud API` `JavaScript`

---

## 🛠 Технологии и инструменты

### Backend
`Python` `Flask` `REST API`

### AI / Automation
`Prompt Engineering` `LLM` `AI Tools` `Image Generation`

### Dev Tools
`Git` `GitHub` `Docker` `PyCharm`

### Frontend
`HTML` `CSS` `JavaScript`

---

## 🔬 Сейчас изучаю

- AI automation systems
- web development
- model fine-tuning
- advanced prompt engineering
- AI-assisted applications
- генерацию и обработку мультимедиа

---

## 📫 Контакты

Telegram: `@iminyaylova`  
Email: `irina.stu78@gmail.com`

---

## 📌 Дополнительно

Некоторые репозитории в профиле являются экспериментальными или исследовательскими проектами.  
Основной интерес — создание практических AI-инструментов, автоматизация процессов и интеграция нейросетевых сервисов в реальные сценарии использования.
