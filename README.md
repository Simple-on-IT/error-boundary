# ErrorBoundary | Frontend Advent #7

## Задача:
Реализовать ErrorBoundary для обработки ошибок приложения и добавить возможность копирования текста ошибки.

## Как выполнить задание:
1. В файлу `routeConfig.tsx` оберните компонент `<MainPage />` в компонент `ErrorBoundary`.
2. Проверьте работоспособность ErrorBoundary в продакшене:
- Соберите проект командой `npm run build`.
- Запустите preview через `npm run preview`.
3. В файле `ErrorBoundary.tsx` допишите функцию onCopy. Эта функция должна копировать текст ошибки в буфер обмена.

## Запуск проекта:
* `npm i` - установка библиотек
* `npm run dev` - сборка для разработки
* `npm run build` - билд проекта
* `npm run preview` - сборка продакшен версии


## Дополнительные материалы:
Документация - https://ru.react.js.org/docs/error-boundaries.html  
Видео - https://youtube.com/shorts/N22IRkGXi8M?feature=share
