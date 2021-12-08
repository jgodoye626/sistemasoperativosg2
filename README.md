# Sistemas Operativos - 2021
Bitacora de comandos linux para el curso sistemas operativos 2021

| Comando                                   | Descripcion                                                 |
| ----------------------------------------- | ----------------------------------------------------------- |
| ls                                        | Lista todos los archivos y carpetas en el directorio actual |
| ls -a                                     | Muestra los archivos escondidos tambien                     |
| cd                                        | Navega al directorio home                                   |
| cd ..                                     | Se mueve un nivel para arriba en el directrio               |
| cd 'directorio'                           | Navega a un directorio especifico                           |
| cat nombre_archivo                        | Imprime en pantalla los contenidos de una archivo           |
| mv nombre_archivo nueva_direccion_archivo | Mueve un archivo a una nueva ubicacion                      |
| sudo                                      | Permite a un usuario correr comandos con privilegios root   |
| rm 'nombre_archivo'                       | Borra un archivo                                            |
| rm -R 'nombre_directorio'                 | Borra un directorio                                         |
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
| sudo apt-get update                       | Consigue todos los paquetes por actualizar conectandose a los repositorios |
| sudo apt-get upgrade                      | Instala las actualizaciones |
| apt                                       | Se usa para la instalacion de paquetes o para actualizar paquetes ya existentes |
| sudo apt install 'package_name'           | Se utiliza para instalar un paquete nuevo de los repositorios linux |
| sudo snap install 'snap'                  | Se utiliza para instalar programas mediante snapcraft.io |
| cut -d: -f1 /etc/passwd                   | Muestra la lista de usuarios que se guardan en /etc/passwd |
| sudo systemctl start/restart/stop/reload/status 'proceso'            | Permite ver diferentes opciones sobre los procesos de systemd y service manager |
| man 'comando'                             | Muestra toda la informacion sobre ese comando en especifico |
| 
