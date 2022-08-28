# Dockerized minimal php-fpm + nginx app

Pretty simple starting point to make some prototype or small pet-project.

1. Drop or create your project in `./app` directory
2. Take a closer look on `docker-compose.yml` and [config](./docker) files, so feel free to use this environment as you want.
3. Run containers:
    ```
    $ docker compose up --build
    ```
4. Go to [http://localhost:8080](http://localhost:8080)

To use xdebug you should listen to port 9003 in your IDE.

[WTFPLv2](LICENSE)
