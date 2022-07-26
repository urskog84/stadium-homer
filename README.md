Singe Docker command

``` powershell
docker run --rm -p 8080:8080 $(docker build . -q)
```

Docker-compise command

``` powershell
docker-compose up --build
```