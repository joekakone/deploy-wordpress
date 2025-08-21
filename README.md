# Deploy Wordpress

## Launch containers
```sh
bash deploy
```

## Check containers
```sh
docker ps
```
```txt
CONTAINER ID   IMAGE               COMMAND                  CREATED          STATUS          PORTS                                     NAMES
0cabc7338984   wordpress:latest    "docker-entrypoint.s…"   27 minutes ago   Up 27 minutes   0.0.0.0:8000->80/tcp, [::]:8000->80/tcp   wordpress-1
0eab983202b4   mysql:latest        "docker-entrypoint.s…"   27 minutes ago   Up 27 minutes   3306/tcp, 33060/tcp                       wordpress-mysql-1
```
