## Описание/Пошаговая инструкция выполнения домашнего задания:
* Добавить индексы в свой проект, сравнить производительность запросов
---
#### 1. Используем ранее установленный mongodb на сервере mongo-2
Загрузим набор данных побольше, с того же Портала открытых данных - https://opendata.mkrf.ru/opendata
![image](https://user-images.githubusercontent.com/8801291/212250038-daf417da-d7d4-479c-9c2d-74bb92f9a455.png)
#### 2. Поиск по дате без индекса
![image](https://user-images.githubusercontent.com/8801291/212252118-ce38b4f8-c258-43e2-b480-83ca867f6f51.png)
#### 2. Поиск по дате c индексом
Создадим индекс и запустим тот же запрос
![image](https://user-images.githubusercontent.com/8801291/212252892-041d76be-213f-4ca6-9191-390e359e9084.png)
![image](https://user-images.githubusercontent.com/8801291/212252963-7d8e02c8-fed8-4555-9ce6-a65f792b12d4.png)
Видим, что победил план план с IXSCAN вместо предыдущего запроса с COLLSCAN.
Время executionTimeMillis: 1 вместо executionTimeMillis: 11917 в запросе без индекса ✨Magic ✨


