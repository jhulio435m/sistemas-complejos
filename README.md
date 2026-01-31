# Sistemas Complejos - Knowledge Hub

Repositorio de documentación técnica y recursos para la especialidad de Ingeniería de Sistemas Complejos.
Generado estáticamente usando **MkDocs** con el tema **Material**.

## Estructura del Proyecto

```text
.
├── docs/
│   ├── 01-gestion-iso/       # Recursos SIG (ISO 9001, 14001, 45001)
│   ├── 02-metodologia-blanda/# SSM (Soft Systems Methodology)
│   ├── 03-dinamica-sistemas/ # Dinámica de Sistemas (Forrester)
│   ├── 04-cibernetica/       # Cibernética Organizacional (VSM)
│   ├── recursos/             # Bibliografía General (SEBoK, NASA)
│   └── index.md              # Portada
├── mkdocs.yml                # Configuración del sitio
└── README.md                 # Este archivo
```

## Guía de Colaboración (DevOps)

Este proyecto fomenta la colaboración abierta. Para contribuir con documentación o mejoras en la estructura, siga los siguientes pasos.

### 1. Preparación del Entorno

Requisitos previos: **Python 3.x** y **Git**.

```bash
# 1. Clonar el repositorio
git clone [https://github.com/jhulio435m/sistemas-complejos](https://github.com/jhulio435m/sistemas-complejos)
cd sistemas-complejos

# 2. Instalar MkDocs y el tema Material
pip install mkdocs
pip install mkdocs-material

```

### 2. Servidor de Desarrollo

Antes de realizar un *commit*, es obligatorio visualizar los cambios en local para asegurar la integridad de los enlaces y formatos.

```bash
mkdocs serve
```

El sitio se desplegará en: `http://127.0.0.1:8000`


### 3.Contribución: 
Para agregar archivos, realice un *Pull Request* a la rama `master`