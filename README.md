# Nextcloud on Kubernetes with Let's Encrypt

While reading the [Nextcloud README](https://github.com/nextcloud/docker/blob/master/README.md) this block jumpped out at me:

>In our [examples](https://github.com/nextcloud/docker/tree/master/.examples) section we have an example for a fully automated setup using a reverse proxy, a container for [Let's Encrypt](https://letsencrypt.org/) certificate handling, database and Nextcloud. It uses the popular [nginx-proxy](https://github.com/jwilder/nginx-proxy) and [docker-letsencrypt-nginx-proxy-companion](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion) containers. Please check the according documentations before using this setup.

This repo is me taking a stab a converting the example [docker-compose.yaml](https://github.com/nextcloud/docker/blob/master/.examples/docker-compose.yml) into something Kubernetes can use. To that end, the files in here were initially generated via Kompose per [this](https://kubernetes.io/docs/tools/kompose/user-guide/) guide on the Kubernetes site.

