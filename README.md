# Sistemas Operativos - 2021
Bitacora de comandos linux para el curso sistemas operativos 2021

| Comando                                   | Descripcion                                                 |
| ----------------------------------------- | ----------------------------------------------------------- |
| ls                                        | Lista todos los archivos y carpetas en el directorio actual |
| ls -a                                     | Muestra los archivos escondidos tambien                     |
| ls -l 'carpeta' -R                        | Recorre todas las carpetas y subcarpetas y las imprime en pantalla |
| ls -l                                     | Muestra el tipo de archivo y los permisos                   |
| r                                         | Permiso para escribir                                       |
| w                                         | Permiso para leer                                           |
| x                                         | Este significa permiso para ejecutar                        |
| chmod                                     | Cambia los permisos para un archivo o directorio            |
| chown                                     | Cambia el dueño de un archivo o directorio                  |
| cd                                        | Navega al directorio home                                   |
| cd ..                                     | Se mueve un nivel para arriba en el directrio               |
| cd 'directorio'                           | Navega a un directorio especifico                           |
| cat nombre_archivo                        | Imprime en pantalla los contenidos de una archivo           |
| mv nombre_archivo nueva_direccion_archivo | Mueve un archivo a una nueva ubicacion                      |
| sudo                                      | Permite a un usuario correr comandos con privilegios root   |
| rm 'nombre_archivo'                       | Borra un archivo                                            |
| rm 'nombre_directorio' -R                 | Borra un directorio                                         |
| rm 'nombre_directorio' -Rf                | Borra de forma forzada un directorio                        |
| clear                                     | Limpia todo el texto de la terminal                         |
| mkdir 'nombre_directorio'                 | Genera un directorio nuevo en el directorio a actual o en la direccion especificada |
| ps -aux                                   | Permite obtener informacion sobre los procesos corriendo actualmente en el sistema  |
| pwd                                       | Muestra el directorio actual en el que se estaba trabajando                         |
| sudo adduser 'nombre_usuario'             | Añade un nuevo usuario al sistema                           |
| sudo userdel -r 'nombre_usuario'          | Borra un usuario                                            |
| cp 'archivo1' 'archivo2'                  | Copia el archivo1 al archivo2                               |
| touch 'nombre_archivo'                    | Genera un archivo vacio                                     |
| nano 'nombre_archivo'                     | Abre un archivo con el editor de texto nano. Si el archivo no existe genera uno nuevo |
| vim 'nombre_archivo'                      | Abre un archivo con el editor de texto vim |
| head 'nombre_archivo'                     | Muestra las primeras 10 lineas de un archivo |
| head 'archivo' -n X                       | Puedo escoger cuantas lineas quiero ver donde X es la cantidad de lineas |
| tail 'nombre_archivo'                     | Muestra las ultimas 10 lineas de un archivo  |
| killall 'nombre_proceso'                  | Mata todos los procesos que tengan el nombre especificado |
| kill PID                                  | Mata el proceso con el ID especificado                    |
| ip a / ip addr                            | Muestra todas las direcciones de IP y las interfaces de red |
| ping 'domain'                             | Hace un pinga a la direccion indicada |
| whoami                                    | Muestra el usuario que se esta usando actualmente |
| tar xzf 'nombre_archivo.tar.gz'           | Permite extraer los contenidos de un archivo gzip comprimido a tar |
| find                                      | Permite buscar un archivo o directorio basado en su nombre u otros parametros |
| wget 'URL'                                | Permite descargar archivos e informacion de diferentes servidores web |
| curl 'URL'                                | Funciona similar al wget, permite transferir informacion desde o hacia un servidor designado sin interaccion del usuario |
| curl -X GET -L 'URL'                      | -X Indica la forma de enviar los datos mediante un GET -L indica la direccion a donde enviar la informacion |
| sudo apt-get update                       | Consigue todos los paquetes por actualizar conectandose a los repositorios |
| sudo apt-get upgrade                      | Instala las actualizaciones |
| apt                                       | Se usa para la instalacion de paquetes o para actualizar paquetes ya existentes |
| sudo apt install 'package_name'           | Se utiliza para instalar un paquete nuevo de los repositorios linux |
| sudo snap install 'snap'                  | Se utiliza para instalar programas mediante snapcraft.io |
| cut -d: -f1 /etc/passwd                   | Muestra la lista de usuarios que se guardan en /etc/passwd |
| sudo systemctl start/restart/stop/reload/status 'proceso'            | Permite ver diferentes opciones sobre los procesos de systemd y service manager |
| man 'comando'                             | Muestra toda la informacion sobre ese comando en especifico |
| grep 'texto'                              | Hace una busqueda de un string dentro de un directorio |
| scp 'archivo' 'nombre_usuario_del_servidor@'direccion_ip_del_servidor':'/ruta_donde_guardar_el_archivo | Hace una copia de un archivo a traves de la red |
| git clone 'url'                           | Para clonar un repositorio git |
| wc                                        | Sirve para hacer conteo de palabras. *Word count* |
| wc 'archivo' -l                           | Solo muestra la cantidad de lineas |
| wc 'archivo' -w                           | Solo muestra la cantida de palabras |
| wc 'archivo' -m                           | Solo muestra la cantidad de caracteres |
| less/more 'archivo'                       | Puedo ver todas las lineas del archivo para ir pasando como paginas un archivo |
| history                                   | Se puede ver el historial de todos los comandos que se han digitado |
| reboot                                    | Reinicia el sistema sin importar que este abierto |
| shutdown                                  | Apaga el sistema sin importar que este abierto    |
| pdfunite 'archivo1' 'archivo2' 'archivosalida' | Se puede usar para juntar varios pdfs en uno solo |
| pdfseparate -f x -l x 'nombre_archivo' 'nombre_archivo_Resultante_%d.pdf' | Permite separar archivos pdfs tomando como parametro el rango de paginas |
| bash 'nombre_script.sh'                   | Se puede usar para correr un script bash |
| ssh                                       | Permite hacer login a un dispositivo remoto con ssh |
| uname =a                                  | Da informacion sobre la version del kernel y la arquitectura |
| sudo passwd -l 'nombre_usuario'           | Cambia la contraseña de un usuario                           |
| w                                         | Muestra quienes estan en linea en el sistema                 |
| docker ps                                 | Muestra todos los contenedores de docker que se estan corriendo |
| docker ps -a                              | Muestra todos los contenedores que estan en el sistema incluidos los que no estan corriendo |
| docker pull 'image'                       | Jala una imagen especifica de docker                            |
| docker run 'image'                        | Corre una imagen de docker                                      |
| docker exec -it 'id_contenedor' bash      | Permite acceder un contenedor que esta corriendo                |
| docker stop 'id_contenedor'               | Detiene un contenedor que esta corriendo                        |
| docker kill 'id_contenedor'               | Detiene un contenedor a la fuerza                               |
| docker commit 'id_contendor' 'nombre_usuario/nombre_imagen' | Crea una nueva imagen de un contenedor editado en el sistema local |
| docker login                              | Hace login a docker hub |
| docker push 'nombre_usuario/nombre_imagen' | Sube una imagen al repositorio de docker hub |
| docker images                             | Muestra todas las imagenes que estan guardadas localmente |
| docker rm 'id_contenedor'                 | Borra un contenedor que ya ha sido detenido |
| docker rmi 'id_contenedor'                | Borra una imagen del espacio local |
| docker build                              | Construye una imagen de un archivo docker que se ha especificado previamente |



