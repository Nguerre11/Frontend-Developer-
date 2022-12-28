*/Este archivo busca evidenciar mi proceso de aprendizaje mediante workflow que considero importantes a recordar.
Mi metodologia se basa en el high order learning implicas dentro de las tecnicas de codificacion para el aprendizaje eficiente.
Mi metodologia se alimenta de la combinacion entre los workflow  y los sistemas de organizacion que realice a mano y que pueden encontrar en la carpeta resourses to learn.
No tome esta documentacion como verdad absoluta, este es solo mi resultado que me ayudara con el pasar del tiempo a ver como he ido mejorando. */

1. Cambiar rama master a main 
Primero, asegúrate de tener las últimas actualizaciones de la rama "master" ejecutando el comando git pull origin master. Esto asegurará que tienes todas las últimas actualizaciones en tu repositorio local.

Cambia a la rama "main" ejecutando el comando git checkout -b main. Esto creará una nueva rama llamada "main" y cambiará a ella.

Empuja la rama "main" al repositorio remoto ejecutando el comando git push -u origin main. Esto creará la rama "main" en el repositorio remoto y la configurará para rastrear la rama local "main".

Elimina la rama "master" del repositorio remoto ejecutando el comando git push origin --delete master. Esto eliminará la rama "master" del repositorio remoto.

Establece la rama "main" como la rama principal en el repositorio remoto ejecutando el comando git push origin main:refs/heads/main. Esto actualizará la rama principal en el repositorio remoto a "main".

Finalmente, actualiza el repositorio local para rastrear la rama "main" como la rama principal ejecutando el comando git symbolic-ref refs/remotes/origin/HEAD refs/remotes/origin/main. Esto actualizará el repositorio local para rastrear la rama "main" como la rama principal.
/* */