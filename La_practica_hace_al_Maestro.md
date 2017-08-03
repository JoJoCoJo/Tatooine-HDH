## La práctica hace al Maestro...  :mortar_board:

![OcktoJedi](https://s-media-cache-ak0.pinimg.com/originals/dc/ef/3a/dcef3abedf0e0761203aaeb85886a6f3.jpg)

1. Crea un listado de todo los pasos que toma hacer un flujo completo de GIT, este listado deberá ser mas un tutorial que un listado. Acompáñalo con imágenes, y recuerda que MarkDown tiene una manera para que se pueda escribir código en el.

  * Para empezar un proyecto en GIT con almacenamiento en GitHub, debemos en entrar a [GitHub](https://github.com/), una vez iniciado sesión, en la parte superior derecha, nos aparecerá a lado de nuestra foto de perfil un icono de :heavy_plus_sign:, al cuál al darle click desplegará un menú, donde debemos seleccionar la primera opción "New repository".

    <p align="center">
      <img src="images/TutoGit-1.png" />
    </p>

  * Se motrará la siguiente pantalla, en la cuál una vez llenado los datos, podremos proceder a usar la terminal

    <p align="center">
      <img src="images/TutoGit-2.png" />
    </p>

  * Primero se debe de asignar un nombre y descripción al nnuevo repositorio.

    <p align="center">
      <img src="images/TutoGit-3.png" />
    </p>

    * Después seleccionar el tipo de repositorio que se va a crear, los cuales pueden ser:

      <p align="center">
        <img src="images/TutoGit-4.png" />
      </p>

      * Público: Da al repositorio la propiedad como su nombre lo indica que sea público y cualquier usuario con cuenta de GitHub pueda acceder / clonar / descargarlo. P.D. Esta opción es gratis.

      * Privado: Brinda la capacidad de definir quienes pueden ver, aportar, descargar / clonar el repositorio para poder ayudar en el trabajo del proyecto añadiendo colaboradores que cuenten con una cuenta de GitHub. P.D. Esta opción es de paga.

  * Posteriormente se puede marcar la opción de crear un repositorio con un archivo README.md

    <p align="center">
      <img src="images/TutoGit-5.png" />
    </p>

    * y seleccionar si se crea el archivo .gitignore el cual dependiendo del proyecto o el lenguaje en el que se vaya a trabajar cambia la creación por defecto del archivo.

      <p align="center">
        <img src="images/TutoGit-6.png" />
      </p>

    * Por último se puede seleccionar una licencia, la más común es la "MIT License" la cual no da crédito de lo que este en el proyecto y que se debe de reconocer a él/los autores del mismo en caso de hacer uso del proyecto en cuestión o modificaciones al mismo implementándolo en algún otro proyecto.

      <p align="center">
        <img src="images/TutoGit-7.png" />
      </p>

  * Por último (para terminar de crear el repositorio) se debe presionar el botón "Create repository", y tendremos el repositorio creado.

    <p align="center">
      <img src="images/TutoGit-8.png" />
    </p>

  * Al terminar la acción nos mostrará la página principal de repositorio, donde:

    <p align="center">
      <img src="images/TutoGit-9.png" />
    </p>

    1. Primero al dar click en el botón "Clone or download" nos desplegará un menú.

    2. Y en seguida podremos copiar directamente el link del repositorio.

  *  Una vez copiado / obtenido el link del repositorio, podemos clonar / descargar el proyecto en nuestras PC / laptops con la siguiente instrucción:

  ```
  git clone git@github.com:JoJoCoJo/shiny-rotary-phone.git
  ```
  * En la terminal obtendríamos el siguiente resultado:

    <p align="center">
      <img src="images/TutoGit-10.png" />
    </p>

    Y ya con eso tendríamos el proyecto en nuestra PC / laptop listo para trabajar. Si ejecutamos los siguientes comando en la terminal:

    ```
    shiny-rotary-phone/
    ls
    ```

  * Podremos ver los archivos / carpetas que acabmos de descargar / clonar del repositorio que acabamos de crear en GitHub.

    <p align="center">
      <img src="images/TutoGit-11.png" />
    </p>

  * Modificando el archivo de LICENSE agregando más autores, podremos proseguir con el tutorial.

    Para abrir el archivo sólo tendremos que escribir desde la terminal la siguiente intrucción:

      ```
      atom .
      ```

    Con la cuál nos abre en este caso Atom con el proyecto listo para empezar a trabajar.

    <p align="center">
      <img src="images/TutoGit-12.png" />
    </p>

    <p align="center">
      <img src="images/TutoGit-13.png" />
    </p>

    Seleccionamos nuestro archivo LICENSE y agregamos autores y como podremos observar, el mismo editor nos indica cuando no hemos guardado cambios y estamos haciendo modificaciones al archivo.

    <p align="center">
      <img src="images/TutoGit-14.png" />
    </p>

    Es hasta que guardamos cambios, se pone normal el icono para cerrar el archivo. Y también se notará el cambio del color del nombre del archivo.

    <p align="center">
      <img src="images/TutoGit-15.png" />
    </p>

  Cuando terminamos de trabajar en nuestros archivos podemos pasar a la terminal para subir nuestros archivos al repositorio de GitHub.

    1. Para empezar escribimos y ejecutamos la instrucción en la terminal:

    ```
    git status
    ```
    La cuál nos mostrará el siguiente resultado:

    <p align="center">
      <img src="images/TutoGit-16.png" />
    </p>

    Como notaremos, nos dice que archios se han tenido una modificación Y nos recomienda ejecutar instrucciones como "git add" que es la que acontinuación usaremos.

    ```
    git add LICENSE
    git status
    ```
    Podemos observar en la terminal que no pasa nada al ejecutar la primera instrucción, pero cuándo ejecutamos la segunda ya nos marca en otro color el estatus actual.

    <p align="center">
      <img src="images/TutoGit-17.png" />
    </p>

    Ahora podemos proceder a hacer el "commit" de los archivos con la siguiente instrucción:

    ```
    git commit -m "Commit Message"
    ```

    Después nos mostrará este resultado en la terminal.

    <p align="center">
      <img src="images/TutoGit-18.png" />
    </p>
