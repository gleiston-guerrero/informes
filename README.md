# Informes de evaluación

Publicación de los informes de evaluación de las asignaturas que imparto en la Universidad Técnica
Estatal de Quevedo, Facultad de Ciencias de la Computación y Diseño Digital, Carrera de Ingeniería
de Software.

**Sitio publicado:** https://gleiston-guerrero.github.io/informes/

Docente: Dr. Gleiston Cicerón Guerrero Ulloa, Ph.D. — gguerrero@uteq.edu.ec

## Contenido

| Ruta | Qué contiene |
|---|---|
| `index.html` | Portada con el listado de asignaturas |
| `AplicacionesWeb/ExamenFinal/` | Examen final del PFC, PPA 2026-2027, semana 19 |

## Por qué este repositorio existe

Los informes se publicaban antes desde el repositorio `Asignaturas`, que además guarda material de
clase, proyectos y archivos comprimidos. Ese repositorio creció hasta rozar el límite de 1 GB que
GitHub Pages admite para un sitio publicado, y el sitio dejó de servirse.

Este repositorio se mantiene deliberadamente pequeño: solo HTML y PDF de informes. Nada de código de
ejemplo, proyectos ni archivos comprimidos. Así el sitio se mantiene liviano y estable.

## Regla de tamaño

Antes de subir algo, compruebe el peso total:

```powershell
"{0:N1} MB" -f ((Get-ChildItem -Recurse -File -Exclude .git | Measure-Object Length -Sum).Sum / 1MB)
```

Si se acerca a los 500 MB, conviene archivar lo antiguo en otro sitio.

## Nota técnica

El archivo `.nojekyll` en la raíz le indica a GitHub Pages que publique los archivos tal cual, sin
procesarlos con Jekyll. No lo borre.
