create astro project
```
bunx create-astro@latest docker_astro
```

deploy container
```
ENVIROMENT=dev docker compose up --build --force-recreate
docker compose up --build --force-recreate
```