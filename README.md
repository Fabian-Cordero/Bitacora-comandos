# Bitacora-comandos
1. ip addr / interfaces de red que tiene la maquina

ping 8.8.8.8 /  muestra los paquetes perdidos y los recibidos

sudo / es dar permisos de administrador para descargar o inyectar codigo

ejemplo: sudo dpkg -i google-chrome-stable_current_amd64.deb

apt  es para descargar paquetes de cualquier cosa

install  instala los paquetes

cd  cambiar de directorio

ls  mostrar lista

dpkg  es para instalar paquetes mediante de la terminal

ejemplo: dpkg -i google-chrome-stable_current_amd64.deb

i- ---> es para instalar el paquete

Se puede descargar mas paquetes con un espacio.

sudo apt update ---> para actualizar todos los repositorios que hay

sudo apt upgrade ---> instalar todas las actualizaciones 

pwd ---> para imprimir o saber de donde esta uno

sudo apt install cmatrix

sudo apt install neofetch --->

whoami --> usuario de la maquina

man --> mostrar el manual de un programa

sudo su --> ir en forma root o usuario root

su root --> ir en forma root o usuario root

exit --> para salir de 

sudo useradd [user] -m

nano --> editor de texto

cat --> leer datos de archivos y mostrar su contenido.

cat /var/log/syslog

tail -n 10 /var/log/syslog

head -n 10 /var/log/syslog

cat /var/log/syslog | more

grep -r "ubuntu" /var/log/syslog | more --> es para buscar/encontrar un archivo especifico o un nombre en especifico

history --> ver el historial

sudo snap install spotify --> instalar programa en la terminal

sudo apachectl start

free -h --> cantidad de memoria y te dice la memoria swap que tiene el sistema

swapon --> donde esta el archivo de swap

cat/proc/sys/vm/swappiness --> indica el swappiness de la computadora

df -h --> sirve para ver todos los discos que tiene conectado en el disco.

sudo mount --> sirve para montar datos

# Comando 1
  for file in /proc/*/status ; do awk '/VmSwap|Name/{printf $2 " " $3}END{ print ""}' $file; done | sort -k 2 -n -r | less

# Comando 2
  free -h

# Comando 3
  swapon

# Comando 4 Swampiness
  cat /proc/sys/vm/swappiness

# Montar un RAM Disk

  sudo mkdir /mnt/ram_disk
  
  sudo mount -t tmpfs -o size=1024m new_ram_disk /mnt/ram_disk
  
chmod ---> Cambia los permisos de las carpetas

chmod + ---> lee, escribe y ejecuta

chmod -x --> quitar los permiso de ejecucción

ls -l ---> muestra la lista de los permiso de los archivos

du -h ---> Tamaño del arhivo

stat ---> Fecha de creacion

touch ---> actualiza la hora de la fecha de modificacion

chwon ---> Tomar posesion de un archivo

file ---> muestra el formato de un archivo

df -h ---> mostrar los false system del sistema

mount ---> es para montar ciertos dispositivos

Gparted ---> Admnistrar las partes del disco duro del sistema

gnome-disk-utility ---> 

kill-9 $PID --- Matar un proceso.

ps -aux ---> Para ver todos los Ids de los programas o los procesos

greg ---> Mostrar localizacion de los procesos

ejemplo ps -aux | greg firefox

pwd ---> Directorio actuar donde esta uno
