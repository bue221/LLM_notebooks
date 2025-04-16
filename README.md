# Python Notebooks

Este repositorio contiene notebooks de Python enfocados en el uso de la API de OpenAI y el desarrollo de modelos de lenguaje.

## Estructura del Proyecto

```
.
├── openAI/                  # Directorio principal de notebooks
│   ├── fine_tuning.ipynb    # Notebook sobre fine-tuning de modelos
│   ├── first_steps_llm.ipynb # Notebook introductorio a LLMs
│   └── data/                # Directorio para datos
├── pyproject.toml           # Configuración de Poetry
├── poetry.lock              # Lock file de dependencias
├── .env.example             # Plantilla de variables de entorno
└── .env                     # Variables de entorno (no versionado)
```

## Requisitos

- Python >= 3.11
- Poetry para gestión de dependencias

## Instalación

1. Clona el repositorio:

```bash
git clone https://github.com/bue221/python-notebooks.git
cd python-notebooks
```

2. Instala las dependencias:

```bash
poetry install
```

3. Configura las variables de entorno:

```bash
cp .env.example .env
# Edita .env con tus credenciales de OpenAI
```

## Dependencias Principales

- openai >= 1.74.1
- python-dotenv >= 1.1.0
- tiktoken >= 0.9.0

## Uso

Los notebooks están organizados para ser ejecutados en secuencia:

1. `first_steps_llm.ipynb`: Introducción a los modelos de lenguaje y la API de OpenAI
2. `fine_tuning.ipynb`: Guía sobre fine-tuning de modelos

## Contribución

Las contribuciones son bienvenidas. Por favor, asegúrate de:

1. Seguir las convenciones de commits
2. Mantener la documentación actualizada
3. Probar los cambios antes de enviar un PR

## Licencia

Este proyecto está bajo la licencia MIT.
