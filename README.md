# Работа с PostgreSQL
## Подключиться к ВМ: 
> ssh arinich@публичный_ключ
<image src="https://github.com/ArinichElena/PostgreSQL/blob/main/подключение%20к%20БД.png">

Посмотреть список БД:
pg_lsclusters



Подключиться к системному пользователю postgres из под ubuntu:
sudo -u postgres psql


Посмотреть имеющиеся БД:
\l



Посмотреть информацию о подключении:
\conninfo


Подключение к БД:
\c postgres


Посмотреть версию СУБД:
select version();


![image](https://user-images.githubusercontent.com/127325338/228846658-8043ea06-09d4-496b-89f1-dc09a3e10419.png)

