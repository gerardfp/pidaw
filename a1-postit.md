# 📝 Proyecto Post-it Board
## Objetivo

El objetivo de esta práctica es trabajar en equipo para desarrollar una aplicación web en entorno cliente utilizando HTML, CSS y JavaScript, aplicando buenas prácticas de colaboración en GitHub (Issues, Projects, Pull Requests y ramas).
El resultado será un tablero de notas tipo post-it, donde el usuario pueda crear, visualizar, editar y eliminar notas, con persistencia en el navegador mediante `localStorage`.

Se puede ver una demo **ORIENTATIVA** de la app a realizar aquí: https://gerardfp.github.io/pidaw/postit/

Duración estimada: 3 horas.

## Instrucciones
### 1. Formación de equipos

Los grupos deberán ser de 3 a 4 personas.
Es importante que el grupo se comunique constantemente para planificar y organizar la distribución de las tareas de manera equitativa.

### 2. Desarrollo del proyecto

Se debe desarrollar una página web interactiva que permita gestionar notas tipo post-it con las siguientes funcionalidades:

* Añadir una nueva nota a partir de un formulario.

* Mostrar todas las notas en un tablero con diseño de post-its de colores.

* Guardar automáticamente las notas en `localStorage`.

* Recuperar las notas al recargar la página.

* Editar directamente el contenido de una nota en el tablero.

* Eliminar una nota con un botón en la propia tarjeta.

#### Requisitos técnicos:

* HTML: estructura de la aplicación (formulario + tablero).

* CSS: diseño atractivo, estilo de post-it con colores y sombras.

* JavaScript: manipulación del DOM, eventos, persistencia en `localStorage`.

#### Trabajo en GitHub

El trabajo colaborativo se gestionará con las herramientas de GitHub:

* **Issues**: cada funcionalidad o tarea (HTML, estilos, añadir notas, editar, eliminar, persistencia) debe estar descrita en un Issue. Cada miembro del equipo debe asumir al menos un Issue.

* **Projects**: organizar las tareas en un tablero con columnas (por ejemplo: "Por hacer", "En progreso", "Hecho") e ir moviéndolas según el avance.

* **Ramas** y **Pull Requests**:

    * Cada tarea o funcionalidad debe desarrollarse en una rama distinta (ejemplo: feature-css, feature-add-note).

    * Al terminar, se debe crear un Pull Request hacia la rama principal (main).

    * Otro miembro del equipo debe revisar y aprobar el código antes de fusionarlo.

* **Commits**: deben ser frecuentes y con mensajes claros y descriptivos (por ejemplo: feat: añadir función para guardar notas en `localStorage`).

* **Documentación**: el repositorio debe incluir un archivo `README.md` con:

    * Descripción del proyecto.

    * Pasos para ejecutarlo en local (abrir el HTML en un navegador).

    * Lista de funcionalidades implementadas.