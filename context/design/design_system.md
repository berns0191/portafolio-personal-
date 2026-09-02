# 📐 Sistema de Diseño & Lineamientos Estéticos

> **Inspirado en:** *Ferrari Movie, DID Global Cinema, Monolog, Half of 8 y Refero Design.*  
> **Tema:** Dark Cinematic Editorial / High-Performance Data.

---

## 🎨 Paleta de Colores (Color Palette)

| Nombre del Token | Hex Code | Uso Principal |
| :--- | :--- | :--- |
| `--bg-primary` | `#08080A` | Fondo principal (Dark profundo / Obsidian) |
| `--bg-secondary` | `#121216` | Fondos de tarjetas, paneles y contenedores |
| `--bg-tertiary` | `#1C1C24` | Hover states, bordes sutiles y modales |
| `--text-primary` | `#F5F5F7` | Encabezados, títulos principales y números destacados |
| `--text-secondary` | `#8E8E93` | Párrafos descriptivos, metadatos y subtítulos |
| `--accent-red` | `#E50914` / `#FF2A2A` | Acento de alta energía / adrenalina (estilo Ferrari/deportes de contacto) |
| `--accent-emerald` | `#00E599` / `#10B981` | Acento financiero / crecimiento bursátil y agroindustria |
| `--border-subtle` | `rgba(255, 255, 255, 0.08)` | Separadores y bordes ultrafinos |

---

## 🔤 Tipografía (Typography Hierarchy)

- **Encabezados (Display / Titles):**
  - *Fuentes recomendadas:* `Syne`, `Clash Display`, `Cabinet Grotesk` o `Inter Tight` (Heavy / Black weight).
  - *Estilo:* Mayúsculas con tracking ajustado o contraste tipográfico editorial.
- **Cuerpo de Texto (Body / Sans):**
  - *Fuentes recomendadas:* `Geist Sans`, `Inter`, o `Satoshi`.
  - *Estilo:* Legibilidad óptima en fondos oscuros (peso 400/500, tamaño 15-17px, line-height 1.6).
- **Métricas / Código / Finanzas (Mono):**
  - *Fuentes recomendadas:* `Geist Mono`, `JetBrains Mono` o `Space Mono`.
  - *Estilo:* Datos numéricos, tickers bursátiles, coordenadas y estadísticas.

---

## ⚡ Principios de Movimiento & Animación (Motion)

1. **Entradas Cinematográficas:** Fade-in con deslizamiento vertical suave (`y: 20 -> 0`, `opacity: 0 -> 1`, duración 0.6s con curvas `cubic-bezier(0.16, 1, 0.3, 1)`).
2. **Hover States Magnéticos:** Aceleración rápida y desaceleración fluida en botones y tarjetas interactivas.
3. **Scroll Reactivo:** Elementos en parallax sutil o revelación progresiva al hacer scroll (inspirado en *Half of 8* y *DID Cinema*).

---

## 🧱 Componentes Clave

- **Cinematic Hero:** Título de gran escala, video de fondo o gradiente reactivo, tagline dinámico y CTA directo.
- **Financial & Data Grid:** Tarjetas con métricas clave (mercados de futuros, bolsa, operaciones de invernaderos) con gráficos sparkline o visualizaciones BI.
- **Editorial Experience Showcase:** Desglose interactivo de la trayectoria de Bernardo (Bursamétrica, agroindustria, idiomas, visión).
- **Structured Minimalist Footer:** Navegación por columnas nítidas, enlaces directos a canales de comunicación y créditos de autor.
