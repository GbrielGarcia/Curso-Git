# Documentacion

git config --global
- Para las configuraciones globales.

git config --global user.name "tu nombre"
- Para configurar el nombre del usuario.

git config --global user.email "tu email"
- Para configurar tu correo electronico.

git config l
- Para visulizar la lista de configuraciones.

git init 
- Para inicializar el repositorio con git

git status
- Para visualizar el estado de la carpeta
  
git add "nombre del archivo sin las """
- agragando archivos a git


git add .
- Para agregar todos los archivos a git

git commit -m "mensaje"
- Es para agregar un mensaje a los archivos guardados.

git commit -am 
- Agrega a todos los archivos ( solo modificados )

git checkout 
- Para volver al estado anterior 

git checkout -f
- para forsarlo


git restore --staged
- para sacar los archivos en espacio de proceso "git add"
  
git diff
- Para ver las diferencias entre los archivos editados.

git diff --stats
- Es para mostrar estadiscas de los archivos editados.

git checkout <numero del commit>
- Para visualizar el commit de ese tiempo.

git log 
- Para ver la informacion del commit

git log --raw
- Nos da tambien la informacion de los archivos en ese commit

git log --sumary
- Para ver la informacion convensada

git log --oneline
- Muestra la informacion convensada solo commit y has