##   postgresql  docker image

https://hub.docker.com/r/brightcommerce/postgresql/




https://hub.docker.com/r/brightcommerce/postgresql/


```

docker run --name postgresql -p 5432:5432 -d brightcommerce/postgresql:latest


```


查看账户名和密码：
```
docker logs postgresql

```



##  另外一个镜像： 【CentOS官方镜像】
https://hub.docker.com/r/centos/postgresql-96-centos7/



```
docker pull centos/postgresql-96-centos7
```


docker run -d --name postgresql_database -e POSTGRESQL_USER=user -e POSTGRESQL_PASSWORD=pass -e POSTGRESQL_DATABASE=db -p 5432:5432 centos/postgresql-96-centos7

```


