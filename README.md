[![Build status](https://ci.appveyor.com/api/projects/status/hh1adgw2ngiqy6rh/branch/main?svg=true)](https://ci.appveyor.com/project/homutovan/shedulizzzer/branch/main)
[![Code style: airbnb](https://img.shields.io/badge/code%20style-airbnb-blue.svg?style=flat-square)](https://github.com/airbnb/javascript)
[![CodeScene Code Health](https://codescene.io/projects/10004/status-badges/code-health)](https://codescene.io/projects/10004)
[![CodeScene System Mastery](https://codescene.io/projects/10004/status-badges/system-mastery)](https://codescene.io/projects/10004)

# SheduliZZZer

## Веб-приложение для автоматизированного составления и оптимизации расписания лекций

### Перед тем, как что-то сюда запушить, сделай следующее:

- Настрой IDE;
- Ознакомься с инструкцией по работе с проектом;
- Убедись, что находишься в ветке main;
- Ознакомься с
  [материалами для самостоятельного изучения ГИТ](https://githowto.com/ru)

### Настройки IDE.

В проекте используется EditorConfig. Некоторые IDE не подхватывают настройки
EditorConfig автоматически - требуют установки расширения. Узнать о
необходимости загрузки и ссылку на расширение для поддерживаемых IDE можно
[здесь](https://editorconfig.org/#download)

Если IDE не поддерживается, нет желания что то еще устанавливать в и так
переполнненый расширениями редактор, или хочется настроить все вручную Мы
используем:

- Кодировка файлов - UTF-8;
- Для отступов 2 пробелa;
- Окончание строки - LF;
- Файл заканчиваем одной пустой строкой.

### Инструкция по работе с проектом

#### Для начала работы с проектом выполните следующие действия:

1. Скачайте и установите [node.js](https://nodejs.org/en/);
2. Клонируйте репозиторий себе на локальную машину
3. Создайте новую ветку с именем, отражающим суть внедряемой фичи;
4. Установите зависимости командой в терминале **npm install**;
5. Внесите необходимые измененияя в файлы проекта;
6. Запустите проект командой - **npm start** и убедитесь в корректности
   внесенных изменений;
7. Запустите скрипт автокоррекции кода - **npm run prettier**;
8. Запустите линтеры для проверки качества кода - **npm run lint**;
9. Исправьте ошибки, выданные линтерами;
10. Если ошибок больше нет - сделайте коммит в созданную ветку;
11. Сделайте пуш в репозиторий.

### Список команд npm:

- **npm start** - запуск дев-сервера;
- **npm run build** - запуск сборки проекта;
- **npm run show:dist** - запуск собранной версии;
- **npm run lint** - запуск линтеров для всех типов файлов;
- **npm run jslint** - запуск линтера для **JS**;
- **npm run lint-html** - запуск линтера для **HTML**;
- **npm run stylelint** - запуск линтера для **CSS**;
- **npm test** - запуск тестов;
- **npm run coverage** - запуск проверки покрытия кода тестами;
- **npm run prettier** - запуск автоформаттера кода.

### Информация о проекте

[Ссылка](https://github.com/Aspirants-FS-FE/SheduliZZZer/wiki)

### Kanban-доска проекта

[Ссылка](https://github.com/orgs/Aspirants-FS-FE/projects/1)
