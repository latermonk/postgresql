##postgresql  docker image

https://hub.docker.com/r/brightcommerce/postgresql/




https://hub.docker.com/r/brightcommerce/postgresql/


```

docker run --name postgresql -p 5432:5432 -d brightcommerce/postgresql:latest


```


```
docker logs postgresql

```

|------------------------------------------------------------------|
| PostgreSQL User: postgres, Password: xxxxxxxxxxxxxx              |
|                                                                  |
| To remove the PostgreSQL login credentials from the logs, please |
| make a note of password and then delete the file pwfile          |
| from the data store.                                             |
|------------------------------------------------------------------|


