# Docker Files - Pingr

Repository to hold docker compose files needed to run all the services containers simultaneously while developing

## Running

To start the services, run the following commands:

```bash
$> docker-compose build
```
Then, run on all the containers:
```bash
$> docker-compose run --rm [container_name] yarn install
```

And up the containers:
```bash
$> docker-compose up
```
