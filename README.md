# Docker Nginx Image _(docker-nginx)_

[![Build Status](https://img.shields.io/travis/orleika/docker-nginx/master.svg?style=flat-square)](https://travis-ci.org/orleika/docker-nginx)
[![nginx](http://img.shields.io/badge/nginx-v1.11.12-blue.svg?style=flat-square)](https://nginx.org/en/download.html)
[![LibreSSL](http://img.shields.io/badge/LibreSSL-v2.5.1-blue.svg?style=flat-square)](https://www.libressl.org/)
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://orleika.github.io/mit-license)

> docker nginx image

Small-Secure-Fast docker nginx image.  
Base image is alpine, which is a security-oriented, lightweight Linux distribution. Most response headers are concealed, and DDoS mitigation is equipped. You should use secure headers included in `conf.d` for further safety considerations. Additionally, nginx caching parameters are optimized.  
This image is automatically released by Docker Cloud.

## Install

This project uses [docker](https://docs.docker.com). Go check them out if you don't have them locally installed.

```sh
$ docker pull orleika/nginx
```

## Usage

```sh
$ docker run -d -p 80:80 orleika/nginx
```

## Contribute

Please open [issues](https://github.com/orleika/docker-nginx/issues/new) or submit Pull requests to report bugs, features, or other problems.  
Please note that this project is released with a Contributor Code of Conduct. By participating in this project you agree to abide by its terms.

## License

[MIT © orleika](LICENSE)
