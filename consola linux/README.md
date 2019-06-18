# comandos linux

1. Cd (de change directory o cambiar directorio), es como su nombre lo indica el comando que necesitarás para acceder a una ruta distinta de la que te encuentras. Por ejemplo, si estas en el directorio /home y deseas acceder a /home/ejercicios, seria:
```shell
  cd /home/ejercicios
```
1.1 Si estás en /home/ejercicios y deseas subir un nivel (es decir ir al directorio /home), ejecutas:
```shell
  cd ..
```
1.2 O bien ir directamente a otro directorio que esta al mismo nivel que el nuestro:
```shell
  cd ../directorio
```
2. Ls (de listar), permite listar el contenido de un directorio o fichero. La sintaxis es:
```shell
ls /home/directorio
```
2.1 El comando ls tiene varias opciones que permiten organizar la salida, lo que resulta particularmente útil cuando es muy grande. Por ejemplo, puedes usar -a para mostrar los archivos ocultos y -l para mostrar los usuarios, permisos y la fecha de los archivos. Así como para todos los comandos Linux, estas opciones pueden combinarse, terminando en algo como:
```shell
ls -la /home/directorio
```
3. Pwd (de print working directory o imprimir directorio de trabajo), imprime nuestra ruta o ubicación al momento de ejecutarlo, así evitamos perdernos si estamos trabajando con múltiples directorios y carpetas. Su sintaxis seria:
```shell
[maquinagustavo] pwd
/home/nombrearchivo
```
4. Cp (de copy o copiar), copia un archivo o directorio origen a un archivo o directorio destino. Por ejemplo, para copiar el archivo prueba.txt ubicado en /home a un directorio de respaldo, podemos usar:
```shell
cp /home/prueba.txt /home/respaldo/prueba.txt
```
# nota
En la sintaxis siempre se especifica primero el origen y luego el destino. Si indicamos un nombre de destino diferente, cp copiará el archivo o directorio con el nuevo nombre.

4.1 El comando también cuenta con la opción -r que copia no sólo el directorio especificado sino todos sus directorios internos de forma recursiva. Suponiendo que deseamos hacer una copia del directorio /home/ejercicios que a su vez tiene las carpetas ejercicio1 y ejercicio2 en su interior, en lugar de ejecutar un comando para cada carpeta, ejecutamos:
```shell
cp -r /home/ejercicios /home/respaldos/
```
5. mv (de move o mover), mueve un archivo a una ruta específica, y a diferencia de cp, lo elimina del origen finalizada la operación. Por ejemplo:
```shell
mv /home/prueba.txt /home/respaldos/prueba2.txt
```
6. Mkdir (de make directory o crear directorio), crea un directorio nuevo tomando en cuenta la ubicación actual. Por ejemplo, si estas en /home y deseas crear el directorio ejercicios, sería:
```shell
mkdir /home/ejercicios
```
6.1 Mkdir tiene una opción bastante útil que permite crear un árbol de directorios completo que no existe. Para eso usamos la opción -p:
```shell
mkdir -p /home/ejercicios/prueba/uno/dos/tres
```
7. Rm (de remove o remover), es el comando necesario para borrar un archivo o directorio. Para borrar el archivo prueba.txt ubicado en /home, ejecutamos:
```shell
rm /home/prueba.txt
```
8. Cat (de concatenar), es una maravillosa utilidad que nos permite visualizar el contenido de un archivo de texto sin la necesidad de un editor. Para utilizarlo solo debemos mencionarlo junto al archivo que deseamos visualizar:
```shell
 cat prueba.txt
 ```
9.clear limpia pantalla
```shell
clear
```
