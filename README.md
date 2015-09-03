nature-demo
===========

Materials for the [November 2014 Nature Article](http://www.nature.com/news/interactive-notebooks-sharing-the-code-1.16261)

### Running the Docker image

```
docker run -it -p 8888:8888 jupyter/nature-demo
```

### Building the Docker images

```
docker build -t jupyter/nature-base base
docker build -t jupyter/nature-demo .
```
