-Entra al thecmdchallenge/ directorio
```bash
ls
cd thecmdchallenge
```
-Imprimir la ruta del directorio actual
```bash
pwd
```
-Listar todos los archivos del directorio actual, incluidos los ocultos
```bash
ls -a
```
-Ahora enumera todos los archivos dentro del proyecto, de forma recursiva
```bash
find . -type f
```
-Limpia todo el desorden de la línea de comandos 
```bash
clear
```
-vaya al último nivel de la carpeta small-name y muestre en la consola el contenido del trophy.txt archivo
```bash
find . -name "trophy"
```
-Sube un nivel y llega al directorio funcode y enumera todos los archivos con la extension tipica de JavasScript
```bash
ls
cd thecmdchallenge/
ls
cd funcode/
ls
find . -type f -name "*.js"
```
-Crea un nuevo directorio dentro de funcode/the-most-Funny llamado "not-that-funny"
```bash
cd the-most-funny
mkdir not-that-funny
ls
```
-Crea una copia de the -mostboring-text.txt y nombrala lol.txt
```bash
ls
cd thecmdchallenge/
cd boringfolder/
ls
cd even-more-boring
ls
cd i-cant-believe-how-boring
ls
cd the-ultimate-boring-inception
ls
cd the-mostboring-text.txt lol.txt
ls
```
-Muévete funcode/kids.jpg hacia dentrofuncode/images/hello/
```bash
(cuando lo último sea /boringfolder):
ls
cd funcode
ls
mv kids.jpg images/hello
cd images
ls
cd hello
ls
```
-Eliminar el directorio small name.
```bash
(volver a que lo último sea /thecmdchallenge)
ls
rm -r small-name
ls
```
-Imprima en la línea de comandos el contenido de the-ultimate-joke.txt
```bash
cat the-ultimate-joke.txt
```
-Elimina todo el contenido de la carpeta aburrida
```bash
rn -r boringfolder
```
-Abra el archivo kamehameha/dragon-ball-jokes.md usando el director de texto de la linea de comandos vi
```bash
cat kamehameha/dragon-ball-jokes.md
```
-Actualiza el archivo kamehameha/dragon-ball-jokes.mdeliminando el primer chiste que leas en el archivo, finalmente guarda y cierra el editor de texto.
```bash
nano kamehameha/dragon-ball-jokes.md
```
