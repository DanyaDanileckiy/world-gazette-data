<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:f59e0b,100:ef4444&height=140&section=header&text=World%20Gazette%20Data&fontSize=36&fontColor=fff&fontAlignY=35" width="100%"/>

**Auto-generated news JSON feeds**

[Русский](README.md) · [English](README.en.md)

[![Raw Index](https://img.shields.io/badge/Index-f59e0b?style=for-the-badge)](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/index.json)
[![Breaking](https://img.shields.io/badge/Breaking-ef4444?style=for-the-badge)](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/breaking.json)

</div>

---

## About

This repository contains **data only** (no source code) for the World Gazette project.  
Files are updated automatically by cron.

## Direct file links

| File | Description | Direct link |
|------|-------------|-------------|
| `index.json` | Sections index & counts | [index.json](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/index.json) |
| `breaking.json` | Breaking news | [breaking.json](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/breaking.json) |
| `sources.json` | Sources | [sources.json](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/sources.json) |
| `status.json` | Status | [status.json](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/status.json) |
| `translations.json` | Translations (base) | [translations.json](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/translations.json) |
| `translations-ru.json` | Translations (Russian) | [translations-ru.json](https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/translations-ru.json) |

Sections folder: [data/sections/](https://github.com/DanyaDanileckiy/world-gazette-data/tree/main/data/sections)

## How to use

All files are available via the raw links above. You can fetch them from any app as regular JSON.

Example:
```js
const index = await fetch('https://raw.githubusercontent.com/DanyaDanileckiy/world-gazette-data/main/data/index.json').then(r => r.json());
```

<div align="center">

**Data is updated automatically**

</div>
