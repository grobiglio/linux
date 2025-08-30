
# Laboratorio 01: La CLI básica

## Objetivo
Familiarizarse con la línea de comandos y navegación en Linux.

### Ejercicios
1. Crear un directorio llamado `prueba`.
2. Dentro de `prueba`, crear un archivo vacío llamado `hola.txt`.
3. Escribir dentro de `hola.txt` el texto "Hola Linux".
4. Listar el contenido de `prueba` mostrando detalles de permisos y tamaño.
5. Copiar `hola.txt` a un nuevo archivo llamado `copia.txt`.
6. Borrar `hola.txt`.

### Soluciones esperadas
```bash
mkdir prueba
cd prueba
touch hola.txt
echo "Hola Linux" > hola.txt
ls -l
cp hola.txt copia.txt
rm hola.txt
```