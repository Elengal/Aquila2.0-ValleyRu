<div align="center">

# 🦅 Aquila 2.0 Valley — Русификатор

**Полный русский перевод мода [Aquila 2.0 Valley](https://steamcommunity.com/sharedfiles/filedetails/?id=3280990469) для RimWorld**

[![RimWorld](https://img.shields.io/badge/RimWorld-1.6-blueviolet?style=flat-square)](https://rimworldgame.com/)
[![Язык](https://img.shields.io/badge/Перевод-Русский-red?style=flat-square)]()
[![Версия](https://img.shields.io/badge/Версия_мода-2.0-orange?style=flat-square)]()
[![Лицензия](https://img.shields.io/badge/Лицензия-MIT-green?style=flat-square)](LICENSE)

</div>

---

## 📖 О моде

**Aquila 2.0 Valley** (天鹰谷 — Долина Аквилы) — масштабное дополнение к Aquila 2.0 Core, добавляющее новые фракции, механику механоидов СиГу (西谷), систему репутации, новые типы брони, оружия, зданий, способностей и предысторий персонажей. Мод значительно расширяет лор вселенной Аквилы.

Данный русификатор переводит мод на русский язык, опираясь на **китайский оригинал автора** — более богатый и полный, чем английская локализация.

## ⚙️ Установка

### Вариант 1: Через Steam Workshop
Подписка на русификатор в Steam Workshop автоматически загрузит и обновит перевод.

### Вариант 2: Вручную
1. Скачайте [последний релиз](../../releases) или нажмите **Code → Download ZIP**
2. Распакуйте папку в директорию `RimWorld/Mods/`
3. Убедитесь, что структура выглядит так: `Mods/Aquila2.0-ValleyRu/About/About.xml`
4. Запустите RimWorld и включите мод в менеджере модов

## 📋 Зависимости

| Мод | Ссылка | Примечание |
|-----|--------|------------|
| **Aquila 2.0 Valley** | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3280990469) | Обязательный |
| **Aquila 2.0 Core** | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3280989190) | Обязательный |
| **Aquila 2.0 Core Ru** | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3607397722) / [GitHub](https://github.com/Elengal/Aquila2.0-CoreRu) | Обязательный |
| **Базовый русификатор RimWorld** | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3615283148) | Обязательный |
| **HAR (Humanoid Alien Races)** | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=839005762) | Обязательный |
| **HAR Русификатор** | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3616740991) | Обязательный |

> ⚠️ **Порядок загрузки:** Aquila 2.0 Core → Aquila 2.0 Core Ru → Aquila 2.0 Valley → Aquila 2.0 Valley Ru

## ✨ Особенности перевода

- 🌏 Перевод основан на **китайском оригинале**, а не на английской локализации — сохранена полнота авторского замысла
- 📝 Унифицированная терминология с Core-русификатором — единообразный лор
- 🤖 Переведены способности механоидов СиГу, предыстории персонажей, система репутации
- ✅ Исправлены критические ошибки: неверные части тела, путаница фракций, непереведённые фрагменты

## 📐 Принципы перевода

| Китайский | Русский | Обоснование |
|-----------|---------|-------------|
| 天鹰 | Аквила | Имя собственное, не переводится |
| 天鹰谷 | Долина Аквилы | Географическое название |
| 西谷 | СиГу | Имя собственное расы механоидов |
| 光辉圣约共和国 | Республика Завета Славы | Государство |
| 光辉圣堂 | Храм Славы | Религиозная организация |
| 蓝影 | Синяя тень | Название броникостюма |
| 布伦希尔德 | Брюнхильда | Мифологическое имя |
| 弗蕾雅 | Фрейя | Мифологическое имя |

## 🐛 Нашли ошибку?

Если вы обнаружили:
- Неточный или корявый перевод
- Непереведённый текст
- Несоответствие оригиналу
- Опечатку

Смело создавайте [Issue](../../issues) — мы разберёмся!

## 💬 Обсуждения

Есть предложения, вопросы или хотите обсудить перевод? Загляните в [Discussions](../../discussions)!

## 🤝 Участие в переводе

Приветствуется любая помощь! Если хотите улучшить перевод:
1. Форкните репозиторий
2. Создайте ветку с описанием правок (`fix/название-исправления`)
3. Внесите изменения
4. Откройте Pull Request с описанием

## 📂 Структура репозитория

```
Aquila2.0-ValleyRu/
├── About/
│   ├── About.xml          # Метаданные мода
│   ├── ModIcon.png        # Иконка мода
│   └── Preview.png        # Превью
├── 1.6/
│   ├── Valley/            # Базовый контент Valley
│   │   └── Languages/Russian (Русский)/
│   │       ├── DefInjected/   # Переводы Def-объектов
│   │       │   ├── AbilityDef/
│   │       │   ├── AlienRace.AlienBackstoryDef/
│   │       │   ├── BodyDef/
│   │       │   ├── FactionDef/
│   │       │   ├── GeneDef/
│   │       │   ├── HediffDef/
│   │       │   ├── ThingDef/
│   │       │   └── ...         # И другие категории
│   │       ├── Keyed/          # Переводы по ключам
│   │       └── Strings/        # Строки (имена и т.д.)
│   └── Ideology/         # Контент для DLC Ideology
│       └── Languages/Russian (Русский)/
│           └── DefInjected/
│               ├── AbilityDef/
│               ├── HediffDef/
│               ├── MemeDef/
│               ├── PreceptDef/
│               └── ...         # И другие категории
└── LoadFolders.xml        # Условия загрузки по модам
```

## 📜 Лицензия

Проект распространяется под лицензией MIT — см. файл [LICENSE](LICENSE).

---

<div align="center">

*Перевод создан с ❤️ для русскоязычного сообщества RimWorld*

</div>
