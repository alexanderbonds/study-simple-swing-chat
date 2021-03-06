# Простой чат на Java

## Цели
Знакомство с языком, возможностями графического интерфейса, сетевыми соединениями, базами данных и многопоточностью.

## Описание
Учебный проект чата на Java. Реализованные возможности:
- обмен сообщениями
- хранение данных пользователей в базе данных
- сохранение истории чата в файл

## Структура проекта
Проект состоит из четырех модулей:
1. `chat-server`: классы сервера и база данных пользователей;
2. `chat-client`: классы клиента;
3. `chat-library`: библиотека команд для обмена сообщениями (общий модуль);
4. `network`: классы-обертки над потоками (общий модуль).

## Используемые технологии
- **Swing**: графический интерфейс;
- **JDBC**: соединение с базой данных;
- **SQLite**: база данных;
- **Maven**: сборщик проекта.
