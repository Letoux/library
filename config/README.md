Pour lancer la BDD postgres sur docker:

```sh
docker run --name postgres \                                                                                                                                                                  ─╯
  -e POSTGRES_DB=database \
  -e POSTGRES_USER=user \
  -e POSTGRES_PASSWORD=password \
  -p 5432:5432 \
  -d postgres
```