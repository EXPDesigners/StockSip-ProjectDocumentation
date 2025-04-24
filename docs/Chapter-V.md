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
| Sprint 1 Velocity                            | 25                                                     |
| Sum of Story Points                          | 21                                                     |

### 5.2.1.2. Aspect Leaders and Collaborators ###

En esta sección, se incluye la matriz de liderazgo y colaboración desarrollada para este primer sprint. Los principales aspectos que se toman en cuenta en este sprint se centran en cada sección y el estilo que debe contener este mismo: inicio, funcionamiento de la aplicación, beneficios para cada segmento, testimonios, exploración de la aplicación, planes y contacto.

| Team Member                        | GitHub Username | Sección Inicio | Funcionamiento de la aplicación | Beneficios | Testimonios | Planes | Contacto | 
|------------------------------------|-----------------|----------------|---------------------------------|------------|-------------|--------|----------|
| Huamani Cruz, Camila Victoria      | victiila06      | L              |                                 |            |             |        | L        |
| Gonzales Castillo, Angel Martin    | XdiabloX426     |                | L                               |            |             | C      |          |
| Coronel Espinoza, Farid Sebastian  | Far14h          |                |                                 | L          |             |        |          |
| Juarez Leon, Nicolas Emilio Walter | JuarezLn10      |                |                                 |            | L           | L      |          |

### 5.2.1.3. Sprint Backlog 1 ###

Como se mencionó previamente en el planeamiento del sprint número 1, el objetivo del mismo es el desarrollar y desplegar una primera versión del landing page del producto. Esto conlleva implementar las diversas secciones que presenta un landing page que puedan ayudar a los visitantes del sitio a conocer mejor el producto en desarrollo.

Luego de definir el objetivo del sprint, se identificaron las historias de usuario útiles para este sprint. A continuación, se dividió cada historia de usuario en tareas relacionadas a la implementación y cumplimiento de dicha historia. Para ello, se utilizó la aplicación _Trello_ que nos ayuda a gestionar el progreso del sprint. 

<p align="center">
  <img src="../img/Chapter V/sprint_backlog.png" 
  alt="sprint_backlog_1"/>

A continuación, se presenta la tabla con las tareas necesarias para completar satisfactoriamente este primer sprint. Además, se asignó un miembro del equipo a cada tarea a desarrollar y el estado de cada tarea.

| Sprint 1     | Sprint Backlog 1                                              |     |                                         |                                                                                                            |                    |                |            |
|--------------|---------------------------------------------------------------|-----|-----------------------------------------|------------------------------------------------------------------------------------------------------------|--------------------|----------------|------------|
| User Stories |                                                               | Work Item/Task                                |                                                                                                            |                    |                |            |
| Id           | Title                                                         | Id  | Title                                   | Description                                                                                                | Estimation (Hours) | Assigned to    | Status     |
| US001        | Ver propuesta de valor clara                                  | 001 | Diseñar sección inicio                  | Diseñar el encabezado con logo, menú de navegación y sección principal.                                    | 0.5                | Camila Huamani | Done       |
|              |                                                               | 002 | Estructura principal de la página       | Crear la estructura principal de la página en HTML y los estilos iniciales en CSS.                         | 0.5                | Camila Huamani | Done       |
|              |                                                               | 003 | Diseñar sección contacto                | Diseñar el pie de página con información de contacto y enlaces a otras secciones                           | 0.5                | Camila Huamani | Done       |
|              |                                                               | 004 | Describir visión y misión               | Agregar espacios que detallen la misión y visión de la empresa.                                            | 0.5                | Camila Huamani | Done       |
|              |                                                               | 005 | Añadir estilos                          | Estilizar las secciones de contacto e inicio para que sean visiblemente agradables y llamativas.           | 0.5                | Camila Huamani | Done       |
| US002        | Acceder a explicación detallada sobre el uso de la aplicación | 001 | Añadir sección de cómo funciona         | Separar una sección de la estructura general para agregar el contenido de explicación de cómo funciona la aplicación. | 0.3     | Martin Gonzales| To-do      |
|              |                                                               | 002 | Descripción de funcionalidades          | Resumir cada funcionalidad que podrá utilizar cada segmento objetivo.                                      | 0.4                | Martin Gonzales| To-do      |
|              |                                                               | 003 | Añadir imágenes referenciales           | Para cada funcionalidad detallada, agregar una imágen referencial.                                         | 0.5                | Martin Gonzales| To-do      |
|              |                                                               | 004 | Agrupar y ordenar imagenes y descripcion| Ordenar y organizar cada funcionalidad descrita con su imagen.                                             | 0.4                | Martin Gonzales| To-do      |
|              |                                                               | 005 | Añadir estilos                          | Usando CSS, añadir estilos a esta sección para que sea visiblemente llamativa.                             | 0.6                | Martin Gonzales| To-do      |
| US003        | Ver beneficios para licorerías	                               | 001 | Implementar sección beneficios          | Diseñar la subsección de beneficios para dueños de licorerías agregando tarjetas con listas de beneficios. | 0.6                | Farid Coronel  | To-do      |
|              |                                                               | 002 | Agregar íconos e imágenes               | Añadir imágenes referenciales al segmento objetivo al que son dirigidos los beneficios.                    | 0.5                | Farid Coronel  | To-do      |
|              |                                                               | 003 | Añadir estilos                          | Añadir estilos usando CSS a la subsección para dar detalles visualmente agradables.                        | 0.5                | Farid Coronel  | To-do      |
| US004        | Ver beneficios para proveedores                               | 001 | Implementar sección beneficios          | Diseñar la subsección de beneficios para proveedores agregando tarjetas con listas de beneficios.          | 0.6                | Farid Coronel  | To-do      |
|              |                                                               | 002 | Agregar íconos e imágenes               | Añadir imágenes referenciales al segmento objetivo al que son dirigidos los beneficios.                    | 0.5                | Farid Coronel  | To-do      |
|              |                                                               | 003 | Añadir estilos                          | Añadir estilos usando CSS a la subsección para dar detalles visualmente agradables.                        | 0.5                | Farid Coronel  | To-do      |    
| US006        | Leer testimonios de clientes		                               | 001 | Añadir sección para testimonios         | Usando HTML, separar una sección para colocar todo el contenido de esta sección.                           | 0.5                | Nicolas Juarez | To-do      |
|              |                                                               | 002 | Redactar testimonios ideales            | Redacatar uno o varios testimonios para cada segmento objetivo que den su opinión sobre la aplicación.     | 0.4                | Nicolas Juarez | To-do      |
|              |                                                               | 003 | Añadir espacios para cada testimonio    | Crear tarjetas en la estructura. Estas tarjetas contendrán el texto del testimonio.                        | 0.4                | Nicolas Juarez | To-do      |
|              |                                                               | 004 | Añadir imágenes referenciales           | Agregar al lado del texto, una imagen referencial de la persona que está dando su testimonio.              | 0.4                | Nicolas Juarez | To-do      |
|              |                                                               | 005 | Añadir estilos                          | Agregar estilos a la sección usando CSS.                                                                   | 0.6                | Nicolas Juarez | To-do      |
| US007        | Comparar planes gratis y premium	                             | 001 | Añadir sección de planes                | Diseñar la sección de planes con tarjetas que detallen las características de cada plan.                   | 0.5                | Martin Gonzales| To-do      |
|              |                                                               | 002 | Añadir información para ambos segmentos | Añadir texto diferenciando funcionalidades que incluye el plan para cada segmento objetivo.                | 0.6                | Martin Gonzales| To-do      |
|              |                                                               | 003 | Agregar texto comparativo               | Añadir texto en las tarjetas que pueda ser utilizado para saber qué contiene el plan premium.              | 0.6                | Martin Gonzales| To-do      |
|              |                                                               | 004 | Añadir íconos                           | Añadir íconos relacionados a lo que ofrece cada plan para cada segmento objetivo.                          | 0.6                | Martin Gonzales| To-do      |  
|              |                                                               | 005 | Añadir estilos                          | Estilizar la sección usando CSS.                                                                           | 0.5                | Nicolas Juarez | To-do      |
| US008        | Conocer el precio y condiciones	                             | 001 | Añadir espacio para precios             | En la sección de planes, agregar un recuadro que indique el precio para cada plan                          | 0.3                | Nicolas Juarez | To-do      |
|              |                                                               | 002 | Añadir estilos                          | Estilizar los recuadros para precios usando CSS.                                                           | 0.3                | Nicolas Juarez | To-do      |

### 5.2.1.4. Development Evidence for Sprint Review ###

### 5.2.1.5. Execution Evidence for Sprint Review ###

### 5.2.1.6. Software Deployment Evidence for Sprint Review ###

### 5.2.1.7. Team Collaboration Insights durint Sprint ###
