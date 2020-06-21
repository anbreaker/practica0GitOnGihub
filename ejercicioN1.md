## Ejercicio 1

Se deberá crear un repositorio y realizar una serie de operaciones **desde la consola de
comandos** sobre el mismo para posteriormente subir el repositorio a Github.
Se deberá entregar a través del formulario de prácticas indicando la URL del repositorio. En el
repositorio, deberá existir un archivo readme.md con las respuestas a las siguientes preguntas:

- **¿Qué comando utilizaste en el paso 11? ¿Por qué?**

  - git reset --hard HEAD~1
  - Este comando deshace el último commit y lo que había en mi working copy
    volviendo a como estaba antes. El staging area queda vacío.

- **¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

  - Tenia un par de opciones:
    - Como realice la subida al repositorio de git, si realizara un pull bajaria el cambio realizado desde el repositorio remoto, o si realizara un git reflog podria navegar hasta este estado.
  - Emplee esta segunta técnica de la siguiente forma:
    - `git reflog` --> Localice el hash que correspondia
    - `git checkout #hashDelCommit`
    - Regresan los cambios efectuados.

- **El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

  - git merge master -m '13) Hacer un merge con ‘master’ (styled absorbe a master)'
    Merge made by the 'recursive' strategy.
    ejercicioN1.md | 33 +++++++++++++++++++++++++++++++++
    1 file changed, 33 insertions(+)
    create mode 100644 ejercicioN1.md

  - Este merge no causo conflictos, se hizo la insercion del archivo donde estoy respondiendo las preguntas de la práctica y conservo sus cambios en git-nuestro.md

- **El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

  - Si hubo conflictos pues los cambios en el archivo git-nuesto.md de las distintas ramas eran totalmente diferentes.
  - Se modificaron la mayoría de lineas entre los archivos.

- **El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
- **¿Qué comando o comandos utilizaste en el paso 25?**
- **El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
- **¿Qué comando o comandos utilizaste en el paso 27?**
- **¿Qué comando o comandos utilizaste en el paso 28?**
- **¿Qué comando o comandos utilizaste en el paso 29?**
- **¿Qué comando o comandos utilizaste en el paso 30?**
- **¿Qué comando o comandos usaste en el paso 32?**
- **¿Qué comando o comandos usaste en el punto 33?**
