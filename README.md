<h1 align="center">Привет, я MRBuggI/Карим/Бугги 👋</h1>
<p align="center">
  Java-разработчик модов и плагинов для Minecraft · 3D и веб в команде <b>BuffTeam</b><br>
  Java developer of Minecraft mods and server plugins · 3D and web at <b>BuffTeam</b>
</p>

<p align="center">
  <a href="#-русский">Русский</a> · <a href="#-english">English</a>
</p>

<p align="center">
  <b>Заказы / Commissions:</b> <a href="https://t.me/Minebughelpbot">@Minebughelpbot</a> в Telegram
</p>

---

## 🇷🇺 Русский

Делаю моды под **Fabric**, **Forge** и **NeoForge** и плагины под **Paper**. Меня интересуют не только игровые фичи, но и то, что под капотом: производительность на больших серверах, совместимость в сборках на сотни модов, честная физика без костылей.

**Работа на заказ:**
- моды по техническому заданию заказчика;
- сборки под заказ: подбор модов, совместимость, настройка;
- доработки и правки для постоянного заказчика.

Версии: Fabric и NeoForge от 1.20.1, Forge от 1.19.2, Paper 1.21. Работаю удалённо, 3-4 часа в день.

**Что для меня важно в коде:**
- **Производительность.** Тяжёлую работу размазываю по тикам, кэширую поиск сущностей, не создаю лишний сетевой трафик.
- **Совместимость.** Где можно обойтись событиями загрузчика, обхожусь без миксинов.
- **Понятность.** README объясняет не только «как запустить», но и «почему сделано так».
- **Автоматизация.** Каждый проект собирается в GitHub Actions, релизы публикуются по тегу.

### ⭐ Избранные проекты

| Проект | О чём | Стек |
|---|---|---|
| [**LagLens**](https://github.com/MrBuggI/LagLens) | Диагностика лагов сервера человеческим языком: где лагает и что с этим делать. Скан чанков размазан по тикам, чтобы сам инструмент не вызывал лаги. | Paper 1.21 · Java 21 |
| [**Magnetism**](https://github.com/MrBuggI/magnetism) | Магнитный блок с моделью диполя: полюса притягиваются и отталкиваются в полёте. 0 миксинов, 0 своих пакетов, кэш сущностей с backoff. | NeoForge 1.21.1 · Java 21 |
| [**Graffity+**](https://github.com/MrBuggI/graffity) | Система граффити: спреи для стен, пола и потолка, ластик, заряды. Рисунок держится на блоке-опоре и исчезает вместе с ним. | Fabric 1.20.1 |
| [**Cockroach**](https://github.com/MrBuggI/CockMod) | Таракан, который живёт в окне инвентаря, убегает от курсора и ест алмазы. Один миксин-аксессор, удаление алмаза проверяет сервер. | Fabric 1.20.1 |
| [**Football**](https://github.com/MrBuggI/football) | Футбольный мяч, который можно пинать. Порт soccermod на Fabric. | Fabric 1.20.1 |
| [**3D Portfolio**](https://github.com/MrBuggI/3d-portfolio) | Сайт-витрина 3D-моделей с просмотром в реальном времени. | React · Three.js |

---

## 🇬🇧 English

I build Minecraft mods for **Fabric**, **Forge** and **NeoForge** and server plugins for **Paper**. I care about what happens under the hood: performance on large servers, compatibility in modpacks with hundreds of mods, and clean physics without hacks.

**Commission work:**
- mods built to a client's specification;
- custom modpacks: mod selection, compatibility, configuration;
- ongoing changes and fixes for a returning client.

Versions: Fabric and NeoForge from 1.20.1, Forge from 1.19.2, Paper 1.21. Remote, 3-4 hours a day.

**What I focus on:**
- **Performance.** Heavy work is spread across ticks, entity lookups are cached, no unnecessary network traffic.
- **Compatibility.** If loader events are enough, I don't use mixins.
- **Clarity.** READMEs explain not only how to run a project, but why it is built that way.
- **Automation.** Every project is built by GitHub Actions, releases are published from tags.

### ⭐ Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**LagLens**](https://github.com/MrBuggI/LagLens) | Explains server lag in plain language: where it lags and how to fix it. The chunk scan is spread across ticks so the tool never causes lag itself. | Paper 1.21 · Java 21 |
| [**Magnetism**](https://github.com/MrBuggI/magnetism) | Magnet block with a dipole model: poles attract and repel mid-air. Zero mixins, zero custom packets, cached entity lookups with backoff. | NeoForge 1.21.1 · Java 21 |
| [**Graffity+**](https://github.com/MrBuggI/graffity) | Graffiti system: spray cans for walls, floors and ceilings, eraser, limited charges. Graffiti hangs on its support block and disappears with it. | Fabric 1.20.1 |
| [**Cockroach**](https://github.com/MrBuggI/CockMod) | A cockroach that lives in the inventory screen, flees from the cursor and eats diamonds. One accessor mixin, the server validates the diamond removal. | Fabric 1.20.1 |
| [**Football**](https://github.com/MrBuggI/football) | A kickable soccer ball. Port of soccermod to Fabric. | Fabric 1.20.1 |
| [**3D Portfolio**](https://github.com/MrBuggI/3d-portfolio) | Showcase website for 3D models with real-time preview. | React · Three.js |

---

## 🛠 Стек / Tech stack

![Java](https://img.shields.io/badge/Java-E76F00?style=flat&logo=openjdk&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white)
![Fabric](https://img.shields.io/badge/Fabric-DBD0B4?style=flat)
![NeoForge](https://img.shields.io/badge/NeoForge-F08A2A?style=flat)
![Paper](https://img.shields.io/badge/Paper-444444?style=flat)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=threedotjs&logoColor=white)
![Blockbench](https://img.shields.io/badge/Blockbench-1E93D9?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
