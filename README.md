# Bitacora-comandos

ip addr / Ver datos de la red

ping 8.8.8.8 /  Hacer ping para ver latencia de red

sudo /  dar permisos de administrador

sudo apt update / actualiza todos los repositorios

sudo apt upgrade / instalar las actualizaciones 

sudo apt install neofetch / Instala programa que permite ver informacion de hardware y software

apt / es para descargar paquetes

dpkg / sirve para instalar paquetes en terminal

cd  / moverse a un directorio

install / instala los paquetes

ls  muestra lista de archivos

exit / salir

pwd / para imprime direcorio de trabajo

man / muestra el manual de un programa

whoami / muestra el usuario

sudo su / usuario root
su root / usuario root

cat / concatenar archivos

cat /etc/passwd / ver los usuarios y sus datos

useradd / crea cuentas de usuario

free -h / leer memoria disponible

df -h / Ver detalles de directorios

du -h archivo.png / ver tamaño de archivo

stat archivo.png / informacion sobre archivo

file archivo.png / ver tipo de archivo

nano / editor de texto
vim / editor de texto

clear / limpiar terminal

apt search / busca posibles comandos

grep / buscar archivo
find / buscar archivo

chmod 777 archivo.png / dar permisos

kill -9 $PID / Matar procesos 

touch / Crea archivos

echo / imprimir

chmod +x script.sh / permisos para ejecutar scripts

sudo passwd [usuario] / Establecer contraseñas 

cat more less / muestra contenido de archivo

history / ver el historial

sudo snap install [programa] / instalar programa 

sudo apachectl start / inicia apache

swapon / muestra donde esta el archivo de swap

cat/proc/sys/vm/swappiness / indica swappiness en la computadora

df -h / muestra los discos duros conectados.

sudo mount / montar datos dispositivos

sudo mkdir /mnt/ram_disk / montar disco RAM
sudo mount -t tmpfs -o size=1024m new_ram_disk /mnt/ram_disk / montar disco RAM
  
chmod / Cambia los permisos de las carpetas

chmod + / lee, escribe y ejecuta

chmod -x / quitar los permiso de ejecucción

ls -l / muestra la lista de los permiso de los archivos

du -h /  Tamaño del arhivo

stat / Fecha de creacion

touch / actualiza la hora de la fecha de modificacion

chwon / Tomar posesion de un archivo

file / muestra el formato de un archivo

Gparted / Admnistrar las partes del disco duro del sistema

ps -aux / Para ver todos los Ids de los programas o los procesos

curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add - / agregar la clave GPG oficial de Docker

sudo add-apt-repository "deb [arch=amd64]https://download.docker.com/linux/ubuntu bionic stable" / agregar el repositorio oficial de Docker

sudo apt-get install docker-ce docker-ce-cli containerd.io / instalar docker

sudo usermod -aG docker ${USER} / usar Docker sin sudo

sudo docker run hello-world / validar funcionamiento docker

sudo systemctl start docker  /  iniciar el Daemon
sudo systemctl enable docker / iniciar el Daemon

docker search ubuntu / buscar imagenes

sudo docker images / ver imagenes instaladas

docker stop container-id / detener un contenedor

docker start container-id / iniciar contenedor

 sudo docker login -u USUARIODOCKERHUB / iniciar sesión en la terminal con el usuario de docker hub
 
 sudo docker push docker-registry-username/docker-image-name / hacer push a la cuenta de DockerHub
 
docker rmi Image Image / eliminar imagen

docker rm ID ID / eliminar contenedores

docker run --rm image_name / eliminar contenedores despues de cerrados

sudo docker rm $(sudo docker ps -a -f status=exited -q) /  Eliminar todos los contenedores con estado “Exited (0)”

sudo docker info / ver datos de docker 

sudo docker images / ver imagenes descargadas 

sudo docker pull ubuntu:latest / descargar version de ubuntu mas actual

docker run [images name] / para correr imagenes

-a docker ps docker ps -a / ver los contenedores que esten UP, incluso los que ya se terminaron de ejecutar 

docker run -d (contenedor) / correr comandos de fondo

 run --name (nombre) (contenedor) / asignar nombre a contenedor docker

zenmap / Ver version de GUI de nmapv

mv / se utiliza para mover archivos

rm / elimina archivos 

rm -R: / elimina archivos de forma recursiva

cp / copia archivos 

scp / transfiere archivos

curl / verifica conectividad a las url

git clone / clona un repositorio

wget / descarga archivos de la web

head / muestra el principio del archivo txt

tail / muestra el final de un archivo txt

less / ver el contenido de un archivo, permite desplazar hacia adelante y atras

more / ver el contenido de un archivo, solo permite desplazar hacia adelante

nmap / determina los tipos de servicios y hosts que se ejecutan en la red

nslookup / consulta de forma manual los servidores de nombres para resolver un nombre de host dado

netstat /  muestran el estado de la red y estadísticas de protocolos como TCP, SCTP y UDP

shutdown now / apaga inmediatamente

reboot / reinicia el sistema

tar / comprime y descomprime archivos

dd / copia y convertierte datos de archivos a bajo nivel

ffmpeg / extrae la pista de audio de cualquier archivo de video y lo convierte en otro formato

fdupes / escanea directorios en busca de ficheros duplicados, con opciones para listarlos y borrarlos





