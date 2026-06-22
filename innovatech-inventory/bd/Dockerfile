FROM mysql:8.0

# Copiar los scripts de inicialización a la carpeta mágica de MySQL
COPY schema.sql /docker-entrypoint-initdb.d/1-schema.sql
COPY seed.sql /docker-entrypoint-initdb.d/2-seed.sql