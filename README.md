# Label studio - Digital Ocean

Project that houses the walkthrough on how to put labelstudio.io instance to a digital ocean droplet (or any other VM with another provider).

# Labelstudio

The labeling framework is open sourced by https://labelstud.io/. 

Official docker image: https://hub.docker.com/r/heartexlabs/label-studio

All the needed services are run using docker containers. The configuration of the containers are in the `docker-compose.yml` file. 

The official github page can be found via: https://github.com/heartexlabs/label-studio 

# Using docker 

The docker containers are run using the `docker-compose` command. The configurations are in the `docker-compose.yml` file. 

The environmental variables for labelstudio are defined in `label.env` file. 

The environment variables for psql are defined in the `psql.env` file. 

The example structures are present in the `label-example.env` and `psql-example.env` files.

To run the application in a detached mode use the command: 

```
docker-compose up -d
```