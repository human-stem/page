# Pendientes editoriales

Las líneas corresponden a esta rama. Responsables indicados por función; el equipo debe asignar a la persona correspondiente. No se publican cifras sin evidencia.

| Archivo | Línea | Dato faltante | Quién debe suministrarlo |
|---|---:|---|---|
| `en/index.html` | 123 | roles de voluntariado para futuras convocatorias | Coordinación de HUMAN STEM |
| `index.html` | 137 | roles de voluntariado para futuras convocatorias | Coordinación de HUMAN STEM |

## Fotografías

Un único diseño neutral: `assets/placeholder-foto.svg` (1200 × 900, relación 4:3). Los seis archivos de `assets/fotos/` son copias de reserva del mismo diseño, con rutas estables compartidas entre inicio y detalle de proyecto.

| Archivos de destino | Entrega esperada | Responsable |
|---|---|---|
| `assets/fotos/superman-01.svg`, `superman-02.svg`, `superman-03.svg` | Tres fotos de 1200 × 900 px, con descripción, fecha y autorización de uso | Dirección del Proyecto Superman |
| `assets/fotos/miltli-01.svg`, `miltli-02.svg`, `miltli-03.svg` | Tres fotos de 1200 × 900 px, con descripción, fecha y autorización de uso | Equipo del Programa Miltli |

Para sustituir la imagen sin cambiar las rutas ni la estructura HTML, reemplazar cada archivo SVG de reserva por un SVG con la fotografía incrustada como `<image href="data:image/jpeg;base64,…" width="1200" height="900"/>`, conservando su viewBox. No basta con renombrar un JPEG a .svg. Las fotografías fuente pueden entregarse como superman-01.jpg a superman-03.jpg y miltli-01.jpg a miltli-03.jpg.

Al incorporar las fotos, actualizar las leyendas pendientes y retirar `data-placeholder="true"`; conservar alt="" si la leyenda describe completamente la imagen. Este ajuste editorial de accesibilidad es necesario, aunque la sustitución gráfica no requiera cambiar el marcado. No se han añadido estadísticas, fechas de proyecto ni criterios no confirmados.
