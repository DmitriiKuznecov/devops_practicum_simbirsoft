<h1>Party Parrot App</h1>

<img src='media/images/party-parrot.gif' alt='parrot' height="200" width="200">
<br>
<br>
<h3></h3>

Sample Python application on Django with PostgreSQL database.

<h3>Requirements</h3>

____


- django 4.0.1
- Pillow 9.0.0
- psycopg2-binary 2.9.3
- django-prometheus 2.2.0
- uwsgi 2.0.19.1

<h3>Deployment</h3>

____

- install Python 3.8
- install Docker - https://docs.docker.com/engine/install/ (Инструкция установки для всех ОС)
- Install Docker-compose - https://docs.docker.com/compose/install/linux/ (Инструкция установки для Linux, т.к. для MAC и Windows устанавливается Docker Desktop, который включает в себя плагин docker-compose)
- Create .env file. Необходимо создать файл с переменными окружения, по аналогии с файлом .env.example в корне проекта. У каждой переменной после равно в угловых скобках написано описание переменной, необходимо заменить их на значения, оставив после равно только значение перменной. Угловые скобки необходимо удалить тоже.

* Start application:
```shell
      docker-compose up -d
```
* Перейти по адресу который был указан в переменной - WEB_HOST_ADDRESS