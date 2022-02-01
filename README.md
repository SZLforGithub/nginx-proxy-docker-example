# nginx-proxy-docker-example

A simple example for [nginx-proxy/acme-companion](https://github.com/nginx-proxy/acme-companion).

## Usage

Change the DEFAULT_EMAIL in environment of docker-compose.yaml with your email.

To run it:

```
docker compose up -d
```

Then move to one of nginx folder:

```
cd nginx1
```

Before you run the test nginx container, you need to change VIRTUAL_HOST and LETSENCRYPT_HOST with your domain.

And finally run:

```
docker compose up -d
```
