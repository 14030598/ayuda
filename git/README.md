
# git

| Comando | Descripción |
|---------|-------------|
|`git init`| Iniciar proyecto de git|
|`git add .`| Preparar archivos que se convertirán en commit, El punto es para agregar todos los archivos modificados|
|`git add nombre_archivo`| Preparar el archivo que se convertirá en commit|
|`git commit -m "Aqui va el mensaje"`| Crear commit con su mensaje|
|`git remote add origin https://github.com/andres2093/santander-front.git`| Agregar remoto "Solo la primera vez"|
|`git push -u origin master`| Enviar commits al servidor de GitHub|
|`git push`| Enviar commits al servidcor estando en master|
|`git clone https://github.com/...`| Clonar un repositorio creado en github(con codigo) a local|
|`git reflog`| Ver |
|`git reset --soft HEAD~1`| Mantiene los cambios|
|`git reset --hard HEAD~1`| No mantiene los cambios |
|`git config --global user.name "your_github_username"` |  |
|`git config --global user.email "your_github_email"` |  |
|`git config -l` | Ver la informacion de configuración |


git reflog [show] [log-options] [<ref>]
git reflog expire [--expire=<time>] [--expire-unreachable=<time>]
	[--rewrite] [--updateref] [--stale-fix]
	[--dry-run | -n] [--verbose] [--all [--single-worktree] | <refs>…​]
git reflog delete [--rewrite] [--updateref]
	[--dry-run | -n] [--verbose] ref@{specifier}…​
git reflog exists <ref>

---

## commits
| Comando | Descripción |
|---------|-------------|
|`git commit --amend -m "Este es el mensaje correcto"`| quieres arreglar el mensaje que has usado para el último commit |
|`git add src/archivo-con-cambios.js`| Quieres añadir más cambios al último commit: Añade los archivos con modificaciones que quieres añadir al commit anterior|
|`git commit --amend -m "Mensaje del commit"`| Vuelve a hacer el commit con el parámetro amend: esto NO va a crear un nuevo commit si no que va a solucionar el anterior|
|`git revert 74a1092`| Deshacer un commit (ya publicado)|
|`gi`| Inicia|
|`gi`| Inicia|
|`gi`| Inicia|


**Importante: _El parámetro de --amend es muy útil pero sólo funciona con el último commit y siempre y cuando NO esté publicado. Si ya has hecho push de ese commit, esto no va a funcionar. Deberías hacer un git revert en su lugar._**


---

## Ramas
| Comando | Descripción |
|---------|-------------|
|`git pull origin desarrollo`| Para obtener update de la rama desarrollo|
|`git fetch`| Obtener una rama del repositorio remoto|
|`git push origin desarrollo`| Para mandar update de la rama desarrollo|
|`git push -u origin experimental`| Para mandar update de la rama desarrollo|
|`git branch` | Para ver la rama en la que te encuentras|
|`git branch nombre_rama`| Crea una rama|
|`git show-branch`| Ver todas las ramas con sus commits|
|`git branch -a`|Ver todas las ramas|
|`git branch -r`|Ver ramas remotas|
|`git switch nombre_rama`|Cambiar a una rama|
|`git switch -`|regresa a la rama anterior de la que se cambio|
|`git checkout -b nombre_rama`|Crea una rama y se mueve a esta|
|`git checkout -d nombre_rama`|Borra la rama (-delete)|
|`git checkout -D nombre_rama`|Borra la rama forzando la eliminacion|
|`git push origin --delete rama_a_borrar`| Eliminar un branch en remoto|
|`git branch -m old_name new_name`|Renombre una rama (-move)
|`git diff primera_rama segunda_rama`|Comparar ramas (opcional: --color-words)|
|`git branch --merged`|Ver las ramas completamente combinadas|
|`git merge experimental -m 'Esto es un merge con mensaje'`| Permite fusionar desde master nombre_rama con el commit|
|`git help branch`|Ayuda branch|

---

## Stats
| Comando | Descripción |
|---------|-------------|
|`git stash save "mensaje opcional para ti"`| Almacenar temporalmente los cambios locales|
|`git stats list`| |
|`git stats apply nombre_stats`| Aplica los cambios y deja una copia en el stats|
|`git stats pop nombre_stats`| Aplica los cambios y elimina los archivos del stats|
|`git stats drop nombre`| Elimina los cambios sin aplicarlos|
|`git stats clear`| Limpia todo el stats|

---

## Merge
| Comando | Descripción |
|---------|-------------|
|`git merge nombre_rama`| Permite fusionar desde master nombre_rama (commit realizados si no no deja)|
|`git rebase`| mover la rama a otro punto del branch|
|``| |
|``| |
|``| |
|``| |

---