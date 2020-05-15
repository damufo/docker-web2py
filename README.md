


# About this repo
The repo contains the Docker image for the [web2py](http://www.web2py.com/) web framework.

Forked from: https://github.com/TheHipbot/docker-web2py
Updated ubuntu version from 14.04 (Trusty) to 16.04 (Xenial)

# Build
$ docker build -t damufo/web2py-py27:latest . 

# Run
$ docker run -d -p 443:443 -p 84:80 damufo/web2py-py27:latest

Site: http://0.0.0.0:84/
Admin site: https://0.0.0.0/admin/
Admin pasword: admin

