# ElasticSearch local setup-
https://www.elastic.co/guide/en/elasticsearch/reference/current/run-elasticsearch-locally.html

Tutorials-
https://reflectoring.io/spring-boot-elasticsearch/

PUT : http://localhost:9200/messages/_doc/1
{
  "message": "The Sky is blue today"
}

POST : http://localhost:9200/messages/_search
{
  "query": 
  {
  "match": {"message": "blue sky"}
  }
}


http://localhost:9200/_cat/indices?v
