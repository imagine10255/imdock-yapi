# Usage

- env：
	- Hardware requirements：`1 GB RAM minimum`
	- work path：`mkdir -p /opt/git-data`
	- ip：`http://192.168.1.121`
- clone：
	- `cd /opt/git-data && git clone https://github.com/branchzero/yapi-docker.git`
- permission：
	- `chmod -R 777 /opt/git-data`
- run command：
	- `docker-compose up -d`
- open chrome：
	- `http://192.168.1.121:3000`



## How to and other docker-compose use the same network :

```
#if you not have group network, you can create this, and other docker-compose use this network setting
~ $ docker network create --driver bridge imdockgroup
```
