# Подключение скриптов: sync, async, defer

Учебная задача о том, как браузер загружает и выполняет скрипты: встроенный, синхронный, `async` и `defer`.

**Решение:** [src/index.html](src/index.html): четыре способа подключения скрипта в одном документе.

Стек: HTML, JavaScript, тесты Jest.

## Условие задачи

В файле `src/index.html` добавьте на страницу следующие скрипты:

-   Встроенный скрипт, который будет исполнять следующий код:

```javascript
document.body.append('inline');
```

-   Внешний скрипт `src/scripts/sync.js`
-   Внешний скрипт `src/scripts/async.js` с атрибутом async
-   Внешний скрипт `src/scripts/defer.js` с атрибутом defer

## Запуск

```
npm install
npm run test
```
