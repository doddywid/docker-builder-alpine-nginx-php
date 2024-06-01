# **Docker Builder with Alpine-NGINX-PHP**

This repository is based on https://github.com/TrafeX/docker-php-nginx.
It is a docker image builder using
- Alpine 3.20 : small footprint
- Nginx Open Source : high performance web server
- PHP-FPM : running php

\
How to use
- Put website asset inside "src/" folder. The folder must be on the same folder with Dockerfile
- Run "docker build" command.
