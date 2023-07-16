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
|cp `origen` `destino`|Copia un fichero desde el origen al destino. `origen` es el nombre del fichero. Si `destino` es un nombre de fichero, hace una copia del fichero de origen con el nombre `destino`. Si es un directorio copia el fichero de origen a dicho directorio.|
|cp `fichero1` `fichero2` ... `ficheron` `dir`|Copia los `n` ficheros especificados en el directorio `dir`|
|cp -r `dir1` `dir2`|Hace una copia del directorio `dir1` con el nombre `dir2`|

|Atajo|Descripción|
|:-----:|-----------|
|Ctrl+Alt+`t`|Abre la terminal|
|Ctrl+`+`|Agranda el tamaño de la fuente en la terminal.|
|Ctrl+`-`|Disminuye el tamaño de la fuente en la terminal.|
