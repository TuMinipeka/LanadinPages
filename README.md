# 🎨 Landing Pages — Galería de Diseños Web
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-brightgreen?style=flat)


**Colección de landing pages modernas, responsivas y listas para usar — con galería de navegación visual**

[🌐 Demo en Vivo](#) · [🐛 Reportar Bug](#) · [⭐ Dale una Estrella](#)

---

## 📋 Tabla de Contenidos

- [Descripción General](#-descripción-general)
- [Características Principales](#-características-principales)
- [Páginas en el Índice](#-páginas-en-el-índice)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Instalación y Configuración](#-instalación-y-configuración)
- [Guía de Estilos](#-guía-de-estilos)
- [Patrones de Diseño Usados](#-patrones-de-diseño-usados)
- [Sistema de Almacenamiento](#-sistema-de-almacenamiento)
- [Pruebas y Validación](#-pruebas-y-validación)
- [Problemas Conocidos](#-problemas-conocidos)
- [Cómo Contribuir](#-cómo-contribuir)
- [Licencia](#-licencia)
- [Autor](#-autor)

---

## 🎯 Descripción General

**Landing Pages Gallery** es un repositorio de diseños web construidos con HTML5 y CSS3 puro. Cada archivo es una landing page independiente con su propio estilo visual, pensada para explorar técnicas modernas de maquetación, tipografía fluida y diseño responsivo.

El proyecto incluye un **índice visual interactivo** (`index.html`) desde el cual se puede previsualizar y acceder a cada diseño en miniatura con un solo clic.

### ✨ Destacados del Proyecto

- 🖼️ **15 Diseños Únicos** en el índice — cada uno con estética y temática propia
- 📱 **100% Responsivos** — adaptados para móvil, tablet y escritorio mediante media queries
- ⚡ **Sin dependencias de JS** — layouts construidos con CSS Grid y Flexbox puros
- 🗂️ **Galería de navegación** — índice con miniaturas de previsualización de cada página
- 🎨 **Variedad de temáticas** — arquitectura, naturaleza, moda, plantas, diseño, viajes y más
- 🧩 **CSS modular** — cada página tiene su propio archivo de estilos independiente
- 🔤 **Tipografía fluida** — uso de `clamp()` para escalar texto sin breakpoints adicionales
- 🌈 **Paletas diversas** — dark mode, light, warm tones, mint green, yellow y más

---

## 🚀 Características Principales

### Layouts y Estructura
- ✅ Diseños de **1, 2 y 3 columnas** con CSS Grid y Flexbox
- ✅ **Hero sections** con imagen de fondo, overlays oscuros y texto superpuesto
- ✅ **Galerías en mosaico** con spans y áreas personalizadas en Grid
- ✅ Layouts con **posicionamiento absoluto/relativo** para elementos decorativos
- ✅ Diseños **full-viewport** (`100vh`) y centrados en pantalla
- ✅ Columnas que se reorganizan verticalmente en dispositivos móviles

### Componentes Visuales
- ✅ **Cards de estadísticas** con números grandes y descripciones
- ✅ Imágenes con forma de **cápsula** (`border-radius: 999px`) y **círculo** (`50%`)
- ✅ **Blobs decorativos** con bordes orgánicos irregulares
- ✅ Elementos flotantes sobre imágenes con superposición de capas (`z-index`)
- ✅ **Logo circular** posicionado absolutamente fuera del card base
- ✅ Efectos de **overlay degradado** sobre imágenes de fondo

### Tipografía y Estética
- ✅ Google Fonts integradas: `Playfair Display`, `DM Sans`, `Cormorant Garamond`, `Nunito`
- ✅ Títulos con **tipografía fluida** usando `clamp(min, vw, max)`
- ✅ Botones tipo **pill** (`border-radius: 50px`) con transiciones hover
- ✅ Paletas variadas con variables CSS (`--verde`, `--marron`, `--accent`, etc.)

### Responsividad
- ✅ Breakpoints en `480px`, `640px`, `768px`, `860px`, `900px` y `1024px`
- ✅ Imágenes que se reordenan y escalan en cada breakpoint
- ✅ Grids que colapsan de múltiples columnas a una sola en móvil
- ✅ Texto que reduce tamaño automáticamente sin desbordamientos

---

## 📄 Páginas en el Índice

Estas son las **15 páginas** que aparecen en la galería principal `index.html`:

| # | Página | Descripción | Temática |
|---|--------|-------------|----------|
| 01 | `page3.html` | Layout editorial: título grande izquierda + texto derecha + imagen full-width | Arquitectura |
| 02 | `page4.html` | Imagen grande izquierda + texto con puntos numerados y botón | Interiorismo |
| 03 | `page6.html` | Hero producto con logo circular, features bar, badges y reloj | Tecnología |
| 04 | `page10.html` | Título tipográfico colorido + grid de 16 imágenes en 4 columnas | Diseño Creativo |
| 05 | `page11.html` | Hero 2 columnas con imágenes + sección features oscura con íconos | Inspiración |
| 06 | `page12.html` | Composición de 3 imágenes con decoraciones: ondas, estrellas y espiral | Lifestyle |
| 07 | `page14.html` | Hero texto izquierda + imagen derecha + tarjeta de 3 estadísticas | Música / App |
| 08 | `page15.html` | Layout 3 columnas con imágenes ovaladas e imágenes de plantas a ambos lados | Naturaleza |
| 09 | `page45.html` | Split 2 columnas: fondo oscuro con texto + columna derecha imagen grande | Diseño |
| 10 | `page33.html` | Hero izquierda con info + galería mosaico en zigzag de 2 columnas | Snacks / Food |
| 11 | `page40.html` | Hero verde menta con blob + imagen planta flotante + 2 cards inferiores | Plantas |
| 12 | `page38.html` | Hero con blob gris + stats numerados + imagen planta + 3 cards inferiores | Plantas |
| 13 | `page41.html` | Split layout: columna izquierda con texto, stats y card + foto full-height | Inmobiliaria |
| 14 | `page50.html` | Hero centrado + galería mosaico con card `large` y `wide` en CSS Grid | Diseño |
| 15 | `page22.html` | 3 secciones: hero cápsulas, imagen + pasos numerados, galería 3 imágenes | Diseño Digital |

---

## 📁 Estructura del Proyecto

```
Landing-Pages/
│
├── 📄 index.html                    # Galería principal con las 15 páginas
│
├── 📁 html/                         # Todas las landing pages individuales
│   ├── page3.html                   # Layout editorial simple
│   ├── page4.html                   # Exploración e inspiración
│   ├── page6.html                   # eWatch — producto tecnológico
│   ├── page10.html                  # Design. Create. Inspire.
│   ├── page11.html                  # New designs, New inspirations
│   ├── page12.html                  # Discover. Explore. Inspire.
│   ├── page14.html                  # Listen to yourself
│   ├── page15.html                  # Adventure Voyage Wandering
│   ├── page22.html                  # Discover the power of design
│   ├── page33.html                  # Ready? Snack time!
│   ├── page38.html                  # Bring GREEN to your home
│   ├── page40.html                  # Love your plants
│   ├── page41.html                  # Dream House
│   ├── page45.html                  # Design, create, and be passionate
│   └── page50.html                  # Beautiful and reliable designs
│
├── 📁 css/                          # Archivos de estilos (uno por página)
│   ├── style.css                    # Estilos del índice principal (galería)
│   ├── style3.css                   # Estilos page3
│   ├── style4.css                   # Estilos page4
│   ├── style6.css                   # Estilos page6
│   ├── style10.css                  # Estilos page10
│   ├── style11.css                  # Estilos page11
│   ├── style12.css                  # Estilos page12
│   ├── style14.css                  # Estilos page14
│   ├── style15.css                  # Estilos page15
│   ├── style22.css                  # Estilos page22
│   ├── styles33.css                 # Estilos page33
│   ├── style38.css                  # Estilos page38
│   ├── style40.css                  # Estilos page40
│   ├── style41.css                  # Estilos page41
│   ├── style45.css                  # Estilos page45
│   └── style50.css                  # Estilos page50
│
└── 📁 image/                        # Recursos multimedia
    ├── 📁 fondos/                   # Miniaturas para el índice (fondo3.png … fondo50.png)
    ├── 📁 pag1/                     # Imágenes reutilizadas entre páginas
    ├── 📁 imagen3/
    ├── 📁 imagen4/
    ├── 📁 imagen6/
    ├── 📁 imagen10/
    ├── 📁 imagen11/
    ├── 📁 imagen12/
    ├── 📁 imagen14/
    ├── 📁 imagen15/
    ├── 📁 image22/
    ├── 📁 image33/
    ├── 📁 image38/
    ├── 📁 image40/
    └── 📁 image41/ …
```

---

## 🛠️ Tecnologías Utilizadas

### Frontend

| Tecnología | Versión | Uso |
|------------|---------|-----|
| **HTML5** | — | Estructura semántica de cada página |
| **CSS3** | — | Layouts, estilos, animaciones y responsividad |
| **CSS Grid** | — | Layouts de múltiples columnas y mosaicos |
| **Flexbox** | — | Alineación de componentes y filas |
| **CSS Custom Properties** | — | Variables de colores, radios y espaciados |
| **Google Fonts** | — | Playfair Display, DM Sans, Cormorant, Nunito, Syne |


### Técnicas CSS Destacadas

```css
/* Tipografía fluida — escala sin necesidad de breakpoints */
font-size: clamp(2rem, 4.5vw, 3.6rem);

/* Padding adaptativo lateral */
padding: 70px clamp(20px, 8vw, 200px);

/* Imagen con forma de cápsula */
border-radius: 0 0 999px 999px;

/* Blob orgánico decorativo */
border-radius: 60% 40% 65% 35% / 48% 60% 40% 52%;

/* Variables CSS para paleta de colores */
:root {
  --verde:      #2d6a2d;
  --marron:     #3a2518;
  --amarillo:   #f5c842;
  --accent:     #60a5fa;
  --radio:      12px;
  --pill:       999px;
}

/* Overlay sobre imagen de fondo */
.hero::before {
  content: '';
  position: absolute;
  inset: 0;
  background: linear-gradient(to bottom, rgba(0,0,0,0.05), rgba(0,0,0,0.65));
}
```

---

## 💻 Instalación y Configuración

### Requisitos Previos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (VS Code recomendado)
- Git (opcional, para clonar el repositorio)
- Extensión **Live Server** para VS Code (recomendado)

### Instalación Local

```bash
# 1️⃣ Clonar el repositorio
git clone https://github.com/tu-usuario/landing-pages.git

# 2️⃣ Navegar a la carpeta del proyecto
cd landing-pages

# 3️⃣ Abrir el índice principal
# Opción A: Abrir index.html directamente en el navegador
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux

# Opción B: Usar Live Server en VS Code
# Click derecho en index.html → "Open with Live Server"
```

### Sin instalación

Puedes abrir cualquier archivo `.html` directamente en tu navegador sin necesidad de servidor local. No requiere instalación de paquetes ni dependencias externas.

---

## 🎨 Guía de Estilos

### Convención de nombrado

Cada página HTML tiene su CSS correspondiente siguiendo la regla:

```
html/pageN.html  →  css/styleN.css
```

La única excepción es `page33.html` que usa `styles33.css` (con "s" al final).

### Paletas de color por página

| Página | Color Principal | Descripción |
|--------|----------------|-------------|
| `page3.html` | `#1a1a1a` / `#fff` | Editorial blanco y negro |
| `page4.html` | `#262626` / `#fff` | Minimalista oscuro |
| `page6.html` | `#635bff` / `#000` | Morado tecnológico |
| `page10.html` | `#222` / `#ff4da6` `#6ac6ff` `#7dff91` | Tipografía colorida dark |
| `page11.html` | `#f7f7f7` / `#1e1e1e` | Claro con sección oscura |
| `page12.html` | `#ffffff` / `#000` | Limpio con posicionamiento |
| `page14.html` | `#fff` / `#3a2518` | Cálido marrón café |
| `page15.html` | `#f9f9f9` / `#2e6a4a` | Verde natural |
| `page22.html` | `#080d1f` / `#9aa0b8` | Dark azul noche |
| `page33.html` | `#ffffff` / `#333` | Neutro limpio |
| `page38.html` | `#fff` / `#2d6a2d` | Verde planta |
| `page40.html` | `#ddecd9` / `#1a1a1a` | Verde menta suave |
| `page41.html` | `#d4e9f5` / `#ebebeb` | Azul claro inmobiliaria |
| `page45.html` | `#fff` / `#000` | Split blanco-negro |
| `page50.html` | `#d3e9f5` → `#f8d9a8` | Gradiente cielo-arena |

### Estructura base de un archivo CSS

```css
/* 1. RESET */
*, *::before, *::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* 2. VARIABLES */
:root {
  --color-primario: #1a1a1a;
  --radio: 12px;
}

/* 3. BODY */
body {
  font-family: 'DM Sans', sans-serif;
  background-color: #fff;
  color: #1a1a1a;
}

/* 4. LAYOUT HERO */
.hero { ... }

/* 5. COMPONENTES */
.card { ... }
.button { ... }

/* 6. RESPONSIVO */
@media (max-width: 768px) { ... }
@media (max-width: 480px) { ... }
```

---

## 🔲 Patrones de Diseño Usados

### 1. Hero con imagen full-width

```css
.hero {
  background-image: url('../image/foto.jpg');
  background-size: cover;
  background-position: center;
  min-height: 100vh;
  position: relative;
}
```

### 2. Logo circular flotante fuera del card

```css
.card {
  position: relative;
  padding-top: 55px;
}
.logo {
  position: absolute;
  top: -42px;
  left: 50%;
  transform: translateX(-50%);
  width: 86px;
  border-radius: 50%;
}
```

### 3. Imagen en cápsula (pill shape)

```css
.hero-images img {
  width: clamp(130px, 18vw, 320px);
  height: clamp(170px, 24vw, 420px);
  object-fit: cover;
  border-radius: 50% 50% 0 0; /* Cápsula abierta por abajo */
}
```

### 4. Grid de galería con mosaico (page50)

```css
.gallery {
  display: grid;
  grid-template-columns: 1fr 1fr 2fr 1fr;
  grid-template-rows: 220px 220px;
  gap: 16px;
}
.card.large { grid-column: 3; grid-row: 1 / 3; }
.card.wide  { grid-column: 1 / 3; grid-row: 2; }
```

### 5. Stats pill flotante (page9 / page11)

```css
.stats {
  position: absolute;
  left: 260px;
  right: 20px;
  bottom: -10rem;
  background: var(--pill-bg);
  border-radius: 64px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  z-index: 4;
}
```

### 6. Blob decorativo detrás de imagen (page38 / page40)

```css
.plant-hero::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 56%;
  height: 90%;
  background-color: var(--gris-fondo);
  border-radius: 0 0 50% 0;
  z-index: 0;
}
```

---

## 🗂️ Sistema de Almacenamiento

Este proyecto es completamente **estático** — no requiere base de datos ni backend. Todas las páginas son HTML y CSS puro que se ejecutan directamente en el navegador.

### Fuentes de datos usadas

```
Texto:     Lorem Ipsum (placeholder estándar de diseño)
Imágenes:  Archivos locales en /image/ organizados por página
Íconos:    Font Awesome CDN (solo en páginas que lo requieren)
Fuentes:   Google Fonts CDN (cargadas en el <head> de cada página)
```

### Estructura de miniaturas del índice

Cada página listada en `index.html` necesita su miniatura en la carpeta `image/fondos/`:

```
image/fondos/fondo3.png    →  Miniatura de page3.html
image/fondos/fondo4.png    →  Miniatura de page4.html
image/fondos/fondo6.png    →  Miniatura de page6.html
image/fondos/fondo10.png   →  Miniatura de page10.html
image/fondos/fondo11.png   →  Miniatura de page11.html
image/fondos/fondo12.png   →  Miniatura de page12.html
image/fondos/fondo14.png   →  Miniatura de page14.html
image/fondos/fondo15.png   →  Miniatura de page15.html
image/fondos/fondo22.png   →  Miniatura de page22.html
image/fondos/fondo33.png   →  Miniatura de page33.html
image/fondos/fondo38.png   →  Miniatura de page38.html
image/fondos/fondo40.png   →  Miniatura de page40.html
image/fondos/fondo41.png   →  Miniatura de page41.html
image/fondos/fondo45.png   →  Miniatura de page45.html
image/fondos/fondo50.png   →  Miniatura de page50.html
```

> 💡 **Tamaño recomendado para miniaturas:** 800×450px (relación 16:9), formato `.png` o `.webp`

---

## 🧪 Pruebas y Validación

### Verificar el índice principal

```
1. Abrir index.html en el navegador
2. Confirmar que aparecen las 15 miniaturas correctamente
3. Hacer clic en cada miniatura y verificar que abre la página correcta en una nueva pestaña
4. Verificar que el layout del índice es responsive (3 → 2 → 1 columna)
```

### Checklist de responsividad por página

```
✅ El layout se adapta en pantallas de 1200px (desktop)
✅ Las columnas colapsan correctamente en 768px (tablet)
✅ El texto no se desborda en 480px (móvil)
✅ Las imágenes mantienen proporción con object-fit: cover
✅ Los botones son accesibles y tapables en touch
✅ El scroll es vertical y nunca horizontal
✅ Las fuentes de Google Fonts cargan correctamente con conexión
```

### Herramientas de prueba recomendadas

- **Chrome DevTools** → `F12` → Toggle Device Toolbar para simular móviles
- **Firefox Responsive Design Mode** → `Ctrl+Shift+M`
- **W3C Validator** → https://validator.w3.org para validar el HTML
- **CSS Validator** → https://jigsaw.w3.org/css-validator para validar los estilos

### Breakpoints a probar

| Resolución | Dispositivo | Resultado Esperado |
|------------|-------------|-------------------|
| 1280px | Desktop | Layout completo en múltiples columnas |
| 1024px | Tablet horizontal | Columnas reducidas, imágenes más pequeñas |
| 768px | Tablet vertical | 1–2 columnas, elementos apilados |
| 480px | Móvil | Una sola columna, tipografía reducida |
| 375px | Móvil pequeño | Espaciados mínimos, botones full-width |

---

## 🐛 Problemas Conocidos

### Limitaciones Actuales

**Rutas de imágenes**
- Las páginas usan rutas relativas (`../image/`) que dependen de la estructura de carpetas
- Si se mueve un archivo HTML fuera de `html/`, las imágenes dejarán de cargar

**Font Awesome**
- `page22.html`, `page33.html` y otras dependen del CDN de Font Awesome
- Sin conexión a internet, los íconos no se mostrarán

**Google Fonts**
- Las páginas con `Playfair Display`, `DM Sans`, etc., requieren conexión a internet
- Sin ella, el navegador usará la fuente fallback definida en el CSS

**Miniaturas del índice**
- Si una miniatura en `image/fondos/` no existe, aparecerá un espacio vacío en el índice

### Funcionalidades Pendientes

- [ ] Filtro por categoría en el índice (diseño, naturaleza, tecnología, etc.)
- [ ] Modo oscuro / claro en el índice principal
- [ ] Animaciones de entrada al hacer hover en las miniaturas
- [ ] Botón de pantalla completa para previsualización dentro del índice
- [ ] Optimización de imágenes con formato `.webp`
- [ ] Barra de búsqueda por nombre de página

```

### Guía de Estilo para nuevas páginas

- Usar nombres de clases descriptivos de forma consistente
- Incluir reset básico (`*`, `box-sizing`) al inicio del CSS
- Declarar variables CSS en `:root` cuando se repitan valores de color o espaciado
- Usar `clamp()` para tipografía fluida en lugar de múltiples breakpoints
- Mínimo 2 breakpoints responsive: `768px` (tablet) y `480px` (móvil)
- Probar en Chrome DevTools antes de hacer commit
- Mantener el CSS de cada página en su propio archivo independiente

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.

```
MIT License

Copyright (c) 2026 Daniel Mayorga

Se concede permiso, de forma gratuita, a cualquier persona que obtenga una copia
de este software y archivos de documentación asociados (el "Software"), para
utilizar el Software sin restricciones, incluyendo sin limitación los derechos
de usar, copiar, modificar, fusionar, publicar, distribuir, sublicenciar, y/o
vender copias del Software, sujeto a las siguientes condiciones:

El aviso de copyright anterior y este aviso de permiso se incluirán en todas
las copias o porciones sustanciales del Software.
```

Ver archivo `LICENSE` para más detalles.

---



---

## 🌟 Agradecimientos

Este proyecto fue desarrollado como ejercicio de aprendizaje en diseño y maquetación web frontend.

**Recursos y Referencias:**
- [MDN Web Docs](https://developer.mozilla.org) — Documentación de HTML y CSS
- [CSS Tricks](https://css-tricks.com) — Guías de Grid, Flexbox y técnicas avanzadas
- [Google Fonts](https://fonts.google.com) — Tipografías utilizadas en los diseños
- [Font Awesome](https://fontawesome.com) — Iconografía vectorial
- [W3Schools](https://w3schools.com) — Tutoriales y ejemplos de referencia

**Inspiración de Diseño:**
- Tendencias de UI en Dribbble y Behance
- Layouts editoriales de revistas digitales
- Páginas de producto de marcas modernas

---

## 📞 Soporte y Contacto

**¿Encontraste un bug o tienes una sugerencia?**

- 🐛 **Reportar Bug:** [GitHub Issues](#)
- 💬 **Preguntas:** [GitHub Discussions](#)

### FAQ

**¿Por qué no carga una imagen en el índice?**
```
Verificar que existe el archivo image/fondos/fondoN.png
La ruta debe ser exactamente esa desde la raíz del proyecto.
```

**¿Por qué no se ven los íconos de Font Awesome?**
```
Las páginas que usan Font Awesome requieren conexión a internet.
Verificar que el CDN esté incluido en el <head>:
<link rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
```

**¿Cómo agrego una nueva página al índice?**
```
1. Crear html/pageN.html con su diseño
2. Crear css/styleN.css con sus estilos
3. Agregar miniatura en image/fondos/fondoN.png
4. Copiar y adaptar el bloque <a> en index.html
```

**¿Puedo usar estas páginas en proyectos reales?**
```
Sí, el proyecto tiene Licencia MIT.
Puedes usar, modificar y distribuir libremente
siempre que incluyas el aviso de copyright original.
```

---

<div align="center">

**🌐 [Ver Galería](#) · 📁 [Ver Repositorio](#) · ⭐ [Dale una Estrella](#)**

Desarrollado con ❤️ por **Daniel Mayorga**

</div>