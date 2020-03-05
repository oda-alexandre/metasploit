# METASPLOIT

![logo](https://assets.gitlab-static.net/uploads/-/system/project/avatar/16791371/metasploit.png=200x200)

## INDEX

- [METASPLOIT](#metasploit)
  - [INDEX](#index)
  - [BADGES](#badges)
  - [INTRODUCTION](#introduction)
  - [PREREQUISITES](#prerequisites)
  - [INSTALL](#install)
    - [DOCKER RUN](#docker-run)
    - [DOCKER COMPOSE](#docker-compose)
  - [LICENSE](#license)

## BADGES

[![pipeline status](https://gitlab.com/oda-alexandre/metasploit/badges/master/pipeline.svg)](https://gitlab.com/oda-alexandre/metasploit/commits/master)

## INTRODUCTION

Docker image of :

- [metasploit](https://www.metasploit.com)

Continuous integration on :

- [gitlab pipelines](https://gitlab.com/oda-alexandre/metasploit/pipelines)

Automatically updated on :

- [docker hub public](https://hub.docker.com/r/alexandreoda/metasploit)

## PREREQUISITES

Use [docker](https://www.docker.com)

## INSTALL

### DOCKER RUN

```docker run -ti --rm --name metasploit -v ${HOME}:/home/metasploit --network host alexandreoda/metasploit
```

### DOCKER COMPOSE

```yml
version: "3.7"

services:
  metasploit:
    container_name: metasploit
    image: alexandreoda/metasploit
    restart: no
    network_mode: host
    privileged: false
    volumes:
      - "${HOME}:/home/metasploit"
```

## LICENSE

[![GPLv3+](http://gplv3.fsf.org/gplv3-127x51.png)](https://gitlab.com/oda-alexandre/metasploit/blob/master/LICENSE)
