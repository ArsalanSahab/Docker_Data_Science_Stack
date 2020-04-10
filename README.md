# Docker_Data_Science_Stack
A Docker Data Science Workflow Stack

## Note : Must Have Docker Installed for Linux , and Docker Desktop for MacOS/Windows

### Defaults

By default the password and secret keys are set to : `root` and user is `admin`.

## How to Run

1. Clone this repository onto your machine .
2. Using commandprompt/terminal navigate to the downloaded repo.
3. Run the command : `docker-compose build apistar` to build the APIStar Image.
4. After the above , run the command : `docker-compose up` , alternatively you can use `docker-compose -d up` to run in background.


### What Services You will Have :

1. Jupyter for Data Manipulation and Exploration.
2. SuperSet for Data Visualisation.
3. Minio for Non-Relational Object Data Storage , which is also Amazon S3 compatible.
4. PostgreSQL for Database , with persistent storage.
5. APIStar for api related queries.
6. Airflow for Task Scheduling.
7. Portriner for administring docker images on ports.



## Service - Port Mappings
| Service | Port |
| --- | --- |
| Airflow | 8080 |
| Apistar | 8000 |
| Jupyter | 8888 |
| Minio | 9000 |
| Portainer | 9090 |
| Postgres | 5432 |
| Superset | 8088 |
