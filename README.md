## PHP(5.6, 7.4)
Dockernize PHP5.6 and PHP7.4 with MsSQL and Memcached

#### Folder structure
- docker
- web-56
- web-74 (Laravel)

#### Configuration
`/etc/hosts` (path depend on OS)
``` bash
127.0.0.1 host.docker.internal
```

#### Up
```
cd docker
docker-compose up -d --build
```

#### Down
```
cd docker
docker-compose down --rmi all --remove-orphans
```

#### Run
web-56: http://host.docker.internal:8000  
web-74: http://host.docker.internal:8001  
