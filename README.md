# Fundamentos del Muestreo Estadístico · Universidad El Bosque

Material de estudio autónomo e interactivo sobre **muestreo estadístico**, basado en
*Sampling: Design and Analysis* de **Sharon L. Lohr**. Cada capítulo es una página HTML
independiente con navegación por módulos, fórmulas renderizadas con KaTeX, tablas, ejemplos
resueltos y gráficos interactivos (Chart.js).

🌐 **Sitio web:** https://jotamao1985.github.io/Muestreo-Un_Bosque_JMS/

## Contenido

| # | Capítulo | Temas | Módulos |
|---|----------|-------|:---:|
| 1 | [Introducción al Muestreo](capitulo-1-introduccion.html) | Sesgo de selección y medición, diseño de cuestionarios, tipos de error | 9 |
| 2 | [Muestreo Aleatorio Simple](capitulo-2-muestreo-aleatorio-simple.html) | MAS, intervalos de confianza, tamaño de muestra, muestreo sistemático | 8 |
| 3 | [Estimación de Razón y Regresión](capitulo-3-razon-y-regresion.html) | Variables auxiliares, razón, regresión, diferencia, dominios | 10 |
| 4 | [Muestreo Estratificado](capitulo-4-muestreo-estratificado.html) | Estratos, pesos, asignación, postestratificación, ciencia de datos | 10 |

La portada [`index.html`](index.html) enlaza los cuatro capítulos.

## Tecnología

- HTML estático de un solo archivo por capítulo (sin build, sin dependencias locales).
- [Tailwind CSS](https://tailwindcss.com/) (CDN), [Font Awesome](https://fontawesome.com/),
  [KaTeX](https://katex.org/), [Chart.js](https://www.chartjs.org/) y [Prism](https://prismjs.com/).
- Diseño responsive y accesible (navegación por teclado, `aria-label`, contraste cuidado).

## Despliegue

El sitio se publica con **GitHub Pages** desde la rama `main` (carpeta raíz). El archivo
`.nojekyll` desactiva el procesamiento Jekyll para servir el HTML tal cual.

## Créditos

Diseñado por **Javier Mauricio Sierra** · Universidad El Bosque · 2026.
Contenido basado en Lohr, S.L. *Sampling: Design and Analysis*.
