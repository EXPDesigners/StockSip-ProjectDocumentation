# Capítulo 4: Product Design #

## _4.1. Style Guidelines_ ##

### 4.1.1. General Style Guidelines ###

La propuesta visual de **StockSip** se basa en transmitir profesionalismo, accesibilidad y tecnología confiable para negocios que requieren control eficiente de su inventario, especialmente licorerías y proveedores. Las decisiones tomadas en cuanto a branding, tipografía, colores y espaciado buscan crear una experiencia clara, funcional y moderna, adecuada tanto para nuevos usuarios como para usuarios frecuentes del sistema.

**Branding**

-   "StockSip" se presenta como una marca moderna y profesional, enfocada en la gestión inteligente de licores.
    
-   El logotipo de StockSip combina elementos gráficos relacionados con licorería (como una copa estilizada o una botella minimalista) con una tipografía limpia, para reflejar sofisticación y control.
    
-   El uso de tonos cálidos oscuros (burdeos, dorado suave, marrones profundos) proyecta calidad, tradición y elegancia, en línea con el mundo de bebidas selectas.
    
-   La frase clave “stock management” debajo del logo refuerza el propósito de la herramienta y su enfoque en la eficiencia operativa.

<p align="center">
  <img src="https://i.imgur.com/AwKOYXI.png" 
  alt="logo-stocksip"/>

  > <p align="center">Logo de StockSip</p>
</p>
<br>

**Tipografía**

-   **Títulos**: “Poppins” — serif elegante, ideal para transmitir distinción y modernidad.
    
-   **Cuerpo de texto**: “Inter” — sans-serif moderna, clara y altamente legible.
    
-   **Botones y microtextos**: “Roboto Medium” — neutral y funcional, facilita la interacción en interfaces digitales.
    
-   **Elementos destacados** usan una variante "bold" o "semi-bold", asegurando énfasis sin sobrecargar visualmente.

<p align="center">
  <img src="https://i.imgur.com/M4bj10w.png" 
  alt="tipografias"/>

  > <p align="center">Tipografías elegidas</p>
</p>
<br>

**Colores**
<br>

Paleta principal:

<p align="center">
  <img src="https://i.imgur.com/pYK88um.jpeg" 
  alt="logo-stocksip"/>

  > <p align="center">Paleta de colores de StockSip</p>
</p>

-   Los tonos oscuros crean una sensación de exclusividad, mientras que los acentos cálidos (como el naranja quemado) dan vitalidad y dinamismo.

-   La armonía entre morado y tonos neutros facilita un diseño elegante sin perder claridad.

- El tono claro equilibra la composición, proporcionando aire y claridad visual, lo cual mejora la legibilidad y la elegancia general del diseño.
<br>

**Espaciado**

-   Diseño moderno y minimalista, con énfasis en claridad visual.
    
-   Márgenes y “padding” van de 12px a 48px, adaptándose al dispositivo.
    
-   El contenido se organiza en secciones bien separadas, para facilitar el escaneo visual y la navegación intuitiva.
    
-   Se prioriza la jerarquía visual con suficiente espacio entre los elementos clave.
<br>

**Tono de la comunicación**
    
- **Serio pero accesible**: transmitimos confianza y precisión sin ser excesivamente técnicos.
    
- **Formal/Casual equilibrado**: nos dirigimos a usuarios emprendedores o gerentes de negocios, con un tono que mezcla profesionalismo y cercanía.
    
- **Respetuoso**: mantenemos un lenguaje claro y respetuoso, enfocado en resolver problemas del usuario.
    
- **Sereno con un toque entusiasta**: buscamos reflejar eficiencia con mensajes motivadores que inviten a la acción sin ser invasivos.
<br>

**Botones**

-   Formato rectangular con bordes ligeramente redondeados (8px).
    
-   Los botones tienen tamaños grandes y están bien espaciados, en pantallas de escritorio, su diseño y posicionamiento optimizan la interacción con el ratón.  

 <p align="center">
  <img src="https://i.imgur.com/93LE3LW.png" 
  alt="botones"/>

  > <p align="center">Botones elegidos</p>
</p>
<br>

**Patrón de diseño web:** 

- Se decidió utilizar el patrón de diseño web de tipo Z para el sitio web de la aplicación. Esta técnica mejora la experiencia del usuario al guiar su atención hacia los elementos claves más importantes que presenta la aplicación y maximizar la efectividad del contenido.
<br>

### 4.1.2. Web Style Guidelines ###

Esta sección define las pautas visuales y de interfaz para el desarrollo de la aplicación en PrimeVue. El enfoque está centrado en garantizar una experiencia consistente, accesible y optimizada para todos los usuarios, independientemente del dispositivo que utilicen.

**Responsive Design**

La interfaz se adapta automáticamente gracias a PrimeFlex y el uso de breakpoints estándar para diseño responsive:

- `sm:` ≤ 576px (móvil)
    
- `md:` 577–768px (tablet)
    
- `lg:` 769–1024px (laptop)
    
- `xl:` > 1024px (escritorio)
<br>

**Componentes y patrones compatibles**

- **Navbar/Menu:** `<Menubar />` o `<TieredMenu />` con integración de rutas y accesos rápidos.

- **Cards:** `<Card />` con íconos de PrimeIcons para acciones.

- **Botones:** `<Button icon="pi pi-check" severity="primary" />`, con soporte para icon-only o full.

- **Toasts y diálogos:** `<Toast />` para notificaciones de éxito, error o alerta, `<Dialog />` para detalles de productos.
<br>

**Accesibilidad**

Todos los componentes siguen prácticas de accesibilidad:

- Uso de atributos `aria-*` en componentes sensibles.

- Navegación por teclado compatible (Tab, Enter, Space, etc.).

- Contraste visual siguiendo la norma WCAG 2.1 AA.

- Tipografías y layouts adaptables mediante `rem/em`.
<br>

## _4.2. Information Architecture_ ##

### 4.2.1. Organization Systems ###

### 4.2.2. Labeling Systems ###

### 4.2.3. SEO Tags and Meta Tags ###

### 4.2.4. Searching Systems ###

### 4.2.5. Navigation Systems ###

## _4.3. Landing Page UI Design_ ##

### 4.3.1. Landing Page Wireframe ###

### 4.3.2. Landing Page Mock-up ###

## _4.4. Web Applications UX/UI Design_ ##

### 4.4.1. Web Applications Wireframes ###

### 4.4.2. Web Applications Wireflow Diagrams ###

### 4.4.3. Web Applications Mock-ups ###

### 4.4.4. Web Applications Userflow Diagrams ###

## _4.5. Web Applications Prototyping_ ##

## _4.6. Strategic Domain-Driven Design_ ##

## 4.6.1. Event Storming ##

## 4.6.2. Domain Message Flow Modeling ##

## 4.6.3. Bounded Context ##

## 4.6.4. Bounded Context Canvas ##

## _4.7. Domain-Driven Software Architecture_ ##

### 4.7.1. Software Architecture Context Diagram ###

### 4.7.2. Software Architecture Container Diagrams ###

### 4.7.3. Software Architecture Components Diagrams ###

## _4.8. Software Object-Oriented Design_ ##

### 4.8.1. Class Diagram ###

### 4.8.2. Class Dictionary ###

## _4.9. Database Design_ ##

### 4.9.1. Database Diagram ###
