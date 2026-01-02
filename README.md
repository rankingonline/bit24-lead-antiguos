# Bit24 - Reactivación de Leads Antiguos

## Descripción del Proyecto
Esta es una landing page diseñada específicamente para una campaña de reactivación de oportunidades antiguas. El objetivo principal es reconectar con leads que mostraron interés en el pasado, presentándoles las últimas novedades de Bit24 y motivándolos a retomar el contacto.

## Objetivos
- **Reconectar**: Captar la atención de leads antiguos.
- **Informar**: Mostrar las nuevas funcionalidades y mejoras de Bit24.
- **Convertir**: Animar a los usuarios a retomar el interés y contactar nuevamente.

## Guía de Estilo

### Tipografía
- **Títulos**: [Comfortaa](https://fonts.google.com/specimen/Comfortaa)
- **Cuerpo/Párrafos**: [Roboto](https://fonts.google.com/specimen/Roboto)

### Paleta de Colores

#### Brand Colors
- **Primary Brand**: `#00BDEF` (Cyan Vivido)
- **Secondary Brand**: `#0E2038` (Navy Profundo)

#### Escala de Grises Saturados (Neutros con tinte de marca)
Usamos la técnica de saturación para evitar grises muertos, inyectando un poco del tono Navy (`#0E2038`) en los neutros.
- **Blanco Puro**: `#FFFFFF`
- **Off-White (Fondo Claro)**: `#F4F8FB`
- **Gris Claro (Bordes/Detalles)**: `#D2DEEB`
- **Gris Medio (Textos secundarios)**: `#647C96`
- **Gris Oscuro (Textos principales)**: `#1F3A56`
- **Negro Profundo (Fondo Oscuro)**: `#050C15`

#### Fondos y Superficies (Backgrounds)
- **BG Light Main**: `#FFFFFF`
- **BG Light Secondary**: `#F0F7FA` (Sutil tinte cyan)
- **BG Dark Main**: `#091526` (Versión más oscura del Secondary)
- **BG Dark Surface (Tarjetas)**: `#152B46` (Versión ligeramente más clara del Secondary para elevación)

#### Gradientes Sugeridos
- **Primary Gradient**: `linear-gradient(135deg, #00BDEF 0%, #009AC2 100%)`
- **Dark Gradient**: `linear-gradient(180deg, #0E2038 0%, #050C15 100%)`
- **Primary Dominant Mix**: `linear-gradient(135deg, #00BDEF 15%, #0E2038 100%)` (Predomina Cyan sobre Navy)
- **Secondary Dominant Mix**: `linear-gradient(135deg, #0E2038 15%, #00BDEF 100%)` (Predomina Navy sobre Cyan)

### Estética Visual
- Formas redondeadas.
- Uso de glassmorphism y transiciones suaves.
- Estilo premium y moderno.
- Uso de recursos visuales corporativos (imágenes/videos de la empresa) e ilustraciones personalizadas.

## Tecnologías
- HTML5
- CSS3 (Vanilla)
- JavaScript

## Novedades de Diseño: "Dinámico & Premium"
Hemos evolucionado el diseño hacia una estética más viva y sofisticada:

### 1. Header Flotante (Glassmorphism)
- **Estilo**: Barra blanca flotante con efecto *backdrop-blur*.
- **Funcionalidad**: Incluye accesos directos de contacto (teléfono/email) y un CTA claro, ocultando elementos secundarios en móvil.

### 2. Animaciones Avanzadas
- **Hero**: Fondo con gradiente cónico rotativo (`conic-gradient`) para dar profundidad atmosférica.
- **Features Grid**:
  - Efecto "Ola" automático: Las tarjetas se iluminan secuencialmente en un ciclo infinito.
  - Hover Inteligente: Al interactuar, la animación automática se pausa y la tarjeta seleccionada destaca con un gradiente interno cyan.
- **Comunidad**: Imágenes flotantes con efecto de brillo (*shine*) al pasar el cursor.
- **Formulario Final**: Fondo con gradiente "respirando" (animación de posición suave) en tonos Navy/petróleo.
- **Last Push CTA**: Tarjeta flotante con animación de pulso y levitación.

### 3. Estructura y Layout
- **Grid Responsivo 2x2**: La sección de características mantiene 2 columnas en escritorio para mejor equilibrio visual.
- **Highlighting**: Uso estratégico de la etiqueta `<span class="highlight-card-brand">Bit24</span>` para resaltar la marca con un estilo de "sticker" pop.

## Estructura de Archivos
- `index.html`: Estructura semántica con secciones claramente delimitadas (Hero, Benefits, Community, FAQ, Final Form, CTA).
- `styles.css`: Hoja de estilos única organizada por secciones, utilizando variables CSS para mantener la consistencia del sistema de diseño.
- `assets/`: Directorio para logotipos e imágenes.
