# command

docker network create

image build

```sh
$ docker build -t clip_kibana .
```

container run

```sh
$ docker run -d --name clip_kibana --link clip_elasticsearch:elasticsearch -p 5601:5601 clip_kibana
```
