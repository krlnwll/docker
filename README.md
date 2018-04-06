dockcer-apache-php5.6
===================================

A Docker image based on Ubuntu 14.04, serving PHP 5.6 running as Apache Module. Useful for Web developers in need for a fixed PHP version.

Usage
------

```
$ docker run -d -P krlnwll/dockcer-apache-php5.6
```

With all the options:

```bash
$ docker run -d -p 8080:80 \
    -v /home/user/webroot:/var/www \
    krlnwll/dockcer-apache-php5.6
```

* `-v [local path]:/var/www` maps the container's webroot to a local path
* `-p [local port]:80` maps a local port to the container's HTTP port 80
