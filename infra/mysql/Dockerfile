FROM mysql/mysql-server:8.0

ENV MYSQL_DATABASE=test-laravel \
  MYSQL_USER=laravel \
  MYSQL_PASSWORD=password5241 \
  MYSQL_ROOT_PASSWORD=password5241 \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/my.cnf
RUN chmod 644 /etc/my.cnf