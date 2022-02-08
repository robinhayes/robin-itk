## Get Started

Build using `docker-compose up`.

**PostgreSQL**   
Log in using `docker exec -it itk-postgres psql -U robin -d itk` once it's running. You can interactively run queries from here.

**Grafana**

Go to `http://localhost/3000` to log-in. The username is `admin` and the password is `password`. You can add the postgres database created in the other container as you would another data source. Pass the database credentials from the `docker-compose` file and use `itk-postgres:5432` as the host.

## Restart From Scratch

To rebuild everything from scratch and start again, you need to remove the containers and the volumes.
