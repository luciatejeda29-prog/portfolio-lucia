# Portfolio web · Lucía Tejeda

Portfolio personal de diseño UX/UI y desarrollo web. Trabajo Final de Diseño UX-UI, Licenciatura en Sistemas de Información (UADER).

## Enlaces

- **Sitio publicado:** https://luciatejeda29-prog.github.io/portfolio-lucia/
- **Figma (solo lectura):** https://www.figma.com/design/p3VqPTWBE3YhFzxBgKKbXQ/Moodboard
- **Repositorio:** https://github.com/luciatejeda29-prog/portfolio-lucia

## Concepto

Tres palabras clave: **cercana, clara, cuidada**. Surgen de mi experiencia en atención al público: la interfaz se piensa como un mostrador donde la persona encuentra rápido lo que busca.

## Stack

- HTML5 semántico
- CSS3 puro con variables (`:root`), Flexbox y Grid
- JavaScript vanilla (solo para el menú mobile)
- Tipografías: Bricolage Grotesque (títulos) y Public Sans (textos), de Google Fonts
- Control de versiones: Git y GitHub
- Despliegue: GitHub Pages

## Estructura

```
├─ index.html
├─ caso-estudio-seguros.html
├─ 404.html
├─ css/styles.css
├─ js/main.js
└─ assets/ (favicon e imágenes)
```

## Accesibilidad y rendimiento

- Enlace "Saltar al contenido", foco visible y navegación por teclado.
- Menú mobile con `aria-expanded` y cierre con la tecla Escape.
- Contraste de texto de al menos 4,5:1 en las combinaciones de color usadas.
- Respeta `prefers-reduced-motion`.
- Imágenes con texto alternativo y dimensiones declaradas.
- **Lighthouse mobile:** Performance 96 · Accessibility 100 · Best Practices 100 · SEO 100

## Proceso

El proceso completo está en el archivo de Figma (moodboard, design system, wireframes y prototipo) y en las slides de la entrega. Resumen:

1. **Benchmark** de tres portfolios: Bruno Simon, Brittany Chiang y Lynn Fisher.
2. **Concepto visual:** paleta, tipografías y estilo de imágenes definidos a partir de las tres palabras clave.
3. **Arquitectura de información:** sitemap de nueve secciones y card sorting con tres personas. Resultado: se agregó el nombre junto al logo y las redes al pie de página.
4. **Test de usabilidad** con tres personas y cinco tareas: 13 de 15 pruebas se completaron sin dificultad. Resultado: se movió la etiqueta de disponibilidad debajo del subtítulo y se renombró "Skills" a "Habilidades" en el menú.

## Créditos y recursos

- Diseño y código propios, sin templates de terceros.
- Fuentes: [Google Fonts](https://fonts.google.com/).
- Imágenes: retrato propio.

## Uso de IA

Usé herramientas de IA como apoyo: Claude (Anthropic), ChatGPT (OpenAI) y el agente de IA de Figma.

- **Qué hizo la IA:** me ayudó con el diseño, el código y la organización del trabajo. Por ejemplo, propuestas de estructura, la base del HTML, CSS y JavaScript, borradores de textos y documentos del proceso, y la generación inicial del design system y de los wireframes en Figma.
- **Qué hice yo:** la investigación (benchmark, card sorting y test de usabilidad con personas reales), la información y los textos con mis datos, los cambios de detalle y las decisiones en general, como el concepto, la paleta y los ajustes a partir de los resultados del test. También publiqué el sitio en GitHub Pages y corregí los problemas de rutas y archivos que aparecieron.

## Despliegue

1. Repositorio público en GitHub, rama `main`.
2. En **Settings → Pages**: *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
3. Cada `git push` a `main` vuelve a publicar el sitio automáticamente.
