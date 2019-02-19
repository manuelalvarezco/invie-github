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










*/