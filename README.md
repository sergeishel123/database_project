# database_project
Проект по предмету "Базы данных"
Реализация базы данных продажи автомобилей в дилерском центре

Лабораторная работа 1:

1)Создание ER-диаграммы для будущей базы данных

2)На момент текущий момент база данных состоит из 4 таблиц: Car(Автомобиль), Brand(Марка автомобиля),Model(Модель автомобиля), Buyer(Покупатель авто). Продавцом автомобиля считаем дилерский центр(надобность в таблице Продавец пока отсутствует)
Таблица Car состоит из 6 полей: id - PK, model_id - внешний ключ, ссылается на поле Model.id таблицы Model, create_date - дата изготовления авто, price - цена авто, buy_date - дата покупкки, Buyer_id - вторичный ключ, ссылается на поле id таблицы Buyer 

3)Экспорт диаграммы на сервер сайта https://sql.iscnet.ru/

Лабораторная работа 2:

1)Исправление некоторых недочётов с организации структуры БД на веб-клиенте

3)Заполнение таблиц БД 4-строками(инстанциями таблиц)

2)Написание запросов для выборки данных, включая соединение нескольких таблиц(с помощью оператора JOIN)
