# Шаблон проекта
> Перед установкой зависимостей и запуском проекта убедитесь, что у вас установлена [последняя версия Node.js & NPM](https://nodejs.org/en/download/current/)

##  Чтобы развернуть проект необходимо:
```sh
$ git clone https://github.com/linata81/complex-start-template-LS.git
$ cd complex-start-template-LS
$ npm install
```

## Скрипты package.json:

| Скрипт | Назначение |
| ------ | ------ |
| dev:mpa | Разработка основного сайта. Страницы **обо мне**, **блог** и т.п. Запустит dev сценарии **Gulp**. |
| dev:spa | Разработка админ панели в стиле **SPA** на **Vue.js** |
| build  | Сборка обоеих частей проекта. Все файлы будут доступны из директории **dist** |
| reg | Консольная утилита для регистрации. Использовать перед началом работы над **админ-панелью**. |

#### Чтобы запустить скрипт:
```sh
$ npm run имя_скрипта
```
