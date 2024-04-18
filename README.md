#	Project 11 – Финальный проект
## Автоматизация теста к API
### Автоматизируй сценарий, который подготовили коллеги-тестировщики:
1.	Клиент создает заказ.
2.	Проверяется, что по треку заказа можно получить данные о заказе.
### Шаги автотеста:
```
1. Выполнить запрос на создание заказа.
2. Сохранить номер трека заказа.
3. Выполнить запрос на получения заказа по треку заказа.
4. Проверить, что код ответа равен 200.
```
## Скриншот:
![App Screenshot](https://i.imgur.com/fw5mVTG.png)
### Configuration
*	URL: https://ab246018-2481-496b-9571-d709554b8df4.serverhub.praktikum-services.ru.
*	Стэк: PyCharm с пакетами: `requests`, `pytest`.