# web-template
网站基础架构



## 依赖

### grpc

```sh
# 1. 安装依赖
pip install grpcio grpcio-tools
# 2. 编写proto文件 
# 3. 生成代码
python -m grpc_tools.protoc -I /dir/to/proto/ --grpc_python_out=. --python_python_out=. hello.proto
# 4. 实现服务端接口 
# 5. 部署

```

### docker


### kafka

```sh
cd docker/kafka/docker-compose.yml
sudo docker-compose up -d
```

### zookeeper 

```sh
docker run --name some-zookeeper --restart always -d zookeeper
```

