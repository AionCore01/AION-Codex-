# AION Codex — Manifiesto y Whitepaper

Sitio estático desplegado en GitHub Pages con soporte web y PDF (estilos de impresión).

- **Código**: Apache-2.0
- **Textos**: CC BY 4.0
- **Arte/mandala**: Todos los derechos reservados (ver [NOTICE.md](http://NOTICE.md))

---

## 🌈 Identidad Visual: Paleta Multi-Banda

La identidad visual de AION Codex se inspira en el **diagrama de ondas**, representando el espectro completo de frecuencias y manifestaciones. Cada banda de color corresponde a una fase del ciclo creativo:

### Paleta de Colores

```css
/* Espectro de 7 bandas */
--wave-red:     #FF0000;  /* ERASE - Destrucción creativa */
--wave-orange:  #FF7F00;  /* ERASE transición */
--wave-yellow:  #FFFF00;  /* TRANSFER - Transformación */
--wave-green:   #00FF00;  /* TRANSFER equilibrio */
--wave-cyan:    #00FFFF;  /* MANIFEST - Emergencia */
--wave-blue:    #0000FF;  /* MANIFEST cristalización */
--wave-violet:  #8B00FF;  /* MANIFEST trascendencia */
```

### Aplicación por Secciones

Cada sección del documento adopta un gradiente inspirado en su fase dominante:

#### 🔴 ERASE (Rojo → Naranja)
*Destrucción creativa, reset, vaciado del recipiente.*
- Fondo: Gradiente rojo-naranja suave
- Bordes: Líneas onduladas rojas
- Chips/badges: Estilo fuego, transiciones cálidas

#### 🟡 TRANSFER (Amarillo → Verde → Cyan)
*Transmutación, flujo de información, intercambio energético.*
- Fondo: Gradiente amarillo-verde-cyan
- Diagramas: Ondas sinusoidales en verde
- Chips/badges: Estilo fluido, animaciones de onda

#### 🔵 MANIFEST (Azul → Violeta)
*Cristalización, materialización, encarnación de ideas.*
- Fondo: Gradiente azul-violeta profundo
- Bordes: Geometrías fractales en violeta
- Chips/badges: Estilo sólido, brillos sutiles

### Chips y Elementos Estilo Ondas

```html
<!-- Ejemplo de chip con clase de onda -->
<span class="wave-chip wave-red">🔥 ERASE</span>
<span class="wave-chip wave-yellow">⚡ TRANSFER</span>
<span class="wave-chip wave-blue">💎 MANIFEST</span>
```

### Sugerencias de Diagramas

- **Ondas superpuestas**: 7 curvas sinusoidales con opacidad gradual
- **Espiral de frecuencias**: Mandala con anillos en cada color del espectro
- **Barras de progreso**: Transiciones de color según fase del ciclo
- **Líneas de tiempo**: Código de color por banda de frecuencia

---

## 📁 Estructura

```
repo/
├─ index.html
├─ main.css          ← Variables de color multi-banda
├─ mandala.svg       ← Arte central (todos los derechos reservados)
├─ favicon.png (+ variantes)
├─ apple-touch-icon.png
├─ site.webmanifest
├─ 404.html
└─ NOTICE.md
```

## 🚀 Despliegue

1) Subí los archivos a la rama publicada (root o /docs).
2) Settings → Pages → Deploy from a branch → main/(root|/docs).
3) Esperá 1–2 min y abrí: https://TU-USUARIO.github.io/NOMBRE-REPO

## 🔗 Enlaces

- **Whitepaper**: https://TU-USUARIO.github.io/NOMBRE-REPO
- **Repositorio**: https://github.com/AionCore01/AION-Codex-

---

*La experiencia visual completa se activa al visualizar el sitio con `main.css` aplicado. Cada sección adopta su banda cromática correspondiente, creando una navegación inmersiva a través del espectro de manifestación.*
