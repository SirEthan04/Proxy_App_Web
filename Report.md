# Carátula

![UPC](recursos/imagenes/upc.png)

**Universidad Peruana de Ciencias Aplicadas S.A.C.**

**Ingeniería de Software**

**Ciclo: 5**

**1ASI0730-2620**

**Aplicaciones Web**

**NRC: 8074**

**Docente: Alex Humberto Sánchez Ponce**
---

### **Informe de Trabajo Final**

* **Nombre del Startup:** Proxy
* **Nombre del Producto:** BodeGo

---

### **Relación de Integrantes**

| Código | Apellidos y Nombres |
| :--- | :--- |
| U20241F385 | Blanco Medina, Jhorch Jhoseff |
| U20241G404 | Caldas Bravo, Mateo |
| U20241F610 | Chavez Sandoval, Dany Yohel |
| U202421082 | Saravia Hiso, Johan Álvaro |
| U20241E096 | Rojas Huaranga, Diego Rances |

---

* **Fecha:** 12/09/2026

---

# Registro de Versiones del Informe

* **Project Report Collaboration Insights**

---

# Contenido

## Tabla de Contenidos

* [Capítulo I: Introducción](#capítulo-i-introducción)

  * [1.1. Startup Profile](#11-startup-profile)

    * [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    * [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  * [1.2. Solution Profile](#12-solution-profile)

    * [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    * [1.2.2. Lean UX Process](#122-lean-ux-process)

      * [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      * [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      * [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      * [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  * [1.3. Segmentos objetivo](#13-segmentos-objetivo)

* [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

  * [2.1. Competidores](#21-competidores)

    * [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    * [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  * [2.2. Entrevistas](#22-entrevistas)

    * [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    * [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    * [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  * [2.3. Needfinding](#23-needfinding)

    * [2.3.1. User Personas](#231-user-personas)
    * [2.3.2. User Task Matrix](#232-user-task-matrix)
    * [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    * [2.3.4. Empathy Mapping](#234-empathy-mapping)
  * [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
  * [2.5. Ubiquitous Language](#25-ubiquitous-language)

* [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

  * [3.1. User Stories](#31-user-stories)
  * [3.2. Impact Mapping](#32-impact-mapping)
  * [3.3. Product Backlog](#33-product-backlog)

* [Capítulo IV: Product Design](#capítulo-iv-product-design)

  * [4.1. Style Guidelines](#41-style-guidelines)

    * [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    * [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  * [4.2. Information Architecture](#42-information-architecture)

    * [4.2.1. Organization Systems](#421-organization-systems)
    * [4.2.2. Labeling Systems](#422-labeling-systems)
    * [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    * [4.2.4. Searching Systems](#424-searching-systems)
    * [4.2.5. Navigation Systems](#425-navigation-systems)
  * [4.3. Landing Page UI Design](#43-landing-page-ui-design)

    * [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    * [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  * [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)

    * [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    * [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    * [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    * [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  * [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  * [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)

    * [4.6.1. Design-Level EventStorming](#461-design-level-eventstorming)
    * [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    * [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    * [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  * [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)

    * [4.7.1. Class Diagrams](#471-class-diagrams)
  * [4.8. Database Design](#48-database-design)

    * [4.8.1. Database Diagrams](#481-database-diagrams)

* [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)

  * [5.1. Software Configuration Management](#51-software-configuration-management)

    * [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    * [5.1.2. Source Code Management](#512-source-code-management)
    * [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    * [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  * [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)

    * [5.2.1. Sprint n](#521-sprint-n)

      * [5.2.1.1. Sprint Planning n](#5211-sprint-planning-n)
      * [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      * [5.2.1.3. Sprint Backlog n](#5213-sprint-backlog-n)
      * [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      * [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      * [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      * [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      * [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  * [5.3. Validation Interviews](#53-validation-interviews)

    * [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    * [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    * [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  * [5.4. Video About-the-Product](#54-video-about-the-product)

* [Conclusiones](#conclusiones)

  * [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

* [Video About-the-Team](#video-about-the-team)

* [Bibliografía](#bibliografía)

* [Anexos](#anexos)

---

# Student Outcome

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
| --- | --- | --- |
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | **Mateo Caldas Bravo** <br><br> AV1: Lideré la organización inicial del equipo mediante la coordinación de reuniones y distribución de actividades. Realicé aportes en la definición de la propuesta de valor de BodeGo, identificación del problema y revisión de los avances realizados durante esta primera etapa. <br><br> TB1: Asumí un rol activo en la coordinación del desarrollo de las funcionalidades relacionadas con productos y lotes, manteniendo comunicación con mis compañeros para identificar dependencias y resolver dificultades durante la implementación. También apoyé la integración de mi trabajo con los demás módulos del Frontend. <br><br> **Johan Alvaro Saravia Hiso** <br><br> AV1: Realicé el análisis inicial del usuario objetivo y colaboré en la recopilación de información sobre las necesidades de los minimarkets. Aporté ideas que permitieron orientar la solución hacia una problemática real identificada. <br><br> TB1: Participé en las decisiones relacionadas con la implementación de los movimientos de inventario, compartiendo avances y observaciones con el equipo. Mantuve una comunicación constante con mis compañeros para facilitar la integración de esta funcionalidad con el resto de la aplicación. <br><br> **Dany Yohel Chavez Sandoval** <br><br> AV1: Aporté conocimientos relacionados con la propuesta tecnológica del proyecto, analizando la estructura inicial de la plataforma y brindando ideas sobre los componentes necesarios para el desarrollo futuro de BodeGo. <br><br> TB1: Contribuí activamente al trabajo en equipo mediante el desarrollo del dashboard de BodeGo y el apoyo en la documentación del proyecto. Además, mantuve una comunicación constante con mis compañeros para coordinar avances y aportar al cumplimiento conjunto de los objetivos. <br><br> **Jhorch Jhoseff Blanco Medina** <br><br> AV1: Colaboré en la revisión de la propuesta inicial del proyecto, brindando observaciones y sugerencias para mejorar la definición de funcionalidades y características principales de la solución. <br><br> TB1: Participé en la coordinación del equipo durante la implementación de las funcionalidades de identidad y acceso, compartiendo avances y apoyando a mis compañeros cuando fue necesario. Mi trabajo permitió avanzar de manera conjunta en la construcción de los módulos del Frontend. <br><br> **Diego Rances Rojas Huaranga** <br><br> AV1: Realicé la organización y revisión de la documentación inicial del proyecto, ayudando a mantener la información ordenada y alineada con los objetivos definidos por el equipo. <br><br> TB1: Participé en el trabajo colaborativo mediante el desarrollo de las funcionalidades relacionadas con los conteos físicos. Compartí los avances realizados con el equipo y atendí las observaciones recibidas para facilitar la integración de esta funcionalidad con los demás componentes. | **AV1:** Durante la primera entrega, logramos establecer una dinámica de trabajo colaborativa en la que cada integrante asumió responsabilidades de acuerdo con sus habilidades. La comunicación y participación conjunta permitieron definir las bases del proyecto y avanzar hacia una propuesta común. <br><br> **TB1:** Durante el Sprint 2, fortalecimos el liderazgo compartido mediante la coordinación de avances, comunicación constante y apoyo entre los integrantes. La colaboración permitió integrar funcionalidades como productos y lotes, identidad y acceso, movimientos y conteos físicos dentro del Frontend de BodeGo. |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | **Mateo Caldas Bravo** <br><br> AV1: Organicé reuniones de coordinación y participé en la planificación de actividades necesarias para cumplir con los objetivos de la primera entrega. Ayudé a establecer prioridades relacionadas con la definición del problema, propuesta de valor y estructura inicial del proyecto. <br><br> TB1: Organicé las actividades necesarias para completar las funcionalidades de productos y lotes, priorizando las tareas de acuerdo con los objetivos establecidos para el Sprint 2. Realicé seguimiento de mis actividades para cumplir con los avances previstos. <br><br> **Johan Alvaro Saravia Hiso** <br><br> AV1: Colaboré durante las reuniones del equipo aportando ideas obtenidas del análisis del usuario objetivo. Ayudé a organizar la información recopilada y definir los aspectos importantes que debían considerarse en la solución. <br><br> TB1: Planifiqué las actividades relacionadas con los movimientos de inventario y distribuí el trabajo de acuerdo con las tareas definidas para el Sprint 2. Gestioné mis avances de manera ordenada para completar la funcionalidad asignada dentro del periodo establecido. <br><br> **Dany Yohel Chavez Sandoval** <br><br> AV1: Participé en la planificación de las actividades relacionadas con la propuesta tecnológica, aportando ideas sobre la estructura de la plataforma y los elementos necesarios para el desarrollo posterior del producto. <br><br> TB1: Participé en un entorno de trabajo colaborativo apoyando tanto en la implementación del dashboard como en la mejora de la documentación. Organicé mis actividades de acuerdo con las metas del equipo y cumplí con las tareas asignadas dentro del tiempo establecido. <br><br> **Jhorch Jhoseff Blanco Medina** <br><br> AV1: Apoyé en la coordinación del trabajo grupal mediante la revisión de avances y planteamiento de mejoras. Colaboré con mis compañeros para mantener una organización adecuada de las tareas asignadas. <br><br> TB1: Organicé las tareas relacionadas con la implementación de identidad y acceso considerando las prioridades definidas para el Sprint 2. Realicé las actividades asignadas y participé en la revisión de los avances para contribuir al cumplimiento de las metas establecidas. <br><br> **Diego Rances Rojas Huaranga** <br><br> AV1: Realicé seguimiento de los avances del equipo y colaboré en la revisión de documentos para asegurar que los entregables mantuvieran coherencia con los objetivos establecidos para esta etapa. <br><br> TB1: Planifiqué las actividades necesarias para implementar los conteos físicos de inventario y realicé seguimiento de su avance durante el Sprint 2. Cumplí con las tareas asignadas y coordiné los ajustes necesarios para completar la funcionalidad. | **AV1:** Durante la primera entrega, establecimos una organización de trabajo que permitió distribuir responsabilidades y mantener una comunicación constante. Esto facilitó la planificación de las actividades y el cumplimiento de los objetivos establecidos para la etapa inicial de BodeGo. <br><br> **TB1:** Durante el Sprint 2, logramos organizar las tareas de acuerdo con las funcionalidades asignadas y realizar seguimiento de los avances. La planificación y coordinación del equipo permitieron cumplir con las actividades previstas para la implementación del Frontend Web de BodeGo. |

---

# Capítulo I: Introducción
## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**Nombre del Startup:** Proxy  

**Nombre del Producto:** BodeGo  

**Enfoque de Negocios:** Aplicación web para la gestión y control de inventario en minimarkets, incluyendo productos, stock, lotes, vencimientos, mermas y movimientos operativos.  

**Propuesta de Valor:** BodeGo es una plataforma web de gestión de inventario para minimarkets que centraliza el control de productos, stock, lotes y fechas de vencimiento. La solución permite registrar movimientos de inventario generados por compras, ventas, mermas y ajustes de inventario, además de generar alertas y reportes que ayuden a reducir pérdidas y mejorar el control operativo.

**Mercado Objetivo:** El producto está dirigido al personal operativo y directivo de minimarkets, dividiendo a sus usuarios en dos segmentos clave: Administradores (dueños o gestores del negocio) y Empleados (personal de atención y almacén).


### 1.1.2. Perfiles de integrantes del equipo
| **Mateo Caldas Bravo (U20241G404)** |
| :--- |
| Soy un estudiante de 19 años cursando el quinto ciclo de la carrera de Ingeniería de Software. Considero que mi capacidad de tener un enfoque analítico y la eficiencia de desarrollar una solución eficiente. Mis habilidades blandas me permiten empatizar con los usuarios y acompañado de mi resiliencia, compromiso y productividad me permiten realizar propuestas mas estructuradas y optimas. |
| ![Foto Mateo](https://github.com/SirEthan04/Proxy_App_Web/blob/main/recursos/imagenes/mateofoto.jpg) |

| **Johan Alvaro Saravia Hiso (U202421082)** |
| :--- |
| Soy un estudiante de 20 años actualmente en el quinto ciclo de la carrera de Ingeniería de Software. Me considero una persona responsable y comprometida con los demás, especialmente al trabajar en equipo. Tengo facilidad para analizar problemas y buscar soluciones prácticas. Además, procuro escuchar y comprender las ideas de mis compañeros para lograr un buen trabajo en conjunto. |
| ![Foto Johan](https://github.com/SirEthan04/Proxy_App_Web/blob/main/recursos/imagenes/johanfoto.jpg) |

| **Chavez Sandoval, Dany Yohel (U20241G610)** |
| :--- |
| Soy un estudiante de 20 años actualmente en el quinto ciclo de la carrera de Ingeniería de Software. Me considero una persona responsable y comprometida con los demás, especialmente al trabajar en equipo. Tengo facilidad para analizar problemas y buscar soluciones prácticas. Además, procuro escuchar y comprender las ideas de mis compañeros para lograr un buen trabajo en conjunto. |
| ![Flujo Dany](https://github.com/SirEthan04/Proxy_App_Web/blob/main/recursos/imagenes/danyfoto.jpg) |

| **Blanco Medina, Jhorch Jhoseff (U20241F385)** |
| :--- |
| Soy un estudiante de 20 años actualmente en el quinto ciclo de la carrera de Ingeniería de Software. Me considero una persona responsable y comprometida con los demás, especialmente al trabajar en equipo. Tengo facilidad para analizar problemas y buscar soluciones prácticas. Además, procuro escuchar y comprender las ideas de mis compañeros para lograr un buen trabajo en conjunto. |
| ![Foto Jhorch](https://github.com/SirEthan04/Proxy_App_Web/blob/main/recursos/imagenes/jhorch%20foto.jpg) |

| **Rojas Huaranga, Diego Rances (U20241E096)** |
| :--- |
| Soy un estudiante de 22 años actualmente en el sexto ciclo de la carrera de Ingeniería de Software. Me concidero una persona conciderada, responsable y que le gusta hacer las cosas bien, me gusta trabajar en equipo, se me facilita el poder resolver problemas y siento que voy a hacer un buen trabajo este ciclo. Además, procuro escuchar y comprender las ideas de mis compañeros para lograr un buen trabajo en conjunto. |
| ![Foto Diego](https://github.com/SirEthan04/Proxy_App_Web/blob/main/recursos/imagenes/perfil-Diego.jpg) |

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática

En el sector del comercio minorista, específicamente en los minimarkets, la gestión operativa se realiza de manera empírica y manual. Esta falta de digitalización genera una baja visibilidad sobre el estado real de los inventarios, impactando directamente en la rentabilidad del negocio debido a la acumulación de mermas y a una deficiente comunicación interna entre el personal.

**Técnica de las 5 'W's y 2 'H's:**

**Who (¿Quién?):** Personal operativo y directivo de los minimarkets, dividido en dos roles clave: Administradores (dueños o gestores) y Empleados (personal de atención y almacén).  

**What (¿Qué?):** Deficiente gestión del inventario perecible que ocasiona mermas por productos vencidos, sumado a la falta de un sistema centralizado de control operativo y actualización de stock en tiempo real.  

**Where (¿Dónde?):** En las instalaciones, almacenes y puntos de venta de los minimarkets de Lima Metropolitana.  

**When (¿Cuándo?):** Ocurre de forma continua durante la operación diaria, intensificándose al momento de la recepción de mercadería, el despacho en caja y la rotación de productos en anaqueles.  

**Why (¿Por qué?):** Debido a la ausencia de herramientas digitales accesibles para el control de stock, la falta de asignación de permisos según el rol operativo y la dependencia de métodos manuales para identificar fechas de vencimiento y registrar operaciones.  

**How (¿Cómo?):** El Administrador gestiona el negocio sin visibilidad centralizada de reportes ni capacidad para lanzar ofertas estratégicas de liquidación. A su vez, el Empleado registra entradas, salidas, mermas o control de inventario mediante procesos manual ya sea anotaciones físicas o de memoria, lo que dificulta detectar a tiempo los productos próximos a caducar e impide mantener el stock actualizado durante la jornada.  

**How Much (¿Cuánto?):** Pérdidas económicas constantes para el minimarket por mermas no detectadas a tiempo, descuadres de stock en el punto de venta y una reducción en el margen de ganancia al no poder liquidar estratégicamente la mercadería de baja rotación.

### 1.2.2 Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
Actualmente, los minimarkets presentan dificultades para mantener un control adecuado de su inventario debido al uso de registros manuales o herramientas poco especializadas. Esto ocasiona diferencias en el stock, poca visibilidad sobre los productos disponibles y dificultades para identificar productos próximos a vencer.

Los Administradores necesitan contar con información centralizada que les permita supervisar el inventario, consultar reportes y tomar decisiones frente a posibles mermas. Por otro lado, los Empleados necesitan una forma rápida y sencilla de actualizar el stock y registrar las operaciones realizadas durante la jornada.

BodeGo busca solucionar esta problemática mediante una plataforma web que centralice la gestión del inventario y permita controlar productos perecibles controlar productos, lotes, fechas de vencimiento y movimientos de stock derivados de las operaciones del minimarket. La solución diferencia las funcionalidades disponibles para Administradores y Empleados y proporciona alertas e información para apoyar el control del inventario.

#### 1.2.2.2. Lean UX Assumptions

##### Business Assumptions

1. Existe una necesidad de mejorar la gestión de inventario en minimarkets que actualmente utilizan procesos manuales.
2. La reducción de mermas por productos vencidos puede generar un beneficio económico para el negocio.
3. Una plataforma web puede facilitar la gestión interna sin requerir herramientas especializadas.
4. La separación de funcionalidades entre Administradores y Empleados puede mejorar el control operativo.

##### User Assumptions

1. Los Administradores necesitan conocer rápidamente el estado general del inventario.
2. Los Administradores necesitan identificar productos próximos a vencer para tomar decisiones oportunas.
3. Los Empleados necesitan actualizar el stock de manera rápida y sencilla.
4. Los Empleados prefieren una interfaz simple para realizar sus tareas operativas.
5. Ambos usuarios necesitan acceder únicamente a las funcionalidades relacionadas con su rol.

##### Business Outcome Assumptions

1. Reducción de productos que vencen sin ser detectados previamente.
2. Mayor frecuencia de actualización del stock.
3. Disminución del uso de registros manuales para controlar el inventario.
4. Mayor visibilidad del estado del inventario para los Administradores.

##### User Outcome and Benefit Assumptions

1. Los Administradores podrán tener mayor control sobre el inventario y las mermas.
2. Los Administradores podrán tomar decisiones utilizando información organizada y actualizada.
3. Los Empleados podrán registrar con mayor facilidad los movimientos que afectan al inventario, como ingresos, salidas, mermas y ajustes.
4. Los Empleados podrán identificar rápidamente productos que requieren atención.
5. Ambos usuarios reducirán su dependencia de registros manuales.

##### Feature Assumptions

1. Un sistema de gestión de inventario permitirá mantener actualizado el stock mediante el registro trazable de entradas, salidas, mermas, devoluciones y ajustes.
2. Las alertas de vencimiento permitirán identificar productos perecibles antes de que se conviertan en mermas.
3. Un dashboard con reportes permitirá al Administrador conocer rápidamente el estado del inventario.
4. La gestión de ofertas permitirá al Administrador impulsar la salida de productos próximos a vencer.
5. Un sistema de roles permitirá diferenciar las acciones disponibles para Administradores y Empleados.

#### 1.2.2.3. Lean UX Hypothesis Statements

##### Hypothesis Statement 1

Creemos que si implementamos un sistema de gestión de inventario, entonces los Administradores y Empleados podrán mantener el stock actualizado con mayor facilidad, reduciendo las diferencias entre el inventario registrado y el inventario disponible.

##### Hypothesis Statement 2

Creemos que si implementamos alertas para productos próximos a vencer, entonces los Administradores y Empleados podrán identificarlos con anticipación y reducir la cantidad de productos que se convierten en mermas.

##### Hypothesis Statement 3

Creemos que si proporcionamos un dashboard con reportes del inventario, entonces los Administradores podrán conocer rápidamente el estado del negocio y tomar decisiones utilizando información organizada.

##### Hypothesis Statement 4

Creemos que si implementamos una funcionalidad para crear ofertas sobre productos próximos a vencer, entonces los Administradores podrán promover su salida antes de que estos productos se conviertan en pérdidas.

##### Hypothesis Statement 5

Creemos que si implementamos un sistema de roles para Administradores y Empleados, entonces cada usuario podrá acceder únicamente a las funcionalidades correspondientes a sus responsabilidades, mejorando el control de las operaciones.

#### 1.2.2.4. Lean UX Canvas

<table>
<tr>
<td width="33%" valign="top">

### Business Problem

Actualmente, los minimarkets presentan dificultades para mantener un control adecuado de su inventario debido al uso de registros manuales o herramientas poco especializadas.

Esto genera diferencias entre el stock registrado y el stock real, poca visibilidad sobre los productos disponibles y dificultades para identificar productos próximos a vencer.

Como consecuencia, los Administradores tienen dificultades para supervisar el negocio y tomar decisiones oportunas, mientras que los Empleados presentan complicaciones para mantener actualizado el inventario durante las operaciones diarias.

---

### Users

- **Administradores:** dueños o responsables del minimarket encargados de supervisar el inventario, consultar reportes, revisar alertas, gestionar productos y controlar los movimientos que modifican las existencias del negocio.

- **Empleados:** trabajadores encargados de realizar operaciones diarias relacionadas con el inventario, como registrar ingresos, salidas, mermas, conteos físicos y otras variaciones autorizadas de stock.

</td>

<td width="34%" valign="top">

### Solutions

- **Gestión centralizada de inventario**, permitiendo registrar, consultar y actualizar la información de los productos.

- **Control de productos perecibles**, facilitando la identificación de productos próximos a vencer.

- **Alertas de vencimiento** que permitan actuar antes de que los productos se conviertan en mermas.

- **Dashboard y reportes** para que el Administrador pueda visualizar información relevante sobre el inventario.

- **Gestión de ofertas** para productos próximos a vencer o con poca rotación.

- **Sistema de roles y permisos**, diferenciando las funcionalidades disponibles para Administradores y Empleados.

</td>

<td width="33%" valign="top">

### Business Outcomes

- Reducir la cantidad de productos que vencen sin ser identificados previamente.

- Incrementar la frecuencia de actualización del inventario.

- Disminuir la dependencia de registros manuales.

- Mejorar la visibilidad del estado del inventario.

- Facilitar la toma de decisiones relacionadas con stock, mermas y productos próximos a vencer.

---

### User Outcomes & Benefits

- **Administradores:** mayor control y visibilidad del inventario, acceso a información organizada y mejor capacidad para tomar decisiones.

- **Empleados:** mayor facilidad para actualizar el stock, identificar productos que requieren atención y registrar operaciones.

- Reducción del esfuerzo requerido para realizar tareas relacionadas con el control del inventario.

- Mayor claridad sobre las funciones correspondientes a cada usuario.

</td>
</tr>
</table>

<br>

<table>
<tr>
<td width="34%" valign="top">

### Hypothesis

Creemos que si BodeGo proporciona una plataforma web que centralice el control del inventario, permita identificar productos próximos a vencer y diferencie las funciones de Administradores y Empleados, entonces será posible mejorar la gestión operativa del minimarket y reducir las pérdidas relacionadas con productos perecibles.

Consideraremos que esta propuesta genera resultados positivos cuando los usuarios logren mantener el stock actualizado con mayor frecuencia, identificar productos próximos a vencer antes de que se conviertan en mermas y reducir su dependencia de registros manuales.

</td>

<td width="33%" valign="top">

### What's the most important thing we need to learn first?

- ¿Los problemas relacionados con el control del stock ocurren con suficiente frecuencia en los minimarkets?

- ¿La pérdida de productos por vencimiento representa una preocupación importante para los Administradores?

- ¿Los Empleados estarían dispuestos a utilizar una plataforma web para registrar y actualizar el inventario?

- ¿Las alertas de vencimiento aportarían valor durante las operaciones diarias del minimarket?

</td>

<td width="33%" valign="top">

### What's the least amount of work we need to do to learn the next most important thing?

- Realizar entrevistas a Administradores y Empleados de minimarkets para conocer sus procesos actuales.

- Desarrollar un prototipo de baja fidelidad con las principales funciones de BodeGo.

- Realizar pruebas de usuario enfocadas en tareas como actualizar stock, buscar productos e identificar productos próximos a vencer.

- Recopilar comentarios de los usuarios para validar o modificar los supuestos planteados.

</td>
</tr>
</table>

## 1.3. Segmentos objetivo

BodeGo está dirigido al personal involucrado en la gestión y operación de minimarkets de Lima Metropolitana. Para el desarrollo de la solución se consideran dos segmentos principales: los **Administradores**, responsables de supervisar y gestionar el negocio, y los **Empleados**, encargados de las actividades operativas relacionadas con el inventario, almacén y atención.

### Segmento: Administradores de minimarkets

Este segmento está conformado por dueños, administradores o encargados de minimarkets que necesitan mantener control sobre el inventario, las mermas y las operaciones realizadas dentro del establecimiento.

- **Aspectos Demográficos:**
  - Edad: 31 a 60 años.
  - Nivel educativo: Secundaria completa, formación técnica o universitaria.
  - Ocupación: Dueños, administradores o gestores de minimarkets.
  - Nivel tecnológico: Medio, con uso frecuente de smartphones, computadoras y aplicaciones de gestión o comunicación.

- **Aspectos Geográficos:**
  - Ubicación: Lima Metropolitana.
  - Zona geográfica: Distritos urbanos con presencia de minimarkets y comercios minoristas.
  - Acceso: Usuarios con conexión a internet y acceso a dispositivos móviles o computadoras.

- **Aspectos Psicográficos:**
  - Interés por mejorar la organización y rentabilidad de su negocio.
  - Buscan reducir pérdidas ocasionadas por productos vencidos o de baja rotación.
  - Valoran tener mayor control sobre el inventario y las actividades de sus empleados.
  - Interés en herramientas que faciliten la toma de decisiones.
  - Preferencia por soluciones sencillas que no compliquen las operaciones del negocio.

### Segmento: Empleados de minimarkets

Este segmento está compuesto por trabajadores encargados de realizar actividades operativas dentro del minimarket, como la recepción de mercadería, reposición de productos, atención al cliente y actualización del inventario.

- **Aspectos Demográficos:**
  - Edad: 18 a 28 años.
  - Nivel educativo: Secundaria completa, formación técnica o universitaria.
  - Ocupación: Personal de atención, caja, almacén o reposición.
  - Nivel tecnológico: Medio, familiarizados principalmente con smartphones y aplicaciones de uso cotidiano.

- **Aspectos Geográficos:**
  - Ubicación: Lima Metropolitana.
  - Zona geográfica: Minimarkets ubicados principalmente en zonas urbanas y comerciales.
  - Acceso: Personal con acceso a internet y dispositivos disponibles dentro del establecimiento.

- **Aspectos Psicográficos:**
  - Buscan realizar sus actividades de manera rápida y sencilla.
  - Valoran herramientas que reduzcan el trabajo manual y repetitivo.
  - Prefieren interfaces intuitivas y fáciles de aprender.
  - Necesitan acceder rápidamente a información sobre stock y productos.
  - Valoran tener claridad sobre las tareas y responsabilidades asignadas.
 
  ### Sustento Metodológico de los Segmentos Objetivo

La delimitación de los perfiles de usuario para **BodeGo** no responde a supuestos teóricos, sino que se fundamenta directamente en los hallazgos obtenidos durante el proceso de investigación y entrevistas (*Needfinding*) 

Por un lado, el segmento de Administradores (con un rango etario de 31 a 60 años) se sustenta en el perfil típico de los dueños y gestores de minimarkets entrevistados —tales como Víctor Alberca, Jimmy Ruiz y Silvia Bravo—, quienes manejan establecimientos comerciales enfrentando problemáticas directas de desorganización de inventario, mermas mensuales por caducidad de productos lácteos o perecibles, y una alta dependencia de herramientas informales (cuadernos y hojas de cálculo de Excel). Sus motivaciones reflejan la necesidad urgente de contar con alertas automatizadas y reportes de control financiero sin requerir una curva de aprendizaje tecnológica compleja.

Por otro lado, el segmento de **Empleados Operativos** (jóvenes entre 18 y 28 años) se alinea con el personal de mostrador, caja y almacén entrevistado (como Joseph, Andrés y Pablo), quienes soportan la mayor carga operativa durante las horas punta de atención al cliente. La investigación demostró que los errores de inventario ocurren principalmente por la fricción de registrar entradas y salidas manualmente bajo presión temporal. Por ello, este segmento requiere interfaces sumamente ágiles, accesibles desde dispositivos móviles o terminales web sencillos, que les permitan agilizar las tareas de reposición y mantener sincronizado el stock real del minimarket de manera inmediata.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

| Competidor | Descripción |
|---|---|
| **Bsale** | Es una plataforma de gestión comercial orientada a pequeñas y medianas empresas. Integra punto de venta, facturación electrónica, control de inventario en tiempo real y reportes. Cada venta o ingreso de mercadería puede actualizar automáticamente el stock, por lo que compite con BodeGo en el control y seguimiento del inventario. |
| **FácilVenta** | Es un software peruano dirigido a negocios como bodegas, minimarkets y tiendas. Integra punto de venta, facturación electrónica SUNAT y gestión de inventario. Para minimarkets incluye funciones como lector de códigos de barras, control de stock mínimo y alertas de productos próximos a vencer, por lo que es uno de los competidores más cercanos a la propuesta de BodeGo. |
| **Adiasoft** | Es un sistema ERP que cuenta con una solución específica para minimarkets, bodegas y retail. Ofrece punto de venta, inventario en tiempo real, códigos de barras, promociones, facturación electrónica, reportes y gestión de múltiples áreas del negocio. Se diferencia por tener un enfoque más amplio y empresarial que BodeGo. |
### 2.1.1. Análisis competitivo
| Competidor | Descripción |
|---|---|
| **Bsale** | Es una plataforma de gestión comercial orientada a pequeñas y medianas empresas. Integra punto de venta, facturación electrónica, control de inventario en tiempo real y reportes. Cada venta o ingreso puede actualizar automáticamente el stock. |
| **FácilVenta** | Es un software peruano dirigido a negocios como bodegas, minimarkets y tiendas. Integra punto de venta, facturación electrónica SUNAT y gestión de inventario. Para minimarkets incluye funciones como lector de códigos de barras, control de stock mínimo y alertas de productos próximos a vencer. |
| **Adiasoft** | Es un sistema ERP que cuenta con una solución específica para minimarkets, bodegas y retail. Ofrece punto de venta, inventario en tiempo real, códigos de barras, promociones, facturación electrónica, reportes y gestión de múltiples áreas del negocio. |
### 2.1.1. Análisis competitivo

| Categoría | Aspecto | **BodeGo** | **Bsale** | **FácilVenta** | **Adiasoft** |
|---|---|---|---|---|---|
| **Perfil** | **Overview** | BodeGo es una aplicación web pensada para ayudar a minimarkets a llevar un mejor control de su inventario. Busca facilitar tareas como registrar productos, controlar lotes, revisar vencimientos, registrar mermas. Además, diferencia las funciones que puede realizar un Administrador y un Empleado. | Bsale es una plataforma que reúne diferentes herramientas para manejar un negocio, como ventas, inventario, facturación electrónica y reportes. Permite que los movimientos realizados en el sistema actualicen el stock del negocio. | FácilVenta es un sistema peruano orientado a pequeños negocios como bodegas y minimarkets. Permite manejar ventas, inventario, facturación electrónica y productos próximos a vencer. | Adiasoft es un sistema de gestión empresarial que cuenta con soluciones para minimarkets y comercios. Permite manejar ventas, inventario, facturación, promociones y otras áreas del negocio. |
| **Perfil** | **Ventaja competitiva ¿Qué valor ofrece a los clientes?** | La principal propuesta de BodeGo es enfocarse en problemas comunes de los minimarkets, como diferencias de stock y productos que vencen sin ser detectados. Busca que el usuario pueda controlar lotes, recibir alertas y tomar acciones antes de que los productos se conviertan en pérdidas. | Su principal ventaja es que reúne varias funciones del negocio en una sola plataforma, permitiendo controlar ventas, inventario y facturación desde un mismo lugar. | Su ventaja es que está bastante orientado a bodegas y minimarkets peruanos. Incluye funciones útiles como control de vencimientos, códigos de barras, stock mínimo y facturación electrónica. | Su ventaja es la cantidad de funciones que ofrece. Puede ser utilizado por negocios que necesitan controlar no solo inventario y ventas, sino también otras áreas de la empresa. |
| **Perfil de Marketing** | **Mercado objetivo** | Dueños, administradores y empleados de minimarkets, especialmente pequeños y medianos negocios que necesitan mejorar el control de sus productos. Inicialmente se busca trabajar con minimarkets de Lima Metropolitana. | Pequeñas y medianas empresas que necesitan controlar ventas, inventario y facturación. | Bodegas, minimarkets, tiendas y pequeños o medianos comercios del Perú. | Minimarkets, tiendas, comercios retail y empresas que necesitan una herramienta de gestión más completa. |
| **Perfil de Marketing** | **Estrategias de marketing** | BodeGo podría promocionarse mediante redes sociales, una landing page, demostraciones del sistema y pruebas con minimarkets. La comunicación estaría enfocada principalmente en mostrar cómo el sistema puede ayudar a reducir pérdidas y facilitar el trabajo diario. | Promociona sus diferentes soluciones mediante su página web, demostraciones, contenido informativo y períodos de prueba para que los negocios conozcan la plataforma. | Utiliza su página web, demostraciones del sistema y contacto directo con los clientes. También destaca que su producto está pensado para negocios peruanos y cumple con requerimientos de SUNAT. | Promociona diferentes versiones de su sistema según el tamaño y tipo de negocio. También ofrece demostraciones y contacto con asesores para explicar las funcionalidades de la plataforma. |
| **Perfil de Producto** | **Productos & Servicios** | Control de productos, categorías, stock, lotes, fechas de vencimiento, mermas, alertas, ofertas, reportes, movimientos de inventario y gestión de usuarios según su rol. | Punto de venta, inventario, facturación electrónica, reportes, códigos de barras, clientes, caja y herramientas para ventas online. | Punto de venta, inventario, facturación electrónica SUNAT, códigos de barras, control de vencimientos, stock mínimo, compras, proveedores y reportes. | Punto de venta, inventario, códigos de barras, lotes, vencimientos, promociones, facturación electrónica, reportes y otros módulos empresariales. |
| **Perfil de Producto** | **Precios & Costos** | Se propone comenzar con un precio aproximado de **S/80 al mes** para un minimarket. La idea sería mantener un precio accesible mientras BodeGo se encuentra en crecimiento. | Sus planes se encuentran aproximadamente desde **S/189 mensuales**, aumentando según las herramientas y características que necesite el negocio. | Cuenta con planes aproximadamente desde **S/140 mensuales**, con opciones de mayor precio que incluyen más características y capacidad. | Cuenta con diferentes planes según las necesidades del negocio, desde opciones básicas hasta planes más completos que pueden superar los **S/300 mensuales**. |
| **Perfil de Producto** | **Canales de distribución (Web y/o Móvil)** | BodeGo funcionará principalmente como una aplicación web responsiva, por lo que podrá utilizarse desde una computadora, tablet o celular mediante un navegador. | Se puede utilizar desde la web y también cuenta con opciones para dispositivos móviles. | Puede ser utilizado desde computadoras y diferentes dispositivos para realizar operaciones del negocio. | Su plataforma puede utilizarse mediante internet desde diferentes dispositivos dependiendo del servicio contratado. |
| **Análisis SWOT** | **Fortalezas** | Está pensado específicamente para los problemas de inventario de los minimarkets. Se enfoca en productos perecibles, vencimientos y mermas. También busca tener una interfaz sencilla y separar claramente las funciones del Administrador y del Empleado. | Es una plataforma conocida y con varias herramientas integradas. Cuenta con inventario, ventas, facturación electrónica y funciones móviles. | Está enfocado directamente en bodegas y minimarkets. Cuenta con control de vencimientos, códigos de barras, stock mínimo y facturación electrónica. | Cuenta con una gran variedad de funciones y puede cubrir diferentes áreas de un negocio desde una sola plataforma. |
| **Análisis SWOT** | **Debilidades** | BodeGo todavía está en desarrollo y no tiene reconocimiento en el mercado. Además, actualmente no busca cubrir funciones como facturación electrónica o un sistema completo de punto de venta. | Al contar con muchas funciones, puede ser más de lo necesario para un minimarket pequeño que solamente busca mejorar su inventario. Además, el costo puede ser elevado para algunos negocios pequeños. | Algunas funciones y capacidades dependen del plan contratado, por lo que un negocio puede necesitar pagar un plan mayor conforme crece. | Al ser un sistema más completo, puede resultar más complejo para un pequeño minimarket que solamente necesita controlar su inventario y operaciones básicas. |
| **Análisis SWOT** | **Oportunidades** | Muchos minimarkets todavía trabajan con cuadernos, Excel o registros poco organizados. Existe la oportunidad de ofrecer una herramienta sencilla y económica que ayude a reducir productos vencidos y errores de stock. | Puede continuar creciendo mediante nuevas integraciones, comercio electrónico y herramientas para empresas que venden por diferentes canales. | Puede seguir captando pequeños negocios que desean pasar de procesos manuales a una solución digital con facturación electrónica. | Puede crecer entre negocios que necesitan manejar varias sucursales o centralizar diferentes áreas dentro de un mismo sistema. |
| **Análisis SWOT** | **Amenazas** | Existen competidores que ya cuentan con experiencia, clientes y funciones similares. Además, algunos minimarkets podrían preferir soluciones que también incluyan facturación electrónica y punto de venta. | Existen soluciones más económicas y especializadas que pueden resultar más atractivas para pequeños negocios. | Tiene que competir con plataformas más conocidas y con otras soluciones locales que pueden ofrecer precios similares. | Los minimarkets pequeños pueden preferir soluciones más sencillas y económicas en lugar de utilizar un ERP con una gran cantidad de módulos. |

### 2.1.2. Estrategias y tácticas frente a competidores
BodeGo busca diferenciarse de Bsale, FácilVenta y Adiasoft siendo una opción más simple y pensada especialmente para minimarkets. La idea es que ayude a llevar un mejor control del stock, detectar productos que están por vencer y evitar pérdidas por mermas.
También se plantea que tenga un precio accesible, alrededor de **S/80 al mes**, y que pueda usarse desde computadora o celular. Además, cada usuario tendría funciones según su rol, para que el sistema sea más fácil de entender y usar.
Como parte de la estrategia, se realizarían pruebas con minimarkets para mostrar de forma clara cómo BodeGo puede ayudar a ahorrar tiempo, reducir errores y tener un mejor control de los productos.

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

### Preguntas para el Segmento 1: Administrador (Dueño / Gestor del Minimarket)

1. ¿Cómo realiza actualmente el control del stock de productos en su minimarket?
2. ¿Qué dificultades tiene para conocer la cantidad real de productos disponibles?
3. ¿Cómo identifica actualmente los productos que están próximos a vencer?
4. ¿Con qué frecuencia tiene pérdidas por productos vencidos o que no se venden a tiempo?
5. ¿Cómo se informa sobre los cambios de stock realizados por sus empleados?
6. ¿Qué información considera importante para controlar mejor el inventario de su negocio?
7. ¿Qué acciones realiza cuando detecta productos próximos a vencer o con poca rotación?
8. ¿Cómo decide cuándo aplicar descuentos o promociones a determinados productos?
9. ¿Con qué frecuencia encuentra diferencias entre el stock registrado y el stock real?
10. ¿Qué funciones le gustaría encontrar en un sistema digital para gestionar su inventario?

### Preguntas para el Segmento 2: Empleado (Personal Operativo / Atención y Almacén)

1. ¿Cómo registra actualmente las entradas y salidas de productos durante su jornada?
2. ¿Qué tan fácil le resulta conocer la cantidad disponible de un producto? 
3. ¿Cómo revisa o identifica los productos que están próximos a vencer?
4. ¿Qué hace cuando encuentra un producto vencido o cercano a su fecha de vencimiento? 
5. ¿En qué momentos del día suelen presentarse más errores en el control del inventario?
6. ¿Cómo comunica al administrador los cambios de stock o problemas con los productos?
7. ¿Qué dificultades tiene al momento de registrar la llegada de nueva mercadería?
8. ¿Con qué frecuencia encuentra diferencias entre el stock registrado y el stock disponible?
9. ¿Qué herramienta o función facilitaría el registro de productos durante su trabajo?
10. ¿Qué actividad relacionada con el inventario le parece más lenta o complicada de realizar?

### 2.2.2. Registro de entrevistas
### Segmento Administradores

| |
|---|
| ![Imagen de la entrevista](recursos/imagenes/admin-diego.png) |
| **Nombres y apellidos:** Victor <br>**Edad:** 35  <br>**Distrito:** San Martin de Porrez  <br>**Resumen de la entrevista:** Víctor Alberca, de 35 años, quien trabaja como administrador de un minimarket y anteriormente tuvo experiencia administrativa en un hotel. Actualmente, el control de inventario del minimarket se realiza principalmente mediante Excel y revisiones manuales. Cuando llega mercadería, se compara la factura o guía de remisión con los productos recibidos físicamente y posteriormente se registra la información en el sistema. Sin embargo, uno de los principales problemas es que, debido a la rapidez con la que entran y salen los productos y a la carga de trabajo, algunas ventas, salidas, devoluciones o productos dañados no se registran correctamente, provocando diferencias entre el stock registrado y el stock real. Otro problema importante es el control de las fechas de vencimiento. Actualmente, los trabajadores deben revisar manualmente los productos, especialmente lácteos, embutidos y otros productos perecibles. Las pérdidas por vencimiento ocurren principalmente de manera mensual y afectan sobre todo a productos de baja rotación o marcas nuevas que tienen poca demanda. Para evitar pérdidas, cuando un producto está próximo a vencer o lleva mucho tiempo sin venderse, se toman medidas como colocarlo en una posición más visible, crear combos, promociones o descuentos. El objetivo es recuperar la inversión antes de tener que desechar el producto. La comunicación sobre cambios en el inventario también se realiza mediante la caja y un grupo de WhatsApp, donde los empleados informan devoluciones, daños u otros incidentes. Sin embargo, muchas veces estos registros se olvidan, generando inconsistencias en el inventario. Víctor considera que un sistema de inventario debería proporcionar información sobre los productos más vendidos, los de menor rotación, productos próximos a vencer, niveles de stock y el dinero invertido en mercadería. También considera importante que el sistema pueda recomendar o generar promociones para productos que tengan poca salida. <br><br>**URL:** https://drive.google.com/file/d/1eK8N08rAOmo-4m1A1KHYJvtxkJl-KD6T/view?usp=drive_link |

| |
|---|
| ![Imagen de la entrevista](recursos/imagenes/Admin1-Entrevista.png) |
| **Nombres y apellidos:** Jimmy Ruiz <br>**Edad:** 31 <br>**Distrito:** San Juan de Lurigancho <br><br>**Resumen de la entrevista:**  <br>Jimmy, administrador de un pequeño minimarket, comenta que actualmente controla el inventario de forma mixta: registra diariamente los movimientos en un cuaderno y, al finalizar la semana, pasa la información a una plantilla de Excel. Sin embargo, uno de los principales problemas es que durante las horas de mayor venta no siempre se registran correctamente todos los productos, lo que genera diferencias entre el stock registrado y el stock real. <br><br>El control de los productos próximos a vencer se realiza de manera manual. Los trabajadores revisan los estantes y el almacén mientras reponen o limpian los productos. A pesar de estas revisiones, se presentan pérdidas una o dos veces al mes, principalmente en productos como lácteos y panes que pueden quedar poco visibles al fondo de los estantes. <br><br>Cuando un producto está próximo a vencer o tiene poca rotación, lo colocan cerca de la caja o en zonas más visibles para facilitar su venta. También aplican descuentos o promociones para intentar recuperar la inversión antes de que el producto venza. <br><br>Jimmy menciona que las diferencias de stock ocurren casi todas las semanas, especialmente en golosinas, galletas, cereales y gaseosas, debido a errores de registro o consumo del personal. <br><br>Finalmente, considera importante contar con un sistema digital, principalmente desde el celular, que permita recibir alertas automáticas de bajo stock y vencimientos, generar reportes de los productos más vendidos y conectarse con un lector de códigos de barras para registrar fácilmente productos, pérdidas o roturas. <br><br>**URL:** https://drive.google.com/file/d/1eAsgHwrdiH4P3uMjAwPBXgNagRQ5b_eY/view?usp=drive_link |

| |
|---|
| ![Imagen de la entrevista](recursos/imagenes/Admin2-Entrevista.png) |
| **Nombres y apellidos:** Silvia Bravo <br>**Edad:** 49  <br>**Distrito:** Independencia <br><br>**Resumen de la entrevista:**  <br>Silvia Bravo, de 49 años, participa en la administración de un minimarket y explica que el control del stock se realiza revisando y contando los productos disponibles. Una de las principales dificultades es que, en ocasiones, la cantidad real no coincide con la cantidad que deberían tener registrada, por lo que deben estar pendientes constantemente del inventario. <br><br>La identificación de productos próximos a vencer se realiza revisando manualmente las fechas de vencimiento. Las pérdidas por vencimiento ocurren con frecuencia, especialmente en productos como yogur, leche y panes, ya que tienen una duración más corta. Para mantenerse comunicados sobre los cambios en el inventario, utilizan principalmente WhatsApp y un registro donde anotan información importante, como las fechas de vencimiento y los productos que ingresan. <br><br>Cuando un producto está próximo a vencer o tiene poca rotación, realizan ofertas, por ejemplo, combinándolo con otro producto que sí tiene mayor salida y reduciendo el precio para facilitar su venta. Los descuentos se aplican principalmente cuando los productos están cerca de vencer. Finalmente, Silvia considera que sería útil contar con un sistema digital que envíe alertas sobre los productos próximos a vencer y que también brinde orientación sobre qué acciones tomar para evitar pérdidas. <br><br>**URL:** https://drive.google.com/file/d/1pg_DvKHgaqZ3YP34jLtGyl6jV7oni1yI/view?usp=drive_link |

### Segmento Empleados

| |
|---|
| ![Imagen de la entrevista](recursos/imagenes/Empleado3-Entrevista.png) |
| **Nombres y apellidos:** Joseph <br>**Edad:** 23 <br>**Distrito:** Puente Piedra <br><br>**Resumen:**  <br>Joseph trabaja en un minimarket realizando tareas de atención al cliente, registro de ventas, reposición de productos y control de almacén. Actualmente, las entradas y salidas de productos se registran manualmente en un cuaderno, lo que puede generar errores o confusiones, especialmente en las horas de mayor movimiento o cuando llega mercadería mientras se atiende a los clientes. <br><br>Para conocer el stock disponible, deben revisar y contar físicamente los productos en los estantes, lo cual puede resultar lento y complicado. La revisión de fechas de vencimiento también se realiza manualmente, generalmente cuando llega nueva mercadería. Si encuentran un producto vencido, lo retiran del estante y se lo comunican al administrador para evitar que llegue al cliente. <br><br>Joseph menciona que los errores en el inventario suelen ocurrir principalmente durante las horas de mayor venta, cuando hay más presión de trabajo. Los cambios de stock o problemas con los productos se comunican de forma verbal y mediante el cuaderno de registro. Además, considera que las tareas más tediosas son contar los productos y revisar uno por uno las fechas de vencimiento. <br><br>Finalmente, señala que sería útil contar con una herramienta digital sencilla que permita registrar entradas y salidas, consultar el stock disponible y facilitar el control del inventario, reduciendo así el tiempo y los errores del proceso manual. <br><br>**URL:** https://drive.google.com/file/d/1TD5vcQrjeOiQnoPlT7bziEpWkTBYGCBs/view?usp=drive_link |

| |
|---|
| ![Imagen de la entrevista](recursos/imagenes/Empelado2-Entrevista.png) |
| **Nombres y apellidos:** Andres Marzano <br>**Edad:** 20  <br>**Distrito:** San Juan de Lurigancho <br><br>**Resumen:**  <br>Andrés Marzano, de 20 años, tiene experiencia trabajando en atención al cliente y almacén. Explica que las entradas de productos se registraban después de verificar que la mercadería recibida coincidiera con la información del documento de entrega, para luego ingresarla en el sistema. Las salidas, por su parte, se registraban mediante boletas electrónicas. <br><br>Uno de los principales problemas era conocer con precisión la cantidad disponible de productos, especialmente cuando se trataba de artículos pequeños, ya que podían cometerse errores al contarlos. Esta tarea se volvía más complicada cuando, al mismo tiempo, tenían que atender a los clientes. <br><br>Para controlar los productos próximos a vencer, colocaban adelante los que tenían menor tiempo de vida útil y dejaban al fondo los productos recién llegados. Además, revisaban las fechas de vencimiento en los turnos de día y noche. Cuando un producto estaba cerca de vencer, trataban de darle prioridad a su venta; si ya quedaban pocos días y no se lograba vender, se registraba como merma para calcular las pérdidas. <br><br>Finalmente, Andrés señala que los mayores errores en el control del inventario se presentaban principalmente durante las mañanas, cuando había mayor cantidad de clientes y debían dividir su atención entre las ventas y las tareas de inventario. <br><br>**URL:** https://drive.google.com/file/d/1BCO2lHzXeeZyN7DED3hQVZv_ULh0Zdx2/view?usp=drive_link |

| |
|---|
| ![Imagen de la entrevista](recursos/imagenes/Empleado1-Entrevista.png) |
| **Nombres y apellidos:** Pablo Moreno <br>**Edad:** 20  <br>**Distrito:** San Juan de Lurigancho <br><br>**Resumen:**  <br>Pablo Moreno, empleado de un minimarket, explica que las entradas y salidas de productos se registran principalmente de forma manual y, en algunos casos, mediante Excel. Este proceso no siempre se actualiza de inmediato, por lo que a veces existen diferencias entre el stock registrado y la cantidad real disponible, especialmente en productos de alta rotación o durante las horas de mayor atención. La revisión de productos próximos a vencer también se realiza manualmente, verificando las fechas directamente en los productos. Cuando un producto está vencido se retira de la venta, mientras que los productos próximos a vencer pueden colocarse en zonas más visibles o venderse con descuento. Pablo también menciona que los errores suelen ocurrir cuando hay muchos clientes o cuando llega bastante mercadería al mismo tiempo. Los problemas de stock se comunican personalmente o por WhatsApp, aunque la información puede perderse entre tantos mensajes. Finalmente, considera que sería útil contar con un sistema digital accesible desde el celular o computadora que permita registrar entradas y salidas, actualizar el stock rápidamente y recibir alertas sobre productos próximos a vencer. <br><br>**URL:** https://drive.google.com/file/d/1_V2W7VMWYRneIBc2ZAb0kEKlw-TLDnwO/view?usp=drive_link |



### 2.2.3. Análisis de entrevistas

## Análisis para el segmento de Administradores
A partir de las entrevistas realizadas a Lucía, Jimmy y Silvia, se pudo ver que los tres tienen problemas parecidos al momento de manejar el inventario de sus minimarkets.
Uno de los problemas que más se repite es la **diferencia entre el stock registrado y el stock real**, ya que el **100 % de los entrevistados** mencionó que en algún momento las cantidades no coinciden. Esto puede pasar por errores al registrar productos, pérdidas, productos dañados o movimientos que no se anotan correctamente.
También se encontró que el **100 % controla las fechas de vencimiento de forma manual**, revisando los productos directamente en los estantes o en el almacén. Esto hace que algunos productos puedan pasar desapercibidos y terminar venciendo, sobre todo los lácteos, yogures, leche y panes.
Por otro lado, los tres entrevistados comentaron que tienen pérdidas por productos vencidos. Para tratar de evitarlo, suelen hacer descuentos, promociones u ofertas. Además, el **66,7 % mencionó que coloca estos productos en lugares más visibles**, como cerca de la caja, para que se vendan más rápido.
En cuanto a las herramientas que utilizan, se puede ver que combinan métodos como Excel, sistemas POS, registros manuales y WhatsApp. Sin embargo, todavía sienten que la información no siempre está actualizada o reunida en un solo lugar.
Respecto a una posible solución, el **100 % considera útil recibir alertas de productos próximos a vencer**. Además, el **66,7 % mostró interés en funciones como alertas de bajo stock, uso desde el celular y registro de productos mediante códigos de barras**.

## Análisis para el segmento de Empleados
A partir de las entrevistas realizadas a Joseph, Andrés y Pablo, se pudo identificar que los tres tienen dificultades con tareas relacionadas con el inventario y el almacén del minimarket.
Uno de los principales problemas es el **registro y control del stock**. El **66,7 % de los entrevistados** mencionó que las entradas y salidas se registran principalmente de forma manual, utilizando cuadernos o Excel. Aunque Andrés trabajaba con un sistema digital, también señaló que podían existir errores al momento de contar los productos.
Otro aspecto que se repite es que los errores suelen aparecer cuando existe mayor carga de trabajo. El **100 % mencionó que los problemas de inventario aumentan durante las horas con mayor cantidad de clientes o cuando llega mercadería**.
La revisión de las **fechas de vencimiento también se realiza manualmente en el 100 % de los casos**. Los trabajadores revisan directamente cada producto y, cuando detectan uno próximo a vencer, tratan de darle mayor prioridad en la venta.
En cuanto a la comunicación, los problemas relacionados con el stock suelen informarse de forma verbal, mediante registros escritos o por WhatsApp. Sin embargo, este proceso puede generar confusiones.
Respecto a una posible solución, el **66,7 % mencionó directamente que sería útil contar con una herramienta digital de gestión**. Entre las funciones más importantes se encuentran el **registro de entradas y salidas, consulta rápida del stock y alertas de productos próximos a vencer**.

## 2.3. Needfinding
### 2.3.1. User Personas

---
Administrador

![User Persona Administrador](recursos/imagenes/UserPersona-Administrador.jpg)

---
Empleado

![User Persona Empleado](recursos/imagenes/UserPersona-Empleado.jpg)

### 2.3.2. User Task Matrix
---
 Administradores

| Tareas identificadas | Frecuencia | Importancia | Evidencia / Justificación |
|---|---|---|---|
| Revisar el estado general del inventario | Alta | Alta | El administrador necesita conocer el stock disponible y detectar diferencias entre el inventario registrado y el real. |
| Supervisar productos próximos a vencer | Alta | Alta | Los productos perecibles pueden generar pérdidas si no se identifican y gestionan antes de su vencimiento. |
| Revisar alertas de stock y vencimientos | Alta | Alta | Permite detectar rápidamente productos con stock crítico, bajo nivel de existencias o próximos a caducar. |
| Consultar reportes e indicadores | Media | Alta | Los reportes ayudan a conocer mermas, movimientos y comportamiento del inventario para tomar mejores decisiones. |
| Aplicar promociones u ofertas | Media | Alta | Las ofertas permiten liquidar productos próximos a vencer o con baja rotación antes de que se conviertan en merma. |
| Revisar las operaciones realizadas por empleados | Alta | Media | El administrador necesita mantener control sobre ingresos, salidas y mermas registradas durante la jornada. |
| Gestionar productos y datos del inventario | Media | Alta | Es necesario registrar, editar y mantener actualizada la información de los productos disponibles. |
| Gestionar empleados y permisos | Baja | Media | El administrador debe controlar qué empleados tienen acceso al sistema y las acciones que pueden realizar según su rol. |
| Configurar parámetros de stock y vencimiento | Baja | Media | Permite adaptar las alertas y reglas de inventario a las necesidades particulares del minimarket. |
| Identificar productos con mayor cantidad de mermas | Media | Alta | Conocer qué productos generan más pérdidas facilita tomar decisiones sobre compras, rotación y promociones. |
---
 Empleados

| Tareas identificadas | Frecuencia | Importancia | Evidencia / Justificación |
|---|---|---|---|
| Registrar el ingreso de mercadería | Alta | Alta | La recepción de productos ocurre regularmente y debe registrarse para mantener actualizado el inventario. |
| Registrar salidas de productos | Alta | Alta | Las salidas modifican constantemente las cantidades disponibles y deben reflejarse correctamente en el stock. |
| Consultar el stock disponible | Alta | Alta | El empleado necesita conocer rápidamente cuántas unidades quedan sin realizar revisiones manuales del almacén. |
| Registrar productos dañados, vencidos o perdidos como merma | Media | Alta | Registrar las mermas permite mantener el stock real y conocer las pérdidas generadas durante la operación. |
| Revisar productos próximos a vencer | Alta | Alta | Permite detectar productos perecibles antes de que caduquen y comunicar la situación al administrador. |
| Consultar información de un producto | Alta | Media | Durante la jornada puede necesitar verificar cantidades, categoría, estado o información relacionada con un producto. |
| Actualizar el stock después de una operación | Alta | Alta | Mantener las cantidades actualizadas evita diferencias entre el inventario físico y el registrado en el sistema. |
| Revisar sus operaciones realizadas durante el día | Media | Media | El historial permite verificar que los ingresos, salidas y mermas hayan sido registrados correctamente. |
| Comunicar incidencias de inventario | Media | Alta | El empleado debe informar situaciones como stock crítico, productos dañados o inconsistencias encontradas durante su jornada. |
| Buscar productos dentro del inventario | Alta | Media | Una búsqueda rápida reduce el tiempo necesario para localizar información entre una gran cantidad de productos. |

### 2.3.3. User Journey Mapping

## Administrador

|  | Etapa 1 | Etapa 2 | Etapa 3 | Etapa 4 | Etapa 5 |
|---|---|---|---|---|---|
| **Title** | Supervisión inicial del negocio | Revisión del inventario | Detección de problemas | Toma de decisiones | Seguimiento de resultados |
| **User Goals** | Conocer el estado general del minimarket | Verificar stock y productos disponibles | Detectar stock crítico, mermas o vencimientos | Reducir pérdidas y mejorar la rotación | Comprobar si las acciones tomadas funcionaron |
| **Process** | Revisa ventas, stock y operaciones del día | Consulta cantidades y revisa productos | Identifica productos próximos a vencer o con poco stock | Aplica promociones, repone productos o toma acciones | Revisa reportes, movimientos y resultados |
| **Problems** | Información dispersa o poco actualizada | Diferencias entre stock registrado y real | Detección tardía de productos próximos a vencer | Falta de información para tomar decisiones rápidas | Dificultad para medir mermas y resultados |
| **Experience** | Expectativa | Atención | Preocupación | Decisión | Tranquilidad / Incertidumbre |
| **Ideas / Opportunities** | Dashboard con información resumida | Inventario actualizado y filtros | Alertas automáticas de stock y vencimiento | Recomendaciones y lanzamiento de ofertas | Reportes claros sobre inventario y mermas |

---

## Empleado

|  | Etapa 1 | Etapa 2 | Etapa 3 | Etapa 4 | Etapa 5 |
|---|---|---|---|---|---|
| **Title** | Inicio de la jornada | Recepción de mercadería | Actualización del inventario | Gestión de incidencias | Revisión de operaciones |
| **User Goals** | Conocer las tareas y estado del inventario | Registrar correctamente los productos recibidos | Mantener actualizado el stock durante el día | Registrar mermas y detectar productos próximos a vencer | Confirmar que sus operaciones fueron registradas correctamente |
| **Process** | Revisa productos, stock y pendientes | Recibe productos y verifica cantidades | Registra ingresos, salidas y consulta existencias | Informa o registra productos dañados, vencidos o faltantes | Consulta el historial de operaciones realizadas |
| **Problems** | Falta de información actualizada | Errores al registrar cantidades o lotes | Olvidar actualizar movimientos durante momentos de alta demanda | Dificultad para identificar vencimientos o comunicar incidencias | No saber si una operación fue registrada correctamente |
| **Experience** | Atención | Concentración | Presión | Preocupación | Alivio |
| **Ideas / Opportunities** | Dashboard simple con acciones rápidas | Registro sencillo de ingresos y lotes | Actualización rápida y automática del stock | Alertas y registro simplificado de mermas | Historial de operaciones fácil de consultar |

---

### 2.3.4. Empathy Mapping

## Administrador

![Empathy Map Administrador](recursos/imagenes/EmphathyMapping-Administrador.jpg)

## Empleado

![Empathy Map Empleado](recursos/imagenes/EmphathyMapping-Empleado.jpg)

## 2.4. Big Picture EventStorming

Nuestro equipo se enfocó en el dominio del negocio de los minimarkets, identificando los Domain Events más significativos a lo largo de la línea de tiempo operativo, desde que la mercadería ingresa al local hasta que es vendida o registrada como merma.
A continuación se identificaron los siguientes flujos principales a través de Domain Events.

![Big Picture EventStorming](recursos/imagenes/Bigpicture-eventstorming.png)

## 2.5. Ubiquitous Language

Para asegurar que entre los miembros del equipo y los stakeholders se comuniquen sin ambigüedades, se definieron los términos específicos correspondientes al Business Domain de BodeGo. Todos los términos tienen su nomenclatura en inglés.

- **Product:** Artículo físico que se comercializa en el minimarket. Contiene información general como nombre, código de barras y categoría.
- **Batch:** Conjunto de unidades de un mismo producto que ingresan al inventario en la misma fecha, también comparten la misma fecha de vencimiento.
- **Stock / Inventory:** Cantidad física actual disponible de un producto o lote específico dentro del minimarket.
- **Wastage:** Unidades de un producto que son retiradas del inventario, pudiendo ser por daño físico, vencimiento o robo.
- **Expiration Date:** Día límite establecido por el fabricante para el consumo seguro de un lote.
- **Threshold:** Límite preestablecido por el administrador que al ser sobrepasado, activa una alerta, como por ejemplo Stock mínimo o Días previos al vencimiento.
- **Inventory Movement:** Registro de auditoría que registra cualquier actualización en el Stock (Entrada, Salida, Ajuste o Merma).
- **Offer:** Descuento de precio aplicado a un lote específico que se encuentre próximo a su fecha de vencimiento para acelerar su rotación.
- **Role:** Conjunto de permisos asignados a un usuario, que puede ser Admin o Employee, que define a qué módulos y acciones tiene acceso dentro de BodeGo.

# Capítulo III: Requirements Specification

## 3.1. User Stories

## Épicas

| **EPIC-01** | **Presencia Digital y Landing Page** |
|-------------|---------------------------------------|
| **Descripción:** | **Como** visitante interesado en mejorar la gestión de un minimarket, **quiero** conocer la propuesta de valor, beneficios, funcionalidades y formas de acceder a BodeGo mediante una Landing Page informativa, **para** evaluar la solución y decidir si deseo utilizarla o solicitar más información. |

---

| **EPIC-02** | **Experiencia Frontend Web** |
|-------------|-------------------------------|
| **Descripción:** | **Como** administrador o empleado, **quiero** utilizar una aplicación web clara, accesible y adaptable a diferentes dispositivos, con navegación organizada, formularios comprensibles y opciones de idioma, **para** interactuar con las funcionalidades de BodeGo de forma sencilla y eficiente. |

---

| **EPIC-03** | **Gestión de Catálogo e Inventario (Inventory)** |
|-------------|------------------------------------------------|
| **Descripción:** | **Como** administrador o empleado autorizado, **quiero** consultar y gestionar productos, categorías, lotes y cantidades disponibles, **para** mantener actualizado el inventario y conocer las existencias del minimarket. |

---

| **EPIC-04** | **Gestión de Operaciones de Inventario (Operations)** |
|-------------|-------------------------------------------------------|
| **Descripción:** | **Como** administrador o empleado autorizado, **quiero** registrar y consultar movimientos, mermas y conteos físicos del inventario, **para** mantener la trazabilidad de las operaciones y detectar diferencias entre las existencias registradas y las verificadas. |

---

| **EPIC-05** | **Gestión de Compras y Ventas (Commercial)** |
|-------------|----------------------------------------------|
| **Descripción:** | **Como** administrador o empleado autorizado, **quiero** preparar, registrar, consultar y confirmar compras y ventas con sus respectivos productos y cantidades, **para** controlar las operaciones comerciales y reflejar correctamente sus efectos en el inventario. |

---

| **EPIC-06** | **Monitoreo y Alertas (Monitoring)** |
|-------------|---------------------------------------|
| **Descripción:** | **Como** administrador o empleado autorizado, **quiero** consultar alertas sobre situaciones relevantes del inventario y dar seguimiento a su atención, **para** identificar oportunamente condiciones que requieren intervención. |

---

| **EPIC-07** | **Reportes e Indicadores del Negocio (Reporting)** |
|-------------|-----------------------------------------------------|
| **Descripción:** | **Como** administrador, **quiero** consultar reportes e indicadores sobre productos, existencias y operaciones del negocio, **para** analizar su desempeño y respaldar la toma de decisiones. |

---

| **EPIC-08** | **Gestión de Identidad, Autenticación y Seguridad (IAM)** |
|-------------|----------------------------------------------------------|
| **Descripción:** | **Como** administrador o usuario registrado, **quiero** acceder al sistema de manera segura y contar con una gestión de usuarios, roles y permisos, **para** proteger la información del negocio y utilizar únicamente las funciones autorizadas. |

---

User Stories

| **Epic / Story ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con (Epic ID)** |
|---|---|---|---|---|
| US01 | Visualización de la propuesta de valor | **Como** visitante, **quiero** conocer la propuesta principal de BodeGo, **para** entender cómo mejora la gestión de un minimarket. | **Scenario:** Consultar propuesta<br><br>**Given** el visitante accede a la Landing Page.<br>**When** consulta la presentación principal.<br>**Then** encuentra la finalidad y los beneficios centrales de BodeGo.<br><br>**Scenario:** Identificar el producto<br><br>**Given** la presentación de BodeGo está disponible.<br>**When** el visitante revisa el contenido inicial.<br>**Then** puede identificar el nombre de la solución y el tipo de negocio al que se dirige. | EPIC-01 |
| US02 | Consulta de beneficios del producto | **Como** visitante, **quiero** identificar los beneficios de BodeGo, **para** evaluar su utilidad para mi negocio. | **Scenario:** Consultar beneficios<br><br>**Given** el visitante revisa la Landing Page.<br>**When** accede al contenido de beneficios.<br>**Then** encuentra información sobre control, reducción de pérdidas y eficiencia.<br><br>**Scenario:** Comparar beneficios<br><br>**Given** los beneficios están publicados.<br>**When** el visitante revisa sus descripciones.<br>**Then** comprende su relación con las necesidades de un minimarket. | EPIC-01 |
| US03 | Presentación informativa de funcionalidades | **Como** visitante, **quiero** conocer las funcionalidades de BodeGo, **para** comprender el alcance general del producto. | **Scenario:** Conocer módulos<br><br>**Given** el visitante consulta la sección de funcionalidades.<br>**When** revisa las descripciones.<br>**Then** identifica inventario, operaciones, monitoreo y reportes.<br><br>**Scenario:** Distinguir objetivos<br><br>**Given** las funcionalidades están publicadas.<br>**When** el visitante consulta cada explicación.<br>**Then** identifica la finalidad de cada módulo sin necesitar acceder a la aplicación. | EPIC-01 |
| US04 | Explicación de los pasos de uso de BodeGo | **Como** visitante, **quiero** conocer los pasos generales para utilizar BodeGo, **para** comprender el flujo básico de trabajo. | **Scenario:** Consultar pasos<br><br>**Given** el visitante accede a Cómo funciona.<br>**When** revisa la secuencia presentada.<br>**Then** identifica actividades de registro, control y análisis del negocio.<br><br>**Scenario:** Comprender secuencia<br><br>**Given** se muestran pasos ordenados.<br>**When** el visitante sigue la explicación.<br>**Then** comprende la relación entre los pasos sin consultar información técnica. | EPIC-01 |
| US05 | Formulario de contacto comercial | **Como** visitante interesado, **quiero** enviar mis datos de contacto, **para** solicitar información sobre BodeGo. | **Scenario:** Completar solicitud<br><br>**Given** el visitante dispone de un formulario de contacto.<br>**When** ingresa los campos obligatorios válidos.<br>**Then** puede preparar una solicitud de información.<br><br>**Scenario:** Evitar datos inválidos<br><br>**Given** la solicitud carece de un dato requerido o el correo no es válido.<br>**When** el visitante intenta enviarla.<br>**Then** se informa el error sin confirmar falsamente la recepción de la solicitud. | EPIC-01 |
| US06 | Visualización del Dashboard operativo | **Como** Administrador, **quiero** consultar indicadores resumidos del negocio, **para** supervisar las operaciones más relevantes. | **Scenario:** Consultar indicadores<br><br>**Given** existe información de negocio disponible.<br>**When** el Administrador accede al Dashboard.<br>**Then** obtiene indicadores y resúmenes consistentes con los datos disponibles.<br><br>**Scenario:** Mostrar ausencia de registros<br><br>**Given** no existen registros para un indicador.<br>**When** el Administrador consulta el Dashboard.<br>**Then** obtiene un resultado vacío o cero y no un valor inventado. | EPIC-02 |
| US07 | Navegación entre módulos autorizados | **Como** usuario autenticado, **quiero** navegar entre los módulos habilitados para mi rol, **para** acceder a mis tareas sin utilizar rutas ajenas. | **Scenario:** Acceder al módulo<br><br>**Given** la sesión del usuario es válida y tiene un permiso.<br>**When** selecciona un módulo autorizado.<br>**Then** puede acceder a sus funcionalidades.<br><br>**Scenario:** Proteger rutas<br><br>**Given** el usuario carece de permiso para una ruta.<br>**When** intenta ingresar directamente.<br>**Then** se deniega su acceso a la función protegida. | EPIC-02 |
| US08 | Consulta visual del inventario | **Como** Administrador o Empleado, **quiero** consultar el catálogo de productos, **para** revisar productos y existencias desde la aplicación. | **Scenario:** Listar productos<br><br>**Given** existen productos disponibles.<br>**When** el usuario consulta el inventario.<br>**Then** obtiene una lista con los datos recibidos del servicio.<br><br>**Scenario:** Inventario vacío<br><br>**Given** el catálogo no contiene productos.<br>**When** el usuario consulta el inventario.<br>**Then** se informa la ausencia de registros sin generar productos ficticios. | EPIC-02 |
| US09 | Consulta visual del detalle de producto | **Como** Administrador o Empleado, **quiero** revisar la información de un producto específico, **para** conocer su categoría, precio y existencias. | **Scenario:** Abrir detalle<br><br>**Given** el producto existe.<br>**When** el usuario solicita su información.<br>**Then** la aplicación presenta los datos correspondientes a ese identificador.<br><br>**Scenario:** Producto inexistente<br><br>**Given** el producto solicitado no está registrado.<br>**When** el usuario intenta consultarlo.<br>**Then** se informa que el recurso no está disponible. | EPIC-02 |
| US10 | Consulta visual de operaciones de inventario | **Como** Administrador o Empleado autorizado, **quiero** consultar operaciones y movimientos, **para** revisar el historial del inventario. | **Scenario:** Consultar operaciones<br><br>**Given** existen movimientos registrados.<br>**When** el usuario consulta el módulo de operaciones.<br>**Then** obtiene tipos, cantidades, fechas y referencias disponibles.<br><br>**Scenario:** Sin movimientos<br><br>**Given** no hay movimientos registrados.<br>**When** el usuario abre el historial.<br>**Then** se muestra un estado sin datos sin inventar operaciones. | EPIC-02 |
| US11 | Búsqueda y filtrado de productos | **Como** Administrador o Empleado, **quiero** buscar productos por criterios disponibles, **para** encontrar mercadería de forma rápida. | **Scenario:** Encontrar coincidencias<br><br>**Given** existen productos en el catálogo.<br>**When** el usuario ingresa un criterio de búsqueda.<br>**Then** la lista contiene solo resultados que cumplen el criterio.<br><br>**Scenario:** No encontrar coincidencias<br><br>**Given** no existe un producto que cumpla el filtro.<br>**When** el usuario ejecuta la búsqueda.<br>**Then** se informa que no hay resultados. | EPIC-02 |
| US12 | Visualización de alertas de inventario | **Como** Administrador, **quiero** consultar las alertas registradas, **para** identificar situaciones que requieren revisión. | **Scenario:** Consultar alertas<br><br>**Given** existen alertas persistidas.<br>**When** el Administrador accede al módulo de monitoreo.<br>**Then** obtiene las alertas disponibles y su estado.<br><br>**Scenario:** Consulta vacía<br><br>**Given** no se encuentran alertas guardadas.<br>**When** el Administrador consulta el módulo.<br>**Then** recibe una lista vacía y no alertas generadas artificialmente. | EPIC-02 |
| US13 | Visualización de reportes operativos | **Como** Administrador, **quiero** consultar los reportes disponibles, **para** evaluar la evolución del negocio. | **Scenario:** Consultar resumen<br><br>**Given** existen datos de compras o ventas aplicables.<br>**When** el Administrador solicita un reporte.<br>**Then** observa resultados basados en los registros disponibles.<br><br>**Scenario:** Consultar sin actividad<br><br>**Given** no existen operaciones confirmadas para el rango solicitado.<br>**When** el Administrador consulta el reporte.<br>**Then** se indican valores cero o listas vacías. | EPIC-02 |
| US14 | Registro visual de productos con validaciones | **Como** Administrador, **quiero** registrar productos desde formularios, **para** mantener organizado el catálogo. | **Scenario:** Registrar producto<br><br>**Given** se proporcionan nombre, categoría, precio y stock mínimo válidos.<br>**When** el Administrador confirma el registro.<br>**Then** la aplicación envía la solicitud y presenta el resultado del servicio.<br><br>**Scenario:** Validar formulario<br><br>**Given** falta un dato requerido o contiene un valor inválido.<br>**When** el Administrador intenta guardar.<br>**Then** la aplicación explica el error y no confirma un registro inexistente. | EPIC-02 |
| US15 | Consulta visual de documentos comerciales | **Como** Administrador o Empleado autorizado, **quiero** revisar compras y ventas en la aplicación, **para** conocer el estado e importe de los documentos. | **Scenario:** Consultar documentos<br><br>**Given** existen compras o ventas registradas.<br>**When** el usuario abre su historial.<br>**Then** obtiene los documentos disponibles con sus estados.<br><br>**Scenario:** Abrir un documento<br><br>**Given** existe un documento comercial.<br>**When** el usuario solicita su detalle.<br>**Then** puede consultar sus artículos, totales y estado de confirmación. | EPIC-02 |
| US16 | Registro de productos en catálogo | **Como** Administrador, **quiero** registrar productos con su categoría y datos de venta, **para** mantener actualizado el catálogo de mercadería. | **Scenario:** Registrar producto válido<br><br>**Given** existe una categoría válida y los datos cumplen las reglas.<br>**When** el Administrador registra el producto.<br>**Then** el sistema crea un producto con identificador y existencias iniciales definidas por el negocio.<br><br>**Scenario:** Rechazar categoría inexistente<br><br>**Given** la categoría solicitada no existe.<br>**When** se intenta registrar el producto.<br>**Then** el registro es rechazado y no se crea el recurso. | EPIC-03 |
| US17 | Actualización de información del producto | **Como** Administrador, **quiero** modificar los datos editables de un producto existente, **para** corregir errores del catálogo. | **Scenario:** Actualizar producto<br><br>**Given** el producto existe y los nuevos valores son válidos.<br>**When** el Administrador solicita modificarlo.<br>**Then** el sistema conserva el identificador y refleja los cambios permitidos.<br><br>**Scenario:** Rechazar actualización inválida<br><br>**Given** el producto no existe o un dato no cumple las reglas.<br>**When** se solicita la actualización.<br>**Then** el sistema rechaza la operación sin alterar el catálogo. | EPIC-03 |
| US18 | Clasificación de productos por categorías | **Como** Administrador, **quiero** asociar productos con categorías registradas, **para** organizar la mercadería por tipo. | **Scenario:** Clasificar producto<br><br>**Given** la categoría indicada existe.<br>**When** se registra un producto que la referencia.<br>**Then** el producto queda asociado a la categoría válida.<br><br>**Scenario:** Evitar categoría ausente<br><br>**Given** el identificador de categoría no existe.<br>**When** se intenta registrar una asociación.<br>**Then** el sistema rechaza la relación. | EPIC-03 |
| US19 | Consulta de productos con stock bajo | **Como** Administrador, **quiero** consultar los productos cuya existencia es inferior al mínimo configurado, **para** identificar necesidades de reposición. | **Scenario:** Identificar productos bajo el mínimo<br><br>**Given** existen productos cuya cantidad está por debajo del stock mínimo.<br>**When** el Administrador consulta el catálogo de productos con bajo stock.<br>**Then** el servicio devuelve los productos que cumplen esa condición.<br><br>**Scenario:** Sin productos críticos<br><br>**Given** todos los productos cumplen sus mínimos configurados.<br>**When** el Administrador solicita el listado de productos con bajo stock.<br>**Then** el servicio devuelve una colección vacía. | EPIC-03 |
| US20 | Consulta de lotes asociados a productos | **Como** Administrador o Empleado, **quiero** consultar lotes de un producto, **para** conocer cantidades y vencimientos disponibles. | **Scenario:** Consultar lotes<br><br>**Given** el producto existe y tiene lotes.<br>**When** el usuario solicita los lotes asociados.<br>**Then** obtiene identificadores, cantidades y vencimientos registrados.<br><br>**Scenario:** Producto sin lotes<br><br>**Given** el producto existe y no tiene lotes.<br>**When** el usuario consulta sus lotes.<br>**Then** obtiene una colección vacía. | EPIC-03 |
| US21 | Consulta de stock actual de productos | **Como** Administrador o Empleado, **quiero** consultar existencias vigentes, **para** conocer disponibilidad para compras y ventas. | **Scenario:** Consultar stock<br><br>**Given** el producto existe.<br>**When** el usuario revisa las existencias.<br>**Then** obtiene la cantidad actual registrada.<br><br>**Scenario:** Consultar sin stock<br><br>**Given** el producto existe sin unidades disponibles.<br>**When** el usuario consulta la cantidad.<br>**Then** recibe cero sin valores negativos. | EPIC-03 |
| US22 | Consistencia del inventario ante confirmaciones comerciales | **Como** Administrador, **quiero** que las confirmaciones de compras y ventas mantengan consistentes las existencias, **para** evitar modificaciones parciales o duplicadas del inventario. | **Scenario:** Conservar cambios de una confirmación válida<br><br>**Given** una operación comercial está en borrador y cumple las reglas.<br>**When** el sistema confirma el documento.<br>**Then** el inventario refleja una sola vez los movimientos correspondientes a esa operación.<br><br>**Scenario:** Evitar cambios al fallar<br><br>**Given** la confirmación comercial no cumple una validación o falla antes de completarse.<br>**When** el sistema rechaza la confirmación.<br>**Then** las existencias no reflejan cambios parciales originados por el documento rechazado. | EPIC-03 |
| US23 | Trazabilidad de salidas originadas en ventas | **Como** Administrador o Empleado autorizado, **quiero** identificar los movimientos de salida originados por una venta confirmada, **para** rastrear su efecto sobre el inventario. | **Scenario:** Identificar salida por venta<br><br>**Given** una venta se confirma y genera movimientos de inventario.<br>**When** el usuario consulta el historial de movimientos.<br>**Then** puede identificar las salidas y la referencia de la venta que las originó.<br><br>**Scenario:** No registrar salida por borrador<br><br>**Given** una venta permanece en borrador.<br>**When** el usuario revisa los movimientos de inventario.<br>**Then** no encuentra salidas generadas por ese borrador. | EPIC-04 |
| US24 | Validación del stock disponible para ventas | **Como** Empleado autorizado, **quiero** evitar confirmar ventas sin unidades suficientes, **para** prevenir existencias negativas. | **Scenario:** Aceptar venta disponible<br><br>**Given** hay stock suficiente para todas las líneas de venta.<br>**When** se solicita confirmar la venta.<br>**Then** la operación se completa respetando el stock disponible.<br><br>**Scenario:** Rechazar venta excesiva<br><br>**Given** la suma requerida supera la disponibilidad.<br>**When** se intenta confirmar la venta.<br>**Then** se rechaza toda la confirmación sin descuento parcial. | EPIC-03 |
| US25 | Consulta de conteos físicos por identificador | **Como** Administrador o Empleado autorizado, **quiero** consultar un conteo físico registrado mediante su identificador, **para** verificar las cantidades declaradas y las diferencias documentadas. | **Scenario:** Consultar conteo existente<br><br>**Given** existe un conteo físico registrado con un identificador válido.<br>**When** el usuario solicita el detalle del conteo.<br>**Then** el sistema muestra el registro y los artículos con sus cantidades contadas.<br><br>**Scenario:** Conteo inexistente<br><br>**Given** el identificador solicitado no corresponde a un conteo.<br>**When** el usuario intenta consultar su detalle.<br>**Then** el servicio informa que el conteo no existe. | EPIC-04 |
| US26 | Consulta del historial de movimientos de inventario | **Como** Administrador o Empleado autorizado, **quiero** consultar movimientos registrados, **para** identificar el origen de los cambios de stock. | **Scenario:** Consultar historial<br><br>**Given** existen movimientos persistidos.<br>**When** el usuario consulta los movimientos.<br>**Then** obtiene fecha, cantidad con signo y origen.<br><br>**Scenario:** Historial vacío<br><br>**Given** no existen movimientos.<br>**When** el usuario realiza la consulta.<br>**Then** obtiene una colección vacía. | EPIC-04 |
| US27 | Consulta de productos próximos a vencer | **Como** Administrador, **quiero** identificar lotes con fechas cercanas de vencimiento, **para** planificar acciones oportunas. | **Scenario:** Identificar lotes próximos<br><br>**Given** existen lotes con vencimiento registrado dentro del período elegido.<br>**When** se consulta la información de vencimientos.<br>**Then** pueden identificarse los lotes que requieren atención.<br><br>**Scenario:** Sin lotes próximos<br><br>**Given** no existen lotes dentro del período elegido.<br>**When** se consulta la información.<br>**Then** se informa que no hay coincidencias. | EPIC-03 |
| US28 | Asignación FIFO de existencias en ventas sin lote explícito | **Como** Empleado autorizado, **quiero** que las ventas sin lote específico consuman existencias en orden de ingreso, **para** mantener reglas de retiro consistentes. | **Scenario:** Distribuir por ingreso<br><br>**Given** una venta contiene un producto con varios lotes disponibles.<br>**When** se confirma sin indicar lote.<br>**Then** se priorizan los lotes por fecha de ingreso de acuerdo con la regla FIFO.<br><br>**Scenario:** Respetar lote explícito<br><br>**Given** una línea de venta señala un lote válido.<br>**When** se confirma la operación.<br>**Then** la cantidad se descuenta del lote indicado. | EPIC-03 |
| US29 | Registro de conteo físico de inventario | **Como** Empleado autorizado, **quiero** registrar cantidades contadas físicamente, **para** documentar diferencias con las existencias del sistema. | **Scenario:** Registrar conteo<br><br>**Given** el usuario tiene permiso y aporta un conteo válido.<br>**When** registra el conteo.<br>**Then** se almacena la cantidad física y la referencia del producto.<br><br>**Scenario:** Consultar conteo<br><br>**Given** el conteo fue registrado correctamente.<br>**When** el usuario solicita su identificador.<br>**Then** obtiene la información guardada. | EPIC-04 |
| US30 | Trazabilidad por producto, lote y operación | **Como** Administrador, **quiero** relacionar movimientos con productos, lotes y documentos de origen, **para** investigar cambios de stock. | **Scenario:** Consultar vínculo<br><br>**Given** existe un movimiento registrado.<br>**When** el Administrador revisa su referencia.<br>**Then** puede identificar el producto, lote y operación de origen cuando corresponda.<br><br>**Scenario:** Distinguir movimientos<br><br>**Given** existen movimientos originados en compras y ventas.<br>**When** se consulta el historial.<br>**Then** se identifica el tipo y origen sin mezclar registros. | EPIC-04 |
| US31 | Registro de mermas de inventario | **Como** Empleado autorizado, **quiero** registrar unidades dañadas o vencidas, **para** mantener el inventario acorde con las pérdidas. | **Scenario:** Registrar merma<br><br>**Given** hay disponibilidad y se indica una cantidad válida.<br>**When** se registra la merma.<br>**Then** se conserva el motivo y se actualiza el stock según la operación.<br><br>**Scenario:** Rechazar merma inválida<br><br>**Given** la cantidad es inválida o supera el stock.<br>**When** se solicita la merma.<br>**Then** se rechaza sin dejar existencias negativas. | EPIC-04 |
| US32 | Clasificación de causas de merma | **Como** Empleado autorizado, **quiero** indicar el motivo de una merma, **para** analizar las causas de pérdidas. | **Scenario:** Clasificar registro<br><br>**Given** la merma se registra con un motivo permitido.<br>**When** el sistema procesa la operación.<br>**Then** el motivo queda asociado al registro.<br><br>**Scenario:** Rechazar motivo<br><br>**Given** el motivo no pertenece al conjunto permitido.<br>**When** se intenta registrar la merma.<br>**Then** se informa la validación correspondiente. | EPIC-04 |
| US33 | Filtrado de alertas por tipo y estado | **Como** Administrador, **quiero** filtrar las alertas por tipo, estado o producto, **para** identificar rápidamente las situaciones que requieren atención. | **Scenario:** Filtrar alertas<br><br>**Given** existen alertas registradas con distintos tipos y estados.<br>**When** el Administrador selecciona filtros en el módulo de monitoreo.<br>**Then** la lista muestra solo las alertas que cumplen los criterios elegidos.<br><br>**Scenario:** Sin coincidencias<br><br>**Given** no existe una alerta que coincida con los filtros seleccionados.<br>**When** el Administrador aplica la búsqueda.<br>**Then** la interfaz informa que no hay coincidencias sin generar alertas nuevas. | EPIC-06 |
| US34 | Generación automática de alertas por stock bajo | **Como** Administrador, **quiero** recibir alertas generadas al detectar bajo stock, **para** atender oportunamente una situación de inventario. | **Scenario:** Generar alerta<br><br>**Given** la existencia de un producto cae bajo el umbral definido.<br>**When** se evalúa la condición de stock.<br>**Then** se registra una alerta identificable.<br><br>**Scenario:** Evitar duplicados<br><br>**Given** ya existe una alerta pendiente por la misma condición.<br>**When** la regla vuelve a evaluarse.<br>**Then** no se genera un aviso duplicado. | EPIC-06 |
| US35 | Consulta de alertas registradas | **Como** Administrador, **quiero** consultar las alertas persistidas en el sistema, **para** identificar los casos que requieren revisión. | **Scenario:** Listar alertas<br><br>**Given** existen alertas guardadas.<br>**When** el Administrador consulta el servicio.<br>**Then** recibe la colección de alertas y sus estados.<br><br>**Scenario:** Consultar identificador inválido<br><br>**Given** el identificador no corresponde a una alerta registrada.<br>**When** se consulta esa alerta.<br>**Then** el servicio informa que no existe el recurso. | EPIC-06 |
| US36 | Seguimiento de alertas de vencimiento | **Como** Administrador, **quiero** identificar las alertas de vencimiento asociadas a lotes, **para** revisar oportunamente la mercadería perecible que requiere atención. | **Scenario:** Consultar alertas de vencimiento<br><br>**Given** existen alertas registradas de tipo vencimiento con lote asociado.<br>**When** el Administrador filtra las alertas por ese tipo.<br>**Then** visualiza las alertas correspondientes a lotes que requieren revisión.<br><br>**Scenario:** Sin alertas de vencimiento<br><br>**Given** no hay alertas guardadas de ese tipo.<br>**When** el Administrador revisa el listado filtrado.<br>**Then** la interfaz muestra un estado sin resultados. | EPIC-06 |
| US37 | Consulta de mermas registradas | **Como** Administrador, **quiero** consultar el historial de mermas, **para** conocer pérdidas documentadas. | **Scenario:** Consultar pérdidas<br><br>**Given** se han registrado mermas.<br>**When** el Administrador consulta el historial.<br>**Then** obtiene cantidades y motivos disponibles.<br><br>**Scenario:** Sin pérdidas<br><br>**Given** no hay mermas registradas.<br>**When** el Administrador consulta el historial.<br>**Then** el resultado indica que no existen registros. | EPIC-04 |
| US38 | Consulta del resumen de ventas | **Como** Administrador, **quiero** conocer el número e importe de ventas confirmadas, **para** evaluar la actividad comercial. | **Scenario:** Consultar resumen<br><br>**Given** existen ventas confirmadas en el intervalo solicitado.<br>**When** el Administrador consulta el resumen.<br>**Then** obtiene cantidad e importe calculados a partir de esas ventas.<br><br>**Scenario:** Sin ventas confirmadas<br><br>**Given** no existen ventas confirmadas dentro del intervalo.<br>**When** se solicita el resumen.<br>**Then** se reportan ceros. | EPIC-07 |
| US39 | Dashboard con indicadores de actividad comercial | **Como** Administrador, **quiero** ver indicadores relevantes sobre operaciones comerciales, **para** tomar decisiones informadas. | **Scenario:** Mostrar resumen comercial<br><br>**Given** existen reportes disponibles.<br>**When** el Administrador consulta sus indicadores.<br>**Then** observa datos consistentes con los resultados del servicio.<br><br>**Scenario:** Sin actividad<br><br>**Given** no existen ventas confirmadas.<br>**When** el Administrador abre el Dashboard.<br>**Then** los indicadores reflejan el resultado cero. | EPIC-07 |
| US40 | Consulta de productos más vendidos | **Como** Administrador, **quiero** identificar productos con mayor cantidad vendida, **para** reconocer tendencias de consumo. | **Scenario:** Consultar ranking<br><br>**Given** existen ventas confirmadas de varios productos.<br>**When** el Administrador consulta el reporte.<br>**Then** obtiene productos ordenados por cantidad vendida.<br><br>**Scenario:** Validar límite<br><br>**Given** se solicita una cantidad de resultados fuera del rango permitido.<br>**When** el servicio recibe la consulta.<br>**Then** rechaza el parámetro inválido. | EPIC-07 |
| US41 | Registro de compras en borrador | **Como** Empleado autorizado, **quiero** registrar una compra con sus líneas y costos, **para** preparar la recepción de mercadería. | **Scenario:** Crear compra<br><br>**Given** el usuario tiene permiso y los artículos son válidos.<br>**When** registra el documento de compra.<br>**Then** se crea una compra en estado borrador con su total.<br><br>**Scenario:** No alterar stock<br><br>**Given** se registra una compra en borrador.<br>**When** se consulta el inventario antes de confirmarla.<br>**Then** las existencias no cambian por ese borrador. | EPIC-05 |
| US42 | Registro de ventas en borrador | **Como** Empleado autorizado, **quiero** registrar una venta con productos y precios, **para** preparar una operación comercial. | **Scenario:** Crear venta<br><br>**Given** el usuario proporciona productos, cantidades e importes válidos.<br>**When** registra la venta.<br>**Then** se guarda un documento en borrador con sus detalles.<br><br>**Scenario:** No descontar anticipadamente<br><br>**Given** una venta todavía no fue confirmada.<br>**When** se consulta la disponibilidad.<br>**Then** las existencias permanecen sin cambios por esa venta. | EPIC-05 |
| US43 | Confirmación de compras de mercadería | **Como** Empleado autorizado, **quiero** confirmar una compra registrada, **para** ingresar las unidades recibidas al inventario. | **Scenario:** Confirmar compra<br><br>**Given** existe una compra en borrador válida.<br>**When** el usuario la confirma.<br>**Then** se marca como confirmada y se generan los movimientos de ingreso.<br><br>**Scenario:** Evitar doble confirmación<br><br>**Given** una compra ya está confirmada.<br>**When** se intenta confirmarla nuevamente.<br>**Then** no se duplica el movimiento ni las unidades. | EPIC-05 |
| US44 | Confirmación de ventas con salida de inventario | **Como** Empleado autorizado, **quiero** confirmar una venta válida, **para** registrar la venta y descontar mercadería. | **Scenario:** Confirmar venta<br><br>**Given** la venta en borrador dispone de stock suficiente.<br>**When** se confirma la venta.<br>**Then** queda confirmada y se registran salidas de inventario.<br><br>**Scenario:** Evitar stock negativo<br><br>**Given** la venta requiere más unidades de las disponibles.<br>**When** se solicita la confirmación.<br>**Then** se rechaza la operación completa. | EPIC-05 |
| US45 | Consulta del historial y detalle comercial | **Como** Administrador o Empleado autorizado, **quiero** consultar compras y ventas existentes, **para** revisar sus importes, productos y estados. | **Scenario:** Listar documentos<br><br>**Given** existen documentos comerciales.<br>**When** el usuario consulta compras o ventas.<br>**Then** obtiene las colecciones disponibles.<br><br>**Scenario:** Obtener detalle<br><br>**Given** el identificador de documento existe.<br>**When** el usuario solicita ese documento.<br>**Then** obtiene sus artículos, total y estado. | EPIC-05 |
| US46 | Registro de usuarios del sistema | **Como** Administrador, **quiero** crear usuarios autorizados, **para** asignar acceso controlado a BodeGo. | **Scenario:** Registrar usuario<br><br>**Given** los datos del nuevo usuario cumplen las reglas y el rol existe.<br>**When** el Administrador registra la cuenta.<br>**Then** el usuario queda creado con el rol asignado.<br><br>**Scenario:** Rechazar correo duplicado<br><br>**Given** el correo ya corresponde a una cuenta.<br>**When** se intenta registrar otra cuenta.<br>**Then** el sistema rechaza la duplicación. | EPIC-08 |
| US47 | Consulta de roles y permisos | **Como** Administrador, **quiero** consultar los roles del sistema, **para** administrar responsabilidades de acceso. | **Scenario:** Consultar roles<br><br>**Given** los roles están configurados.<br>**When** el Administrador solicita la lista.<br>**Then** obtiene los roles existentes.<br><br>**Scenario:** Denegar acceso indebido<br><br>**Given** una persona no posee el rol requerido.<br>**When** intenta realizar una operación administrativa protegida.<br>**Then** el servicio deniega la operación. | EPIC-08 |
| US48 | Inicio de sesión con credenciales | **Como** usuario registrado, **quiero** autenticarme mediante correo y contraseña, **para** acceder a las funciones autorizadas. | **Scenario:** Autenticar usuario válido<br><br>**Given** la cuenta está activa y las credenciales son correctas.<br>**When** se solicita iniciar sesión.<br>**Then** el servicio devuelve una credencial de acceso y el usuario correspondiente.<br><br>**Scenario:** Rechazar credenciales<br><br>**Given** las credenciales no son válidas.<br>**When** se solicita iniciar sesión.<br>**Then** el servicio no autoriza el ingreso. | EPIC-08 |
| US49 | Consulta del usuario autenticado | **Como** usuario autenticado, **quiero** consultar mi identidad y rol actual, **para** comprobar los permisos de mi sesión. | **Scenario:** Consultar perfil<br><br>**Given** la sesión tiene un token válido.<br>**When** el usuario solicita su información.<br>**Then** el servicio devuelve su identificador, nombre y rol.<br><br>**Scenario:** Token inválido<br><br>**Given** no existe una credencial válida.<br>**When** se solicita el perfil autenticado.<br>**Then** el acceso se rechaza. | EPIC-08 |
| US50 | Cierre de sesión del Frontend | **Como** usuario autenticado, **quiero** cerrar mi sesión de trabajo, **para** evitar que otros continúen utilizando mi acceso. | **Scenario:** Cerrar sesión<br><br>**Given** el usuario mantiene una sesión activa.<br>**When** solicita salir.<br>**Then** la aplicación elimina su estado autenticado y vuelve al acceso.<br><br>**Scenario:** Bloquear navegación<br><br>**Given** la sesión fue cerrada.<br>**When** se solicita una ruta protegida.<br>**Then** la aplicación exige autenticación nuevamente. | EPIC-08 |
| US51 | Galería visual de pantallas de BodeGo | **Como** visitante, **quiero** consultar vistas representativas de la aplicación, **para** conocer cómo se presentan sus módulos principales. | **Scenario:** Consultar galería<br><br>**Given** las capturas de la plataforma están publicadas.<br>**When** el visitante consulta la presentación visual.<br>**Then** encuentra imágenes asociadas a descripciones de los módulos.<br><br>**Scenario:** Consultar en móvil<br><br>**Given** el visitante dispone de un dispositivo de pantalla pequeña.<br>**When** revisa la galería.<br>**Then** puede comprender las imágenes y descripciones sin perder información esencial. | EPIC-01 |
| US52 | Presentación de roles Administrador y Empleado | **Como** visitante, **quiero** conocer las responsabilidades de cada tipo de usuario, **para** evaluar cómo se adapta BodeGo al personal del minimarket. | **Scenario:** Consultar rol administrador<br><br>**Given** la información de roles está disponible.<br>**When** el visitante revisa las capacidades del Administrador.<br>**Then** comprende sus responsabilidades generales.<br><br>**Scenario:** Consultar rol empleado<br><br>**Given** la información de roles está disponible.<br>**When** el visitante consulta el perfil Empleado.<br>**Then** comprende las tareas operativas permitidas y sus límites. | EPIC-01 |
| US53 | Consulta de plan y precio comercial | **Como** visitante interesado, **quiero** conocer el precio y las funcionalidades incluidas en BodeGo, **para** evaluar la contratación del producto. | **Scenario:** Consultar precio<br><br>**Given** la oferta comercial está publicada.<br>**When** el visitante consulta el apartado de precio.<br>**Then** obtiene el monto y las funcionalidades que se ofrecen.<br><br>**Scenario:** Solicitar información<br><br>**Given** el visitante desea conocer condiciones comerciales.<br>**When** sigue la opción de contacto asociada al plan.<br>**Then** puede acceder a la solicitud de información. | EPIC-01 |
| US54 | Cambio de idioma español/inglés en el Frontend | **Como** usuario de BodeGo, **quiero** cambiar el idioma de la interfaz entre inglés y español, **para** utilizar los módulos y formularios en el idioma de mi preferencia. | **Scenario:** Cambiar idioma durante la navegación<br><br>**Given** el usuario tiene la aplicación abierta en uno de los idiomas admitidos.<br>**When** utiliza el selector para alternar entre inglés y español.<br>**Then** los textos traducibles cambian sin perder la pantalla activa.<br><br>**Scenario:** Mantener idioma preferido<br><br>**Given** el usuario seleccionó un idioma admitido.<br>**When** navega entre módulos o recarga la página.<br>**Then** la aplicación conserva la preferencia si el almacenamiento está disponible. | EPIC-02 |
| US55 | Preparación de compras con carrito de productos | **Como** Empleado autorizado, **quiero** armar una compra con varias líneas, **para** evitar registrar artículos uno por uno. | **Scenario:** Agregar líneas<br><br>**Given** existen productos elegibles.<br>**When** el usuario agrega artículos, cantidades y costos.<br>**Then** la compra calcula subtotales y el total de sus líneas.<br><br>**Scenario:** Validar artículos<br><br>**Given** alguna línea tiene cantidad o costo inválidos.<br>**When** el usuario intenta guardar.<br>**Then** se informa qué dato debe corregirse. | EPIC-02 |
| US56 | Preparación de ventas con disponibilidad visible | **Como** Empleado autorizado, **quiero** armar una venta consultando existencias, **para** evitar ofrecer unidades no disponibles. | **Scenario:** Armar venta<br><br>**Given** existen productos con stock disponible.<br>**When** el usuario agrega artículos y cantidades.<br>**Then** la aplicación muestra cantidades y subtotal de la operación.<br><br>**Scenario:** Prevenir exceso<br><br>**Given** la cantidad pedida supera el stock mostrado.<br>**When** el usuario intenta continuar.<br>**Then** la aplicación advierte la disponibilidad insuficiente. | EPIC-02 |
| US57 | Estados de confirmación y resultado de compras y ventas | **Como** Empleado autorizado, **quiero** conocer si un documento fue registrado o confirmado, **para** evitar repetir operaciones por incertidumbre. | **Scenario:** Confirmar documento<br><br>**Given** un documento comercial válido está en borrador.<br>**When** el usuario solicita su confirmación.<br>**Then** se informa el resultado obtenido del servicio.<br><br>**Scenario:** Evitar doble envío<br><br>**Given** hay una confirmación en curso.<br>**When** el usuario vuelve a intentar la operación.<br>**Then** la aplicación evita envíos simultáneos repetidos. | EPIC-02 |
| US58 | Presentación de estados vacíos, carga y error de servicios | **Como** usuario de BodeGo, **quiero** recibir información clara al consultar módulos, **para** distinguir datos vacíos de fallas de conexión. | **Scenario:** Respuesta vacía<br><br>**Given** el servicio responde correctamente sin registros.<br>**When** el usuario consulta el módulo.<br>**Then** se presenta un estado sin datos.<br><br>**Scenario:** Falla de consulta<br><br>**Given** el servicio devuelve un error o no responde.<br>**When** el usuario abre el módulo.<br>**Then** la aplicación informa la falla sin inventar registros. | EPIC-02 |
| US59 | Previsualización de stock antes de operaciones | **Como** Empleado autorizado, **quiero** revisar el stock consultado y la variación propuesta, **para** confirmar cantidades con mayor seguridad. | **Scenario:** Consultar disponibilidad<br><br>**Given** un producto está registrado con existencias.<br>**When** el usuario prepara una operación.<br>**Then** observa el stock de referencia y la variación prevista.<br><br>**Scenario:** Cambiar producto<br><br>**Given** el usuario reemplaza el artículo de la operación.<br>**When** consulta nuevamente la disponibilidad.<br>**Then** la aplicación actualiza la referencia asociada al producto seleccionado. | EPIC-02 |
| US60 | Protección frente a resultados inciertos de operaciones | **Como** usuario de BodeGo, **quiero** conocer si una operación quedó pendiente de confirmación, **para** evitar duplicar solicitudes cuando se pierde la conexión. | **Scenario:** Solicitud incierta<br><br>**Given** una solicitud de escritura no confirma su resultado.<br>**When** la aplicación detecta que no puede determinar el estado.<br>**Then** mantiene el seguimiento de la operación pendiente sin reenviar automáticamente.<br><br>**Scenario:** Cambio de contexto<br><br>**Given** hay un registro pendiente asociado a una sesión.<br>**When** el usuario cambia de identidad o vuelve a ingresar.<br>**Then** la aplicación no atribuye la solicitud anterior al nuevo usuario. | EPIC-02 |

---

Technical Stories

| **Technical Stories ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con (Epic ID)** |
|---|---|---|---|---|
| TS01 | Gestión REST de productos | **Como** Developer, **quiero** exponer recursos REST de registro y consulta de productos en ASP.NET Core, **para** proporcionar información consistente del catálogo al Frontend Web de BodeGo. | **Scenario:** Registrar un producto<br><br>**Given** existe una categoría válida y se proporcionan los datos obligatorios del producto.<br>**When** la API procesa `POST /api/v1/products`.<br>**Then** registra el producto y devuelve código `201` con su información.<br><br>**Scenario:** Consultar el catálogo<br><br>**Given** existen productos registrados.<br>**When** la API procesa `GET /api/v1/products`.<br>**Then** devuelve código `200` y la colección de productos.<br><br>**Scenario:** Consultar un producto inexistente<br><br>**Given** el identificador solicitado no corresponde a un producto.<br>**When** la API procesa `GET /api/v1/products/{id}`.<br>**Then** devuelve código `404` sin crear ni modificar recursos. | EPIC-03 |
| TS02 | Gestión REST de categorías | **Como** Developer, **quiero** publicar servicios REST para registrar y consultar categorías, **para** organizar los productos de BodeGo dentro del contexto Inventory. | **Scenario:** Registrar categoría válida<br><br>**Given** el nombre y los datos de la categoría cumplen las reglas de negocio.<br>**When** la API recibe `POST /api/v1/categories`.<br>**Then** crea la categoría y responde con código `201`.<br><br>**Scenario:** Consultar categorías<br><br>**Given** existen categorías almacenadas.<br>**When** la API recibe `GET /api/v1/categories`.<br>**Then** devuelve código `200` con las categorías registradas.<br><br>**Scenario:** Evitar una categoría duplicada<br><br>**Given** ya existe una categoría con el nombre que se intenta registrar.<br>**When** la API recibe otra solicitud `POST /api/v1/categories` con ese nombre.<br>**Then** responde con código `409` sin duplicar el registro. | EPIC-03 |
| TS03 | Consultas REST de lotes y productos con stock bajo | **Como** Developer, **quiero** exponer consultas de lotes por producto y de productos con existencias críticas, **para** apoyar el seguimiento de la disponibilidad y los vencimientos. | **Scenario:** Consultar lotes de un producto<br><br>**Given** existe un producto con lotes asociados.<br>**When** se procesa `GET /api/v1/products/{id}/lots`.<br>**Then** responde con código `200` y los lotes del producto.<br><br>**Scenario:** Consultar lotes de un producto inexistente<br><br>**Given** el identificador indicado no corresponde a un producto.<br>**When** se procesa `GET /api/v1/products/{id}/lots`.<br>**Then** responde con código `404`.<br><br>**Scenario:** Consultar catálogo con stock bajo<br><br>**Given** existen productos cuya disponibilidad cumple la condición de stock bajo.<br>**When** se ejecuta `GET /api/v1/products/low-stock`.<br>**Then** responde con código `200` y los productos coincidentes. | EPIC-03 |
| TS04 | Consulta REST del historial de movimientos de inventario | **Como** Developer, **quiero** publicar la consulta de movimientos registrados desde Operations, **para** permitir la trazabilidad de los cambios de inventario producidos por las operaciones del negocio. | **Scenario:** Consultar movimientos existentes<br><br>**Given** hay movimientos de inventario almacenados.<br>**When** se ejecuta `GET /api/v1/inventory-movements`.<br>**Then** devuelve código `200` y los registros disponibles.<br><br>**Scenario:** Consultar historial sin movimientos<br><br>**Given** no hay movimientos registrados.<br>**When** se ejecuta `GET /api/v1/inventory-movements`.<br>**Then** devuelve código `200` con una colección vacía.<br><br>**Scenario:** Consultar movimientos de operaciones comerciales<br><br>**Given** una compra o venta confirmada generó movimientos de inventario.<br>**When** se consulta el historial después de la confirmación.<br>**Then** la respuesta incluye los movimientos registrados por dicha operación. | EPIC-04 |
| TS05 | Registro y consulta REST de mermas | **Como** Developer, **quiero** disponer de servicios REST para registrar y consultar mermas, **para** documentar las pérdidas operativas y actualizar correctamente las existencias. | **Scenario:** Registrar merma autorizada<br><br>**Given** un usuario autorizado solicita una merma válida sobre existencias disponibles.<br>**When** la API recibe `POST /api/v1/wastes`.<br>**Then** registra la merma y devuelve código `201`.<br><br>**Scenario:** Consultar mermas<br><br>**Given** existen mermas registradas.<br>**When** la API recibe `GET /api/v1/wastes`.<br>**Then** devuelve código `200` con sus registros.<br><br>**Scenario:** Rechazar merma sin disponibilidad<br><br>**Given** la cantidad solicitada supera las existencias utilizables.<br>**When** se solicita registrar la merma.<br>**Then** la API rechaza la operación con código `409` sin descontar stock. | EPIC-04 |
| TS06 | Registro y consulta REST de conteos físicos | **Como** Developer, **quiero** publicar operaciones REST para registrar conteos de inventario y consultarlos por identificador, **para** documentar la verificación física de existencias. | **Scenario:** Registrar conteo válido<br><br>**Given** un usuario autorizado proporciona una cantidad física válida.<br>**When** se ejecuta `POST /api/v1/inventory-counts`.<br>**Then** la API registra el conteo y responde con código `201`.<br><br>**Scenario:** Consultar conteo registrado<br><br>**Given** existe un conteo físico con el identificador indicado.<br>**When** se ejecuta `GET /api/v1/inventory-counts/{id}`.<br>**Then** la API responde con código `200` y los datos del conteo.<br><br>**Scenario:** Consultar conteo inexistente<br><br>**Given** no existe un conteo con el identificador solicitado.<br>**When** se ejecuta `GET /api/v1/inventory-counts/{id}`.<br>**Then** la API responde con código `404`. | EPIC-04 |
| TS07 | Gestión REST de compras comerciales | **Como** Developer, **quiero** exponer servicios de creación y consulta de compras, **para** permitir la preparación y seguimiento de adquisiciones de mercadería antes de confirmarlas. | **Scenario:** Crear una compra en borrador<br><br>**Given** un usuario autorizado envía una compra con productos y cantidades válidos.<br>**When** la API procesa `POST /api/v1/purchases`.<br>**Then** registra la compra en borrador y responde con código `201`.<br><br>**Scenario:** Consultar compras registradas<br><br>**Given** existen compras almacenadas.<br>**When** se procesa `GET /api/v1/purchases`.<br>**Then** la API responde con código `200` y la colección correspondiente.<br><br>**Scenario:** Consultar compra inexistente<br><br>**Given** el identificador solicitado no corresponde a ninguna compra.<br>**When** se ejecuta `GET /api/v1/purchases/{id}`.<br>**Then** la API responde con código `404`. | EPIC-05 |
| TS08 | Gestión REST de ventas comerciales | **Como** Developer, **quiero** implementar servicios REST para preparar y consultar ventas, **para** registrar sus productos, cantidades y estado antes de aplicar una salida de inventario. | **Scenario:** Registrar venta en borrador<br><br>**Given** un usuario autorizado envía los datos válidos de una venta.<br>**When** se ejecuta `POST /api/v1/sales`.<br>**Then** la API registra el borrador y responde con código `201`.<br><br>**Scenario:** Consultar ventas registradas<br><br>**Given** existen ventas en el sistema.<br>**When** se ejecuta `GET /api/v1/sales`.<br>**Then** la API responde con código `200` y la colección de ventas.<br><br>**Scenario:** Consultar venta inexistente<br><br>**Given** no existe una venta con el identificador solicitado.<br>**When** se ejecuta `GET /api/v1/sales/{id}`.<br>**Then** la API responde con código `404`. | EPIC-05 |
| TS09 | Confirmación transaccional de compras y ventas | **Como** Developer, **quiero** confirmar compras y ventas mediante operaciones REST transaccionales, **para** actualizar las existencias y registrar movimientos sin duplicar confirmaciones ni dejar cambios parciales. | **Scenario:** Confirmar una compra válida<br><br>**Given** existe una compra en borrador con datos válidos.<br>**When** se ejecuta `POST /api/v1/purchases/{id}/confirm`.<br>**Then** la compra queda confirmada y se registran sus entradas de inventario en una misma operación.<br><br>**Scenario:** Confirmar una venta con disponibilidad<br><br>**Given** existe una venta en borrador y hay stock suficiente.<br>**When** se ejecuta `POST /api/v1/sales/{id}/confirm`.<br>**Then** la venta queda confirmada y se descuentan las existencias y registran las salidas asociadas.<br><br>**Scenario:** Evitar confirmación duplicada<br><br>**Given** un documento comercial ya fue confirmado.<br>**When** se vuelve a solicitar su confirmación.<br>**Then** la API responde con código `409` sin aplicar los movimientos por segunda vez.<br><br>**Scenario:** Rechazar venta sin stock<br><br>**Given** una venta requiere más existencias que las disponibles.<br>**When** se intenta confirmar la venta.<br>**Then** la API rechaza la confirmación sin generar descuentos parciales. | EPIC-05 |
| TS10 | Consulta REST de alertas del inventario | **Como** Developer, **quiero** ofrecer recursos REST de lectura de alertas desde Monitoring, **para** permitir su consulta desde los módulos de monitoreo del Frontend. | **Scenario:** Listar alertas registradas<br><br>**Given** existen alertas almacenadas.<br>**When** se ejecuta `GET /api/v1/alerts`.<br>**Then** la API responde con código `200` y la colección de alertas.<br><br>**Scenario:** Consultar alerta por identificador<br><br>**Given** existe una alerta con el identificador indicado.<br>**When** se ejecuta `GET /api/v1/alerts/{id}`.<br>**Then** la API responde con código `200` y el detalle de la alerta.<br><br>**Scenario:** Consultar alerta inexistente<br><br>**Given** el identificador válido no corresponde a una alerta.<br>**When** se ejecuta `GET /api/v1/alerts/{id}`.<br>**Then** la API responde con código `404`. | EPIC-06 |
| TS11 | Consulta REST de resumen de ventas | **Como** Developer, **quiero** publicar un servicio REST con indicadores agregados de ventas confirmadas, **para** respaldar el análisis del negocio desde Reporting. | **Scenario:** Consultar resumen de ventas<br><br>**Given** existen ventas confirmadas dentro del período consultado.<br>**When** se ejecuta `GET /api/v1/reports/sales-summary`.<br>**Then** la API responde con código `200` y los indicadores calculados.<br><br>**Scenario:** Consultar período sin ventas<br><br>**Given** no hay ventas confirmadas para los filtros indicados.<br>**When** se solicita el resumen de ventas.<br>**Then** la API devuelve un resultado válido con valores acumulados en cero.<br><br>**Scenario:** Rechazar fechas inválidas<br><br>**Given** se envían parámetros `from` o `to` con formato no válido.<br>**When** se consulta el resumen de ventas.<br>**Then** la API responde con código `400`. | EPIC-07 |
| TS12 | Consulta REST de productos más vendidos | **Como** Developer, **quiero** proporcionar un ranking REST de productos vendidos con filtros de fecha y límite, **para** apoyar el análisis de ventas y las decisiones comerciales. | **Scenario:** Consultar ranking de productos<br><br>**Given** existen ventas confirmadas con productos registrados.<br>**When** se ejecuta `GET /api/v1/reports/top-products`.<br>**Then** la API devuelve código `200` y los productos ordenados por cantidad vendida.<br><br>**Scenario:** Limitar cantidad de resultados<br><br>**Given** existen suficientes productos en el ranking.<br>**When** se envía un valor válido de `limit` en la consulta.<br>**Then** la respuesta contiene como máximo la cantidad de productos solicitada.<br><br>**Scenario:** Rechazar límite inválido<br><br>**Given** el parámetro `limit` no cumple las reglas de validación.<br>**When** se ejecuta `GET /api/v1/reports/top-products`.<br>**Then** la API responde con código `400`. | EPIC-07 |
| TS13 | Autenticación JWT y consulta de identidad | **Como** Developer, **quiero** ofrecer servicios REST para iniciar sesión y consultar la identidad autenticada, **para** controlar el acceso a los recursos protegidos de BodeGo. | **Scenario:** Autenticar credenciales válidas<br><br>**Given** existe un usuario activo con credenciales correctas.<br>**When** se ejecuta `POST /api/v1/auth/login`.<br>**Then** la API responde con código `200` y la información de autenticación correspondiente.<br><br>**Scenario:** Rechazar credenciales incorrectas<br><br>**Given** el correo o la contraseña no son válidos.<br>**When** se ejecuta `POST /api/v1/auth/login`.<br>**Then** la API responde con código `401` sin conceder acceso.<br><br>**Scenario:** Consultar usuario autenticado<br><br>**Given** la solicitud incluye un token válido.<br>**When** se ejecuta `GET /api/v1/auth/me`.<br>**Then** la API responde con código `200` y la información autorizada del usuario. | EPIC-08 |
| TS14 | Gestión REST de usuarios | **Como** Developer, **quiero** exponer registro y consulta de usuarios mediante endpoints protegidos, **para** administrar cuentas del personal de forma controlada. | **Scenario:** Registrar un usuario autorizado<br><br>**Given** un Administrador autenticado envía datos válidos de una cuenta.<br>**When** la API procesa `POST /api/v1/users`.<br>**Then** crea la cuenta y responde con código `201` sin exponer la contraseña.<br><br>**Scenario:** Consultar usuarios autorizados<br><br>**Given** un Administrador autenticado solicita la lista de usuarios.<br>**When** se ejecuta `GET /api/v1/users`.<br>**Then** la API devuelve código `200` y los datos permitidos.<br><br>**Scenario:** Rechazar correo duplicado<br><br>**Given** ya existe una cuenta con el correo proporcionado.<br>**When** el Administrador intenta registrar otra cuenta con ese correo.<br>**Then** la API devuelve código `409` sin duplicar el usuario. | EPIC-08 |
| TS15 | Consulta REST de roles y protección administrativa | **Como** Developer, **quiero** exponer consultas de roles protegidas por políticas de autorización, **para** respaldar la administración de permisos y restringir el acceso según el perfil. | **Scenario:** Listar roles con autorización<br><br>**Given** el usuario está autenticado como Administrador.<br>**When** se ejecuta `GET /api/v1/roles`.<br>**Then** la API responde con código `200` y los roles disponibles.<br><br>**Scenario:** Consultar rol inexistente<br><br>**Given** un Administrador consulta un identificador de rol válido que no existe.<br>**When** se ejecuta `GET /api/v1/roles/{id}`.<br>**Then** la API responde con código `404`.<br><br>**Scenario:** Restringir consulta a usuario no administrador<br><br>**Given** un usuario autenticado no cumple la política de Administrador.<br>**When** intenta consultar `GET /api/v1/roles`.<br>**Then** el servicio deniega el acceso con código `403`. | EPIC-08 |
| TS16 | Documentación OpenAPI con Scalar e integración REST del Frontend | **Como** Developer, **quiero** publicar la documentación de la API mediante OpenAPI y Scalar y verificar su consumo desde Vue, **para** facilitar la integración y validación de los servicios de BodeGo. | **Scenario:** Consultar documentación con Scalar<br><br>**Given** la API se ejecuta en un entorno con documentación habilitada.<br>**When** el Developer abre la interfaz de Scalar.<br>**Then** puede consultar los grupos de endpoints, métodos, esquemas y parámetros registrados en OpenAPI.<br><br>**Scenario:** Consumir servicio desde el Frontend<br><br>**Given** el Frontend Vue tiene configurada la URL de la API y el origen está permitido por CORS.<br>**When** la aplicación realiza una solicitud REST válida.<br>**Then** puede recibir y procesar la respuesta del servicio correspondiente.<br><br>**Scenario:** Gestionar respuesta de error de servicio<br><br>**Given** una solicitud desde Vue recibe una respuesta HTTP de error.<br>**When** el Frontend procesa el resultado.<br>**Then** presenta un estado de error comprensible sin interpretar la operación como exitosa. | EPIC-02 |

---

## 3.2. Impact Mapping

---

| **Business Goals** | **Actors** | **Impact** | **Deliverables** | **User Stories** |
|---|---|---|---|---|
| **Goal N°1:**<br>**Captar el interés de negocios minoristas mediante una presencia digital clara que comunique la propuesta de valor de BodeGo durante los primeros 12 meses.** | Visitante / Cliente potencial | Conocer la solución BodeGo, comprender sus beneficios y solicitar información sobre la plataforma. | Landing Page comercial.<br><br>Secciones informativas del producto.<br><br>Formulario de contacto. | **US01: Visualización del Hero Principal.** Como visitante, quiero visualizar una sección principal con la propuesta de valor de BodeGo, para comprender cómo la plataforma ayuda a gestionar inventarios y reducir mermas.<br><br>**US02: Visualización de Beneficios del Producto.** Como visitante, quiero conocer los beneficios principales de BodeGo, para identificar las ventajas de utilizar una plataforma de gestión operativa.<br><br>**US03: Presentación de Funcionalidades Principales.** Como visitante, quiero visualizar las funcionalidades principales de BodeGo, para conocer las herramientas disponibles antes de utilizar la aplicación.<br><br>**US05: Formulario de Contacto Comercial.** Como visitante, quiero enviar una solicitud de contacto, para recibir información adicional sobre BodeGo. |
| | Visitante / Cliente potencial | Entender el funcionamiento general del producto antes de incorporarlo al negocio. | Sección explicativa del funcionamiento de la plataforma. | **US04: Visualización del Funcionamiento de BodeGo.** Como visitante, quiero conocer cómo funciona BodeGo, para entender el flujo general de uso dentro de una bodega o minimarket. |
| **Goal N°2:**<br>**Mejorar el control operativo del inventario reduciendo errores de registro manual en un 40% durante los primeros 12 meses.** | Administrador | Mantener productos correctamente registrados y organizados dentro del sistema. | Gestión de productos.<br><br>Categorías.<br><br>Detalle de productos. | **US16: Registro de Productos.** Como Administrador, quiero registrar nuevos productos, para mantener actualizado el catálogo de inventario.<br><br>**US17: Edición de Información del Producto.** Como Administrador, quiero modificar la información de un producto registrado, para mantener datos actualizados.<br><br>**US18: Clasificación de Productos por Categoría.** Como Administrador, quiero asignar categorías a los productos, para organizar el inventario y facilitar su búsqueda.<br><br>**US09: Consulta del Detalle de Producto.** Como Administrador o Empleado, quiero visualizar el detalle de un producto, para revisar información específica del artículo. |
| | Administrador / Empleado | Encontrar rápidamente productos y conocer su disponibilidad actual. | Buscador y filtros de inventario.<br><br>Visualización de inventario. | **US08: Visualización del Módulo de Inventario.** Como Administrador o Empleado, quiero visualizar el inventario registrado, para conocer la disponibilidad actual de productos.<br><br>**US11: Filtrado y Búsqueda de Productos.** Como Administrador o Empleado, quiero buscar productos mediante filtros, para encontrar rápidamente los artículos que necesito gestionar.<br><br>**US21: Consulta de Stock Actual.** Como Administrador o Empleado, quiero consultar la cantidad disponible de cada producto, para conocer el estado actual del inventario. |
| **Goal N°3:**<br>**Reducir en un 30% las pérdidas generadas por productos vencidos, dañados o deteriorados durante los primeros 10 meses.** | Administrador / Empleado | Controlar productos perecibles y actuar antes de generar pérdidas económicas. | Gestión de lotes.<br><br>Control de vencimientos.<br><br>Registro de mermas.<br><br>Alertas preventivas. | **US20: Gestión de Lotes y Fechas de Vencimiento.** Como Empleado, quiero registrar lotes con fechas de vencimiento, para controlar productos perecibles.<br><br>**US27: Control de Productos Próximos a Vencer.** Como Administrador, quiero identificar productos próximos a vencer, para tomar acciones preventivas.<br><br>**US31: Registro de Productos Dañados o Vencidos.** Como Empleado, quiero registrar productos dañados o vencidos, para mantener actualizado el inventario.<br><br>**US34: Generación de Alertas de Stock Bajo.** Como Administrador, quiero recibir alertas cuando un producto tenga stock bajo, para anticipar necesidades de reposición. |
| **Goal N°4:**<br>**Digitalizar el 80% de las operaciones diarias realizadas por empleados durante los primeros 6 meses de implementación.** | Empleado Operativo | Registrar correctamente ingresos, salidas y movimientos del inventario. | Registro de operaciones.<br><br>Actualización automática de stock.<br><br>Historial operativo. | **US19: Registro de Ingreso de Inventario.** Como Empleado, quiero registrar ingresos de productos al inventario, para mantener actualizado el stock disponible.<br><br>**US23: Registro de Salida de Productos.** Como Empleado, quiero registrar salidas de productos, para mantener actualizado el inventario.<br><br>**US26: Historial de Movimientos de Inventario.** Como Administrador, quiero consultar el historial de movimientos, para conocer la trazabilidad.<br><br>**US34: Visualización de Operaciones del Empleado.** Como Empleado, quiero consultar mis operaciones realizadas, para verificar movimientos registrados durante mi jornada. |
| **Goal N°5:**<br>**Mejorar la toma de decisiones del administrador mediante indicadores y reportes operativos durante los primeros 12 meses.** | Administrador | Analizar información del negocio para tomar decisiones estratégicas. | Dashboard administrativo.<br><br>Reportes analíticos.<br><br>Indicadores operativos. | **US37: Dashboard de Indicadores del Negocio.** Como Administrador, quiero visualizar indicadores generales del negocio, para conocer rápidamente el estado operativo.<br><br>**US38: Reporte de Rotación de Productos.** Como Administrador, quiero conocer la rotación de productos, para identificar comportamiento del inventario.<br><br>**US39: Reporte de Productos Próximos a Vencer.** Como Administrador, quiero consultar productos próximos a vencer, para planificar acciones preventivas.<br><br>**US40: Reporte de Mermas del Negocio.** Como Administrador, quiero visualizar reportes de mermas, para analizar pérdidas generadas. |
| **Goal N°6:**<br>**Garantizar que todos los accesos al sistema sean seguros mediante autenticación y permisos definidos durante la primera versión productiva.** | Administrador / Empleado | Acceder únicamente a las funcionalidades correspondientes según su responsabilidad. | Gestión de usuarios.<br><br>Roles y permisos.<br><br>Autenticación.<br><br>Gestión de contraseña. | **US46: Registro de Usuarios del Sistema.** Como Administrador, quiero registrar usuarios dentro de BodeGo, para permitir accesos autorizados.<br><br>**US47: Gestión de Roles y Permisos.** Como Administrador, quiero asignar roles y permisos, para controlar el acceso a funcionalidades.<br><br>**US48: Inicio de Sesión Seguro.** Como usuario registrado, quiero iniciar sesión mediante mis credenciales, para acceder de manera segura.<br><br>**US49: Recuperación y Cambio de Contraseña.** Como usuario, quiero recuperar o cambiar mi contraseña, para mantener protegido mi acceso.<br><br>**US50: Cierre de Sesión y Protección de Cuenta.** Como usuario, quiero cerrar mi sesión correctamente, para evitar accesos no autorizados. |

---

## 3.3. Product Backlog

---

# Product Backlog — BodeGo

| **# Orden** | **Story ID (US / TS)** | **Título** | **Descripción** | **Story Points** (1 / 2 / 3 / 4 / 5 / 6) |
|---:|:---:|---|---|---:|
| **1** | **US01** | Visualización de la propuesta de valor | **Como** visitante, **quiero** conocer la propuesta principal de BodeGo, **para** entender cómo mejora la gestión de un minimarket. | **2** |
| **2** | **US02** | Consulta de beneficios del producto | **Como** visitante, **quiero** identificar los beneficios de BodeGo, **para** evaluar su utilidad para mi negocio. | **2** |
| **3** | **US03** | Presentación informativa de funcionalidades | **Como** visitante, **quiero** conocer las funcionalidades de BodeGo, **para** comprender el alcance general del producto. | **3** |
| **4** | **US04** | Explicación de los pasos de uso de BodeGo | **Como** visitante, **quiero** conocer los pasos generales para utilizar BodeGo, **para** comprender el flujo básico de trabajo. | **2** |
| **5** | **US05** | Formulario de contacto comercial | **Como** visitante interesado, **quiero** enviar mis datos de contacto, **para** solicitar información sobre BodeGo. | **4** |
| **6** | **US07** | Navegación entre módulos autorizados | **Como** usuario autenticado, **quiero** navegar entre los módulos habilitados para mi rol, **para** acceder a mis tareas sin utilizar rutas ajenas. | **4** |
| **7** | **US08** | Consulta visual del inventario | **Como** Administrador o Empleado, **quiero** consultar el catálogo de productos, **para** revisar productos y existencias desde la aplicación. | **3** |
| **8** | **US06** | Visualización del Dashboard operativo | **Como** Administrador, **quiero** consultar indicadores resumidos del negocio, **para** supervisar las operaciones más relevantes. | **5** |
| **9** | **US11** | Búsqueda y filtrado de productos | **Como** Administrador o Empleado, **quiero** buscar productos por criterios disponibles, **para** encontrar mercadería de forma rápida. | **4** |
| **10** | **US09** | Consulta visual del detalle de producto | **Como** Administrador o Empleado, **quiero** revisar la información de un producto específico, **para** conocer su categoría, precio y existencias. | **3** |
| **11** | **US14** | Registro visual de productos con validaciones | **Como** Administrador, **quiero** registrar productos desde formularios, **para** mantener organizado el catálogo. | **4** |
| **12** | **US10** | Consulta visual de operaciones de inventario | **Como** Administrador o Empleado autorizado, **quiero** consultar operaciones y movimientos, **para** revisar el historial del inventario. | **3** |
| **13** | **US12** | Visualización de alertas de inventario | **Como** Administrador, **quiero** consultar las alertas registradas, **para** identificar situaciones que requieren revisión. | **3** |
| **14** | **US13** | Visualización de reportes operativos | **Como** Administrador, **quiero** consultar los reportes disponibles, **para** evaluar la evolución del negocio. | **4** |
| **15** | **US15** | Consulta visual de documentos comerciales | **Como** Administrador o Empleado autorizado, **quiero** revisar compras y ventas en la aplicación, **para** conocer el estado e importe de los documentos. | **3** |
| **16** | **US51** | Galería visual de pantallas de BodeGo | **Como** visitante, **quiero** consultar vistas representativas de la aplicación, **para** conocer cómo se presentan sus módulos principales. | **4** |
| **17** | **US52** | Presentación de roles Administrador y Empleado | **Como** visitante, **quiero** conocer las responsabilidades de cada tipo de usuario, **para** evaluar cómo se adapta BodeGo al personal del minimarket. | **3** |
| **18** | **US53** | Consulta de plan y precio comercial | **Como** visitante interesado, **quiero** conocer el precio y las funcionalidades incluidas en BodeGo, **para** evaluar la contratación del producto. | **3** |
| **19** | **US16** | Registro de productos en catálogo | **Como** Administrador, **quiero** registrar productos con su categoría y datos de venta, **para** mantener actualizado el catálogo de mercadería. | **4** |
| **20** | **TS01** | Gestión REST de productos | **Como** Developer, **quiero** exponer recursos REST de registro y consulta de productos en ASP.NET Core, **para** proporcionar información consistente del catálogo al Frontend Web de BodeGo. | **5** |
| **21** | **US18** | Clasificación de productos por categorías | **Como** Administrador, **quiero** asociar productos con categorías registradas, **para** organizar la mercadería por tipo. | **3** |
| **22** | **TS02** | Gestión REST de categorías | **Como** Developer, **quiero** publicar servicios REST para registrar y consultar categorías, **para** organizar los productos de BodeGo dentro del contexto Inventory. | **4** |
| **23** | **US21** | Consulta de stock actual de productos | **Como** Administrador o Empleado, **quiero** consultar existencias vigentes, **para** conocer disponibilidad para compras y ventas. | **3** |
| **24** | **US19** | Consulta de productos con stock bajo | **Como** Administrador, **quiero** consultar los productos cuya existencia es inferior al mínimo configurado, **para** identificar necesidades de reposición. | **3** |
| **25** | **US20** | Consulta de lotes asociados a productos | **Como** Administrador o Empleado, **quiero** consultar lotes de un producto, **para** conocer cantidades y vencimientos disponibles. | **3** |
| **26** | **US27** | Consulta de productos próximos a vencer | **Como** Administrador, **quiero** identificar lotes con fechas cercanas de vencimiento, **para** planificar acciones oportunas. | **3** |
| **27** | **TS03** | Consultas REST de lotes y productos con stock bajo | **Como** Developer, **quiero** exponer consultas de lotes por producto y de productos con existencias críticas, **para** apoyar el seguimiento de la disponibilidad y los vencimientos. | **4** |
| **28** | **US24** | Validación del stock disponible para ventas | **Como** Empleado autorizado, **quiero** evitar confirmar ventas sin unidades suficientes, **para** prevenir existencias negativas. | **5** |
| **29** | **US22** | Consistencia del inventario ante confirmaciones comerciales | **Como** Administrador, **quiero** que las confirmaciones de compras y ventas mantengan consistentes las existencias, **para** evitar modificaciones parciales o duplicadas del inventario. | **6** |
| **30** | **US28** | Asignación FIFO de existencias en ventas sin lote explícito | **Como** Empleado autorizado, **quiero** que las ventas sin lote específico consuman existencias en orden de ingreso, **para** mantener reglas de retiro consistentes. | **6** |
| **31** | **US17** | Actualización de información del producto | **Como** Administrador, **quiero** modificar los datos editables de un producto existente, **para** corregir errores del catálogo. | **4** |
| **32** | **US41** | Registro de compras en borrador | **Como** Empleado autorizado, **quiero** registrar una compra con sus líneas y costos, **para** preparar la recepción de mercadería. | **5** |
| **33** | **TS07** | Gestión REST de compras comerciales | **Como** Developer, **quiero** exponer servicios de creación y consulta de compras, **para** permitir la preparación y seguimiento de adquisiciones de mercadería antes de confirmarlas. | **5** |
| **34** | **US42** | Registro de ventas en borrador | **Como** Empleado autorizado, **quiero** registrar una venta con productos y precios, **para** preparar una operación comercial. | **5** |
| **35** | **TS08** | Gestión REST de ventas comerciales | **Como** Developer, **quiero** implementar servicios REST para preparar y consultar ventas, **para** registrar sus productos, cantidades y estado antes de aplicar una salida de inventario. | **5** |
| **36** | **US43** | Confirmación de compras de mercadería | **Como** Empleado autorizado, **quiero** confirmar una compra registrada, **para** ingresar las unidades recibidas al inventario. | **6** |
| **37** | **US44** | Confirmación de ventas con salida de inventario | **Como** Empleado autorizado, **quiero** confirmar una venta válida, **para** registrar la venta y descontar mercadería. | **6** |
| **38** | **TS09** | Confirmación transaccional de compras y ventas | **Como** Developer, **quiero** confirmar compras y ventas mediante operaciones REST transaccionales, **para** actualizar las existencias y registrar movimientos sin duplicar confirmaciones ni dejar cambios parciales. | **6** |
| **39** | **US45** | Consulta del historial y detalle comercial | **Como** Administrador o Empleado autorizado, **quiero** consultar compras y ventas existentes, **para** revisar sus importes, productos y estados. | **3** |
| **40** | **US54** | Cambio de idioma español/inglés en el Frontend | **Como** usuario de BodeGo, **quiero** cambiar el idioma de la interfaz entre inglés y español, **para** utilizar los módulos y formularios en el idioma de mi preferencia. | **5** |
| **41** | **US55** | Preparación de compras con carrito de productos | **Como** Empleado autorizado, **quiero** armar una compra con varias líneas, **para** evitar registrar artículos uno por uno. | **4** |
| **42** | **US56** | Preparación de ventas con disponibilidad visible | **Como** Empleado autorizado, **quiero** armar una venta consultando existencias, **para** evitar ofrecer unidades no disponibles. | **5** |
| **43** | **US57** | Estados de confirmación y resultado de compras y ventas | **Como** Empleado autorizado, **quiero** conocer si un documento fue registrado o confirmado, **para** evitar repetir operaciones por incertidumbre. | **4** |
| **44** | **US58** | Presentación de estados vacíos, carga y error de servicios | **Como** usuario de BodeGo, **quiero** recibir información clara al consultar módulos, **para** distinguir datos vacíos de fallas de conexión. | **4** |
| **45** | **US59** | Previsualización de stock antes de operaciones | **Como** Empleado autorizado, **quiero** revisar el stock consultado y la variación propuesta, **para** confirmar cantidades con mayor seguridad. | **3** |
| **46** | **US60** | Protección frente a resultados inciertos de operaciones | **Como** usuario de BodeGo, **quiero** conocer si una operación quedó pendiente de confirmación, **para** evitar duplicar solicitudes cuando se pierde la conexión. | **5** |
| **47** | **TS16** | Documentación OpenAPI con Scalar e integración REST del Frontend | **Como** Developer, **quiero** publicar la documentación de la API mediante OpenAPI y Scalar y verificar su consumo desde Vue, **para** facilitar la integración y validación de los servicios de BodeGo. | **5** |
| **48** | **US26** | Consulta del historial de movimientos de inventario | **Como** Administrador o Empleado autorizado, **quiero** consultar movimientos registrados, **para** identificar el origen de los cambios de stock. | **3** |
| **49** | **TS04** | Consulta REST del historial de movimientos de inventario | **Como** Developer, **quiero** publicar la consulta de movimientos registrados desde Operations, **para** permitir la trazabilidad de los cambios de inventario producidos por las operaciones del negocio. | **3** |
| **50** | **US23** | Trazabilidad de salidas originadas en ventas | **Como** Administrador o Empleado autorizado, **quiero** identificar los movimientos de salida originados por una venta confirmada, **para** rastrear su efecto sobre el inventario. | **4** |
| **51** | **US30** | Trazabilidad por producto, lote y operación | **Como** Administrador, **quiero** relacionar movimientos con productos, lotes y documentos de origen, **para** investigar cambios de stock. | **4** |
| **52** | **US29** | Registro de conteo físico de inventario | **Como** Empleado autorizado, **quiero** registrar cantidades contadas físicamente, **para** documentar diferencias con las existencias del sistema. | **4** |
| **53** | **US25** | Consulta de conteos físicos por identificador | **Como** Administrador o Empleado autorizado, **quiero** consultar un conteo físico registrado mediante su identificador, **para** verificar las cantidades declaradas y las diferencias documentadas. | **3** |
| **54** | **TS06** | Registro y consulta REST de conteos físicos | **Como** Developer, **quiero** publicar operaciones REST para registrar conteos de inventario y consultarlos por identificador, **para** documentar la verificación física de existencias. | **5** |
| **55** | **US31** | Registro de mermas de inventario | **Como** Empleado autorizado, **quiero** registrar unidades dañadas o vencidas, **para** mantener el inventario acorde con las pérdidas. | **4** |
| **56** | **US32** | Clasificación de causas de merma | **Como** Empleado autorizado, **quiero** indicar el motivo de una merma, **para** analizar las causas de pérdidas. | **2** |
| **57** | **US37** | Consulta de mermas registradas | **Como** Administrador, **quiero** consultar el historial de mermas, **para** conocer pérdidas documentadas. | **3** |
| **58** | **TS05** | Registro y consulta REST de mermas | **Como** Developer, **quiero** disponer de servicios REST para registrar y consultar mermas, **para** documentar las pérdidas operativas y actualizar correctamente las existencias. | **5** |
| **59** | **US33** | Filtrado de alertas por tipo y estado | **Como** Administrador, **quiero** filtrar las alertas por tipo, estado o producto, **para** identificar rápidamente las situaciones que requieren atención. | **3** |
| **60** | **US35** | Consulta de alertas registradas | **Como** Administrador, **quiero** consultar las alertas persistidas en el sistema, **para** identificar los casos que requieren revisión. | **3** |
| **61** | **US36** | Seguimiento de alertas de vencimiento | **Como** Administrador, **quiero** identificar las alertas de vencimiento asociadas a lotes, **para** revisar oportunamente la mercadería perecible que requiere atención. | **3** |
| **62** | **US34** | Generación automática de alertas por stock bajo | **Como** Administrador, **quiero** recibir alertas generadas al detectar bajo stock, **para** atender oportunamente una situación de inventario. | **5** |
| **63** | **TS10** | Consulta REST de alertas del inventario | **Como** Developer, **quiero** ofrecer recursos REST de lectura de alertas desde Monitoring, **para** permitir su consulta desde los módulos de monitoreo del Frontend. | **3** |
| **64** | **US38** | Consulta del resumen de ventas | **Como** Administrador, **quiero** conocer el número e importe de ventas confirmadas, **para** evaluar la actividad comercial. | **4** |
| **65** | **US39** | Dashboard con indicadores de actividad comercial | **Como** Administrador, **quiero** ver indicadores relevantes sobre operaciones comerciales, **para** tomar decisiones informadas. | **5** |
| **66** | **TS11** | Consulta REST de resumen de ventas | **Como** Developer, **quiero** publicar un servicio REST con indicadores agregados de ventas confirmadas, **para** respaldar el análisis del negocio desde Reporting. | **4** |
| **67** | **US40** | Consulta de productos más vendidos | **Como** Administrador, **quiero** identificar productos con mayor cantidad vendida, **para** reconocer tendencias de consumo. | **4** |
| **68** | **TS12** | Consulta REST de productos más vendidos | **Como** Developer, **quiero** proporcionar un ranking REST de productos vendidos con filtros de fecha y límite, **para** apoyar el análisis de ventas y las decisiones comerciales. | **4** |
| **69** | **US46** | Registro de usuarios del sistema | **Como** Administrador, **quiero** crear usuarios autorizados, **para** asignar acceso controlado a BodeGo. | **4** |
| **70** | **US48** | Inicio de sesión con credenciales | **Como** usuario registrado, **quiero** autenticarme mediante correo y contraseña, **para** acceder a las funciones autorizadas. | **5** |
| **71** | **TS13** | Autenticación JWT y consulta de identidad | **Como** Developer, **quiero** ofrecer servicios REST para iniciar sesión y consultar la identidad autenticada, **para** controlar el acceso a los recursos protegidos de BodeGo. | **6** |
| **72** | **US49** | Consulta del usuario autenticado | **Como** usuario autenticado, **quiero** consultar mi identidad y rol actual, **para** comprobar los permisos de mi sesión. | **3** |
| **73** | **US47** | Consulta de roles y permisos | **Como** Administrador, **quiero** consultar los roles del sistema, **para** administrar responsabilidades de acceso. | **3** |
| **74** | **TS14** | Gestión REST de usuarios | **Como** Developer, **quiero** exponer registro y consulta de usuarios mediante endpoints protegidos, **para** administrar cuentas del personal de forma controlada. | **5** |
| **75** | **TS15** | Consulta REST de roles y protección administrativa | **Como** Developer, **quiero** exponer consultas de roles protegidas por políticas de autorización, **para** respaldar la administración de permisos y restringir el acceso según el perfil. | **4** |
| **76** | **US50** | Cierre de sesión del Frontend | **Como** usuario autenticado, **quiero** cerrar mi sesión de trabajo, **para** evitar que otros continúen utilizando mi acceso. | **2** |

---

# Capítulo IV: Product Design

## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines

El sistema de diseño de **BodeGo** se basa en una estética moderna, limpia y funcional, orientada a facilitar la gestión diaria de inventarios en minimarkets. La interfaz busca mostrar la información de manera clara y ordenada, permitiendo que Administradores y Empleados puedan identificar rápidamente el estado del stock, los productos próximos a vencer y las operaciones realizadas.

- **Branding & Tono:**
  - **Tono:** Profesional, confiable y práctico.
  - **Lenguaje:** Claro, directo y orientado a las operaciones del minimarket.
  - **Personalidad:** BodeGo se presenta como una herramienta de apoyo para mantener el inventario organizado y reducir pérdidas por productos perecibles.
  - **Identidad:** Se prioriza la sensación de control, rapidez y seguridad en las operaciones.

- **Typography:**
  - **Fuente principal:** Hanken Grotesk.
  - **Títulos:** Uso de pesos Bold o SemiBold para destacar nombres de módulos, indicadores y datos importantes.
  - **Contenido:** Peso Regular para tablas, descripciones y textos informativos.
  - **Etiquetas:** Tamaño reducido para estados, categorías, fechas y datos secundarios.
  - Se mantiene una jerarquía visual clara entre títulos, subtítulos, indicadores y contenido.

- **Colors:**
  - **Principal:** Azul `#2563EB`, utilizado para botones, acciones principales, elementos seleccionados y enlaces.
  - **Secundario:** Azul oscuro `#0F172A`, empleado principalmente en textos importantes y elementos de alto contraste.
  - **Terciario:** Verde `#10B981`, utilizado para indicar estados correctos, productos activos, ingresos o acciones exitosas.
  - **Neutral:** Gris `#64748B`, empleado en información secundaria, iconos y etiquetas.
  - **Rojo:** Utilizado para alertas críticas, productos vencidos, stock crítico y errores.
  - **Amarillo/Naranja:** Utilizado para advertencias y productos próximos a vencer.

- **Spacing:**
  - Los módulos mantienen márgenes y separaciones constantes entre tarjetas, tablas y formularios.
  - Las tarjetas utilizan bordes suavemente redondeados.
  - La información se distribuye mediante bloques y columnas para evitar la saturación visual.
  - Los indicadores principales cuentan con mayor espacio para facilitar su identificación.

- **Iconografía:**
  - Se utilizan iconos simples acompañados de texto para facilitar la comprensión.
  - Los iconos permiten diferenciar rápidamente acciones como registrar ingreso, registrar salida, registrar merma, consultar inventario o acceder a reportes.
  - Los colores de los iconos también ayudan a comunicar el estado de cada operación.

---

### 4.1.2. Web Style Guidelines

BodeGo está diseñado principalmente como una **aplicación web de gestión interna**, por lo que la interfaz busca aprovechar el espacio disponible en computadoras utilizadas en las áreas administrativas, de almacenamiento o de atención del minimarket.”

Los diseños presentan una navegación lateral permanente y un área principal destinada a dashboards, tablas, gráficos y operaciones.

- **Diseño Responsivo:**
  - **En Computadora (Desktop):** Se mantiene un menú lateral fijo y el contenido se distribuye utilizando tarjetas, tablas y columnas.
  - **En Tablet:** El contenido puede reducir el número de columnas y reorganizar tarjetas de forma vertical.
  - **En Celular:** Las tarjetas y controles se presentan en una sola columna y el menú lateral puede transformarse en un menú desplegable.

- **Componentes Web:**
  - **Botón Primario:** Fondo azul para acciones principales como “Nuevo producto”, “Registrar operación” o “Lanzar oferta”.
  - **Botón Secundario:** Fondo claro o borde azul para acciones complementarias como editar, ver detalle o cancelar.
  - **Botón de Peligro:** Rojo para acciones relacionadas con eliminación, errores o estados críticos.

- **Tarjetas de Indicadores:**
  - Presentan información resumida como productos totales, stock crítico, productos por vencer y mermas.
  - Incluyen iconos y colores que ayudan a diferenciar cada indicador.
  - Se ubican principalmente en la parte superior de los dashboards.

- **Tablas:**
  - Se utilizan para mostrar productos, lotes, empleados y operaciones.
  - Presentan columnas claramente separadas.
  - Incorporan estados mediante etiquetas de colores como **Activo**, **Crítico**, **Próximo a vencer** o **Vencido**.
  - Pueden incluir buscadores, filtros y paginación.

- **Formularios:**
  - Campos de entrada con bordes simples y etiquetas visibles.
  - Los formularios deben mostrar mensajes claros cuando un dato sea incorrecto.
  - Las acciones de guardar o registrar deben destacar sobre las opciones secundarias.

- **Navegación:**
  - Barra lateral ubicada en el lado izquierdo.
  - Logo de BodeGo ubicado en la parte superior.
  - El módulo seleccionado se diferencia mediante color de fondo o texto destacado.
  - En la parte inferior se muestra información del usuario y la opción para cerrar sesión.

- **Interacción:**
  - Los cambios de estado deben mostrarse inmediatamente después de registrar una operación.
  - Las acciones importantes deben generar mensajes de confirmación.
  - Los elementos interactivos deben cambiar visualmente al pasar el cursor.
  - Los gráficos y tablas deben mantener una lectura sencilla sin sobrecargar la pantalla.

- **Accesibilidad:**
  - Alto contraste entre fondo y texto.
  - Los estados no deben identificarse únicamente mediante colores, sino también mediante texto o iconos.
  - Los botones principales deben tener un tamaño suficiente para ser identificados fácilmente.

---

## 4.2. Information Architecture
### 4.2.1. Organization Systems

La arquitectura de información de BodeGo se organiza mediante sistemas **jerárquicos, secuenciales y matriciales**, permitiendo que cada usuario pueda acceder rápidamente a las funciones correspondientes a su rol.

Los mockups muestran una clara separación entre el Dashboard del Administrador y el Dashboard del Empleado, además de módulos especializados para inventario, vencimientos, compras, ventas, alertas, reportes, empleados y configuración.

- **Sistema Jerárquico:**
  - **Dashboard Administrador:** Primero se muestran indicadores generales como productos totales, stock crítico, productos por vencer y mermas. Después se muestran alertas, movimientos, productos vendidos y lotes próximos a vencer.
  - **Dashboard Empleado:** Primero se muestran ingresos, salidas y mermas del día; posteriormente aparecen las operaciones rápidas y el historial diario.
  - **Inventario:** Se muestra primero el catálogo general y posteriormente el detalle de cada producto.
  - **Vencimientos:** Se priorizan primero los productos vencidos o próximos a vencer.

- **Sistema Secuencial:**
  - **Registro de Producto:** Datos generales → categoría → stock → precio → información del lote → guardar.
  - **Registro de Ingreso:** Seleccionar producto → ingresar cantidad → registrar lote → confirmar.
  - **Registro de Salida:** Seleccionar producto → indicar cantidad → confirmar operación.
  - **Registro de Merma:** Seleccionar producto → cantidad → motivo → confirmar registro.
  - **Gestión de Vencimiento:** Identificar producto → revisar días restantes → seleccionar acción → actualizar inventario.

- **Sistema Matricial:**
  - **Inventario:** Producto + categoría + estado.
  - **Vencimientos:** Producto + lote + fecha de vencimiento + estado.
  - **Operaciones:** Tipo de operación + empleado + fecha + producto.
  - **Empleados:** Nombre + rol + turno + estado.
  - **Reportes:** Fecha + categoría + producto + tipo de movimiento.

- **Esquemas de Categorización:**
  - **Por Rol:** Administrador y Empleado.
  - **Por Función:** Dashboard, Inventario, Vencimientos, Alertas, Reportes, Empleados y Configuración.
  - **Por Estado:** Activo, stock bajo, stock crítico, próximo a vencer y vencido.
  - **Cronológico:** Las operaciones y alertas se presentan comenzando por las más recientes.
  - **Por Prioridad:** Los productos con mayor riesgo de vencimiento o falta de stock aparecen primero.

---

### 4.2.2. Labeling Systems

El sistema de etiquetado de BodeGo utiliza palabras breves y relacionadas directamente con las actividades realizadas en un minimarket. El objetivo es que Administradores y Empleados puedan reconocer cada función sin conocimientos técnicos.

## Etiquetas Principales de Navegación

- **Dashboard:** Resumen del estado actual del minimarket.
- **Inventario:** Gestión y consulta de productos y stock.
- **Vencimientos:** Control de productos y lotes próximos a caducar.
- **Alertas:** Notificaciones sobre situaciones que requieren atención.
- **Reportes:** Visualización de métricas e indicadores del negocio.
- **Empleados:** Gestión del personal y permisos.
- **Configuración:** Ajustes generales del sistema.

## Etiquetas de Acciones

- **“Nuevo producto”**: Registra un producto en el inventario.
- **“Registrar ingreso”**: Añade unidades al stock.
- **“Registrar salida”**: Registra productos que salen del inventario.
- **“Registrar merma”**: Registra productos perdidos, dañados o vencidos.
- **“Consultar inventario”**: Permite revisar productos disponibles.
- **“Lanzar oferta”**: Permite aplicar una estrategia de liquidación.
- **“Ver producto”**: Abre información detallada del producto.
- **“Editar”**: Permite modificar información registrada.

## Etiquetas Contextuales

- **Éxito:** “Operación registrada correctamente”.
- **Stock bajo:** “Quedan pocas unidades disponibles”.
- **Stock crítico:** “Producto con stock crítico”.
- **Próximo a vencer:** “Producto próximo a vencer”.
- **Vencido:** “Producto vencido”.
- **Error:** “No se pudo completar la operación. Inténtalo nuevamente”.

---

### 4.2.3. SEO Tags and Meta Tags

En esta sección se definen los principales **SEO Tags y Meta Tags** utilizados en BodeGo, tanto para la **Landing Page** como para las páginas principales de la **Web Application**.

El objetivo es mejorar la identificación del sitio en los motores de búsqueda y mantener una estructura clara en los títulos y descripciones de cada página. En el caso de las secciones internas de la aplicación, se evita su indexación debido a que contienen información privada del minimarket.

### Landing Page

La Landing Page es la página pública principal de BodeGo y está orientada a presentar la solución, sus beneficios y funcionalidades.

| Tag | Valor |
|---|---|
| **Title** | BodeGo \| Gestión de Inventario para Minimarkets |
| **Description** | BodeGo es una plataforma web que ayuda a la gestion de minimarkets que permite controlar su stock, gestionar productos perecibles, reducir mermas y supervisar sus operaciones diarias. |
| **Keywords** | BodeGo, gestión de inventario, minimarket, control de stock, productos perecibles, control de vencimientos, mermas, inventario digital |
| **Author** | Equipo BodeGo |
| **Robots** | index, follow |
| **Language** | es |
| **Viewport** | width=device-width, initial-scale=1.0 |

**Implementación:**

```html
<title>BodeGo | Gestión de Inventario para Minimarkets</title>

<meta
  name="description"
  content="BodeGo es una plataforma web que ayuda a los minimarkets a controlar su stock, gestionar productos perecibles, reducir mermas y supervisar sus operaciones diarias."
/>

<meta
  name="keywords"
  content="BodeGo, gestión de inventario, minimarket, control de stock, productos perecibles, control de vencimientos, mermas, inventario digital"
/>

<meta name="author" content="Equipo BodeGo" />
<meta name="robots" content="index, follow" />
<meta name="language" content="Spanish" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

---

### Web Application

Las páginas internas de BodeGo están orientadas al uso de Administradores y Empleados. Debido a que contienen información operativa y requieren autenticación, no deben ser indexadas por los motores de búsqueda.

| Página | Title | Description | Keywords | Author | Robots |
|---|---|---|---|---|---|
| **Inicio de Sesión** | Iniciar Sesión \| BodeGo | Accede a BodeGo para gestionar el inventario, productos, vencimientos y operaciones de tu minimarket. | BodeGo, iniciar sesión, inventario minimarket, gestión de stock | Equipo BodeGo | noindex, nofollow |
| **Dashboard Administrador** | Dashboard Administrador \| BodeGo | Visualiza el estado general del inventario, alertas, productos por vencer y operaciones del minimarket. | dashboard, BodeGo, inventario, stock, alertas, vencimientos | Equipo BodeGo | noindex, nofollow |
| **Inventario** | Inventario \| BodeGo | Consulta y administra los productos, categorías, stock y estado del inventario del minimarket. | inventario, productos, stock, BodeGo, minimarket | Equipo BodeGo | noindex, nofollow |
| **Vencimientos** | Control de Vencimientos \| BodeGo | Supervisa lotes y productos próximos a vencer para reducir pérdidas y mejorar la rotación del inventario. | vencimientos, productos perecibles, lotes, mermas, BodeGo | Equipo BodeGo | noindex, nofollow |
| **Alertas** | Centro de Alertas \| BodeGo | Revisa alertas relacionadas con stock crítico, productos próximos a vencer y operaciones del minimarket. | alertas, stock crítico, vencimientos, BodeGo | Equipo BodeGo | noindex, nofollow |
| **Reportes** | Reportes y Analítica \| BodeGo | Consulta reportes e indicadores sobre inventario, movimientos, productos y mermas del minimarket. | reportes, analítica, inventario, mermas, stock, BodeGo | Equipo BodeGo | noindex, nofollow |
| **Empleados** | Gestión de Empleados \| BodeGo | Administra empleados, roles, permisos y actividad operativa dentro del minimarket. | empleados, roles, permisos, personal, BodeGo | Equipo BodeGo | noindex, nofollow |
| **Dashboard Empleado** | Dashboard Empleado \| BodeGo | Consulta operaciones diarias y accede al registro de ingresos, salidas y mermas del inventario. | empleado, operaciones, inventario, ingresos, salidas, mermas | Equipo BodeGo | noindex, nofollow |
| **Operaciones** | Operaciones de Inventario \| BodeGo | Registra ingresos, salidas y mermas de productos para mantener actualizado el stock del minimarket. | operaciones, ingresos, salidas, mermas, stock, BodeGo | Equipo BodeGo | noindex, nofollow |

---

### Consideraciones de Indexación

La **Landing Page** utiliza:

```html
<meta name="robots" content="index, follow" />
```

Esto permite que los motores de búsqueda puedan encontrar y mostrar BodeGo en los resultados de búsqueda.

Por otro lado, las páginas internas de la **Web Application** utilizan:

```html
<meta name="robots" content="noindex, nofollow" />
```

Esto evita que páginas como Dashboard, Inventario, Empleados, Reportes u Operaciones sean indexadas, ya que contienen información interna y requieren autenticación para acceder.

---

### 4.2.4. Searching Systems

El sistema de búsqueda de BodeGo permite localizar rápidamente productos, lotes, empleados y operaciones, reduciendo el tiempo necesario para revisar grandes cantidades de información.

- **Herramientas de Búsqueda:**
  - **Barra de búsqueda:** Disponible principalmente en Inventario y otras pantallas con grandes cantidades de registros.
  - **Filtro por categoría:** Permite visualizar productos pertenecientes a una categoría determinada.
  - **Filtro por estado:** Permite mostrar productos activos, con stock bajo, críticos o vencidos.
  - **Filtro por fechas:** Utilizado en reportes, operaciones y vencimientos.
  - **Filtro por lote:** Facilita la identificación de productos perecibles.

- **Búsqueda en Inventario:**
  - Código del producto.
  - Nombre.
  - Categoría.
  - Estado.
  - Cantidad disponible.

- **Búsqueda en Vencimientos:**
  - Producto.
  - Número de lote.
  - Fecha de vencimiento.
  - Días restantes.
  - Nivel de prioridad.

- **Visualización de Resultados:**
  - Los resultados se presentan principalmente mediante tablas.
  - Los estados importantes se identifican mediante colores y etiquetas.
  - Los resultados pueden organizarse por prioridad o fecha de vencimiento.
  - Cuando no existan coincidencias se puede mostrar: **“No se encontraron resultados con los filtros seleccionados.”**

---

### 4.2.5. Navigation Systems

El sistema de navegación de BodeGo busca reducir la cantidad de pasos necesarios para acceder a las principales funciones del minimarket. La navegación se adapta de acuerdo con los permisos del Administrador y del Empleado.

## Estructura de Navegación del Administrador

La barra lateral puede incluir:

**Dashboard | Inventario | Vencimientos | Alertas | Reportes | Empleados | Configuración**

El Administrador tiene acceso a funciones de supervisión, análisis y configuración.

## Estructura de Navegación del Empleado

La navegación del Empleado debe concentrarse principalmente en las operaciones necesarias durante su jornada:

**Dashboard | Inventario | Operaciones**

Desde el Dashboard también dispone de accesos rápidos para:

- Registrar ingreso.
- Registrar salida.
- Registrar merma.
- Consultar inventario.

## Técnicas de Navegación

- **Menú lateral:** Permite desplazarse entre módulos sin regresar al inicio.
- **Acciones rápidas:** Permiten realizar las operaciones más frecuentes desde el Dashboard.
- **Breadcrumbs o rutas:** Facilitan regresar desde el detalle de un producto hacia el inventario.
- **Paginación:** Utilizada en tablas con gran cantidad de productos, empleados u operaciones.
- **Filtros:** Permiten reducir el contenido sin cambiar de pantalla.

## Estados de Navegación

- **Cargando:** Se muestran indicadores visuales mientras se obtiene la información.
- **Sin resultados:** Se informa cuando una búsqueda o filtro no tiene coincidencias.
- **Error:** Se muestra un mensaje indicando que no fue posible cargar la información.
- **Operación exitosa:** Se confirma inmediatamente después de registrar un ingreso, salida o merma.
- **Alerta crítica:** Los elementos que necesitan atención inmediata se destacan mediante rojo.
- **Advertencia:** Los productos próximos a vencer o con stock bajo se identifican con amarillo o naranja.

---

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe

![WireframeL1](recursos/imagenes/Landing1.png)
---
![WireframeL2](recursos/imagenes/Landing2.png)
---
![WireframeL3](recursos/imagenes/Landing3.png)
---
![WireframeL4](recursos/imagenes/Landing4.png)
---
![WireframeL5](recursos/imagenes/Landing5.png)
---

### 4.3.2. Landing Page Mock-ups

![LPMock-Up1](recursos/imagenes/LandingPage-mockup1.jpg)
---

![LPMock-Up2](recursos/imagenes/LandingPage-mockup2.jpg)
---

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes

![Wireframe 1](recursos/imagenes/WF1.png)

---

![Wireframe 2](recursos/imagenes/WF2.png)

---

![Wireframe 3](recursos/imagenes/WF3.png)

---

![Wireframe 4](recursos/imagenes/WF4.png)

---

![Wireframe 5](recursos/imagenes/WF5.png)

---

![Wireframe 6](recursos/imagenes/WF6.png)

---

![Wireframe 7](recursos/imagenes/WF7.png)

---

![Wireframe 8](recursos/imagenes/WF8.png)

---

![Wireframe 9](recursos/imagenes/WF9.png)

---

![Wireframe 10](recursos/imagenes/WF10.png)

---

![Wireframe 11](recursos/imagenes/WF11.png)

---

![Wireframe 12](recursos/imagenes/WF12.png)

---

![Wireframe 13](recursos/imagenes/WF13.png)

---

![Wireframe 14](recursos/imagenes/WF14.png)

---
enlace: https://www.figma.com/design/lkkyQ42TCu70ZypY4hiuMi/Figma-Proxy?node-id=4-2&t=ZKhGhyVBP4tT2C8g-1

### 4.4.2. Web Applications Wireflow Diagrams
![Wireflow 0](recursos/imagenes/Wireflow_App.png)

---

enlace: https://www.figma.com/design/lkkyQ42TCu70ZypY4hiuMi/Figma-Proxy?node-id=9-8766&t=ZKhGhyVBP4tT2C8g-1

---

### 4.4.3. Web Applications Mock-ups
![Mockup App 1](recursos/imagenes/Mockup-App1.png)

---

![Mockup App 2](recursos/imagenes/Mockup-App2.png)

---

![Mockup App 3](recursos/imagenes/Mockup-App3.png)

---

![Mockup App 4](recursos/imagenes/Mockup-App4.png)

---

![Mockup App 5](recursos/imagenes/Mockup-App5.png)

---

![Mockup App 6](recursos/imagenes/Mockup-App6.png)

---

![Mockup App 7](recursos/imagenes/Mockup-App7.png)

---

![Mockup App 8](recursos/imagenes/Mockup-App8.png)

---

![Mockup App 9](recursos/imagenes/Mockup-App9.png)

---

![Mockup App 10](recursos/imagenes/Mockup-App10.png)

---

![Mockup App 11](recursos/imagenes/Mockup-App11.png)

---

![Mockup App 12](recursos/imagenes/Mockup-App12.png)

---

![Mockup App 13](recursos/imagenes/Mockup-App13.png)

---

![Mockup App 14](recursos/imagenes/Mockup-App14.png)

---
[Enlace de Figma](https://www.figma.com/design/lkkyQ42TCu70ZypY4hiuMi/Figma-Proxy?node-id=4-2&t=ZKhGhyVBP4tT2C8g-1)
---

### 4.4.4. Web Applications User Flow Diagrams

## LEYENDA

![Leyenda Flow Diagram](recursos/imagenes/LEYENDA.jpg)

## FLUJO DE USUARIO

![Flujo de Usuario Flow Diagram](recursos/imagenes/FLUJO%20DE%20USUARIO.jpg)

## FLUJO DE ADMINISTRADOR

![Flujo de Administrador Flow Diagram](recursos/imagenes/FLUJO%20DE%20ADMINISTRADOR.jpg)

## FLUJO DE EMPLEADO

![Flujo de Empleado Flow Diagram](recursos/imagenes/FLUJO%20DE%20EMPLEADO.jpg)

---

## 4.5. Web Applications Prototyping

![WireflowApp](recursos/imagenes/wireflowapp45.jpg)

Enlance de Figma: https://www.figma.com/design/lkkyQ42TCu70ZypY4hiuMi/Figma-Proxy?node-id=4-2&t=ZKhGhyVBP4tT2C8g-1

![PrototypingVideo](recursos/imagenes/prototypingvideo.jpg)

Enlace del video: https://drive.google.com/drive/folders/1l4HlhDxX7ZoHEbH96fOAfosutOivB_S6?usp=sharing

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Design-Level EventStorming
![Estructura / Captura 1](recursos/imagenes/es1.png)

---

![Estructura / Captura 2](recursos/imagenes/es2.png)

---

![Estructura / Captura 3](recursos/imagenes/es3.png)

---

![Estructura / Captura 4](recursos/imagenes/es4.png)

---

![Estructura / Captura 5](recursos/imagenes/es5.png)

---

![Estructura / Captura 6](recursos/imagenes/es6.png)

---

![Estructura / Captura 7](recursos/imagenes/es7.png)

---

![Estructura / Captura 8](recursos/imagenes/es8.png)

---

![Estructura / Captura 9](recursos/imagenes/es9.png)

---

![Estructura / Captura 9](recursos/imagenes/es91.png)

---

![Estructura / Captura 9](recursos/imagenes/es92.png)

---

![Estructura / Captura 9](recursos/imagenes/es93.png)

---
[Nuestro link del miro](https://miro.com/app/board/uXjVHm55KfI=/)
---

### 4.6.2. Software Architecture Context Diagram
![Context](recursos/imagenes/SystemContext.png)
### 4.6.3. Software Architecture Container Diagrams
![Container](recursos/imagenes/Containers.png)

### 4.6.4. Software Architecture Components Diagrams
![Components-Worker](recursos/imagenes/Components-Worker.png)

---

![Components-API](recursos/imagenes/Components-API.png)
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
![Class-Diagram](recursos/imagenes/DiagramaAppWeb.png)

- **Conteos Físicos BC:**

![DiagramaDB / BC1](recursos/imagenes/conteosfisicos-appweb.jpg)

---

- **Movimientos de Inventario BC:**

![DiagramaDB / BC2](recursos/imagenes/movimientos-de-inventario-BC.jpg)

---

- **Catálogo e Inventario BC:**

![DiagramaDB / BC3](recursos/imagenes/Catalogo-e-inventario-BC.jpg)

---

- **Monitoreo y Alertas BC:**

![DiagramaDB / BC4](recursos/imagenes/Monitoreo-y-Alertas-BC.jpg)

---

- **Reportes y Dashboard BC:**

![DiagramaDB / BC5](recursos/imagenes/Reportes-y-Dashboard-BC.jpg)
  
---

## 4.8. Database Design
Se presenta el diseño de la base de datos relacional que permitirá graficar la información para los objetos de cada Bounded Context identificados en la aplicación BodeGo.

### 4.8.1. Database Diagrams
El siguiente diagrama de base de datos Entity-Relationship contiene las tablas, columnas y tipos de datos que establecen las relaciones entre las entidades del sistema.
![Diagrama / Diseño 1](recursos/imagenes/d1.png)

---

![Diagrama / Diseño 2](recursos/imagenes/d2.png)

---

![Diagrama / Diseño 3](recursos/imagenes/d3.png)

---

![Diagrama / Diseño 4](recursos/imagenes/d4.png)

---

![Diagrama / Diseño 5](recursos/imagenes/d5.png)

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
Para el desarrollo de BodeGo se establecerán un conjunto de herramientas que permitan mantener la consistencia del proyecto durante su ciclo de vida. Estas configuraciones permitirán que los integrantes del equipo trabajen bajo una misma estructura para el control de versiones, configuración del entorno de desarrollo y posterior despliegue de la aplicación.

### 5.1.1. Software Development Environment Configuration
## . Project Management

- **Discord:** Una herramienta de comunicación y coordinación del equipo. Permite organizar conversaciones por canales, realizar reuniones de voz, compartir avances, resolver dudas y coordinar las actividades relacionadas con el desarrollo de BodeGo.
---
![Imagen de la entrevista](recursos/imagenes/dc1.jpg)
---
[link de inicio sesion](https://discord.com/)

---

imagen para mostrar evidencia de uso: 

![imagen](recursos/imagenes/dc2.jpg)

## . Requirement Management

- **Miro:** Se utilizará como herramienta colaborativa para la gestión y análisis de requisitos de BodeGo. Permitirá organizar visualmente información obtenida durante la investigación, como User Personas, Empathy Maps, User Journey Maps e Impact Mapping.
---
![Imagen de la entrevista](recursos/imagenes/miro.png)

---

[link de inicio de sesion](https://miro.com/es/)

- **UXPressia:** Se utilizará para elaborar y documentar artefactos relacionados con la experiencia de usuario, como User Personas y User Journey Maps, permitiendo representar las características, necesidades, objetivos y experiencias de los segmentos de usuarios de BodeGo.
---
![Imagen de la entrevista](recursos/imagenes/ux.png)
---

[link de inicio de sesion](https://uxpressia.com/)

- **Structurizr:** Se utilizará para modelar y documentar la arquitectura de software de BodeGo mediante diagramas basados en el modelo C4. Permitirá representar la estructura general del sistema, sus principales contenedores, componentes y relaciones.
---
![Imagen de la entrevista](recursos/imagenes/struc.png)
---

## . Product UX/UI Design

- **Figma:** Una herramienta de colaboración que facilita el desarrollo conjunto de wireframes y mockups.
---
![Imagen de la entrevista](recursos/imagenes/figma.png)
---
[link de inicio de sesion](https://www.figma.com/es-la/)

- **LucidChart:** Una herramienta colaborativa que posibilita la creación conjunta de wireframes flow y mockups flow.
---
![Imagen de la entrevista](recursos/imagenes/lucid.png)
---
[link de inicio de sesion](https://lucid.co/es/lucidchart)

## . Software Development

- **HTML5:** Es un lenguaje de etiquetado utilizado para crear la estructura de una página web. Se empleará para incluir componentes como texto, imágenes, enlaces, botones y videos.
---
![Imagen de la entrevista](recursos/imagenes/html.png)
---
[informacion relacionada](https://www.esic.edu/rethink/tecnologia/html5-que-es-caracteristicas-y-como-funciona-c#:~:text=El%20HTML5%20es%20un%20est%C3%A1ndar,%2C%20estilo%20de%20letra%2C%20etc.)

- **CSS:** Es un lenguaje de diseño gráfico utilizado para dar formato y estilo a la presentación de los documentos HTML.
---
![Imagen de la entrevista](recursos/imagenes/css.png)
---
[informacion relacionada](https://developer.mozilla.org/es/docs/Web/CSS)

- **JavaScript:** Es un lenguaje de programación dinámico orientado a objetos que se utilizará para implementar funcionalidades e interactividad en la aplicación web.
---
![Imagen de la entrevista](recursos/imagenes/js.png)
---
[informacion relacionada](https://developer.mozilla.org/es/docs/Web/JavaScript)

- **WebStorm** Un entorno de desarrollo integrado (IDE) que emplearemos para trabajar con JavaScript.
---
![Imagen de la entrevista](recursos/imagenes/wsuwu.png)
---
[link de descarga](https://www.jetbrains.com/es-es/idea/download/?section=windows)

## . Software Testing

- **Lenguaje Gherkin:** Es un Lenguaje Específico de Dominio (DSL) diseñado para describir el comportamiento esperado del sistema mediante escenarios comprensibles tanto para desarrolladores como para otros integrantes del equipo.

## . Software Documentation

- **GitHub:** Es una plataforma utilizada para el alojamiento y control de versiones del código fuente de un proyecto. Facilita el trabajo colaborativo entre los integrantes del equipo y permite mantener un historial de los cambios realizados.
---
![Imagen de la entrevista](recursos/imagenes/gh6.jpg)
---


## . Software Deployment

- **GitHub Pages:** Es una plataforma que permite realizar despliegues de aplicaciones web directamente desde un repositorio de GitHub.
---
![Imagen de la entrevista](recursos/imagenes/gh7.png)
---
[link de inicio](https://github.com/?locale=es-419)
---
[link de descarga](https://github.com/apps/desktop?locale=es-419)
---
Nuestro repositorio de documentación: https://github.com/SirEthan04/Proxy_App_Web
---
Nuestro repositorio de landingpage: https://github.com/SirEthan04/Proxy_App_Web_LandingPage
---
Nuestro repositorio de frontend: https://github.com/SirEthan04/Proxy_Web_App_Front-end
---
Nuestro repositorio de web aplication: https://github.com/SirEthan04/Proxy_Web_App_Back-end
---
### 5.1.2. Source Code Management
---

![Estructura / Captura 9](recursos/imagenes/gh9.jpg)

---
## GitFlow Implementation
Para organizar el trabajo colaborativo del equipo se utilizará **GitFlow** como modelo de ramificación, empleando Git para el control de versiones.
Este modelo permitirá separar el código estable de BodeGo de las funcionalidades que se encuentren en desarrollo, facilitando que diferentes integrantes del equipo puedan trabajar simultáneamente en módulos como inventario, productos, lotes, mermas, ofertas, usuarios y reportes.

### Main Branch

La rama main será la rama principal y contendrá las versiones estables de BodeGo que se encuentren preparadas para producción.
No se desarrollarán funcionalidades directamente sobre esta rama. Los cambios llegarán a main mediante la integración de ramas release y hotfix.

## Develop Branch

La rama develop contendrá los cambios más recientes del proyecto que serán incluidos en próximas versiones de BodeGo.
Funcionará como punto de integración de las diferentes funcionalidades desarrolladas por el equipo. Antes de que una versión sea incorporada a main, las nuevas características serán integradas y verificadas previamente en develop.

## Feature Branch

Las ramas feature serán utilizadas para desarrollar nuevas funcionalidades de **BodeGo** de forma independiente.
Cada característica deberá contar con su propia rama, permitiendo que los integrantes del equipo trabajen en diferentes módulos sin modificar directamente la rama develop.

## Release Branch

Las ramas release serán utilizadas cuando las funcionalidades previstas para una nueva versión de BodeGo ya hayan sido integradas en develop.
Su objetivo será preparar una versión antes de pasarla a producción. Durante esta etapa podrán realizarse pruebas, ajustes menores y correcciones de errores sin impedir que el equipo continúe desarrollando nuevas características en develop.

## Hotfix Branch

Las ramas hotfix serán utilizadas para corregir errores importantes encontrados en una versión de BodeGo que ya se encuentre en producción.
Estas ramas permitirán solucionar rápidamente un problema sin interrumpir el desarrollo de nuevas funcionalidades que continúe realizándose en develop.

## Support Branch

Para la primera etapa del desarrollo de BodeGo no se utilizarán ramas supoort, debido a que el proyecto no contempla inicialmente el mantenimiento simultáneo de múltiples versiones antiguas del producto.
En caso de que en el futuro BodeGo deba mantener diferentes versiones en producción, podrán incorporarse ramas de soporte específicas.

## Conventional Commits

Para mantener un historial de cambios claro y comprensible, los mensajes de los commits del proyecto BodeGo seguirán la especificación Conventional Commits.

Esta convención permitirá identificar rápidamente el propósito de cada modificación realizada por los integrantes del equipo.¿

La estructura general será: git commit -m <type>[optional scope]: <title>“ -m “<description” 

### Tipos de Conventional Commits
- feat: Incorporación de una nueva funcionalidad.
- fix: Corrección de un error. 
- docs: Cambios en documentación. 
- style: Cambios de formato que no modifican el funcionamiento. 
- refactor: Reestructuración del código sin agregar funcionalidades ni corregir errores. 
- test: Adición o modificación de pruebas. 
- chore: Tareas de mantenimiento o configuración. 
- perf: Mejoras relacionadas con el rendimiento. 

### 5.1.3. Source Code Style Guide & Conventions
Como norma general, todo el código desarrollado para BodeGo deberá utilizar nombres en inglés. Esto incluye variables, funciones, métodos, clases, archivos, atributos y demás elementos utilizados durante el desarrollo.

La finalidad de estas reglas es mantener un código ordenado y fácil de entender para todos los integrantes del equipo.

---

HTML

Use Lowercase Element Names

Los elementos HTML se escribirán en minúsculas.

```html
<section>
    <h2>Inventory</h2>
    <p>Available products</p>
</section>
```

Close All HTML Elements

Todos los elementos HTML que necesiten una etiqueta de cierre deberán cerrarse correctamente.

```html
<section>
    <h2>Inventory</h2>
    <p>Available products</p>
</section>
```

Use Lowercase Attribute Names

Los atributos HTML también se escribirán en minúsculas.

```html
<a href="/inventory">View inventory</a>
```

Use Alternative Text for Images

Las imágenes utilizadas en BodeGo deberán incluir el atributo alt para indicar brevemente su contenido.

```html
<img
    src="assets/bodego-logo.png"
    alt="BodeGo logo">
```

Use Semantic HTML Elements

Cuando sea posible, se utilizarán etiquetas semánticas para organizar mejor las páginas.
Algunas de las etiquetas que se utilizarán son:

```text
header
nav
main
section
article
footer
```

Spaces and Equal Signs

No se utilizarán espacios innecesarios alrededor del signo igual en los atributos.

Correcto:

```html
<link rel="stylesheet" href="styles.css">
```

Incorrecto:

```html
<link rel = "stylesheet" href = "styles.css">
```


CSS

ID and Class Naming

Las clases e identificadores CSS deberán utilizar nombres claros y relacionados con el elemento que representan.

```css
#inventory {
}

#dashboard {
}

.product-card {
}

.stock-alert {
}
```
Se evitarán nombres poco descriptivos como:

```css
.box1 {
}

.element2 {
}
```

ID and Class Name Style

Para los nombres de clases e identificadores CSS se utilizará kebab-case.

```css
.product-card {
}

.inventory-table {
}

.stock-alert {
}
```

Shorthand Properties

Cuando sea posible, se utilizarán propiedades abreviadas para evitar código innecesario.

En lugar de:

```css
.product-card {
    margin-top: 16px;
    margin-right: 16px;
    margin-bottom: 16px;
    margin-left: 16px;
}
```

Se utilizará:

```css
.product-card {
    margin: 16px;
}
```

Declaration Order

Las propiedades CSS deberán mantenerse ordenadas para facilitar la lectura del código.

```css
.product-card {
    background: white;
    border: 1px solid #e5e7eb;
    border-radius: 8px;
    display: flex;
    margin: 16px;
    padding: 16px;
    text-align: left;
}
```

JavaScript

Use Expanded Syntax

El código JavaScript deberá escribirse de manera clara y ordenada, colocando cada instrucción en una línea diferente cuando sea necesario.

```javascript
function calculateAvailableStock() {
    console.log("Calculating available stock");
}
```
Variable Naming

Las variables utilizarán camelCase y deberán tener nombres descriptivos en inglés.

```javascript
let availableStock = 20;
let productName = "Milk";
let expirationDate = "2026-10-20";
let criticalStockThreshold = 5;
```

Se evitarán nombres poco claros como:

```javascript
let x;
let data1;
let thing;
```

Declaring Variables

Se utilizará const cuando el valor no necesite cambiar.

```javascript
const productId = 10;
const productName = "Milk";
```

Se utilizará let cuando el valor pueda modificarse.

```javascript
let availableStock = 20;

availableStock = availableStock - 1;
```

Function Naming

Las funciones utilizarán camelCase y sus nombres deberán indicar claramente la acción que realizan.

Ejemplos:

```javascript
function registerProduct() {
}
```

```javascript
function calculateStock() {
}
```

```javascript
function showExpirationAlert() {
}
```

Constants

Las constantes globales podrán utilizar UPPER_SNAKE_CASE.

Ejemplos:

```javascript
const MAX_LOGIN_ATTEMPTS = 5;
const DEFAULT_STOCK_THRESHOLD = 10;
```
C#

PascalCase

Las clases utilizarán PascalCase.

```C#
public class ProductService
{
}
public class InventoryService
{
}
public class BatchService
{
}
```
camelCase

Las variables locales, parámetros y atributos utilizarán camelCase.

```C#
private int productId;
private string productName;
Clear Comments
```

Los comentarios se utilizarán cuando ayuden a entender partes del código que los demás integrantes del grupo no comprendan.

```C#
// Checks whether the batch is close to its expiration date.
public bool IsNearExpiration(DateTime expirationDate)
{
    return expirationDate.Date < DateTime.Today.AddDays(7);
}

```

---

Single Responsibility

Cada clase deberá encargarse principalmente de una responsabilidad.

- ProductService se encargará de las operaciones relacionadas con productos.
- InventoryService se encargará de las operaciones relacionadas con inventario.
- BatchService se encargará de la gestión de lotes.
- WastageService se encargará del registro y gestión de mermas.

Gherkin

Los escenarios y criterios de aceptación de BodeGo deberán seguir una estructura uniforme y utilizar nombres en inglés.

escriptive and Concise Titles for Scenarios

Los escenarios deberán tener títulos claros que permitan entender rápidamente qué comportamiento se está evaluando.

```gherkin
Feature: User authentication

Scenario: Successful login
    Given the user has an active account
    When the user enters valid credentials
    Then the system should grant access according to the user role
```

Follow the Given-When-Then Structure Consistently

Los escenarios deberán utilizar la estructura Given, When y Then.

- Given: representa la condición inicial.
- When: representa la acción realizada.
- Then: representa el resultado esperado.


Focus on Business-Readable Language

Los escenarios deberán utilizar un lenguaje relacionado con las actividades del minimarket y evitar detalles técnicos de programación.

```gherkin
Scenario: Register damaged product as wastage

    Given the employee finds a damaged product
    When the employee registers the product as wastage
    Then the stock should be updated
    And the wastage should be recorded
```
Add Comments When Necessary

Se podrán agregar comentarios cuando sea necesario explicar el propósito de un escenario.

```gherkin
# This scenario checks the registration of expired products as wastage.

Scenario: Register expired product as wastage

    Given a product batch has expired
    When the employee registers the expired units
    Then the units should be recorded as wastage
    And the stock should be updated
```

### 5.1.4. Software Deployment Configuration

En esta sección se describe la configuración técnica prevista para la publicación de los componentes de **BodeGo desarrollados en el curso Aplicaciones Web**, considerando los repositorios de código fuente, los procesos de compilación, los entornos de ejecución y la comunicación entre el Frontend y el Backend.

El ecosistema de BodeGo se compone de tres productos de software diferenciados:

1. **Landing Page y Documentación del Proyecto:** la Landing Page está desarrollada con **HTML, CSS y JavaScript**, por lo que puede publicarse mediante un servicio de alojamiento estático. La documentación del proyecto se administra en **GitHub**, mediante el repositorio `Proxy_App_Web`, que incluye una dirección de GitHub Pages para su consulta.

2. **Frontend Web Application (Web App):** desarrollada con **Vue 3, Vite, Pinia y PrimeVue**. El proyecto dispone de configuración para **Firebase Hosting**, permitiendo publicar los archivos generados durante la compilación y utilizar reglas de redirección para mantener la navegación de la Single Page Application (SPA).

3. **Backend REST API:** desarrollado con **ASP.NET Core (.NET 10), C# y Entity Framework Core**, utilizando **MySQL** como sistema de persistencia. El Backend organiza sus funcionalidades en los bounded contexts Inventory, Operations, Commercial, Monitoring, Reporting e IAM, y utiliza **OpenAPI con Scalar** para documentar sus servicios durante el desarrollo.

**Configuración técnica del despliegue**

| Componente | Plataforma / Tecnología | Configuración |
|---|---|---|
| Landing Page | HTML, CSS, JavaScript y alojamiento estático | Publicación de `index.html` y sus recursos CSS, JavaScript e imágenes. |
| Documentación | GitHub y GitHub Pages | Publicación del informe y sus recursos desde el repositorio del curso. |
| Frontend Web | Vue 3, Vite y Firebase Hosting | `npm run build` genera el directorio `dist`, utilizado como carpeta pública por Firebase Hosting. |
| Backend REST | ASP.NET Core, C# y .NET 10 | Compilación de producción mediante `dotnet publish -c Release` y ejecución en un entorno compatible con .NET. |
| Base de datos | MySQL y Entity Framework Core | Configuración de la cadena de conexión mediante variables de entorno o mecanismos seguros. |

Para el desarrollo local, el Frontend utiliza **Vite en `http://localhost:5174`**, mientras que el Backend ASP.NET Core dispone de un perfil HTTP en **`http://localhost:5281`**. La comunicación entre ambos se configura mediante `VITE_API_BASE_URL` y la política CORS del servidor.

Para el despliegue de producción, se debe establecer la URL pública del Backend, configurar el acceso seguro a MySQL y autorizar el dominio del Frontend. Asimismo, se deben comprobar las rutas internas de Vue, las solicitudes HTTPS y el funcionamiento de los servicios REST.

**Repositorios del proyecto:**

- Documentación: https://github.com/SirEthan04/Proxy_App_Web
- Frontend: https://github.com/SirEthan04/Proxy_Web_App_Front-end
- Backend: https://github.com/SirEthan04/Proxy_Web_App_Back-end

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
## Sprint 1 - Desarrollo de la Landing Page de BodeGo
Durante el Sprint 1, el equipo se enfocó en desarrollar la primera versión funcional de la Landing Page de BodeGo.
El objetivo fue transformar los wireframes y diseños realizados previamente en una página web funcional que permitiera presentar de manera clara la solución propuesta para los minimarkets.

#### 5.2.1.1. Sprint Planning 1

El print Planning permitió organizar las actividades que serían desarrolladas durante el Sprint 1.
En esta reunión se definió como objetivo principal implementar la Landing Page de BodeGo.

| Sprint # | Sprint 1 |
|---|---|
| **Sprint Planning Background** | El Sprint tiene como objetivo implementar la primera versión funcional de la Landing Page de BodeGo a partir de los wireframes y diseños elaborados, priorizando la presentación del producto y el contacto con potenciales usuarios. |
| **Date** | 17-09-2026 |
| **Time** | 5:00 pm |
| **Location** | Discord |
| **Prepared By** | Equipo de desarrollo BodeGo |
| **Attendees (to planning meeting)** | Dany / Mateo / Jhorch / Johan / Diego |
| **Sprint 0 Review Summary** | No existe un sprint previo, ya que Sprint 1 constituye el inicio del desarrollo incremental del producto. |
| **Sprint 0 Retrospective Summary** | No existe un sprint previo ni una retrospectiva anterior. |
| **Sprint Goal & User Stories** | US01 – Visualización de la propuesta de valor (2 SP); US02 – Consulta de beneficios del producto (2 SP); US03 – Presentación informativa de funcionalidades (3 SP); US04 – Explicación de los pasos de uso de BodeGo (2 SP); US05 – Formulario de contacto comercial (4 SP). |
| **Sprint 1 Goal** | Desarrollar una Landing Page funcional y responsive que presente la propuesta de valor de BodeGo, sus beneficios, funcionalidades y pasos de uso, e incluya un formulario de contacto para potenciales usuarios. |
| **Sprint 1 Velocity** | No disponible como velocidad histórica, al tratarse del primer sprint. Capacidad planificada: **13 Story Points**. |
| **Sum of Story Points** | **13 Story Points** |

#### 5.2.1.2. Aspect Leaders and Collaborators

Durante el Sprint 1, el equipo de BodeGo distribuyó las responsabilidades necesarias para desarrollar la primera versión funcional de la Landing Page. Se definieron responsables principales y colaboradores para la estructura y navegación, la presentación de beneficios y funcionalidades, la sección de contacto y la adaptación de la interfaz a distintos tamaños de pantalla.

| Team Member (Last Name, First Name) | GitHub Username | Landing Page Structure & Navigation | Product Benefits & Impact | Product Features & Explanation | Contact & Footer Section | Responsive Design |
|---|---|:---:|:---:|:---:|:---:|:---:|
| Chavez Sandoval, Dany Yohel | Danysss-cmd | L | C | C | - | C |
| Caldas Bravo, Mateo | Ethan.Matt | C | L | C | - | C |
| Blanco Medina, Jhorch Jhoseff | Bleim-154 | C | C | L | - | C |
| Saravia Hiso, Johan Álvaro | yowuan | - | C | C | L | C |
| Rojas Huaranga, Diego Rances | Diego27-16 | C | C | C | C | L |

#### 5.2.1.3. Sprint Backlog 1

Durante el Sprint 1, las actividades estuvieron orientadas al desarrollo de la primera versión funcional de la Landing Page de BodeGo.

El objetivo principal fue transformar los wireframes y mockups previamente diseñados en una interfaz web funcional que permita comunicar la propuesta de valor del producto, presentar sus principales funcionalidades y captar potenciales usuarios interesados en la solución.

![Evidencia Sprint Backlog n1](https://github.com/SirEthan04/Proxy_Open_Source/blob/main/Recursos/images/EvidenciaSprintBacklog%20N1.jpg)
Enlace: https://trello.com/invite/b/6aac64ebaf51e9bfb4c107de/ATTI7980c4d39c19509f8439a763ed2f3081F674FEDD/bodego

---

| **User Story ID** | **Story Title** | **Task ID** | **Task Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
|---|---|---|---|---|---:|---|---|
| US01 | Visualización de la propuesta de valor | TSK001 | Create Landing Page structure | Preparar la estructura HTML inicial y los estilos generales de la Landing Page a partir de los wireframes del producto. | 2 | Dany | Hecho |
| US01 | Visualización de la propuesta de valor | TSK002 | Implement navigation bar | Desarrollar la barra de navegación con el logotipo, los enlaces a las secciones informativas y el botón principal de acción. | 2 | Dany | Hecho |
| US01 | Visualización de la propuesta de valor | TSK003 | Implement hero section | Implementar el título, la propuesta de valor, la imagen principal y los botones de acción del encabezado de BodeGo. | 3 | Dany | Hecho |
| US02 | Consulta de beneficios del producto | TSK004 | Implement benefits section | Implementar la sección de beneficios destacando la organización del inventario, la reducción de pérdidas y la mejora de las actividades operativas. | 4 | Mateo | Hecho |
| US02 | Consulta de beneficios del producto | TSK005 | Implement impact section | Incorporar los mensajes y recursos visuales que explican el impacto esperado de BodeGo en la gestión de un minimarket. | 2 | Mateo | Hecho |
| US03 | Presentación informativa de funcionalidades | TSK006 | Implement features section | Desarrollar las tarjetas informativas que presentan las funcionalidades de inventario, operaciones, monitoreo y reportes. | 3 | Yorch | Hecho |
| US03 | Presentación informativa de funcionalidades | TSK007 | Adapt features section to responsive layouts | Ajustar la disposición y legibilidad de las tarjetas de funcionalidades para pantallas de escritorio, tablet y móvil. | 2 | Diego | Hecho |
| US04 | Explicación de los pasos de uso de BodeGo | TSK008 | Implement how it works section | Desarrollar la sección «Cómo funciona» con los pasos generales para registrar productos, controlar inventario y consultar información operativa. | 3 | Yorch | Hecho |
| US04 | Explicación de los pasos de uso de BodeGo | TSK009 | Adapt how it works section to responsive layouts | Ajustar la presentación de pasos, textos y elementos visuales de «Cómo funciona» para dispositivos de distintos tamaños. | 2 | Diego | Hecho |
| US05 | Formulario de contacto comercial | TSK010 | Implement contact form and validation | Crear el formulario de contacto comercial e incorporar las validaciones de campos obligatorios para solicitar información sobre BodeGo. | 4 | Johan | Hecho |
| US05 | Formulario de contacto comercial | TSK011 | Implement contact details and footer | Desarrollar el pie de página con enlaces informativos, referencias del producto y datos de contacto para los visitantes. | 2 | Johan | Hecho |

---

#### 5.2.1.4. Development Evidence for Sprint Review

---

| Repository              | Branch                    | Commit ID | Commit Message                          | Commit Message Body                                                            | Committed on |
| ----------------------- | ------------------------- | --------- | --------------------------------------- | ------------------------------------------------------------------------------ | ------------ |
| Danysss-cmd/Landing Page Repository | feature/hero-section      | 371ee21   | feat: improve hero section design       | Implementación y mejora del diseño de la sección principal de la Landing Page. | 17/09/2026   |
| SirEthan04/Landing Page Repository | feature/value-proposition | fa49632   | feat: improve value proposition section | Desarrollo de la sección de beneficios y propuesta de valor del producto.      | 17/09/2026   |
| Bleim-154/Landing Page Repository | feature/solutions-section | 003f372   | feat: improve solutions section         | Implementación de la sección de soluciones y funcionalidades principales.      | 17/09/2026   |
| SirEthan04//Landing Page Repository | feature/impact-section    | 7182b63   | feat: improve impact section            | Desarrollo de la sección de impacto mostrando beneficios del producto.         | 17/09/2026   |
| yowuan/Landing Page Repository | feature/contact-form      | e281064   | feat: improve contact form              | Implementación del formulario de contacto comercial.                           | 17/09/2026   |
| Dany27-16/Landing Page Repository | feature/footer            | dfb92c0   | feat: improve footer section            | Implementación del footer con información general y enlaces.                   | 17/09/2026   |

---

#### 5.2.1.5. Execution Evidence for Sprint Review

---

![Estructura / Captura 9](recursos/imagenes/nl1.jpg)

---

![Estructura / Captura 9](recursos/imagenes/nl2.jpeg)

---
![Estructura / Captura 9](recursos/imagenes/nl3.jpeg)

---
![Estructura / Captura 9](recursos/imagenes/nl4.jpeg)

---
![Estructura / Captura 9](recursos/imagenes/nl5.jpeg)

---
![Estructura / Captura 9](recursos/imagenes/nl6.jpeg)

---
![Estructura / Captura 9](recursos/imagenes/nl7.jpeg)

---
![Estructura / Captura 9](recursos/imagenes/nl8.jpeg)

---
![Estructura / Captura 9](recursos/imagenes/nl9.jpeg)

---
![Estructura / Captura 9](recursos/imagenes/nl10.jpeg)

---
![Estructura / Captura 9](recursos/imagenes/nl11.jpeg)

---

Landing Page Desplegada: https://sirethan04.github.io/Proxy_App_Web_LandingPage/

---

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
Se ha omitido la sección de la aplicación web debido a que solo se ha desarrollado la Landing Page. Se ofrecerá más información sobre la aplicación en
una etapa posterior del desarrollo.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
Se ha omitido la sección de la aplicación web debido a que solo se ha desarrollado la Landing Page. Se ofrecerá más información sobre la aplicación en
una etapa posterior del desarrollo.

#### 5.2.1.8. Team Collaboration Insights during Sprint
---

![Estructura / Captura 9](recursos/imagenes/gh8.png)

---

### 5.2.2. Sprint 2

## Sprint 2 - Desarrollo del Frontend Web de BodeGo

Durante el Sprint 2, el equipo se enfocó en desarrollar la primera versión funcional del Frontend Web de BodeGo.

El objetivo fue implementar las principales vistas de la aplicación, permitiendo la navegación entre módulos, consulta del inventario, visualización de productos, alertas, reportes y demás funcionalidades definidas para esta etapa.

#### 5.2.2.1. Sprint Planning 2

El Sprint Planning permitió organizar las actividades correspondientes al desarrollo inicial del Frontend Web de BodeGo. Durante la reunión se seleccionaron las historias US06–US15, orientadas a implementar las vistas y funcionalidades principales de la aplicación, con una estimación total de **36 Story Points** de acuerdo con el Product Backlog actualizado.

| **Sprint #** | **Sprint 2** |
|---|---|
| **Sprint Planning Background** | El Sprint tiene como objetivo desarrollar la primera versión funcional del Frontend Web de BodeGo utilizando Vue 3, implementando las interfaces y la navegación necesarias para consultar y gestionar visualmente la información del negocio. |
| **Date** | 04-10-2026 |
| **Time** | 2:00 pm |
| **Location** | Discord |
| **Prepared By** | Equipo de desarrollo BodeGo |
| **Attendees (to planning meeting)** | Dany / Mateo / Jhorch / Johan / Diego |
| **Sprint 1 Review Summary** | Se desarrolló la primera versión funcional de la Landing Page de BodeGo, incorporando la propuesta de valor, los beneficios, las funcionalidades principales, la explicación de uso y el formulario de contacto comercial. |
| **Sprint 1 Retrospective Summary** | Se identificó la necesidad de mantener la identidad visual de BodeGo, mejorar la organización de los componentes y continuar con el desarrollo de interfaces adaptables a diferentes dispositivos. |
| **Sprint Goal & User Stories** | US06 – Visualización del Dashboard operativo (5 SP); US07 – Navegación entre módulos autorizados (4 SP); US08 – Consulta visual del inventario (3 SP); US09 – Consulta visual del detalle de producto (3 SP); US10 – Consulta visual de operaciones de inventario (3 SP); US11 – Búsqueda y filtrado de productos (4 SP); US12 – Visualización de alertas de inventario (3 SP); US13 – Visualización de reportes operativos (4 SP); US14 – Registro visual de productos con validaciones (4 SP); US15 – Consulta visual de documentos comerciales (3 SP). |
| **Sprint 2 Goal** | Desarrollar la primera versión funcional del Frontend Web de BodeGo, implementando interfaces organizadas y responsive para el Dashboard, inventario, productos, operaciones, alertas, reportes y documentos comerciales, permitiendo la navegación entre módulos y preparando la aplicación para su posterior integración con el Backend. |
| **Sprint 2 Velocity** | **13 Story Points** como referencia del Sprint 1. La velocidad real del Sprint 2 se determinará al verificar las historias completadas. |
| **Sum of Story Points** | **36 Story Points** |

---

#### 5.2.2.2. Aspect Leaders and Collaborators

Durante el Sprint 2 se identificaron los principales aspectos de trabajo necesarios para implementar el Frontend Web de BodeGo.

| **Team Member (Last Name, First Name)** | **GitHub Username** | **Frontend Structure & Navigation** | **Dashboard & Modules** | **Inventory & Products** | **Alerts & Reports** | **Responsive Design** |
|---|---|:---:|:---:|:---:|:---:|:---:|
| Chavez Sandoval, Dany Yohel | Danysss-cmd | L | C | C | C | C |
| Caldas Bravo, Mateo | Ethan.Matt | C | L | C | C | C |
| Blanco Medina, Jhorch Jhoseff | Bleim-154 | C | C | L | C | C |
| Saravia Hiso, Johan Álvaro | yowuan | C | C | C | L | C |
| Rojas Huaranga, Diego Rances | Diego27-16 | C | C | C | C | L |

#### 5.2.2.3. Sprint Backlog 2

Durante el Sprint 2, las actividades estuvieron orientadas al desarrollo de la primera versión funcional del Frontend Web de BodeGo.

El objetivo principal fue implementar las principales vistas de la aplicación y permitir la navegación entre sus diferentes módulos.

![Evidencia Sprint Backlog N2](https://github.com/SirEthan04/Proxy_App_Web/blob/main/recursos/imagenes/Evidencia%20Sprint%20Backlog%20n2.jpg)

Enlace: https://trello.com/invite/b/6aac64ebaf51e9bfb4c107de/ATTI7980c4d39c19509f8439a763ed2f3081F674FEDD/bodego

---

| **User Story ID** | **Story Title** | **Task ID** | **Task Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
|---|---|---|---|---|---:|---|---|
| US06 | Visualización del Dashboard operativo | TSK012 | Implement dashboard layout | Desarrollar la estructura visual del Dashboard operativo en Vue, con secciones para el resumen del negocio y los indicadores principales. | 4 | Mateo | Hecho |
| US06 | Visualización del Dashboard operativo | TSK013 | Display dashboard indicators | Implementar las tarjetas de indicadores y su presentación cuando no existan datos disponibles en el contexto consultado. | 3 | Mateo | Hecho |
| US07 | Navegación entre módulos autorizados | TSK014 | Configure application routes | Definir las rutas principales de Vue Router para Dashboard, inventario, operaciones, alertas, reportes y documentos comerciales. | 4 | Dany | Hecho |
| US07 | Navegación entre módulos autorizados | TSK015 | Implement sidebar navigation | Implementar el menú de navegación y el estado visual del módulo activo, mostrando las opciones correspondientes al perfil utilizado en la interfaz. | 2 | Dany | Hecho |
| US08 | Consulta visual del inventario | TSK016 | Implement inventory listing | Crear la vista de inventario y la tabla de consulta de productos registrados. | 4 | Yorch | Hecho |
| US08 | Consulta visual del inventario | TSK017 | Display inventory information | Presentar en la tabla los datos relevantes del producto y las existencias disponibles, incluyendo el estado vacío cuando corresponda. | 3 | Yorch | Hecho |
| US09 | Consulta visual del detalle de producto | TSK018 | Implement product detail view | Desarrollar la vista o panel de detalle al seleccionar un producto desde el listado. | 3 | Johan | Hecho |
| US09 | Consulta visual del detalle de producto | TSK019 | Display product detail fields | Mostrar la categoría, el precio y la información de existencias del producto consultado, con mensajes para datos no disponibles. | 2 | Johan | Hecho |
| US10 | Consulta visual de operaciones de inventario | TSK020 | Implement inventory operations view | Desarrollar la interfaz para revisar operaciones y movimientos asociados al inventario. | 3 | Johan | Hecho |
| US10 | Consulta visual de operaciones de inventario | TSK021 | Display operations history | Implementar la tabla de historial con tipo de operación, producto, cantidad y fecha cuando dichos datos estén disponibles. | 3 | Johan | Hecho |
| US11 | Búsqueda y filtrado de productos | TSK022 | Implement product search | Implementar la búsqueda de productos mediante el nombre u otro criterio disponible en la vista de inventario. | 3 | Yorch | Hecho |
| US11 | Búsqueda y filtrado de productos | TSK023 | Implement inventory filters | Incorporar filtros de productos y un mensaje de resultados vacíos cuando no haya coincidencias. | 3 | Yorch | Hecho |
| US12 | Visualización de alertas de inventario | TSK024 | Implement alerts module view | Desarrollar la vista para consultar las alertas operativas relacionadas con el inventario. | 4 | Mateo | Hecho |
| US12 | Visualización de alertas de inventario | TSK025 | Display alert details and states | Mostrar el tipo, mensaje y estado de cada alerta, contemplando una presentación adecuada cuando no existan alertas. | 2 | Mateo | Hecho |
| US13 | Visualización de reportes operativos | TSK026 | Implement reports module view | Construir la interfaz de reportes operativos con secciones y controles para consultar los reportes disponibles. | 4 | Diego | Hecho |
| US13 | Visualización de reportes operativos | TSK027 | Display report results | Implementar la presentación de los resultados e indicadores de cada reporte, incluyendo un estado sin información. | 3 | Diego | Hecho |
| US14 | Registro visual de productos con validaciones | TSK028 | Implement product registration form | Crear el formulario de registro de productos y sus campos de información obligatoria. | 4 | Dany | Hecho |
| US14 | Registro visual de productos con validaciones | TSK029 | Validate product form inputs | Incorporar validaciones de campos y mensajes visuales de confirmación o error en el envío del formulario. | 3 | Dany | Hecho |
| US15 | Consulta visual de documentos comerciales | TSK030 | Implement commercial documents view | Desarrollar la interfaz de consulta visual de documentos de compras y ventas de la aplicación. | 4 | Diego | Hecho |
| US15 | Consulta visual de documentos comerciales | TSK031 | Display commercial document details | Mostrar el tipo de documento, su estado, los importes y los datos de detalle disponibles en la interfaz. | 3 | Diego | Hecho |

---

#### 5.2.2.4. Development Evidence for Sprint Review.

---

| Repository              | Branch                    | Commit ID | Commit Message                          | Commit Message Body                                                            | Committed on |
| ----------------------- | ------------------------- | --------- | --------------------------------------- | ------------------------------------------------------------------------------ | ------------ |
| Danysss-cmd/Proxy_Web_App_Front-end | develop      | a4069a8   | feat: add dashboard       | Implementación del dashboard principal de BodeGo para visualizar información resumida e indicadores generales del sistema. | 05/10/2026   |
| SirEthan04/Proxy_Web_App_Front-end | develop | 9e1b553   | feat: add lots products | Implementación de la gestión de productos y lotes, permitiendo visualizar y administrar la información asociada al inventario.      | 05/10/2026   |
| Bleim-154/Proxy_Web_App_Front-end | develop | 5c41ea5   | feat: add catalog and inventory | Implementación del módulo de catálogo e inventario, incluyendo la gestión de categorías, productos y su información relacionada.      | 05/10/2026   |
| Diego27-16/Proxy_Web_App_Front-end | develop    | 808803e   | add physical count  | Implementación de la funcionalidad de conteos físicos para registrar y comparar las cantidades del inventario físico con las cantidades registradas en el sistema.         | 06/10/2026   |
| yowuan/Proxy_Web_App_Front-end | develop     | 4b74f3d   | feature: add movementsV2    | Implementación del módulo de movimientos de inventario para registrar y consultar entradas, salidas y ajustes asociados a los lotes.                      | 06/10/2026   |

---

#### 5.2.2.5. Execution Evidence for Sprint Review

---

![Estructura / alertas](recursos/imagenes/loginbodego.jpg)

---

![Estructura / alertas](recursos/imagenes/dashboardbodego.jpg)

---

![Estructura / alertas](recursos/imagenes/productosbodego.jpg)

---

![Estructura / movimientos](recursos/imagenes/operacionesbodego.jpg)

---

![Estructura / lotes](recursos/imagenes/alertasbodego.jpg)

---

![Estructura / productos](recursos/imagenes/reportesbodego.jpg)

---

![Estructura / panel](recursos/imagenes/mermasbodego.jpg)

---

![Estructura / login](recursos/imagenes/usuariosbodego.jpg)

---

#### 5.2.2.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 2 no se desarrollaron ni documentaron servicios web, debido a que el objetivo principal del sprint fue la implementación del Frontend Web de BodeGo.

La documentación de los servicios y endpoints correspondientes a la lógica del negocio será desarrollada durante el Sprint 3, cuando se inicie la implementación del Backend.

#### 5.2.2.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 2 se realizó el despliegue de la primera versión del Frontend Web de BodeGo utilizando GitHub Pages.

El despliegue permitió publicar la aplicación web y verificar el correcto funcionamiento de las principales vistas desarrolladas durante el sprint.

Actividades realizadas:

1. Integración de los cambios desarrollados en el repositorio del Frontend.
2. Configuración del despliegue mediante GitHub Pages.
3. Publicación de la primera versión del Frontend Web.
4. Verificación de las principales vistas y rutas de la aplicación.
5. Validación del acceso a la aplicación desde el entorno publicado.

**Evidencias del despliegue:**

1. Configuración dentro del Github:
---
![Imagen de la entrevista](recursos/imagenes/ghn1.jpg)
---
3. Despliegue exitoso del Frontend (Firebase):
---
![Imagen de la entrevista](recursos/imagenes/ghn2.jpg)
---
5. Verificación y autorizacion en el IntellIdea:
 ---
![Imagen de la entrevista](recursos/imagenes/ghn3.jpg)
---
7. Aplicación Web publicada.
---
![Imagen de la entrevista](recursos/imagenes/ghn4.jpg)
---

**Enlace de la aplicación:**  
Enlace: https://proxy-app-web-a4eca.firebaseapp.com/

Únicamente funciona por ahora el enlace para iniciar sesión y muestra los datos de los productos  pero no permite cambiar por el momento porque requiere datos de categoría que no se pueden implementar categorías en mockapi.

#### 5.2.2.8. Team Collaboration Insights during Sprint

---

![Estructura / TeamColaborations](recursos/imagenes/TeamColabSprint2.jpg)

---

## 5.2.3. Sprint 3

**Sprint 3 – Desarrollo de servicios Backend y mejoras de la Landing Page y Frontend Web de BodeGo**

Durante el Sprint 3, el equipo de BodeGo planificó desarrollar los principales servicios REST del Backend del curso **Aplicaciones Web**. El trabajo se concentró en los bounded contexts **Inventory, Operations y Commercial**, para gestionar productos, categorías, lotes, existencias, movimientos, mermas, conteos físicos, compras y ventas.

Asimismo, se contemplaron mejoras en la Landing Page para presentar las pantallas de la aplicación, explicar los roles de Administrador y Empleado e incorporar información comercial. En el Frontend Web, desarrollado con **Vue 3**, se planificaron mejoras de internacionalización, preparación de compras y ventas, visualización de disponibilidad y manejo de estados de las operaciones. El objetivo fue avanzar hacia una integración funcional entre la interfaz y la API.

#### 5.2.3.1. Sprint Planning 3

El Sprint Planning permitió seleccionar las historias del Product Backlog correspondientes al desarrollo de los servicios de inventario, operaciones y gestión comercial, además de las mejoras de la Landing Page y del Frontend Web. Se incluyeron las **US16–US32, US41–US45 y US51–US60**, junto con las **TS01–TS09 y TS16**, considerando las dependencias entre los módulos y las operaciones del Backend.

El alcance planificado comprende **32 User Stories (129 SP)** y **10 Technical Stories (47 SP)**, para un total de **176 Story Points**.

| **Sprint #** | **Sprint 3** |
|---|---|
| **Sprint Planning Background** | Se planifica la implementación de servicios REST en ASP.NET Core para catálogo, categorías, lotes, stock, historial de movimientos, mermas y conteos físicos. También se considera el flujo comercial de compras y ventas, incluyendo su preparación y confirmación con validaciones de inventario. De forma complementaria, se programan mejoras en la Landing Page y en el Frontend Vue, así como la documentación de los servicios mediante OpenAPI y Scalar y su integración progresiva con la aplicación. |
| **Date** | 29-10-2026 |
| **Time** | 2:00 pm |
| **Location** | Discord |
| **Prepared By** | Equipo de desarrollo BodeGo |
| **Attendees (to planning meeting)** | Dany / Mateo / Jhorch / Johan / Diego |
| **Sprint 2 Review Summary** | Durante el Sprint 2 se desarrolló la primera versión funcional del Frontend Web de BodeGo con Vue 3. Se implementaron las vistas del Dashboard, navegación, inventario, detalle de productos, operaciones, búsqueda y filtros, alertas, reportes, registro visual de productos y consulta de documentos comerciales. Las tareas TSK012–TSK031 quedaron registradas como Hecho, correspondientes a las US06–US15 y a 36 Story Points planificados. El Sprint 2 no incluyó la TS01, cuya implementación REST se programó para el Sprint 3. |
| **Sprint 2 Retrospective Summary** | Se identificó la necesidad de conectar progresivamente las vistas de Vue con los recursos REST reales, diferenciar los estados de carga, vacío y error, validar las existencias antes de confirmar operaciones comerciales y evitar envíos duplicados o resultados inciertos. También se acordó mantener la coherencia visual entre la Landing Page y el Frontend, y reforzar la documentación de la API con Scalar. |
| **Sprint Goal & User Stories** | **Inventory y Operations:** US16–US32. **Commercial:** US41–US45. **Mejoras de Landing Page:** US51–US53. **Mejoras de Frontend Web:** US54–US60. **Technical Stories:** TS01–TS09 y TS16. |
| **Sprint 3 Goal** | Desarrollar y documentar los servicios REST principales de BodeGo mediante ASP.NET Core, C# y Entity Framework Core para gestionar productos, categorías, lotes, existencias, movimientos, mermas y conteos físicos, así como registrar, consultar y confirmar compras y ventas de manera consistente con el inventario. Complementariamente, mejorar la Landing Page mediante una galería de pantallas, la presentación de roles y la información comercial; y fortalecer el Frontend Vue con cambio de idioma español/inglés, carritos para compras y ventas, consulta y previsualización de stock, estados de confirmación y manejo de situaciones de carga, error o incertidumbre. Integrar progresivamente los módulos con la API y documentar sus recursos con OpenAPI y Scalar, preparando los contextos de Monitoring, Reporting e IAM para el siguiente sprint. |
| **Sprint 3 Velocity** | **176 Story Points planificados**. La velocidad real se determinará al revisar las historias efectivamente completadas al cierre del sprint. |
| **Sum of Story Points** | **176 Story Points**: 129 SP de User Stories y 47 SP de Technical Stories. |

---

#### 5.2.3.2. Aspect Leaders and Collaborators

Durante el Sprint 3 se identificaron los principales aspectos de trabajo para continuar el desarrollo de BodeGo, incluyendo la implementación de servicios REST, así como mejoras en la Landing Page y el Frontend Web.

Las responsabilidades se distribuyeron considerando las User Stories US16–US32, US41–US45 y US51–US60, junto con las Technical Stories TS01–TS09 y TS16.

En el Backend, las actividades comprendieron los servicios de Inventory, Operations y Commercial, abarcando productos, lotes, inventario, movimientos, mermas, conteos físicos, compras y ventas.

En la Landing Page y el Frontend Web, se contemplaron mejoras de presentación, internacionalización, experiencia de usuario y gestión visual de operaciones. Las funcionalidades de IAM quedaron reservadas para el Sprint 4.

| **Team Member (Last Name, First Name)** | **GitHub Username** | **Landing Page Improvements & Product Presentation** | **Frontend Features & User Experience** | **Backend Architecture & Catalog Services** | **Inventory, Lots & Stock Queries** | **Movements, Wastes & Physical Counts** | **Purchases, Sales & Confirmations** | **API Integration, Scalar & Testing** |
|---|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Chavez Sandoval, Dany Yohel | Danysss-cmd | L | C | C | - | C | C | L |
| Caldas Bravo, Mateo | Ethan.Matt | C | C | C | C | C | L | C |
| Blanco Medina, Jhorch Jhoseff | Bleim-154 | C | C | L | C | C | C | C |
| Saravia Hiso, Johan Álvaro | yowuan | C | C | C | L | L | C | C |
| Rojas Huaranga, Diego Rances | Diego27-16 | C | L | - | C | C | C | C |

---

#### 5.2.3.3. Sprint Backlog 3

Durante el Sprint 3, el equipo planificó la implementación de los servicios REST del Backend de BodeGo para Aplicaciones Web, con énfasis en Inventory, Operations y Commercial. Asimismo, se incluyeron mejoras de la Landing Page (US51–US53) y del Frontend Vue 3 (US54–US60), orientadas a mejorar la presentación comercial del producto y la experiencia de uso.

El Sprint Backlog comprende 32 User Stories (US16–US32, US41–US45 y US51–US60) y 10 Technical Stories (TS01–TS09 y TS16), con 176 Story Points planificados (129 SP de US y 47 SP de TS). Las historias de usuario se presentan primero y las historias técnicas al final. Las User Stories (US51-US60) corresponden a las mejoras implementadas en este Sprint con respecto al Landing Page y Frontend.

![Evidencia Sprint Backlog N3](Recursos/images/sprintbacklogN3OP.jpg)

Enlace: 

---

| **User Story ID** | **Story Title** | **Task ID** | **Task Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
|---|---|---|---|---|---:|---|---|
| US16 | Registro de productos en catálogo | TSK032 | Implement product registration | Implementar el alta de productos mediante `POST /api/v1/products`, con datos de venta y categoría del catálogo. | 4 | Jhorch | Done |
| US16 | Registro de productos en catálogo | TSK033 | Validate category and product input | Verificar campos obligatorios y la existencia de la categoría seleccionada antes de persistir el producto. | 3 | Jhorch | To Review |
| US16 | Registro de productos en catálogo | TSK034 | Check product persistence and response | Revisar la respuesta de creación y comprobar que el producto figure en la consulta del catálogo. | 3 | Jhorch | To Review |
| US16 | Registro de productos en catálogo | TSK035 | Test product registration failures | Probar solicitudes incompletas, categoría inexistente y respuestas de error sin crear registros parciales. | 3 | Jhorch | To Do |
| US17 | Actualización de información del producto | TSK036 | Define product update contract | Definir campos editables y comportamiento esperado de `PUT /api/v1/products/{id}`, recurso aún no presente en el ZIP revisado. | 3 | Jhorch | To Do |
| US17 | Actualización de información del producto | TSK037 | Implement product update operation | Implementar actualización del producto existente en las capas de aplicación y persistencia de Inventory. | 5 | Jhorch | To Do |
| US17 | Actualización de información del producto | TSK038 | Validate update business constraints | Validar identificador existente, categoría válida y reglas de datos editables sin alterar otros recursos. | 3 | Jhorch | To Do |
| US17 | Actualización de información del producto | TSK039 | Test product update scenarios | Probar actualización válida, recurso inexistente e información incorrecta; documentar respuestas reales. | 3 | Jhorch | To Do |
| US18 | Clasificación de productos por categorías | TSK040 | Implement category selection for products | Permitir seleccionar una categoría existente al crear un producto del catálogo. | 3 | Jhorch | Done |
| US18 | Clasificación de productos por categorías | TSK041 | Validate product category relation | Validar que el identificador de categoría corresponda a un registro disponible antes de asociarlo. | 3 | Jhorch | To Review |
| US18 | Clasificación de productos por categorías | TSK042 | Expose category in product response | Comprobar que el producto consultado conserve su relación con la categoría asignada. | 2 | Jhorch | Done |
| US18 | Clasificación de productos por categorías | TSK043 | Test category assignment edge cases | Probar categoría válida, inexistente y ausencia de clasificación obligatoria según contrato. | 2 | Jhorch | To Do |
| US19 | Consulta de productos con stock bajo | TSK044 | Implement low stock products query | Exponer la consulta `GET /api/v1/products/low-stock` para productos bajo el umbral establecido. | 4 | Jhorch | Done |
| US19 | Consulta de productos con stock bajo | TSK045 | Validate low stock thresholds | Revisar comparación de existencias y mínimo configurado para identificar productos críticos. | 3 | Jhorch | To Review |
| US19 | Consulta de productos con stock bajo | TSK046 | Display low stock results for business use | Comprobar que la respuesta contenga los datos de producto y disponibilidad necesarios para revisión. | 2 | Jhorch | To Review |
| US19 | Consulta de productos con stock bajo | TSK047 | Test low stock and empty results | Probar productos por debajo y encima del umbral y respuesta sin coincidencias. | 3 | Jhorch | To Do |
| US20 | Consulta de lotes asociados a productos | TSK048 | Implement product lots query | Implementar consulta `GET /api/v1/products/{id}/lots` para recuperar los lotes asociados a un producto. | 4 | Jhorch | Done |
| US20 | Consulta de lotes asociados a productos | TSK049 | Map lot quantity and expiration | Comprobar que cada lote consultado incluya datos de identificación, cantidad y vencimiento. | 3 | Jhorch | Done |
| US20 | Consulta de lotes asociados a productos | TSK050 | Handle products with no lots | Presentar una colección vacía válida cuando el producto no tenga lotes vinculados. | 2 | Jhorch | Done |
| US20 | Consulta de lotes asociados a productos | TSK051 | Test lots query scenarios | Probar producto con varios lotes, sin lotes e identificador inexistente. | 3 | Jhorch | To Do |
| US21 | Consulta de stock actual de productos | TSK052 | Expose current product stock | Comprobar que las consultas de producto y sus lotes permitan recuperar existencias vigentes. | 3 | Jhorch | Done |
| US21 | Consulta de stock actual de productos | TSK053 | Verify stock aggregation consistency | Contrastar las cantidades de lotes con el stock presentado al consultar un producto. | 4 | Jhorch | To Review |
| US21 | Consulta de stock actual de productos | TSK054 | Handle zero stock products | Comprobar el tratamiento de productos con cantidad cero, sin inventar un endpoint agregado independiente. | 2 | Jhorch | Done |
| US21 | Consulta de stock actual de productos | TSK055 | Test current stock queries | Validar resultados con varios lotes, stock cero y registros inexistentes. | 3 | Jhorch | To Do |
| US22 | Consistencia del inventario ante confirmaciones comerciales | TSK056 | Review confirmation stock transaction | Revisar la operación transaccional de confirmación comercial que modifica existencias y movimientos. | 4 | Mateo | To Review |
| US22 | Consistencia del inventario ante confirmaciones comerciales | TSK057 | Protect against partial stock changes | Verificar que una falla al confirmar compra o venta no persista cambios parciales en las cantidades. | 4 | Mateo | To Review |
| US22 | Consistencia del inventario ante confirmaciones comerciales | TSK058 | Confirm stock change on success | Comprobar que una confirmación válida actualice las existencias asociadas una sola vez. | 3 | Mateo | To Review |
| US22 | Consistencia del inventario ante confirmaciones comerciales | TSK059 | Test failure and rollback scenarios | Probar errores durante confirmación y comparar existencias antes y después del rechazo. | 4 | Mateo | To Do |
| US23 | Trazabilidad de salidas originadas en ventas | TSK060 | Link confirmed sales to stock exits | Revisar la relación entre una venta confirmada y los movimientos de salida generados. | 4 | Mateo | Done |
| US23 | Trazabilidad de salidas originadas en ventas | TSK061 | Verify sale origin traceability | Comprobar referencias de producto, lote y operación comercial en el historial disponible. | 3 | Mateo | To Review |
| US23 | Trazabilidad de salidas originadas en ventas | TSK062 | Ensure drafts produce no movement | Comprobar que una venta en borrador no origine movimientos de salida de inventario. | 3 | Mateo | Done |
| US23 | Trazabilidad de salidas originadas en ventas | TSK063 | Test sales movement trace | Validar trazabilidad con ventas confirmadas, borradores y consulta posterior de movimientos. | 3 | Mateo | To Do |
| US24 | Validación del stock disponible para ventas | TSK064 | Validate available quantity before sale | Verificar la disponibilidad de los productos solicitados al confirmar una venta. | 4 | Mateo | Done |
| US24 | Validación del stock disponible para ventas | TSK065 | Reject sale with insufficient stock | Comprobar el rechazo de una confirmación que exceda existencias disponibles sin descontar stock. | 4 | Mateo | Done |
| US24 | Validación del stock disponible para ventas | TSK066 | Enforce positive quantities on sales | Revisar validaciones de cantidades positivas y referencias válidas de las líneas de venta. | 3 | Mateo | Done |
| US24 | Validación del stock disponible para ventas | TSK067 | Test overselling prevention | Probar venta válida, exceso de unidades y reintento tras el rechazo. | 3 | Mateo | To Do |
| US25 | Consulta de conteos físicos por identificador | TSK068 | Implement inventory count detail query | Exponer `GET /api/v1/inventory-counts/{id}` para consultar un conteo físico registrado. | 3 | Johan | Done |
| US25 | Consulta de conteos físicos por identificador | TSK069 | Map physical and recorded quantities | Comprobar que el detalle incluya cantidad contada, referencias del inventario y datos disponibles. | 3 | Johan | Done |
| US25 | Consulta de conteos físicos por identificador | TSK070 | Handle count not found | Gestionar correctamente la consulta de un identificador de conteo inexistente. | 2 | Johan | Done |
| US25 | Consulta de conteos físicos por identificador | TSK071 | Test count detail responses | Probar consulta válida, identificador inexistente y consistencia de datos del conteo. | 3 | Johan | To Do |
| US26 | Consulta del historial de movimientos de inventario | TSK072 | Implement inventory movement listing | Exponer la consulta `GET /api/v1/inventory-movements` del contexto Operations. | 4 | Johan | Done |
| US26 | Consulta del historial de movimientos de inventario | TSK073 | Map movement history information | Comprobar identificación, tipo, cantidad y referencias de origen cuando estén disponibles. | 3 | Johan | Done |
| US26 | Consulta del historial de movimientos de inventario | TSK074 | Handle history without records | Mostrar resultados vacíos válidos sin interpretarlos como error de servicio. | 2 | Johan | Done |
| US26 | Consulta del historial de movimientos de inventario | TSK075 | Test movement history queries | Probar movimientos comerciales, historial vacío y forma de la respuesta. | 3 | Johan | To Do |
| US27 | Consulta de productos próximos a vencer | TSK076 | Retrieve lot expiration information | Consultar las fechas de vencimiento de los lotes desde `GET /api/v1/products/{id}/lots`. | 3 | Johan | Done |
| US27 | Consulta de productos próximos a vencer | TSK077 | Define upcoming expiration threshold | Establecer el criterio temporal para identificar lotes próximos a vencer sin crear una ruta no implementada. | 3 | Johan | In Process |
| US27 | Consulta de productos próximos a vencer | TSK078 | Present upcoming expiration results | Preparar la identificación visual de lotes que cumplen el umbral en el consumo de datos existente. | 3 | Johan | In Process |
| US27 | Consulta de productos próximos a vencer | TSK079 | Test expiration boundary cases | Verificar lotes vencidos, próximos a vencer, vigentes y producto sin lotes. | 3 | Johan | To Do |
| US28 | Asignación FIFO de existencias en ventas sin lote explícito | TSK080 | Review FIFO allocation on sale confirmation | Verificar la regla de asignación FIFO para ventas sin un lote explícito en la confirmación comercial. | 4 | Mateo | To Review |
| US28 | Asignación FIFO de existencias en ventas sin lote explícito | TSK081 | Order available lots by receipt | Comprobar la selección de lotes según antigüedad de ingreso cuando la venta requiere asignación automática. | 4 | Mateo | Done |
| US28 | Asignación FIFO de existencias en ventas sin lote explícito | TSK082 | Respect explicitly selected lot | Revisar que un lote elegido expresamente no sea reemplazado por la asignación FIFO automática. | 3 | Mateo | Done |
| US28 | Asignación FIFO de existencias en ventas sin lote explícito | TSK083 | Test multi lot FIFO scenarios | Probar consumo con uno o varios lotes, stock insuficiente y selección de lote explícito. | 4 | Mateo | To Do |
| US29 | Registro de conteo físico de inventario | TSK084 | Implement physical inventory count registration | Registrar conteos mediante `POST /api/v1/inventory-counts` con la cantidad física observada. | 4 | Johan | Done |
| US29 | Registro de conteo físico de inventario | TSK085 | Validate count product and quantity | Comprobar referencias del inventario y restricciones de cantidad para registrar un conteo. | 3 | Johan | Done |
| US29 | Registro de conteo físico de inventario | TSK086 | Preserve count evidence without stock update | Verificar que guardar el conteo documente la observación sin realizar un ajuste manual automático. | 3 | Johan | Done |
| US29 | Registro de conteo físico de inventario | TSK087 | Test physical count registration | Probar registro válido, cantidad inválida y consulta posterior del conteo. | 3 | Johan | To Do |
| US30 | Trazabilidad por producto, lote y operación | TSK088 | Review movement product and lot references | Comprobar que las operaciones almacenadas conserven referencias al producto y lote afectados. | 4 | Johan | To Review |
| US30 | Trazabilidad por producto, lote y operación | TSK089 | Link inventory movement to source operation | Revisar la identificación de la compra, venta o merma que originó un cambio de stock. | 3 | Johan | Done |
| US30 | Trazabilidad por producto, lote y operación | TSK090 | Trace stock change through history | Comprobar que el historial permita diferenciar operaciones de entrada y salida por su origen. | 3 | Johan | Done |
| US30 | Trazabilidad por producto, lote y operación | TSK091 | Test stock traceability cases | Probar movimientos originados por compras, ventas y mermas verificando referencias disponibles. | 3 | Johan | To Do |
| US31 | Registro de mermas de inventario | TSK092 | Implement waste registration REST resource | Registrar mermas mediante `POST /api/v1/wastes` sobre existencias disponibles. | 4 | Johan | Done |
| US31 | Registro de mermas de inventario | TSK093 | Validate waste quantity and product | Comprobar cantidad positiva, referencia válida y disponibilidad para descontar unidades. | 3 | Johan | Done |
| US31 | Registro de mermas de inventario | TSK094 | Apply waste stock effect consistently | Verificar que la merma registrada reduzca existencias y se refleje en operaciones de inventario. | 4 | Johan | Done |
| US31 | Registro de mermas de inventario | TSK095 | Test waste and insufficient stock | Probar merma válida, cantidad excesiva y rechazo sin pérdida parcial de datos. | 3 | Johan | To Do |
| US32 | Clasificación de causas de merma | TSK096 | Identify accepted waste reasons | Revisar los motivos admitidos en el modelo y contrato de registro de mermas. | 2 | Johan | To Review |
| US32 | Clasificación de causas de merma | TSK097 | Validate waste reason in request | Comprobar que una solicitud de merma incluya una causa permitida. | 3 | Johan | Done |
| US32 | Clasificación de causas de merma | TSK098 | Return reason in waste history | Verificar que el registro y consulta de mermas conserve el motivo asociado. | 2 | Johan | Done |
| US32 | Clasificación de causas de merma | TSK099 | Test invalid waste reason values | Probar cada causa admitida y el rechazo de un motivo desconocido. | 2 | Johan | To Do |
| US41 | Registro de compras en borrador | TSK100 | Implement purchase draft registration | Crear compras en borrador mediante `POST /api/v1/purchases` con sus productos, cantidades y costos. | 5 | Mateo | Done |
| US41 | Registro de compras en borrador | TSK101 | Validate purchase document lines | Comprobar referencias de productos y cantidades válidas en las líneas de compra. | 3 | Mateo | Done |
| US41 | Registro de compras en borrador | TSK102 | Ensure drafts do not alter inventory | Verificar que crear un borrador no incremente existencias ni registre entradas de stock. | 3 | Mateo | Done |
| US41 | Registro de compras en borrador | TSK103 | Test purchase draft scenarios | Probar creación válida, líneas incorrectas y consulta posterior del borrador. | 4 | Mateo | To Do |
| US42 | Registro de ventas en borrador | TSK104 | Implement sales draft registration | Crear ventas en borrador mediante `POST /api/v1/sales` con artículos, cantidades y precios. | 5 | Mateo | Done |
| US42 | Registro de ventas en borrador | TSK105 | Validate sale document lines | Revisar validaciones de producto, precio y cantidad de cada línea de venta. | 3 | Mateo | Done |
| US42 | Registro de ventas en borrador | TSK106 | Ensure sales drafts do not reduce stock | Comprobar que registrar una venta en borrador no descuente unidades disponibles. | 3 | Mateo | Done |
| US42 | Registro de ventas en borrador | TSK107 | Test sales draft scenarios | Probar creación de borrador, líneas inválidas y consulta del documento recién registrado. | 4 | Mateo | To Do |
| US43 | Confirmación de compras de mercadería | TSK108 | Implement purchase confirmation | Confirmar compras mediante `POST /api/v1/purchases/{id}/confirm`. | 5 | Mateo | Done |
| US43 | Confirmación de compras de mercadería | TSK109 | Increase stock from confirmed purchases | Verificar que confirmar una compra registre entradas y aumente las existencias correspondientes. | 4 | Mateo | Done |
| US43 | Confirmación de compras de mercadería | TSK110 | Prevent duplicate purchase confirmation | Comprobar que un documento confirmado no vuelva a incrementar el stock ante otro intento. | 3 | Mateo | Done |
| US43 | Confirmación de compras de mercadería | TSK111 | Test purchase confirmation transactions | Probar confirmación válida, repetida y fallida, comprobando atomicidad. | 4 | Mateo | To Do |
| US44 | Confirmación de ventas con salida de inventario | TSK112 | Implement sale confirmation | Confirmar ventas mediante `POST /api/v1/sales/{id}/confirm`. | 5 | Mateo | Done |
| US44 | Confirmación de ventas con salida de inventario | TSK113 | Deduct stock and record sales exit | Verificar disminución de stock y creación de movimientos correspondientes a la venta confirmada. | 4 | Mateo | Done |
| US44 | Confirmación de ventas con salida de inventario | TSK114 | Reject overstock and repeated confirmation | Comprobar rechazo por inventario insuficiente o venta ya confirmada, sin duplicar movimientos. | 3 | Mateo | Done |
| US44 | Confirmación de ventas con salida de inventario | TSK115 | Test sales confirmation outcomes | Probar venta válida, sin stock, confirmación duplicada y reversión ante errores. | 4 | Mateo | To Do |
| US45 | Consulta del historial y detalle comercial | TSK116 | Implement commercial history queries | Habilitar `GET /api/v1/purchases` y `GET /api/v1/sales` para listar documentos. | 4 | Mateo | Done |
| US45 | Consulta del historial y detalle comercial | TSK117 | Expose purchase and sale details | Verificar `GET /api/v1/purchases/{id}` y `GET /api/v1/sales/{id}` con sus líneas y estados. | 4 | Mateo | Done |
| US45 | Consulta del historial y detalle comercial | TSK118 | Present document state and totals | Comprobar que los registros devuelvan los importes y estados necesarios para el seguimiento. | 3 | Mateo | Done |
| US45 | Consulta del historial y detalle comercial | TSK119 | Test commercial history and detail | Probar documentos existentes, listados vacíos e identificadores inexistentes. | 3 | Mateo | To Do |
| US51 | Galería visual de pantallas de BodeGo | TSK120 | Implement landing application gallery | Presentar capturas representativas de Dashboard, inventario y operaciones con explicaciones breves de cada pantalla. | 4 | Dany | Done |
| US51 | Galería visual de pantallas de BodeGo | TSK121 | Validate gallery readability and layout | Revisar disposición responsive, legibilidad de imágenes y correspondencia de textos con la aplicación. | 3 | Dany | To Do |
| US52 | Presentación de roles Administrador y Empleado | TSK122 | Implement administrator and employee presentation | Incorporar una sección que distinga las responsabilidades del Administrador y del Empleado en BodeGo. | 3 | Dany | Done |
| US52 | Presentación de roles Administrador y Empleado | TSK123 | Review roles copy and mobile presentation | Validar textos, jerarquía visual y adaptación móvil de la descripción de ambos perfiles. | 3 | Dany | To Do |
| US53 | Consulta de plan y precio comercial | TSK124 | Implement landing pricing information | Presentar el precio, plan y características comerciales publicadas de BodeGo, utilizando información aprobada. | 4 | Dany | Done |
| US53 | Consulta de plan y precio comercial | TSK125 | Connect pricing inquiry with contact section | Vincular la consulta comercial con el formulario o canal de contacto y revisar su diseño responsive. | 3 | Dany | Done |
| US54 | Cambio de idioma español/inglés en el Frontend | TSK126 | Implement Vue English Spanish language switching | Integrar selector y recursos i18n inglés/español para navegación y módulos prioritarios de la aplicación. | 4 | Diego | Done |
| US54 | Cambio de idioma español/inglés en el Frontend | TSK127 | Verify translations and language persistence | Comprobar traducciones, preferencia al navegar o recargar y requisito de idioma inicial. | 4 | Diego | To Do |
| US55 | Preparación de compras con carrito de productos | TSK128 | Implement purchase cart interactions | Permitir añadir, editar y retirar líneas de productos en la preparación de una compra. | 4 | Diego | Done |
| US55 | Preparación de compras con carrito de productos | TSK129 | Validate cart totals and purchase payload | Revisar cantidades, precios, cálculos y transformación del carrito al borrador de compra. | 4 | Diego | To Do |
| US56 | Preparación de ventas con disponibilidad visible | TSK130 | Implement sales cart with stock visibility | Mostrar productos y existencias consultadas durante la preparación de la venta en Vue. | 4 | Diego | Done |
| US56 | Preparación de ventas con disponibilidad visible | TSK131 | Validate cart quantities against availability | Advertir cantidades superiores al stock mostrado y revisar la información antes de enviar el borrador. | 4 | Diego | To Do |
| US57 | Estados de confirmación y resultado de compras y ventas | TSK132 | Implement commercial confirmation statuses | Visualizar estados de borrador, confirmación y resultado en compras y ventas. | 4 | Diego | Done |
| US57 | Estados de confirmación y resultado de compras y ventas | TSK133 | Prevent repeated confirmation interaction | Bloquear interacciones duplicadas durante el envío y verificar las respuestas reales de la API. | 3 | Diego | To Do |
| US58 | Presentación de estados vacíos, carga y error de servicios | TSK134 | Implement loading empty and error states | Usar componentes de estado para consultas pendientes, listados vacíos y fallas de servicios REST. | 4 | Diego | Done |
| US58 | Presentación de estados vacíos, carga y error de servicios | TSK135 | Validate feedback across priority modules | Comprobar mensajes de interfaz en inventario, compras y ventas frente a datos vacíos y fallos HTTP. | 3 | Diego | To Do |
| US59 | Previsualización de stock antes de operaciones | TSK136 | Implement stock preview before operation | Presentar stock consultado y variación estimada al preparar una compra o venta. | 3 | Diego | Done |
| US59 | Previsualización de stock antes de operaciones | TSK137 | Refresh stock preview on product change | Verificar recalculo de cantidades al cambiar producto, lote o unidades antes del envío. | 3 | Diego | To Do |
| US60 | Protección frente a resultados inciertos de operaciones | TSK138 | Implement pending evidence for uncertain requests | Mostrar un estado de resultado incierto cuando se pierde la respuesta de una operación comercial enviada. | 4 | Diego | Done |
| US60 | Protección frente a resultados inciertos de operaciones | TSK139 | Validate retry and context change safeguards | Evitar asumir éxito o duplicar solicitudes al reintentar y comprobar el cambio de contexto tras una respuesta incierta. | 4 | Diego | To Do |
| TS01 | Gestión REST de productos | TSK140 | Review products API contract and schemas | Revisar métodos `POST`, `GET` y consulta por ID de productos, recursos, validaciones y respuestas documentadas. | 4 | Jhorch | To Review |
| TS01 | Gestión REST de productos | TSK141 | Execute products endpoint contract checks | Validar códigos HTTP y estructuras JSON de creación, listado y producto inexistente. | 4 | Jhorch | To Do |
| TS02 | Gestión REST de categorías | TSK142 | Review categories REST contract | Revisar `GET`, `POST` y consulta por ID de categorías; no atribuir actualización o eliminación a esta API. | 4 | Jhorch | To Review |
| TS02 | Gestión REST de categorías | TSK143 | Execute categories REST validation checks | Comprobar registro, listado, duplicados y categoría inexistente contra el contrato OpenAPI. | 3 | Jhorch | To Do |
| TS03 | Consultas REST de lotes y productos con stock bajo | TSK144 | Review lots and low stock REST contracts | Documentar `GET /api/v1/products/{id}/lots` y `GET /api/v1/products/low-stock` con sus respuestas. | 4 | Jhorch | To Review |
| TS03 | Consultas REST de lotes y productos con stock bajo | TSK145 | Test stock and expiration query endpoints | Validar resultados con lotes, productos sin lotes, stock crítico y recurso inexistente. | 4 | Jhorch | To Do |
| TS04 | Consulta REST del historial de movimientos de inventario | TSK146 | Review inventory movements REST contract | Inspeccionar `GET /api/v1/inventory-movements` y los campos de trazabilidad disponibles en el modelo. | 4 | Johan | To Review |
| TS04 | Consulta REST del historial de movimientos de inventario | TSK147 | Execute movement history contract tests | Validar historial con compras y ventas confirmadas, y respuesta vacía si no hay movimientos. | 4 | Johan | To Do |
| TS05 | Registro y consulta REST de mermas | TSK148 | Review wastes API contract and policy | Documentar `POST` y `GET /api/v1/wastes`, motivos válidos y reglas para cantidades disponibles. | 4 | Johan | To Review |
| TS05 | Registro y consulta REST de mermas | TSK149 | Execute waste endpoint tests | Comprobar creación, consulta y rechazo por datos o existencias no válidos. | 4 | Johan | To Do |
| TS06 | Registro y consulta REST de conteos físicos | TSK150 | Review inventory counts API contract | Documentar `POST /api/v1/inventory-counts` y `GET /api/v1/inventory-counts/{id}` con esquemas de solicitud y respuesta. | 4 | Johan | To Review |
| TS06 | Registro y consulta REST de conteos físicos | TSK151 | Execute inventory count endpoint checks | Verificar registro, consulta, identificador inexistente y reglas de cantidad del conteo. | 4 | Johan | To Do |
| TS07 | Gestión REST de compras comerciales | TSK152 | Review purchase REST contract | Revisar `POST`, `GET` y detalle de `/api/v1/purchases`, validación de líneas y estado borrador. | 4 | Mateo | To Review |
| TS07 | Gestión REST de compras comerciales | TSK153 | Test purchase REST requests and responses | Comprobar creación de borradores, consultas por ID y errores de datos inválidos. | 4 | Mateo | To Do |
| TS08 | Gestión REST de ventas comerciales | TSK154 | Review sales REST contract | Revisar `POST`, `GET` y detalle de `/api/v1/sales`, esquemas de venta y estado inicial. | 4 | Mateo | To Review |
| TS08 | Gestión REST de ventas comerciales | TSK155 | Test sales REST request contract | Probar documentos válidos, consulta de ventas y error por identificador inexistente. | 4 | Mateo | To Do |
| TS09 | Confirmación transaccional de compras y ventas | TSK156 | Review purchase and sale confirmation transaction | Revisar contratos `POST /api/v1/purchases/{id}/confirm` y `POST /api/v1/sales/{id}/confirm`, stock y prevención de duplicados. | 5 | Mateo | To Review |
| TS09 | Confirmación transaccional de compras y ventas | TSK157 | Execute transactional confirmation integration tests | Comprobar integridad y movimientos en confirmaciones válidas, repetidas y rechazadas por stock. | 5 | Mateo | To Do |
| TS16 | Documentación OpenAPI con Scalar e integración REST del Frontend | TSK158 | Configure and review Scalar OpenAPI documentation | Revisar exposición del documento OpenAPI y de Scalar con métodos y esquemas de los contextos incluidos en Sprint 3. | 4 | Dany | Done |
| TS16 | Documentación OpenAPI con Scalar e integración REST del Frontend | TSK159 | Validate Vue API integration and error handling | Comprobar URL base, CORS y tratamiento de respuestas exitosas y fallidas al consumir API desde Vue. | 5 | Dany | To Do |

---

#### 5.2.3.4. Development Evidence for Sprint Review

Durante el Sprint 3 se registraron avances en el desarrollo de los servicios REST del Backend de BodeGo. Las evidencias se presentan mediante el historial de commits del repositorio, principalmente en los bounded contexts **Inventory, Operations y Commercial**.

**Backend — Inventory, Operations y Commercial**

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| Danysss-cmd/Proxy_Web_App_Back-end | develop | `e2edfa5` | Merge pull request #11 from SirEthan04/feature/deploy-render-backend | Integración de la rama de preparación del Backend para Render. | 13/11/2026 |
| Danysss-cmd/Proxy_Web_App_Back-end | develop | `8bda67b` | Preparar backend para despliegue Docker en Render | Preparación de la configuración Docker para un posible despliegue del servicio ASP.NET Core en Render. | 13/11/2026 |
| Danysss-cmd/Proxy_Web_App_Back-end | develop | `5efc680` | Merge pull request #9 from SirEthan04/feature/cors-frontend | Integración de los cambios de configuración CORS destinados a la comunicación con el Frontend. | 10/11/2026 |
| Danysss-cmd/Proxy_Web_App_Back-end | develop | `bebed47` | Configurar CORS para conectar el frontend Vue | Configuración de CORS para habilitar solicitudes desde el cliente Vue según los orígenes permitidos. | 10/11/2026 |
| Danysss-cmd/Proxy_Web_App_Back-end | develop | `bc1cdfd` | Merge pull request #8 from SirEthan04/feature/confirmaciones-commercial | Integración de cambios del flujo de confirmaciones del bounded context Commercial. | 10/11/2026 |
| Danysss-cmd/Proxy_Web_App_Back-end | develop | `d5c18c8` | Documentar flujo completo de compras y ventas | Documentación del flujo de las operaciones comerciales de compras y ventas. | 10/11/2026 |
| Danysss-cmd/Proxy_Web_App_Back-end | develop | `38ca7af` | Agregar pruebas de confirmaciones | Incorporación de pruebas para la lógica de confirmación de operaciones comerciales. | 10/11/2026 |
| Danysss-cmd/Proxy_Web_App_Back-end | develop | `1306a6a` | Agregar endpoints de confirmacion comercial | Incorporación de rutas REST para confirmar documentos de compras y ventas. | 10/11/2026 |
| Danysss-cmd/Proxy_Web_App_Back-end | develop | `1eb903c` | Integrar persistencia transaccional de confirmaciones | Cambios en la persistencia transaccional del proceso de confirmación de operaciones comerciales. | 10/11/2026 |
| Danysss-cmd/Proxy_Web_App_Back-end | develop | `6a49776` | Implementar descuento de ventas confirmadas | Implementación del descuento de existencias asociado a ventas confirmadas. | 10/11/2026 |
| Danysss-cmd/Proxy_Web_App_Back-end | develop | `d59e055` | Implementar recepcion de compras y lotes | Cambios vinculados a la recepción de compras y su relación con los lotes del inventario. | 10/11/2026 |
| Danysss-cmd/Proxy_Web_App_Back-end | develop | `adfcb3d` | Preparar comandos de confirmacion comercial | Definición de comandos necesarios para ejecutar la confirmación comercial. | 10/11/2026 |
| Bleim-154/Proxy_Web_App_Back-end | develop | `c9e6694` | Merge pull request #6 from SirEthan04/feature/operations | Integración de la rama de desarrollo del bounded context Operations. | 09/11/2026 |
| Bleim-154/Proxy_Web_App_Back-end | develop | `6f782dc` | Agregar pruebas y documentacion de Operations | Incorporación de pruebas y documentación de servicios del contexto Operations. | 09/11/2026 |
| Bleim-154/Proxy_Web_App_Back-end | develop | `b157c39` | Implementar registro y consulta de conteos fisicos | Desarrollo de las operaciones de registro y consulta de conteos físicos. | 09/11/2026 |
| Bleim-154/Proxy_Web_App_Back-end | develop | `aa9cf47` | Agregar consulta de mermas | Incorporación de la consulta de mermas registradas. | 09/11/2026 |
| Bleim-154/Proxy_Web_App_Back-end | develop | `d0404bb` | Implementar registro seguro de mermas | Desarrollo del registro de mermas y sus validaciones operativas; el mensaje no acredita IAM. | 09/11/2026 |
| Bleim-154/Proxy_Web_App_Back-end | develop | `07735db` | Agregar consulta de movimientos de inventario | Incorporación de consultas para el historial de movimientos de inventario. | 09/11/2026 |
| Bleim-154/Proxy_Web_App_Back-end | develop | `520735f` | Implementar repositorios de Operations | Implementación de repositorios de persistencia para Operations. | 09/11/2026 |
| Bleim-154/Proxy_Web_App_Back-end | develop | `63b6c4f` | Preparar contratos y reglas de Operations | Definición de contratos y reglas de negocio del contexto Operations. | 09/11/2026 |
| yowuan/Proxy_Web_App_Back-end | develop | `791337e` | Merge pull request #5 from SirEthan04/feature/commercial | Integración del desarrollo inicial del bounded context Commercial. | 09/11/2026 |
| yowuan/Proxy_Web_App_Back-end | develop | `76454da` | Implementar endpoints basicos de compras y ventas | Implementación de endpoints REST básicos para compras y ventas. | 09/11/2026 |
| yowuan/Proxy_Web_App_Back-end | develop | `caccfbf` | Agregar repositorios de Commercial | Incorporación de repositorios de persistencia para las operaciones comerciales. | 09/11/2026 |
| SirEthan04/Proxy_Web_App_Back-end | develop | `f84d25e` | Merge pull request #4 from SirEthan04/feature/inventory | Integración de los cambios desarrollados para el bounded context Inventory. | 09/11/2026 |

**EVIDENCIA:**
![Estructura / Backendcommits](recursos/imagenes/backcommitsAW.jpg)

---

**Frontend Web — Integración y mejoras**

Durante el Sprint 3 se realizaron mejoras en el Frontend Web de BodeGo, principalmente en los módulos de inventario, compras y ventas, así como en su integración con los servicios REST del Backend desarrollado en ASP.NET Core.

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| Danysss-cmd/Proxy_Web_App_Front-end | develop | `6c5b207` | Merge pull request #8 from SirEthan04/feature/deploy-render-frontend | Integración de la rama de preparación del Frontend Vue para Render. | 13/11/2026 |
| Danysss-cmd/Proxy_Web_App_Front-end | develop | `c5f7ebc` | Preparar frontend Vue para despliegue en Render | Ajustes de configuración destinados al despliegue del Frontend Vue en Render. | 13/11/2026 |
| Danysss-cmd/Proxy_Web_App_Front-end | develop | `c7a5abb` | Merge pull request #6 from SirEthan04/feature/integracion-operations | Integración de cambios relacionados con las interfaces y servicios de Operations. | 11/11/2026 |
| Danysss-cmd/Proxy_Web_App_Front-end | develop | `b733cb2` | Integrar operaciones de inventario con backend ASP.NET Core | Conexión de funcionalidades de Operations del Frontend con el Backend ASP.NET Core. | 11/11/2026 |
| Danysss-cmd/Proxy_Web_App_Front-end | develop | `c3f4c5e` | Merge pull request #4 from SirEthan04/feature/integracion-backend | Integración de cambios orientados al consumo de servicios del Backend. | 10/11/2026 |
| Danysss-cmd/Proxy_Web_App_Front-end | develop | `6c8e7ab` | Merge pull request #3 from SirEthan04/feature/commercial-purchases-sales | Integración de mejoras del flujo de compras y ventas en el Frontend. | 10/11/2026 |
| Danysss-cmd/Proxy_Web_App_Front-end | develop | `e260ef5` | Integrar productos y categorias con backend ASP.NET Core | Conexión de las pantallas de productos y categorías con servicios ASP.NET Core. | 10/11/2026 |
| Danysss-cmd/Proxy_Web_App_Front-end | develop | `dcc7782` | chore: clean up project structure for BodeGo presentation | Organización de la estructura del proyecto para su presentación y mantenimiento. | 07/11/2026 |
| Danysss-cmd/Proxy_Web_App_Front-end | develop | `87388f6` | feat(commercial): complete purchases sales and intuitive inventory workflows | Avances en flujos visuales de compras y ventas y su interacción con el inventario. | 06/11/2026 |
| Danysss-cmd/Proxy_Web_App_Front-end | develop | `6f3c7ff` | feat(inventory): add interactive stock workflows and verifiable reports | Mejoras en los flujos interactivos del inventario; el commit también menciona reportes, reservados para Sprint 4. | 04/11/2026 |
| Danysss-cmd/Proxy_Web_App_Front-end | develop | `066940d` | refactor(shared): centralize Axios configuration | Centralización de la configuración HTTP de Axios para el consumo de servicios desde Vue. | 04/11/2026 |

**EVIDENCIA:**
![Estructura / Frontendcommits](recursos/imagenes/frontcommitsAW.jpg)

----

**Landing Page — Mejoras de presentación de BodeGo**

Durante el Sprint 3 se actualizaron las secciones y el contenido visual de la Landing Page de **Aplicaciones Web**, con el propósito de mostrar mejor la propuesta de BodeGo y las pantallas de su Frontend Vue. Las contribuciones se registraron en la rama `main` del repositorio de Landing Page.

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| yowuan/Proxy_App_Web_LandingPage | main | `45c61fd` | Merge pull request #2 from SirEthan04/feature/nuevos-cambios | Integración a `main` de la rama `feature/nuevos-cambios`, correspondiente a modificaciones adicionales de la Landing Page. | 13/11/2026 |
| yowuan/Proxy_App_Web_LandingPage | main | `c113c83` | Agrega nuevas modificaciones a la landing page | Incorporación de nuevas modificaciones a la Landing Page; el mensaje no especifica los archivos ni las secciones afectadas. | 13/11/2026 |
| yowuan/Proxy_App_Web_LandingPage | main | `44689ed` | Merge pull request #1 from SirEthan04/feature/landing-update | Integración a `main` de la rama `feature/landing-update` con la actualización de la Landing Page. | 13/11/2026 |
| yowuan/Proxy_App_Web_LandingPage | main | `ca1087e` | Agrega la nueva version de la landing page | Incorporación de una nueva versión de la Landing Page, según el mensaje del commit. | 13/11/2026 |

**EVIDENCIA:**
![Estructura / Landingcommits](recursos/imagenes/landingcommitsAW.jpg)

---

#### 5.2.3.5. Execution Evidence for Sprint Review

---

Durante el Sprint 3 se realizaron mejoras en el Frontend Web de BodeGo, desarrollado con Vue 3, fortaleciendo las interfaces de inventario y las operaciones comerciales de compras y ventas. Asimismo, se avanzó en la integración de estos módulos con los servicios REST del Backend ASP.NET Core.

**Evidencias de la Landing Page**

Durante este sprint se incorporaron mejoras en la presentación visual de BodeGo, permitiendo mostrar de manera más clara las características de la plataforma y sus principales módulos.

![Estructura / landingmejora ](recursos/imagenes/landingUp1.jpg)

![Estructura / landingmejora ](recursos/imagenes/landingUp2.jpg)

![Estructura / landingmejora ](recursos/imagenes/landingUp3.jpg)

![Estructura / landingmejora ](recursos/imagenes/landingUp4.jpg)

---

**Evidencias del Frontend Web**

En el Frontend Web se continuó con la implementación y mejora de las interfaces del sistema, optimizando la interacción de los usuarios con las funcionalidades disponibles.

![Estructura / selecuser](recursos/imagenes/selecuser.jpg)

![Estructura / categorias](recursos/imagenes/categorias_bodego_av3.jpg)

![Estructura / movimientos](recursos/imagenes/movimientos_bodego_av3.jpg)

---

**Evidencias del Backend**

En el Backend se desarrollaron servicios REST utilizando Java y Spring Boot para gestionar la información y las operaciones principales de BodeGo.

![Estructura / movimientos](recursos/imagenes/swagger1.jpg)

![Estructura / movimientos](recursos/imagenes/swagger2.jpg)

![Estructura / movimientos](recursos/imagenes/swagger3.jpg)

![Estructura / movimientos](recursos/imagenes/swagger4.jpg)

![Estructura / movimientos](recursos/imagenes/swagger5.jpg)

---

#### 5.2.3.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 3 se avanzó en el desarrollo y la documentación de los servicios REST del Backend de BodeGo, implementado con **ASP.NET Core y C#**. La API incorpora operaciones relacionadas con productos, categorías, lotes, movimientos de inventario, mermas, conteos físicos, compras, ventas, alertas, reportes y usuarios. La documentación técnica se presenta mediante **OpenAPI y Scalar**.

A continuación, se detallan los métodos HTTP y endpoints identificados en el código, utilizando las Technical Stories definidas para este Sprint (**TS01–TS09 y TS16**). Las TS01–TS09 identifican los contratos REST correspondientes a sus respectivos módulos. TS16 se utiliza para la documentación transversal en OpenAPI/Scalar de otros endpoints existentes, sin atribuirle su implementación funcional.

---

**Servicios REST documentados en OpenAPI y Scalar**

| **Technical Story** | **Módulo** | **Método HTTP** | **Endpoint** | **Descripción** |
|---|---|---|---|---|
| TS01 | Productos | GET | `/api/v1/products` | Consultar el listado de productos registrados. |
| TS01 | Productos | POST | `/api/v1/products` | Registrar un nuevo producto en el catálogo. |
| TS01 | Productos | GET | `/api/v1/products/{id}` | Consultar la información de un producto mediante su identificador. |
| TS02 | Categorías | GET | `/api/v1/categories` | Consultar el listado de categorías registradas. |
| TS02 | Categorías | POST | `/api/v1/categories` | Registrar una nueva categoría de productos. |
| TS02 | Categorías | GET | `/api/v1/categories/{id}` | Consultar una categoría mediante su identificador. |
| TS03 | Lotes | GET | `/api/v1/products/{id}/lots` | Consultar los lotes asociados a un producto y sus existencias. |
| TS03 | Stock bajo | GET | `/api/v1/products/low-stock` | Consultar los productos con existencias bajas. |
| TS04 | Movimientos de inventario | GET | `/api/v1/inventory-movements` | Consultar el historial de entradas y salidas del inventario. |
| TS05 | Mermas | GET | `/api/v1/wastes` | Consultar las mermas registradas en el inventario. |
| TS05 | Mermas | POST | `/api/v1/wastes` | Registrar una merma indicando el producto, la cantidad perdida y el motivo. |
| TS06 | Conteos físicos | POST | `/api/v1/inventory-counts` | Registrar un conteo físico de productos. |
| TS06 | Conteos físicos | GET | `/api/v1/inventory-counts/{id}` | Consultar los detalles de un conteo físico mediante su identificador. |
| TS07 | Compras | POST | `/api/v1/purchases` | Registrar una compra en estado borrador. |
| TS07 | Compras | GET | `/api/v1/purchases` | Consultar el listado de compras registradas. |
| TS07 | Compras | GET | `/api/v1/purchases/{id}` | Consultar el detalle de una compra mediante su identificador. |
| TS08 | Ventas | POST | `/api/v1/sales` | Registrar una venta en estado borrador. |
| TS08 | Ventas | GET | `/api/v1/sales` | Consultar el listado de ventas registradas. |
| TS08 | Ventas | GET | `/api/v1/sales/{id}` | Consultar el detalle de una venta mediante su identificador. |
| TS09 | Confirmación de compras | POST | `/api/v1/purchases/{id}/confirm` | Confirmar una compra, incrementar las existencias y registrar movimientos de entrada. |
| TS09 | Confirmación de ventas | POST | `/api/v1/sales/{id}/confirm` | Confirmar una venta, descontar existencias y registrar movimientos de salida. |
| TS16 | Alertas | GET | `/api/v1/alerts` | Consultar las alertas disponibles mediante la API. |
| TS16 | Alertas | GET | `/api/v1/alerts/{id}` | Consultar una alerta mediante su identificador. |
| TS16 | Reportes de ventas | GET | `/api/v1/reports/sales-summary` | Obtener un resumen de ventas confirmadas con filtros opcionales de fecha. |
| TS16 | Productos más vendidos | GET | `/api/v1/reports/top-products` | Consultar los productos más vendidos mediante un ranking. |
| TS16 | Autenticación | POST | `/api/v1/auth/login` | Autenticar las credenciales de un usuario. |
| TS16 | Autenticación | GET | `/api/v1/auth/me` | Consultar la información del usuario autenticado. |
| TS16 | Usuarios | POST | `/api/v1/users` | Registrar un nuevo usuario en el sistema. |
| TS16 | Usuarios | GET | `/api/v1/users` | Consultar el listado de usuarios registrados. |
| TS16 | Usuarios | GET | `/api/v1/users/{id}` | Consultar la información de un usuario mediante su identificador. |
| TS16 | Roles | GET | `/api/v1/roles` | Consultar el listado de roles disponibles. |
| TS16 | Roles | GET | `/api/v1/roles/{id}` | Consultar la información de un rol mediante su identificador. |
| TS16 | Documentación OpenAPI | GET | `/openapi/v1.json` | Consultar la especificación OpenAPI de los servicios publicados. |
| TS16 | Documentación Scalar | GET | `/scalar` | Acceder a la documentación interactiva de la API. |
| TS16 | Documentación Scalar | GET | `/scalar/v1` | Acceder a la documentación Scalar de la versión `v1`. |

---

**EVIDENCIA: Documentación de servicios con Scalar**

![Documentación de servicios REST - Evidencia 1](recursos/imagenes/endpointsEv1.jpg)

![Documentación de servicios REST - Evidencia 2](recursos/imagenes/endpointsEv2.jpg)

![Documentación de servicios REST - Evidencia 3](recursos/imagenes/endpointsEv3.jpg)

![Documentación de servicios REST - Evidencia 4](recursos/imagenes/endpointsEv4.jpg)

---

#### 5.2.3.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 3 se realizaron actividades de configuración y despliegue de los componentes de BodeGo utilizando la plataforma Render. El Backend, desarrollado con ASP.NET Core y C#, se preparó para ejecutarse mediante Docker y conectarse a una base de datos MySQL externa. Asimismo, se configuró y publicó el Frontend Web, desarrollado con Vue 3 y Vite, como un sitio estático conectado a la dirección pública de la API.

A continuación, se describen los pasos realizados para el despliegue de ambos componentes, incluyendo la vinculación con los repositorios de GitHub, la configuración de las variables de entorno, los parámetros de construcción y la verificación del estado de publicación en Render.

---

**Despliegue del Backend**

**Paso 1. Vinculación del repositorio del Backend en Render**

Se inició la creación de un nuevo servicio web en Render y se seleccionó como origen el repositorio de GitHub `SirEthan04/Proxy_Web_App_Back-end`. Esta vinculación permite utilizar el código fuente del Backend para realizar el proceso de construcción y despliegue de la API REST.

![Selección del repositorio del Backend en Render](Recursos/images/backdeployAW1.jpg)

*Vinculación del repositorio de GitHub del Backend con Render.*

**Paso 2. Configuración general del servicio y de Docker**

Se configuró un servicio web destinado a ejecutar el Backend de BodeGo mediante Docker. Durante esta etapa se definieron los parámetros generales del servicio, incluyendo su nombre, repositorio de origen y rama de desarrollo.

La configuración utilizada para el despliegue corresponde al servicio `bodego-api`, vinculado con la rama `develop` del repositorio y ubicado en la región Virginia (US East).

![Configuración inicial del servicio Backend](Recursos/images/backdeployAW2.jpg)

*Configuración inicial del servicio web y selección de Docker como entorno de ejecución.*

![Configuración del Backend con Docker](Recursos/images/backdeployAW3.jpg)

*Configuración del servicio `bodego-api` y selección de la rama `develop`.*

**Paso 3. Selección del plan de ejecución y configuración del entorno**

Se seleccionó el plan Free de Render para alojar el servicio Backend. Asimismo, se configuraron las variables `ASPNETCORE_ENVIRONMENT` y `DOTNET_ENVIRONMENT` con el valor `Production`, estableciendo el entorno de ejecución de la aplicación ASP.NET Core.

![Selección del plan de despliegue](Recursos/images/backdeployAW4.jpg)

*Selección del plan de ejecución y configuración del entorno Production.*

**Paso 4. Configuración de variables de autenticación**

Se registraron las variables de entorno necesarias para la configuración de autenticación JWT, incluyendo `Jwt__Issuer`, `Jwt__Audience`, `Jwt__LifetimeMinutes` y `Jwt__SigningKeyBase64`.

Esta configuración permite establecer los parámetros de emisión, destinatario, duración y firma de los tokens de autenticación sin colocar los valores sensibles directamente en el código fuente.

![Configuración de variables JWT](Recursos/images/backdeployAW5.jpg)

*Configuración de las variables de autenticación JWT en Render, con el valor secreto oculto.*

**Paso 5. Configuración de la conexión a MySQL**

Se configuró la variable `ConnectionStrings__DefaultConnection` para establecer los parámetros de conexión entre el Backend y una base de datos MySQL externa.

Esta variable reúne la información necesaria para identificar el servidor, la base de datos y las credenciales utilizadas por la aplicación para acceder al sistema de persistencia.

![Configuración de conexión a MySQL](Recursos/images/backdeployAW6.jpg)

*Configuración de la cadena de conexión MySQL mediante variables de entorno, con los datos de acceso ocultos.*

**Paso 6. Configuración de CORS para la comunicación con el Frontend**

Se incorporó la variable `Cors__AllowedOrigins__0` para definir los orígenes autorizados a realizar solicitudes HTTP desde el navegador hacia el Backend.

La configuración mostrada incluye un origen correspondiente al entorno local de desarrollo. Para completar la integración con el Frontend publicado en Render, debe verificarse también que su dominio público esté autorizado.

![Configuración de CORS](Recursos/images/backdeployAW7.jpg)

*Configuración de variables de entorno y CORS para el Backend de BodeGo.*

**Paso 7. Ejecución y verificación del despliegue del Backend**

Una vez completada la configuración, Render ejecutó el proceso de despliegue del Backend. En los registros se observa el inicio de la aplicación ASP.NET Core, la ejecución en el entorno Production y la habilitación del servidor HTTP.

Finalmente, Render mostró el estado **Deploy succeeded / Live**, confirmando que el servicio había sido publicado.

![Despliegue exitoso del Backend](Recursos/images/backdeployAW8.jpg)

*Confirmación del despliegue exitoso del Backend y visualización de sus registros de ejecución en Render.*

---

**Despliegue del Frontend Web**

**Paso 8. Creación del sitio estático y vinculación con GitHub**

Para realizar el despliegue del Frontend Web de BodeGo, se creó un nuevo Static Site en Render, vinculado con el repositorio `SirEthan04/Proxy_Web_App_Front-end`.

Se configuró el sitio con el nombre `bodego-frontend` y se seleccionó la rama `develop` como origen del despliegue.

Además, se estableció el comando de construcción `npm ci && npm run build` y se definió `dist` como directorio de publicación, correspondiente a los archivos estáticos generados por Vite.

![Configuración del Frontend en Render](Recursos/images/frontdeployAW1.jpg)

*Configuración del repositorio, rama, comando de construcción y directorio de publicación del Frontend Web.*

**Paso 9. Configuración de la conexión del Frontend con el Backend**

Se registró la variable de entorno `VITE_API_BASE_URL`, que permite definir la dirección base utilizada por el Frontend para comunicarse con la API REST de BodeGo.

Esta configuración permite que la aplicación Vue utilice la dirección del servicio Backend durante su construcción para el entorno de publicación.

![Configuración de variable de entorno del Frontend](Recursos/images/frontdeployAW2.jpg)

*Configuración de la variable `VITE_API_BASE_URL` con la dirección del Backend de BodeGo.*

**Paso 10. Ejecución y verificación del despliegue del Frontend**

Después de completar la configuración, Render ejecutó el proceso de construcción de la aplicación Vue mediante Vite.

En los registros se observa la transformación de los módulos y la generación de los archivos estáticos de producción. Posteriormente, Render completó la publicación del sitio y mostró el estado **Deploy succeeded / Live**.

Este resultado confirma que el Frontend Web de BodeGo fue construido y publicado correctamente como un sitio estático.

![Despliegue exitoso del Frontend](Recursos/images/frontdeployAW3.jpg)

*Confirmación del despliegue exitoso del Frontend Web y registros de construcción de Vite en Render.*

---

#### 5.2.3.8. Team Collaboration Insights during Sprint

Durante el Sprint 3, los integrantes del equipo de BodeGo colaboraron en el desarrollo de los servicios REST del Backend y en la incorporación de mejoras en el Frontend Web y la Landing Page. Las actividades se organizaron de acuerdo con las responsabilidades establecidas en el Sprint Planning, priorizando la implementación de funcionalidades relacionadas con la gestión de productos, inventario, operaciones comerciales y la integración de los distintos componentes del sistema.

La colaboración se gestionó mediante GitHub, utilizando ramas de desarrollo, commits y Pull Requests para organizar e integrar los cambios realizados. Estas prácticas permitieron mantener un seguimiento de las contribuciones y facilitar el trabajo conjunto entre los integrantes del equipo.

Para evidenciar la participación durante el sprint, se presentan las estadísticas de GitHub Insights, los registros de Contributors y los historiales de commits correspondientes a los tres repositorios del proyecto.

**Colaboración en la Landing Page**

Durante el Sprint 3 se realizaron mejoras en la Landing Page de BodeGo, orientadas a actualizar la presentación visual de la plataforma y mostrar las principales funcionalidades del Frontend desarrollado para Aplicaciones Web. Estas modificaciones incluyeron ajustes en el contenido y la incorporación de imágenes representativas de los módulos del sistema.

Las contribuciones realizadas se organizaron mediante ramas de desarrollo y Pull Requests, permitiendo integrar progresivamente los cambios en la rama principal del repositorio.

**Insights**

![Estructura / Landing Insight](recursos/imagenes/insightsLanAW.jpg)

**Contributors**

![Estructura / Landing Contributors](recursos/imagenes/contributorsLanAW.jpg)

**Commits**

![Estructura / Landing Commits](recursos/imagenes/commitsLanAW.jpg)

---

**Colaboración en el Frontend Web**

En el Frontend Web, desarrollado con Vue 3, el equipo continuó con la mejora de las interfaces y su integración con los servicios REST del Backend. Las actividades estuvieron relacionadas principalmente con la gestión de productos, las operaciones de inventario y los procesos comerciales de compras y ventas.

Asimismo, se realizaron ajustes en la experiencia de usuario, la navegación y la comunicación con la API, buscando facilitar la interacción con las funcionalidades disponibles. El uso de ramas de desarrollo y Pull Requests permitió organizar las modificaciones e integrar los avances de manera progresiva.

**Insights**

![Estructura / Front Insight](recursos/imagenes/insightsFronAW.jpg)

**Contributors**

![Estructura / Front Contributors](recursos/imagenes/contributorsFronAW.jpg)

**Commits**

![Estructura / Front Commits](recursos/imagenes/commitsFronAW.jpg)

---

**Colaboración en el Backend**

Durante el Sprint 3, el equipo trabajó en la implementación de los servicios REST del Backend de BodeGo, utilizando ASP.NET Core y C#, con Entity Framework Core y MySQL para la persistencia de datos.

Las actividades se concentraron principalmente en los bounded contexts Inventory, Operations y Commercial, mediante el desarrollo de endpoints para la gestión de productos y categorías, consulta de lotes, movimientos de inventario, registro de mermas, conteos físicos y operaciones de compras y ventas.

También se avanzó en la integración de los servicios, la implementación de validaciones y la documentación de la API mediante OpenAPI y Scalar. El trabajo colaborativo se organizó a través de ramas y Pull Requests, facilitando la incorporación de los cambios desarrollados por los integrantes del equipo.

**Insights**

![Estructura / Back Insight](recursos/imagenes/insightsBackAW.jpg)

**Contributors**

![Estructura / Back Contributors](recursos/imagenes/contributorsBackAW.jpg)

**Commits**

![Estructura / Back Commits](recursos/imagenes/commitsBackAW.jpg)

---


## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

#### Preguntas para el Segmento 1: Administradores o Dueños de Minimarkets

**Datos del entrevistado**

1. ¿Cuál es tu nombre completo?
2. ¿Qué edad tienes y en qué distrito resides?
3. ¿Cuál es tu función dentro del minimarket o negocio?

**Validación de la Landing Page**

1. Después de revisar la Landing Page, ¿qué entiendes que ofrece BodeGo y cuál crees que es su propósito?
2. ¿Qué beneficios o funcionalidades presentadas consideras más útiles para administrar tu negocio?

**Validación del Frontend**

3. **Dashboard:** Al observar los indicadores del panel principal, ¿qué tan fácil te resulta identificar el estado general del inventario?
4. **Productos y categorías:** Al buscar y revisar un producto, ¿qué tan sencillo te resulta encontrar su información y comprender cómo está organizado el catálogo?
5. **Lotes:** Al consultar los lotes de un producto, ¿qué tan clara te parece la información sobre cantidades y fechas de vencimiento?
6. **Alertas:** Al revisar las alertas de inventario, ¿puedes identificar fácilmente qué productos necesitan atención y por qué?
7. **Auditoría:** Al explorar los registros de auditoría, ¿consideras que la información presentada te permitiría realizar un seguimiento de las operaciones del negocio?
8. **Recomendaciones y ofertas:** Después de explorar estas secciones, ¿qué tan claras te resultan las opciones para consultar recomendaciones y crear ofertas para determinados productos?
9. **Gestión de negocios:** Al revisar las opciones para administrar la información del negocio, ¿qué tan fácil te resulta comprender las acciones disponibles?
10. **Evaluación general:** Después de utilizar BodeGo, ¿qué funcionalidad consideras más útil para administrar tu minimarket y qué mejorarías de la aplicación?

#### Preguntas para el Segmento 2: Empleados de Minimarkets

**Datos del entrevistado**

1. ¿Cuál es tu nombre completo?
2. ¿Qué edad tienes y en qué distrito resides?
3. ¿Cuál es tu función dentro del minimarket o negocio?

**Validación de la Landing Page**

1. Después de revisar la Landing Page, ¿qué entiendes que permite hacer BodeGo dentro de un minimarket?
2. ¿Qué funcionalidad presentada en la página consideras que podría facilitar más tus actividades diarias?

**Validación del Frontend**

3. **Navegación:** Al ingresar a la aplicación, ¿qué tan sencillo te resulta encontrar las diferentes secciones y comprender para qué sirven?
4. **Consulta de productos:** Al buscar un producto específico, ¿qué tan fácil te resulta encontrarlo y revisar su información?
5. **Lotes:** Al consultar los lotes de un producto, ¿puedes identificar claramente las cantidades disponibles y las fechas de vencimiento?
6. **Movimientos de inventario:** Al explorar el registro de entradas y salidas, ¿qué tan sencillo te resulta comprender el proceso para registrar un movimiento?
7. **Conteos físicos:** Al realizar un conteo físico de ejemplo, ¿qué tan claras te resultan las cantidades que debes ingresar y la información que muestra el sistema?
8. **Ajustes y solicitudes de corrección:** Al explorar estas opciones, ¿comprendes cuándo utilizarías una solicitud de corrección y qué información deberías proporcionar?
9. **Mermas:** Al intentar registrar una merma, ¿qué tan sencillo te resulta identificar el producto, indicar la cantidad y seleccionar el motivo de la pérdida?
10. **Evaluación general:** Después de utilizar BodeGo, ¿qué actividad te pareció más sencilla, cuál te generó dificultades y qué mejorarías para facilitar tu trabajo diario?

### 5.3.2. Registro de Entrevistas

#### Segmento Administradores

| |
|---|
| ![Entrevista de validación a Ian Figueroa](recursos/imagenes/ianvalidation.png) |
| **Nombres y apellidos:** Ian figueroa <br> **Edad:** 21 años <br> **Distrito:** Pueblo libre <br><br> **Resumen de la entrevista:** <br><br> El entrevistado, administrador de un minimarket, participó en la validación de la Landing Page y el Frontend de BodeGo. Consideró que ambas interfaces presentan un diseño agradable, organizado y fácil de comprender. Destacó especialmente la gestión de productos, el control de lotes y las alertas de vencimiento, ya que estas funcionalidades permitirían mantener el inventario ordenado y prevenir pérdidas. <br><br> Durante la exploración del Frontend, señaló que la navegación es sencilla y que la información de productos y lotes resulta clara. Sin embargo, presentó algunas dificultades iniciales para comprender los movimientos de inventario y los conteos físicos. Como mejoras, sugirió incorporar explicaciones breves en ciertas opciones, hacer más visible el botón de acceso a la aplicación y mostrar las alertas importantes directamente en el Dashboard. En general, expresó una opinión favorable de BodeGo y consideró que sería útil para administrar un minimarket. <br><br> **URL:** https://drive.google.com/file/d/1QDDfA513IN4V9-ISeddfb7UXCcF5LJZo/view?usp=sharing |

| |
|---|
| ![Entrevista de validación a Silvia Bravo](recursos/imagenes/silviavalidation.png) |
| **Nombres y apellidos:** Silvia Bravo <br> **Edad:** 49 años <br> **Distrito:** Independencia <br><br> **Resumen de la entrevista:** <br><br> Silvia Bravo, administradora de un minimarket, participó en la validación de la Landing Page y el Frontend de BodeGo. Comprendió que la plataforma permite administrar productos y analizar información del negocio. Destacó especialmente las alertas de vencimiento, ya que considera importante identificar los productos próximos a vencer para evitar pérdidas económicas. <br><br> Durante la exploración del Frontend, señaló que el Dashboard, los productos, categorías y lotes presentan información clara y ordenada, facilitando la identificación de cantidades y fechas de vencimiento. También consideró útiles las alertas de inventario para reconocer problemas de stock y encontró comprensible el proceso de creación de ofertas. Finalmente, expresó satisfacción con la aplicación y no propuso mejoras adicionales durante la entrevista. <br><br> **URL:** https://drive.google.com/file/d/1PbotiWeN0J_HhGiSwgg5suCbzT8MPkfL/view?usp=sharing |

#### Segmento Empleados

| |
|---|
| ![Entrevista de validación a Andres Marzano](recursos/imagenes/andrevalidation.png) |
| **Nombres y apellidos:** Andres Marzano <br> **Edad:** 20 años <br> **Distrito:** San Juan de Lurigancho <br><br> **Resumen de la entrevista:** <br><br> Andrés Marzano, empleado de un minimarket, participó en la validación de la Landing Page y el Frontend de BodeGo. Consideró que la plataforma permite organizar y controlar el inventario de manera sencilla, destacando especialmente la consulta de productos, el control de lotes y las fechas de vencimiento, ya que estas funcionalidades facilitarían las actividades diarias y ayudarían a prevenir pérdidas. <br><br> Durante la exploración del Frontend, señaló que la navegación es intuitiva y que los módulos de productos, movimientos de inventario, conteos físicos y mermas presentan procesos claros y ordenados. Sin embargo, mencionó que inicialmente necesitó explorar con mayor detenimiento la sección de ajustes y solicitudes de corrección. Como mejora, sugirió incorporar pequeñas indicaciones para orientar a los usuarios nuevos. En general, consideró que BodeGo es una aplicación organizada, fácil de utilizar y útil para mejorar el control del inventario. <br><br> **URL:** https://drive.google.com/file/d/1kbf-Qn4dSuX-iFd8flkezSBHotO6Bovf/view?usp=sharing |

| |
|---|
| ![Entrevista de validación a Joseph](recursos/imagenes/josephvalidation.png) |
| **Nombres y apellidos:** Joseph <br> **Edad:** 23 años <br> **Distrito:** Puente Piedra <br><br> **Resumen de la entrevista:** <br><br> Joseph, empleado de un minimarket, participó en la validación de la Landing Page y el Frontend de BodeGo. Consideró que la plataforma es fácil de utilizar y destacó la organización del menú, la consulta de productos y lotes, el registro de movimientos y las mermas. Valoró especialmente la posibilidad de controlar las cantidades disponibles y las fechas de vencimiento. <br><br> Sin embargo, mencionó algunas dificultades iniciales para comprender los conteos físicos, ajustes y solicitudes de corrección. Como mejoras, sugirió incorporar un buscador de productos, resaltar con colores los lotes próximos a vencer y agregar explicaciones breves en algunas funcionalidades. En general, consideró que BodeGo ayudaría a ahorrar tiempo, organizar el inventario y mejorar el control de la mercadería. <br><br> **URL:** https://drive.google.com/file/d/15XCPZ9IbjHR71gtagHLYNYeGB1Hx49IP/view?usp=sharing |

| |
|---|
| ![Entrevista de validación a Pablo Moreno](recursos/imagenes/pablovalidation.jpg) |
| **Nombres y apellidos:** Pablo Moreno <br> **Edad:** 20 años <br> **Distrito:** Callao <br><br> **Resumen de la entrevista:** <br><br> Pablo Moreno, trabajador de un minimarket, participó en la evaluación de la Landing Page y el Frontend de BodeGo. Durante la validación, señaló que la plataforma presenta una interfaz clara y organizada, lo que facilita el acceso a sus diferentes funcionalidades. Destacó principalmente el registro de entradas y salidas de mercadería, la consulta del stock y el control de lotes, ya que estas herramientas permitirían agilizar tareas que actualmente realiza de forma manual o mediante Excel. Asimismo, consideró útil el registro de mermas para mantener un mejor control de los productos dañados o vencidos. <br><br> Por otro lado, indicó que al principio tuvo algunas dudas al utilizar los conteos físicos y las solicitudes de corrección, aunque logró comprender su funcionamiento después de explorarlos. Entre sus sugerencias, mencionó la incorporación de un buscador de productos, avisos más visibles sobre fechas de vencimiento y pequeñas instrucciones para orientar a los nuevos usuarios. Finalmente, expresó una opinión favorable sobre BodeGo, considerando que su implementación podría simplificar las actividades diarias, disminuir las diferencias de inventario y mejorar la organización de los productos dentro del minimarket. <br><br> **URL:** https://drive.google.com/file/d/1kbf-Qn4dSuX-iFd8flkezSBHotO6Bovf/view?usp=sharing |

### 5.3.3. Evaluaciones según heurísticas

**BodeGo - Landing Page y Aplicación Web**

La evaluación se realizó tomando como referencia las entrevistas de validación de los segmentos Administradores y Empleados de minimarkets, considerando las opiniones de Ian Figueroa, Silvia Bravo, Andrés Marzano y Joseph.

#### TAREAS A EVALUAR

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

1. Explorar la Landing Page y comprender la propuesta de valor de BodeGo.
2. Navegar por el Dashboard y consultar los indicadores del inventario.
3. Buscar productos y revisar sus categorías.
4. Consultar lotes y fechas de vencimiento.
5. Revisar alertas y movimientos de inventario.
6. Realizar conteos físicos y gestionar solicitudes de corrección.
7. Registrar mermas.
8. Explorar recomendaciones y ofertas.

#### ESCALA DE SEVERIDAD

Los problemas identificados se clasifican utilizando la siguiente escala:

| Nivel | Descripción                                                                                                         |
| ----- | ------------------------------------------------------------------------------------------------------------------- |
| **1** | **Problema superficial:** No impide utilizar la aplicación y puede resolverse fácilmente.                           |
| **2** | **Problema menor:** Puede generar pequeñas dificultades de uso, pero permite continuar con las actividades.         |
| **3** | **Problema mayor:** Dificulta considerablemente completar una tarea y requiere una corrección prioritaria.          |
| **4** | **Problema muy grave:** Impide continuar utilizando una funcionalidad importante y requiere una corrección urgente. |

#### TABLA RESUMEN

| # | Problema                                                                                                      | Escala de severidad | Heurística / Principio violado     |
| - | ------------------------------------------------------------------------------------------------------------- | :-----------------: | ---------------------------------- |
| 1 | Algunas opciones de conteos físicos, ajustes y solicitudes de corrección requieren mayor orientación inicial. |          2          | Ayuda y documentación              |
| 2 | Las alertas importantes podrían destacarse mejor en el Dashboard.                                             |          2          | Visibilidad del estado del sistema |
| 3 | Los lotes próximos a vencer podrían identificarse más rápidamente mediante indicadores visuales.              |          1          | Reconocimiento antes que recuerdo  |
| 4 | El botón para ingresar a la aplicación desde la Landing Page podría ser más visible.                          |          1          | Reconocimiento antes que recuerdo  |

#### DESCRIPCIÓN DE PROBLEMAS

**PROBLEMA #1: Orientación inicial en conteos físicos y solicitudes de corrección**

**Severidad:** 2
**Heurística relacionada:** Ayuda y documentación.

**Problema:**

Durante las entrevistas, algunos participantes señalaron que inicialmente necesitaron explorar las opciones de conteos físicos, ajustes y solicitudes de corrección para comprender sus diferencias. Sin embargo, después de revisar las funcionalidades, lograron entender su propósito y continuar utilizando la plataforma.

**Recomendación:**

Incorporar pequeñas descripciones o mensajes de ayuda que expliquen cuándo utilizar cada funcionalidad, facilitando el aprendizaje de los usuarios nuevos.

**Captura de pantalla:**
<p align="center">
  <img src="recursos/images/heuristica1.jpg" alt="Evidencia de conteos físicos y solicitudes de corrección" width="650">
</p>

---

**PROBLEMA #2: Visibilidad de alertas importantes en el Dashboard**

**Severidad:** 2
**Heurística relacionada:** Visibilidad del estado del sistema.

**Problema:**

Ian Figueroa sugirió que las alertas más importantes, como los productos con stock bajo o próximos a vencer, tengan mayor presencia en el Dashboard. Esto permitiría identificar rápidamente las situaciones que requieren atención.

**Recomendación:**

Destacar las alertas prioritarias mediante indicadores visuales o tarjetas informativas dentro del panel principal, facilitando su identificación.

**Captura de pantalla:**
<p align="center">
  <img src="recursos/imagenes/heuristica2.jpg" alt="Evidencia de conteos físicos y solicitudes de corrección" width="650">
</p>

---

**PROBLEMA #3: Identificación visual de lotes próximos a vencer**

**Severidad:** 1
**Heurística relacionada:** Reconocimiento antes que recuerdo.

**Problema:**

Joseph consideró que la información de los lotes es clara y fácil de comprender. No obstante, recomendó resaltar los lotes próximos a vencer para identificarlos más rápidamente, sin tener que revisar individualmente todas las fechas.

**Recomendación:**

Incorporar etiquetas o indicadores de color acompañados de texto que permitan diferenciar los lotes vigentes, próximos a vencer y vencidos.

**Captura de pantalla:**
<p align="center">
  <img src="recursos/imagenes/heuristica3.jpg" alt="Evidencia de conteos físicos y solicitudes de corrección" width="650">
</p>

---

**PROBLEMA #4: Visibilidad del acceso a la aplicación desde la Landing Page**

**Severidad:** 1
**Heurística relacionada:** Reconocimiento antes que recuerdo.

**Problema:**

Ian Figueroa destacó que la Landing Page presenta información organizada y un diseño agradable. Como oportunidad de mejora, comentó que el botón para ingresar a BodeGo podría ser más visible para los usuarios que visitan la página por primera vez.

**Recomendación:**

Destacar el botón **«Ingresar a BodeGo»** en una ubicación visible de la Landing Page, facilitando el acceso directo a la aplicación.

**Captura de pantalla:**
<p align="center">
  <img src="recursos/imagenes/heuristica4.jpg" alt="Evidencia de conteos físicos y solicitudes de corrección" width="650">
</p>

#### CONCLUSIONES DE LA EVALUACIÓN HEURÍSTICA

Las entrevistas de validación reflejaron una percepción positiva sobre la usabilidad de BodeGo. Los participantes destacaron la organización de la información, la facilidad de navegación y la utilidad de las funcionalidades relacionadas con productos, lotes, inventario y alertas de vencimiento.

Se identificaron únicamente **cuatro oportunidades de mejora**, clasificadas con severidades 1 y 2, relacionadas principalmente con la orientación inicial y la visibilidad de información importante.

En general, los entrevistados consideraron que BodeGo es una plataforma comprensible y útil para mejorar la gestión de inventarios en minimarkets. Las recomendaciones recopiladas permitirán perfeccionar la experiencia de usuario sin requerir cambios significativos en la estructura general de la aplicación.


## 5.4. Video About-the-Product

En esta sección se presenta el video de BodeGo, en el cual se comunica la problemática que aborda la plataforma, su propuesta de valor y las principales funcionalidades destinadas a mejorar la gestión de inventarios y las operaciones de los minimarkets.

**Video About-the-Product:** https://youtu.be/VCTRhL0PRmo

# Conclusiones

## Conclusiones y recomendaciones
El proyecto BodeGo busca solucionar el problema de la falta de control y organización del inventario en los minimarkets, especialmente en la gestión de productos perecibles, diferencias de stock y pérdidas ocasionadas por vencimientos. A través de una plataforma web de gestión, se permite que los Administradores y Empleados puedan realizar sus actividades de manera más ordenada, rápida y eficiente.

Las validaciones realizadas permitieron confirmar que los usuarios presentan dificultades al utilizar métodos manuales como cuadernos, archivos de Excel o revisiones físicas constantes. Por ello, funcionalidades como el control de inventario, alertas de vencimiento, reportes y gestión de roles representan una solución alineada con las necesidades identificadas durante el proceso de investigación.

La aplicación busca ofrecer una experiencia sencilla e intuitiva, enfocándose en reducir el tiempo empleado en tareas operativas y mejorar la toma de decisiones dentro del minimarket. Entre sus principales características destacan:

- Control actualizado del inventario.
- Alertas sobre productos próximos a vencer.
- Reportes para conocer el estado del negocio.
- Gestión de usuarios según sus responsabilidades.

Estas funcionalidades están diseñadas para disminuir los errores en el registro de productos, evitar pérdidas innecesarias y brindar mayor visibilidad sobre el estado real del inventario. De esta manera, BodeGo permite que los Administradores puedan tomar decisiones más oportunas y que los Empleados puedan realizar sus tareas de forma rápida y organizada.

---

# Video About-the-Team

---

# Bibliografía

Angular. (s. f.). *What is Angular?* Angular Documentation. https://angular.dev/overview

Brown, S. (s. f.). *The C4 model for visualising software architecture*. https://c4model.com/

ESIC Business & Marketing School. (2023, mayo). *HTML5: qué es, características y cómo funciona*. ESIC. https://www.esic.edu/rethink/tecnologia/html5-que-es-caracteristicas-y-como-funciona-c

Evans, E. (2003). *Domain-driven design: Tackling complexity in the heart of software*. Addison-Wesley Professional. https://www.oreilly.com/library/view/domain-driven-design-tackling/0321125215/

GitHub. (s. f.). *About pull requests*. GitHub Docs. https://docs.github.com/en/pull-requests/get-started/about-pull-requests

Gothelf, J., & Seiden, J. (2021). *Lean UX: Designing great products with agile teams* (3.ª ed.). O'Reilly Media. https://www.oreilly.com/library/view/lean-ux-3rd/9781098116293/

JetBrains. (s. f.). *IntelliJ IDEA*. https://www.jetbrains.com/es-es/idea/download/

MDN Web Docs. (s. f.-a). *CSS*. Mozilla. https://developer.mozilla.org/es/docs/Web/CSS

MDN Web Docs. (s. f.-b). *JavaScript*. Mozilla. https://developer.mozilla.org/es/docs/Web/JavaScript

Microsoft. (s. f.). *TypeScript documentation*. https://www.typescriptlang.org/docs/

OpenAPI Initiative. (2025, 19 de septiembre). *OpenAPI Specification* (versión 3.1.2). https://spec.openapis.org/oas/v3.1

PostgreSQL Global Development Group. (s. f.). *PostgreSQL documentation*. https://www.postgresql.org/docs/

Schwaber, K., & Sutherland, J. (2020). *The Scrum Guide: The definitive guide to Scrum: The rules of the game*. https://scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-US.pdf

Spring. (s. f.). *Spring Boot reference documentation*. https://docs.spring.io/spring-boot/reference/

Universidad Peruana de Ciencias Aplicadas. (2026). *Enunciado del trabajo final: Desarrollo de Aplicaciones Open Source (1ASI0729), ciclo académico 2026-20* (versión 1.0) [Documento académico del curso].

---

# Anexos
---
Enlace de Figma: https://www.figma.com/design/lkkyQ42TCu70ZypY4hiuMi/Figma-Proxy?node-id=4-2&t=ZKhGhyVBP4tT2C8g-1
---
Nuestro link del miro: https://miro.com/app/board/uXjVHm55KfI=/
---
Nuestro repositorio de documentación: https://github.com/SirEthan04/Proxy_App_Web
---
Nuestro repositorio de landingpage: https://sirethan04.github.io/Proxy_App_Web_LandingPage/
---
Nuestro repositorio de frontend: https://github.com/SirEthan04/Proxy_Web_App_Front-end
---
Nuestro repositorio de web aplication: https://github.com/SirEthan04/Proxy_Web_App_Back-end
---
