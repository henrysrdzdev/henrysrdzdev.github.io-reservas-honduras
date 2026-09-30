---
name: "Archivo Mundial"
description: "Atlas táctico y editorial de la historia completa de los Mundiales."
colors:
  pitch-black: "#04110d"
  archive-field: "#071b15"
  tactical-panel: "#0c261e"
  deep-panel: "#0e2a21"
  active-field: "#13362a"
  field-line: "#315244"
  field-line-strong: "#456b59"
  chalk-ivory: "#f4efdf"
  bright-chalk: "#fffaf0"
  copy-sage: "#c8d8ce"
  muted-sage: "#9db8aa"
  champion-gold: "#d4ab4f"
  archive-gold-link: "#f0c96e"
  scoreboard-blue: "#55a9c7"
  ink-green: "#102018"
typography:
  display:
    fontFamily: "Barlow Semi Condensed, Arial Narrow, sans-serif"
    fontSize: "clamp(3.5rem, 9vw, 6rem)"
    fontWeight: 700
    lineHeight: 0.84
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "Barlow Semi Condensed, Arial Narrow, sans-serif"
    fontSize: "clamp(2.3rem, 5vw, 4.6rem)"
    fontWeight: 700
    lineHeight: 0.95
    letterSpacing: "-0.025em"
  title:
    fontFamily: "Barlow Semi Condensed, Arial Narrow, sans-serif"
    fontSize: "clamp(1.5rem, 2.5vw, 2.25rem)"
    fontWeight: 700
    lineHeight: 1
  body:
    fontFamily: "Barlow Semi Condensed, Arial Narrow, sans-serif"
    fontSize: "clamp(1.05rem, 1.7vw, 1.25rem)"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "Barlow Semi Condensed, Arial Narrow, sans-serif"
    fontSize: "0.82rem"
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: "0.04em"
rounded:
  square: "0px"
  marker: "50%"
spacing:
  micro: "8px"
  compact: "10px"
  control-x: "13px"
  table-y: "14px"
  control: "18px"
  gutter: "clamp(20px, 5vw, 72px)"
  section-y: "clamp(52px, 8vw, 104px)"
components:
  button-primary:
    backgroundColor: "{colors.chalk-ivory}"
    textColor: "{colors.ink-green}"
    typography: "{typography.label}"
    rounded: "{rounded.square}"
    padding: "13px 18px"
  button-primary-hover:
    backgroundColor: "{colors.bright-chalk}"
    textColor: "{colors.ink-green}"
  button-portal:
    backgroundColor: "{colors.champion-gold}"
    textColor: "{colors.ink-green}"
    typography: "{typography.label}"
    rounded: "{rounded.square}"
    padding: "10px 16px"
  nav-link:
    backgroundColor: "transparent"
    textColor: "{colors.copy-sage}"
    typography: "{typography.label}"
    rounded: "{rounded.square}"
    padding: "9px 13px"
  nav-link-active:
    backgroundColor: "{colors.active-field}"
    textColor: "{colors.chalk-ivory}"
---

# Design System: Archivo Mundial

## Overview

**Creative North Star: "El Atlas Táctico de Archivo"**

Archivo Mundial convierte la historia del torneo en un campo nocturno que se puede leer: capas de verde profundo funcionan como césped y archivo, las líneas finas ordenan el contenido como marcas tácticas y el dorado señala logros o rutas prioritarias. La densidad es editorial y espaciosa, con datos abundantes pero jerarquizados mediante escala, columnas y numerales tabulares.

El sistema se siente preciso, educativo y apasionado. La fotografía entra como recorte documental amplio, nunca como decoración menor; la interfaz evita la portada deportiva genérica centrada en un trofeo y las cuadrículas de tarjetas intercambiables.

**Key Characteristics:**

- Campo casi negro en capas verdes, con tiza marfil y líneas visibles.
- Titulares condensados, mayúsculos y de gran escala; datos con numerales tabulares.
- Dorado reservado para campeones, rutas y acciones prioritarias; azul para actualidad y foco.
- Composición editorial de ancho amplio, divisores rectos y progresiones cronológicas.
- Fotografías documentales de borde a borde o en recortes grandes con pies de imagen.

## Colors

La paleta reproduce un campo nocturno impreso como archivo: verdes profundos sostienen la lectura, el marfil actúa como tiza y dos acentos separan mérito histórico de señal contemporánea.

### Primary

- **Dorado de campeón** (`champion-gold`): destaca cifras ganadoras, rutas tácticas, bordes de hitos y el acceso persistente al portal.

### Secondary

- **Azul de marcador** (`scoreboard-blue`): aparece con moderación en focos accesibles, hitos modernos y el dato que necesita distinguirse del archivo histórico.

### Neutral

- **Negro de cancha** (`pitch-black`) y **campo de archivo** (`archive-field`): fondo exterior y lienzo principal.
- **Panel táctico** (`tactical-panel`), **panel profundo** (`deep-panel`) y **campo activo** (`active-field`): capas de sección, tarjetas documentales y navegación seleccionada.
- **Tiza marfil** (`chalk-ivory`) y **tiza brillante** (`bright-chalk`): texto principal, titulares y acciones claras.
- **Salvia de lectura** (`copy-sage`) y **salvia atenuada** (`muted-sage`): párrafos, notas y pies de imagen.
- **Línea de campo** (`field-line`) y **línea reforzada** (`field-line-strong`): divisores, bordes y estructura tabular.
- **Tinta verde** (`ink-green`): texto sobre superficies claras o doradas.

### Named Rules

**The Medal and Marker Rule.** El dorado comunica historia, mérito o ruta prioritaria; el azul comunica foco, actualidad o una excepción contemporánea. No deben competir como acentos equivalentes.

**The Dark Field Rule.** El contenido ordinario permanece sobre verdes profundos; las superficies claras se reservan para acciones y bandas de énfasis, no para tarjetas dispersas.

## Typography

**Display Font:** Barlow Semi Condensed (con Arial Narrow y sans-serif como respaldo)  
**Body Font:** Barlow Semi Condensed (con Arial Narrow y sans-serif como respaldo)  
**Label/Mono Font:** Barlow Semi Condensed con numerales tabulares para fechas, marcadores y estadísticas

**Character:** Una sola familia condensada une la voz editorial y la precisión estadística. El contraste nace de la escala, el peso, las mayúsculas y el espaciado, no de mezclar familias decorativas.

### Hierarchy

- **Display** (700, `clamp(3.5rem, 9vw, 6rem)`, 0.84): títulos de portada y aperturas de página, siempre en mayúsculas y con ajuste estrecho.
- **Headline** (700, `clamp(2.3rem, 5vw, 4.6rem)`, 0.95): encabezados de sección con máximo visual aproximado de 900px.
- **Title** (700, `clamp(1.5rem, 2.5vw, 2.25rem)`, 1): títulos de era, escena y bloque comparativo.
- **Body** (400, `clamp(1.05rem, 1.7vw, 1.25rem)`, 1.5): narrativa principal, limitada normalmente a 62–72 caracteres.
- **Label** (700, `0.82rem`, `0.04em`, mayúsculas cuando nombra categorías): navegación compacta, metadatos y rótulos de datos.

### Named Rules

**The One-Family Rule.** Toda la jerarquía usa Barlow Semi Condensed; los cambios de voz se logran con escala, peso y caja.

**The Tabular Archive Rule.** Fechas, títulos, resultados y coordenadas usan numerales tabulares para conservar alineación y lectura comparativa.

## Layout

El lienzo ocupa casi todo el viewport con un margen exterior de 12px y un máximo de 1480px. El contenido editorial usa un contenedor de 1320px; las secciones aplican un canal horizontal fluido (`clamp(20px, 5vw, 72px)`) y una respiración vertical amplia (`clamp(52px, 8vw, 104px)`). Las cuadrículas se adaptan mediante `auto-fit` con mínimos recurrentes de 280px, 360px, 420px o 430px según la carga de lectura.

La navegación envuelve sus enlaces antes de perder legibilidad. Bajo 780px reduce el eje cronológico y la escala del display; bajo 600px las composiciones divididas se convierten en una columna, la cronología abandona su raíl lateral y la línea táctica del hero desaparece. Tablas y archivos densos conservan sus columnas y ofrecen desplazamiento horizontal enfocable.

**The Field Progression Rule.** Las secuencias históricas avanzan como recorridos: eje, línea, coordenadas o bandas continuas; no como una colección de tarjetas aisladas.

## Elevation & Depth

El sistema no usa sombras. La profundidad se construye con capas tonales de verde, fotografías oscurecidas, bordes de 1px y alternancia de filas. El movimiento vertical de 2px en acciones y el dibujo de la ruta del hero comunican respuesta sin simular elevación material.

### Named Rules

**The No-Shadow Rule.** Ninguna superficie obtiene jerarquía mediante `box-shadow`; use contraste tonal, borde o escala tipográfica.

**The Structural Line Rule.** Las líneas son arquitectura: separan eras, tablas y regiones funcionales con trazos de 1px, dorados para hitos o verdes para estructura neutral.

## Shapes

La forma dominante es rectangular y de esquina cuadrada. Botones, enlaces activos, paneles, tablas e imágenes no redondean sus bordes. El único círculo recurrente es el marcador de marca y los nodos de una ruta táctica; su geometría pertenece al lenguaje de cancha, no a un sistema de tarjetas redondeadas.

## Components

### Buttons

- **Shape:** rectángulos compactos de esquina cuadrada (`0px`).
- **Primary:** tiza marfil sobre tinta verde, con relleno (`13px 18px`) y peso 700.
- **Hover / Focus:** ascenso de 2px y cambio a tiza brillante; todo foco visible usa un contorno azul de 3px separado 4px.
- **Portal:** dorado de campeón sobre tinta verde, con borde dorado y relleno (`10px 16px`); es una acción persistente, no una variante ornamental.

### Cards / Containers

- **Corner Style:** cuadrado, sin redondeo.
- **Background:** paneles verde profundo sobre el campo de archivo, o estructura abierta sin relleno.
- **Shadow Strategy:** ninguna sombra; la separación depende de bordes y cambio tonal.
- **Border:** línea de campo de 1px; el dorado marca hitos y el azul una excepción moderna.
- **Internal Padding:** paneles editoriales entre 22px y 36px; bloques de era usan relleno fluido de 38px a 78px.

### Navigation

La barra es un panel táctico con borde inferior. Los enlaces usan peso 700, espaciado compacto y borde transparente; hover y activo añaden fondo de campo activo y línea reforzada. En móvil la marca ocupa su propia fila y los enlaces se centran sin ocultarse.

### Chronology & Coordinates

La cronología combina una columna de año con contenido separado por una línea vertical; las coordenadas presentan cada edición como una casilla documental dentro de un campo. En pantallas estrechas ambos patrones se apilan, pero conservan el orden temporal, el contraste y los numerales tabulares.

### Archive Table

La tabla usa cabecera dorada con tinta verde, filas verdes alternadas, separadores de 1px y celdas de `14px 15px`. Se conserva ancha en móvil dentro de un contenedor desplazable con foco visible.

## Do's and Don'ts

### Do:

- **Do** use verde oscuro como continuidad de fondo y cambios tonales para distinguir secciones.
- **Do** reserve el dorado para campeones, rutas y acciones prioritarias, y el azul para foco o actualidad.
- **Do** construya jerarquía con titulares condensados, datos tabulares, líneas de 1px y espacios amplios.
- **Do** trate cronologías y comparaciones como progresiones continuas que se mantienen legibles en móvil.
- **Do** use recortes fotográficos amplios con texto alternativo, borde de archivo y pie explicativo.

### Don't:

- **Don't** añada sombras, degradados, vidrio esmerilado ni radios suaves a las superficies.
- **Don't** convierta el archivo en una cuadrícula de tarjetas iguales o en una portada centrada alrededor de un trofeo.
- **Don't** use dorado y azul con la misma frecuencia ni como decoración sin significado.
- **Don't** introduzca otra familia tipográfica o iconos de glifo donde bastan texto, líneas y marcadores geométricos.
- **Don't** sacrifique navegación, contraste o acceso a datos al adaptar la interfaz a pantallas estrechas.
