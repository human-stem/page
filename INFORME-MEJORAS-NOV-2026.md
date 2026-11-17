# Mejoras de noviembre de 2026

Fecha de edición: 16 de noviembre de 2026 (Ciudad de México).
Repositorio: HUMAN-STEM/page. Rama: `mejoras-nov-2026`, basada en `c07d7c1f4e69a881cfffa599745de3c794450641`.
No se solicitó despliegue ni fusión. Se conservan HTML, CSS, JavaScript, fuentes y componentes existentes, sin dependencias ni scripts externos nuevos.

## Estado por tarea

| Tarea | Estado | Resultado |
|---|---|---|
| 1. Metadatos | Implementada | URLs canónicas y Open Graph, hreflang recíproco es-MX/en/x-default, idiomas y un JSON-LD NGO en inicio con datos ya presentes. Eliminados keywords; auditoría ajustada. Incluye 404 y alias existentes. |
| 2. Colabora | Implementada; roles pendientes | Tres públicos con mensaje y acción por correo, en ambas portadas. Sin convocatoria abierta; retirados enlaces al formulario y QR también de Miltli. |
| 3. Evidencias | Estructura implementada; contenido pendiente | Cuatro bloques, tres imágenes por bloque. Un diseño SVG neutral y seis copias de reserva con rutas estables, compartidas por inicio y páginas de proyecto. Estado, fechas y leyendas pendientes; sin cifras inventadas. |
| 4. Superman | Implementada; datos pendientes | Grado médico como aspiración sin respaldo actual; criterios, pasos, canal de solicitudes y resumen de entrevista marcados pendientes. El correo general se ofrece para consultas, sin presentarlo como procedimiento confirmado de solicitud. |
| 5. Miltli | Implementada; datos pendientes | Presentación antes de la guía: qué es, dónde, fase, participación, nombre y equipo. Marcadores sin inventar información. |
| 6. Equipo | Implementada; biografía pendiente | Jair tiene la misma estructura de trayectoria y aprendizaje central que Iñaki. Los rótulos identifican explícitamente a cada persona y su cargo existente. |
| 7. Inglés | Implementada | Enlaces a páginas españolas etiquetados «(in Spanish)», incluidos menú, mapa y créditos. Páginas de proyectos sin traducir. |
| 8. Mapa y fecha | Implementada | Nuevas anclas en mapa, descripción de colaboración vigente y actualización de los ocho pies al 16 de noviembre de 2026. Sitemap y robots alineados con la URL canónica. |

## Archivos modificados y nuevos

- Páginas principales: `index.html`, `en/index.html`, `superman.html`, `miltli.html`, `mapa-del-sitio.html`, `creditos.html`, `uso-responsable-ia.html`.
- Páginas adicionales existentes: `404.html`, `colabora.html`, `quienes-somos.html`, `uso_responsable_ia.html`.
- Estilos compartidos y portada: `comun.css`, `horizonte.css`.
- Mantenimiento: `herramientas/auditar.js`, `robots.txt`, `sitemap.xml`.
- Imágenes nuevas: `assets/placeholder-foto.svg`, `assets/fotos/superman-01.svg`, `assets/fotos/superman-02.svg`, `assets/fotos/superman-03.svg`, `assets/fotos/miltli-01.svg`, `assets/fotos/miltli-02.svg`, `assets/fotos/miltli-03.svg`.
- Documentación nueva: `PENDIENTES.md` y este informe.

## Verificación

- 597 comprobaciones estáticas sin fallos: once páginas HTML; un h1 y un main por página; orden de encabezados; identificadores únicos; destinos locales y anclas; idiomas; canonical; Open Graph; ausencia de keywords y formularios cerrados; atributos y número de fotos; hreflang; JSON-LD; correspondencia entre cada marcador y su archivo/línea en PENDIENTES.md.
- Sintaxis JavaScript de `herramientas/auditar.js` comprobada con Node.
- Las secciones nuevas quedan dentro del contenido principal y enlazadas desde la navegación. Reutilizan los estilos de foco visibles existentes. La portada permite crecer al contenido para no depender de una altura fija.
- No fue posible ejecutar la auditoría de navegador: Playwright está disponible, pero su navegador empaquetado no; Chromium del sistema falla al arrancar por la restricción de sockets del entorno (`Operation not permitted`). Por tanto, quedan sin verificar visualmente el diseño adaptable, foco por teclado, transiciones, contraste y axe-core. La revisión estática no sustituye esas pruebas.
- No se verificaron enlaces externos, entrega del correo, contenido del video ni hechos que el equipo dejó sin aportar. No se incluyen resultados de producción porque no se desplegó.

## Diferencias y decisiones respecto al repositorio

- No hay proceso de compilación ni generador de metadatos; cada head está escrito directamente en HTML.
- La auditoría existente exigía keywords, en conflicto con la tarea 1; ahora detecta su presencia como obsoleta.
- Robots y sitemap apuntaban a `luismac2022.github.io/HUMAN/`, además del dominio anterior en Open Graph. Se corrigieron para evitar señales canónicas contradictorias.
- Miltli conservaba un QR y enlaces al formulario de septiembre; se retiraron junto con los de las portadas para respetar el cierre informado.
- El mapa afirmaba «prótesis de grado médico» sin matiz; se alineó con la aspiración descrita en Superman.
- Para conservar rutas distintas al reemplazar fotos se crearon seis copias del único diseño de placeholder. PENDIENTES.md documenta nombres, dimensiones y reemplazo mediante SVG con fotografía incrustada. Sustituir la imagen no exige cambiar rutas ni estructura HTML; completar leyendas y retirar el atributo de placeholder sí exige la edición editorial correspondiente.
- Los alias se conservan como redirecciones, con canonical absoluto al destino. El 404 conserva su comportamiento.

## Información que debe aportar el equipo

PENDIENTES.md registra cada marcador por archivo y línea, con responsable por función: roles, estados y fechas de proyectos, fotos y descripciones, criterios y pasos de solicitud de prótesis, respaldo de la aspiración médica, resumen de entrevista, presentación y equipo de Miltli y biografía/aprendizaje de Jair. Los responsables son propuestas por función, no nuevas identidades ni asignaciones confirmadas.
