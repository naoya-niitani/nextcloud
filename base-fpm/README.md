## 概要
nextcloud ファイルサーバ

## 構成
| server | image |
| -- | -- |
| office | [`libreoffice/online`](https://hub.docker.com/r/libreoffice/online) |
| db | [`mariadb`](https://hub.docker.com/_/mariadb) |
| session storage | [`redis`](https://hub.docker.com/_/mariadb) |
| app | [`nextcloud:fpm`](https://hub.docker.com/layers/library/nextcloud/fpm/images/sha256-d97ae5124564943ccaac2281006f0d314787115d954b7a4bd67c3bca46a6e13f?context=explore) |
| web | [`nginx`](https://hub.docker.com/_/nginx) |
| cron | [`nextcloud:fpm`](https://hub.docker.com/layers/library/nextcloud/fpm/images/sha256-d97ae5124564943ccaac2281006f0d314787115d954b7a4bd67c3bca46a6e13f?context=explore) |


## 参考
- https://hub.docker.com/r/libreoffice/online
- https://github.com/smehrbrodt/nextcloud-libreoffice-online
- https://github.com/nextcloud/docker
- https://github.com/Zegorax/docker-libreoffice-online
