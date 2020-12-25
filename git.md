#  GIT



Guardar la contraseña en el disco:  
		`$ git config --global credential.helper store`

Iniciar git:  
		 `$ git init`

Agregar repositorio:  
 		`$ git add .`

Crear un commit:  
		 `$ git commit -m 'mensaje'`

Estado del proyecto:  
 		`$ git status`

Lista la configuración:  
		 `$ git config --list`

Cambiar la configuración:  
		 `$ git conig --global <propiedad>`

eliminar los cambios anteriores:  
		 `$ git reset '--hard o soft'`

Ver una version anterior:  
		 `$ git checkout "código del commit"`

Crear rama:  
 		`$ git checkout -b <nombre de la rama>`

cambiarme de rama:  
 		`$ git checkout <rama a la que quiero ir>`

Listar las ramas del proyecto:  
 		`$ git branch`

Integrar los cambios de la rama (parado en el main):  
		 `git merge <rama que se va a integrar>`

Cambiar el nombre de la rama:  
		 `git branch -m <nuevo nombre>`

borrar una rama:  
		`git branch -d <nombre de la rama>`

Eliminar el último commit:  
		`$ git checkout -- HEAD <nombre del archivo>`

Subir una rama:  
		`$ git push -u origin <nombre de la rama>`

Ver los cambios hechos en el repositorio remoto:  
		`$ git fetch origin`

Actualizar el último commit:  
		`$ git commit --amend --no-edit`

Descartar el último commit:  
		`$ git reset --hard HEAD~<número de commits que se van a descartar>`

Recuperar commits descartados:  
		`$ git reset --hard HEAD{<número de commits>}`

Editar commits:  
		`$ git rebase -i HEAD~<número de commits>`

Agregar cambios y crear commit:  
`$ git commit -am`  

Empezar a enviar información del repositorio local al remoto  
`$ git remote add origin <url del repositorio remoto>` 

Crear llave SSH   
`$ ssh-keygen -t rsa -b 4096 -C "<correo>"`

Agregar la llave   
`ssh-add <ruta de la llave>`

