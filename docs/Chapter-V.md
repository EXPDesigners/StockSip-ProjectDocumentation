# Capítulo 5: Product Implementation, Validation & Deployment #

## _5.1. Software Configuration Management_ ##

### 5.1.1. Software Development Environment Configuration ###

### 5.1.2. Source Code Management ###

### 5.1.3. Source Code Style Guide & Conventions ###

### 5.1.4. Software Deployment Configuration ###

## _5.2. Landing Page, Services & Applications Implementation_ ##

### 5.2.1. Sprint 1 ###

### 5.2.1.1. Sprint Planning 1 ###

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
  alt="Sprint Backlog 1 de StockSip"/>

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
