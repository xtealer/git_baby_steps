<h1 style="text-align: center;">Git First Steps</h1>

```python
print('bienvenidos a el mundo %s'%('git'))
```

- **`git config`** Usado para establecer configuración específica de usuario, como sería el  caso de email,nombre de usuario y tipo de formato, etc… Por ejemplo, el siguiente comando se usa para  establecer un email:
  ej. `git config --global user.email sam@google.com`

- **git init** Este comando se usa para crear un nuevo repertorio GIT.

- **git add** Este comando puede ser usado para agregar archivos al index. Por  ejemplo, el siguiente comando agrega un nombre de archivo temp.txt en el  directorio local del index. ej. `git add temp.txt`

- **git clone** Este comando se usa con el propósito de crear una copia de un repositorio. 
  ej. **Remoto** `git clone alex@93.188.160.58:/path/to/repository`
  ej. **Local** `git clone /ruta/local/repositorio`

- **`git commit`** Usado para agregar cambios al repositorio local.
  ej. `git commit –m “Message to go with the commit here”`
- **`git status`** Este comando muestra la lista de los archivos que se han cambiado junto  con los archivos que están por ser añadidos o para hacer commit.

- **`git push`**

  Este es uno de los comandos más básicos. Un simple push envía los  cambios que se han hecho en la rama principal de los repositorios remotos  que están asociados con el directorio que está trabajando. 
  ej. `git push origin master`

  

- **`git checkout`** El comando checkout se puede usar para crear ramas o cambiar entre  ellas. 
  <u>Crear y cambiar a nuevo branch:</u>

  `command git checkout -b <banch-name>`

  <u>Solo cambiar a rama:</u>
  `git checkout <branch-name>`

  

- **`git remote`** El comando git se usa para conectar a un repositorio remoto. 
  <u>Mostrar repositorios conectados:</u>

  `git remote -v`

  <u>Crear nuevo remote:</u>

  `git remote add origin <93.188.160.58>`

- **`git branch`** Este comando se usa para listar, crear o borrar ramas.

- **`git pull`** Para poder fusionar todos los cambios que se han hecho en el repositorio local trabajado repositorio remoto.

- **`git merge`** Este comando se usa para fusionar un branches.
  ej. `git merge origin/master`

- **`git diff`** Este comando se usa para ver una lista de cambios realizados desde el ultimo commit. ej. `git diff HEAD file`

- **`git tag`** Etiquetar se usa para marcar commits específicos con asas simples. `git tag 1.1.0 <mi etiqueta>`

- **git log** Ejecutar este comando muestra una lista de commits en una rama junto con todos los detalles. ej.

```
~$> git log
commit 15f4b6c44b3c8344caasdac9e4be13246e21sadw
Author: Alex Hunter <alexh@gmail.com>
```

- **`git reset`** Para resetear el index y el directorio que está trabajando al último commit realizado. `git reset --hard HEAD`
- **`git rm`** Este comando se puede usar para remover archivos del index y del directorio que está trabajando. `git rm miarchivo.txt`
-  **`git stash`** Ayuda a guardar cambios que aun no seran implementados.
- **`git show`** Se usa para mostrar información sobre cualquier objeto git.
- **`git fetch`** Este comando le permite al usuario buscar todos los objetos de un  repositorio remoto que actualmente no reside en el directorio local que  está trabajando. ej. `git fetch origin`
- **`git grep`** Este comando le permite al usuario buscar en los árboles de contenido  cualquier frase o palabra. ej. `git grep “www.tupaginaweb.com”`
- **`gitk`** Este es la interfaz gráfica para un repositorio local.
- **`git instaweb`** Con este comando un servidor web puede correr interconectado con el  repositorio local. Un navegador web también está automáticamente  dirigido a el.
  ej. `git instaweb –http=webrick`
- **`git gc`** Para optimizar el repositorio por medio de una recolección de basura,  que limpiara archivos innecesarios y los optimizara, usa.
- **`git archive`** Este comando le permite al usuario crear archivos zip o tar que contengan los constituyentes de un solo árbol de repositorio. 
  ej. `git archive  –-format=tar master`
- **`git prune`** Con este comando los objetos que no tengan ningún puntero entrante serán eliminados.
- **`git fsck`** Para poder hacer un chequeo de integridad del sistema de archivos git,  usa este comando. Cualquier objeto corrompido será detectado.
- **`git rebase`** Este comando se usa para la re aplicación de los compromisos en otra rama. Por ejemplo:git rebase master

-----

### Links con mas información acerca de comandos

- [CheatSheet Github \(ingles\)](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)

- [Visual CheatSheet \(ingles\)](http://ndpsoftware.com/git-cheatsheet.html#loc=workspace)
- [GitDocs \(ingles\)](https://book.git-scm.com/docs)
- [Branching \(español\)](https://www.genbeta.com/desarrollo/manejo-de-ramas-de-desarrollo-con-git)
- [Git CheatSheet \(español\)](https://rogerdudler.github.io/git-guide/index.es.html)

----

