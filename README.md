
## docker-compose启动
~~~
# 单机
docker-compose up -d && docker-compose logs -f

# 集群
docker-compose -f cluster.yml up -d
~~~
