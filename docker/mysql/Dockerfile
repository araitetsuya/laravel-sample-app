FROM mysql/mysql-server:8.0

ENV MYSQL_DATABASE=laravel
ENV MYSQL_USER=laravel
ENV MYSQL_PASSWORD=laravel
ENV MYSQL_ROOT_PASSWORD=laravel
ENV TZ=Asia/Tokyo

COPY ./my.cnf /etc/my.cnf
RUN chmod 644 /etc/my.cnf