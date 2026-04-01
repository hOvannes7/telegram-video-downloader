<div align="center">

# Telegram Video Downloader

Расширение Chrome для скачивания видео и изображений из Telegram Web

[📥 Скачать](https://github.com/hOvannes7/telegram-video-downloader/archive/refs/heads/main.zip) • [📖 Документация](USAGE.md)

[Русский](README.md) | [English](README_EN.md)

</div>

## 🚀 Быстрый старт

### Установка

1. Откройте Chrome → `chrome://extensions/`
2. Включите **Режим разработчика**
3. Нажмите **Загрузить распакованное**
4. Выберите папку с расширением

### Использование

1. Откройте [Telegram Web](https://web.telegram.org/)
2. Найдите видео или изображение
3. Нажмите **⬇ Download**
4. Готово!

## 🔥 Возможности

- **Безлимитные загрузки** — никаких ограничений
- **2 версии** — поддержка `/a/` и `/k/`
- **Приватность** — нет телеметрии и внешних запросов
- **Современный дизайн** — в стиле Telegram
- **Быстрая загрузка** — Range API

## 📁 Структура

```
├── manifest.json
├── background.js
├── content_tg.js
├── inject.js
├── popup.html
├── popup.js
└── icons/
    ├── 16.png
    ├── 48.png
    └── 128.png
```

## 🔒 Безопасность

- ✅ Загрузка напрямую с CDN Telegram
- ✅ Нет внешних запросов
- ✅ Нет телеметрии
- ✅ Минимальное хранение данных

## 📄 Лицензия

MIT
