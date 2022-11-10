# Study.Poetry-FastAPI-Docker

## init poetry

```
poetry init
```

## install fast api

```
poetry add "fastapi[all]"
```

## export package for dockerfile

```
poetry export --without-hashes --format=requirements.txt > requirements.txt
```

## docker build

```
docker build . -t "my-first-fastapi-app"
```

## docker images

```
docker images
```

## docker run

```
docker run -p 8000:8000 my-first-fastapi-app
```