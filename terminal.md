# TERMINAL

Conocer la ubicación actual:  
 `$ pwd`  
Listar los elementos de una carpeta:
 `$ ls`     
Cambiar la ubicación:
 `$ cd <nombre de la carpeta>`<br>
Crear una carpeta:
 `$ mkdir <nombre de la nueva carpeta>`<br>
Abir con el editor:
 `$ code .` o `$ atom .`<br>
Eliminar archivo:
 `$ rm <nombre del archivo>`<br>
Eliminar carpeta:
 `$ rm -rf <nombre de la carpeta>`<br>
Mover archivo:
 `$ mv <archivo o carpeta> <carpeta destino>`<br>
Copiar archivo:
 `$ cp <archivo> <carpeta donde se va a copiar>`<br>
Copiar carpeta:
 `$ cp -r <carpeta> <carpeta donde se va a copiar>`<br>
Abrir la carpeta:
 `$ xdg-open .` <br>
Instalar un paquete .deb:
 `$ sudo dpkg -i <nombre del paquete>`

## GIT

Guardar la contraseña en el disco:
`$ git config --global credential.helper store`<br>
Iniciar git:
 `$ git init` <br>
Agregar repositorio:
 `$ git add .` <br>
Crear un commit:
 `$ git commit -m 'mensaje'`<br>
Estado del proyecto:
 `$ git status`<br>
Lista la configuración:
 `$ git config --list`<br>
Cambiar la configuración:
 `$ git conig --global <propiedad>`<br>
eliminar los cambios anteriores:
 `$ git reset '--hard o soft'`<br>
Ver una version anterior:
 `$ git checkout "código del commit"`<br>
Crear rama:
 `$ git checkout -b <nombre de la rama>`<br>
cambiarme de rama:
 `$ git checkout <rama a la que quiero ir>`<br>
Listar las ramas del proyecto:
 `$ git branch`<br>
Integrar los cambios de la rama (parado en el main):
 `git merge <rama que se va a integrar>`<br>
Cambiar el nombre de la rama:
 `git branch -m <nuevo nombre>`<br>
borrar una rama:
`git branch -d <nombre de la rama>`<br>
Eliminar el último commit:
`$ git checkout -- HEAD <nombre del archivo>`<br>
Subir una rama:
`$ git push -u origin <nombre de la rama>`<br>
Ver los cambios hechos en el repositorio remoto:
`$ git fetch origin`<br>
Actualizar el último commit:
`$ git commit --amend --no-edit`<br>
Descartar el último commit:
`$ git reset --hard HEAD~<número de commits que se van a descartar>`<br>
Recuperar commits descartados:
`$ git reset --hard HEAD{<número de commits>}`<br>
Editar commits:
`$ git rebase -i HEAD~<número de commits>`<br>
Agregar cambion y crear commit:
`$ git commit -am`  
