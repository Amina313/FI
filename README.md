# FINAL project
основные цели и задачи проекта;
Цель проекта — разработать сервис для предсказания стоимости домов на основе истории предложений.

краткую информацию о данных;
Каждая недвижимость описывается следующими признаками:
1. status - статус
2. private pool	- частный бассейн
3. propertyType	- тип недвижимости
4. street	- улица
5. baths	- бани
6. homeFacts-	предметы домашнего обихода
7. fireplace-	камин
8. city	- город
9. schools	- школы
10. sqft	- площадь
11. zipcode	- почтовый индекс
12. beds	- кровати
13. state	- штат
14. stories	- истории
15. mls-id	- mls-идентификатор
16. PrivatePool	- личный бассейн
17. MlsId	 - MLSидентификатор
18. target - цель(целевой признак)

этапы работы над проектом.
Шаг 1: Определение задачи

Цель проекта: Создать сервер, который будет принимать данные о домах и возвращать предсказанную стоимость.

Шаг 2: Сбор данных

Источники данных:
Открытые базы данных (например, Kaggle, Zillow, Redfin).

Шаг 3: Предобработка данных

Очистка данных: Удалияем пропуски, дубликаты и аномалии.
Преобразование данных: Преобразуем категориальные переменные в числовые (например, с помощью one-hot encoding).
Нормализация: Нормализуем числовые данные для улучшения работы модели.

Шаг 4: Анализ данных

Визуализация: Используем библиотеки, такие как Matplotlib и Seaborn, для визуализации данных и выявления закономерностей.
Корреляционный анализ: Определяем, какие факторы наиболее сильно влияют на стоимость домов.

Шаг 5: Моделирование

 Рассмотрим различные алгоритмы машинного обучения, такие как:
* Линейная регрессия
* Деревья решений
* Случайный лес
* Градиентный бустинг
Разделяем данные на обучающую и тестовую выборки, обучяем модель и оценим её производительность с помощью метрик (MAE, RMSE и т.д.).

Шаг 6: Разработка сервера

Выбор фреймворка: Используем Flask или FastAPI для создания RESTful API.
Создание API:
Создадим эндпоинт для получения данных о доме.
Реализуем логику для обработки входящих данных и предсказания стоимости.
Документация API: Используем Swagger или Postman для документирования вашего API.

Шаг 7: Развертывание

Выбор платформы: Рассмотрим использование облачных платформ, таких как Heroku, AWS или Google Cloud.
Контейнеризация: Используем Docker для упрощения развертывания и управления зависимостями.
Мониторинг: Настроем мониторинг и логирование для отслеживания работы сервера.

Шаг 8: Тестирование

Провём тестирование API, чтобы убедиться, что он работает корректно.


Шаг 9: Документация

Подготовим полную документацию, включая описание модели, API и инструкции по развертыванию.
