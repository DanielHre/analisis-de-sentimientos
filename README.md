# Humor y TDAH en TikTok: Un análisis de sentimiento para desestigmatizar percepciones en redes sociales

Este proyecto tiene como objetivo analizar el sentimiento expresado en los comentarios de un video de TikTok sobre el TDAH, utilizando técnicas de procesamiento de lenguaje natural (NLP) y análisis de sentimiento para evaluar las percepciones positivas, negativas y neutrales. La investigación busca entender cómo el humor puede influir en la forma en que se percibe este trastorno y contribuir a desestigmatizarlo.

## Documentación
- [Plan de Investigación](docs/research_plan.md)
- [Referencias y Estudios](refs/)

## Estructura del Proyecto
```bash
analisis-sentimiento/                # Raíz del proyecto
├── .github/                         # Configuraciones específicas de GitHub (workflows, templates de issues/PR, etc.)
├── vscode/                          # Configuraciones para Visual Studio Code (ajustes de proyecto, extensiones, etc.)
├── conf/                            # Archivos de configuración adicionales del proyecto (si se utilizan)
├── data/                            # Conjuntos de datos y archivos relacionados (raw, procesados, etc.)
├── docs/                            # Documentación del proyecto (incluye el plan de investigación, guías, etc.)
├── notebooks/                       # Jupyter Notebooks para análisis y experimentación
│   ├── 1-data/                      # Notebooks y scripts para adquisición y limpieza de datos
│   ├── 2-exploration/               # Notebooks para análisis exploratorio (EDA)
│   └── 3-modeling/                  # Notebooks para modelado y análisis de sentimiento
├── src/                             # Código de producción (funciones, módulos, scripts principales)
└── test/                            # Pruebas unitarias e integración
.
├── .editorconfig                    # Configuración para mantener estilos de código consistentes en distintos editores
├── .gitignore                       # Lista de archivos/carpetas que Git debe ignorar (archivos temporales, etc.)
├── pre-commit-config                # Configuración para hooks de pre-commit (por ejemplo, linters y formateadores)
├── python-version                   # Especifica la versión de Python a utilizar en el proyecto
├── LICENSE                          # Archivo de licencia (MIT License)
├── Makefile                         # Archivo Makefile para automatizar tareas comunes (tests, compilación, etc.)
├── README.md                        # Descripción general y guía del proyecto (este archivo)
├── codecov.yml                      # Configuración para Codecov (herramienta de cobertura de pruebas)
├── mkdoc.yml                        # Configuración para MkDocs (para generar el sitio de documentación)
├── pyproject.toml                   # Configuración del proyecto y herramientas (build, formateo, etc.)
└── requirements.txt                  # Listado de dependencias del proyecto (se recomienda renombrarlo a requirements.txt)

```
