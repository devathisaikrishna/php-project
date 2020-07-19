FROM mysql:latest
VOLUME ./online-shopping-system/database/onlineshop.sql:/docker-entrypoint-initdb.d/onlineshop.sql
ENV  MYSQL_ROOT_PASSWORD: root MYSQL_DATABASE: database MYSQL_USER: edureka MYSQL_PASSWORD: admin
EXPOSE 3306
