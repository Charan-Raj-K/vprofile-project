FROM mysql:8.0.33
LABEL "PROJECT"="VPROFILE"
LABEL "AUTHOR"="CHARAN"

ENV MYSQL_ROOT_PASSWORD="vproddbpass"
ENV MYSQL_DATABSE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
