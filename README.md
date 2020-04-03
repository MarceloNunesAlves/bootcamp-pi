# bootcamp-pi


### Travis:

https://travis-ci.org/github/tentativafc/bootcamp-pi

### Comandos úteis

Build da imagem de teste

```sh
docker build -t tentativafc/bootcamp-pi-test -f ./Dockerfile.dev .
```

Rodar a imagem de teste

```sh
docker run tentativafc/bootcamp-pi-test pytest
```

```sh
docker build -t tentativafc/bootcamp-pi .
```

```sh
docker run -p 5000:5000 tentativafc/bootcamp-pi
```


