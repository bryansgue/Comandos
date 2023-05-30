# Comandos

Comando para borrar todos los cambios no guardados en tu repositorio local y reemplazará su contenido con el último commit en la rama del repositorio remoto:

git fetch origin main && git reset --hard origin/main

Instalar Docker:
sudo docker build -t ml_casadi .

Acceder al contenedor Docker:
sudo docker exec -it bb1f32509950 /bin/bash

Si deseas ver tanto los contenedores en ejecución como los detenidos, puedes agregar la opción -a al comando:

docker ps -a

Adicional a la Docker de Patrick:

cd build
cmake -DACADOS_WITH_OPENMP=ON ..
make install -j4


