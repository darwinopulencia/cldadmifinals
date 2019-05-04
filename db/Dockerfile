    
FROM mariadb:10.4

COPY darwincrud.sql /docker-entrypoint-initdb.d
ENV MYSQL_ROOT_PASSWORD =123

EXPOSE 3306
