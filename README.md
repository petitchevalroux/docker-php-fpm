# PHP-fpm in Docker
Available on:
* [docker hub](https://registry.hub.docker.com/u/petitchevalroux/php-fpm/)
* [github](https://github.com/petitchevalroux/docker-php-fpm)

## Quick start
* [Install docker](https://docs.docker.com/installation/)
* [Install fig](http://www.fig.sh/install.html)
* Clone this repository
```bash
git clone https://github.com/petitchevalroux/docker-php-fpm.git .
```
* Launch
```bash
fig up -d
```
* Find your docker host
```bash
echo $DOCKER_HOST
tcp://192.168.59.103:2376
```
* Open your browser at the following url: http://<host>:8080/index.php replacing <host> with value from $DOCKER_HOST. (In my case http://192.168.59.103:8080/index.php)


## About me
http://petitchevalroux.net