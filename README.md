# FullMute - Массовый сканер технологий сайтов

![FullMute](https://img.shields.io/badge/FullMute-v1.0.0-green.svg)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

**FullMute** - высокопроизводительный асинхронный сканер для массового анализа технологий веб-сайтов. Определяет CMS, фреймворки, языки программирования, базы данных и обнаруживает уязвимые файлы.

**Создатель**: [@a11mut3d](https://t.me/a11mut3d)

## ✨ Возможности

- **🚀 Высокая производительность**: Асинхронная обработка до 50 доменов одновременно
- **🔍 Детектирование технологий**:
  - CMS системы (WordPress, Joomla, Drupal, Bitrix, OpenCart и другие)
  - Фреймворки (Laravel, Django, Ruby on Rails, Express.js, Flask)
  - Языки программирования (PHP, Python, Ruby, Node.js, Java, ASP.NET)
  - Базы данных (MySQL, PostgreSQL, MongoDB, SQLite, Oracle)
  - Веб-серверы (Nginx, Apache, IIS, Cloudflare, Litespeed)
- **📁 Обнаружение файлов**:
  - Git репозитории (`.git/HEAD`)
  - Конфигурационные файлы (`.env`, `wp-config.php`, `config.php`)
  - Лог-файлы (`error.log`, `access.log`, `debug.log`)
  - Backup файлы (`backup.zip`, `database.sql`, `backup.sql`)
  - Временные файлы (`/tmp`, `/temp`)
- **📊 Статистика в реальном времени**: Красивый интерфейс с live-статистикой
- **💾 Сохранение результатов**: База данных SQLite с историей сканирований
- **🕵️ Скрытность**: Ротация User-Agent и минимальное воздействие на целевые сайты

## 📦 Установка

### Требования
- Python 3.8+
- pip (менеджер пакетов Python)

### Установка зависимостей
```bash
# Клонируйте репозиторий
git clone https://github.com/yourusername/FullMute.git
cd FullMute
```
# Установите зависимости
pip install -r requirements.txt
```

## Использование

**Базовое использование**
```bash
python main.py -f domains.txt
```
**Расширенные опции**
```bash
# С указанием базы данных и количеством потоков
python main.py -f domains.txt -d results.db -t 30

# Помощь по командам
python main.py --help
```
