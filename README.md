# ecocyc notebook

## Description
This app contains a neo4j server and a jupyter-notebook interface to a parsed version of [EcoCyc](https://ecocyc.org/). 

## Starting

See [docker-compose](https://docs.docker.com/compose/) for details. 

To run the first time, navigate to the folder (containing docker-compose.yml) and type:

    docker-compose up

Thereafter you can use 

    docker-compose start

Or

    docker-compose stop

Open your browser at the http://localhost:8888/?token=... link printed to the terminal. If the logs are not printed, run

    docker-compose logs 
 
to find the corrent link and token. 

For data persistence between images for the neo4j database, there is a volume on the host at `$HOME/neo4j/data`. 

### Usage

See example.ipynb as an example notebook to explore the graph. 
