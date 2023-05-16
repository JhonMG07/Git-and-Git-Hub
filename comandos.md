git init: Inicializa un repositorio 
git clone <https://name-of-the-repository-link>: Clona un repositorio ya existente a la computadora en la direccion donde se encuentre el terminal
git branch <branch-name>: Crea una nueva rama con el nombre especificado
git push -u <remote> <branch-name>: Empuja la rama creada al repositorio remoto (Por general github)
git branch o git branch --list: Lista todas las ramas existentes en el repositorio local
git branch -d <branch-name>: Borra la rama en el repositorio local
git checkout <name-of-your-branch>: Permite visitar otra rama del repositorio local
git checkout -b <name-of-your-branch>: Permite crear una nueva rama en base a la que te encuentras localmente y cambiar a esta en un solo paso
git status: Muestra el estado de los archivos existentes
git add <file>: Agrega el archivo especificado para ser commiteados
git add -A o git add .: Agrega todos los archivos para ser commiteados
git commit -m "commit message": Realiza el commit de los cambios agregados con un mensaje escrito
git push <remote> <branch-name>: Envia los cambios del repositorio local a una rama del repositorio remoto (Debe tener commits)
git push --set-upstream <remote> <name-of-your-branch> or git push -u origin <branch_name>: lo mismo de arriba pero no debe necesita tener commits
git pull <remote>: Permite copiar los cambios de la rama existente en el repositorio remoto al repositorio local
git revert <commit-id>: Permite revertir los cambios actuales a un commit previo
git merge <branch-name>: Permite unir los cambios de 2 ramas, en caso de conflicto de debe corregir de manera manual
git rebase <branch-name>: Permite poner los cambios de la rama actual en la cabeza de los cambios de la rama ingresada en el comando
git reset: este si les dejo que revisen que tiene muchos usos y les voy a confundir xd
