# exchangelapaz-web

Prototipo estático del sitio de Exchange La Paz (HTML/CSS), servido con nginx en Docker.

Local: `docker build -t exchangelapaz-web . && docker run --rm -p 8080:80 exchangelapaz-web` y abre http://localhost:8080

Dokploy: aplicación desde GitHub, build type Dockerfile, puerto 80.
