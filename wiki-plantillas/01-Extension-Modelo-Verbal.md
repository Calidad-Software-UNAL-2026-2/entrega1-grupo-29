# Paso 1 — Extensión del Modelo Verbal

> Recuerda: mínimo 1 funcionalidad adicional + 1 requisito de calidad
> asociado, señalados explícitamente como decisión del equipo (no parte
> del enunciado original).

## Funcionalidad adicional propuesta por el equipo

Funcionalidad adicional no contemplada explícitamente en el enunciado original

La plataforma de archivo digital Paperless incorporará un módulo de copias de seguridad y recuperación de documentos que permitirá generar respaldos periódicos de los documentos almacenados y de sus metadatos asociados. En caso de pérdida de información, eliminación accidental o falla técnica, los usuarios administradores podrán restaurar los documentos desde una copia de seguridad disponible, procurando mantener la integridad y disponibilidad de la información. Además, el sistema permitirá verificar el resultado de las copias de seguridad y registrar las operaciones de respaldo y restauración para facilitar su seguimiento.

## Requisito de calidad asociado

La plataforma deberá permitir la recuperación de los documentos y sus metadatos a partir de una copia de seguridad válida, de manera que al menos el 99 % de los documentos incluidos en una prueba de restauración se recuperen íntegramente y puedan consultarse correctamente. Este requisito se verificará mediante pruebas periódicas de restauración con conjuntos de documentos representativos, comparando los archivos recuperados con los originales.
## Justificación de la decisión

El equipo considera necesaria esta extensión debido a que Paperless administrará documentos digitales que pueden contener información importante para los procesos administrativos y operativos de una organización. Aunque el enunciado original contempla mecanismos de seguridad, permisos de acceso, cifrado y auditoría, no especifica un procedimiento para recuperar información ante pérdidas accidentales, fallas técnicas o daños en los datos almacenados.
Por esta razón, incorporar copias de seguridad y recuperación permitirá complementar las medidas de seguridad existentes, reducir el impacto de posibles incidentes y fortalecer la confiabilidad de la plataforma. Asimismo, establecer un requisito de calidad medible permitirá verificar que el mecanismo de recuperación funcione correctamente y que la información restaurada conserve su integridad.
