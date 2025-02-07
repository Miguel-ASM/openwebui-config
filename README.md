# Config for openwebui

## Start the app

Add env variables:

```bash
cp .env .env.sample
```

edit `CUSTOM_SUBDOMAIN` in your .env file to the value you want. Start the service

```bash
docker compose up -d
```

To access the UI, go to `http://<CUSTOM_SUBDOMAIN>.localhost` in your browser.

## Stop the app

```bash
docker compose down
```

or stop the container from docker desktop dashboard.
