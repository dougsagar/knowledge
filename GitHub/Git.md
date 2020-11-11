# Git

**What it is Git?**
* Distribuited version control 
* Cordinates work between multiple developers
* Who made what changes and when
* Revert back any time
* Local & remote repos

**Basic Commands**

![Git States](/images/git_states.png)
Format: ![Alt Text](url)


	* git init: le indica al SO que esta listo para comenzar a utilizar git (puede ser un folder con archivos del código o un proyecto ya creado)
	* git add <file>: agrega nuevos archivos del working directory staging area
	* git status: ver en que status se encuentran los archivos (si están en working directory o si están en el staging área)
	* git commit: es para pasar los archivos del staging área al repositorio (es como para crear un primer snapshot, primera foto de la versión del código)
	* git log: 
	* git push: es para subir el código a un repositorio remoto (normalmente se utiliza para subirlo a un servidor para que pueda ser accedido por los desarrolladores que tienen permiso para modificar el código)
	* git pull: para los casos donde está trabajando múltiples desarrolladores, este comando trae todos esos cambios
	* git clone: hace una copia local desde el servidor donde se encuentra el repositorio para poder trabajar con el código
	* git checkout: revierte los cambios trabajados antes de agregarlos al stanging área.
	* git diff: muestra que lineas fueron agregadas al codigo respecto al último cambio.
	* git commit -m "": Para hacer un commit sin abrir VI.
	* git branch "": Crea una nueva version alternativa local del branch master.
	* git checkout "branch name": para moverse entre branch.
	* git branch: Indica en cual branch se está trabajando.
	* git add. : Para agregar varios archivos al staging are al mismo tiempo.
	* git config --global user.email "" :  Agrega correo del autor
	* git config --global user.name "" : Agrega nombre del autor
	* git remote add origins "https://github.com/nombre_usuario/nombre_proyecto.git": agregar un reposito a un destino remoto.
