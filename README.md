# budget

# Budget Version 1.0

Цель: Реализовать минимальный функционал, что бы сразу начать пользоваться продуктом

Технологии: python, FastApi, SqlAlchemy

Функционал api
1. Регистрация и авторизация
2. Добавление расхода
3. Просмотр расходов: Всё время, месяц и день

Данные
1. User
    - id
    - username
    - email
2. ExpenseTransaction
    - id
    - author_id
    - created_at
    - value
    - description