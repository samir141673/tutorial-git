## Tutorial de git para principiantes

## Introduccion

git en nuestro archivo crea una carperta llamada "stanging" y otra .git(repositorio)
Inicialmente el archivo esta como untrack
cuando pondemos git add tutorial.md entra al staging y se convierte en track y cuando ponemos git commit -m "comentario" ingresar al repositori .git
Un commit es una version

## Rama princial master

La rama master es la version oficial , y creamos mas versiones y la version actual se llama la rama HEAD , ojo la rama master es la version oficial de nuestro proyecto

# recomendacion

de la version uno de la rama master nosotros debemos de sacar una copia de la version uno , por convencion lo llamamos ramma dev y de dev podemos sacar mas ramas y versiones, como modo prueba, una vez terminado podemos ingresarlo en la rama oficial , la rama master como una version definitiva

1. git init (iniciar un nuevo proyecto)
2. git status para ver el estado del git
3. git add tutorial.md o git add . (si ponemos varios archivos )archivo.html (subir un archivo)
4. git commit -m "agregar un comentario del archivo a subir"
5. git log --oneline o solo git log (mas detallado) para ver el estado actual del git y ver los commits y el autor
6. git checkout codigo-commit de esta forma volvemos a la version anterior
7. git show nos muestra mas detallado los commit
8. git reset codigo commit --hard va eliminar todos las versiones, o commit anteriores

## Ramas en Git

1. git branch para ver todas las ramas q tenemos y si vemos que nos sale un asterisco a su lado , esto nos quiere decir q estamos parados en dicha rama
2. git branch nueva_rama para crear una nueva rama
3. git checkout nueva_rama cambiamos a la nueva rama , ahora nuestro HEAD esta en nueva_rama en donde podemos poner los commit (versiones que queramos) pero si volvemos a la rama master veremos q los archivos creados en la nueva rama desaparecen porq cambiamos de rama
4. si queremos traer los cambios q hubo en la rama nueva_rama , lo invocamos desde el master para q se integre en la rama master
5. git merge nueva_rama de esta forma integramos los cambios q hibo en la nueva_rama , despues de hacer un git log --oneline , podemos ver q git master esta compartiendo la cabezera con la nueva_rama

## ojo , podemos voler y seguir trabajando en la rama nueva_rama

para hacer un solo commit en todos los archivos modificados podriamos poner esto git commit -am "mensaje"

# Introduccion a Repositorios Remotos con Git y Github

1. Creamos un nuevo repositiorio en github
2. Despues de llevar los datos ponemos crete repository
3. Ahora vamos a enlazar el repositorio local con el remoto
4. ingregamos a git y dentro de la carpeta pegamos el
   git remote add origin https://github.com/samir141673/tutorial-git.git
5. despues pegamos elgit push -u origin main
6. refrescamos la pagina , y vamos a ver todos nuestros repositorios remotos en github
