## ------------------ENGLISH-----------------
---
# discord-auto-quests
An automated JavaScript script for Discord PTB clients and the web version that allows users to complete Discord Quests in the background.

# Discord Quests Auto-Runner v3.2 🚀
An automated JavaScript script with a built-in GUI for Discord desktop clients and the web version, allowing you to easily complete **Discord Quests** (video watching, game launch, stream, and activity emulation).

---

## ✨ Features

* **🎨 Built-in GUI Panel:** Floating overlay right inside the Discord client with status updates and control buttons.
* **📜 Interactive Log Box:** Real-time log window with timestamps, event coloring, and **copyable text** (`user-select: text`).
* **🎯 Manual Queue Control:**
  * Initial queue is empty upon launch — complete only what you want.
  * Select specific quests from a dropdown list to add them to the queue.
  * **"➕ All" Button:** Add all incomplete quests to the queue in one click.
* **⚡ Direct API Heartbeats (No Hanging):** Directly sends progress requests to Discord's `/quests/{id}/heartbeat` API, bypassing native process detection bugs.
* **📹 Support for all quest types:**
  * Video watching (`WATCH_VIDEO`, `WATCH_VIDEO_ON_MOBILE`)
  * Game launch emulation (`PLAY_ON_DESKTOP`)
  * Stream emulation (`STREAM_ON_DESKTOP`)
  * Activity play (`PLAY_ACTIVITY`)
* **🔒 Security:** Runs 100% locally in your client console and never sends tokens or data to third-party servers.

---

## 🚀 How to Run

1. Open **Discord PTB** or the web version of Discord.
2. Open Developer Tools / Console:
   * **Windows / Linux:** `Ctrl + Shift + I`
   * **macOS:** `Cmd + Option + I`
3. Go to the **Console** tab.
4. Copy the code from `index.js`, paste it into the console, and press `Enter`.

---

## 🎮 Interface & Controls

| Element / Command | Function |
| :--- | :--- |
| **Dropdown Menu** | Select and add a specific quest to the execution queue |
| **`➕ All` Button** | Enqueue all remaining active quests on the account |
| **`⏭️ Skip` Button** | Skip the currently active quest and move to the next in queue |
| **`🛑 Stop` Button** | Stop all tasks, clean up process mocks, and remove UI overlay |
| **Log Window** | Shows real-time progress and errors. Text can be freely selected and copied |
| `window.skipQuest()` | Console command to skip current quest |
| `window.stopQuests()` | Console command to stop the runner completely |

---

## ⚠️ Disclaimer

This tool was created exclusively for educational and informational purposes. Running scripts in the Discord console may violate Discord's Terms of Service (ToS). Use this script at your own risk.





---

## ----------RUSSIAN--------------
---
Автоматический JavaScript-скрипт с графическим интерфейсом для клиентов PTB и веб-версии Discord, позволяющий проходить задания **Discord Quests** (просмотр видео, эмуляция запуска игр, стримов и активностей) в фоновом режиме.

# Discord Quests Auto-Runner v3.2 🚀

---

## ✨ Возможности

* **🎨 Встроенный графический интерфейс (GUI):** Плавающее окно поверх клиента Discord со статусом выполнения и кнопками управления.
* **📜 Интерактивное окно логов:** Вывод событий в реальном времени с метками времени, подсветкой ошибок и **возможностью выделения и копирования текста**.
* **🎯 Гибкое управление очередью:**
  * При запуске скрипта очередь изначально пуста.
  * Выбор и добавление нужного квеста из выпадающего списка.
  * **Кнопка «➕ Все»:** Добавление всех незавершённых квестов в очередь в один клик.
* **⚡ Прямая отправка API Heartbeat (Без зависаний):** Прямые запросы к API Discord (`/quests/{id}/heartbeat`), исключающие зависания эмуляции процессов.
* **📹 Поддержка всех типов квестов:**
  * Просмотр видео (`WATCH_VIDEO`, `WATCH_VIDEO_ON_MOBILE`)
  * Эмуляция запуска игр (`PLAY_ON_DESKTOP`)
  * Эмуляция стриминга (`STREAM_ON_DESKTOP`)
  * Активности (`PLAY_ACTIVITY`)
* **🔒 Безопасность:** Скрипт выполняется на 100% локально в вашем клиенте и не передает токены или данные на сторонние серверы.

---

## 🚀 Инструкция по запуску

1. Откройте **Discord PTB** или браузерную версию Discord.
2. Откройте консоль разработчика:
   * **Windows / Linux:** `Ctrl + Shift + I`
   * **macOS:** `Cmd + Option + I`
3. Перейдите на вкладку **Console** (**Консоль**).
4. Скопируйте код из файла `index.js`, вставьте его в консоль и нажмите `Enter`.

---

## 🎮 Элементы управления и команды

| Элемент / Команда | Описание |
| :--- | :--- |
| **Выпадающий список** | Выбрать конкретный квест и добавить его в очередь |
| **Кнопка `➕ Все`** | Добавить сразу все доступные незавершённые квесты в очередь |
| **Кнопка `⏭️ Скип`** | Пропустить текущий выполняемый квест и перейти к следующему |
| **Кнопка `🛑 Стоп`** | Полностью остановить работу, очистить виртуальные процессы и закрыть интерфейс |
| **Окно логов** | Отображает прогресс и ошибки. Текст внутри окна можно свободно выделять мышью и копировать |
| `window.skipQuest()` | Команда в консоли для пропуска текущего квеста |
| `window.stopQuests()` | Команда в консоли для полной остановки скрипта |

---

## ⚠️ Отказ от ответственности (Disclaimer)

Данный инструмент создан исключительно в ознакомительных и образовательных целях. Использование скриптов в консоли Discord может нарушать Условия использования сервиса (Discord ToS). Вы используете данный скрипт на свой страх и риск.
