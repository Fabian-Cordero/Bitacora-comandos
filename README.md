# Bitacora-comandos

|Comando | Descripción |
| ------------- | ------------- |
|ip addr | Ver datos de la red|
||
|ping 8.8.8.8 |  Hacer ping para ver latencia de red|
||
|sudo | Dar permisos de administrador|
||
|sudo apt update | Actualiza todos los repositorios|
||
|sudo apt upgrade | Instalar las actualizaciones| 
||
|sudo apt install neofetch | Instala programa que permite ver informacion de hardware y software|
||
|apt | Descargar paquetes|
||
|dpkg | Sirve para instalar paquetes en terminal|
||
|cd  | Moverse a un directorio|
||
|install | Instala los paquetes|
||
|ls  | Muestra lista de archivos|
||
|exit | Salir
||
|pwd | Imprime direcorio de trabajo|
||
|man | Muestra el manual de un programa|
||
|whoami | Muestra el usuario|
||
|sudo su | Usuario root|
||
|su root | Usuario root|
||
|cat | Concatenar archivos|
||
|cat /etc/passwd | Ver los usuarios y sus datos|
||
|useradd | Crea cuentas de usuario|
||
|free -h | Leer memoria disponible|
||
|df -h | Ver detalles de directorios|
||
|du -h archivo.png | Ver tamaño de archivo|
||
|stat archivo.png | Informacion sobre archivo|
||
|file archivo.png | Ver tipo de archivo|
||
|nano | Editor de texto|
||
|vim | Editor de texto|
||
|clear | Limpiar terminal|
||
|apt search | Busca posibles comandos|
||
|grep | Buscar archivo|
||
|find | Buscar archivo|
||
|chmod 777 archivo.png | Dar permisos|
||
|kill -9 $PID | Matar procesos |
||
|touch | Crea archivos|
||
|echo | Imprimir|
||
|chmod +x script.sh | Permisos para ejecutar scripts|
||
|sudo passwd [usuario] | Establecer contraseñas|
||
|cat more less | Muestra contenido de archivo|
||
|history | Ver el historial|
||
|sudo snap install [programa] | Instalar programa| 
||
|sudo apachectl start | Inicia apache|
||
|swapon | Muestra donde esta el archivo de swap|
||
|cat/proc/sys/vm/swappiness | Indica swappiness en la computadora|
||
|df -h | Muestra los discos duros conectados|
||
|sudo mount | Montar datos dispositivos|
||
|sudo mkdir /mnt/ram_disk | Montar disco RAM|
||
|sudo mount -t tmpfs -o size=1024m new_ram_disk /mnt/ram_disk |Montar disco RAM|
||
|chmod | Cambia los permisos de las carpetas|
||
|chmod + | Lee, escribe y ejecuta|
||
|chmod -x | Quitar los permiso de ejecucción|
||
|ls -l | Muestra la lista de los permiso de los archivos|
||
|du -h | Tamaño del arhivo|
||
|stat | Fecha de creacion|
||
|touch | Actualiza la hora de la fecha de modificacion|
||
|chwon | Tomar posesion de un archivo|
||
|file | Muestra el formato de un archivo|
||
|Gparted | Admnistrar las partes del disco duro del sistema|
||
|ps -aux | Para ver todos los Ids de los programas o los procesos|
||
|curl -fsSL https://download.docker.com/linux/debian/gpg l sudo apt-key add - | Agregar la clave GPG oficial de Docker|
||
|sudo add-apt-repository "deb [arch=amd64]https://download.docker.com/linux/ubuntu bionic stable" | Agregar el repositorio oficial de Docker|
||
|sudo apt-get install docker-ce docker-ce-cli containerd.io | Instalar docker|
||
|sudo usermod -aG docker ${USER} | Usar Docker sin sudo|
||
|sudo docker run hello-world | Validar funcionamiento docker|
||
|sudo systemctl start docker  |  Iniciar el Daemon|
||
|sudo systemctl enable docker | Iniciar el Daemon|
||
|docker search ubuntu | Buscar imagenes|
||
|sudo docker images | Ver imagenes instaladas|
||
|docker stop container-id | Detener un contenedor|
||
|docker start container-id | Iniciar contenedor|
||
|sudo docker login -u USUARIODOCKERHUB | Iniciar sesión en la terminal con el usuario de docker hub|
||
|sudo docker push docker-registry-username/docker-image-name | Hacer push a la cuenta de DockerHub|
|| 
|docker rmi Image Image | Eliminar imagen|
||
|docker rm ID ID | Eliminar contenedores|
||
|docker run --rm image_name | Eliminar contenedores despues de cerrados|
||
|sudo docker rm $(sudo docker ps -a -f status=exited -q) |  Eliminar todos los contenedores con estado “Exited (0)”||
||
|sudo docker info | Ver datos de docker|
||
|sudo docker images | Ver imagenes descargadas| 
||
|sudo docker pull ubuntu:latest | Descargar version de ubuntu mas actual|
||
|docker run [images name] | Para correr imagenes|
||
|-a docker ps docker ps -a | Ver los contenedores que esten UP, incluso los que ya se terminaron de ejecutar |
||
|docker run -d (contenedor) | Correr comandos de fondo|
||
|run --name (nombre) (contenedor) | Asignar nombre a contenedor docker|
||
|zenmap | Ver version de GUI de nmapv|
||
|mv | Se utiliza para mover archivos|
||
|rm | Elimina archivos 
||
|rm -R: | Elimina archivos de forma recursiva|
||
|cp | Copia archivos| 
||
|scp | Transfiere archivos|
||
|curl | Verifica conectividad a las url|
||
|git clone | Clona un repositorio|
||
|wget | Descarga archivos de la web|
||
head | Muestra el principio del archivo txt|
||
|tail | Muestra el final de un archivo txt|
||
|less | Ver el contenido de un archivo, permite desplazar hacia adelante y atras|
||
|more | Ver el contenido de un archivo, solo permite desplazar hacia adelante|
||
|nmap | Determina los tipos de servicios y hosts que se ejecutan en la red|
||
|nslookup | Consulta de forma manual los servidores de nombres para resolver un nombre de host dado|
||
|netstat |  Muestran el estado de la red y estadísticas de protocolos como TCP, SCTP y UDP|
||
|shutdown now | Apaga inmediatamente|
||
|reboot | Reinicia el sistema|
||
|tar | Comprime y descomprime archivos|
||
|dd | Copia y convertierte datos de archivos a bajo nivel|
||
|ffmpeg | Extrae la pista de audio de cualquier archivo de video y lo convierte en otro formato|
||
|fdupes | Escanea directorios en busca de ficheros duplicados, con opciones para listarlos y borrarlos|



