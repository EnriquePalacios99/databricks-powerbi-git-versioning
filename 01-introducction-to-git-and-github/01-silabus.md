# Curso de Introducción a Git y GitHub

---

## Módulo 1: Introducción a Git

### 1.1 ¿Qué es Git?
* Control de versiones (VCS)
* Sistemas de control de versiones centralizados vs. distribuidos
* Ventajas de usar Git

### 1.2 Instalación y Configuración Inicial
* Cómo instalar Git en diferentes sistemas operativos (Windows, macOS, Linux)
* Configuración básica de Git: `git config` (nombre de usuario, email)

### 1.3 Conceptos Básicos de Git
* **Repositorio (Repository)**: Local y remoto
* **Commit**: Capturando cambios
* **Branch (Rama)**: Líneas de desarrollo
* **Merge**: Uniendo ramas
* **Head**: Puntero a la rama actual

## Módulo 2: Trabajando con Git Localmente

### 2.1 Inicializando un Repositorio
* `git init`: Creando un nuevo repositorio
* `git clone`: Clonando un repositorio existente

### 2.2 El Ciclo de Vida de los Archivos en Git
* **Untracked**: Archivos no seguidos
* **Unmodified**: Archivos sin modificar
* **Modified**: Archivos modificados
* **Staged**: Archivos preparados para el commit
* `git status`: Verificando el estado de los archivos

### 2.3 Realizando Commits
* `git add`: Preparando archivos para el commit
* `git commit`: Guardando cambios en el repositorio
* Mensajes de commit significativos

### 2.4 Deshaciendo Cambios
* `git restore`: Deshaciendo cambios en el directorio de trabajo
* `git reset`: Deshaciendo cambios en el área de staging y/o historial
* `git revert`: Revirtiendo un commit existente

### 2.5 Historial de Commits
* `git log`: Visualizando el historial de commits
* Opciones de `git log` para una mejor visualización

## Módulo 3: Ramas (Branches) en Git

### 3.1 Fundamentos de las Ramas
* Por qué usar ramas
* Ramas principales: `main` (o `master`)

### 3.2 Creación y Navegación de Ramas
* `git branch`: Listar, crear y eliminar ramas
* `git checkout`: Cambiando entre ramas
* `git switch`: Una alternativa moderna a `git checkout` para cambiar de rama

### 3.3 Fusionando Ramas (Merging)
* `git merge`: Combinando cambios de una rama a otra
* Resolución de conflictos de merge

## Módulo 4: Introducción a GitHub

### 4.1 ¿Qué es GitHub?
* Plataforma de alojamiento de repositorios Git
* Características principales: Issues, Pull Requests, Proyectos, Wikis

### 4.2 Creando un Repositorio en GitHub
* Pasos para crear un nuevo repositorio remoto
* Conectando un repositorio local a uno remoto (`git remote add origin`)

### 4.3 Subiendo y Bajando Cambios
* `git push`: Subiendo cambios al repositorio remoto
* `git pull`: Bajando cambios del repositorio remoto

### 4.4 Colaboración con Pull Requests
* **Forking**: Creando una copia de un repositorio
* **Pull Request (PR)**: Proponiendo cambios
* Proceso de revisión y merge de PRs

## Módulo 5: Flujos de Trabajo Comunes

### 5.1 Flujo de Trabajo Centralizado
* Uso básico de `main` (o `master`)

### 5.2 Flujo de Trabajo de Feature Branch
* Crear una rama por cada nueva característica
* Mergear al finalizar

### 5.3 Resolución de Conflictos Comunes
* Conflictos al hacer `git pull`
* Conflictos al hacer `git merge`

## Módulo 6: Temas Avanzados y Buenas Prácticas (Opcional)

### 6.1 `git ignore`
* Ignorando archivos y directorios

### 6.2 Etiquetas (Tags)
* `git tag`: Marcando versiones específicas del código

### 6.3 Stashing
* `git stash`: Guardando cambios temporalmente

### 6.4 Buenas Prácticas en Git y GitHub
* Mensajes de commit descriptivos
* Ramas claras y específicas
* Revisión de código
* Mantener el repositorio limpio

---

### Recursos Adicionales
* Documentación oficial de Git
* Documentación de GitHub
* Cursos en línea y tutoriales
