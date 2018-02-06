# ecocyc notebook

## Description

This app contains a neo4j server and a Jupyter-notebook interface to a parsed version of [EcoCyc](https://ecocyc.org/). 

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
 
to find the correct link. 

### Usage

See `examples/example.ipynb` as an example notebook to explore the graph. You should be able to run the cells immediately. 

### To do list

* ... 
