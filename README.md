# elk-docker-compose
ELK Dcoker Compose Version 7.6.0

### Requirements
Docker Desktop 
Windows 10

#### Clone Git
`git clone https://github.com/mzubairsaleem/elk-docker-compose.git elk`

#### Change Directory To ELK
`cd elk`

#### Start Docker Conatiners
`docker-compose up -d --build`

#### Restart Docker Containers
`docker-compose restart`

#### Stop Docker Containers
`docker-compose stop`


## Configs

##### Elasticsearch Configurtations File
`./elk/elasticsearch/config/elasticsearch.yml`

##### Kibana Configurtations File
`./elk/kibana/config/kibana.yml`

##### Logstash Configurtations File
`./elk/logstash/config/logstash.yml`
##### Logstash Pipelines
`./elk/logstash/pipeline/logstash.conf`