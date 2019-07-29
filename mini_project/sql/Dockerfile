FROM mysql
ENV MYSQL_ROOT_PASSWORD docker
ENV MYSQL_DATABASE country_club
COPY country_club.sql /docker-entrypoint-initdb.d/
