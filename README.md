# ds-environment

Commands:

* Building the Image
```docker
docker build -t diogosantiago/ds-environment
```

* Running a new container named **DS (Data Science)**

```docker
docker run -d -p 8888:8888 --name DS diogosantiago/ds-environment
```

* Run in your local browser localhost:8888
