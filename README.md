# json-examples

This repo contains an example configuration setup. It uses dashbase's demo nginx data and repeatedly indexing them. 

To try the example, git clone this repo, cd to its directory, then run dashbase-compose start. It will start a node, an API server, system metrics server, and web-ui (from localhost:8080). Zookeeper need to be running on localhost:2181.

The logs and indices will be generate in the logs/ and index/ subdirectory.

