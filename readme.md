# About

	基于 docker 的 web 开发环境


# 使用


	1. cp env-example .env

	2. 修改宿主机代码路径及容器前缀

	3. 启动：docker-compose up -d

	4. 关闭：docker-compose down

	5. 启动/关闭/重启服务：docker-compose start|stop|restart nginx|php|mysql|redis


# 软件

	- nginx：1.19.2

	- mysql：5.7.13

	- redis：6.0.7

	- php：7.3-fpm-alpine

	- swoole：4.5.3

# php 扩展


	/var/www/html # php -m
	[PHP Modules]
	bcmath
	Core
	ctype
	curl
	date
	dom
	fileinfo
	filter
	ftp
	gd
	hash
	iconv
	json
	libxml
	mbstring
	mcrypt
	mongodb
	mysqli
	mysqlnd
	openssl
	pcre
	PDO
	pdo_mysql
	pdo_sqlite
	Phar
	posix
	rdkafka
	readline
	redis
	Reflection
	session
	SimpleXML
	sockets
	sodium
	SPL
	sqlite3
	standard
	swoole
	tokenizer
	xml
	xmlreader
	xmlwriter
	Zend OPcache
	zip
	zlib

	[Zend Modules]
	Zend OPcache

