### Usage
```
docker network create eureka-net
docker run --rm -it --net eureka-net -e EUREKA_PROVIDER_PORT=8800 -e EUREKA_SERVER_PEER_URL=http://192.168.1.10:8761/eureka -d yexianyi/eureka-provider
```

### Note:
1) EUREKA_PROVIDER_PORT: the exposed port for providing service
2) EUREKA_SERVER_PEER_URL：eureka registry url
