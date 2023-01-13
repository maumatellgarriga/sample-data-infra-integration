FROM postgres:11-alpine

ENV POSTGRES_PASSWORD="default_password"
COPY restaurants.sql /restaurants.sql
CMD PGPASSWORD=$POSTGRES_PASSWORD psql -h postgreSQL -d postgres -U postgres -f restaurants.sql
