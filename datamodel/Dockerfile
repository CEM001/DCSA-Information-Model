FROM postgres:10-alpine
EXPOSE 5432
COPY initdb.d/* /docker-entrypoint-initdb.d/
COPY referencedata.d/* /referencedata.d/
