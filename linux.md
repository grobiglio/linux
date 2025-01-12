# Resumen de los principales comandos de Linux

|Comando|Descripción|
|:-----:|-----------|
|cat|Muestra el contenido de un archivo en la terminal.|
|exit|Sale de la terminal de comandos.|
|mkdir `nombre del directorio`|Crea el directorio cuyo nombre se especifica|
|mkdir `dir1` `dir2` ... `dirn`|Crea los `n` directorios especificados. Si se especifica la ruta, los crea en la ruta especificada.|
|mkdir -p `dir/subdir`|Crea el subdirectorio `subdir`. Si `dir` no existe lo crea.|
|rm `nombre del fichero`|Borra el fichero cujo nombre se indica.|
|rm -r `dir`|:warning: Este comando borra el directorio con todo su contenido. :warning:|
|rm -rf `dir`|Elimina el directorio sin pedir confirmación.|
|pwd|Imprime en pantalla el directorio de trabajo. (Siglas de print working directory)|
|touch `nombre del fichero`|Crea el fichero cuyo nombre se especifica.|
|touch `fichero1` `fichero2` ... `ficheron`|Crea los `n` ficheros especificados.|
|date|Muestra la fecha y hora actual.|
|cp `origen` `destino`|Copia un fichero desde el origen al destino. `origen` es el nombre del fichero. Si `destino` es un nombre de fichero, hace una copia del fichero de origen con el nombre `destino`. Si es un directorio copia el fichero de origen a dicho directorio. El comando `cp` crea un fichero nuevo con el nombre del propietario que está ejecutando el comando, no de quién creó el fichero original.|
|cp `fichero1` `fichero2` ... `ficheron` `dir`|Copia los `n` ficheros especificados en el directorio `dir`|
|cp -r `dir1` `dir2`|Hace una copia del directorio `dir1` con el nombre `dir2`|
|mv `fichero1` `fichero2`|Cambia el nombre del `fichero1` a `fichero2`. Mueve el fichero. El comando `mv` no modifica el propietario y el grupo propietario.|

|Otros comandos|Descripción|
|:------------:|-----------|
|htop|Muestra el rendimiento del sistema.<br>En caso de que no se encuentre instalado se debe instalar ejecutando el comando `sudo apt install htop`|

|Atajo|Descripción|
|:-----:|-----------|
|Ctrl+Alt+`t`|Abre la terminal|
|Ctrl+`+`|Agranda el tamaño de la fuente en la terminal.|
|Ctrl+`-`|Disminuye el tamaño de la fuente en la terminal.|
