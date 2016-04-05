# Devops delivery pipeline ElasticSearch docker image

```
sudo docker build -t elasticsearch .
sudo docker run --name=box-elastic -p 9200:9200 -v /etc/hosts:/etc/hosts -it -d elasticsearch
```

