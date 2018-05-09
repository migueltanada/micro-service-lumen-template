# micro-service-lumen-template

### Steps to use

- Install docker-compose 
```bash
curl -L https://github.com/docker/compose/releases/download/1.21.0/docker-compose-$(uname -s)-$(uname -m) -o /usr/bin/docker-compose
chmod +x /usr/bin/docker-compose
```
- Go inside root folder of source code ``cd micro``
- Clone Repository ``git clone https://github.com/migueltanada/micro-service-lumen-template.git``
- Move docker templates ``mv micro-service-lumen-template/Dockerfile micro-service-lumen-template/docker-compose.yml .``
- Move index.php (Only if you don't have an existing index.php) ``mv micro-service-lumen-template/index.php .``
- Remove template folder `` rm -rf micro-service-lumen-template``
- Start your container! ``docker-compose up -d``

*the contents of index.php only points to your server.php*
