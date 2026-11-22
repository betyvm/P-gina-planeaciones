# Banco de Planeaciones

App para guardar planeaciones exitosas y llenar con un clic el formato de planeación del
Jardín de Niños “Barbarita Barrera de González” (ciclo 2026-2027).

- **Formato**: toca el *Nombre del proyecto* y elige una planeación del banco; todo el formato se llena solo.
  “Descargar Word” genera el .docx con el mismo encabezado, logos y colores del formato oficial.
  En el sitio también funciona “Imprimir”.
- **Editar**: captura o modifica una planeación. Los contenidos y PDA se eligen del Programa Sintético
  de la Fase 2 (1°, 2° y 3°) con las claves del cuadernillo; los momentos cambian según la modalidad.
- **Banco**: busca, filtra por campo formativo o eje, duplica, elimina, descarga o carga el banco.
- **Avance**: muestra qué PDA del grado ya tienen planeación en el banco y cuáles faltan.

## Dónde se guardan las planeaciones

- **`banco.json`** es el banco compartido: lo que está ahí aparece en todos tus dispositivos.
- Lo que crees o cambies en la app se guarda primero **solo en ese dispositivo** (la app te avisa).
  Para pasarlo a todos: en la pestaña Banco pulsa **Descargar banco** y sube el archivo `banco.json`
  a este repositorio (*Add file → Upload files*), reemplazando el anterior. En 1 o 2 minutos el sitio
  se actualiza.

## Publicar el sitio (GitHub Pages)

1. *Settings → Pages → Build and deployment → Source: Deploy from a branch*.
2. Elige la rama del proyecto y la carpeta `/ (root)` → *Save*.
3. Para que la dirección sea `https://<usuario>.github.io/planeaciones/`, cambia el nombre del
   repositorio a `planeaciones` en *Settings → General*.

En el iPhone: abre el sitio en Safari → Compartir → **Agregar a pantalla de inicio**.

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | La app (página del sitio). Se genera a partir de `app.html`. |
| `app.html` | La misma app en la versión que se publica dentro de Claude. |
| `banco.json` | El banco compartido de planeaciones. |
| `catalogo.js` | Contenidos y PDA de los 4 campos formativos (Programa Sintético Fase 2, SEP 2024). |
| `plantilla.js` | Plantilla Word del formato (encabezado, logos, hoja horizontal). |
| `manifest.webmanifest`, `img/icono-*.png` | Nombre e ícono al agregarla a la pantalla de inicio. |
| `img/` | Logos del encabezado. |

Referencias: Programa Sintético de la Fase 2 (SEP, 2024) y el Cuadernillo de Planeación
(momentos por modalidad p. 69, elementos de la planeación pp. 79-81, claves de contenidos y PDA pp. 27 y 42-56).
