# webdev-training-d2

## Responsive Images

https://github.com/ThetHlaing/padc7-foundation-ltc-day1/blob/answer/6.%20Images/index.html

## Docker

https://docs.docker.com/get-started/

https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-18-04

https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615


```
docker ps -a
```



## Elastic Search

https://www.tutorialspoint.com/elasticsearch/elasticsearch_query_dsl.htm

### Installation 

https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html

```
docker pull docker.elastic.co/elasticsearch/elasticsearch:7.3.1
```

```
docker run -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" docker.elastic.co/elasticsearch/elasticsearch:7.3.1
```

```
docker image ls
```



### Setup in Laravel with scout-elasticsearch component

```
composer require babenkoivan/scout-elasticsearch-driver
```

https://github.com/babenkoivan/scout-elasticsearch-driver#installation

```
php artisan scout:import "App\Post"
```


### Python Automation

https://github.com/ThetHlaing/padc7-foundation-day16



