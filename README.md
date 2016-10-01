# docker-buildkube

docker image for [buildkite agent](https://github.com/buildkite/docker-buildkite-agent) and [kubernetes](http://kubernetes.io/docs)

## how to

### install

install `docker`, then

```shell
git clone https://github.com/ahdinosaur/docker-buildkube
```

### build

```shell
docker build -t ahdinosaur/buildkube .
```

### run

```shell
docker run -i -t ahdinosaur/buildkube --start help
```

### publish

```shell
docker push ahdinosaur/buildkube
```
