# Devops delivery pipeline ElasticSearch docker image

## Run from dockerhub image
```
sudo docker run --name=box-elastic -p 9200:9200 -v /etc/hosts:/etc/hosts -it -d devopsru/training-elastic-image
```


## Build and run
```
sudo docker build -t elasticsearch .
sudo docker run --name=box-elastic -p 9200:9200 -v /etc/hosts:/etc/hosts -it -d elasticsearch
```

