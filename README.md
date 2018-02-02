# ecocyc notebook

This app contains a neo4j server and a jupyter-notebook interface. 
To run the first time, navigate to the folder and type:

   docker-compose up

Thereafter you can use 

   docker-compose start

Or

   docker-compose stop

See docker-compose for details. 

There is a volume on the host at `$HOME/neo4j/data`

example.ipynb is an example notebook to explore the graph. 
