# neo4j-docker

A docker-compose file and configuration for running neo4j.

Installation:

1. clone this repo
2. install the [Neo4J GDS plugin](https://neo4j.com/docs/graph-data-science/current/installation/neo4j-server/):
   1. `mkdir neo4j_plugins/`
   2. `wget https://graphdatascience.ninja/neo4j-graph-data-science-2.3.2.zip`
   3. `unzip neo4j-graph-data-science-2.3.2.zip`
   4. `mv neo4j-graph-data-science-2.3.2.zip neo4j_plugins/`
3. start with `docker-compose start`
4. you will need to change the default password on the first start

See also: the [Neo4J docker documentation](https://neo4j.com/docs/operations-manual/current/docker/)
