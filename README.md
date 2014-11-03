# Apache Docker

This image simply provides an up-to-date ubuntu 14.04 install with apache working on port 80.

## Config

You should mount your files via a volume or a wrapper Dockerfile to `/var/www/html`

## To Run:

```
docker run -d -p 80:80 -v /path/to/html:/var/www/html mikesplain/apache
```
