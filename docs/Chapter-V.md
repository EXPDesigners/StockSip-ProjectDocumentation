# Capítulo 5: Product Implementation, Validation & Deployment #

## _5.1. Software Configuration Management_ ##

### 5.1.1. Software Development Environment Configuration ###

* **Project Management**

  En el aspecto de gestión y desarrollo del ciclo de vida del proyecto se utilizó la aplicación Discord y Google Meet para las reuniones de grupo en las cuales se conversan sobre temas relacionados a avances y corrección de aspectos del proyecto. Luego, para la documentación del proyecto, se utilizó el formato MarkDown


* **Requirements Management**

  Para el manejo de los requisitos (historias de usuario, product backlog, sprint backlog), se utilizó Trello es una herramienta ideal para gestionar proyectos. Usando esta herramienta, se puede organizar un product backlog, ya que permite estructurar tareas visualmente en un tablero. Puedes crear listas que representen etapas del flujo de trabajo, y en cada lista añadir tarjetas que describan las user stories o tareas individuales. Estas tarjetas permiten detallar información clave, como prioridades, etiquetas de color, descripciones y checklists, facilitando así el seguimiento y la colaboración del equipo.

* **Product UX/UI Design**

  Para el desarrollo de plantillas de los User Persona  y del Impact Mapping se utilizó UXPressia. Es una plataforma especializada en la creación de mapas de experiencia del usuario ofreciendo una interfaz enfocada exclusivamente en UX que facilita la estructuración clara y profesional de estos elementos. Destaca por sus plantillas personalizables, la posibilidad de añadir datos reales, imágenes y métricas, y por permitir la colaboración en tiempo real. Para la creación del Lean UX Canvas se utilizó la aplicación canva. Esta aplicación es una herramienta versátil para crear diversos diseños. Canva facilita la colaboración del equipo y la exportación de los proyectos en archivo PNG o PDF, manteniendo el proceso creativo ordenado y atractivo. Para los Journey Mapping, Empathy Mapping, entre otros mapas,  se decidió utilizar Miro. Esta aplicación permite una colaboración en tiempo real entre equipos, ofrece una interfaz visual e intuitiva, y cuenta con plantillas prediseñadas que agilizan el proceso sin perder calidad metodológica.

  Luego, para el desarrollo de wireframes, mockups y prototipos de aplicación, se decidió utilizar Figma. Esta es una herramienta que facilita el diseño de interfaces, permitiéndonos trabajar con colores, imágenes, formas, y otros elementos visuales para crear nuestra aplicación. Nos ofrece la posibilidad de probar diversos modelos de dispositivos. Además, esta plataforma será clave en la creación de nuestro prototipo, ya que brinda una simulación interactiva que permite visualizar y experimentar el proyecto desde la perspectiva del usuario.


* **Software Development**

  Para el desarrollo del Software correspondiente al Landing Page, se utilizarán dos aplicaciones, las cuales son GitHub y JetBrains. La primera ayuda al equipo a gestionar de manera correcta los avances colaborativos del proyecto. Por otro lado, JetBrains ayudará a trabajar el proyecto con lenguajes como HTML5, CSS y JavaScript, y el framework Vue para el desarrollo del landing page, web services y frontend.

* **Software Testing**

  Las pruebas del Landing Page se realizarán mediante uso del navegador web para verificar que el diseño del mismo cumple con aspectos como el diseño responsivo en cualquier dispositivo desde el que se acceda al landing page del proyecto. Además, para visualizar que se han implementado correctamente elementos visuales que deben aparecer en las distintas secciones de la página.


### 5.1.2. Source Code Management ###

En esta sección, se describen los medios y esquemas de organización para gestionar de manera efectiva los archivos de proyecto relacionados a Landing Page, Web Services y Frontend Web Applications. En el caso de los repositorios, se usará GitHub para almacenar los archivos. Además, se implementará GitFlow. Esta función de GitHub ayudará al equipo, gracias a las ramas de características de lanzamiento, a poder trabajar paralelamente en el proyecto y a tomar el control de versiones de avance del proyecto.

#### **5.1.2.1. Repositorios**

A continuación, se adjuntan los enlaces para acceder a los repositorios donde se almacenarán los archivos de proyecto relacionados al Landing Page.

* **Landing Page: [https://github.com/EXPDesigners/StockSip-LandingPage.git](https://github.com/EXPDesigners/StockSip-LandingPage.git)**

**5.1.2.2. GitFlow**  
Como se mencionó previamente, GitFlow ayudará al equipo de desarrollo a gestionar de manera efectiva el proyecto en su ciclo de vida. En general, GitHub ayudará a facilitar el desarrollo del proyecto para el equipo ya que es más sencillo desarrollar trabajos en equipo en los repositorios de los archivos de proyecto.

##### **5.1.2.2.1. Main Branches**

* **Main Branch**   
  Llamada también rama principal del proyecto, esta es la rama predeterminada del proyecto creado en el repositorio. Esta rama representa el historial del proyecto lo que ayuda a llevar el control de versiones del mismo.

    
* **Develop Branch**  
  Llamada también rama de desarrollo del proyecto. Esta rama es una bifurcación de código original del proyecto para definir nuevos rumbos respecto del proyecto original que servirá para evaluar variaciones del proyecto para su evolución. Además, ayudan a incorporar nuevas funciones al proyecto.

##### **5.1.2.2.2. Supporting Branches**

* **Feature Branch**  
  También llamada rama de característica del proyecto, es una rama de desarrollo que ayuda a incorporar nuevas funciones al proyecto en desarrollo. Además, permite el aislamiento de la función agregada y que varios colaboradores puedan trabajar simultáneamente en dicha funcionalidad.

* **Release Branch**  
  También llamada rama de lanzamiento del proyecto, es una versión de código del proyecto que se usa para empezar un nuevo ciclo de lanzamiento del producto de software. Además, en esta rama se pueden realizar correcciones de errores de la versión pasada del proyecto. Finalmente, una vez terminada con esta rama, se suma a la rama principal del proyecto y se le asigna un nuevo número de versión de proyecto.

    
* **Hotfix Branch**  
  También llamada rama de corrección del proyecto, es una rama que permite dar mantenimiento al código del proyecto. Se utiliza principalmente para arreglar errores en alguna sección del producto de software de manera rápida.

#### **5.1.2.3. Release Versioning Conventions**

Para la nomenclatura de los lanzamientos del Landing Page, se utilizará Semantic Versioning que consta de tres partes para describir cambios mayores, cambios menores y parches para corrección de bugs, según la siguiente estructura:

* Número principal: Incrementa cuando se realiza un cambio mayor y significativo al proyecto.  
* Número secundario: Incrementa cuando se realiza un cambio menor al proyecto como arreglo de errores o agregación de características.  
* Número terciario: Incrementa cuando se realiza un parche al proyecto como una corrección de bugs o errores visuales.

#### **5.1.2.3. Commits Conventions**

Para los textos de mensajes en los *‘commits’* del proyecto en Git, se utilizará Conventional Commits. Estos son mensajes de confirmación que son fáciles de entender por los colaboradores del proyecto. Finalmente, estos mensajes siguen la siguiente estructura:

<!-- Commits-->
<p align="center">
  <img src="https://i.imgur.com/vfirypa.png" alt="Commits">

La sección *‘type’* indica el tipo de mensaje de confirmación que se usará. A continuación, la sección *‘description’* indica la descripción que se le agrega al mensaje de confirmación, por ejemplo, una característica agregada. Además, la sección *‘body’* incluye una descripción más detallada del cambio aplicado al proyecto.  
Luego, se tienen distintos tipos de mensajes de confirmación. Por ejemplo, se tiene el mensaje tipo *‘fix’* que incluye una corrección al proyecto. Utilizar este tipo conlleva aumentar el número terciario de la versión del proyecto (por ejemplo, de 1.0.0. a 1.0.1.). Después, utilizar el mensaje de tipo *‘feat’* conlleva agregar una nueva función a la aplicación, por lo tanto, se debe aumentar el número secundario de la versión (por ejemplo, de 1.0.0. a 1.1.0.). Finalmente, si se agrega una sección de tipo ‘BREAKING CHANGE’ indicaría que las versiones anteriores del proyecto dejarán de ser compatibles entre sí, lo que conlleva un cambio significativo y el aumento del número principal de la versión (por ejemplo, de 1.0.0. a 2.0.0.).

### 5.1.3. Source Code Style Guide & Conventions ###

En esta sección, se definen las referencias que se usaron para adoptar estrategias de nomenclatura de elementos de programación en los lenguajes que se usarán para la solución (HTML, CSS, JavaScript, y C\#). En general, la nomenclatura de los archivos y secciones en la programación se hará en inglés.

* **Nomenclatura en HTML:**  
  Para la codificación del proyecto en HTML, se utilizará el artículo *“HTML Style Guide and Coding Conventions”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que incluye la programación en HTML como si se debe escribir en minúsculas o mayúsculas las secciones del cuerpo del documento. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://www.w3schools.com/html/html5\_syntax.asp](https://www.w3schools.com/html/html5_syntax.asp)   
  Finalmente, se aplicará el contenido del artículo para la nomenclatura en HTML para el landing page de StockSip a desarrollar.

* **Nomenclatura en CSS:**  
  Para la codificación del proyecto en Cascading Style Sheets (CSS), se utilizará el artículo *“Google HTML/CSS Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que incluye la programación en CSS como capitalización en código de colores, referencias a imágenes, etc. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://google.github.io/styleguide/htmlcssguide.html](https://google.github.io/styleguide/htmlcssguide.html)   
  Finalmente, se aplicará el contenido del artículo para la nomenclatura en CSS para el estilo de colores que se quiere agregar al landing page de StockSip a desarrollar.

* **Nomenclatura en JavaScript:**  
  Para la codificación del proyecto en JavaScript, se utilizará el artículo *“Google JavaScript Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que conforman un proyecto desarrollado en JavaScript, según los lineamientos establecidos por Google.Se trata de la guía de estilo oficial de JavaScript de Google, un documento detallado que establece una serie de convenciones para escribir código JavaScript limpio, coherente y fácil de mantener, especialmente en equipos de trabajo. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://google.github.io/styleguide/jsguide.html](https://google.github.io/styleguide/jsguide.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockSip.  
    
* **Nomenclatura en Vue:**  
  Para la codificación del proyecto en Vue, se utilizará el artículo *“Vue Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que conforman un proyecto desarrollado con Vue.js 2\. Se trata de la guía de estilo oficial de Vue 2, en la cual se detallan las convenciones recomendadas para escribir código claro, consistente y fácil de mantener. Esta guía organiza sus recomendaciones en diferentes niveles de prioridad; reglas esenciales, reglas fuertemente recomendadas, reglas recomendadas, reglas de uso con precaución y reglas estrictamente opcionales. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://v2.vuejs.org/v2/style-guide/?redirect=true](https://v2.vuejs.org/v2/style-guide/?redirect=true)  
  Finalmente, se aplicará el contenido del artículo para el Frontend Applications de StockSip.  
    
* **Nomenclatura en C\#:**  
  Para la codificación del proyecto en C\#, se utilizará el artículo *“C\# Coding Conventions”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que conforman un proyecto desarrollado en C\#, según las convenciones oficiales de codificación establecidas por Microsoft. Se trata de la guía de convenciones de estilo de código para C\# publicada por Microsoft, la cual proporciona una serie de recomendaciones para escribir código claro, coherente y mantenible en aplicaciones .NET. A continuación se adjunta el enlace para acceder al artículo de referencia:  [https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockSip.

### 5.1.4. Software Deployment Configuration ###

En esta sección, se especifica la configuración para realizar el despliegue de la solución en el repositorio. Para realizar esto, se usó GitHub Pages para lanzar el landing page, Web Services y Frontend Web Applications. A continuación, se describen los pasos necesarios para desplegar el Landing Page del proyecto, empezando por la creación del repositorio hasta el lanzamiento del proyecto.

* **Paso 1: Creación del repositorio**  
  Como primer paso, se debe crear el repositorio en GitHub que será el lugar donde se aloja todo lo relacionado al Landing Page.

<p align="center">
  <img src="https://i.imgur.com/Kz79wpm.png" alt="Crear">

* **Paso 2: Carga de archivos necesarios**   
  Como segundo paso, se importan todos los archivos necesarios para el desarrollo del landing page como imágenes, archivos HTML, CSS y JavaScript.

<p align="center">
  <img src="https://i.imgur.com/RNjUuSV.png">

* **Paso 3: Preparar el lanzamiento**  
  Como tercer paso, se juntan todas las características del proyecto en una sola para verificar el correcto funcionamiento de cada una. Luego, se envía todo a la rama principal donde se encuentra, por defecto, el proyecto.

<p align="center">
  <img src="https://i.imgur.com/KtKEa2v.png">

* **Paso 4: Lanzar el Landing Page**  
  Como cuarto paso, cuando todo se encuentre en la rama principal, se accede a la sección Configuración del repositorio, luego, se selecciona la opción “GitHub Pages” y se seleccionará la rama principal que es la que se desea desplegar.

<p align="center">
  <img src="https://i.imgur.com/rIxAdyy.png">

* **Paso 5: Acceder al Landing Page**  
  Como paso final, el entorno otorgará un enlace para poder acceder al proyecto desplegado.
  
<p align="center">
  <img src="https://i.imgur.com/iE4Zzk7.png">

## _5.2. Landing Page, Services & Applications Implementation_ ##

### 5.2.1. Sprint 1 ###

### 5.2.1.1. Sprint Planning 1 ###

A continuación, se detalla, en la tabla siguiente, información sobre el planeameanto del primer sprint. En general, el objetivo de este sprint se centra en el desarrollo y despliegue de la primera versión del sitio web estático de StockSip.

| Sprint #                                     | Sprint 1                                               |
|----------------------------------------------|--------------------------------------------------------|
| <b> Sprint planning Background </b>          | --                                                     |
| Date                                         | 2025/04/20                                             |
| Time                                         | 05:00 PM                                               |
| Location                                     | Reunión mediante llamada virtual en Discord            |
| Prepared By                                  | Huamani Cruz, Camila Victoria                          |
| Attendees                                    | Huamani Cruz, Camila Victoria / Juarez Leon, Nicolas Emilio Walter / Gonzales Castillo, Angel Martin / Coronel Espinoza, Farid Sebastian |
| <b> Sprint Goal & User Stories </b>          | --                                                     |
| Sprint 1 Goal                                | <b> Our focus </b> is on develop and deploy the first version of the landing page <br> <b> We believe it delivers </b> a first view of what our product offers to our target segments <br> <b> This will be confirmed when </b> the target segments are visiting the site and can see and know the benefits on using our product. |
| Sprint 1 Velocity                            | 20                                                     |
| Sum of Story Points                          | 16                                                     |

### 5.2.1.2. Aspect Leaders and Collaborators ###

En esta sección, se incluye la matriz de liderazgo y colaboración desarrollada para este primer sprint. Los principales aspectos que se toman en cuenta en este sprint se centran en cada sección y el estilo que debe contener este mismo: inicio, funcionamiento de la aplicación, beneficios para cada segmento, testimonios, exploración de la aplicación, planes y contacto.

| Team Member                        | GitHub Username | Sección Inicio | Funcionamiento de la aplicación | Beneficios | Testimonios | Planes | Contacto | 
|------------------------------------|-----------------|----------------|---------------------------------|------------|-------------|--------|----------|
| Huamani Cruz, Camila Victoria      | victiila06      | L              | L                               |            |             |        | L        |
| Gonzales Castillo, Angel Martin    | XdiabloX426     |                |                                 |            |             | L      |          |
| Coronel Espinoza, Farid Sebastian  | Far14h          |                |                                 | L          |             |        |          |
| Juarez Leon, Nicolas Emilio Walter | JuarezLn10      |                |                                 |            | L           | C      |          |

### 5.2.1.3. Sprint Backlog 1 ###

Como se mencionó previamente en el planeamiento del sprint número 1, el objetivo del mismo es el desarrollar y desplegar una primera versión del landing page del producto. Esto conlleva implementar las diversas secciones que presenta un landing page que puedan ayudar a los visitantes del sitio a conocer mejor el producto en desarrollo.

Luego de definir el objetivo del sprint, se identificaron las historias de usuario útiles para este sprint. A continuación, se dividió cada historia de usuario en tareas relacionadas a la implementación y cumplimiento de dicha historia. Para ello, se utilizó la aplicación _Trello_ que nos ayuda a gestionar el progreso del sprint. 
[Link de acceso al Sprint Backlog #1 en Trello](https://trello.com/invite/b/68254069b45285c273087923/ATTI2507d3d76e72207b9b855c678811f82d3CF68D96/stocksip-sprint-backlog-1)

<p align="center">
  <img src="../img/Chapter V/sprint_backlog_1.png" 
  alt="sprint_backlog_1"/>

A continuación, se presenta la tabla con las tareas necesarias para completar satisfactoriamente este primer sprint. Además, se asignó un miembro del equipo a cada tarea a desarrollar y el estado de cada tarea.

| Sprint 1     | Sprint Backlog 1                                              |     |                                         |                                                                                                            |                    |                |            |
|--------------|---------------------------------------------------------------|-----|-----------------------------------------|------------------------------------------------------------------------------------------------------------|--------------------|----------------|------------|
| User Stories |                                                               | Work Item/Task                                |                                                                                                            |                    |                |            |
| Id           | Title                                                         | Id  | Title                                   | Description                                                                                                | Estimation (Hours) | Assigned to    | Status     |
| US001        | Ver propuesta de valor clara                                  | 001 | Diseñar sección inicio                  | Diseñar el encabezado con logo, menú de navegación y sección principal.                                    | 0.5                | Camila Huamani | Done       |
|              |                                                               | 002 | Crear estructura principal del Landing Page  | Crear la estructura principal de la página en HTML y los estilos iniciales en CSS.                         | 0.5                | Camila Huamani | Done       |
|              |                                                               | 003 | Diseñar sección contacto                | Diseñar el pie de página con información de contacto y enlaces a otras secciones                           | 0.5                | Camila Huamani | Done       |
|              |                                                               | 004 | Describir visión y misión del startup   | Agregar espacios que detallen la misión y visión de la empresa.                                            | 0.5                | Camila Huamani | Done       |
|              |                                                               | 005 | Añadir estilos a la sección Inicio      | Estilizar las secciones de contacto e inicio para que sean visiblemente agradables y llamativas.           | 0.5                | Camila Huamani | Done       |
| US002        | Acceder a explicación detallada sobre el uso de la aplicación | 001 | Añadir sección sobre funcionamiento de la aplicación | Separar una sección de la estructura general para agregar el contenido de explicación de cómo funciona la aplicación. | 0.3     | Camila Huamani | Done       |
|              |                                                               | 002 | Describir las funcionalidades           | Resumir cada funcionalidad que podrá utilizar cada segmento objetivo.                                      | 0.4                | Camila Huamani | Done       |
|              |                                                               | 003 | Añadir imágenes referenciales sobre funcionalidades | Para cada funcionalidad detallada, agregar una imágen referencial.                                         | 0.5                | Camila Huamani | Done       |
|              |                                                               | 004 | Ordenar las imagenes y las descripciones de funcionalidades | Ordenar y organizar cada funcionalidad descrita con su imagen.                                             | 0.4                | Camila Huamani | Done       |
|              |                                                               | 005 | Añadir estilos a la sección de funcionamiento | Usando CSS, añadir estilos a esta sección para que sea visiblemente llamativa.                             | 0.6                | Camila Huamani | Done      |
| US003        | Ver beneficios para licorerías	                               | 001 | Implementar sección beneficios para licorerías         | Diseñar la subsección de beneficios para dueños de licorerías agregando tarjetas con listas de beneficios. | 0.6                | Farid Coronel  | Done      |
|              |                                                               | 002 | Agregar íconos e imágenes a la sección beneficios para licorerías | Añadir imágenes referenciales al segmento objetivo al que son dirigidos los beneficios.                    | 0.5                | Farid Coronel  | Done      |
|              |                                                               | 003 | Añadir estilos a la sección de beneficios para licorerías | Añadir estilos usando CSS a la subsección para dar detalles visualmente agradables.                        | 0.5                | Farid Coronel  | Done      |
| US004        | Ver beneficios para proveedores                               | 001 | Implementar sección beneficios para proveedores | Diseñar la subsección de beneficios para proveedores agregando tarjetas con listas de beneficios.          | 0.6                | Farid Coronel  | Done      |
|              |                                                               | 002 | Agregar íconos e imágenes a la sección beneficios para proveedores | Añadir imágenes referenciales al segmento objetivo al que son dirigidos los beneficios.                    | 0.5                | Farid Coronel  | Done      |
|              |                                                               | 003 | Añadir estilos a la sección de beneficios para proveedores | Añadir estilos usando CSS a la subsección para dar detalles visualmente agradables.                        | 0.5                | Farid Coronel  | Done      |    
| US006        | Leer testimonios de clientes		                               | 001 | Añadir sección para testimonios         | Usando HTML, separar una sección para colocar todo el contenido de esta sección.                           | 0.5                | Nicolas Juarez | Done      |
|              |                                                               | 002 | Redactar testimonios de personas sobre la aplicación  | Redactar uno o varios testimonios para cada segmento objetivo que den su opinión sobre la aplicación.     | 0.4                | Nicolas Juarez | Done      |
|              |                                                               | 003 | Añadir tarjetas para cada testimonio    | Crear tarjetas en la estructura. Estas tarjetas contendrán el texto del testimonio.                        | 0.4                | Nicolas Juarez | Done      |
|              |                                                               | 004 | Añadir imágenes de personas para testimonios  | Agregar al lado del texto, una imagen referencial de la persona que está dando su testimonio.              | 0.4                | Nicolas Juarez | Done      |
|              |                                                               | 005 | Añadir estilos a la sección de testimonios | Agregar estilos a la sección usando CSS.                                                                   | 0.6                | Nicolas Juarez | Done      |
| US007        | Comparar planes gratis y premium	                             | 001 | Añadir sección de planes de suscripción | Diseñar la sección de planes con tarjetas que detallen las características de cada plan.                   | 0.5                | Martin Gonzales| Done      |
|              |                                                               | 002 | Añadir información para segmentos de dueños de licorería y proveedores | Añadir texto diferenciando funcionalidades que incluye el plan para cada segmento objetivo.                | 0.6                | Martin Gonzales| Done      |
|              |                                                               | 003 | Agregar comparación entre planes  | Añadir texto en las tarjetas que pueda ser utilizado para saber qué contiene el plan premium.              | 0.6                | Martin Gonzales| Done      |
|              |                                                               | 004 | Añadir íconos relacionados a planes | Añadir íconos relacionados a lo que ofrece cada plan para cada segmento objetivo.                          | 0.6                | Martin Gonzales| Done      |  
|              |                                                               | 005 | Añadir estilos a la sección planes | Estilizar la sección usando CSS.                                                                           | 0.5                | Nicolas Juarez | Done      |
| US008        | Conocer el precio y condiciones	                             | 001 | Añadir espacio para precios en las tarjetas de planes | En la sección de planes, agregar un recuadro que indique el precio para cada plan                          | 0.3                | Nicolas Juarez | Done      |
|              |                                                               | 002 | Añadir estilos a los precios | Estilizar los recuadros para precios usando CSS.                                                           | 0.3                | Martin Gonzales| Done      |


### 5.2.1.4. Development Evidence for Sprint Review ###

En esta sección, se describen los principales avances de implementación realizados en este primer sprint. Se tiene como principal avance la implementación de cada sección del landing page en su primera versión.
Cada miembro del equipo avanzó progresivamente con cada sección del landing page. Finalmente, se añadieron estilos a las secciones usando CSS.

A continuación, se muestra una tabla que contiene la información sobre los _commits_ hechos que contienen partes de las funcionalidades que debemos implementar para completar el primer sprint.

| Repository                             | Branch                           | Commit Id    | Commit Message                                                                 | Commited On |
|----------------------------------------|----------------------------------|--------------|--------------------------------------------------------------------------------|-------------|
| EXPDesigners/StockSip-LandingPage      | master                           | fb8ea1f      | feat(home): add home section and styles                                        | 23/04/2025  |
| EXPDesigners/StockSip-LandingPage      | master                           | 97add20      | feat(footer): add footer section and styles                                    | 23/04/2025  |
| EXPDesigners/StockSip-LandingPage      | feature/how-it-works             | a1bf565      | feat(how-it-works): add how it works section                                   | 23/04/2025  |
| EXPDesigners/StockSip-LandingPage      | feature/how-it-works             | 2266f74      | feat(how-it-works): add how it works section styles                            | 23/04/2025  |
| EXPDesigners/StockSip-LandingPage      | feature/how-it-works             | ecff3e9      | Update style.css                                                               | 23/04/2025  |
| EXPDesigners/StockSip-LandingPage      | feature/benefits                 | e0325a6      | feat(benefits): add initial html structure for benefits section.               | 26/04/2025  |
| EXPDesigners/StockSip-LandingPage      | feature/benefits                 | e20b3e0      | feat(benefits): add styles for benefits section.                               | 26/04/2025  |
| EXPDesigners/StockSip-LandingPage      | feature/testimonials             | b6994f1      | feat(testimonials): add html structure for testimonials section.               | 26/04/2025  |
| EXPDesigners/StockSip-LandingPage      | feature/testimonials             | 32520e9      | feat(testimonials): add css styles for testimonials section.                   | 26/04/2025  |
| EXPDesigners/StockSip-LandingPage      | feature/testimonials             | 56e5700      | docs: add testimonials images.                                                 | 26/04/2025  |
| EXPDesigners/StockSip-LandingPage      | feature/premium-plans            | 20f6557      | feat(premium-plans): add premium plans html.                                   | 26/04/2025  |
| EXPDesigners/StockSip-LandingPage      | feature/premium-plans            | 1167681      | chore: add premium plan image.                                                 | 26/04/2025  |
| EXPDesigners/StockSip-LandingPage      | feature/premium-plans            | 507f100      | feat(premium-plans): add premium plans css styles.                             | 26/04/2025  |

### 5.2.1.5. Execution Evidence for Sprint Review ###
El objetivo de este sprint fue realizar, en colaboracion con todo el equipo, la creacion del landing page.

<p align="center">
  <img src="https://i.imgur.com/iE4Zzk7.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/AtWUtPY.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/T5F4i5T.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/wyFDw0M.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/rwnScm7.png"/>
</p>

### 5.2.1.6. Software Deployment Evidence for Sprint Review ###
La organizacion de nuestro codigo se realizo en un repositorio en GitHub. Para el despliegue del landing page se utilizo GitHub Pages
* Primero se creo un repositorio para alojar el codigo del landing page
* Segundo, cada integrante del equipo creo una rama de cada funcion del landing page
<p align="center">
  <img src="https://i.imgur.com/WLeViFN.png"/>
</p>

* Tercero, se realizo el merge a develop para corregir errores
* Cuarto, cuando se corrigieron los errores, se realizo merge al master
* Quinto, se desplego el landing page mediante GitHub Pages, evidencia:
<p align="center">
  <img src="https://i.imgur.com/iE4Zzk7.png"/>
</p>

### 5.2.1.7. Team Collaboration Insights durint Sprint ###
El proyecto se realizo mediante repositorio en GitHub. Integrantes participantes:
<p align="center">
  <img src="https://i.imgur.com/DAyXhVR.png"/>
</p>

Commits de los integrantes en el Landing Page:
<p align="center">
  <img src="https://i.imgur.com/YdN51Bf.png"/>
</p>

Grafico de los push y merge realizados por el equipo:
<p align="center">
  <img src="https://i.imgur.com/6khY971.png"/>
</p>

### 5.3.1. Sprint 2 ###

### 5.3.1.1. Sprint Planning 2 ###

A continuación, se detalla, en la tabla siguiente, información sobre el planeameanto del segundo sprint. Además, para este sprint se definieron dos objetivos para cubrir los aspectos de sitio web estático y aplicación front-end. El primer objetivo se centra en desarrollar una mejora visual para el sitio web estático y añadir secciones para Call-To-Action para los visitantes del sitio web. Por otro lado, el segundo objetivo se centra en el desarrollo y despliegue de la primera versión de la aplicación front-end de StockSip.

| Sprint #                            | Sprint 2                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ----------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <b> Sprint planning Background </b> | --                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Date                                | 2025/04/29                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Time                                | 11:15 AM                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Location                            | Reunión presencial en el aula VH107 del curso en la sede Villa                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Prepared By                         | Gonzales Castillo, Angel Martin                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Attendees                           | Huamani Cruz, Camila Victoria / Juarez Leon, Nicolas Emilio Walter / Gonzales Castillo, Angel Martin / Coronel Espinoza, Farid Sebastian                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Sprint 1 Review Summary             | In the previous sprint, the team completed a first view of the Landing Page implementing the basic sections and styles it will need like Benefits, Plans, Information about the Startup.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Sprint 1 Retrospective Summary      | The principal area the team has to improve is having more communication between the members to let each others know how is the progress is going for each member. Now, the plan for next sprint is to work more organized so each member know what to do.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| <b> Sprint Goal & User Stories </b> | --                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Sprint 2 Goals                      | <b> Our focus </b> is to offer a more detailed visualization and a greater adaptability of the current StockSip Landing Page. <br> <b> We believe it delivers </b> different forms of accessing the Landing Page from different sizes of screens and languages to target segments and visitors. <br> <b> This will be confirmed when </b> our target segments and visitors access the Landing through different devices. <br><br> <b> Our focus </b> is on implement and deploy the first functional version of the Front-End application with key features like digital warehouses, the dashboard, registration of products, warnings, care guides and basic navigation between sections. <br> <b> We believe it delivers </b> a complete first vision of functionalities the aplication offers to the target segments. <br> <b> This will be confirmed when </b> our target segments register to  the application and use the principal funcionalities like warehouses and care guides. |
| Sprint 2 Velocity                   | 100                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Sum of Story Points                 | 99                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
<br>

### 5.3.1.2. Aspect Leaders and Collaborators ###

En esta sección, se incluye la matriz de liderazgo y colaboración desarrollada para este segundo sprint. Los principales aspectos que se toman en cuenta en este sprint se centran en cada las principales secciones que presenta el Front-End Web Application. Para esto, hemos definido las siguientes secciones: Inventarios y Zonas, Productos, Cuenta de Usuario, Reportes (Guía de cuidados y Reprote de pérdidas) y Alertas.

| Team Member                        | GitHub Username | Inventarios y Zonas | Productos | Cuenta de Usuario | Reportes (Guía de cuidados y Reporte de pérdidas) | Alertas |     |
| ---------------------------------- | --------------- | ------------------- | --------- | ----------------- | ------------------------------------------------- | ------- | --- |
| Huamani Cruz, Camila Victoria      | victiila06      |                     |           | L                 | C                                                 |         |     |
| Gonzales Castillo, Angel Martin    | XdiabloX426     |                     |           |                   | L                                                 | L       |     |
| Coronel Espinoza, Farid Sebastian  | Far14z          | L                   | C         |                   |                                                   |         |     |
| Juarez Leon, Nicolas Emilio Walter | JuarezLn10      | C                   | L         |                   |                                                   |         |     |


### 5.3.1.3. Sprint Backlog 2 ###

Como se mencionó previamente en el planeamiento del sprint número 2, el objetivo del mismo es (OBJETIVO).

Luego de definir el objetivo del sprint, se identificaron las historias de usuario útiles para este sprint. A continuación, se dividió cada historia de usuario en tareas relacionadas a la implementación y cumplimiento de dicha historia. Para ello, se utilizó la aplicación _Trello_ que nos ayuda a gestionar el progreso del sprint. 
[Link de acceso al Sprint Backlog #2 en Trello](https://trello.com/b/UjadbQbv/stocksip-sprint-backlog-2?filter=label:Aplicaciones%20Web)

<p align="center">
  <img src="https://i.imgur.com/8rBZn5r.png" 
  alt="Sprint goal y Stories del Sprint #2"/>
</p>

  <p align="center">
  <img src="https://i.imgur.com/e8fotVt.png" 
  alt="Sprint Backlog 2 en desarrollo"/>
  </p>
  

A continuación, se presenta la tabla con las tareas necesarias para completar satisfactoriamente este segundo sprint. Además, se asignó un miembro del equipo a cada tarea a desarrollar y el estado de cada tarea.

| Sprint 2     | Sprint Backlog 2                                              |             |                                                                                    |                                                                                                                                                                     |                    |                 |             |
|--------------|---------------------------------------------------------------|-------------|------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|-----------------|-------------|
| User Stories |                                                               | Work Item/Task                                                                                   |                                                                                                                                                                     |                    |                 |             |
| Id           | Title                                                         | Id          | Title                                                                              | Description                                                                                                                                                         | Estimation (Hours) | Assigned to     | Status      |
| US017        | Visualizar lista completa de productos en stock               | US017T001   | Crear una sección para visualizar los productos de un inventario                   | Crear un componente que muestre en una tabla los productos que posee un almacén.                                                                                    | 8                  | Nicolas Juarez  | In-Progress |
|              |                                                               | US017T002   | Crear una sección para el almacén seleccionado                                     | Crear una nueva sección que muestre toda la información relacionada al inventario como productos, capacidad, etc.                                                   | 8                  | Nicolas Juarez  | In-Progress |
|              |                                                               | US017T003   | Incluir un paginador para mostrar cierta cantidad de productos por página          | Implementar un paginador en la sección que ayude a organizar la información del inventario.                                                                         | 6                  | Nicolas Juarez  | In-Progress | 
|              |                                                               | US017T004   | Incluir un fake-api para simulación de datos de backend                            | Implementar un fake-api que ayude a probar los componentes usados que requieran mostrar, modificar o crear datos.                                                   | 5                  | Nicolas Juarez  | Done        |
| US016        | Registrar nuevo producto al inventario                        | US016T001   | Integrar un API para carga de imagenes de productos a la aplicación                | Utilizar Cloudinary para carga de URL de la imagen del producto subido.                                                                                             | 5                  | Nicolas Juarez  | In-Progress |
|              |                                                               | US016T002   | Crear un botón que permita cargar imagenes de productos al usuario                 | Programar un botón que abra el explorador de archivos del usuario para que pueda subir la foto de su producto.                                                      | 4                  | Nicolas Juarez  | In-Progress |
|              |                                                               | US016T003   | Crear un formulario base para edición y creación de cualquier entidad              | Añadir un componente que sirva de base para otros formularios que sirvan para crear y editar cualquier entidad.                                                     | 4                  | Nicolas Juarez  | Done        |
|              |                                                               | US016T004   | Crear un formulario para crear un producto en el inventario                        | Crear un componente usando como base el componente genérico de formularios para crear un formulario de creación de productos.                                       | 6                  | Nicolas Juarez  | In-Progress |
| US025        | Crear guía de conservación por tipo de licor                  | US025T001   | Crear un botón que permita crear una nueva guía de conservación                    | Programar un botón que muestre el formulario para crear una nueva guía de conservación.                                                                             | 4                  | Martin Gonzales | In-Progress |
|              |                                                               | US025T002   | Crear un formulario para crear una nueva guía de conservación                      | Crear un componente formulario usando como base el formulario base implementado.                                                                                    | 6                  | Martin Gonzales | Done        |
| US026        | Consultar guía de conservación desde el inventario            | US026T001   | Implementar un método para asignar una guía a un producto                          | Crear un método para asignar una guía de conservación a su respectivo producto.                                                                                     | 5                  | Martin Gonzales | In-Progress |
|              |                                                               | US026T002   | Implementar botón para visualizar guía de conservación de un producto              | Crear un botón en la sección de información de un producto en especifíco que muestre la guía de conservación de dicho producto.                                     | 7                  | Martin Gonzales | In-Progress |
| US024        | Visualizar productos en riesgo de vencimiento o merma         | US024T001   | Crear una sección que muestre los productos a cercanos a su vencimiento            | Crear un componente en el panel de control que muestre la lista de productos cuya fecha de vencimiento esté cerca a la fecha actual.                                | 5                  | Nicolas Juarez  | In-Progress |      
|              |                                                               | US024T002   | Crear un botón que redirija al usuario al producto cerca a su vencimiento          | Crear un botón que redirija al usuario a la información de producto del producto que ha seleccionado.                                                               | 6                  | Nicolas Juarez  | In-Progress | 
| US033        | Crear zonas de almacenamiento dentro del local                | US033T001   | Integrar un API para carga de imagenes referenciales a las zonas de inventario     | Integrar Cloudinary y utilizarlo para carga de URL de la imagen referencial de la zona de inventario creada.                                                        | 5                  | Farid Coronel   | In-Progress |
|              |                                                               | US033T002   | Crear un botón que permita cargar imagenes de zona de almacenamiento al usuario    | Programar un botón que abra el explorador de archivos del usuario para que pueda subir la foto referencial de su zona de inventario creada.                         | 4                  | Farid Coronel   | Done        |
|              |                                                               | US016T004   | Crear un formulario para crear un producto en el inventario                        | Crear un componente usando como base el componente genérico de formularios para crear un formulario de creación de zonas de inventario.                             | 6                  | Farid Coronel   | Done        |
| US027        | Generar reporte de pérdidas por tipo de baja                  | US027T001   | Crear un formulario para generar reporte de pérdidas                               | Crear un componente tomando de base el formulario genérico para crear un formulario para generar un reporte de pérdidas.                                            | 7                  | Martin Gonzales | Done        |                                                              
| US028        | Visualizar resumen económico de pérdidas                      | US028T001   | Crear un método que calcule el total de pérdidas                                   | Crear un método que calcule las pérdidas de los reportes generados para obtener un total.                                                                           | 4                  | Martin Gonzales | In-Progress |
|              |                                                               | US028T002   | Crear una sección que muestre el resumen económico de pérdidas                     | Crear un componente que muestre cada valor de pérdida y su total en el panel de control.                                                                            | 8                  | Martin Gonzales  | In-Progress |
| US020        | Detallar el estado de salida de productos del inventario      | US020T001   | Crear una nueva sección para mostrar los movimientos de salida de productos        | Crear una nueva sección donde se mostrará todo lo relacionado a movimientos de salida de los productos.                                                             | 4                  | Nicolas Juarez  | In-Progress |
|              |                                                               | US020T002   | Crear una sección de historial de movimientos de salida de productos               | Crear una sección dentro de la principal donde se muestre la lista de movimientos de salida realizados por un mismo usuario.                                        | 6                  | Nicolas Juarez  | In-Progress |
|              |                                                               | US020T003   | Crear un formulario para registrar la salida de un producto                        | Crear un nuevo componente formulario sobre la salida de uno o varios productos del inventario del usuario.                                                          | 5                  | Nicolas Juarez  | In-Progress |
|              |                                                               | US020T004   | Implementar un método que actualice el stock del producto                          | Crear un método que actualice el stock de un producto que haya sido usado para realizar un movimiento de salida.                                                    | 7                  | Nicolas Juarez  | In-Progress |
| US036        | Visualizar el mapa general de zonas y productos               | US036T001   | Crear una nueva sección para mostrar los inventarios del usuario                   | Crear una nueva sección en donde únicamente se mostrará las zonas de inventario del usuario.                                                                        | 4                  | Farid Coronel   | Done        |
|              |                                                               | US036T002   | Crear una sección que enliste los inventarios del usuario                          | Crear un componente que enliste todas las zonas de inventario que el usuario posee.                                                                                 | 5                  | Farid Coronel   | Done        |
| US022        | Alertas por próximo vencimiento                               | US022T001   | Designar sección para el panel de alertas                                          | Crear una nueva sección solamente para la visualización de alertas.                                                                                                 | 4                  | Martin Gonzales | Done        |
|              |                                                               | US022T002   | Implementar un método que verifique las fechas de vencimiento de los productos     | Crear un método que verifique las fechas de vencimiento y emita una alerta si la fecha de vencimiento es cercana a la fecha actual.                                 | 8                  | Martin Gonzales | Done        |
|              |                                                               | US022T003   | Implementar método para que la alerta se muestre en el panel de alertas            | Crear un método que cree la alerta y la almacene en el panel de alertas en cualquier momento.                                                                       | 6                  | Martin Gonzales | In-Progress |
| US038        | Ver alertas destacadas en el panel de control                 | US038T001   | Implementar método para agregar alertas importantes al panel de control            | Crear un método que coloque las alertas importantes en una sección del panel de control del usuario.                                                                | 4                  | Martin Gonzales | In-Progress |
|              |                                                               | US038T002   | Crear una sección para las alertas destacadas en el panel de control               | Crear un componente dentro de la sección de panel de control que muestre la lista de alertas destacadas.                                                            | 5                  | Martin Gonzales | In-Progress |
| US043        | Consultar historial de guías emitidas                         | US043T001   | Crear una sección para Guías de conservación                                       | Crear una sección nueva para que se muestre todo lo relacionado a guías de conservación como creación, edición o historial.                                         | 4                  | Martin Gonzales | In-Progress |
|              |                                                               | US043T002   | Implementar una sección para el historial de guías                                 | Crear un componente que muestra la lista de guías de conservación creadas.                                                                                          | 6                  | Martin Gonzales | Done        |
| US034        | Asignar productos a una zona específica                       | US034T001   | Crear un método para mover un producto a otro inventario                           | Crear un método colocado en un botón que permita al usuario cambiar el inventario del producto seleccionado.                                                        | 6                  | Nicolas Juarez  | In-Progress |                                               
|              |                                                               | US034T002   | Implementar un diálogo de confirmación sobre la transferencia de producto a otro inventario| Crear un diálogo para que el usuario confirme que desea transferir el producto seleccionado a otro inventario.                                              | 4                  | Nicolas Juarez  |
| US021        | Configurar alertas de reposición de productos                 | US021T001   | Implementar una sección para configurar alertas                                    | Crear una sección nueva dentro de la sección de Alertas para la configuración de las mismas.                                                                        | 4                  | Martin Gonzales | In-Progress |
|              |                                                               | US021T002   | Implementar un método para alterar el stock mínimo que pueda tener un producto     | Crear un método que permita al usuario alterar el número mínimo de productos que puede presentar en su inventario.                                                  | 6                  | Martin Gonzales | In-Progress |
| US037        | Visualizar resumen general en el panel de control             | US037T001   | Designar sección para el panel de datos                                            | Crear una nueva sección solamente para información del panel de datos o dashboard.                                                                                  | 4                  | Camila Huamani  | Done        |
|              |                                                               | US037T002   | Usar gráficos estadísticos para la visualización de información clave              | Implementar gráficos estadísticos que utilicen la información de productos e inventarios del usuario.                                                               | 8                  | Camila Huamani  | Done        |
|              |                                                               | US037T003   | Implementar las alertas en la sección del panel de datos                           | Implementar las alertas generadas sobre diversos aspectos en el panel de datos.                                                                                     | 7                  | Martin Gonzales | In-Progress |
| US044        | Cambiar estado de una guía a entregado                        | US044T001   | Implementar un método para asociar una guía de cuidado a un producto               | Desde la vista de proveedor, puede asociar una guía creada con un producto que al ser entregado al dueño de licorería, también podrá visualizar la guía.            | 8                  | Martin Gonzales | In-Progress |
|              |                                                               | US044T002   | Implementar acceso a la guía asociada al producto desde la información del mismo   | En el apartado de información del producto, dejar un espacio para acceder a la guía de cuidados del producto (si es que tiene una).                                 | 6                  | Nicolas Juarez  | In-Progress |
| US019        | Eliminar un producto del inventario                           | US019T001   | Implementar un botón que permita eliminar un producto registrado                   | Agregar un botón que permita al usuario eliminar un producto de su inventario.                                                                                      | 4                  | Nicolas Juarez  | In-Progress |
|              |                                                               | US019T002   | Implementar un diálogo de confirmación antes de eliminar un producto               | Programar un diálogo para que se muestre al presionar el botón de eliminar para que el usuario confirme su acción y no hayan equivocaciones.                        | 4.5                | Nicolas Juarez  | In-Progress |
|              |                                                               | US019T003   | Implementar un botón para disminuir stock del producto                             | Programar un botón que ayude al usuario a disminuir el contador del stock del producto.                                                                             | 5                  | Nicolas Juarez  | In-Progress |
| US018        | Editar un producto registrado                                 | US018T001   | Implementar un botón que permita editar un producto registrado                     | Agregar un botón que permita al usuario editar un producto existente en alguno de sus inventarios en la aplicación.                                                 | 4                  | Nicolas Juarez  | In-Progress |
|              |                                                               | US018T002   | Implementar un formulario para editar un producto registrado                       | Usar como base el formulario genérico para crear un componente formulario para la edición de información del producto seleccionado.                                 | 6                  | Nicolas Juarez  | In-Progress |
| US035        | Editar o eliminar una zona de almacenamiento                  | US035T001   | Implementar un botón que permita eliminar una zona de almacenamiento               | Agregar un botón que permita al usuario eliminar una zona de almacenamiento.                                                                                        | 4                  | Farid Coronel   | In-Progress |
|              |                                                               | US035T002   | Implementar un diálogo de confirmación antes de eliminar una zona de almacenamiento| Programar un diálogo para que se muestre al presionar el botón de eliminar para que el usuario confirme su acción y no hayan equivocaciones.                        | 4.5                | Farid Coronel   | In-Progress |
|              |                                                               | US035T003   | Implementar un botón que permita editar una zona de almacenamiento                 | Agregar un botón que permita al usuario editar una zona de almacenamiento existente en la aplicación.                                                               | 4.5                | Farid Coronel   | In-Progress |
|              |                                                               | US035T004   | Implementar un formulario para editar una zona de almacenamiento                   | Usar como base el formulario genérico para crear un componente formulario para la edición de información de la zona de almacenamiento seleccionada.                 | 6.5                | Farid Coronel   | In-Progress |
| US005        | Sección sobre la aplicación para el visitante                 | US005T001   | Agregar sección con imágenes de la aplicación                                      | En el Landing Page, se debe agregar una nueva sección que muestra imágenes de algunas pantallas principales de la aplicación.                                       | 4                  | Camila Huamani  | In-Progress |
|              |                                                               | US005T002   | Añadir imágenes a la sección sobre la aplicación                                   | En la sección sobre la aplicación del Landing Page, agregar imágenes de las principales secciones de la aplicación.                                                 | 4                  | Camila Huamani  | In-Progress |
|              |                                                               | US005T003   | Dar estilo a la sección sobre la aplicación                                        | Usar CSS para darle una mejor vista a la sección sobre la aplicación.                                                                                               | 4                  | Camila Huamani  | In-Progress |
|              |                                                               | US005T004   | Agregar un botón para cambiar de idiomas en el Landing Page                        | En el header del Landing Page, agregar un botón que sea programado para que cambie el idioma de la página.                                                          | 5.5                | Camila Huamani  | Done        |
| US045        | Editar datos personales del perfil                            | US045T001   | Crear una sección para editar información del usuario                              | Crear un componente dentro de la sección Perfil que permita al usuario editar información personal en la aplicación.                                                | 5                  | Camila Huamani  | Done        |
| US048        | Ver tipo de cuenta y plan actual                              | US048T001   | Crear un pequeño apartado para mostrar información de la cuenta del usuario        | Crear un pequeño componente dentro de la sección Perfil que muestra información sobre la cuenta de usuario como el tipo de cuenta.                                  | 4                  | Camila Huamani  | In-Progress |
| US046        | Subir y actualizar foto de perfil                             | US046T001   | Integrar un API para carga de imagenes de perfil a la aplicación                   | Utilizar Cloudinary para facilitar la carga de imágenes de perfil de los usuarios.                                                                                  | 4                  | Camila Huamani  | In-Progress |
|              |                                                               | US046T002   | Crear un pequeño apartado para mostrar la foto de perfil del usuario               | Crear un pequeño componente dentro de la sección Perfil que muestre la imagen del usuario.                                                                          | 4                  | Camila Huamani  | In-Progress |
|              |                                                               | US046T003   | Crear un botón que permita cargar archivos al usuario                              | Programar un botón que abra el explorador de archivos del usuario para que pueda subir su foto de perfil.                                                           | 4                  | Camila Huamani  | In-Progress |
| US050        | Ver fecha de vencimiento del Plan Premium                     | US050T001   | Crear un apartado para visualizar el tiempo restante del plan premium              | Crear un componente que contenta el tiempo restante que le queda a la suscripción del usuario registrado.                                                           | 4                  | Camila Huamani  | Done        | 
| US049        | Visualizar beneficios del Plan Premium                        | US049T001   | Crear un apartado para beneficios del plan premium                                 | Crear un componente que contenga información sobre beneficios que brinda el plan premium a los usuarios.                                                            | 4                  | Camila Huamani  | Done        | 
| US011        | Inicio de sesión de usuario registrado                        | US011T001   | Crear una sección para inicio de sesión de usuarios                                | Crear un componente para inicio de sesión de usuarios usando como requisitos el usuario y la contraseña.                                                            | 4                  | Camila Huamani  | Done        | 
|              |                                                               | US011T002   | Añadir estilos a la sección de inicio de sesión de usuario                         | Usar estilos con CSS para darle mejor vista a la pantalla de inicio de sesión.                                                                                      | 4                  | Camila Huamani  | Done        |
| US009        | Registro de usuario                                           | US009T001   | Crear una sección para registro de usuario                                         | Crear un componente para registro de usuarios usando espacios para completar como nombre, correo, contraseña y dirección.                                           | 4                  | Camila Huamani  | Done        |
|              |                                                               | US009T002   | Añadir estilos a la sección de registro de usuario                                 | Usar estilos con CSS para darle mejor vista a la pantalla de registro.                                                                                              | 4                  | Camila Huamani  | Done        |
|              |                                                               | US009T003   | Integrar un API para selección de dirección del usuario                            | Para el apartado de la dirección de usuario se debe usar un API que muestre un mapa con el que el usuario puede interactuar para marcar su ubicación                | 4.5                | Camila huamani  | Done        |
| US010        | Selección de rol durante registro                             | US010T001   | Crear un botón para seleccionar rol de usuario                                     | Usando PrimeVue, usar el componente del botón en cascada para que el usuario pueda elegir su rol al registrarse.                                                    | 4                  | Camila Huamani  | Done        |

### 5.3.1.4. Development Evidence for Sprint Review ###

En esta sección, se describen los principales avances de implementación realizados en este segundo sprint.

A continuación, se muestra una tabla que contiene la información sobre los _commits_ hechos que contienen partes de las funcionalidades que debemos implementar para completar el primer sprint.

| Repository                             | Branch                           | Commit Id | Commit Message                                                   | Commited On |
|----------------------------------------|----------------------------------|-----------|------------------------------------------------------------------|-------------|
| OpenDoors/StockSip-Front-End-App       |                                  |           |                                                                  |             |
| OpenDoors/StockSip-Front-End-App       |                                  |           |                                                                  |             |
| OpenDoors/StockSip-Front-End-App       |                                  |           |                                                                  |             |
| OpenDoors/StockSip-Front-End-App       |                                  |           |                                                                  |             |
| OpenDoors/StockSip-Front-End-App       |                                  |           |                                                                  |             |

### 5.3.1.5. Execution Evidence for Sprint Review ###

El objetivo de este sprint fue realizar, en colaboracion con todo el equipo, la actualización del landing page y la aplicación Front End.

#### **Landing Page**

**Inicio Actualizado**
<p align="center">
  <img src="https://i.imgur.com/bWmj21P.png"/>
</p>

<br>
**Estadísticas**
<p align="center">
  <img src="https://i.imgur.com/MO3fXPK.png"/>
</p>
<br>
**Propuesta de valor**
<p align="center">
  <img src="https://i.imgur.com/pSt2Wse.png"/>
</p>
<br>

**Exploración de la Aplicación**
<p align="center">
  <img src="https://i.imgur.com/IgEFQLT.png"/>
</p>
<br>
**Preguntas frecuentes**
<p align="center">
  <img src="https://i.imgur.com/POUjGSU.png"/>
</p>
<br>

#### **Front End Application**

**Inicio de sesión**
<p align="center">
  <img src="https://i.imgur.com/R0Jwexh.png"/>
</p>
<br>
**Perfil de usuario**

<p align="center">
  <img src="https://i.imgur.com/ND0kzSd.png"/>
</p>
<br>
**Reportes**

<p align="center">
  <img src="https://i.imgur.com/e6GsbX2.png"/>
</p>
<br>
**Guías de Conservación**
<p align="center">
  <img src="https://i.imgur.com/tNrzFR0.png"/>
</p>
<br>
**Alertas**
<p align="center">
  <img src="https://i.imgur.com/Pi1zS2F.png"/>
</p>
<br>

### 5.3.1.6. Team Collaboration Insights durint Sprint ###

El proyecto se realizo mediante repositorio en GitHub. Integrantes participantes:
<p align="center">
  <img src="https://i.imgur.com/DAyXhVR.png"/>
</p>

Commits de los integrantes en el Landing Page:
<p align="center">
  <img src="https://i.imgur.com/3B3zlvd.png"/>
</p>

Commits de los integrantes en el Front End:
<p align="center">
  <img src="https://i.imgur.com/Rcpfw7u.png"/>
</p>

Grafico de los push y merge realizados por el equipo:
<p align="center">
  <img src="https://i.imgur.com/qF08116.png"/>
</p>
