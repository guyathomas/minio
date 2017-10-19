#Minio Server

This is a Minio server for the Bluxomous host.

The base dockerfile will spin up 4 servers locally for testing, and using docker swarm, the `docker-compose-prod.yml` file will run on nodes with the label `arch = arm`