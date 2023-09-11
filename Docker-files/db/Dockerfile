FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Satya"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQl_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql