FROM mysql:latest
COPY lekir.sql /docker-entrypoint-initdb.d/dump.sql
USER root
RUN chmod 755 /var/lib/mysql
