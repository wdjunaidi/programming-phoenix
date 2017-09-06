# Programming Phoenix

Repository for working through _Programming Phoenix_ book.

## Notes

There is postgres docker container for this book project.
Information for the docker container:
  - name: *phoenix-psql*
  - username: postgres
  - password: postgres
  - port: 5432

To connect to the postgres instant's psql:
  `docker run -it --rm --link phoenix-postgres:postgres postgres psql -h postgres -U postgres`
  
  
