# Examen Primer Parcial



#### 1. ¿Qué es y para qué sirve Visual Studio Code?
Es un editor de código. Sirve para escribir y editar código, depurar, ejecutar terminal, manejar control de versiones (Git) y añadir funcionalidades mediante extensiones.

#### 2. ¿Qué es y para qué sirve la Terminal de Comandos?
La terminal de comandos es una interfaz de texto donde se ejecutan comandos del sistema y herramientas.

#### 3. ¿Qué es y para qué sirve Markdown?
Markdown es un lenguaje de marcado ligero para escribir texto con formato (encabezados, listas, código, enlaces)

#### 4. ¿Qué es y para qué sirve Git?
Git es un sistema de control de versiones distribuido que permite registrar cambios en el código, crear ramas, volver a versiones anteriores y colaborar con otros sin perder historial.

#### 5. ¿Qué es y para qué sirve GitHub?
GitHub es un servicio en la nube para git repositorios Git. Se usa para compartir código, colaborar con pull requests, issues, revisar historial y desplegar documentación pública.

#### 6. ¿Para qué sirven los siguientes comandos: pwd, whoami, touch, mkdir, cp, mv, ls, clear, cd y rm?

pwd:muestra la ruta del directorio actual

whoami:muestra el usuario actual

touch:crea un archivo vacío o actualiza su fecha

mkdir: crea un directorio

cp: copia archivo o carpeta

mv: mueve o renombra

ls: lista archivos

clear: limpia la pantalla de la terminal

cd: cambia de directorio

rm: elimina archivo

#### 7. ¿Qué significan los siguientes caracteres en la terminal: ~, /, ., .., ?

~: representa el directorio home del usuario (ej: /home/usuario o C:\Users\usuario). Ej: cd ~.

/: en Unix/Linux es el separador de rutas y la raíz del sistema (/). En rutas Windows se usa \, pero / también se acepta en muchas herramientas.

.: directorio actual.

..: directorio padre (subir un nivel). 

?: comodín que representa un sólo carácter en patrones de búsqueda.

#### 8. ¿Cómo se inicializa un repositorio en Git?

Se inicializa con:

git init

git add .

git commit -m "Primer commit"

#### 9. ¿Cómo creas un repositorio en GitHub?

Por la web: GitHub - New repository - nombre -  README - Create repository.
Después copia la URL del repo para vincularla con tu local.

#### 10. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?

En la consola:

git remote add origin - "link de git hub"
git push -u origin main


#### 11. ¿Cuál es el flujo básico de trabajo en Git y GitHub? Explica la secuencia de comandos.

El flujo básico es:

Hacer cambios en los archivos.

Agregar cambios al área de preparación.

Confirmar los cambios con un mensaje descriptivo.

Subir al repositorio remoto.

Ejemplo:

git status
git add .
git commit -m "Mensaje descriptivo"
git pull --rebase origin main
git push origin main

#### 12. ¿Para qué sirve el archivo .gitignore?

El archivo .gitignore indica a Git qué archivos o carpetas no deben ser rastreados ni subidos al repositorio.

#### 13. ¿Cuál es el propósito de una rama?

Una rama permite trabajar de manera independiente, sin afectar nuestra rama principal

#### 14. ¿Qué es una fusión?

Una fusión (merge) combina los cambios de una rama con otra, haciendo el trabajo uno con la rama.

#### 15. Explica los diferentes tipos de fusión que existen.

- Fast-forward: mueve el puntero de la rama principal sin crear un commit nuevo.

- Manual-Merge: esta es para hacer la fusion de manera manual y resolver conflictos de duplicacion.

#### 16. ¿Cómo puedes ver el historial de tu repositorio?

Con el comando:

git log

#### 17. ¿Cuál es el propósito de una etiqueta?

Una etiqueta (tag) marca un punto específico en el historial, como una versión estable del proyecto.

