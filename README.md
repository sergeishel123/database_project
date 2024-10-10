# database_project
Проект по предмету "Базы данных"
Реализация базы данных продажи автомобилей в дилерском центре

# ЛАБОРАТОРНАЯ РАБОТА 1:

1)Создание ER-диаграммы для будущей базы данных

2)На момент текущий момент база данных состоит из 4 таблиц: Car(Автомобиль), Brand(Марка автомобиля),Model(Модель автомобиля), Buyer(Покупатель авто). Продавцом автомобиля считаем дилерский центр(надобность в таблице Продавец пока отсутствует)
Таблица Car состоит из 6 полей: id - PK, model_id - внешний ключ, ссылается на поле Model.id таблицы Model, create_date - дата изготовления авто, price - цена авто, buy_date - дата покупкки, Buyer_id - вторичный ключ, ссылается на поле id таблицы Buyer 

Таблица Brand состоит из 4 полей : id - PK, name - название марки авто, main_office - город и страна компании, email - электронная почта, возможно NULL

Таблица Model состоит из 3 полей: id -PK, name - название модели авто, brand_id - внешний ключ FK, ссылается на поле id таблицы Brand

Таблица Buyer состоит из 4 полей : id - PK, name - имя покупателя, mobile_phone - номер телефона , age - возраст


3)Экспорт диаграммы на сервер сайта https://sql.iscnet.ru/

# ЛАБОРАТОРНАЯ РАБОТА 2:

1)Исправление некоторых недочётов с организации структуры БД на веб-клиенте

3)Заполнение таблиц БД 4-строками(инстанциями таблиц)

2)Написание запросов для выборки данных, включая соединение нескольких таблиц(с помощью оператора JOIN)

# ЛАБОРАТОРНАЯ РАБОТА 3:
1)Создание представления price_buyer, хранящее в себе SELECT - запрос с соединением полей Car.price и Byuer.name из таблиц Car и Buyer соответсвенно
price_buyer позволяет быстро получить информацию о том, какую цену заплатил дилер за покупку автомобиля

# ЛАБОРАТОРНАЯ РАБОТА 4:
1) Проверка работы индексов или хэшей
