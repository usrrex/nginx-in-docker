# Debian+Nginx
This repository contains __Dockerfile__ of [Nginx](https://nginx.org) and [Debian](https://www.debian.org).
## Base Docker Image
- [debian](https://hub.docker.com/_/debian)
## Instalation
1. Install [Docker](https://www.docker.org)
2. Download this dockerfile
3. Build image:
   ```
   docker build -t="rexvitaminoff/test:v6" github.com/usrrex/nginx-in-docker
   ```
   ## Usage
   ```
   docker run -d -p 80:80 rexvitaminoff/test:v6
   ```
   After few seconds, open http://<host> to see the welcome page.
