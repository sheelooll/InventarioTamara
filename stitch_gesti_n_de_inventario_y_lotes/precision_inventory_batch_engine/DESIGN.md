---
name: Precision Inventory & Batch Engine
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#89ceff'
  on-secondary: '#00344d'
  secondary-container: '#00a2e6'
  on-secondary-container: '#00344e'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#00885d'
  on-tertiary-container: '#000703'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#c9e6ff'
  secondary-fixed-dim: '#89ceff'
  on-secondary-fixed: '#001e2f'
  on-secondary-fixed-variant: '#004c6e'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
  code-batch:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
  space-2xl: 2rem
---

## Brand & Style

The design system establishes a high-density, utility-driven workspace modeled after modern developer and productivity tools (such as Linear and Vercel). It is built for supply chain managers, warehouse operators, and operations leads who handle critical perishable inventories under strict expiration timelines. 

The aesthetic fuses **Corporate / Modern utilitarianism** with **tactile, soft-edge engineering**. The interface prioritizes:
- **Instant readability under duress:** High-signal alerts, scannable batch numbers, and high-visibility status tags.
- **Calm, low-fatigue environments:** Subdued structural surfaces (slate neutrals) paired with surgically placed primary actions and semantic alert indicators.
- **Precision craft:** Fine 1px borders, subtle micro-contrasts between layered surfaces, and crisp geometric sans typography that remains razor-sharp in data-dense tables.

All terminology and user-facing copy follow clear, concise standard Spanish suited for enterprise operations (e.g., *Lote*, *Vencimiento*, *Existencias*, *Trazabilidad*, *Cuarentena*).

## Colors

The system uses an engineered indigo as its primary operational accent, framed against deep, slate-tinted neutrals in dark mode and cool, luminous grays in light mode.

### Paleta Base y Neutros
- **Primario (Indigo):** `#6366F1` (Dark mode default), `#4F46E5` (Light mode accent / interactivo).
- **Superficies Neutras (Dark):** 
  - Canvas base: `#090D16`
  - Nivel 1 (Sidebar / Cards): `#0F172A`
  - Nivel 2 (Modales / Menús contextuales): `#1E293B`
  - Bordes y divisores estructurales: `#334155` (con opacidad 40%–60%)
- **Superficies Neutras (Light):**
  - Canvas base: `#F8FAFC`
  - Nivel 1 (Cards / Tablas): `#FFFFFF`
  - Nivel 2 (Dropdowns / Toolbars): `#F1F5F9`
  - Bordes: `#E2E8F0`

### Colores Semánticos de Ciclo de Vida y Vencimiento
La escala semántica codifica el estado físico y regulatorio de cada lote de forma inequívoca:
- **Vencido (Caducado / Bloqueado):** 
  - Fondo: `#450A0A` (Dark) / `#FEF2F2` (Light)
  - Borde: `#991B1B`
  - Texto / Icono: `#F87171` (Dark) / `#991B1B` (Light)
- **Crítico (< 30 días restantes):** 
  - Fondo: `#7F1D1D` al 30% (Dark) / `#FFF1F2` (Light)
  - Borde: `#DC2626`
  - Texto / Icono: `#EF4444` (Dark) / `#B91C1C` (Light)
- **Por Vencer (< 90 días restantes):** 
  - Fondo: `#78350F` al 30% (Dark) / `#FFFBEB` (Light)
  - Borde: `#D97706`
  - Texto / Icono: `#FBBF24` (Dark) / `#B45309` (Light)
- **Óptimo / Aceptable (En regla):** 
  - Fondo: `#064E3B` al 30% (Dark) / `#ECFDF5` (Light)
  - Borde: `#059669`
  - Texto / Icono: `#34D399` (Dark) / `#047857` (Light)

## Typography

The design system employs **Inter** across all UI tiers to achieve clean mechanical clarity and optimal micro-legibility inside dense data grids, date picker filters, and SKU tags. 

Numeric operational identifiers—such as Lote (Batch ID), GTIN/EAN-13, SKU, and internal serial numbers—leverage tabular numbers (`tnum`) via OpenType features and map to the dedicated `code-batch` role (using JetBrains Mono) for rapid optical alignment down vertical columns.

- **Headlines:** Compact, low letter-spacing (`-0.02em` on `headline-xl` and `headline-lg`) to preserve tight dashboard real estate.
- **Body & Labels:** Tuned with slightly open tracking (`-0.005em` to `0em`) to ensure legibility when displaying inventory notes, warehouse rack coordinates, or dates.
- **Labels:** Semibold and Medium weights ensure buttons, batch status pills, and column sort headers retain clear visual hierarchy without requiring increased font sizes.

## Layout & Spacing

The layout is structured around an adaptive 12-column layout for dashboard overview screens, transforming into full-width fluid toolbars and master-detail data tables for inventory operations.

- **Escritorio / Pantallas Anchas (>= 1280px):** Barra lateral de navegación colapsable fija (240px o 64px contraída). Panel principal con márgenes de `margin-desktop` (2rem) y espacio entre columnas de `gutter-desktop` (1.5rem). Las vistas de detalle de lote pueden usar un panel deslizante lateral (*drawer*) de 480px de ancho fijo.
- **Tableta (768px - 1279px):** Navegación lateral en riel compacto (iconos con tooltip). Las tablas de datos priorizan: Código Lote, Producto, Vencimiento, Cantidad y Estado; el resto de atributos se visualizan al expandir la fila.
- **Móvil (< 768px):** Disposición de columna única con márgenes de `1rem`. Las tablas matriciales se convierten en tarjetas verticales ordenadas cronológicamente por urgencia de expiración. La barra de acciones de filtro se fija en la parte superior con deslizamiento horizontal.

## Elevation & Depth

The design system builds spatial hierarchy through **tonal layering and low-contrast borders** rather than deep, heavy shadows, maintaining the lightweight aesthetic of Linear and Vercel.

1. **Superficie Base (Canvas):** Fondo mate plano que sostiene la estructura global de la aplicación.
2. **Superficie Elevada (Cards, Tablas y Paneles):** Fondos con una gradación tonal sutilmente superior al canvas (`#0F172A` sobre `#090D16` en modo oscuro; `#FFFFFF` sobre `#F8FAFC` en modo claro), reforzados por un borde perimetral nítido de 1px (`rgba(255, 255, 255, 0.08)` en oscuro, `#E2E8F0` en claro).
3. **Superficie Flotante (Dropdowns, Tooltips, Modales, Filtros Popover):** 
   - Sombra ambiental extendida: `0 8px 30px rgba(0, 0, 0, 0.35)` en modo oscuro, y `0 10px 25px -5px rgba(15, 23, 42, 0.08)` en modo claro.
   - Borde sutil de 1px para delimitar los contornos sobre elementos de fondo.
4. **Efecto Focus & Selección:** Anillo de enfoque de doble capa: `box-shadow: 0 0 0 1px #0F172A, 0 0 0 3px #6366F1` para inputs y filas seleccionadas, garantizando total accesibilidad sin romper la retícula visual.

## Shapes

The design system adheres to a contemporary soft geometry (`roundedness: 2`):

- **Contenedores Principales (Tarjetas de métricas, tablas, modales):** Usan `rounded-xl` (12px a 16px) para dar una terminación suave y moderna a los contenedores pesados.
- **Controles de Interfaz (Botones, campos de entrada, selectores de fecha):** Usan `rounded-lg` (8px), proporcionando balance entre compacidad y amabilidad táctil.
- **Badges y Chips de Estado de Lote:** Adquieren forma de píldora completa (`rounded-full`), diferenciándolos visualmente de los botones y elementos de acción rectangulares.
- **Indicadores de Cantidad y Marcadores de Alerta:** Micro-píldoras y avatares redondeados que contrastan suavemente con las líneas rectas de las tablas de datos.

## Components

### 1. Badges de Estado de Vencimiento (Píldoras)
- **Estructura:** Forma `rounded-full`, padding `space-xs` vertical y `space-sm` horizontal.
- **Tipografía:** `label-sm` (11px semibold, tracking mayúsculas o capitalizado).
- **Iconografía:** Micro-indicador circular (6px) con brillo pulsante para estado **Crítico** y **Vencido**, e icono contextual SVG (12px) opcional.
- **Variantes Semánticas:**
  - *Vencido:* Fondo `#450A0A`, borde `#991B1B`, texto `#FCA5A5`. Etiqueta: «Vencido».
  - *Crítico:* Fondo `#7F1D1D`/40, borde `#DC2626`, texto `#F87171`. Etiqueta: «< 30 días».
  - *Por Vencer:* Fondo `#78350F`/40, borde `#D97706`, texto `#FCD34D`. Etiqueta: «< 90 días».
  - *Óptimo:* Fondo `#064E3B`/40, borde `#059669`, texto `#6EE7B7`. Etiqueta: «En regla».

### 2. Botones (Buttons)
- **Primario:** Fondo `#6366F1` (Dark) / `#4F46E5` (Light), texto blanco, `rounded-lg`, padding `space-sm` por `space-lg`. Micro-interacción: transición de 120ms con escala de brillo al hover y `translate-y-px` al click.
- **Secundario / Outline:** Fondo transparente o blanco/neutro sutil con borde fino `#334155` (Dark) o `#CBD5E1` (Light). Hover: fondo con opacidad del 5% del neutral.
- **Destructivo:** Fondo `#991B1B`/20, borde `#DC2626`/60, texto `#EF4444`. Usado para bajas forzosas de stock caducado o eliminación de lotes en cuarentena.

### 3. Tablas de Inventario y Filas de Lotes
- **Encabezados:** Tipografía `label-sm` en gris apagado (`#94A3B8`), mayúsculas discretas, con flechas de ordenación visibles en hover.
- **Filas:** Altura fija compacta de 44px o regular de 52px. Separador inferior de 1px.
- **Estados de Fila:** 
  - Hover: Fondo elevado con transición rápida.
  - Alerta: Borde izquierdo destacado de 3px de grosor según el estado del lote (ej. franja roja `#DC2626` para lotes críticos).
- **Celdas Numéricas:** Código de Lote con fuente monoespaciada (`code-batch`) y alineación a la derecha en cantidades de stock disponible y unidades reservadas.

### 4. Campos de Entrada (Input Fields) y Filtros
- **Inputs:** Fondo `#0F172A` (Dark) / `#FFFFFF` (Light), borde perimetral de 1px `#334155` (`#CBD5E1` en light), `rounded-lg`, tipografía `body-md`.
- **Rango de Fechas / Datepicker:** Selector doble para fecha de fabricación y fecha de expiración con visualización de días restantes en tiempo real dentro del placeholder.

### 5. Checkboxes y Radio Buttons
- Elementos geométricos con esquinas redondeadas (`rounded` de 4px para checkboxes, `rounded-full` para radio).
- Estado activo en `#6366F1` con checkmark blanco y borde coincidente.

### 6. Tarjetas de Métricas de Almacén (KPI Cards)
- Superficie elevada con borde de 1px.
- Distribución: Etiqueta superior (`label-md`), métrica en `headline-lg`, y delta comparativo o barra de progreso horizontal con la distribución de días a vencer (segmentos verde, ámbar y rojo).