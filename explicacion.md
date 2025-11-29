crear un repositorio local de git


rama principal de git: main (main)


git init (comando que inicializa el repositorio local)
ctrl + J + Enter
<!-- para seguimiento git add index.html -->


git funciona en ramas, en un codigo base(tronco) en sus ramas hay versiones 
<!-- esto renombra la rama principal de master a main -->
git branch -M main


# añadir origen remoto a donde vamos a subir nuestro código
git remote add origin https://github.com/acostamr97-max/repo-de-prueba.git

# enviar el ultimo commit a la rama principal 
git push -u origin main




<!-- una vez ya subido el repo, si se quiere hacer algun cambio hay que escribir 
git add.
git commit -m "mensaje"
git push  -->