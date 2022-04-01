## Tutorial de git para principiantes

1. git init (iniciar un nuevo proyecto)
2. git status para ver el estado del git
3. git add tutorial.md o git add . (si ponemos varios archivos )archivo.html (subir un archivo)
4. git commit -m "agregar un comentario del archivo a subir"
5. git log para ver el estado actual del git y ver los commits y el autor
6. git diff en caso de modificar algo en el archivo ver que se modifico
7. git checkout -- tutorial.md en caso q queramos volver al estado anterior de contenido q teniamos , eso en caso que no hayamos dado un git add..
8. en caso que hayamos subido con git add. en ese caso pondriamos
   git reset HEAD tutorial.md , despues podemos git status y vemos q esta como si no lo hibieramos subido aun y despues ponemos git checkout -- tutorial.md para recien ir al estado anterior que queriamos
