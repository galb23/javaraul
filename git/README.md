# javaraul
# comandos git
1. para clonar un repositorio el comando es:
```shell
  git clone https://github.com/galb23/javaraul.git
```
2. para actualizar el git de nuestro repositorio local se utiliza el sigueinte comando
```shell
git fetch origin
```
3. para ver el estado en el que esta el repositorio se usa el sigueite comando
```shell
git status
```
4. para agregar todos  los archivos que se modificaron se debe usar el siguiente comando
```shell
git add˽.
```
4.1 para agregar un archivo que se modifico se debe usar el siguiente comando
```shell
git add [nombre del archivo]
```
5. para hacer commit se utiliza el sigueinte comando
```shell
git commit -m "mensaje del commit "
```
6. para subir los cambios
```shell
git push origin [nombre de la rama]
```
# archivos de configuracion de git
  - el archivo gitignore sirve para ignorar archivos o evitar que se suban archivos al repositorio, se debe de escribir dentro del archivo los nombres de los archivos que no se quieran subir
  ```shell
  .gitignore
  ```
  - la carpeta que contiene los archivos de configuracion del repositorio se llama **.git** dentro de esta carpeta esta el archivo **"config"** en el se guarda la configuracion del repositorio
# comando de ramas

1. para crear una rama se usa el sigueinte comando
```shell
git branch [nombre de la rama que se va a crear]
```
2. para cambiarnos a la nueva rama se utiliza el sigueinte comando
```shell
git checkout [nombre de la rama a la que se desea cambiar]
```
3. para ver las ramas qe tenemos disponibles que tenemos en local se usa el siguiente comando si la rama tiene un asterisco * es la rama donde te encuentras posicionado
```shell
git branch
```
4. para mezclar cambios entre ramas primero se tienen que posicionar en la rama que se desea tener los cambios(ya no se necesita hacer  git add si no se tienen conflictos )
```shell
git merge [rama de la que se quiere traer los cambios]
```
5. para crear una rama y posicionarse sobre ella se utiliza el comando
```shell
git checkout -b [nombre de la rama que se va a crear]
```
6. para traer los cambios que estan en el servidor de una rama determinada se utiliza el sigueinte comando
```shell
git pull origin  [nombre de la rama que se van a traer los cambios del servidor ]
```
# regresar estados anteriores
1. para ver los cambios que se hicieron en el archivo se utiliza el comando
```shell
git diff
```
2. para regresar a un estado anterior inmediato un archivo se utiliza el comando
```shell
git checkout "ruta del archivo"
```
3. para regresar todos los cambios hasta el ultimo commit se utiliza
```shell
git checkout .
```
4. para ver el log de los commit se utiliza el comando
```shell
git log
```
5. para regresar a un commit especifico se utiliza el comando
```shell
git checkout [uuid del commit]
```
5.1. para hacer el commit de los cambios
```shell
git status
git add .
git commit -m "descripcion"
git checkout -b [nombre de la rama]
git checkout [rama donde se quiere tener los cambios]
git merge [rama de la que se quieren traer los cambios]
git push origin [rama ala que se quiere subir]
```
![representacion grafica de un cambio de estado ](https://lh3.googleusercontent.com/NAUizkUNyqFqb9DehLZmhHWpQcsPrrEtHIEAXyAKFSyj27SpCLmFwQHqKUCRzyKr38TPCluhjx0=w1336-h604)
