# Django tutorial
## DB
```
docker run -p 5432:5432 --rm --name django-tutorial -v /home/tokens/PycharmProjects/mysite/postgres:/var/lib/postgresql/data -e POSTGRES_PASSWORD=mysecretpassword -d postgres:13
```