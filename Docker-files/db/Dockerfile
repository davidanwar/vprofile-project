FROM mysql:8.0.34
LABEL "Project"="Vprofile"
LABEL "Author"="David"

ENV MYSQL_ROOT_PASSWORD="d4v1d4nw4r"
ENV MYSQL_DATABASE="accounts"


ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql