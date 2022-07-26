Clone

``` powershell
git clone git@github.com:urskog84/stadium-homer.git

cd stadium-homer
```
Singe Docker command

``` powershell
docker run --rm -p 8080:8080 --name homer $(docker build . -q)
```

Docker-compise command

``` powershell
docker-compose up --build
```