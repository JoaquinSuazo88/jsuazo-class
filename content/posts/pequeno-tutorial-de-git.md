+++
title = 'Pequeno Tutorial De Git'
date = 2024-07-26T14:10:13-04:00
draft = false
+++


## Pequeño Tutorial de Git: Controla tu código como un profesional

### ¿Qué es Git?

Imagina que estás escribiendo un libro. Cada vez que avanzas, guardas una copia. Si cometes un error, puedes volver a una versión anterior. Git hace esto mismo, pero con código. 

Es un **sistema de control de versiones distribuido**, lo que significa que cada desarrollador tiene una copia completa del historial del proyecto en su computadora. Esto permite trabajar sin conexión y facilita la colaboración en equipo.

### Un Poco de Historia

Creado por Linus Torvalds (el mismo de Linux) en 2005, Git nació de la necesidad de un sistema de control de versiones rápido y eficiente para el desarrollo del kernel de Linux. Su diseño innovador lo popularizó rápidamente, convirtiéndolo en el estándar de la industria.

### Comandos Más Usados:

* **git init:** Crea un nuevo repositorio Git en la carpeta actual.
* **git clone <URL>:** Copia un repositorio remoto a tu máquina local.
* **git add <archivo>:** Agrega un archivo al área de preparación (staging area), listo para ser "commiteado".
* **git commit -m "Mensaje descriptivo":** Guarda los cambios del área de preparación en el historial del repositorio.
* **git status:** Muestra el estado de los archivos (modificados, agregados, etc.).
* **git push:** Envía los "commits" locales al repositorio remoto.
* **git pull:** Descarga los cambios del repositorio remoto y los integra en tu rama local.
* **git branch <nombre_rama>:** Crea una nueva rama.
* **git checkout <nombre_rama>:** Cambia a la rama especificada.
* **git merge <nombre_rama>:** Fusiona la rama especificada con la rama actual.
* **git log:** Muestra el historial de "commits" en la rama actual.

### Flujo de Trabajo Básico:

1. **Clonar o crear un repositorio:** `git clone <URL>` o `git init`.
2. **Crear una rama para tu nueva funcionalidad:** `git checkout -b <nombre_rama>`.
3. **Hacer cambios en los archivos.**
4. **Agregar los archivos modificados al área de preparación:** `git add <archivo>` o `git add .` para agregar todos.
5. **Confirmar los cambios con un mensaje descriptivo:** `git commit -m "Mensaje descriptivo"`.
6. **Repetir los pasos 3 a 5 hasta que la funcionalidad esté completa.**
7. **Cambiar a la rama principal:** `git checkout main`.
8. **Actualizar la rama principal con los cambios del remoto:** `git pull`.
9. **Fusionar tu rama con la rama principal:** `git merge <nombre_rama>`.
10. **Resolver cualquier conflicto de fusión que pueda surgir.**
11. **Enviar los cambios al repositorio remoto:** `git push`.

### Recursos Adicionales:

* **Documentación oficial de Git:** [https://git-scm.com/doc](https://git-scm.com/doc)
* **Tutorial interactivo de Git:** [https://try.github.io/](https://try.github.io/)
* **Libro Pro Git (gratuito):** [https://git-scm.com/book/es/v2](https://git-scm.com/book/es/v2)

Este tutorial cubre lo básico de Git. A medida que te familiarices con él, descubrirás comandos y flujos de trabajo más avanzados que te ayudarán a colaborar en proyectos de desarrollo de software de forma más efectiva.