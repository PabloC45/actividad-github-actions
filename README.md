# Actividad GitHub Actions

Este repositorio contiene un ejemplo básico de integración continua (CI) utilizando GitHub Actions.

## Descripción

El proyecto incluye un workflow configurado en `.github/workflows/main.yml` que se ejecuta automáticamente cada vez que se realiza un **push** al repositorio.

## Funcionamiento del Pipeline

El pipeline realiza las siguientes tareas:

1. Descarga el contenido del repositorio.
2. Configura el entorno de Python.
3. Instala las dependencias necesarias.
4. Ejecuta el linter **Flake8** para verificar que el código cumple con las reglas de estilo y sintaxis.

## Estructura del proyecto

```text
.
├── app.py
├── README.md
└── .github
    └── workflows
        └── main.yml
```
