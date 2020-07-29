# Docker 应用示例

### 项目说明
用于 Docker 单机版的一些应用示例。

### 克隆代码
```
git clone https://github.com/ztj1993/docker-example.git
```

### 部署之前
项目要求有一个名字为 `custom` 的网络，建议执行下面的代码创建网络。

```
docker network create --subnet=172.25.0.0/16 custom
```
