# Config for openwebui

## Start the app

Add env variables:

```bash
cp .env .env.sample
```

edit `HOST_PORT` to the port from which you want to access the ui. Start the service

```bash
docker compose up -d
```

## Stop the app

```bash
docker compose down
```

or stop the container from docker desktop dashboard.
