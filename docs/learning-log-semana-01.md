# Semana 1 — Entorno de desarrollo, Linux y Git

## Objetivo

Familiarizarme con el entorno de desarrollo utilizando WSL, Linux, Visual Studio Code y Git. Comprender los conceptos fundamentales del control de versiones y aprender a trabajar con repositorios locales y remotos en GitHub.

## Conceptos estudiados

### 1. WSL (Windows Subsystem for Linux)

WSL permite ejecutar un entorno Linux dentro de Windows sin necesidad de utilizar una máquina virtual tradicional.

Se utiliza para trabajar con herramientas de desarrollo Linux, ejecutar comandos, instalar dependencias y desarrollar aplicaciones desde Windows.

**VS Code + WSL:** permite abrir proyectos alojados en el sistema de archivos Linux y utilizar directamente su terminal, intérpretes y herramientas.

### 2. Terminal y comandos básicos de Linux

La terminal permite interactuar con el sistema operativo mediante comandos.

| Comando | Función |
|---|---|
| `pwd` | Muestra el directorio actual. |
| `ls` | Lista archivos y directorios. |
| `cd` | Cambia de directorio. |
| `mkdir` | Crea directorios. |
| `touch` | Crea archivos vacíos o actualiza sus fechas. |
| `cp` | Copia archivos o directorios. |
| `mv` | Mueve o renombra archivos. |
| `rm` | Elimina archivos o directorios. |
| `cat` | Muestra el contenido de archivos. |
| `chmod` | Modifica los permisos de archivos y directorios. |

**Rutas absolutas y relativas:**

- **Absoluta:** indica la ubicación completa desde la raíz del sistema. Ejemplo: `/home/usuario/proyectos`.
- **Relativa:** indica una ubicación tomando como referencia el directorio actual. Ejemplo: `./docs`.

**Permisos:** Linux utiliza permisos de lectura (`r`), escritura (`w`) y ejecución (`x`) para controlar el acceso a archivos y directorios.

### 3. Git y control de versiones

Git es un sistema de control de versiones distribuido que permite registrar cambios en el código, mantener un historial y trabajar con distintas versiones de un proyecto.

Conceptos fundamentales:

- **Repositorio:** directorio de un proyecto cuyo historial de cambios es administrado por Git.
- **Working directory:** archivos sobre los que se está trabajando.
- **Staging area:** área donde se preparan los cambios para el próximo commit.
- **Commit:** registro de un conjunto de cambios en el historial.
- **Branch:** rama independiente de desarrollo.
- **Merge:** operación que integra cambios de diferentes ramas.
- **Conflicto:** ocurre cuando Git no puede combinar ciertos cambios automáticamente y requiere intervención.
- **Repositorio remoto:** copia del repositorio alojada en un servidor, por ejemplo GitHub.

### 4. Comandos principales de Git

| Comando | Función |
|---|---|
| `git init` | Inicializa un repositorio. |
| `git status` | Muestra el estado de los archivos. |
| `git add` | Agrega cambios al staging area. |
| `git commit` | Registra los cambios preparados. |
| `git log` | Muestra el historial de commits. |
| `git diff` | Muestra diferencias entre versiones o cambios. |
| `git branch` | Lista o administra ramas. |
| `git switch -c` | Crea una rama y cambia a ella. |
| `git merge` | Integra cambios de otra rama. |
| `git push` | Envía commits al repositorio remoto. |
| `git pull` | Obtiene e integra cambios del remoto. |

**Flujo básico de trabajo:**

Modificar archivos → `git add` → `git commit` → `git push`.

### 5. GitHub y trabajo colaborativo

GitHub es una plataforma que permite alojar repositorios Git y colaborar en proyectos de software.

Conceptos principales:

- **Push:** publicar commits locales en el repositorio remoto.
- **Pull:** obtener e integrar cambios remotos.
- **Pull Request (PR):** propuesta para incorporar cambios de una rama a otra, permitiendo revisarlos antes de integrarlos.
- **Merge:** integrar los cambios aprobados en la rama de destino.

**Diferencia importante:** Git es la herramienta de control de versiones; GitHub es una plataforma que utiliza Git para alojar y gestionar proyectos.

### 6. Documentación y organización del proyecto

Se trabajó con los siguientes archivos:

- `README.md`: presentación del proyecto, descripción, requisitos e instrucciones.
- `.gitignore`: indica qué archivos o directorios no rastreados debe ignorar Git.
- `learning-log.md`: registro de las actividades, conceptos y dificultades encontradas durante la formación.

La documentación permite comprender el funcionamiento de un proyecto, facilita su mantenimiento y mejora el trabajo colaborativo.

## Práctica de la semana

Las actividades de esta etapa se centraron en:

1. Trabajar con Linux mediante WSL y Visual Studio Code.
2. Practicar comandos de navegación y manipulación de archivos.
3. Crear y organizar el repositorio `netops-lab`.
4. Registrar cambios mediante commits.
5. Trabajar con ramas y comprender la integración de cambios.
6. Utilizar GitHub y el flujo de pull requests.
7. Preparar la documentación inicial del proyecto.

## Conclusión y aprendizajes

Durante esta primera semana se establecieron las bases del entorno de desarrollo y del control de versiones.

Los conceptos más importantes fueron comprender cómo Git administra los cambios, diferenciar el trabajo local del remoto y entender la importancia de las ramas, los commits y los pull requests.

También se reforzó el uso de la terminal Linux y la importancia de mantener los proyectos organizados y documentados.

Estos conocimientos serán fundamentales para las siguientes etapas, donde se incorporarán programación, automatización, desarrollo backend y despliegue de aplicaciones.

**Próxima etapa:** Semana 2 — Bash y diagnóstico del sistema Linux.
