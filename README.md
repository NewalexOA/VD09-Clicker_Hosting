# Кликер - Учебный проект

## Описание

Этот проект представляет собой простое веб-приложение, разработанное на основе Flask, с игровой механикой, связанной с подсчетом кликов. Приложение включает функционал регистрации и аутентификации пользователей. 

## Функциональность

- **Регистрация пользователей**: Пользователи могут зарегистрировать новый аккаунт.
- **Аутентификация**: Вход и выход из системы.
- **Подсчет кликов**: Основная игровая механика, позволяющая пользователям увеличивать количество кликов, нажимая на кнопку.

## Установка

1. **Клонируйте репозиторий**:
    ```bash
    git clone https://github.com/NewalexOA/VD09-Clicker_Hosting.git
    ```
2. **Перейдите в директорию проекта**:
    ```bash
    cd VD09-Clicker_Hosting
    ```
3. **Создайте и активируйте виртуальное окружение**:
    ```bash
    python -m venv venv
    source venv/bin/activate   # Для Windows: venv\Scripts\activate
    ```
4. **Установите зависимости**:
    ```bash
    pip install -r requirements.txt
    ```

## Использование

1. **Запустите приложение**:
    ```bash
    flask run
    ```
2. **Откройте в браузере**:
    ```
    http://127.0.0.1:5000
    ```

## Структура проекта

- `models.py`: Определяет модели базы данных.
- `routes.py`: Определяет маршруты и логику обработки запросов.
- `templates/`: Содержит HTML-шаблоны.
  - `base.html`: Базовый шаблон.
  - `index.html`: Главная страница с игрой.
  - `login.html`: Страница входа.
  - `register.html`: Страница регистрации.
- `static/`: Содержит статические файлы (CSS, JS).

## Лицензия

Этот проект предназначен исключительно для учебных целей.