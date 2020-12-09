# TERMINAL

Conocer la ubicación actual: `$ pwd`<br>
Listar los elementos de una carpeta: `$ ls`<br>
Cambiar la ubicación: `$ cd <nombre de la carpeta>`<br>
Crear una carpeta: `$ mkdir <nombre de la nueva carpeta>`<br>
Abir con el editor: `$ code .` o `$ atom .`<br>
Eliminar archivo: `$ rm <nombre del archivo>`<br>
Eliminar carpeta: `$ rm -r <nombre de la carpeta>`<br>
Mover archivo: `$ mv <archivo o carpeta> <carpeta destino>`<br>
Copiar archivo: `$ cp <archivo> <carpeta donde se va a copiar>`<br>
Copiar carpeta: `$ cp -r <carpeta> <carpeta donde se va a copiar>`<br>

Abrir la carpeta: `$ xdg-open .` <br>
Instalar un paquete .deb: `$ sudo dpkg -i <nombre del paquete>`

## GIT

Guardar la contraseña en el disco: `$ git config --global credential.helper store`<br>
Iniciar git: `$ git init` <br>
Agregar repositorio: `$ git add .` <br>
Crear un commit: `$ git commit -m 'mensaje'`<br>
Estado del proyecto: `$ git status`<br>
Lista la configuración: `$ git config --list`<br>
Cambiar la configuración: `$ git conig --global <propiedad>`<br>
eliminar los cambios anteriores: `$ git reset '--hard o soft'`<br>
Ver una version anterior: `$ git checkout "código del commit"`<br>
