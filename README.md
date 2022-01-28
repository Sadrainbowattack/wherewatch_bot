# project_bot
Проект бота для LearnPython
Данный бот позволяет искать фильм\сериал на нескольких подписочных сервисах одновременно. 
Пользователь вводит команду '/search "Название"' и получает ссылки на данный фильм в популярных подписочных сервисах.
Реализованы следующие сервисы: Kinopoisk, Netflix, Okko, Ivi.
Бот использует в работе Selenium WebDriver и используется база данных PostgreSQL.

### Установка
1. Клонируйте репозиторий, создайте виртуальное окружение
2. Установите зависимости `pip install -r requirements.txt`
3. Создайте файл settings.py и создайте в нем переменные:
API_KEY='Ключ вашего бота'
BD_KEY='Ссылка на вашу Базу данных'
n_login = 'Логин netflix'
n_password = 'Пароль netflix'

### Запуск
Чтобы запустить бота, выполните в консоли:python bot_main.py
