![image](https://user-images.githubusercontent.com/1423657/30296932-37f27d82-9746-11e7-8049-10ccac3d4994.png)

# Elasticsearch on Steroids!
Water & Soap Docker container providing a ready to use FOSS Elastic stack:

* Kibi 5.4.x 
* Elasticsearch 5.4.x
* Sentinl Alerts 5.4.x
* ReadOnlyREST Auth 5.4.x

##### Run
```
docker run -d -p 9200:9200 -p 5606:5606 -e ES_USER=admin -e ES_PASS=password qxip/docker-kibi-steroids
```

![image](https://user-images.githubusercontent.com/1423657/30291894-87e5059c-9734-11e7-957c-314af6c2ece9.png)
