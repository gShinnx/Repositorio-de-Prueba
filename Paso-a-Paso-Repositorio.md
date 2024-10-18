# Paso a Paso

## Notas del paso a paso de lo que fuí haciendo en este repositorio, escribiré lo comandos y todo lo que vaya a usar.



# Pasos:


1. Lo primero que hice fue, en GitHub, crear mi repositorio llamado "Repositorio-de-Pruebas".
2. Creé una carpeta con el nombre de "Pruebas 1" y la abrí con VSCode.
3. En VSCode en la terminal de comandos, inicié el repositorio con __git init__ y después creé este archivo y el archivo de README.md.
4. Despues los agregué al escenario, los puedo agregar tanto con el comando __git add .__ (el cuál agrega todos los archivos al repositorio) como también agregandolos por separado de esta forma __git add README.md__ y __git add Paso-a-Paso-Repositorio.md__.
5. Realicé el primer commit, para hacerlo use este comando __git commit -m "---"__ (Cabe aclarar que es -M porque es el primer commit que se realiza de nuevos archivos, si fuesen en archivos ya en seguimiento seria -AM)(Entre comillas va el texto que queremos para identificar a nuestro commit)
6. Le cambié el nombre a mi rama principal de master a main, usé este comando __git branch -m main__.
7. Lo siguiente que hice fue conectar este repositorio, este repositorio con el repositorio remoto de GitHub, al principio dijimos que creamos un repositorio en GitHub, al crearlo, nos dió una serie de pasos y un comando con un link, este comando es __git remote add origin https://github.com/gShinnx/Repositorio-de-Prueba.git__, luego de usar este comando, hay otro que usaremos, el cual es __git push -u origin main__, el cual lo que hace es insertar la información a GitHub(Push = Insertar) estos dos comandos son super importantes porque con ellos conectaremos ambos repositorios entre sí.
