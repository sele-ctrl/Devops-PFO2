## DevOps  PFO N°2
Despliegue de aplicaciones usando **Docker** y **Docker Compose**
la web es la creada previamente en back-end (Petshop - Huellitas Felices”)


## Comando para ejecutar por consola

docker compose up -d (iniciar)
///////////////////////////////////
docker ps
docker compose logs -f webapp
(estos hacen que veas el estado y logs)
///////////////////////////////////
docker compose down
(para deterlo)
///////////////////////////////////
docker compose down
docker compose up -d --build
(reiniciar por falla)

## Al iniciar el host es http://localhost:3000



