This is an example of a containerized a full stack nodejs application in docker

Requirement
---------------
Docker must be installed on your PC

To implement
-------------
Download the docker-compose.yml file and run. You can use -d flag to run in background
> docker-compose up

- Tear down
> docker-compose down

- To re-build, remove the "image:" configuration for the app service and add this "build: ./app" config
> docker-compose build

- To be able to edit files for a dev environment, update the volume configuration of the compose file
  + volumes: ./:/usr/src/app


