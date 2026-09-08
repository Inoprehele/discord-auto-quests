------------------ENGLISH-----------------
# discord-auto-quests
An automated JavaScript script for Discord PTB clients and the web version that allows users to complete Discord Quests (such as watching videos or emulating the launch of games, streams, and activities) in the background.
# Discord Quests Auto-Runner 🚀
An automated JavaScript script for Discord desktop clients and the web version, allowing you to complete **Discord Quests** (video watching, game launch, stream, and activity emulation) in the background.

---

## ✨ Features

* **Support for all quest types:**
  * 📹 Video watching (`WATCH_VIDEO`, `WATCH_VIDEO_ON_MOBILE`)
  * 🎮 Game launch emulation (`PLAY_ON_DESKTOP`)
  * 📡 Stream emulation (`STREAM_ON_DESKTOP`)
* **Automatic ID Selection:** Deep search for `applicationId` within Discord's API structure for new and custom events.
* **Smart Queue:** Automatic sorting and sequential execution of all active quests on the account.
* **Security:** The script runs locally in your client and does not send tokens or data to third-party servers.

---

## 🚀 How to Run

0. Download **Discord PTB** ( https://ptb.discord.com/ )
1. Open **Discord PTB** or the web version of Discord.
2. Open the Developer Console:
   * **Windows / Linux:** `Ctrl + Shift + I`
   * **macOS:** `Cmd + Option + I`
3. Go to the **Console** tab.
4. Copy the code from the `index.js` file, paste it into the console, and press `Enter`.

---

## 🎮 Control Commands

After launching the script, the following functions are available in the console:

| Command | Description |
| :--- | :--- |
| `skipQuest()` | Skip the current quest and move to the next one in the queue |
| `stopQuests()` | Completely stop the script and clear active processes |
| `getQuestQueue()` | Display current progress and the list of remaining quests |

---

## ⚠️ Disclaimer

This tool was created exclusively for educational and informational purposes. Running scripts in the Discord console may violate Discord's Terms of Service (ToS). Use this script at your own risk.







----------RUSSIAN--------------
Автоматический JavaScript-скрипт для клиентов PTB и веб-версии Discord, позволяющий проходить задания **Discord Quests** (просмотр видео, эмуляция запуска игр, стримов и активностей) в фоновом режиме.

---

##  Возможности

* **Поддержка всех типов квестов:**
  * 📹 Просмотр видео (`WATCH_VIDEO`, `WATCH_VIDEO_ON_MOBILE`)
  * 🎮 Эмуляция запуска игр (`PLAY_ON_DESKTOP`)
  * 📡 Эмуляция стриминга (`STREAM_ON_DESKTOP`)
* **Автоматический выбор ID:** Глубокий поиск `applicationId` в структуре API Discord для новых и кастомных ивентов.
* **Умная очередь:** Автоматическая сортировка и последовательное выполнение всех активных квестов на аккаунте.
* **Безопасность:** Скрипт выполняется локально в вашем клиенте и не передает токены или данные на сторонние серверы.

---

## 🚀 Инструкция по запуску
0. Скачайте **Discord PTB**(https://ptb.discord.com/)
1. Откройте **Discord PTB** или браузерную версию Discord.
2. Откройте консоль разработчика:
   * **Windows / Linux:** `Ctrl + Shift + I`
   * **macOS:** `Cmd + Option + I`
3. Перейдите на вкладку **Console** (**Консоль**).
4. Скопируйте код из файла `index.js`, вставьте его в консоль и нажмите `Enter`.

---

## 🎮 Команды управления

После запуска скрипта в консоли доступны следующие функции:

| Команда | Описание |
| :--- | :--- |
| `skipQuest()` | Пропустить текущий квест и перейти к следующему в очереди |
| `stopQuests()` | Полностью остановить работу скрипта и очистить процессы |
| `getQuestQueue()` | Показать текущий прогресс и список оставшихся квестов |

---

## ⚠️ Отказ от ответственности (Disclaimer)

Данный инструмент создан исключительно в ознакомительных и образовательных целях. Использование скриптов в консоли Discord может нарушать Условия использования сервиса (Discord ToS). Вы используете данный скрипт на свой страх и риск.
