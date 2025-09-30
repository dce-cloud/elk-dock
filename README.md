# elk-dock

基于 Docker Compose 搭建的ELK服务环境

# IP地址

内部IP地址从 172.25.33.3 开始

### ELK (172.25.33.3)
| service | backend ip | version | 备注 |
|---|---|---|---|
| es-init | 172.25.33.3 | latest |
| es | 172.25.33.4 | latest |
| kibana | 172.25.33.5 | latest |
| logstash | 172.25.33.6 | latest |
| elk-box | 172.25.33.7 | latest |
| filebeat | 172.25.33.8 | latest |
| go-stash | 172.25.33.9 | latest |


# 使用到的镜像
```json
[
]
```
