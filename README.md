# Subcomité de Trasplante Renal — Checklist

Herramienta tipo checklist, autocontenida (HTML/CSS/JS, sin dependencias de servidor ni backend), para llevar a cabo las sesiones del Subcomité de Trasplante Renal de CIMA. Basta con abrir `index.html` en cualquier navegador.

## Contenido de la herramienta

- **Datos de la sesión**: fecha, hora, folio, modalidad, asistentes.
- **Identificación del paciente**: nombre, fecha de nacimiento (la edad se calcula sola), sexo, expediente, diagnóstico, tipo de trasplante candidato.
- **Datos antropométricos**: peso, talla, IMC (calculado y clasificado automáticamente), grupo sanguíneo y Rh.
- **Checklist de laboratorios** agrupado en biometría/química, panel viral/serologías e inmunología/histocompatibilidad, cada estudio con estatus Completo / Incompleto / N.A. y comentario; se pueden agregar estudios adicionales.
- **Checklist de estudios de imagen** y de **valoraciones por especialista**, mismo formato, también ampliable.
- **Resumen clínico**, **acuerdos/pendientes** (lista dinámica) y **comentarios generales**.
- **Resolución del subcomité**: Aprobado / Aprobado condicionado / No aprobado, con espacio para justificación.
- Botón para generar un **resumen de acta en texto** (copiable) y botón para **imprimir/guardar como PDF**.
- **Borrador autoguardado** en el navegador (localStorage) para no perder la captura durante la sesión; los datos no se envían a ningún servidor.

## Uso

Abre `index.html` directamente en el navegador (doble clic, o `Archivo > Abrir`). No requiere instalación, servidor ni conexión a internet, salvo para cargar las tipografías (si no hay internet, usa las tipografías del sistema como respaldo).
