# Curso de Git / GitLLab

- CONTROL DE VERSIONES CON GITLAB AF 82897 - GR 85303
- Duración: 16 horas
- Modalidad: On-line
- Fechas: 11/11/2025 - 14/11/2025
- Horario: 9:30 - 13:30

Formador: Alejandro Cerezo
<alce65@hotmail.es>

## Contenidos

- Introducción a Git y GitLab
  - Fundamentos del control de versiones.
  - Conceptos básicos de Git.
  - Características principales de GitLab.
- Configuración inicial y gestión de repositorios
  - Creación y clonación de repositorios
  - Configuración de SSH Y HTTPS
  - Organización y gestión de proyectos en GitLab
- Operaciones básicas con Git
  - Realización de commits y revert
  - Trabajo con ramos (branching)
  - Resolución de conflictos en merges
- Flujos de trabajo en equipo
  - Flujos de trabajo basados en GitLab Flow.
  - Uso de merge requests y revisión de código
  - Gestión de issues y etiquetado.
- Automatización y CI/CD Básico en GitLab
  - Introducción a pipelines en GitLab.
  - Configuración básica de GitLab CI/CD.
  - Integración de pruebas automáticas.
- Buenas prácticas y resolución de problemas
  - Estrategias para un historial limpio y ordenado.
  - Manejo de errores comunes en Git.

Desarrollo del curso en la carpeta Oficial -> [repo](https://github.com/IconoTC/Control-de-versiones-con-GitLab-AF-82897---GR-85303)

## Desarrollo del curso

<!-- ### Día 1 (Martes 11 Noviembre 2025)

- Presentación profesor / alumnos
- Introducción: Qué es un SCV y qué un SCV distribuido
- IDE / Editor de código: Visual Studio Code (VSC)
- Instalación de Git
- Terminales
- Configuración inicial

  - Configuración global y por repositorio
  - Configuración de usuario: name, email

- Primeros pasos con Git
  - Primer repo (init), primer commit: readme.md & .gitignore
  - Anatomía de un repositorio git: working directory, staging area (index o cache) y repositorio (.git)
  - Estados de un archivo: untracked (U), tracked (modified (M), staged (A), committed)
  - add/commit/reset y status/log/show

- [descanso] 11:20-11:40

- Primeros pasos con Git (2)

  - Modificación de ficheros
  - Mensajes de commit

- Anatomía de comandos típicos, referencias VS paths

  - HEAD, master, HEAD~1 y otras referencias útiles
  - Referencias por mensaje de commit (:/cadena)

- Integración con otras herramientas y entornos
  - Clientes gráficos
  - Entornos de desarrollo
  - Repositorios remotos: GitHub, GitLab, Bitbucket
    - remotes -> push / pull
    - Clonar un repositorio: clone
- Comprobar el repositorio.
  - git log
  - git show
  - git diff
- Aliases
  - Qué son
  - Cómo crearlos desde el CLI: `git config --global alias.co checkout`
  - Crearlos editando el fichero de configuración: `git config --global -e`
- Ficheros Markdown
  - Qué son
  - Sintaxis básica
  - Vista previa en VSC / GitHub / GitLab -->

<!-- ### Día 2 (Miércoles 12 Noviembre 2025)

- Git internals
  - Estructura de un repositorio git: .git
  - Objetos git: blobs, trees, commits (y tags)
    - Creación y lectura de objetos
    - Creación del árbol de objetos en un primer commit
    - Modificación del árbol de objetos en commits sucesivos
  - Referencias: heads, ramas (tags y remotes)
  - Taller: creación de un repositorio git "a mano"
- Herramientas para preparar un buen commit en cualquier situación

  - Operaciones en la Staging Area (Index)
    - Añadir ficheros
    - Eliminar de la Staging Area (Index)
  - Eliminar ficheros: git rm
  - Cambiar nombre de ficheros: git mv
  - git blame

- [descanso] 11:20-11:40

- Reescribiendo la historia

  - Advertencia
  - git command --amend
    - Ref logs
  - git checkout
  - git reset
  - Evolución de git checkout: Nuevos comandos git switch y git restore

    - git checkout y reset a nivel de archivo (restore)

  - rebase interactivo (comentar por encima)
    - edit: modificando un commit
    - squash y fixup: fusionando commits
    - drop: eliminando un commit

- Otros comandos

  - git clean
  - git revert
  - git bisect -->

<!-- ### Día 3 (Jueves 13 Noviembre 2025)

- Trabajando en paralelo

  - Ramas
    - Crear y seleccionar
      - Crear desde referencia
    - Ver ramas
    - Borrar ramas
    - Mover y renombrar ramas
  - Combinación de ramas: Merge y Rebase

    - git merge
      - fast-forward
      - three-way merge
    - git rebase

  - git stash
  - Resolución de conflictos
  - git cherry-pick

- [descanso] 11:20-11:40

- Trabajando en paralelo (2)

  - (Patches: Creación y aplicación)
  - Etiquetas (tags)
    - Tags anotadas y tags ligeros
    - Crear, listar, eliminar

- Repositorios remotos

  - Repositorios "bare"
  - Clonar repositorios: git clone
  - git remote
  - git push
    - push tags
  - git pull

    - git fetch
    - git merge / git rebase
    - Conflictos

  - Ramas remotas
    - Seguimiento de ramas remotas (tracking branches)
    - Crear ramas locales a partir de ramas remotas: fetch + checkout / switch -c
    - Subir ramas locales a ramas remotas: -u
    - Eliminar ramas remotas
  - Pull requests (GitHub) / Merge requests (GitLab)
    - Flujo de trabajo típico
    - Revisión de código -->

<!-- - ### Día 4 (Viernes 14 Noviembre 2025)

  - Pull requests (GitHub) / Merge requests (GitLab)
    - Resolución de conflictos en remoto
    - Buenas prácticas:
      - Actualizar la rama con la rama main antes de hacer el merge
      - Resolución de conflictos en local
      - Eliminar la rama una vez hecho el merge

- Flujos de trabajo (workflows)

  - Citar: Git Flow / GitLab Flow
  - GitHub Flow
    - Ship-Show-Ask

- Buenas prácticas (citar)

- GitLab
  - Hosting de Repositorios
    - repositorios públicos y privados; ramas y remotos: push y pull (v.s.)
    - forks
  - Colaboración
    - merge requests: revisión de código y comentarios (v.s.)
    - MR desde ramas y forks
    - Proyectos
      - issues y milestones
      - To-Do lists
    - Wikis
  - GitLab CLI
    - Instalación y configuración
    - Comandos básicos
  - GitLab Pages
    - Configuración y uso
    - Práctica: publicar nuestro repositorio demo

- [descanso] 11:20-11:40

- Integración continua / Entrega continua (CI/CD)
  - Introducción a CI/CD
  - Configuración de un pipeline: stages y jobs
  - Artefactos
  - Variables
  - Despliegues: environments
- Despliegues en GitLab
  - Releases -->
