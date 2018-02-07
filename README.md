# docker-mysql-ja_JP

This repository contains Dockerfile for [mysql](https://hub.docker.com/_/mysql/) ja_JP.

## Install

As a prerequisite, you need [Docker](https://docker.com) to be installed.

To download this image from the public docker hub:

	$ docker pull smapira/docker-mysql-ja_jp

To re-build this image from the dockerfile:

	$ docker build -t docker-mysql-ja_jp .

## Usage

To run:

	$ docker run -d --name mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -e TZ=Asia/Tokyo smapira/docker-mysql-ja_jp

To login:

	$ docker exec -it mysql mysql -uroot -p

## Super Thanks
- [最速で日本語環境のMySQL Dockerコンテナを建てる方法](https://qiita.com/muff1225/items/48e0753e7b745ec3ecbd)

