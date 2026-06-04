# Surgery-PMPH-10edition
<div align="center">

> *« Руководство студента-медика XXI века »*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> Справочник клинических навыков на основе учебника «Хирургия» (10-е издание) издательства «Народное медицинское издательство» — 240 навыков в области хирургии и неотложной помощи
<br>
<br>
<img src="https://github.com/xllgreen/Surgery-PMPH-10edition-/blob/main/assets/Surgery.png" width="260px">
<br>

Зачем штудировать целый учебник?<br>
Просто задайте вопрос и получите решение прямо из учебника

<br>

**Другие языки / Other Languages:**

[English](README_EN.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## О проекте

Этот проект систематически объединяет ключевые области клинической хирургии, неотложной и интенсивной терапии, периоперационного ведения, травматологии, комплексного лечения опухолей, инфекционного контроля и диагностики/лечения мультисистемных заболеваний, охватывая **240 ключевых клинических навыков** в 17 основных категориях.

**Целевая аудитория**: Хирурги, врачи скорой помощи, реаниматологи, студенты-медики

**Учебное пособие**: «Хирургия» (10-е издание), Народное медицинское издательство

## Структура проекта

```
Surgery-PMPH-10edition/
├── SKILL.md              # Основной реестр — индекс 240 навыков
├── README.md             # Этот файл — описание проекта и руководство по использованию
├── <skill-name>/         # Подробное описание каждого навыка
│   └── SKILL.md          #   Детали навыка (показания, этапы выполнения, ссылки)
├── scripts/              # Исполняемые вспомогательные скрипты
│   ├── skill-search.sh   #   Поиск навыков по ключевым словам
│   └── skill-report.sh   #   Генератор отчёта по навыкам
├── config/               # Файлы конфигурации
│   └── skill-config.yaml #   Конфигурация категорий и метаданных навыков
└── tests/                # Проверка и тестирование
    └── validate-all.sh   #   Скрипт проверки целостности
```

## Категории навыков

| Категория | Навыков | Описание |
|-----------|---------|----------|
| 🚑 Неотложная помощь и реанимация | 14 | СЛР, противошоковая терапия, электролитные нарушения |
| 🦴 Травмы и переломы | 27 | Классификация переломов, репозиция и фиксация, повреждения нервов |
| 🩺 Общая хирургия и неотложная абдоминальная патология | 22 | Аппендицит, кишечная непроходимость, грыжа, перитонит |
| 🫁 Гепатобилиарная и панкреатическая хирургия | 19 | Желчнокаменная болезнь, панкреатит, травма печени |
| 🩻 Гастроинтестинальная хирургия | 10 | Рак желудка, колоректальный рак, ГЭРБ |
| 🫘 Урология | 24 | Камни, опухоли, инфекции, повреждения уретры |
| 🩸 Сосудистая хирургия | 7 | ТГВ, варикозное расширение вен, сосудистая пластика |
| 🔥 Ожоги и пластическая хирургия | 8 | Оценка площади, классификация глубины, пересадка кожи |
| 🧬 Онкология и комплексное лечение | 16 | Стадирование TNM, химиолучевая терапия, сохранение конечности |
| 📋 Периоперационное ведение | 18 | Предоперационная оптимизация, антибиотики, нутритивная поддержка |
| 💉 Анестезия и боль | 11 | Управление дыхательными путями, спинальная анестезия, местная анестезия |
| ⚖️ Эндокринология и метаболизм | 6 | Гиперпаратиреоз, дегидратация, электролиты |
| 🦠 Инфекция и иммунитет | 7 | Туберкулёз, сепсис, столбняк |
| 📡 Визуализация и интервенция | 10 | Ангиография, эндоскопия, интервенционная радиология |
| 🏋️ Реабилитация и функциональная оценка | 12 | Реабилитация после переломов, неврологическая оценка |
| 🦿 Ревматология и заболевания позвоночника | 5 | Анкилозирующий спондилит, стеноз позвоночного канала |
| 🔧 Прочие специальные навыки | 10 | ОРДС, ОПП, дефибрилляция и др. |

## Быстрый старт

### Установка

CLI:
```bash
openclaw skills install surgery-pmph-10edition
```

Prompt:
```bash
Before installing anything, inspect the ClawHub skill metadata and setup requirements.
If the skill asks you to install a third-party package or CLI, verify its source, maintainer, and package contents before running the install command.
Install the skill "Surgery-PMPH-10edition" (xllgreen/surgery-pmph-10edition) from ClawHub only after those checks pass.
Skill page: https://clawhub.ai/xllgreen/surgery-pmph-10edition
Keep the work scoped to this skill only.
After install, help me finish setup from verified skill metadata.
Use only the metadata you can verify from ClawHub; do not invent missing requirements.
Ask before making any broader environment changes.
```

### Поиск навыков

```bash
# Поиск по ключевому слову
bash scripts/skill-search.sh аппендицит

# Создание отчёта по навыкам
bash scripts/skill-report.sh
```

### Использование

Каждый навык состоит из четырёх разделов:
1. **Показания** — Когда применять данный навык
2. **Этапы выполнения** — Стандартизированный алгоритм действий
3. **Меры предосторожности** — Противопоказания и предупреждения
4. **Ссылки** — Дополнительные подробные материалы

## Об авторе

**xllgreen ([xllgreen.github.io](https://xllgreen.github.io))** — Студент-медик Клинического медицинского факультета Университета Цзюцзян · Техно-гик

## Лицензия

Содержимое этого проекта составлено на основе учебника «Хирургия» (10-е издание) издательства «Народное медицинское издательство» и предназначено только для учебных целей.

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FSurgery-PMPH-10edition-&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&legend=top-left" />
 </picture>
</a>
