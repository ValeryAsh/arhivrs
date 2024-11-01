# План на четыре недели для изучения основ бэкенд-разработки

## Неделя 1: Основы серверной разработки и Node.js

1. **Изучение клиент-серверной архитектуры и HTTP**:
   - Прочитайте про клиент-серверную модель и основы HTTP.
   - [Основы клиент-серверной архитектуры и HTTP-запросов (MDN)](https://developer.mozilla.org/ru/docs/Learn/Server-side/First_steps/Client-Server_overview)

2. **Установка и настройка Node.js**:
   - Установите Node.js и настройте среду.
   - [Официальное руководство по установке Node.js](https://nodejs.org/ru/)

3. **Основы Node.js**:
   - Посмотрите вводный курс по Node.js, изучите основное API, работу с файлами и потоками.
   - **Видео**: [Введение в Node.js для начинающих (YouTube)](https://www.youtube.com/watch?v=TlB_eWDSMt4)
   - **Текст**: [Руководство по Node.js (W3Schools)](https://www.w3schools.com/nodejs/)

4. **Создание простого сервера на Node.js**:
   - Напишите базовый HTTP-сервер, который возвращает текст или JSON.
   - [Создание HTTP-сервера на Node.js (MDN)](https://developer.mozilla.org/ru/docs/Learn/Server-side/Node_server_without_framework)

---

## Неделя 2: Express.js и работа с API

1. **Установка и настройка Express.js**:
   - Установите Express.js и создайте первый сервер.
   - [Express.js — Руководство для начинающих (YouTube)](https://www.youtube.com/watch?v=L72fhGm1tfE)

2. **Маршруты и обработка запросов в Express.js**:
   - Изучите работу с маршрутами (routes), обработку запросов GET и POST.
   - **Видео**: [Express.js для начинающих (Traversy Media)](https://www.youtube.com/watch?v=gnsO8-xJ8rs)
   - **Документация**: [Основы Express.js (Express.js Docs)](https://expressjs.com/ru/starter/basic-routing.html)

3. **Создание простого REST API**:
   - Реализуйте API для создания, чтения, обновления и удаления (CRUD) заметок.
   - **Практическое задание**: Создайте API для хранения списка задач с методами GET, POST, PUT, DELETE.

---

## Неделя 3: Работа с базами данных (SQLite)

1. **Основы SQL и запросов**:
   - Познакомьтесь с основными SQL-командами: SELECT, INSERT, UPDATE, DELETE.
   - **Видео**: [Основы SQL за 30 минут (YouTube)](https://www.youtube.com/watch?v=HXV3zeQKqGY)
   - **Текст**: [Учебник SQL (W3Schools)](https://www.w3schools.com/sql/)

2. **Установка и работа с SQLite**:
   - Установите SQLite и попробуйте работать с ним из консоли.
   - [Документация по SQLite](https://www.sqlite.org/docs.html)

3. **Подключение SQLite к Node.js**:
   - Используйте `sqlite3` или `better-sqlite3` для интеграции SQLite с Node.js.
   - **Текст**: [SQLite и Node.js — пошаговое руководство](https://www.sqlitetutorial.net/sqlite-nodejs/)

4. **Интеграция базы данных с Express API**:
   - Добавьте базу данных в приложение, чтобы хранить данные заметок.
   - **Практическое задание**: Реализуйте функции CRUD для работы с заметками через базу данных.

---

## Неделя 4: Аутентификация и создание простого проекта

1. **JWT и сессии**:
   - Изучите, как работают JSON Web Tokens (JWT), настройте базовую регистрацию и авторизацию.
   - **Видео**: [JWT и аутентификация для начинающих (YouTube)](https://www.youtube.com/watch?v=7Q17ubqLfaM)
   - **Текст**: [Руководство по JWT (MDN)](https://developer.mozilla.org/ru/docs/Web/HTTP/Authentication)

2. **Реализация аутентификации и авторизации**:
   - Добавьте регистрацию и авторизацию к вашему приложению для заметок.
   - **Практическое задание**: Реализуйте JWT-токены для управления доступом к ресурсам приложения.

3. **Финальный проект — Приложение для заметок с авторизацией**:
   - Объедините всё, что вы изучили: настройте API, базу данных и авторизацию.
   - Попробуйте протестировать проект, добавьте базовые проверки на ошибки.

---
