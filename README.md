# Geekbrains React

## Оглавление

- [Урок 1. Настройка среды разработки и первое React-приложение](#Урок-1)
- [Урок 2. Жизненный цикл React-компонента](#Урок-2)
- [Урок 3. Продолжаем погружение в React и подключаем UI-библиотеку](#Урок-3)
- [Урок 4. Роутинг в React: разбиваем мессенджер на чаты](#Урок-4)
- [Урок 5. Redux. Управление состоянием приложения](#Урок-5)

## Урок 1
### Настройка среды разработки и первое React-приложение

- Создан проект
- Настроены package.json и webpack.config
- Установлен webpack-dev-server
- Создано простейшее React-приложение с использованием функциональных компонентов

## Урок 2
### Жизненный цикл React-компонента

- Разобран жизненный цикл компонентов на примере App и Child
- Созданы компоненты MessageField и Message
- Реализована отправка сообщений по нажатию кнопки
- Реализован ответ от робота

## Урок 3
### Продолжаем погружение в React и подключаем UI-библиотеку

- Подключён Material-UI
- Сделана первичная вёрстка, явно выделено поле для сообщений
- Визуально разделены сообщения от пользователя и ответы робота
- Добавлена возможность ввода текста сообщения и его отправки


## Урок 4
### Роутинг в React: разбиваем мессенджер на чаты

- Подключён BrowserRouter
- Создать верхний компонент Router
- Приложение разбито на чаты с помощью роутера (URLs: /chat/<chat_id>/)
- Реализовано хранение сообщений в словаре с id в качестве ключа
- Реализовано хранение чатов в словаре (chatId: {title: название, messageList: массив из id сообщений})

## Урок 5
### Redux. Управление состоянием приложения

- Подключён Redux
- Подключено расширение Redux DevTools
- Созданы action-ы отправки сообщения и добавления чата
- Чаты перенесены в Redux