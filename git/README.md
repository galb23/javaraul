# javaraul
# comandos git
1. para clonar un repositorio el comando es:
```shell
  git clone https://github.com/galb23/javaraul.git
```
2. para ver el estado en el que esta el repositorio se usa el sigueite comando
```shell
git status
```
3. para agregar todos  los archivos que se modificaron se debe usar el siguiente comando
```shell
git add˽.
```
3.1 para agregar un archivo que se modifico se debe usar el siguiente comando
```shell
git add [nombre del archivo]
```
4. para hacer commit se utiliza el sigueinte comando
```shell
git commit -m "mensaje del commit "
```
5. para subir los cambios
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
