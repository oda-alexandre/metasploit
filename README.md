# METASPLOIT

## INDEX

  - [METASPLOIT](#metasploit)
  - [INDEX](#index)
  - [BADGES](#badges)
  - [INTRODUCTION](#introduction)
  - [PREREQUISITES](#prerequisites)
  - [INSTALL](#install)
  - [LICENSE](#license)

## BADGES

[![pipeline status](https://gitlab.com/oda-alexandre/metasploit/badges/master/pipeline.svg)](https://gitlab.com/oda-alexandre/metasploit/commits/master)

## INTRODUCTION

Docker image of :

- [metasploit](https://www.metasploit.com)

Continuous integration on :

- [gitlab](https://gitlab.com/oda-alexandre/metasploit/pipelines)

Automatically updated on :

- [docker hub public](https://hub.docker.com/r/alexandreoda/metasploit)

## PREREQUISITES

Use [docker](https://www.docker.com)

## INSTALL

```docker run -ti --rm --name metasploit -v ${HOME}:/home/metasploit --network host alexandreoda/metasploit```

## LICENSE

[![GPLv3+](http://gplv3.fsf.org/gplv3-127x51.png)](https://gitlab.com/oda-alexandre/metasploit/blob/master/LICENSE)
