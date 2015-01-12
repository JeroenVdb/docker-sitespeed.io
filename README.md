docker-sitespeed.io
===================
This [Docker](https://www.docker.com/) tries to encapsulate all functionalities of [Sitespeed.io](http://www.sitespeed.io/).

### Usage

Test url and save the report to your host
````
docker run --rm -v "$(pwd)":/sitespeed.io jeroenvdb/docker-sitespeed.io sitespeed.io --url http://httpbin.org/
````
Replace `http://httpbin.org/` with the url of your choice. It will save the report in your current working directory and delete the Docker container once done.


Test url and send data to Graphite server
````
todo
````

Test url and send data to Graphite server, hosted in another Docker
````
todo
````

### Build
```
docker build -t="jeroenvdb/sitespeed:dev" .
```
