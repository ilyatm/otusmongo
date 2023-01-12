## Описание/Пошаговая инструкция выполнения домашнего задания:
* создать новый проект в Google Cloud Platform/ЯндексОблако, например mongo2022-, где yyyymmdd год, месяц и день вашего рождения (имя проекта должно быть уникально на уровне GCP)
* далее создать инстанс виртуальной машины Compute Engine с дефолтными параметрами
* добавить свой ssh ключ в GCE metadata
* зайти удаленным ssh (первая сессия), не забывайте про ssh-add
* установить MongoDB
* зайти клиентом и создать свою БД
* настроить доступ извне и проверить подключение с ноутбука
---
#### 1. Создаём новый проект в облаке
![image](https://user-images.githubusercontent.com/8801291/212012668-e01ea851-d00e-462b-a77b-f71eb0c2cd5a.png)
#### 2. Создаём инстанс виртуальной машины
![image](https://user-images.githubusercontent.com/8801291/212012887-93aa97c6-5c31-4663-805d-cfc98726d7a1.png)
#### 3. Настраиваем авторизацию по ключу
![image](https://user-images.githubusercontent.com/8801291/212013226-19b815ed-3d27-46a0-be99-c0df090a4961.png)
#### 4. Подключаемся по ssh 
![image](https://user-images.githubusercontent.com/8801291/212013455-af85e869-fd31-449b-939c-6152e1353b59.png)
#### 5. Устанавливаем mongodb-org
![image](https://user-images.githubusercontent.com/8801291/212020331-4b0e1b79-393a-450e-af24-d333e8b130d9.png)
#### 6. подключаемся к серверу
![image](https://user-images.githubusercontent.com/8801291/212020528-a9ce6d4a-a10b-4ab4-8f43-7d5e6d5502b4.png)
