# GIT INICIO DE GIT CONTROL DE VERSIONES
creando elemento desde la terminal 
code index.html

*
CONFIGURACION GLOBAL DE GIT DESPUES DE LA INSTALACION

git config --global user.email "smithmoreno2120@gmail.com"

 git config --global user.name "Devsag"

*
INICIAR UN REPOSITORIO 
 git init

* AÑADIR O PREPARAR ARCHIVO PARA LA SIGUIENTE CONFIRMACION
git add . (todos los archivos)
git add (archivos undivuales)

* VER ESAATDO DE LA MODIFICACION 
git status

*CONFIRMAR ESTADO DEL ARCHIVO
git commit -m "mensaje de confirmacion de lo que se hizo en el archivo"

*VOLVER A UN REPO /MOVERNO  ENTRE RAMAS
git checkout + el/ f116d51 que obtenemos  con git log --oneline

vover git checkout master o la rama donde estamos trabajando

*ETIQUETA DE VERSION /O REGISTRO DE UN CODIGO ESTABLE ENTRE EL PASADO Y EL FUTURO

git tag (nombre de version)

listar todas las etiquetas mediante git tag

volver a ver lo que tenia en la anterior version

git checkout v1

*TRABAJO EN EQUIPO RAMAS

lo usual la rama master es para trabjar en la app que va ir  a producion
 
y para trabajar en desarrolo , se crea una rama 

git checkout -b Develop

git branch   ver rama donde estoy


git checkout master/new rama
moverme entre ramas

 en importante crear una rama que no afecte las dos principarles

git checkout -b 


*SUBIR REPOSITORIO EXISTENTE

git remote add (el origin puede ser cualquier alias) https://github.com/Devsaga12/GIT.git
git branch -M main
git push -u (alias del http )origin main(nombre de la rama donde vamos a subir nuestra version)
