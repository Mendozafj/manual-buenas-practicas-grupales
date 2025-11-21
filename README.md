# Manual de Buenas Prácticas para Trabajos Universitarios en Grupo

Este repositorio contiene el desarrollo del “Manual de buenas prácticas para trabajos académicos en grupo”, elaborado para la asignatura Proyecto de Sistema. 

El objetivo principal es demostrar el uso de Git y GitHub como herramientas de colaboración, control de versiones y organización, aplicadas a la creación de documentos académicos.

Aunque el trabajo se realiza de manera individual, se sigue una estructura que simula el trabajo en equipo: cada sección se desarrolla en una rama independiente, se revisa mediante Pull Requests y se integra a la rama principal siguiendo un flujo de trabajo ordenado.

---

## Objetivos del proyecto

- Elaborar un manual académico que recopile buenas prácticas para la organización de trabajos en grupo.
- Utilizar Git de forma estructurada para controlar versiones y registrar cambios.
- Emplear GitHub como entorno colaborativo: issues, ramas, Pull Requests y tablero de proyecto.
- Mantener un historial claro del proceso mediante un CHANGELOG y versiones etiquetadas.
- Generar una versión final del documento en formato PDF a partir del archivo principal en Markdown.

---

## Flujo de trabajo utilizado

Para mantener un proceso ordenado y reproducible, se empleó el siguiente método:

1. Cada sección del manual se registró como una issue independiente.
2. Para cada issue se creó una rama específica.
3. El contenido se redactó directamente en el archivo `manual.md`.
4. Los cambios se enviaron mediante Pull Requests.
5. Cada PR fue revisado y aprobado antes de integrarse en la rama principal.
6. Las issues se cerraron automáticamente mediante la vinculación en los PR.
7. El tablero del proyecto se utilizó para seguir el estado de cada tarea.
8. Una vez completadas todas las secciones, se preparó una versión estable del manual.

Este enfoque permite mantener un historial claro del progreso y facilita la trazabilidad de cada parte del documento.

## Obtener la versión en PDF 

Para obtener la versión en PDF se debe utilizar "Pandoc".

```
pandoc documentos/manual.md -o documentos/manual.pdf
```

## Versionado

Las versiones formales se publican mediante etiquetas (tags).  
Ejemplo:
v1.0
