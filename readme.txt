 /*
git init -> Inicializando el proyecto
git status -> estado actual de cambios
git add name-file -> agregando cambio de un archivo en especifico
git add -A -> agregando todos cambios
git push -> agregar archivo
git commit -m "message"-> Agregando commit con mensaje
git commit --amend (esc + : wq) -> agregando información al ultimo commit sin mensaje
git log -> estado de los commit
git tag -a (version) -m 'version del proyecto' ->agregando versiones
git tag (version) (commit_id)-> versionando un commit hecho
git tag -l -> listando tag 
git tag -d (version) -> elimina el tag
git tag -f -a (version) -m 'message'-> renombrar el tag 
git log --oneline -> En una linea
git log --oneline --graph
git log -3 || -1 || -2 ->último(s) commit
git diff -> compara los commit
git diff f8b299f -> compara este commit con lo que está actual
git diff 09366ea f8b299f -> compara versiones
git diff [version_1] vs [version_2]
git reset --soft [sha_#] -> desde que commit quiero quitar los cambios pero lo mantiene en stage para ser envadi
git reset --mixed [sha_#] -> quita los commit y no deja los archivos en el stage
git reset --hard[sha_#] -> Elimina archivos quitando cambios y del sgate directory
git branch name_ -> crear ramas
git branch -l -> Listar ramas
git branch -d name_ -> eliminar ramas
git branch -D name_ -> forsar eliminacion de ramas
git branch -m name_ name_2-> renombrar ramas
git checkout name_ -> mover entre ramas
git checkout (log) -> devolverse en el tiempo
git checkout -b name_ -> crear y navegar hacia la rama
git merge (rama) -> ubicado en la rama ppal mesclamos los cambios
git rebase (rama) -> sin bifurcaciones (solo en local)
git clone url(git) -> clonar repo
git remote add nombre_repo url(git) -> añadir repo
git remote remove nombre_repo
git fetch origin master ->  descarga los cambios a una rama generalmente llamada origin/master, seguido de esto tienes que fuisonar esa rama //trar cambios del repo remoto
git  merge origin/master --allow-unrelated-histories -> mesclar ramas
git pull origin master -> es como ejecutar los 2 pasos anteriores(fetch y merge) en uno solo //trar cambios del repo remoto
git push origin master -> subir cambios al repo remoto
git push origin master --tags -> subir los tags
git push origin responsive -> enviar otra rama


http://18.222.191.121/l4sportugal/public/login
jbarbosa@leads4sales.pt
l4sportugal



*/