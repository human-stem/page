# Pendientes editoriales

Las líneas corresponden a esta rama. Responsables indicados por función; el equipo debe asignar a la persona correspondiente. No se publican cifras sin evidencia.

| Archivo | Línea | Dato faltante | Quién debe suministrarlo |
|---|---:|---|---|
| `en/index.html` | 123 | roles de voluntariado para futuras convocatorias | Coordinación de HUMAN STEM |
| `index.html` | 139 | roles de voluntariado para futuras convocatorias | Coordinación de HUMAN STEM |
| `index.html` | 183 | estado actual de Proyecto Superman | Dirección del Proyecto Superman |
| `index.html` | 184 | fechas de las actividades documentadas de Proyecto Superman | Dirección del Proyecto Superman |
| `index.html` | 188 | descripción de la foto | Coordinación de HUMAN STEM |
| `index.html` | 192 | descripción de la foto | Coordinación de HUMAN STEM |
| `index.html` | 196 | descripción de la foto | Coordinación de HUMAN STEM |
| `index.html` | 202 | estado actual de Programa Miltli | Equipo del Programa Miltli |
| `index.html` | 203 | fechas de las actividades documentadas de Programa Miltli | Equipo del Programa Miltli |
| `index.html` | 207 | descripción de la foto | Coordinación de HUMAN STEM |
| `index.html` | 211 | descripción de la foto | Coordinación de HUMAN STEM |
| `index.html` | 215 | descripción de la foto | Coordinación de HUMAN STEM |
| `miltli.html` | 107 | descripción del Programa Miltli validada por su equipo | Equipo del Programa Miltli |
| `miltli.html` | 109 | lugares donde se realiza el Programa Miltli | Equipo del Programa Miltli |
| `miltli.html` | 111 | fase actual del Programa Miltli | Equipo del Programa Miltli |
| `miltli.html` | 113 | actividades y compromiso de participación en el Programa Miltli | Equipo del Programa Miltli |
| `miltli.html` | 115 | significado y origen verificados del nombre Miltli | Equipo del Programa Miltli |
| `miltli.html` | 117 | nombres, roles y biografías del equipo del Programa Miltli | Equipo del Programa Miltli |
| `miltli.html` | 123 | estado actual de Programa Miltli | Equipo del Programa Miltli |
| `miltli.html` | 124 | fechas de las actividades documentadas de Programa Miltli | Equipo del Programa Miltli |
| `miltli.html` | 128 | descripción de la foto | Equipo del Programa Miltli |
| `miltli.html` | 132 | descripción de la foto | Equipo del Programa Miltli |
| `miltli.html` | 136 | descripción de la foto | Equipo del Programa Miltli |
| `superman.html` | 61 | estándar y evidencia que respalden la aspiración de grado médico del Proyecto Superman | Dirección del Proyecto Superman |
| `superman.html` | 349 | resumen textual verificado de la entrevista de Proyecto Superman | Dirección del Proyecto Superman |
| `superman.html` | 382 | criterios para solicitar una prótesis de Proyecto Superman | Dirección del Proyecto Superman |
| `superman.html` | 384 | pasos y proceso de atención de solicitudes de prótesis | Dirección del Proyecto Superman |
| `superman.html` | 386 | primer paso de contacto y canal confirmado para solicitudes de prótesis | Dirección del Proyecto Superman |
| `superman.html` | 392 | estado actual de Proyecto Superman | Dirección del Proyecto Superman |
| `superman.html` | 393 | fechas de las actividades documentadas de Proyecto Superman | Dirección del Proyecto Superman |
| `superman.html` | 397 | descripción de la foto | Dirección del Proyecto Superman |
| `superman.html` | 401 | descripción de la foto | Dirección del Proyecto Superman |
| `superman.html` | 405 | descripción de la foto | Dirección del Proyecto Superman |

## Fotografías

Un único diseño neutral: `assets/placeholder-foto.svg` (1200 × 900, relación 4:3). Los seis archivos de `assets/fotos/` son copias de reserva del mismo diseño, con rutas estables compartidas entre inicio y detalle de proyecto.

| Archivos de destino | Entrega esperada | Responsable |
|---|---|---|
| `assets/fotos/superman-01.svg`, `superman-02.svg`, `superman-03.svg` | Tres fotos de 1200 × 900 px, con descripción, fecha y autorización de uso | Dirección del Proyecto Superman |
| `assets/fotos/miltli-01.svg`, `miltli-02.svg`, `miltli-03.svg` | Tres fotos de 1200 × 900 px, con descripción, fecha y autorización de uso | Equipo del Programa Miltli |

Para sustituir la imagen sin cambiar las rutas ni la estructura HTML, reemplazar cada archivo SVG de reserva por un SVG con la fotografía incrustada como `<image href="data:image/jpeg;base64,…" width="1200" height="900"/>`, conservando su viewBox. No basta con renombrar un JPEG a .svg. Las fotografías fuente pueden entregarse como superman-01.jpg a superman-03.jpg y miltli-01.jpg a miltli-03.jpg.

Al incorporar las fotos, actualizar las leyendas pendientes y retirar `data-placeholder="true"`; conservar alt="" si la leyenda describe completamente la imagen. Este ajuste editorial de accesibilidad es necesario, aunque la sustitución gráfica no requiera cambiar el marcado. No se han añadido estadísticas, fechas de proyecto ni criterios no confirmados.
