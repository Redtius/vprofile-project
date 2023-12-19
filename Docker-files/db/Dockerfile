FROM mysql:8.0.33

LABEL name="database"
LABEL version="1.0"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD ./db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql

