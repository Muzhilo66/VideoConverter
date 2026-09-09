# 🎬 VideoConverter

**VideoConverter** — бесплатный кроссплатформенный конвертер видео для подготовки файлов к публикации на **YouTube** и **Instagram**.

Программа рассчитана в том числе на слабые компьютеры и оптимизирована для работы на маломощном оборудовании — включая **Intel Atom D525**.

---

## 🚀 VideoConverter v1.0.0

Первый стабильный релиз VideoConverter.

Программа позволяет быстро конвертировать видео в **H.264**, подготовить его под нужный формат YouTube или Instagram и обработать сразу несколько файлов.

---

## ✨ Возможности

### 🎥 Конвертация видео

- **H.264** — универсальный формат, подходящий для YouTube и Instagram
- Поддержка различных исходных видеоформатов
- Оптимизированная обработка для слабых ПК
- Сохранение аудио в **AAC 128 kbps**

### 📦 Пакетная обработка

Конвертируйте сразу несколько видеофайлов за одну операцию.

Это удобно при подготовке большого количества видео для публикации.

---

## ▶️ Пресеты YouTube

Готовые настройки для популярных разрешений:

- **4K**
- **1080p**
- **720p**
- **480p**

При необходимости программа автоматически масштабирует исходное видео под выбранное разрешение.

### 🖼️ Масштабирование для YouTube

Видео вписывается в выбранный кадр **с сохранением пропорций**.

Если соотношение сторон исходного видео отличается от целевого, используются **чёрные поля**, чтобы избежать обрезки изображения.

---

## 📱 Пресеты Instagram

Готовые форматы для публикации в Instagram:

- **Square — 1:1**
- **Portrait — 4:5**
- **Landscape — 1.91:1**
- **Story / Reels — 9:16**

### ✂️ Масштабирование для Instagram

Для Instagram видео автоматически масштабируется с заполнением выбранного кадра.

При необходимости изображение **обрезается по краям**, чтобы полностью заполнить целевой формат без чёрных полос.

---

## 🖥️ Поддерживаемые платформы

| Платформа | Архитектура | Формат |
|-----------|-------------|--------|
| 🪟 **Windows** | 64-bit | `.exe` установщик |
| 🍎 **macOS** | Intel / Apple Silicon | `.zip` |
| 🐧 **Linux** | x64 | `.zip` |

---

## 📦 Скачать VideoConverter v1.0.0

### 🪟 Windows

**VideoConverter-Setup.exe**

[⬇️ Скачать VideoConverter для Windows](https://github.com/Muzhilo66/VideoConverter/releases/download/v1.0.0/VideoConverter-Setup.exe)

Размер: **55 MB**

**SHA-256:**

`22069091e1b9c05126d7a1db159de790bb3c43fcd129313d3576e74965002fc3`

---

### 🍎 macOS

**VideoConverter-Mac.zip**

[⬇️ Скачать VideoConverter для macOS](https://github.com/Muzhilo66/VideoConverter/releases/download/v1.0.0/VideoConverter-Mac.zip)

Поддерживаются:

- Intel
- Apple Silicon

Размер: **63.6 MB**

**SHA-256:**

`f9a1c4fa1c896b2c2df33038e7eb3d4e7fbd124769006c2da53d0a626343028a`

---

### 🐧 Linux

**VideoConverter-Linux.zip**

[⬇️ Скачать VideoConverter для Linux](https://github.com/Muzhilo66/VideoConverter/releases/download/v1.0.0/VideoConverter-Linux.zip)

Архитектура:

- x64

Размер: **65.2 MB**

**SHA-256:**

`7196c8281971d659a958752aa6cdb6ecd1e9b1e094f9f71dc261b875065b7b56`

---

## 🛠️ Установка

### 🪟 Windows

1. Скачайте `VideoConverter-Setup.exe`.
2. Запустите установщик.
3. Следуйте инструкциям на экране.
4. После установки запустите VideoConverter.

---

### 🍎 macOS

1. Скачайте `VideoConverter-Mac.zip`.
2. Распакуйте архив.
3. Откройте терминал в папке программы.
4. При необходимости сделайте файлы исполняемыми:

```bash
chmod +x VideoConverter-mac_universal
chmod +x bin/ffmpeg
```

5. Запустите программу:

```bash
./VideoConverter-mac_universal
```

> Если macOS блокирует запуск приложения, разрешите его запуск в настройках безопасности системы.

---

### 🐧 Linux

1. Скачайте `VideoConverter-Linux.zip`.
2. Распакуйте архив.
3. Откройте терминал в папке программы.
4. Сделайте файлы исполняемыми:

```bash
chmod +x VideoConverter-linux_x64
chmod +x bin/ffmpeg
```

5. Запустите программу:

```bash
./VideoConverter-linux_x64
```

---

## 🔧 FFmpeg

VideoConverter использует **FFmpeg** для обработки и конвертации видео.

Необходимые файлы FFmpeg входят в состав дистрибутивов программы.

Отдельная установка FFmpeg для работы VideoConverter не требуется.

---

## 🔐 Проверка файлов

Для проверки целостности скачанного файла можно использовать контрольную сумму **SHA-256**.

| Файл | SHA-256 | Размер |
|------|---------|--------|
| `VideoConverter-Setup.exe` | `22069091e1b9c05126d7a1db159de790bb3c43fcd129313d3576e74965002fc3` | 55 MB |
| `VideoConverter-Mac.zip` | `f9a1c4fa1c896b2c2df33038e7eb3d4e7fbd124769006c2da53d0a626343028a` | 63.6 MB |
| `VideoConverter-Linux.zip` | `7196c8281971d659a958752aa6cdb6ecd1e9b1e094f9f71dc261b875065b7b56` | 65.2 MB |

---

## 📜 Исходный код

VideoConverter распространяется как проект с открытым исходным кодом.

- [📦 Исходный код ZIP](https://github.com/Muzhilo66/VideoConverter/archive/refs/tags/v1.0.0.zip)
- [📦 Исходный код TAR.GZ](https://github.com/Muzhilo66/VideoConverter/archive/refs/tags/v1.0.0.tar.gz)
- [💻 Репозиторий GitHub](https://github.com/Muzhilo66/VideoConverter)

---

## 📥 Все релизы

[Перейти к списку всех релизов VideoConverter](https://github.com/Muzhilo66/VideoConverter/releases)

---

## 🐛 Нашли ошибку?

Если вы обнаружили ошибку, столкнулись с проблемой или хотите предложить улучшение:

[Создать Issue на GitHub](https://github.com/Muzhilo66/VideoConverter/issues)

---

## 💰 Поддержать проект

**VideoConverter — бесплатное приложение с открытым исходным кодом.**

Если программа оказалась полезной и вы хотите поддержать дальнейшую разработку:

### 🇷🇺 Для России

💳 **ЮMoney / ЮKassa**

`410019857381536`

Любая поддержка помогает развивать проект и выпускать новые версии. ❤️

---

## 📝 Версия

**VideoConverter v1.0.0**

Первый релиз: **2026**

---

*Made with ❤️ using* [*Neutralino.js*](https://neutralino.js.org/)
