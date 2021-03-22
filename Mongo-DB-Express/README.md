# Mongo DB using Mongo Express for local development
This simple docker compose example shows, how to setup a mongo db instance for local development using also the mongo express as a UI. The usage of the environemtns, ports, etc. for the services is documentent on http://hub-docker.com. Furthermore the data will be stored as a named volume for don't lose the data during the development.


## Validate yaml with docker-compose config
Before running and setting up the docker-compose, it is possible to validate the yaml file like follows:

docker-compose -f fileName.yaml config


## Run yaml with docker-compose up
After validating the yaml file was successful, the docker command for execute the docker-compose command like follows:

docker-compose -f fileName.yaml up


## Using mongo-db and mongo-express
After running the docker-compose command successfully, the results appear in the terminal. The UI can be reached under http://localhost:8081