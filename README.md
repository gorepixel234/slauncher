# SLauncher ⛏

> Быстрый, красивый и бесплатный лаунчер для Minecraft

![Windows](https://img.shields.io/badge/Windows-10%2F11-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Version](https://img.shields.io/badge/Version-2.1-gold)

## 🎮 Возможности

- **Все версии** — от Minecraft 1.0 до последнего релиза
- **7 загрузчиков** — Vanilla, Forge, Fabric, NeoForge, OptiFine, Forge+OptiFine, Fabric+OptiFine
- **Скачивание модов** — интеграция с Modrinth и CurseForge
- **Пиксельный дизайн** — интерфейс в стиле оригинального Minecraft
- **Сохранение настроек** — никнейм, RAM, версия и загрузчик запоминаются
- **Настройка RAM** — от 1 до 16 ГБ

## ⬇️ Скачать

Скачай последнюю версию на странице [Releases](../../releases).

| Файл | Платформа | Размер |
|------|-----------|--------|
| `SLauncher.exe` | Windows x64 | ~30 МБ |

## 📸 Скриншот

> Добавь скриншот лаунчера сюда

## 🔧 Системные требования

- Windows 10/11 (64-bit)
- Java 8+ (для Minecraft)
- 2 ГБ оперативной памяти
- Интернет-соединение

## 📦 Загрузчики

| Загрузчик | Поддержка |
|-----------|-----------|
| Vanilla | ✅ Полная |
| Forge | ✅ Автоустановка |
| Fabric | ✅ Автоустановка |
| NeoForge | ✅ Автоустановка |
| OptiFine | ⚡ Ручная установка |
| Forge+OptiFine | ⚡ Forge авто + OptiFine вручную |
| Fabric+OptiFine | ⚡ Fabric авто + OptiFabric вручную |

## 🧩 Моды

SLauncher поддерживает установку модов из двух источников:

- **Modrinth** — открытая платформа модов
- **CurseForge** — крупнейший каталог модов

При скачивании модов с этих сайтов, .jar файлы автоматически перемещаются в папку `mods`.

## 🛠 Сборка из исходников

```bash
# Установка зависимостей
pip install customtkinter minecraft-launcher-lib Pillow requests

# Запуск
python SLauncher.pyw

# Сборка в .exe
pip install pyinstaller
pyinstaller --onefile --noconsole --name SLauncher --icon icon.ico SLauncher.pyw
```

## 📄 Лицензия

MIT License — используй как хочешь!

## ❤️ Благодарности

- [minecraft-launcher-lib](https://github.com/JakobDev/minecraft-launcher-lib) — библиотека для работы с Minecraft
- [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter) — современный UI для Python
- Сделано с помощью AI ⛏

---

**Minecraft является торговой маркой Mojang AB.**
