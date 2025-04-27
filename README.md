### Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

#### Identidad de marca

**Nombre y concepto**: Flow Sense representa la capacidad de gestionar el tiempo de manera intuitiva y fluida. El nombre combina "Flow" (flujo, estado óptimo de productividad) con "Sense" (sentido, percepción), transmitiendo la idea de una herramienta que ayuda a percibir y optimizar el flujo de trabajo.

**Misión**: Transformar la gestión del tiempo para empresas y profesionales independientes mediante soluciones tecnológicas intuitivas y adaptables.

**Valores de marca**:

- Eficiencia
- Innovación
- Adaptabilidad
- Confiabilidad
- Simplicidad


#### Paleta de colores

La paleta de colores de Flow Sense se basa en tonos azules que transmiten profesionalismo, confianza y tecnología, complementados con colores secundarios para crear una experiencia visual coherente:

**Colores primarios**:

- Azul primario: `hsl(215, 80%, 50%)` - Color principal de la marca, utilizado en botones de acción y elementos destacados
- Azul secundario: `hsl(240, 60%, 60%)` - Utilizado para gradientes y elementos secundarios


**Colores neutros**:

- Fondo claro: `hsl(0, 0%, 100%)` - Modo claro
- Fondo oscuro: `hsl(222.2, 84%, 4.9%)` - Modo oscuro
- Texto principal claro: `hsl(222.2, 84%, 4.9%)` - Modo claro
- Texto principal oscuro: `hsl(210, 40%, 98%)` - Modo oscuro
- Texto secundario claro: `hsl(215.4, 16.3%, 46.9%)` - Modo claro
- Texto secundario oscuro: `hsl(215, 20.2%, 65.1%)` - Modo oscuro


**Colores de estado**:

- Éxito/Confirmación: Verde `hsl(142.1, 76.2%, 36.3%)`
- Error/Alerta: Rojo `hsl(0, 84.2%, 60.2%)`
- Información: Azul claro `hsl(210, 100%, 77%)`


#### Tipografía

**Fuente principal**: Sistema sans-serif moderno y legible

- Títulos: Sans-serif, negrita (700)
- Subtítulos: Sans-serif, semibold (600)
- Cuerpo de texto: Sans-serif, regular (400)


**Jerarquía tipográfica**:

- H1: 3rem (48px) / 6rem en pantallas grandes
- H2: 2.25rem (36px) / 3rem en pantallas grandes
- H3: 1.5rem (24px)
- Texto de cuerpo: 1rem (16px)
- Texto pequeño: 0.875rem (14px)


**Espaciado de línea**:

- Títulos: 1.1
- Cuerpo de texto: 1.5


#### Iconografía

Flow Sense utiliza iconos de la biblioteca Lucide React, seleccionados por su estilo limpio y coherente. Los iconos siguen estas directrices:

- Estilo de línea consistente con grosor de 1.5px
- Esquinas ligeramente redondeadas
- Tamaños estandarizados: 16px, 20px y 24px
- Color adaptado al tema (claro/oscuro)
- Uso semántico (cada icono representa claramente su función)


#### Elementos de diseño

**Bordes y esquinas**:

- Radio de borde estándar: 0.75rem (12px)
- Radio de borde pequeño: 0.5rem (8px)


**Sombras**:

- Sombra ligera: `0 1px 3px rgba(0,0,0,0.1)`
- Sombra media: `0 4px 6px rgba(0,0,0,0.1)`
- Sombra elevada: `0 10px 15px rgba(0,0,0,0.1)`


**Espaciado**:
Sistema de espaciado basado en múltiplos de 4px:

- Espaciado extra pequeño: 0.25rem (4px)
- Espaciado pequeño: 0.5rem (8px)
- Espaciado base: 1rem (16px)
- Espaciado medio: 1.5rem (24px)
- Espaciado grande: 2rem (32px)
- Espaciado extra grande: 3rem (48px)


### 4.1.2. Web Style Guidelines

#### Componentes UI

**Botones**:

- Primario: Fondo azul primario, texto blanco, radio de borde 0.75rem
- Secundario/Outline: Borde visible, fondo transparente, radio de borde 0.75rem
- Terciario/Ghost: Sin borde, fondo transparente, cambio de color al hover
- Estados: Normal, Hover, Focus, Disabled
- Tamaños: Small (h-8), Medium (h-10), Large (h-12)


**Tarjetas**:

- Fondo blanco (modo claro) o gris oscuro (modo oscuro)
- Radio de borde 0.75rem
- Borde sutil
- Padding interno consistente (1.5rem)
- Estructura: CardHeader, CardContent, CardFooter


**Formularios**:

- Inputs con bordes visibles y radio de borde 0.75rem
- Labels siempre visibles encima de los campos
- Mensajes de error en color rojo debajo del campo
- Estados de validación visualmente diferenciados
- Padding consistente (0.75rem)


**Navegación**:

- Navbar fijo en la parte superior
- Links con estados hover y active claramente diferenciados
- Indicadores visuales para la sección actual
- Menú móvil con animación de despliegue


**Badges**:

- Tamaño pequeño y compacto
- Radio de borde completo (pill)
- Colores que contrastan con el fondo


#### Responsive Design

**Breakpoints**:

- Mobile: 0-639px
- Tablet: 640px-1023px
- Desktop: 1024px+


**Estrategias responsive**:

- Mobile-first design
- Layouts flexibles con CSS Grid y Flexbox
- Imágenes responsivas con optimización automática
- Menú hamburguesa en dispositivos móviles
- Ajustes de tamaño de texto para diferentes dispositivos
- Componentes adaptables (ej. tabs verticales en móvil)


#### Accesibilidad

- Contraste de color WCAG AA (4.5:1 para texto normal, 3:1 para texto grande)
- Textos alternativos para todas las imágenes
- Navegación por teclado completamente soportada
- Etiquetas ARIA apropiadas
- Estructura semántica de HTML
- Soporte para lectores de pantalla
- Modo oscuro para reducir la fatiga visual


#### Animaciones y transiciones

- Duración corta: 0.2s para microinteracciones
- Duración media: 0.3-0.5s para transiciones de componentes
- Curvas de aceleración naturales (ease-in-out)
- Animaciones sutiles para feedback de interacción
- Animaciones más elaboradas para elementos destacados
- Respeto por la preferencia de usuario de movimiento reducido


#### Modo oscuro

- Implementación completa de tema claro y oscuro
- Transición suave entre modos
- Preservación de la identidad de marca en ambos modos
- Ajuste automático según preferencias del sistema
- Opción manual para cambiar entre modos


## 4.2. Information Architecture

### 4.2.1. Organization Systems

#### Estructura jerárquica

Flow Sense implementa una estructura jerárquica clara que organiza el contenido de manera lógica y facilita la navegación del usuario:

**Nivel 1: Secciones principales**

- Inicio (Landing Page)
- Características
- Beneficios
- Tecnología
- Planes
- Acceso (Login/Registro)


**Nivel 2: Subsecciones**

- Características

- Para Empresas
- Para Freelancers



- Planes

- Freelancer
- Business
- Enterprise





**Nivel 3: Páginas específicas**

- Prueba gratuita
- Contacto
- Bienvenida
- Dashboard (post-registro)


#### Categorización de contenido

El contenido de Flow Sense se organiza en categorías claramente definidas que reflejan las necesidades de los diferentes tipos de usuarios:

**Por tipo de usuario**:

- Soluciones para empresas
- Soluciones para freelancers


**Por funcionalidad**:

- Gestión de tiempo
- Supervisión en tiempo real
- Análisis de productividad
- Facturación
- Gestión de clientes


**Por etapa del customer journey**:

- Descubrimiento (landing page)
- Consideración (planes, características)
- Decisión (prueba gratuita, contacto)
- Onboarding (bienvenida)
- Uso (dashboard)


#### Esquemas de organización

**Esquema secuencial**:
La landing page sigue un flujo narrativo lógico que guía al usuario desde el conocimiento del producto hasta la acción:

1. Hero (presentación del producto)
2. Características (qué hace)
3. Beneficios (por qué es valioso)
4. Tecnología (cómo funciona)
5. Testimonios (prueba social)
6. Planes (opciones de compra)
7. CTA final (llamada a la acción)


**Esquema por audiencia**:
El contenido se adapta según el tipo de usuario, presentando características y beneficios específicos para:

- Empresas (supervisión, gestión de turnos, análisis)
- Freelancers (registro automático, gestión de clientes, facturación)


**Esquema por tarea**:
La organización facilita las principales tareas que los usuarios necesitan realizar:

- Conocer el producto
- Comparar planes
- Iniciar una prueba gratuita
- Contactar con ventas
- Acceder a la cuenta


### 4.2.2. Labeling Systems

#### Terminología consistente

Flow Sense utiliza un sistema de etiquetado coherente en toda la plataforma para garantizar claridad y consistencia:

**Términos clave**:

- "Supervisión en tiempo real" (no "monitoreo" o "seguimiento")
- "Gestión de turnos" (no "administración de horarios")
- "Análisis de productividad" (no "métricas de rendimiento")
- "Registro automático" (no "tracking automático")
- "Facturación inteligente" (no "facturación automática")


**Convenciones de nomenclatura**:

- Botones de acción: Verbos en infinitivo ("Comenzar", "Solicitar")
- Títulos de sección: Sustantivos o frases nominales ("Características", "Beneficios")
- Planes: Nombres que reflejan el segmento de usuario ("Freelancer", "Business", "Enterprise")


#### Iconografía semántica

Los iconos se utilizan de manera consistente para reforzar el significado:

**Asociaciones icono-concepto**:

- Usuarios (👥): Equipos, colaboración
- Reloj (🕒): Tiempo, horarios, registro
- Gráfico (📊): Análisis, métricas, productividad
- Rayo (⚡): Velocidad, automatización, eficiencia
- Maletín (💼): Clientes, proyectos, negocios
- Chip (🖥️): Tecnología, IoT, sensores
- Mensaje (💬): Comunicación, asistentes de voz


#### Microcopy

El microcopy (pequeños textos de interfaz) sigue estas directrices:

- **Tono**: Profesional pero cercano
- **Voz**: Activa y directa
- **Instrucciones**: Claras y concisas
- **Mensajes de error**: Específicos y orientados a soluciones
- **CTAs**: Accionables y con valor claro ("Comenzar prueba gratuita" en lugar de "Registrarse")
- **Tooltips**: Informativos sin ser redundantes


### 4.2.3. SEO Tags and Meta Tags

#### Meta tags principales

```html
<!-- Meta tags básicos -->
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Flow Sense - Gestión inteligente del tiempo</title>
<meta name="description" content="Soluciones inteligentes de productividad para empresas y freelancers con tecnología IoT e IA. Optimiza tu tiempo y mejora la eficiencia de tu equipo.">

<!-- Meta tags para keywords -->
<meta name="keywords" content="gestión del tiempo, productividad, IoT, inteligencia artificial, software empresarial, freelancers, registro de horas, facturación automática">

<!-- Meta tags de autor y copyright -->
<meta name="author" content="Flow Sense">
<meta name="copyright" content="© 2025 Flow Sense">

<!-- Meta tags de robots -->
<meta name="robots" content="index, follow">
<meta name="googlebot" content="index, follow">
```

#### Open Graph y Twitter Cards

```html
<!-- Open Graph para compartir en redes sociales -->
<meta property="og:type" content="website">
<meta property="og:url" content="https://flowsense.com/">
<meta property="og:title" content="Flow Sense - Gestión inteligente del tiempo">
<meta property="og:description" content="Soluciones inteligentes de productividad para empresas y freelancers con tecnología IoT e IA.">
<meta property="og:image" content="https://flowsense.com/og-image.jpg">
<meta property="og:image:alt" content="Dashboard de Flow Sense mostrando análisis de productividad">
<meta property="og:site_name" content="Flow Sense">
<meta property="og:locale" content="es_ES">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:site" content="@flowsense">
<meta name="twitter:title" content="Flow Sense - Gestión inteligente del tiempo">
<meta name="twitter:description" content="Soluciones inteligentes de productividad para empresas y freelancers con tecnología IoT e IA.">
<meta name="twitter:image" content="https://flowsense.com/twitter-card.jpg">
<meta name="twitter:image:alt" content="Dashboard de Flow Sense mostrando análisis de productividad">
```

#### Structured Data (JSON-LD)

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "Flow Sense",
  "applicationCategory": "BusinessApplication",
  "operatingSystem": "Web",
  "offers": {
    "@type": "Offer",
    "price": "69",
    "priceCurrency": "PEN",
    "priceValidUntil": "2025-12-31"
  },
  "description": "Soluciones inteligentes de productividad para empresas y freelancers con tecnología IoT e IA.",
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4.8",
    "ratingCount": "127"
  }
}
</script>
```

#### Canonical URL y hreflang

```html
<!-- URL canónica -->
<link rel="canonical" href="https://flowsense.com/">

<!-- Alternativas de idioma -->
<link rel="alternate" hreflang="es" href="https://flowsense.com/">
<link rel="alternate" hreflang="en" href="https://flowsense.com/en/">
<link rel="alternate" hreflang="x-default" href="https://flowsense.com/">
```

#### Favicon y Apple Touch Icon

```html
<!-- Favicons -->
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" href="/icon.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/apple-touch-icon.png">
<link rel="manifest" href="/manifest.webmanifest">
<meta name="theme-color" content="#1E90FF">
```

### 4.2.4. Searching Systems

#### Búsqueda interna

Aunque la landing page no implementa un sistema de búsqueda completo, la aplicación Flow Sense incluye las siguientes capacidades de búsqueda para usuarios registrados:

**Funcionalidades de búsqueda**:

- Búsqueda global en la barra superior
- Filtros avanzados por fecha, cliente, proyecto
- Búsqueda predictiva con autocompletado
- Resultados en tiempo real
- Historial de búsquedas recientes


**Algoritmo de búsqueda**:

- Indexación de contenido por relevancia
- Búsqueda por palabras clave y frases exactas
- Corrección ortográfica automática
- Resultados personalizados según el perfil del usuario
- Ranking basado en frecuencia de uso


**Presentación de resultados**:

- Agrupación por categorías (clientes, proyectos, tareas)
- Vista previa de información relevante
- Acciones rápidas desde los resultados
- Indicadores visuales de coincidencia


#### Navegación asistida

Para facilitar la localización de información sin búsqueda explícita:

**Sugerencias contextuales**:

- Recomendaciones basadas en el comportamiento del usuario
- Accesos directos a funciones frecuentes
- Notificaciones inteligentes sobre tareas pendientes


**Filtros y ordenación**:

- Filtros predefinidos para escenarios comunes
- Ordenación por múltiples criterios (fecha, nombre, prioridad)
- Vistas personalizables y guardables


### 4.2.5. Navigation Systems

#### Navegación global

**Barra de navegación principal**:

- Posición: Fija en la parte superior
- Elementos: Logo, enlaces principales, botones de acción, toggle de tema
- Comportamiento: Responsive, colapsa en menú hamburguesa en móvil
- Estados: Indicador visual de sección actual


**Footer**:

- Enlaces secundarios: Términos, Privacidad, Contacto
- Información legal: Copyright, año
- Logo y nombre de la empresa


#### Navegación contextual

**Tabs y pestañas**:

- Utilizadas para alternar entre vistas relacionadas (Empresas/Freelancers)
- Diseño visual claro con indicador de selección
- Transiciones suaves entre contenidos


**Breadcrumbs**:

- Implementados en secciones internas de la aplicación
- Formato: Inicio > Categoría > Subcategoría > Página actual
- Navegación rápida a niveles superiores


#### Navegación utilitaria

**Call-to-Actions (CTAs)**:

- CTA primario: "Comenzar ahora" (prueba gratuita)
- CTA secundario: "Solicitar demo" (contacto de ventas)
- Posicionamiento estratégico: Hero section, después de características, final de página


**Enlaces de acceso**:

- "Iniciar sesión" para usuarios existentes
- "Prueba gratuita" para nuevos usuarios
- Ubicados consistentemente en la esquina superior derecha


#### Navegación de página

**Scroll suave**:

- Enlaces de anclaje a secciones de la misma página
- Animación suave al navegar entre secciones
- Indicador visual de la sección actual en la navegación


**Botón "Volver arriba"**:

- Aparece al hacer scroll hacia abajo
- Posición fija en esquina inferior derecha
- Animación suave al hacer clic


## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

#### Hero Section

```plaintext
+-----------------------------------------------+
|  LOGO   NAV LINKS             LOGIN  SIGNUP  |
+-----------------------------------------------+
|                                               |
|  HEADLINE TEXT                   HERO IMAGE   |
|  Subheadline text                             |
|                                               |
|  [CTA BUTTON] [SECONDARY CTA]                 |
|                                               |
+-----------------------------------------------+
```

#### Features Section

```plaintext
+-----------------------------------------------+
|                                               |
|           FEATURES SECTION TITLE              |
|           Descriptive subtitle                |
|                                               |
+-----------------------------------------------+
|                                               |
|  [TABS: EMPRESAS | FREELANCERS]               |
|                                               |
+-----------------------------------------------+
|                                               |
|  +----------+  +----------+  +----------+     |
|  | ICON     |  | ICON     |  | ICON     |     |
|  | Title    |  | Title    |  | Title    |     |
|  | Desc     |  | Desc     |  | Desc     |     |
|  +----------+  +----------+  +----------+     |
|                                               |
|  [CTA BUTTON FOR SELECTED TAB]                |
|                                               |
+-----------------------------------------------+
```

#### Benefits Section

```plaintext
+-----------------------------------------------+
|                                               |
|           BENEFITS SECTION TITLE              |
|           Descriptive subtitle                |
|                                               |
+-----------------------------------------------+
|                                               |
|  +----------+  +----------+  +----------+     |
|  | ICON     |  | ICON     |  | ICON     |     |
|  | Title    |  | Title    |  | Title    |     |
|  | Desc     |  | Desc     |  | Desc     |     |
|  +----------+  +----------+  +----------+     |
|                                               |
|  +----------+  +----------+  +----------+     |
|  | ICON     |  | ICON     |  | ICON     |     |
|  | Title    |  | Title    |  | Title    |     |
|  | Desc     |  | Desc     |  | Desc     |     |
|  +----------+  +----------+  +----------+     |
|                                               |
+-----------------------------------------------+
```

#### Technology Section

```plaintext
+-----------------------------------------------+
|                                               |
|           TECHNOLOGY SECTION TITLE            |
|           Descriptive subtitle                |
|                                               |
+-----------------------------------------------+
|                                               |
|  +---------------+  +---------------+         |
|  | ICON          |  | ICON          |         |
|  | Title         |  | Title         |         |
|  | Description   |  | Description   |         |
|  +---------------+  +---------------+         |
|                                               |
|  +---------------+                            |
|  | ICON          |                            |
|  | Title         |                            |
|  | Description   |                            |
|  +---------------+                            |
|                                               |
+-----------------------------------------------+
```

#### Testimonials Section

```plaintext
+-----------------------------------------------+
|                                               |
|           TESTIMONIALS SECTION TITLE          |
|           Descriptive subtitle                |
|                                               |
+-----------------------------------------------+
|                                               |
|  [<]                                     [>]  |
|                                               |
|  +---------------------------------------+    |
|  | ★★★★★                                  |    |
|  | "Testimonial quote text..."           |    |
|  |                                       |    |
|  | [AVATAR] Name                         |    |
|  |          Position, Company            |    |
|  +---------------------------------------+    |
|                                               |
|  [○●○○○○] (Pagination indicators)             |
|                                               |
+-----------------------------------------------+
```

#### Pricing Section

```plaintext
+-----------------------------------------------+
|                                               |
|           PRICING SECTION TITLE               |
|           Descriptive subtitle                |
|                                               |
+-----------------------------------------------+
|                                               |
|  +----------+  +----------+  +----------+     |
|  | FREELANCER|  | BUSINESS |  | ENTERPRISE|   |
|  | Price     |  | Price    |  | Price     |   |
|  | Features  |  | Features |  | Features  |   |
|  | List      |  | List     |  | List      |   |
|  |           |  |          |  |           |   |
|  | [CTA]     |  | [CTA]    |  | [CTA]     |   |
|  +----------+  +----------+  +----------+     |
|                                               |
+-----------------------------------------------+
```

#### CTA Section

```plaintext
+-----------------------------------------------+
|                                               |
|           FINAL CTA HEADLINE                  |
|           Subheadline text                    |
|                                               |
|  [PRIMARY CTA BUTTON] [SECONDARY CTA BUTTON]  |
|                                               |
+-----------------------------------------------+
```

#### Footer

```plaintext
+-----------------------------------------------+
|                                               |
|  LOGO   Copyright text         Footer links   |
|                                               |
+-----------------------------------------------+
```

### 4.3.2. Landing Page Mock-up

#### Especificaciones de diseño

**Resoluciones**:

- Desktop: 1440px de ancho
- Tablet: 768px de ancho
- Mobile: 375px de ancho


**Formato**:

- Diseño en Figma
- Exportación en formato PNG y SVG
- Componentes reutilizables


**Interacciones**:

- Estados hover y active para elementos interactivos
- Animaciones de scroll y transición
- Comportamiento responsive


#### Elementos visuales clave

**Hero Section**:

- Gradiente de fondo sutil (azul primario a secundario)
- Imagen principal de dashboard con efecto de sombra y blur
- Botones CTA con alto contraste
- Logo de Flow Sense en la navegación


**Características**:

- Tabs con indicador de selección
- Tarjetas con iconos representativos
- Bordes redondeados y efectos hover
- Botón CTA contextual según la tab seleccionada


**Beneficios**:

- Fondo ligeramente contrastante (gris claro/oscuro)
- Iconos con círculos de fondo
- Animación al hacer hover sobre las tarjetas
- Disposición en grid responsiva


**Tecnología**:

- Iconos con círculos de fondo en color primario translúcido
- Tarjetas elevadas con sombra sutil
- Animación de entrada al hacer scroll


**Testimonios**:

- Carrusel con controles de navegación
- Estrellas de valoración
- Comillas decorativas
- Avatar circular del cliente
- Indicadores de paginación activos


**Planes de precios**:

- Tarjetas con bordes y esquinas redondeadas
- Plan destacado con borde de color primario
- Badge "Popular" en el plan recomendado
- Lista de características con iconos de check
- Botones CTA de ancho completo


**CTA final**:

- Fondo con gradiente de color primario a secundario
- Texto en color blanco de alto contraste
- Botones con bordes visibles
- Efectos hover distintivos


**Footer**:

- Separador superior sutil
- Logo más pequeño
- Enlaces agrupados por categorías
- Información de copyright


#### Versiones de tema

**Tema claro**:

- Fondo principal blanco
- Texto principal en gris oscuro
- Elementos de UI con sombras sutiles
- Acentos de color primario


**Tema oscuro**:

- Fondo principal azul muy oscuro
- Texto principal en blanco/gris claro
- Elementos de UI con bordes sutiles
- Acentos de color primario ligeramente más brillantes


#### Componentes interactivos

**Navegación**:

- Barra de navegación fija con efecto de blur al hacer scroll
- Indicador de sección actual
- Menú hamburguesa animado en móvil
- Transición suave entre secciones


**Tabs**:

- Animación de deslizamiento al cambiar
- Indicador de selección con transición
- Adaptación a vertical en móvil


**Carrusel de testimonios**:

- Transición suave entre slides
- Controles de navegación visibles
- Indicadores de paginación interactivos
- Autoplay con pausa al hover


**Botones CTA**:

- Efectos hover con cambio de color y sombra
- Animación sutil al hacer clic
- Estados disabled claramente diferenciados


**Toggle de tema**:

- Iconos de sol/luna
- Animación de rotación al cambiar
- Transición suave de colores en toda la interfaz

## 4.4. Web Applications UX/UI Design


### 4.4.1. Web Applications Wireframes
**Wireframe de inicio de sesión**
![Captura de pantalla 2025-04-24 165601](https://github.com/user-attachments/assets/5b8e08f7-a316-4c2f-8da6-e33b960a4a89)

### 4.4.2. Web Applications Wireflow Diagrams

### 4.4.3. Web Applications Mock-ups

### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Aplications Prototyping

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Software Architecture Context Diagrams
![structurizr-84132-Diagram1](https://github.com/user-attachments/assets/ef088ba9-203d-4b33-9126-08536be771b6)

### 4.6.2. Software Architecture Container Diagrams
![structurizr-84132-Diagram2](https://github.com/user-attachments/assets/b8446713-aaf0-4a49-952c-6bb1d27e4441)

### 4.6.3. Software Architecture Components Diagrams
API Rest Component Diagram:
![structurizr-84132-Diagram3](https://github.com/user-attachments/assets/b12a425c-9604-4f73-99f0-0d6ef5e45013)

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams
![Captura de pantalla 2025-04-24 191604](https://github.com/user-attachments/assets/96318d7a-6d9a-487a-96ba-4b6297d316be)

### 4.7.2. Class Dictionary
**Empresa**:
La clase Empresa representa a una compañía que puede gestionar varios empleados dentro del sistema. Tiene una relación de asociación con User.

**Freelancer**:
La clase Freelancer representa a un trabajador independiente que ofrece servicios. Tiene una relación de asociación con User.

**Calendario**:
La clase Calendario representa el calendario personal de cada usuario, donde se gestionan los eventos. Tiene una relación de agregación con Evento y de asociación con User.

**Evento**:
La clase Evento representa un evento programado en el calendario de un usuario. Tiene una relación de agregación con Calendario.

**Tarea**:
La clase Tarea representa una actividad o trabajo que debe realizar un usuario. Tiene una relación de asociación con User y de dependencia con Reporte.

**Reporte**:
La clase Reporte representa un informe de la productividad de un usuario basado en su rendimiento de tareas. Tiene una relación de asociación con User y Tarea.

## 4.8 Database Design

### 4.8.1 Database Diagram
![Captura de pantalla 2025-04-24 194450](https://github.com/user-attachments/assets/bd489bce-fc44-434d-9213-f66bf85c88d8)


