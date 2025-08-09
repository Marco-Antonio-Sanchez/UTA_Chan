La política de liberación implementada para el proyecto uta-foro se documentó en el archivo RELEASE_POLICY.md (ver captura de pantalla de código o fragmento siguiente):

markdown
Copiar código
# RELEASE_POLICY

## Objetivo
Asegurar que las liberaciones del proyecto **uta-foro** sean controladas, verificables y cumplan con las normativas internas de calidad y seguridad.

## Versionado
- Se aplicará versionado semántico: `MAJOR.MINOR.PATCH` (ej. `v1.0.0`).
- El número de versión se registra en `VERSION.txt` y en la etiqueta (tag) de Git.

## Requisitos de liberación
1. Todas las pruebas automatizadas deben pasar.
2. Revisión y aprobación por al menos 2 revisores.
3. Validación del líder técnico (firma digital o comentario en PR).
4. Documentación mínima actualizada:
   - `README.md`
   - `CHANGELOG.md`
5. `VERSION.txt` actualizado.
6. Firma de QA previa a la liberación.
Esta política asegura:

Control de versiones con versionado semántico.

Validación de cambios antes de llegar a main.

Evidencia documental mínima por cada liberación.
