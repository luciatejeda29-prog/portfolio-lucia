# Portfolio web · Lucía Tejeda

Portfolio personal de diseño UX/UI y front-end. Trabajo Final de Diseño UX-UI, Licenciatura en Sistemas de Información (UADER).

## Enlaces

- **Sitio publicado:** https://luciatejeda29-prog.github.io/portfolio-lucia/
- **Figma (solo lectura):** COMPLETAR_LINK_FIGMA
- **Repositorio:** https://github.com/luciatejeda29-prog/portfolio-lucia

## Concepto

Tres palabras clave: **cercana, clara, cuidada**. Vienen de mi experiencia en atención al público: la interfaz se piensa como un mostrador donde la persona encuentra rápido lo que busca.

## Stack

- HTML5 semántico
- CSS3 puro con variables (`:root`), Flexbox y Grid
- JavaScript vanilla (solo para el menú mobile)
- Tipografías: Bricolage Grotesque y Public Sans (Google Fonts)
- Control de versiones: Git y GitHub
- Despliegue: GitHub Pages

## Estructura

```
├─ index.html
├─ caso-estudio-seguros.html
├─ 404.html
├─ css/styles.css
├─ js/main.js
└─ assets/ (favicon, imágenes)
```

## Accesibilidad y rendimiento

- Enlace "Saltar al contenido", foco visible y navegación por teclado.
- Menú mobile con `aria-expanded` y cierre con Escape.
- Contraste de texto de al menos 4,5:1.
- Respeta `prefers-reduced-motion`.
- Imágenes en WebP con `width` y `height`.
- Lighthouse mobile: COMPLETAR (Performance / Accessibility / Best Practices / SEO)

## Proceso

Usuario objetivo, benchmark, moodboard, arquitectura de información, wireframes, design system, prototipo y test de usabilidad: ver el archivo de Figma y las slides del proceso. COMPLETAR_LINK_SLIDES

## Capturas

| Desktop | Mobile |
| --- | --- |
| ![Desktop](assets/img/captura-desktop.png) | ![Mobile](assets/img/captura-mobile.png) |

## Créditos y recursos

- Diseño y código propios. No se usaron templates de terceros. COMPLETAR si usaste alguno.
- Fuentes: [Google Fonts](https://fonts.google.com/).
- Compresión de imágenes: [Squoosh](https://squoosh.app/).

## Uso de IA

Usé Claude (Anthropic) como asistente para generar la base del HTML, CSS y JavaScript, y borradores de textos. COMPLETAR: qué revisé, probé y modifiqué yo (por ejemplo: cambié la paleta, ajusté los textos con mis datos reales, probé el sitio en mobile y teclado, corregí errores de rutas).

## Despliegue

1. Repositorio público en GitHub con la rama `main`.
2. En **Settings → Pages**: *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
3. Cada `git push` a `main` vuelve a publicar el sitio automáticamente.
4. La URL final está en este README y en la descripción del repositorio.
