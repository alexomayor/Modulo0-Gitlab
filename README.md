#Mi proyecto

1. Creo el repositorio local.
   1.1. Abro Git Bash.
   1.2. Navego hasta el directorio del repositorio local.
   1.3. Inicializo el repositorio local con "git init".
2. Creo un repositorio en GitHub y conecto ambos.
   2.1. Accedo a github.com/ y creo un nuevo repositorio remoto, publico, seleccionando un nombre (NewRep-LabGit)..
   2.2. Copio la URL del repositorio remoto.
   2.3. En el terminal, desde el directorio del repositorio local, uso "git remote add origin <URL-recien-copiada>".
3. Creo la nueva rama.
   3.1. En Visual Studio Code, creo un nuevo archivo en el repositorio local (README.md).
   3.2. Ejecuto "git add ." para anhadir el nuevo archivo al stagging.
   3.3. Ejecuto "git commit ." para hacer el primer commit.
   3.4. Ejecuto "git push" para subir el nuevo archivo al repositorio en remoto.
   3.5. Creo una nueva rama mediante "git checkout development".
   3.6. Genero cambios en README.
4. Hago merge.
   4.1 Cambio a la rama "main" con "git checkout main".
   4.2 Fusiono ambas con "git merge development".
5. Realizo push mediante "git push".
