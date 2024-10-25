# Método 3: Fork y Clonado

En este método, utilizamos la función de **Fork** de GitHub para copiar un repositorio en nuestra cuenta, luego lo clonamos para trabajar en él localmente y realizar cambios.

## Pasos

1. **Hacer Fork del Repositorio en GitHub**
    - Ve a la URL del repositorio original: [https://github.com/danielcastelao/pruebasReadme.git](https://github.com/danielcastelao/pruebasReadme.git).
    - Haz clic en el botón `Fork` en la parte superior derecha de la página para crear una copia del repositorio en tu cuenta de GitHub.

2. **Clonar el Fork en tu Máquina Local**
    - Clona el repositorio forkeado en tu cuenta de GitHub en una nueva carpeta llamada `repo_metodo3`:

      ```bash
      git clone https://github.com/MI_USUARIO/pruebasReadme.git repo_metodo3
      ```

3. **Acceder al Directorio Clonado**
    - Entra en el directorio del repositorio clonado:

      ```bash
      cd repo_metodo3
      ```

4. **Realizar Cambios y Hacer Commit**
    - Realiza los cambios que desees en los archivos del repositorio.
    - Añade los cambios a Git y haz un commit:

      ```bash
      git add .
      git commit -m "Documentación del proceso en Método 3"
      ```

5. **Subir los Cambios al Repositorio Forkeado en GitHub**
    - Sube los cambios al repositorio en GitHub:

      ```bash
      git push origin main
      ```

   Ahora tienes tu propio fork del repositorio original, donde puedes realizar cambios y subirlos a tu cuenta de GitHub.
