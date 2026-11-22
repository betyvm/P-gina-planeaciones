# Banco de Planeaciones

App para guardar planeaciones exitosas y llenar con un clic el formato de planeación del
Jardín de Niños “Barbarita Barrera de González” (ciclo 2026-2027).

- **Formato**: toca el *Nombre del proyecto* y elige una planeación del banco; todo el formato se llena solo.
  “Descargar Word” genera el .docx con el mismo encabezado, logos y colores del formato oficial.
- **Editar**: captura o modifica una planeación. Los contenidos y PDA se pueden elegir del
  Programa Sintético de la Fase 2 (1°, 2° y 3°) sin escribirlos.
- **Banco**: busca, filtra por campo formativo o eje, duplica, elimina y descarga o carga respaldos.

## Archivos

| Archivo | Qué es |
|---|---|
| `app.html` | La app (versión que se publica en claude.ai). |
| `index.html` | La misma app como página completa, para abrirla sin conexión en la computadora. Se genera a partir de `app.html`. |
| `catalogo.js` | Contenidos y PDA de los 4 campos formativos, tomados del Programa Sintético de la Fase 2 (SEP, 2024). |
| `plantilla.js` | Plantilla Word del formato (encabezado, logos, hoja horizontal). |
| `banco-inicial.js` | Planeaciones de ejemplo para la versión sin conexión. |
| `img/` | Logos del encabezado. |

En la versión sin conexión (`index.html`) el banco se guarda solo en ese navegador; usa
“Descargar respaldo” para no perderlo.
