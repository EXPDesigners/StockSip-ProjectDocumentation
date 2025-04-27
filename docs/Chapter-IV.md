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

La organización jerárquica del Landing Page de "StockSip" ha sido diseñada con el propósito de guiar al usuario de manera lógica y efectiva desde su primer contacto con la solución hasta su conversión en cliente. Esta estructura responde a principios de arquitectura de la información que priorizan la claridad, la relevancia y la progresión natural del contenido, permitiendo que los usuarios comprendan de inmediato el valor del producto, cómo funciona, sus beneficios, y los pasos para adquirirlo.

**Inicio**

- **Propósito**: Captar la atención del visitante con un mensaje claro y directo.
    
- **Contenido**: Nombre del producto, propuesta de valor destacada y llamado a la acción (CTA).


**Información explicativa**

- **¿Cómo funciona?:** Descripción paso a paso del funcionamiento del sistema.
    
- **Beneficios:** Listado de ventajas competitivas de la solución para los usuarios.
    
- **Testimonios:** Opiniones de usuarios actuales que validan la experiencia con StockSip.


**Conversión**

- **Planes:** Detalle de los distintos planes de suscripción disponibles.

<p align="center">
  <img src="https://i.imgur.com/FmDNTCb.png">

  > <p align="center">Organización en el landing page</p>


Además la arquitectura jerárquica en la interfaz de la aplicación web de "StockSip" ha sido diseñada para facilitar el acceso y gestión eficiente de las múltiples funcionalidades del sistema. Esta estructura permite una distribución lógica del contenido, reduciendo la carga cognitiva del usuario y mejorando su capacidad para encontrar rápidamente las herramientas que necesita.


<p align="center">
  <img src="https://i.imgur.com/AGeCflJ.png">

  > <p align="center">Organización en la aplicación</p>

**Pantalla de inicio**

Una vista general tipo dashboard que presenta:

- Tarjetas resumen del stock actual, productos por vencer, y alertas activas.
    
- Notificaciones destacadas (por vencimiento o bajo stock).
    
- Gráficos breves sobre tendencias de entradas/salidas recientes.

**Navegación principal**

Sistema jerárquico accesible desde un menú lateral con iconografía clara. Incluye las siguientes pestañas:

- Dashboard
    
- Inventario
    
- Zonas de almacenamiento
    
- Alertas
    
- Facturación
    
- Guías
    
- Perfil

**Filtrado y organización avanzada**

**a. Para Dueños de Licorerías**

- **Filtros por:** Tipo de producto y nivel de stock y vencimiento.
    
- **Funcionalidades destacadas:** Visualización de productos críticos, registro de nuevas entradas y salidas y gestión de zonas de almacenamiento.

**b. Para Proveedores de Licores**

- **Filtros por:** Temporalidad de pedidos (última semana, mes).
    
- **Funcionalidades destacadas:** Emisión y consulta de guías, gestión de facturación y seguimiento de entregas.


**Segmentación por audiencia**

**a. Dueños de licorerías**

- Enfoque en gestión de stock, reducción de pérdidas por caducidad, registro de movimientos y planificación de compras.
    
- Visualización clara de productos prioritarios y herramientas para reorganizar zonas de almacenamiento.

**b. Proveedores de licores**

- Acceso a historial de pedidos y entregas.
    
- Visualización de demanda por producto y licorería.

- Herramientas de seguimiento y emisión de guías y facturas desde la plataforma.
<br>

### 4.2.2. Labeling Systems ###

El sistema de etiquetado de "StockSip" ha sido diseñado para ser claro, directo y fácil de entender, usando palabras clave con un número mínimo de términos sin perder precisión. Las etiquetas evitan tecnicismos innecesarios y buscan reducir la carga cognitiva del usuario.

**Principios:**

- **Consistencia**: Se usan las mismas etiquetas en botones, menús y mensajes relacionados (por ejemplo: “Nuevo Producto”, “Registrar Salida”, “Ver Detalles”).

- **Simplicidad**: Se evita el uso de jergas técnicas o frases largas. Ejemplos: “Stock mínimo”, “Fecha de caducidad”, “Alerta activa”.

**Etiquetado en el Landing Page:**

- **Inicio**: Es la primera sección que el usuario ve al entrar. Resume qué es StockSip y capta la atención con un mensaje claro y directo.
    
- **Cómo Funciona**: Explica paso a paso el funcionamiento de la plataforma, mostrando lo fácil que es empezar y gestionar el inventario.
    
- **Beneficios**: Resalta las ventajas clave de usar StockSip, como ahorro de tiempo, reducción de pérdidas y toma de decisiones inteligentes.
    
- **Testimonios**: Incluye opiniones reales de usuarios que ya usan la plataforma, lo que genera confianza en nuevos visitantes.
    
- **Planes**: Presenta los diferentes planes de suscripción disponibles, con precios, características y comparaciones para facilitar la elección.

**Etiquetado en la Aplicación Web:**

- **Inventario**: Sección principal donde se visualiza y gestiona el stock de productos disponibles.

- **Nuevo Producto**: Permite registrar un nuevo artículo en el sistema, ingresando sus datos básicos.

- **Alertas de Vencimientos**: Muestra los productos próximos a caducar para tomar decisiones rápidas.

- **Zonas de almacenamiento**: Permite al usuario crear una zona de almacenamiento o gestionar zonas donde guardar o exponer sus productos.

- **Reportes**: Área donde se pueden consultar y descargar informes de movimiento y estado del inventario.

- **Configuración**: Sección para ajustar preferencias del sistema, notificaciones y datos de la cuenta.

- **Perfil Usuario**: Acceso a los datos personales del usuario, con opción para editar información o cerrar sesión.
<br>

### 4.2.3. SEO Tags and Meta Tags ###

Con el objetivo de mejorar la visibilidad de "StockSip" en los motores de búsqueda y facilitar su descubrimiento tanto por licorerías como por proveedores interesados en optimizar la gestión de sus productos, se ha establecido una estrategia SEO que incluye el uso adecuado de etiquetas HTML para los principales elementos informativos del sitio y la aplicación web.

**Landing Page**

- **Title:**  
`<title>StockSip – Optimiza tu inventario de forma inteligente</title>`

Una frase concisa que refleja la propuesta de valor de la herramienta y contiene palabras clave como "optimiza", "inventario" e "inteligente", términos que los usuarios suelen emplear al buscar soluciones de este tipo.

- **Meta Description:**  
`<meta name="description" content="StockSip es una plataforma digital diseñada para ayudar a licorerías y proveedores a gestionar sus inventarios de forma eficiente. Recibe alertas de vencimiento, mejora tus decisiones de compra y evita pérdidas gracias a recomendaciones inteligentes basadas en tu historial de productos.">`  

Esta descripción amplía la explicación del producto, destacando sus beneficios clave y diferenciadores, a la vez que integra términos como “plataforma digital”, “alertas”, “decisiones de compra” y “recomendaciones inteligentes”.

- **Meta Keywords:**  
`<meta name="keywords" content="gestión de inventarios, licorerías, proveedores, plataforma de stock, control de vencimiento, optimización de productos, sugerencias de compra, StockSip">`  

Un conjunto seleccionado de palabras y frases clave que abarca tanto el público objetivo (licorerías, proveedores) como funcionalidades (control, stock, sugerencias).

- **Meta Author:**  
`<meta name="author" content="Equipo StockSip – Diseño UX/UI y Desarrollo Web">`  

Incluye una referencia al equipo responsable del diseño y desarrollo del producto, lo cual puede apoyar en términos de confianza y atribución de contenido.

---

**Web Application – Dashboard Principal**

- **Title:**  
`<title>Panel de Control – StockSip | Visualiza, gestiona y optimiza tu inventario</title>`  

Este título complementa el nombre de la aplicación con un llamado a la acción claro y directo, enfocado en los principales objetivos que el usuario puede lograr desde el dashboard.

- **Meta Description:**  
`<meta name="description" content="Explora tu panel de control personalizado en StockSip. Administra tu inventario, accede a reportes detallados, recibe sugerencias de compra y controla tus productos a punto de vencer. Toda la información que necesitas, en un solo lugar.">`  

Redactado con una estructura clara y centrada en la funcionalidad. Refuerza el valor del dashboard como núcleo operativo de la aplicación, destacando acciones prácticas que el usuario puede realizar.

- **Meta Keywords:**  
`<meta name="keywords" content="dashboard de inventario, stock inteligente, gestión operativa, productos por vencer, reportes automáticos, control de licorerías, sugerencias de compra, plataforma StockSip">`  

En esta lista se incluyen palabras clave enfocadas en la experiencia dentro del entorno de aplicación, usando términos que reflejan una intención de uso concreta (ej. “dashboard de inventario”, “reportes automáticos”).

- **Meta Author:**  
`<meta name="author" content="Equipo de Desarrollo Web – StockSip, 2025">`  

Agrega también el año del lanzamiento del producto para reforzar la actualidad del sistema y su vigencia.
<br>


### 4.2.4. Searching Systems ###

Dentro de la sección Inventario, el sistema de búsqueda está integrado de forma simple pero efectiva para que el usuario pueda localizar productos rápidamente. Se utiliza un campo de búsqueda principal centrado en la parte superior de la tabla, acompañado de botones de acción. Este campo permite buscar por nombre de producto o tipo (por ejemplo: “Whiskey”, “Vino”).


<p align="center">
  <img src="https://i.imgur.com/Ut4hET5.png">

  > <p align="center">Búsqueda en el inventario</p>


**Filtros de Búsqueda**

Al realizar una búsqueda, los usuarios pueden refinar los resultados mediante una variedad de criterios clave que les permiten adaptar la visualización a sus necesidades específicas:


- **Categoría:** Posibilidad de filtrar por tipo de licor o bebida, tales como destilados, vinos, cervezas, espumantes, etc.
- **Disponibilidad por zona:** Permite verificar si un producto está disponible en alguna zona creada por el usuario.

**Resultados de Búsqueda**

Los resultados se presentan en un formato visual tipo tabla, diseñado para proporcionar información clave de forma rápida. Cada fila en la tabla incluye:

- Nombre del producto
- Tipo
- Precio
- Fecha de caducidad
- Stock actual
- Stock mínimo

Se implementa una codificación por colores para facilitar la interpretación visual de las tendencias:

- **Verde:** Indica un stock aceptable
- **Rojo:** Indica un riesgo en el stock

**Búsqueda Avanzada (Proveedores)**

StockSip incluye una función de búsqueda avanzada especialmente diseñada para proveedores de licores:

- **Guías de conservación por tipo de producto:** Acceso exclusivo a documentos y recomendaciones técnicas que detallan las mejores prácticas para la conservación de diferentes tipos de licores (temperatura, humedad, tiempo de almacenamiento recomendado, etc.).
- **Planes de reabastecimiento:** Herramienta que permite proyectar necesidades de reposición de stock basándose en históricos de venta, frecuencia y patrones de consumo.
<br>

### 4.2.5. Navigation Systems ###

La navegación en **StockSip** está diseñada para facilitar el recorrido del usuario de manera clara y rápida. En el landing page se implementa una barra de navegación fija con las secciones clave para el visitante. Estas son:

- Inicio
- ¿Cómo funciona?
- Beneficios
- Contacto
- Empezar


<p align="center">
  <img src="https://i.imgur.com/Xs1UCzf.png">

  > <p align="center">Barra de navegación fija</p>

<br>

En la aplicación web, se implementa una barra lateral fija con íconos, la cual permite el acceso directo a las funcionalidades clave como:  

- Dashboard
- Inventario
- Alertas
- Reportes
- Compras
- Zonas
- Facturación
- Configuración

Cada sección está representada con un ícono claro y una etiqueta visible al pasar el cursor o expandir el menú, asegurando una navegación fluida.

<p align="center">
  <img src="https://i.imgur.com/NRXVoUd.png">

  > <p align="center">Barra de navegación desplegable</p>

<br>

## _4.3. Landing Page UI Design_ ##

### 4.3.1. Landing Page Wireframe ###

Para el desarrollo del Landing Page de StockSip, se realizaron diversos bosquejos de baja fidelidad en la aplicación de diseño de interfaz Figma para crear la estructura de las pantallas del Landing Page de la solución.

<p align="center">
  <img src="https://i.imgur.com/iwIbHR9.png"/>
</p>

### 4.3.2. Landing Page Mock-up ###
Para el desarrollo del Landing Page de StockSip, se realizaron bosquejos de alta fidelidad en la aplicación Figma. Para el desarrollo de estas pantallas, se tomó como base los Wireframes previamente diseñados, sin embargo, estas pantallas poseen colores adecuados y la tipografía definida para las distintas secciones del Landing Page.
 
 <p align="center">
   <img src="https://i.imgur.com/BgjTngT.png"/>
 </p>

## _4.4. Web Applications UX/UI Design_ ##

### 4.4.1. Web Applications Wireframes ###
En esta sección se presentarán los wireframes de la aplicación, los cuales son bosquejos de baja fidelidad sobre las funcionalidades principales de nuestra solución. Finalmente, se dividieron estos wireframes en doce secciones.

### Seccion inicio de seccion/registro ####
En esta sección, el usuario podra crear su cuenta e iniciar seccion con la cuenta anteriormente creada. Podra elegir entre el rol de dueño de licoreria y proveedor. Tambien podra recuperar su contraseña mediante un codigo de confirmacion, el codigo le llegara a su correo que registro al crear su cuenta.

<p align="center">
  <img src="https://i.imgur.com/Avjk8pL.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/nDzzNXF.png"/>
</p>

### Perfil ###
En esta sección, se presentan los perfiles de los dos tipos de usuarios. En el los usuarios podran cambiar sus datos personales, caracteristicas y podra cambiar el tipo de plan entre Plan Free y Plan Premium

<p align="center">
  <img src="https://i.imgur.com/MQm7fZw.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/QiuEB6B.png"/>
</p>

### DashBoard ###
En esta sección, los dos tipos de usuarios podran ver su dashboard, este contiene un resumen general, alertas recientes y accesos rapidos para las herramientas de la aplicacion.
<p align="center">
  <img src="https://i.imgur.com/aMI2gZi.png"/>
</p>

### Facturacion ###
En esta sección, el usuario podra ver las facturas que realizo, asi mismo, tambien puede crear comprobante cuando este por realizar una venta.
<p align="center">
  <img src="https://i.imgur.com/rV3e8Tw.png"/>
</p>

### Alertas ###
En esta sección, el usuario podra ver las alertas a mayor detalle. Vera cuanto de stock de cada producto cuenta en su almacen. Tambien podra ver los productos proximos a vencer. 
<p align="center">
  <img src="https://i.imgur.com/sKzNbHf.png"/>
</p>

### Guias de Conservacion ###
En esta sección, el usuario podrá crear guías de conservación de vinos, diseñadas para orientar y apoyar a los nuevos ingresantes en el rubro de la licorería, proporcionando buenas prácticas y consejos esenciales para el manejo adecuado de estos productos.
<p align="center">
  <img src="https://i.imgur.com/uqhqF5h.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/UH90st6.png"/>
</p>

### Descuentos ###
En esta sección, el usuario podrá crear descuentos para sus productos y gestionar las promociones activas, permitiéndole visualizar, editar o desactivar los descuentos vigentes de manera sencilla y organizada.
<p align="center">
  <img src="https://i.imgur.com/N79pqpg.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/sOJHXkw.png"/>
</p>

### Planes de reabastecimiento ###
En esta sección, el usuario podrá crear planes de reabastecimiento para su almacén, definiendo la frecuencia con la que renovará su inventario. Además, podrá visualizar y gestionar los planes ya creados, asegurando una mejor organización y un flujo constante de productos.
<p align="center">
  <img src="https://i.imgur.com/OI536xW.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/DR9V9Ds.png"/>
</p>

### Reportes ###
En esta sección, el usuario podrá generar reportes relacionados con pérdidas, remisiones internas, así como cuidados y conservación de sus productos, permitiéndole llevar un control detallado y mejorar la gestión de su inventario
<p align="center">
  <img src="https://i.imgur.com/RnGhBax.png"/>
</p>

### Zonas de Almacenamiento ###
En esta sección, el usuario podrá crear y editar las zonas de almacenamiento para sus productos, permitiéndole organizar mejor su inventario y llevar un control más preciso de su negocio.
<p align="center">
  <img src="https://i.imgur.com/Rs86kW9.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/ijUNCF2.png"/>
</p>

### Ordenes de Compra ###
En esta sección, el usuario podrá realizar órdenes de compra a los proveedores, enviando automáticamente los detalles —como los productos solicitados y las cantidades requeridas— al correo electrónico del proveedor, facilitando así una comunicación rápida y precisa.
<p align="center">
  <img src="https://i.imgur.com/0GrbA72.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/eFKoMM6.png"/>
</p>

### Catalogo ###
En esta sección, el usuario podrá visualizar el catálogo del proveedor y realizar órdenes de compra de manera sencilla. A su vez, el proveedor tendrá la posibilidad de crear y gestionar sus propios catálogos, agregando la información necesaria de cada producto para facilitar la venta y mantener actualizada su oferta.
<p align="center">
  <img src="https://i.imgur.com/F6D4GOr.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/7Kc3XAS.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/jFjoH7u.png"/>
</p>

### Inventario ###
En esta sección, el usuario podrá gestionar su inventario utilizando diversas herramientas: agregar, editar y eliminar productos, registrar la salida de productos indicando el tipo de salida, y visualizar un resumen general del estado de todo su inventario, facilitando así un control más eficiente y organizado.
<p align="center">
  <img src="https://i.imgur.com/dlDrYu0.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/IRfisL1.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/IpSYiFz.png"/>
</p>

### 4.4.2. Web Applications Wireflow Diagrams ###

Un wireflow o flujo de pantalla es un diagrama donde se reúnen distintos wireframes realizados cuya finalidad es contar las metas del usuario con la aplicación y cómo las consiguen. Luego, los pasos para la creación de cada diagrama empiezan por la definición de un objetivo del usuario que desea cumplir. Luego, se define el flujo de tareas que se deben ser realizadas por el usuario en la aplicación para conseguir dicho objetivo. Y, finalmente, se traducen dichas tareas por pantallas y, también, se trazan decisiones en botones del wireframe.

- **User Goal 1:** Usuario desea registrarse en la aplicación

Primero, se definen las tareas típicas que realizaría un usuario para completar este objetivo:

<p align="center">
  <img src="../img/Chapter IV/wireflows/taskflow_1.png"
    alt="taskflow_1"/>
</p>

Luego, se muestra el resultado de la traducción de acción a pantallas. A continuación, en este flujo se muestra el proceso para registrar una cuenta en la aplicación que empieza en el momento en el que el usuario accede a la aplicación web y continúa con el mismo usuario colocando inforamción requerida para crear una cuenta.

<p align="center">
  <img src="../img/Chapter IV/wireflows/wireflow_1.png"
    alt="wireflow_1"/>
</p>

- **User Goal 2:** Usuario desea iniciar sesión con su cuenta en la aplicación

Primero, se definen las tareas típicas que realizaría un usuario para completar este objetivo:

<p align="center">
  <img src="../img/Chapter IV/wireflows/taskflow_2.png"
    alt="taskflow_2"/>
</p>

Luego, se muestra el resultado de la traducción de acción a pantallas. A continuación, en este flujo se muestra el para iniciar sesión en la aplicación. Para ello, el usuario debe haber creado una cuenta previamente. Luego, debe colocar las credenciales de su cuenta en los recuadros e iniciar sesión.

<p align="center">
  <img src="../img/Chapter IV/wireflows/wireflow_2.png"
    alt="wireflow_2"/>
</p>

- **User Goal 3:** Usuario desea cambiar su contraseña

Primero, se definen las tareas típicas que realizaría un usuario para completar este objetivo:

<p align="center">
  <img src="../img/Chapter IV/wireflows/taskflow_3.png"
    alt="taskflow_3"/>
</p>

Luego, se muestra el resultado de la traducción de acción a pantallas. A continuación, en este flujo se muestra el proceso para recuperar la contraseña de una cuenta. Para ello, el usuario accede a la sección para realizar dicha acción y coloca el correo electrónico asociado a su cuenta. Luego, recibirá un código de verificación y con ese código podrá continuar al siguiente paso y crear una nueva contraseña.

<p align="center">
  <img src="../img/Chapter IV/wireflows/wireflow_3.png"
    alt="wireflow_3"/>
</p>

- **User Goal 4:** Dueño de licorería desea visualizar su inventario

Primero, se definen las tareas típicas que realizaría un usuario para completar este objetivo:

<p align="center">
  <img src="../img/Chapter IV/wireflows/taskflow_4.png"
    alt="taskflow_4"/>
</p>

Luego, se muestra el resultado de la traducción de acción a pantallas. A continuación, en este flujo se muestra el proceso para visualizar el inventario. Primero, el usuario debe iniciar sesión. A continuación, accederá al Dashboard que es la vista principal al iniciar sesión. Finalmente, debe dar clic en el botón de Inventario y podrá visualizarlo.

<p align="center">
  <img src="../img/Chapter IV/wireflows/wireflow_4.png"
    alt="wireflow_4"/>
</p>

- **User Goal 5:** Dueño de licorería desea agregar un producto a su inventario

Primero, se definen las tareas típicas que realizaría un usuario para completar este objetivo:

<p align="center">
  <img src="../img/Chapter IV/wireflows/taskflow_5.png"
    alt="taskflow_5"/>
</p>

Luego, se muestra el resultado de la traducción de acción a pantallas. A continuación, en este flujo se muestra el proceso para registrar un producto en un inventario digital. Para ello, el usuario deberá registrar toda la información relacionada al producto deseado. Finalmente, se debe guardar la información y el producto se mostrará en el inventario.

<p align="center">
  <img src="../img/Chapter IV/wireflows/wireflow_5.png"
    alt="wireflow_5"/>
</p>

- **User Goal 6:** Dueño de licorería desea registrar la salida de un producto

Primero, se definen las tareas típicas que realizaría un usuario para completar este objetivo:

<p align="center">
  <img src="../img/Chapter IV/wireflows/taskflow_6.png"
    alt="taskflow_6"/>
</p>

Luego, se muestra el resultado de la traducción de acción a pantallas. A continuación, en este flujo se muestra el proceso que sigue típicamente un dueño de licorería para registrar el motivo de salida de un producto de su negocio. Para ello, el usuario debe acceder al inventario y seleccionar el botón para registrar salida. Luego, deberá seleccionar el producto y el motivo de salida. Finalmente, guardar, y se completará el proceso.

<p align="center">
  <img src="../img/Chapter IV/wireflows/wireflow_6.png"
    alt="wireflow_6"/>
</p>

- **User Goal 7:** Dueño de licorería desea conocer el estado de la salud de su inventario

Primero, se definen las tareas típicas que realizaría un usuario para completar este objetivo:

<p align="center">
  <img src="../img/Chapter IV/wireflows/taskflow_7.png"
    alt="taskflow_7"/>
</p>

Luego, se muestra el resultado de la traducción de acción a pantallas. A continuación, en este flujo se muestra que para acceder a la sección de Salud del Inventario, se debe realizar una acción de scroll en la pantalla de inventario.

<p align="center">
  <img src="../img/Chapter IV/wireflows/wireflow_7.png"
    alt="wireflow_7"/>
</p>

- **User Goal 8:** Dueño de licorería desea visualizar la sección Reportes

Primero, se definen las tareas típicas que realizaría un usuario para completar este objetivo:

<p align="center">
  <img src="../img/Chapter IV/wireflows/taskflow_8.png"
    alt="taskflow_8"/>
</p>

Luego, se muestra el resultado de la traducción de acción a pantallas. A continuación, este flujo muestra que acceder a la sección de Reportes se puede conseguir desde la barra lateral izquierda al presionar el ícono que representa a dicha sección.

<p align="center">
  <img src="../img/Chapter IV/wireflows/wireflow_8.png"
    alt="wireflow_8"/>
</p>

- **User Goal 9:** Dueño de licorería desea generar un nuevo reporte

Primero, se definen las tareas típicas que realizaría un usuario para completar este objetivo:

<p align="center">
  <img src="../img/Chapter IV/wireflows/taskflow_9.png"
    alt="taskflow_9"/>
</p>

Luego, se muestra el resultado de la traducción de acción a pantallas. A continuación, este flujo muestra el proceso para registrar un nuevo reporte. Para ello, el dueño de licorería debe rellenar la información que se le solicita y guardar. De esta forma, se mostrará al recargar la sección.

<p align="center">
  <img src="../img/Chapter IV/wireflows/wireflow_9.png"
    alt="wireflow_9"/>
</p>

- **User Goal 10:** Dueño de licorería desea saber si un producto se encuentra en una zona de almacenamiento determinada

Primero, se definen las tareas típicas que realizaría un usuario para completar este objetivo:

<p align="center">
  <img src="../img/Chapter IV/wireflows/taskflow_10.png"
    alt="taskflow_10"/>
</p>

Luego, se muestra el resultado de la traducción de acción a pantallas. A continuación, este flujo inicia en la sección de zonas, donde el dueño de licorería usa la barra de navegación para escribir el nombre del producto que desea buscar. Finalmente, la aplicación mostrará las zonas en las que se encuentra almacenado dicho producto.

<p align="center">
  <img src="../img/Chapter IV/wireflows/wireflow_10.png"
    alt="wireflow_10"/>
</p>

- **User Goal 11:** Dueño de licorería desea generar una nueva orden de compra

Primero, se definen las tareas típicas que realizaría un usuario para completar este objetivo:

<p align="center">
  <img src="../img/Chapter IV/wireflows/taskflow_11.png"
    alt="taskflow_11"/>
</p>

Luego, se muestra el resultado de la traducción de acción a pantallas. A continuación, en este flujo se muestra un caso típico que puede ocurrir al intentar registrar una nueva orden de compra ya que los usuarios pueden olvidar completar algunos espacios solicitados. Es por ello, que al intentar registrar una orden con espacios incompletos, la aplicación muestra un mensaje de error.

<p align="center">
  <img src="../img/Chapter IV/wireflows/wireflow_11.png"
    alt="wireflow_11"/>
</p>

- **User Goal 12:** Proveedor desea generar una nueva guía de conservación

Primero, se definen las tareas típicas que realizaría un usuario para completar este objetivo:

<p align="center">
  <img src="../img/Chapter IV/wireflows/taskflow_12.png"
    alt="taskflow_12"/>
</p>

Luego, se muestra el resultado de la traducción de acción a pantallas. A continuación, se muestra que el proveedor accede a la sección de Guías de conservación desde la sección Reportes. Luego, usa el botón para crear una nueva guía y completa los espacios requeridos. Finalmente, guarda y se muestra la guía creada.

<p align="center">
  <img src="../img/Chapter IV/wireflows/wireflow_12.png"
    alt="wireflow_12"/>
</p>

- **User Goal 13:** Usuario desea generar una nueva factura

Primero, se definen las tareas típicas que realizaría un usuario para completar este objetivo:

<p align="center">
  <img src="../img/Chapter IV/wireflows/taskflow_14.png"
    alt="taskflow_14"/>
</p>

Luego, se muestra el resultado de la traducción de acción a pantallas. A continuación, se muestra que el usuario accede a la sección de facturación y usa el botón para registrar una nueva factura. Luego, completa los espacios requeridos para el registro exitoso. Finalmente, guarda la información y la factura se mostrará en la sección de facturación.

<p align="center">
  <img src="../img/Chapter IV/wireflows/wireflow_14.png"
    alt="wireflow_14"/>
</p>

### 4.4.3. Web Applications Mock-ups ###

En esta sección se presentarán los mockups de la aplicación móvil, los cuales son bosquejos de media o alta fidelidad sobre las funcionalidades principales de nuestra solución. Para el diseño de los mockups, se partió de los wireframes realizados previamente.

**Sección Inicio de Sesión/Registro:**

<p align="center">
  <img src="https://i.imgur.com/fMshcIe.png">
</p>

<p align="center">
  <img src="https://i.imgur.com/NBgoFGy.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/Vpu9Xhy.png">
</p>
<br>

**Sección Inventario**

<p align="center">
  <img src="https://i.imgur.com/1F7fKRQ.png">
</p>

<p align="center">
  <img src="https://i.imgur.com/vkj7MJ6.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/j1z4xzr.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/3rDFtk5.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/9tbuVPZ.png">
</p>

**Sección Alertas**

<p align="center">
  <img src="https://i.imgur.com/KtmxSDE.png">
</p>
**Sección Reportes**

<p align="center">
  <img src="https://i.imgur.com/KNvt2l3.png">
</p>

**Sección Zonas de Almacenamiento**

<p align="center">
  <img src="https://i.imgur.com/oc7Fiw6.png">
</p>

<p align="center">
  <img src="https://i.imgur.com/oW3qoga.png">
</p>

**Sección Guías de Conservación**

<p align="center">
  <img src="https://i.imgur.com/qToTuj2.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/5zV66UP.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/6rNXauW.png">
</p>

**Sección Órdenes de Compra**

<p align="center">
  <img src="https://i.imgur.com/cqXAFru.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/cuQUvDD.png">
</p>


**Sección Facturación**

<p align="center">
  <img src="https://i.imgur.com/2uKMUCK.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/nkCN76Z.png">
</p>


**Sección Catálogo**

<p align="center">
  <img src="https://i.imgur.com/pm6lUDP.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/ZhjZnCe.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/wtS0pKc.png">
</p>

**Seccion Descuentos**

<p align="center">
  <img src="https://i.imgur.com/FfVhfyT.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/HMW0RZq.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/8orFcJ6.png">
</p>

**Sección Planes de Reabastecimiento**

<p align="center">
  <img src="https://i.imgur.com/mLVhFIY.png">
</p>

<p align="center">
  <img src="https://i.imgur.com/clsjNpr.png">
</p>

<p align="center">
  <img src="https://i.imgur.com/rqm3XcZ.png">
</p>

**Sección Dashboard**

<p align="center">
  <img src="https://i.imgur.com/jwFzslM.png">
</p>

**Sección Perfil**

<p align="center">
  <img src="https://i.imgur.com/1w4POXL.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/Y2DiMKN.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/0eNkAz9.png">
</p>


### 4.4.4. Web Applications Userflow Diagrams ###

Un user flow o trayectoria del usuario es un diagrama que consiste en mostrar el trayecto del usuario representado por un diagrama de flujo e indica el camino que debe seguir el usuario para cumplir con un objetivo en específico en la aplicación. Además, el user flow debe determinar estos pasos para completar una experiencia digital satisfactoria para el usuario.

- **User Goal 1:** Usuario desea registrarse en la aplicación

**Happy Path**

En esta ruta esperada, el flujo concentra un proceso de registro de cuenta en la aplicación. Asimismo, el usuario es recibido por la pantalla principal y debe registrarse en la aplicación usando información que solicite el registro. Finalmente, al crease la cuenta, el usuario puede continuar con el uso de la aplicación. Cabe recalcar, que este flujo no toma en cuenta la elección de plan ya que los usuarios que se registran, automáticamente poseen un plan de uso gratuito que limita sus funciones.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow1_happy_path.png"
    alt="userflow_1_happypath"/>

**Unhappy Paths**

Estas rutas alternas toman en cuenta que el usuario ha colocado alguna información errónea que no pasó la verificación o que no completó uno o varios espacios requeridos para proceder con el registro.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow1_unhappy_path.png"
    alt="userflow_1_unhappypath"/>

- **User Goal 2:** Usuario desea iniciar sesión con su cuenta en la aplicación

**Happy Path**

En esta ruta esperada, el flujo representa el proceso de inicio de sesión del usuario para acceder a la aplicación. Cabe recalcar, que desde este flujo sí toma en cuenta la elección de plan. Asimismo, de ahora en adelante, se trabaja con usuarios que poseen el plan premium.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow2_happy_path.png"
    alt="userflow_2_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el usuario ha colocado alguna información de su cuenta erróneamente, lo que prohibe, en ese instante, poder acceder a su cuenta.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow2_unhappy_path.png"
    alt="userflow_2_unhappypath"/>

- **User Goal 3:** Usuario desea cambiar su contraseña

**Happy Path**

En esta ruta esperada, el usuario inicia en un estado en el que no recuerda su contraseña para acceder a la aplicación. Para ello, deberá seguir el proceso para recuperación de contraseñas mediante el uso de su correo electrónico. Luego, recibirá un código de verificación que deberá introducir en la aplicación para poder crear una nueva contraseña.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow3_happy_path.png"
    alt="userflow_3_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el usuario ha indicado un correo no registrado en la aplicación (si introduces un correo registrado, enviará un código de verificación a dicho correo aunque no sea tuyo). Por lo tanto, no recibirá ningún código de verificación y no podrá restaurar su contraseña.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow3_unhappy_path.png"
    alt="userflow_3_unhappypath"/>

- **User Goal 4:** Dueño de licorería desea visualizar su inventario

**Happy Path**

En esta ruta esperada, el dueño de licorería inicia sesión en su cuenta para, de esta manera, pueda acceder a la pantalla principal (dashboard). Finalmente, el usuario, mediante un clic, accede al inventario digital y puede visualizar sus productos.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow4_happy_path.png"
    alt="userflow_4_happypath"/>

- **User Goal 5:** Dueño de licorería desea agregar un producto a su inventario

**Happy Path**

En esta ruta esperada, el dueño de licorería accede al inventario digital y utiliza la función de agregación de productos. En la siguiente pantalla, rellena cada espacio requerido correctamente y guarda la información. A continuación, la aplicación asociará dicho producto a su almacén y se mostrará.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow5_happy_path.png"
    alt="userflow_5_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el dueño de licorería intenta registrar un producto con información errónea o nula, lo cual no es posible y recibe un mensaje de error.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow5_unhappy_path.png"
    alt="userflow_5_unhappypath"/>

- **User Goal 6:** Dueño de licorería desea registrar la salida de un producto

**Happy Path**

En esta ruta esperada, el dueño de licorería desea registrar la razón por la cual uno o varios productos salieron de su negocio. Para ello, posee dos secciones que debe completar: el producto y la razón. No hay manera de provocar errores en esta pantalla.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow6_happy_path.png"
    alt="userflow_6_happypath"/>

- **User Goal 7:** Dueño de licorería desea conocer el estado de la salud de su inventario

**Happy Path**

En esta ruta esperada, el dueño de licorería desea visualizar el dashboard alternativo que muestra la salud de su inventario. Es por ello que realiza un scroll en la pantalla de su inventario y accede al lugar que desea visualizar.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow7_happy_path.png"
    alt="userflow_7_happypath"/>

- **User Goal 8:** Dueño de licorería desea visualizar la sección Reportes

**Happy Path**

En esta ruta esperada, el dueño de licorería accede a la sección Reportes desde la pantalla principal (puede acceder a la sección Reportes desde cualquier otra sección). Para ello, utiliza el ícono que representa a dicha sección y la aplicación lo redirigirá.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow8_happy_path.png"
    alt="userflow_8_happypath"/>

- **User Goal 9:** Dueño de licorería desea generar un nuevo reporte

**Happy Path**

En esta ruta, el dueño de licorería accede a la sección Reportes y selecciona el botón para registrar un nuevo reporte. Luego, rellena la inforamción que le solicita la aplicación correctamente. Finalmente, se procesa el registro y se muestra en la sección.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow9_happy_path.png"
    alt="userflow_9_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el dueño de licorería intenta registrar un reporte con información errónea o incompleta, lo que no es posible. Por lo tanto, se le muestra un aviso de que su acción no ha sido procesada.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow9_unhappy_path.png"
    alt="userflow_9_unhappypath"/>

- **User Goal 10:** Dueño de licorería desea saber si un producto se encuentra en una zona de almacenamiento determinada

**Happy Path**

En esta ruta esperada, el dueño de licorería accede a la sección Zonas. Luego, utiliza la barra de navegación al colocar el nombre del producto que desea buscar. Finalmente, la aplicación encuentra el producto y las zonas en las que se encuentra y las muestra al usuario.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow10_happy_path.png"
    alt="userflow_10_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el dueño de licorería intenta buscar el nombre de un producto no registrado en su almacén o que no ha sido colocado en alguna zona. Por lo tanto, la aplicación mostrará una sección vacía.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow10_unhappy_path.png"
    alt="userflow_10_unhappypath"/>

- **User Goal 11:** Dueño de licorería desea generar una nueva orden de compra

**Happy Path**

En esta ruta esperada, el dueño de licorería accede a la sección para realizar pedidos a los proveedores. Luego, selecciona el botón para generar una nueva orden. A continuación, el dueño de licorería completa la información requerida como productos a pedir y cantidad por cada uno. Finalmente, coloca el correo del proveedor al que desea hacer un pedido y envía.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow11_happy_path.png"
    alt="userflow_11_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el dueño de licorería intenta registrar una orden de compra con información incompleta, lo cual, no es posible. Por lo tanto, recibe un mensaje de error,

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow11_unhappy_path.png"
    alt="userflow_11_unhappypath"/>

- **User Goal 12:** Proveedor desea generar una nueva guía de conservación

**Happy Path**

En esta ruta esperada, el proveedor accede a la sección Reportes y hace clic en el botón de Conservación. A continuación, es dirigido a la sección donde puede visualizar sus guías creadas y botones para modificar y crear nuevas guías. Luego, el proveedor se dispone a generar una nueva guía. Para ello, completa la información requerida correctamente y guarda. Finalmente, se muestra toda la información que ha registrado el proveedor.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow12_happy_path.png"
    alt="userflow_12_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el proveedor, por error o equivocación, intenta crear una guía de conservación con información faltante o errónea. Por lo tanto, no se crea su guía de conservación.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow12_unhappy_path.png"
    alt="userflow_12_unhappypath"/>

- **User Goal 13:** Usuario desea generar una nueva factura

**Happy Path**

En esta ruta esperada, el usuario accede a la sección Facturación donde puede visualizar sus facturas y botones para generar una nueva factura manualmente. A continuación, presiona el botón para registrar una nueva factura. Luego, completa los espacios requeridos correctamente y guarda la información.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow13_happy_path.png"
    alt="userflow_13_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el usuario intenta registrar una factura con información errónea o faltante. Por lo tanto, no será posible registrar la factura.

<p align="center">
  <img src="../img/Chapter IV/userflow_diagrams/userflow13_unhappy_path.png"
    alt="userflow_13_unhappypath"/>

## _4.5. Web Applications Prototyping_ ##

En esta sección, se evidencian pruebas de uso de los prototipos de las aplicaciones para el entorno Web Browser. Además, se adjunta un video donde se usan los prototipos y las interacciones con el prototipo se basan en los User Flows descritos previamente.

<p align="center">
  <img src="../img/Chapter IV/prototipo.png">

  > <p align="center">Prototipo de StockSip</p>


[StockSip_Prototipo_Web_Browser.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202315234_upc_edu_pe/EevYUjJIIfBJqhDYgPgbwOcBHpyjsJ1DSKIn8G_uzrF4Dw?e=jVpUAx&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

## _4.6. Strategic Domain-Driven Design_ ##

Para identificar nuestros Bounded Context, es necesario realizar un análisis estratégico del dominio. Este análisis se puede llevar a cabo utilizando las siguientes herramientas:

## 4.6.1. Event Storming ##

Para identificar los eventos de dominio, es recomendable realizar una sesión de Event Storming. Esta técnica permite visualizar y comprender el flujo de eventos dentro del dominio, facilitando la identificación de los Bounded Context.

1. Bounded Context **Inventory**

![inventoryBC-event-storming](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Event-Storming/inventoryBC-event-storming.png)

2. Bounded Context **Order**

![orderBc-event-storming](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Event-Storming/orderBC-event-storming.png)

3. Bounded Context **Authentication**

![authenticationBc-event-storming](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Event-Storming/authenticationBC-event-storming.png)

4. Bounded Context **Payment**

![paymentBc-event-storming](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Event-Storming/paymentBC-event-storming.png)

5. Bounded Context **Reporting**

![reportingBc-event-storming](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Event-Storming/reporting-event-storming.png)

6. Bounded Context **Notification**

![notificationBc-event-storming](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Event-Storming/notificationBC-event-storming.png)
 

## 4.6.2. Domain Message Flow Modeling ##

El modelado del flujo de mensajes de dominio es una técnica que permite visualizar cómo los diferentes Bounded Contexts interactúan entre sí a través de eventos y comandos. Esta técnica ayuda a identificar las dependencias y las relaciones entre los distintos contextos, facilitando la comprensión del sistema en su conjunto.

1. **Escenario**: Registrar un nuevo producto en el catálogo

![scenario-register-product](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Domain-Message-Flow-Modelling/scenario1.png)

2. **Escenario**: Notificar el estado de un pedido

![scenario-notify-order-status](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Domain-Message-Flow-Modelling/scenario2.png)

3. **Escenario**: Registrar una nueva cuenta

![scenario-register-account](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Domain-Message-Flow-Modelling/scenario3.png)

## 4.6.3. Bounded Context ##

Los Bounded Contexts son divisiones estratégicas dentro del dominio que permiten gestionar diferentes aspectos del sistema de manera independiente. Cada Bounded Context tiene su propio modelo de dominio, lo que facilita la evolución y el mantenimiento del sistema en su conjunto.

1. Bounded Context **Inventory**: Gestiona el control de inventario en almacenes, incluyendo ajustes de stock, registro de productos y seguimiento de movimientos, para garantizar disponibilidad y precisión en tiempo real.


2. Bounded Context **Order**: Gestiona el ciclo completo de órdenes (compra/venta), la configuración de catálogos (productos y promociones) y la planificación de reabastecimiento, asegurando disponibilidad de inventario y una experiencia fluida para clientes y proveedores.


3. Bounded Context **Authentication**: Gestiona la identidad de usuarios (dueños de licorerías y proveedores) y su acceso al sistema, incluyendo autenticación y autorización.


4. Bounded Context **Payment**: Gestionar las operaciones relacionadas con los pagos de los planes disponibles en la plataforma, incluyendo la suscripción, renovación, cancelación y validación de acceso según el estado del plan contratado.


5. Bounded Context **Reporting**: Genera documentación formal y reportes para el negocio, incluyendo:


- Remisión interna (movimiento entre almacenes)
- Guías de conservación/cuidados (para productos y almacenes especiales)
- Reportes de pérdidas (mermas, daños, vencimientos)
- Facturación (documentos legales para clientes)


6. Bounded Context **Notification**: Gestiona y distribuye alertas estratégicas sobre eventos críticos del negocio, incluyendo:


- Notificaciones de productos próximos a vencer
- Actualizaciones de estado en órdenes de compra/venta
- Alertas tempranas de falta de stock

## 4.6.4. Bounded Context Canvas ##

El Bounded Context Canvas es una herramienta visual que permite documentar y comprender mejor los diferentes Bounded Contexts dentro del dominio. A continuación se presentan ejemplos de Bounded Context Canvas para cada uno de los contextos identificados.

1. Bounded Context Canvas - **Inventory**:

![inventoryBC-canvas](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Bounded-Context-Canvas/inventoryBC-canvas.png)

2. Bounded Context Canvas - **Order**:

![orderBc-canvas](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Bounded-Context-Canvas/orderBC-canvas.png)

3. Bounded Context Canvas - **Authentication**:

![authenticationBc-canvas](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Bounded-Context-Canvas/authenticationBC-canvas.png)

4. Bounded Context Canvas - **Payment**:

![paymentBc-canvas](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Bounded-Context-Canvas/paymentBC-canvas.png)

5. Bounded Context Canvas - **Reporting**:

![reportingBc-canvas](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Bounded-Context-Canvas/reportingBC-canvas.png)

6. Bounded Context Canvas - **Notification**:

![notificationBc-canvas](../img/Chapter%20IV/Strategic-Domain-Driven-Design/Bounded-Context-Canvas/notificationBC-canvas.png)

## _4.7. Domain-Driven Software Architecture_ ##

Es una metodología que organiza y estructura el software en base a los dominios de negocio, permitiendo una mejor comprensión y gestión de la complejidad del sistema. A continuación se presentan los diagramas que representan la arquitectura del software:

### 4.7.1. Software Architecture Context Diagram ###

Un diagrama de contexto es una representación visual que muestra cómo un sistema interactúa con otros sistemas y actores externos. En el caso de StockSip, el diagrama de contexto ilustra las interacciones entre la aplicación y los usuarios, así como otros sistemas relevantes.

![StockSip Context Diagram](../img/Chapter%20IV/Software-Architecture/context-diagram.png)
> <p align="center">StockSip Context Diagram</p>

### 4.7.2. Software Architecture Container Diagrams ###

Un diagrama de contenedores es una representación visual que muestra los diferentes contenedores (aplicaciones, bases de datos, servicios, etc.) que componen un sistema y cómo interactúan entre sí. En el caso de StockSip, el diagrama de contenedores ilustra la arquitectura general del sistema, incluyendo la aplicación web, la base de datos y otros componentes relevantes.

![StockSip Container Diagram](../img/Chapter%20IV/Software-Architecture/container-diagram.png)
> <p align="center">StockSip Container Diagram</p>

### 4.7.3. Software Architecture Components Diagrams ###

Un diagrama de componentes es una representación visual que muestra los diferentes componentes de un contenedor y cómo interactúan entre sí. En el caso de StockSip, el diagrama de componentes ilustra la arquitectura interna de la aplicación web de cada bounded context.

1. Reporting Context

![StockSip Reporting Context Diagram](../img/Chapter%20IV/Software-Architecture/components-diagrams/reporting-component.png)
> <p align="center">StockSip Reporting Component Diagram</p>

2. Authentication Context

![StockSip Authentication Context Diagram](../img/Chapter%20IV/Software-Architecture/components-diagrams/authentication-component.png)
> <p align="center">StockSip Authentication Component Diagram</p>

3. Order Context

![StockSip Order Context Diagram](../img/Chapter%20IV/Software-Architecture/components-diagrams/order-component.png)
> <p align="center">StockSip Order Component Diagram</p>

4. Notification Context

![StockSip Notification Context Diagram](../img/Chapter%20IV/Software-Architecture/components-diagrams/notification-component.png)
> <p align="center">StockSip Notification Component Diagram</p>

5. Inventory Context

![StockSip Inventory Context Diagram](../img/Chapter%20IV/Software-Architecture/components-diagrams/inventory-component.png)
> <p align="center">StockSip Inventory Component Diagram</p>

6. Payment Context

![StockSip Payment Context Diagram](../img/Chapter%20IV/Software-Architecture/components-diagrams/payment-component.png)
> <p align="center">StockSip Payment Component Diagram</p>

## _4.8. Software Object-Oriented Design_ ##

### 4.8.1. Class Diagram ###

A continuación, se adjunta el link de acceso a la vista del diagrama de clases diseñado en LucidChart:
[Link de acceso al Diagrama de Clases en LucidChart](https://lucid.app/lucidchart/ec768747-d2c7-48c6-b460-c7356ca0aee1/edit?viewport_loc=1370%2C-110%2C7082%2C3161%2CHWEp-vi-RSFO&invitationId=inv_ac631679-aad8-41c4-8176-75d50798aa73)

<p align="center">
  <img src="../img/Chapter IV/class_diagram.png" 
  alt="class_diagram"/>

### 4.8.2. Class Dictionary ###

En esta sección, se detallará el diccionario de las principales clases que se muestran en el diagrama de clases previamente mostrado.

- **Profile:** Es la clase que contiene la información personal y de contacto del usuario que se registra en la aplicación. Esta clase es la que interactúa con las otras clases de la aplicación.
- **User:** Es la clase que contiene información de cuenta de la persona que se registra en la aplicación.
- **Role:** Es un _value object_ que indica si el usuario es proveedor de productos o dueño de una licorería. 
- **Membership:** Es la clase que contiene la información de la membresía que adquiere un usuario en la aplicación.
- **Address:** Es un _value object_ que contiene la información sobre la dirección geográfica de un usuario (lugar del local de venta).
- **ProfileId:** Es un _value object_ que contiene al identificador único de cada perfil de usuario. Se usa en otras clases para evitar referenciar la clase Profile completa.
- **ProviderId:** Es un _value object_ que contiene al identificador único de cada proveedor. Se usa en las órdenes de pedido para evitar referenciar la clase Provider completa.
- **Money:** Es un _value object_ que sirve para crear valores de moneda válidos en la aplicación. Contiene un valor que puede ser decimal y una divisa.
- **Report:** Es una clase que contiene información de cada reporte que genere el usuario sobre el inventario o productos que posea.
- **Invoice:** Es una clase que contiene la información relacionada a la factura generada tras una compra al proveedor.
- **SalesOrder:** Es una clase que contiene un objeto PurchaseOrder. Es la clase que manipula el **proveedor** y posee estados para indicar cuándo será entregado.
- **PurchaseOrder:** Es una clase que contiene la lista de productos que va a solicitar el **dueño de licorería** al **proveedor**. Posee un método para calcular el precio total del pedido a ordenar.
- **PurchaseOrderItem:** Es una clase que contiene el detalle del producto que necesita el **dueño de licorería** y su cantidad deseada. Posee un método para calcular el subtotal del ítem.
- **ReplenishmentPlan:** Es una clase que contiene la información detallada del plan de reabastecimiento que posee un **proveedor** para enviar los pedidos de sus clientes. Posee un atributo "frequencyDays" que es una métrica de aproximación para saber cuánto tiempo le toma a un **dueño de licorería** a solicitar un pedido para abastecerse.
- **ConservationGuide:** Es una clase que contiene información sobre los cuidados que debe tener el **dueño de licorería** al tratar con los productos que adquiere
- **Inventory:** Es la clase principal de la aplicación. Contiene productos y el stock de cada uno. Además, genera alertas dependiendo del estado actual del almacén. Posee métodos para actualizar el stock de productos y actualizar el almacén en general (eliminar, agregar productos).
- **Zone:** Es una clase que contiene información sobre la zona en la que se encuentra el almacén. Por ejemplo: La zona de muestra de productos, el almacén general de productos, entre otros.
- **Product:** Es una clase que contiene todo el detalle de los productos tanto del proveedor como del dueño de licorería. Posee métodos para actualizar la información del producto, para colocar un stock mínimo que, si el número de stock es más bajo que el colocado, podrá generar notificaciones sobre bajo stock al usuario.
- **ProductInfo:** Es un _value object_ que contiene la información más importante del producto como el nombre, cantidad de líquido, precio unitario y fecha de vencimiento.
- **Provider:** Es una clase que contiene información sobre un proveedor de productos.
- **Alert:** Es una clase que se usa para estructurar un mensaje de alerta o notificación que recibirá el usuario.

## _4.9. Database Design_ ##

### 4.9.1. Database Diagram ###
