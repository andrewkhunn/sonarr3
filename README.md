### [Sonarr3](https://github.com/Sonarr/Sonarr)

```shell
docker run --rm --name sonarr3 -p 8989:8989 -v /tmp/sonarr3:/config hotio/sonarr3
```

```yaml
sonarr3:
  container_name: sonarr3
  image: hotio/sonarr3
  ports:
    - "8989:8989"
  volumes:
    - /tmp/sonarr3:/config
```

```shell
VERSION=image
VERSION=stable
VERSION=unstable
VERSION=https://download.sonarr.tv/v3/phantom-develop/3.0.1.371/Sonarr.phantom-develop.3.0.1.371.linux.tar.gz
VERSION=file:///config/Sonarr.phantom-develop.3.0.1.371.linux.tar.gz
```
