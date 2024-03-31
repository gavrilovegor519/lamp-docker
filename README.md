# LAMP-Docker

The LAMP kit for Docker.

## Run

1. Add this code to the `~/.bashrc` file:

    ```shell
    export UID=$(id -u) 
    export GID=$(id -g)
    ```

2. Restart the Bash terminal

3. Run the LAMP:

    ```shell
    docker compose up -d
    ```

## Stop

```shell
docker compose down
```

Or:

```shell
docker compose down --volumes
```
