FROM postgres:9.6.5

WORKDIR /files

ADD https://raw.githubusercontent.com/vishnubob/wait-for-it/db049716e42767d39961e95dd9696103dca813f1/wait-for-it.sh ./wait-for-it.sh
RUN chmod a+x ./wait-for-it.sh

COPY ./importer/scripts/generate/blockImporterTables-beta.sql ./schema.sql
