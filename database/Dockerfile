FROM mysql:8.0-debian
EXPOSE 3000

ENV MYSQL_ROOT_PASSWORD=password
ENV MYSQL_DATABASE=todo
ENV MYSQL_USER=todo-user
ENV MYSQL_PASSWORD=password

COPY ./scripts/init.sql /docker-entrypoint-initdb.d/
