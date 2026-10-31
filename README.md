<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:f59e0b,100:ef4444&height=140&section=header&text=World%20Gazette%20Data&fontSize=36&fontColor=fff&fontAlignY=35" width="100%"/>

**Автоматически генерируемые новостные JSON-фиды**

[Русский](README.md) · [English](README.en.md)

[![Raw Index](https://img.shields.io/badge/Индекс-f59e0b?style=for-the-badge)](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/index.json)
[![Breaking](https://img.shields.io/badge/Breaking-ef4444?style=for-the-badge)](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/breaking.json)

</div>

---

## О репозитории

Этот репозиторий содержит **только данные** (без кода) для проекта World Gazette.  
Файлы автоматически обновляются по cron.

## Прямые ссылки на файлы

| Файл | Описание | Прямая ссылка |
|------|----------|----------------|
| `index.json` | Индекс разделов и количество | [index.json](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/index.json) |
| `breaking.json` | Срочные новости | [breaking.json](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/breaking.json) |
| `sources.json` | Источники | [sources.json](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/sources.json) |
| `status.json` | Статус | [status.json](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/status.json) |
| `translations.json` | Переводы (базовые) | [translations.json](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/translations.json) |
| `translations-ru.json` | Переводы (русский) | [translations-ru.json](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/translations-ru.json) |

Папка с разделами: [data/sections/](https://github.com/DanyaDanileckiy/world-gazette-data/tree/main/data/sections)

## Как использовать

Все файлы доступны по прямым raw-ссылкам выше. Можно подключать их в любом приложении как обычный JSON.

Пример:
```js
const index = await fetch('https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/index.json').then(r => r.json());
```

<div align="center">

**Данные обновляются автоматически**

</div>
