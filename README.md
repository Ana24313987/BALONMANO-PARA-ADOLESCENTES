[README.md](https://github.com/user-attachments/files/28292203/README.md)
# 🤾 Balonmano Pro — Guía Interactiva

Herramienta educativa interactiva sobre reglas y tácticas de balonmano, diseñada para adolescentes. Desarrollada como página web estática con enfoque en accesibilidad y aprendizaje activo.

## ✨ Características

- **Sección de reglas**: Las 4 reglas fundamentales del balonmano explicadas de forma visual y concisa.
- **Diagrama de cancha**: SVG técnico e interactivo con las zonas tácticas etiquetadas (área de 6m, línea de 9m, penalti de 7m).
- **Ilustraciones SVG propias**: Escenas de juego dibujadas en código (jugador lanzando, corriendo, suspensión), sin dependencia de imágenes externas.
- **Quiz táctico**: 4 preguntas con retroalimentación inmediata y mensajes personalizados según la respuesta.
- **Animaciones de entrada**: Secciones con fade-in por scroll usando `IntersectionObserver`.
- **Diseño responsivo**: Adaptado para móvil, tablet y escritorio.
- **Accesibilidad WCAG**: Roles ARIA, `aria-live`, tamaños mínimos de toque (44px), contraste adecuado y soporte para `prefers-reduced-motion`.

## 📁 Estructura del proyecto

```
balonmano_pro.html   # Archivo único autocontenido (HTML + CSS + JS)
README.md            # Este archivo
```

## 🚀 Cómo usar

No requiere instalación ni servidor. Abre directamente en cualquier navegador moderno:

```bash
# Opción 1: doble clic sobre el archivo
balonmano_pro.html

# Opción 2: desde terminal
open balonmano_pro.html        # macOS
start balonmano_pro.html       # Windows
xdg-open balonmano_pro.html    # Linux
```

## 🛠️ Tecnologías

| Tecnología | Uso |
|---|---|
| HTML5 semántico | Estructura y accesibilidad |
| CSS3 (variables, grid, flexbox) | Layout y diseño |
| SVG inline | Ilustraciones de balonmano |
| JavaScript vanilla | Quiz, animaciones, IntersectionObserver |
| Google Fonts (Montserrat + Inter) | Tipografía |

## 🎨 Diseño

Paleta oscura inspirada en interfaces de alto rendimiento deportivo:

| Variable | Color |
|---|---|
| `--bg` | `#0A192F` — fondo principal |
| `--accent` | `#64FFDA` — verde agua, énfasis |
| `--danger` | `#FF6B6B` — rojo, errores y balón |
| `--muted` | `#8892B0` — texto secundario |

## ♿ Accesibilidad

- Etiquetas `aria-label` en secciones de navegación y SVG
- `aria-live="polite"` en los mensajes de feedback del quiz
- Soporte completo para `prefers-reduced-motion`
- Tamaños mínimos de área táctil de 44×44px en todos los botones
- Contraste de color alineado con WCAG 2.1 nivel AA

## 👩‍💻 Autora

**Ana Cuadros Valeriano**  
Diseño Instruccional y Desarrollo  
Herramienta desarrollada bajo lineamientos DUA (Diseño Universal para el Aprendizaje) y estándares de accesibilidad WCAG.
