# docker-nginx

[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://orleika.github.io/mit-license)
[![Build Status](https://img.shields.io/travis/orleika/docker-nginx/master.svg?style=flat-square)](https://travis-ci.org/orleika/docker-nginx)
[![nginx](http://img.shields.io/badge/nginx-v1.11.9-blue.svg?style=flat-square)](https://nginx.org/en/download.html)
[![LibreSSL](http://img.shields.io/badge/LibreSSL-v2.5.1-blue.svg?style=flat-square)](https://www.libressl.org/)
[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

> nginx docker image

Small-Secure-Fast nginx docker image.  
Base image is alpine, which is a security-oriented, lightweight Linux distribution.  
Most response headers are concealed, and DDoS mitigation is equipped.
You should use secure headers included in `conf.d` for further safety considerations.  
Additionally, nginx caching parameters are optimized.

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [Contribute](#contribute)
- [License](#license)

## Install

```sh
$ docker pull orleika/nginx
```

## Usage

```sh
$ docker run -d -p 80:80 orleika/nginx
```

## Contribute

PRs accepted.

## License

MIT © orleika
