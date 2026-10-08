# Recursividad

Sitio estático en `index.html`, sin dependencias, listo para GitHub Pages.

La explicación está enfocada en la materia Estructura de Datos e incluye programas introductorios en Java para factorial, Fibonacci, Torres de Hanói, recorrido de listas enlazadas, recorrido de árboles binarios y el fractal de Sierpiński. Los controles web utilizan JavaScript solo para mostrar las visualizaciones interactivas.

La página incluye una sección de publicación con los pasos para activar GitHub Pages, el formato esperado del enlace y una nota clara de que el sitio todavía no tiene una URL pública hasta completar ese despliegue. También ofrece un enlace para saltar al contenido y controles etiquetados para facilitar la navegación con teclado y tecnologías de asistencia.

## Personalizar y publicar

1. La página ya contiene los nombres de los cinco integrantes del equipo.
2. Sube `index.html` y este `README.md` a la raíz de un repositorio de GitHub.
3. En el repositorio, abre **Settings → Pages**; en **Build and deployment**, selecciona **Deploy from a branch**, elige la rama `main` y la carpeta `/ (root)`, y guarda.
4. Espera a que termine la publicación. GitHub Pages mostrará el enlace del sitio en esa misma sección.

## Crear el PDF para entregar

Abre `index.html` en un navegador y usa el botón **Guardar como PDF** (o `Ctrl+P`). Selecciona **Guardar como PDF** como destino. La hoja de estilos de impresión prepara la página para exportarse e incluye las referencias bibliográficas.

## Probar los ejemplos Java

Cada programa se muestra completo en la página. Copia el ejemplo en un archivo con el nombre de su clase pública (por ejemplo, `Factorial.java`) y compílalo con `javac Factorial.java`; ejecútalo con `java Factorial`. El ejemplo de Fibonacci está limitado a n ≤ 30 para que su versión recursiva sencilla termine en un tiempo razonable.
