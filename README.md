## SPRINT-2

### 01-GIT

¿Qué significan y para que sirven las siguientes palabras clave?

- local: La traducción al español es "local". Hace referencia a que trabajamos con un repositorio local de GIT, el cual podemos manipular y/o crear archivos paara posteriormente poder subir los cambios al origin.

- remote: La traducción al español es "remoto". Con este comando podemos ejecutar instrucciones que afecten directamente al origen.

- init: No encontre una traducción al español como tal, pero da a entender que es una abreviación de "initial", que traducido al español es "inicial", se usa generalmente cuando se va a crear un proyecto nuevo con GIT.

- clone: La traducción al español es "clonar". En conjunto con la palabra git, la instrucción "git clone linkejemplo.git" nos permite clonar o descargar un repositorio desde GitHub para poder usarlo, analizarlo, contribuir o respaldarlo en nuestra PC.

- add: La traducción al español es "agregar". En combinación con la palabra git, la instrucción "git add archivo" nos permite agregar y pasar un archivo que estaba en estado UNTRACKED al estado STAGED y TRACKED cuando terminamos de trabajar o modificar y poder llevar el registro de sus cambios.

- commit: La traducción al español es "cometer". Cuando escribimos la instrucción "git commit -v" o "git commit -m 'mensaje del commit o cambios que se le hicieron al o los archivo(s)'" es donde se registran como tal los cambios o un 'checkpoint' donde podemos regresar en el tiempo y se debe de comentar preferentemente en inglés.

- push: La traducción al español es "empujar". Cuando usamos la instrucción "git push origin branchEjemplo" se suben al servidor de preferencia (GitHub, BitBucket, etc...), todos los cambios realizados en la rama de los archivos que se crearon o modificaron durante el trabajo realizado.

- pull: La traducción al español es "jalar". Se utiliza de la siguiente manera "git pull origin branchEjemplo" para poder descargar/bajar los cambios que sean realizado a la rama donde queremos y podamos trabajar con la versión más reciente.

- merge: La traducción al español es "unir". Ya cuando tenemos todos los cambios listos en estado COMMITTED y estan subidos en la plataforma, en este caso GitHub, poder combinar los cambios de las ramas y poder dejar sólo una con las cual poder seguir trabajando.


+ Nombra las fases de GIT y que pasa en cada una de ellas...
  + UNTRACKED: Es el estado que se le da a los archivos de los cuales aun no se lleva el registro en el proyecto.
  + TRACKED: Es el estado que se le da a los archivos de los cuales se monitorea la actividad.
  + MODIFIED: Es el estado que se le da a los archivos a los cuales se han modificado y guardados cambios sin haber hecho el COMMIT, pero después de haber hecho el ADD y se registran los cambios hasta que se ejucuta la instrucción COMMIT.
  + STAGED: Es el estado que se le da a los archivos de los cuales ya se acabron de modificar, pero que aun no se procede a hacer el COMMIT como tal, ya que se sigue trabajando sobre otros archivos.
  + COMMITTED: Es el estado que se le da a los archivos los cuales ya están listos para poder ejecutar la instrucción PUSH, la cual respalda los archivos en el servidor, tal como GitHub.

+ ¿Que son las cosas que NO se deben hacer en un repositorio de GIT?
  + Tener muchas ramas, sobre todo las que ya no se usen.
  + Subir los cambios directo a la rama master.
  + No checar el status.


+ ¿A que año debía volver Marty McFly para reestablecer la linea de tiempo?
    + 1985
