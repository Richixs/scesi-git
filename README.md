# Git y GitHub :octocat: Richixs <sub>SCESI-2025</sub>
Este documento Markdown es parte de una de las prácticas de la postulación para la **SCESI-2025**, donde encontrarás cómo usar **Git** y **GitHub**, desde los primeros comandos hasta conceptos un poco más complejos. También está enfocado para servirte de guía para aprender o recordar cómo utilizar Git y GitHub. ¡Espero que te sirva! :shipit:

### Tabla de Contenidos
1. [¿Qué es Git?](#qué-es-git)
2. [Instalación de Git](#instalación-de-git)
    - [Windows](#windows)
    - [Linux :penguin:](#linux)

## ¿Qué es Git?

**Git** es un sistema de control de versiones distribuido, creado por Linus Torvalds en 2005, diseñado para manejar todo tipo de proyectos, desde pequeños hasta muy grandes, con velocidad y eficiencia.

### ¿Qué es un sistema de control de versiones?

Un **sistema de control de versiones** (VCS, por sus siglas en inglés) es una herramienta que permite llevar un registro de todos los cambios realizados en los archivos de un proyecto a lo largo del tiempo. Esto permite:

- Ver qué se cambió, cuándo y por quién.
- Recuperar versiones anteriores del proyecto si algo sale mal.
- Trabajar en equipo sin sobrescribir el trabajo de otros.
- Probar nuevas ideas sin arriesgar la versión estable del código.

### ¿Por qué usar Git?

- **Historial completo:** Git permite llevar un registro detallado de todos los cambios realizados en tu proyecto.
- **Trabajo colaborativo:** Facilita que múltiples personas trabajen en paralelo sin conflictos.
- **Uso de ramas:** Puedes experimentar en ramas separadas sin afectar el código principal.
- **Reversión de errores:** Si cometes un error, puedes deshacer cambios y volver a un estado anterior.
- **Sistema distribuido:** Cada usuario tiene una copia completa del repositorio, lo que da mayor flexibilidad y seguridad.

## Instalación de Git

Para comenzar a usar Git, primero necesitas instalarlo en tu sistema. A continuación se explica cómo hacerlo según tu sistema operativo.

### Windows

1. Ve al sitio oficial: [https://git-scm.com](https://git-scm.com)
2. Descarga el instalador para Windows.
3. Ejecuta el instalador y sigue los pasos:
   - En la mayoría de los casos, puedes dejar las opciones por defecto.
   - Asegúrate de seleccionar **"Git from the command line and also from 3rd-party software"** para poder usar Git desde la terminal.
4. Una vez finalizada la instalación, abre una terminal (puedes usar **Git Bash** que viene con la instalación) y escribe:

   ```bash
   git --version
   ```
    Esto debería mostrar la versión instalada de Git si todo salió bien.

### Linux

> [!IMPORTANT]
> El comando para instalar Git puede variar según la distribución de Linux que uses, ya que cada una tiene su propio gestor de paquetes.

Aquí un ejemplo usando **Arch Linux**:
``` bash
sudo pacman -S git
```

Este comando instalará Git utilizando el gestor de paquetes `pacman`, común en Arch Linux y distribuciones derivadas como Manjaro.

> [!TIP] 
> Si estás en otra distribución:
> - "En Debian usa `sudo apt install git`"
> - "En Fedora usa `sudo dnf install git`"
> - "En openSUSE usa `sudo zypper install git`"

### Verifica la instalación

Después de instalar, puedes confirmar que Git está funcionando correctamente con:

``` bash
git --version
```
Esto debería mostrar la versión instalada de Git si todo salió bien.