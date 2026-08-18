# AI Log — HW04

## Uso de inteligencia artificial

Para esta actividad se utilizó inteligencia artificial como herramienta de apoyo durante el desarrollo del proyecto.

### Tailwind CSS

Se utilizó IA para:

- Convertir estilos CSS anteriores a clases utilitarias de Tailwind CSS.
- Organizar el diseño responsive utilizando los prefijos `sm:`, `md:` y `lg:`.
- Implementar los estilos para tarjetas, botones, formularios, tablas y navegación.
- Implementar el modo oscuro utilizando la variante `dark:`.
- Revisar la estructura del HTML y mejorar la organización de las clases.

La IA no reemplazó completamente el proceso de desarrollo. Se revisó el código y se realizaron ajustes para adaptarlo al diseño del proyecto.

### Wireframes en Figma

La IA se utilizó como apoyo para planificar los diferentes estados de las pantallas del sistema.

Se definieron tres pantallas principales:

1. Dashboard / Inicio
2. Inventario
3. Ventas

Para cada pantalla se diseñaron tres estados:

- Estado vacío.
- Estado con datos.
- Estado de error o validación.

La implementación visual final de los wireframes se realizó en Figma.

## Paleta de colores sugerida

Como referencia se utilizó una paleta basada en el diseño inicial del proyecto:

| Uso | Color |
|---|---|
| Sidebar principal | `#5A3A5B` |
| Acción principal | `#92278F` |
| Acción secundaria | `#61AEBE` |
| Ingresos | `#CCE8C2` |
| Gastos | `#EFB9BD` |
| Ganancia | `#B9DCE3` |
| Ventas | `#E6EFB5` |
| Fondo claro | `#F1F5F9` |

## ¿Qué aprendí sobre Tailwind?

Aprendí que Tailwind permite construir la interfaz directamente utilizando clases utilitarias en el HTML, sin tener que crear una regla CSS independiente para cada elemento.

También aprendí a utilizar los prefijos responsive como `sm:`, `md:` y `lg:` para adaptar la interfaz a diferentes tamaños de pantalla.

Otro aprendizaje importante fue el uso de la variante `dark:` para definir estilos diferentes cuando la página se encuentra en modo oscuro.

Finalmente, aprendí que `localStorage` puede utilizarse junto con Tailwind para guardar la preferencia de tema del usuario y restaurarla cuando se vuelve a cargar la página.

## Cambios realizados sobre las sugerencias de IA

La propuesta inicial se adaptó al diseño existente del proyecto. Se mantuvo principalmente la identidad visual del Figma original, incluyendo el sidebar morado, las tarjetas de resumen y los diferentes colores utilizados para representar ingresos, gastos, ganancia y ventas.

También se ajustaron algunos colores y estructuras para mejorar la legibilidad en modo oscuro y en dispositivos pequeños.