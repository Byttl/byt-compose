# Byt Compose

This docker-composer.yml file give you the possibility to run Byt behind a ssl proxy
It use let's encrypt and automatically renew the certificate

All credit goes to https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion for the let's encrypt container
And https://github.com/jwilder/nginx-proxy for the nginx proxy

## Setup

Replace the `/local` paths to your desired configuration and set your domain name.

```
docker-composer up -d
```

and that's all :)
