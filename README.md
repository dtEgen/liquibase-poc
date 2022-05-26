# liquibase-poc


- docker run --name postgres -p 5432:5432 --network egen -e POSTGRES_PASSWORD=postgres  -d  postgres 
- docker run --network egen --rm -v /Users/danie.ltchape/projects/sandbox/liquibase:/liquibase/changelog liquibase/liquibase --defaultsFile=./changelog/liquibase properties update
- https://www.liquibase.org/get-started/best-practices
