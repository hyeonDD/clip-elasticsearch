# command

docker network create

```sh
docker network create clip_multimodal
```

image build

```sh
$ docker build -t clip_elasticsearch .
```

container run

```sh
$ docker run -d --name clip_elasticsearch --net clip_multimodal -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" clip_elasticsearch
```

login user, password

| name     | value    |
| -------- | -------- |
| user     | elastic  |
| password | changeme |
