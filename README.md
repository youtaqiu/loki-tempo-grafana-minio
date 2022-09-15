# loki-tempo-grafana-minio
loki tempo grafana minio

### 1.创建grafana目录并赋权
```shell
mkdir -p grafana/data &&  sudo chown 472:472 grafana/data  && sudo chown 1000:1000 grafana/data
```
### 2.启动服务
```shell
docker-compose up -d
```

### 3.打开Grafana控制台

```http
http://localhost:3001
```