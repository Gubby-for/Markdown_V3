# COEVALUACIÓN DE CMS Y SSG

**Nombre del evaluador:** Luiggi Neyra.  
**Persona evaluada:** Ivan Lau Li.  
**Mi repositorio:** https://github.com/ZhorenNG/MARKDOWN_V2.  
**Repositorio que evalúo:** https://github.com/Gubby-for/Markdown_V3.  

## A. Puntuación de la investigación

| Código | Criterio | Máximo | Puntos asignados | Evidencia y justificación concreta |
| :--- | :--- | :---: | :---: | :--- |
| A1 | Concepto y funcionamiento de SSG. | 1 | 0.50 | Se define brevemente el concepto en el bloque de cita de `ssg.md`, pero no se profundiza en el proceso de compilación/build. |
| A2 | SSG frente a HTML manual. | 0,5 | 0.15 | Menciona que evita programar desde cero, pero falta un apartado comparativo directo frente al desarrollo en HTML manual. |
| A3 | Comparación de Jekyll, Hugo y Astro. | 1 | 0.20 | No se desarrolla la tabla ni el texto comparativo de estas tres herramientas dentro de `ssg.md`. |
| A4 | Concepto y funcionamiento de CMS. | 1 | 0.60 | `cms.md` define el concepto y diferencia correctamente Backend y Frontend, aunque el contenido es algo conciso. |
| A5 | Clasificación de CMS y ejemplos. | 0,5 | 0.45 | Clasificación clara en Código Abierto, Propietarios y SaaS con ejemplos adecuados (WordPress, Drupal, Shopify, Wix). |
| A6 | Top 5 y estadísticas de mercado. | 0,5 | 0.00 | Ausente en `cms.md`. No se incluye el ranking Top 5 ni datos estadísticos de cuota de mercado. |
| A7 | Comparativa CMS dinámico-SSG. | 1 | 0.50 | Se incluye mediante imagen (`./MISC/CMSvsSSG.png`), pero se requiere la tabla formateada en texto Markdown. |
| A8 | Claridad y apoyo visual. | 0,5 | 0.40 | Buena estructura general y uso de recursos visuales, aunque con pequeños detalles ortográficos a pulir. |
| **Subtotal** | **A** | **6** | **2.80** | |

## B. Puntuación de la actividad Markdown

| Código | Criterio | Máximo | Puntos asignados | Evidencia y justificación concreta |
| :--- | :--- | :---: | :---: | :--- |
| B1 | Organización del proyecto. | 0,75 | 0.65 | Buena organización en subcarpeta `MISC/` para los recursos multimedia del proyecto. |
| B2 | Adaptación de la investigación. | 0,75 | 0.40 | Contenido correctamente dividido en `cms.md` y `ssg.md`, aunque la información investigada resulta breve. |
| B3 | Sintaxis Markdown. | 0,5 | 0.40 | Correcto uso de títulos, listas, citas y enlaces. Existen pequeñas erratas tipográficas ("ies donde", "pernsonalizables"). |
| B4 | Imágenes y rutas. | 0,5 | 0.50 | Imágenes vinculadas correctamente con rutas relativas a `./MISC/`. |
| B5 | Dos vídeos de hasta 5 minutos. | 0,5 | 0.50 | Enlaces e imágenes-enlace a vídeos educativos de YouTube incluidos en ambos documentos. |
| B6 | Enlace de cms.md a ssg.md. | 0,5 | 0.25 | `ssg.md` enlaza a `cms.md` (`[Ir a CMS](cms.md)`), pero falta el enlace recíproco desde `cms.md` hacia `ssg.md`. |
| B7 | Legibilidad de ambos documentos. | 0,5 | 0.40 | Documentos escaneables con buena separación visual (`---`), aunque requieren revisión ortográfica. |
| **Subtotal** | **B** | **4** | **3.10** | |

## C. Nota propuesta y valoración inicial

**Puntuación real A + B:** 5.90 /10.

**Justificación de la nota, entre 2 y 4 líneas:**  
La puntuación refleja un buen trabajo técnico en la maquetación Markdown, organización de archivos y uso de recursos multimedia. Sin embargo, la nota se ve reducida principalmente en la parte teórica debido a la falta de apartados clave como el Top 5/estadísticas de CMS y la comparativa detallada entre generadores de sitios estáticos (Jekyll, Hugo, Astro).

**Dos puntos fuertes:**
- **Estructura y gestión de archivos:** Excelente organización mediante la carpeta `./MISC/` para almacenar imágenes y uso correcto de rutas relativas.
- **Apoyo audiovisual:** Buena integración de enlaces a vídeos explicativos y recursos gráficos para enriquecer los documentos.

**Dos mejoras prioritarias:**

| Propuesta | Archivo y apartado | Observación y mejora propuesta |
| :--- | :--- | :--- |
| **P1** | `cms.md`: Sección de Estadísticas y Top 5. | Incorporar el ranking Top 5 de CMS junto con datos estadísticos de cuota de mercado, citando la fuente y fecha. |
| **P2** | `ssg.md`: Sección de Comparativa de SSG y HTML manual. | Crear una tabla Markdown comparando Jekyll, Hugo y Astro, e incluir un apartado que contraste SSG vs. HTML manual. Además, añadir el enlace de vuelta a `ssg.md` en `cms.md`. |

## D. Respuesta y correcciones del propietario del proyecto

**Cumplimenta:** [Ivan Lau Li].

| Propuesta | Respuesta y decisión razonada | Corrección aplicada y archivo | Commit |
| :--- | :--- | :--- | :--- |
| **P1** | [Aceptada]. | [añadi la tabla de la comparacion de cms ]. | [Enlace](https://github.com/Gubby-for/Markdown_V3/pull/2/changes/81f9940c767fe5014a88519b9354fde1e8194e1d). |
| **P2** | [Aceptada]. | [Añadi la tabla de los tres tipos que se pedian]. | [Enlace](https://github.com/Gubby-for/Markdown_V3/pull/2/changes/01ea3e8bdd8259650762e0267a9d33b171012312). |
