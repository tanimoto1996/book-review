FROM mysql/mysql-server:5.7

ENV MYSQL_DATABASE=books \
  MYSQL_USER=tanimoto \
  MYSQL_PASSWORD=kakaka \
  MYSQL_ROOT_PASSWORD=kakaka \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/my.cnf
RUN chmod 644 /etc/my.cnf