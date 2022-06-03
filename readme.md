# Comandos de Git

- Crear un directorio:

    ```
    mkdir nombre_directorio
    ```

- Crear un repositorio local:

    ```
    git init nombre_repositorio
    ```

- Clonar un repositorio remoto a local:

    ```
    git clone url_repositorio
    ```

- Crear un commit:

    1.1.1 Añadir un fichero al staging area:

        git add nombre_fichero.extension


    1.1.2 Añadir todos los ficheros modificados o creados al staging area:

        git add .

    \* Para eliminar un fichero del staging area antes de hacer el commit:

        git rm --cached nombre_fichero.extension

    1.2 Hacer el commit con los cambios:

        git commit -m "Título del commit"

    2 Hacer directamente el commit (solo para ficheros ya existentes en ambos repositorios):

        git commit -am "Título del commit"

- Ver la situación de los ficheros:

    ```
    git status
    ```

- Ver el historial de commits:

    ```
    git log
    ```

- Configurar el repositorio:

    ```
    git remote add <nombre> <url>
    ```

    \* Otra forma de hacerlo es seguir las instrucciones del repositorio creado en GitHub

- Subir los cambios al repositorio remoto:

    ```
    git push <nombre>
    ```

- Asociar el repositorio local al remoto:
    
    \* Seguir las instrucciones del repositorio creado en GitHub

- Consultar los repositorios remotos asociados:

    ```
    git remote -v
    ```
- Bajar cambios de remoto a local:

    ```
    git pull origin main
    ```