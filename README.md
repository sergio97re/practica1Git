# practica1Git
1.- git reset HEAD~ + git restore git-nuestro.md. Si ejecutamos solo el primer comando, únicamente deshacemos el commit, para perder los cambios en el working 
copy ,es necesario ejecutar el segundo comando git restore git-nuestro.md

2.- git reset --hard <ID COMMIT>. Hay que ejecutar este comando para poder recuperar el commit deshecho.

3.- git merge main. No se creó ningún conflicto.

4.- git checkout styled -> git merge htmlify. Sí, causó conflictos, ya que había varias líneas distintas en el archivo de cada rama.

5.- git checkout main -> git merge styled. No generó ningún conflicto.

6.- git graph

7.- git merge --no-ff title. No podría ser fast-forward por Git no puede aplicar los cambios directamente desde la rama en la que se encuentra hacia la rama 
que quiere fusionar.

8.- git reset --hard HEAD~

9.- git checkout .

10.- git branch -D title

11.- git reflog -> git merge b9eaf3f

12.- git reset e733290

13.- git reset 2cbcf97
