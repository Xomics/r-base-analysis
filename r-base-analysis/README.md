# Docker container for general analyses with R


## Pull Docker image
```{bash}
docker pull casperdevisser/r-base-analysis:v0.4 #latest
```

## Build Docker image 

```{bash}
# Dockerfile VERSION = v0.4
docker build --build-arg BUILD_DATE=$(date -u +'%Y-%m-%dT%H:%M:%SZ') -t casperdevisser/r-base-analysis:$VERSION . 
```