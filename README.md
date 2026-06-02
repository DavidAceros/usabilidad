# Tienda Inclusiva

## ¿Qué es este proyecto?
Una landing page diseñada para una plataforma de compras en línea enfocada en accesibilidad. La página presenta un catálogo de productos, promociones, soporte y un menú de accesibilidad que facilita el uso por personas con discapacidad visual, motora o auditiva.

## ¿Para quién es esta página?
Esta página está dirigida a:
- Personas con discapacidad visual que necesitan alto contraste, texto legible y etiquetas claras.
- Personas con discapacidad motora que requieren botones grandes, zonas de interacción amplias y navegación por teclado.
- Personas con discapacidad auditiva que se benefician de contenido textual claro, soporte visible y una navegación simple.
- Cualquier usuario que busque una experiencia de compra más accesible y usable.

## ¿Por qué se creó?
El objetivo es ofrecer una experiencia inclusiva en el comercio electrónico, reduciendo las barreras comunes en sitios de compra online y garantizando un acceso más sencillo a productos, promociones y soporte.

## Protocolos y prácticas aplicadas
- Uso de HTML semántico: `header`, `main`, `section`, `nav`, `footer` y roles ARIA donde corresponde.
- Navegación por teclado: enfoque visible, botones nativos y enlaces activables con `Tab`, `Enter` y `Esc`.
- Diseño responsive: el contenido se adapta a móviles, tabletas y computadoras.
- Etiquetas y descripciones: `aria-label`, `aria-live`, `aria-describedby`, texto alternativo en imágenes y etiquetas asociadas a formularios.
- Soporte de interacción accesible: iconos con texto, botones `focus-visible`, botones grandes y estados claros.

## WCAG y accesibilidad implementadas
Se incorporaron mejoras alineadas con las pautas WCAG, incluyendo:
- WCAG 2.1 AA:
  - Contraste suficiente entre texto y fondo.
  - Texto escalable con ajustes de tamaño.
  - Enfoque visible para cada elemento interactivo.
  - Contenido compatible con lectores de pantalla mediante ARIA y estructura semántica.
- WCAG 2.1 AAA / buenas prácticas:
  - Alternativas textuales descriptivas para imágenes.
  - Opciones de alto contraste activables.
  - Reducción de animaciones y transiciones con opción de desactivarlas.

## Principios de usabilidad aplicados
- Claridad: se presenta contenido directo con encabezados y botones bien identificados.
- Consistencia: estilos de interacción similares en botones, tarjetas y enlaces.
- Feedback: estados visibles en botones, retroalimentación en el panel de accesibilidad y mensajes de estado.
- Control del usuario: se permite personalizar la visualización con opciones de accesibilidad.
- Minimizar la carga cognitiva: diseño limpio, secciones bien definidas y navegación fácil.

## Tecnologías usadas
- HTML5
- CSS con Tailwind CSS CDN
- JavaScript ligero para accesibilidad y control de preferencias.

## Estructura principal
- `index.html`: página principal con diseño, contenido y funcionalidades.
- Enlaces de soporte y accesibilidad anclados a secciones clave.

---

Este repositorio es un ejemplo de cómo construir una landing page de comercio accesible y usable, pensando en la diversidad de perfiles de usuario y en el cumplimiento de pautas de accesibilidad modernas.