# MA Service UI

## Pull
```
docker pull --platform linux/amd64 node:lts-buster-slim
```

## Build
```
docker build --platform linux/amd64 -t dgbtechnologies/bowtie-analysis-ui:latest . --no-cache
```

## Push
```
docker push dgbtechnologies/bowtie-analysis-ui:latest
```