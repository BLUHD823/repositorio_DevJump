# repositorio_DevJump:

En la página de GitHub le doy a crear repositorio.

Luego para tener el repositorio en mi computadora lo clono con el comando 'git clone <link del repositorio>'

# Commit inicial:

En el archivo Read.me escribo todos los comandos que utilicé

Comandos utilizados:

cd

mkdir

list

touch

git add .

git commit -m 

git push

Para guardar los cambios de ese archivo utilizo el comando 'git add .' y para hacer commit ' git commit -m "commit inicial" '

# Push inicial:

Para subir los archivos al repositorio en GitHub tengo que utilizar el comando ' git push '

# Ignorar archivos

Para lograr que git ignore los archivos que yo quiero, tengo que lograr usar los comandos de gitignore

Primero crea un archivo de txt con el siguiente nombre 'touch .gitignore'

Luego tengo que crear un fichero 'touch privado.txt' y una carpeta 'mkdir "carpeta privada"'

Para lograr que Git ignore esos archivos, tengo que ir al archivo .gitignore y escribir los nombres de esos mismos archivos '/privado.txt'

#Añadir fichero:

Crear el fichero 1 'touch 1.txt'

Agregarlo con con los comandos 'git add .' y luego 'git commit -m "creación del fichero 1"'

#Crear una rama v0.2:

Para crear una rama tenemos que usar el comadno 'git branch <nombre de la rama>'



Luego creamos una carpeta 'mkdir "carpeta de trabajo"' 
  
Desde la consola nos ubicamos en la carpeta y creamos el archivo 'touch 2.txt'
  
Para poder agregarlos tenemos que cambiar de rama y por eso usamos el comando 'git cheakout <nombre de la rama>' para cambiar al branch v0.2

#Crear rama remota
  
Una vez en la otra rama para que la carpeta se guarde en tenemos que usar los comandos 'git add .' y 'git commit -m "creación de fichero"'
  
#Merge directo

Primero para posicionarse en la rama principal hay que usar el comando 'git checkout main'
  
Segundo, para hacer el merge con las dos ramas hay que usar el comando 'git merge v0.2'
  
#Merge con conflicto
  
Para evitar los conflictos en la rama main hay que cambiar el archivo 1.txt y escrbir "Hola"
  
Luego cambiar de ramas 'git checkout v0.2' y en el 1.txt agregar "Adios"
