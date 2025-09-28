# bigdata-dock

基于 Docker Compose 搭建的大数据服务环境

# IP地址
内部IP地址从 172.25.27.3 开始

### ELK (172.21.3.60) [待定]
| service | backend ip | frontend ip | version | 备注 |
|---|---|---|---|---|
| es-init | 172.21.3.60 | 172.20.3.60 | latest |
| es | 172.21.3.61 | 172.20.3.61 | latest |
| kibana | 172.21.3.62 | 172.20.3.62 | latest |
| logstash | 172.21.3.63 | 172.20.3.63 | latest |
| elk-box | 172.21.3.64 | 172.20.3.64 | latest |
| filebeat | 172.21.3.65 | 172.20.3.65 | latest |
| go-stash | 172.21.3.66 | 172.20.3.66 | latest |


# 使用到的镜像
- 默认使用docker.io 镜像
- 若想使用自定义仓库镜像，需要定义 `DOCKER_REGISTRY_URL` 变量

```json
[
    "traefik:v3.4",
]
```
