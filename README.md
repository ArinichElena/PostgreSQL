# Работа с PostgreSQL
## cmd
#### Подключиться к ВМ:
> ssh arinich@публичный_ключ
<image src="https://github.com/ArinichElena/PostgreSQL/blob/main/подключение%20к%20БД.png">

#### Посмотреть список БД:
> pg_lsclusters
<image src="https://github.com/ArinichElena/PostgreSQL/blob/main/список%20БД.png">

#### Подключиться к системному пользователю postgres из под ubuntu:
> sudo -u postgres psql
<image src="https://github.com/ArinichElena/PostgreSQL/blob/main/подключение%20к%20пользователю.png">

#### Посмотреть имеющиеся БД:
> \l
<image src="https://github.com/ArinichElena/PostgreSQL/blob/main/имеющиеся%20БД.png">

#### Посмотреть информацию о подключении:
> \conninfo
<image src="https://github.com/ArinichElena/PostgreSQL/blob/main/информация%20о%20подключении.png">

#### Подключение к БД:
> \c postgres
<image src="https://github.com/ArinichElena/PostgreSQL/blob/main/подключение%20к%20БД.png">

#### Посмотреть версию СУБД:
> select version();
<image src="https://github.com/ArinichElena/PostgreSQL/blob/main/посмотреть%20версию%20СУБД.png">
  
## Dbeaver
#### Подключение через Dbeaver:
<image src="https://github.com/ArinichElena/PostgreSQL/blob/main/Dbeaver.png">
  
#### Посмотреть версию СУБД через Dbeaver:
<image src="https://github.com/ArinichElena/PostgreSQL/blob/main/Dbeaver%20(version%20BD).png">  
