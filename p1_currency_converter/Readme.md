p_1_currency_converter

# Общая информация
Это консольное приложение, которое позволяет конвертировать валюты из одной в другую.

# Flow
1. One-One:
	- Выбрать валюту #1
	- Ввести сумму
	- Выбрать валюту #2
	- Получить ответ
2. One-Many:
	- Выбрать валюту #1
	- Ввести сумму
	- Выбрать все валюты
	- Получить список всех расчетов
3. Изменить курс:
	- Выбрать валюту #1
	- Выбрать валюту #2
	- Ввести сумму курса

# Требования
## База
- Загрузка актуального курса из *.csv
- Для расчетов использовать memory-cache
- Сохранять изменения курса в *.csv
- Общая ветка develop
- Каждая задача в ветке feature/{название задачи}
`feature/add_csv_logical`
## Стек
- Язык: GO::latest
- Хранилище: memory-cache, *.csv
- Логгирование: log
- Архитектура: MVC || MVP

# Отправка на ревью
- Создать репозиторий с названием проекта `P_1_Сurrency_converter`
- Добавить `@vladjong` в [личный репозиторий для ревью](https://docs.github.com/ru/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository)
- Отправить ссылку в телеграмм `@va_gaidenko`
- Добавить файл с Readme.md для проекта, где будет описан весь flow

*При расчетах помни про копейки