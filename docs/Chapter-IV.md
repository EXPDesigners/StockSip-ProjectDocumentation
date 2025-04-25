# Capítulo 4: Product Design #

## _4.1. Style Guidelines_ ##

### 4.1.1. General Style Guidelines ###

### 4.1.2. Web Style Guidelines ###

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

### 4.7.1. Software Architecture Context Diagram ###

### 4.7.2. Software Architecture Container Diagrams ###

### 4.7.3. Software Architecture Components Diagrams ###

## _4.8. Software Object-Oriented Design_ ##

### 4.8.1. Class Diagram ###

### 4.8.2. Class Dictionary ###

## _4.9. Database Design_ ##

### 4.9.1. Database Diagram ###
