# Carátula

<p align="center">
  <img src="http://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" width="100" alt="Descripción">
</p>

<p align="center"><b>Universidad Peruana de Ciencias Aplicadas S.A.C.</b></p>
<p align="center"><b>Ingeniería de Software</b></p>
<p align="center"><b>Ciclo: 5</b></p>
<p align="center"><b>1ASI0730-2620</b></p>
<p align="center"><b>Aplicaciones Web</b></p>
<p align="center"><b>NRC: 8074</b></p>
<p align="center"><b>Docente: Alex Humberto Sánchez Ponce</b></p>

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
| U20241G610 | Chavez Sandoval, Dany Yohel |
| U202421082 | Saravia Hiso, Johan Álvaro |
| [Código 3] | Rojas Huaranga, Diego Rances |

---

* **Fecha:** 12/09/2026

---

# Registro de Versiones del Informe

* **Project Report Collaboration Insights**

---

# Contenido

## Tabla de Contenidos

* [Carátula](#carátula)
* [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
* [Contenido](#contenido)
* [Student Outcome](#student-outcome)

---

# Student Outcome

---

# Capítulo I: Introducción
## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**Nombre del Startup:** Proxy  

**Nombre del Producto:** BodeGo  

**Enfoque de Negocios:** Aplicación web para la gestión integral de inventario, mermas y control operativo interno en minimarkets.  

**Propuesta de Valor:** BodeGo es una solución web de gestión interna que optimiza el control de stock y reduce las mermas por productos perecibles mediante un sistema de doble rol operativo. La plataforma permite al Administrador visualizar reportes, configurar el sistema y lanzar ofertas estratégicas, mientras que facilita al Empleado la actualización rápida de stock y el registro de las operaciones diarias en el punto de venta.  

**Mercado Objetivo:** El producto está dirigido al personal operativo y directivo de minimarkets, dividiendo a sus usuarios en dos segmentos clave: Administradores (dueños o gestores del negocio) y Empleados (personal de atención y almacén).


### 1.1.2. Perfiles de integrantes del equipo
| **Mateo Caldas Bravo (U20241G404)** |
| :--- |
| Soy un estudiante de 19 años cursando el quito ciclo de la carrera de Ingeniería de Software. Considero que mi capacidad de tener un enfoque analítico y la eficiencia de desarrollar una solución eficiente. Mis habilidades blandas me permiten empatizar con los usuarios y acompañado de mi resiliencia, compromiso y productividad me permiten realizar propuestas mas estructuradas y optimas. |
| Foto |

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática

En el sector del comercio minorista, específicamente en los minimarkets, la gestión operativa se realiza de manera empírica y manual. Esta falta de digitalización genera una baja visibilidad sobre el estado real de los inventarios, impactando directamente en la rentabilidad del negocio debido a la acumulación de mermas y a una deficiente comunicación interna entre el personal.

**Técnica de las 5 'W's y 2 'H's:**

**Who (¿Quién?):** Personal operativo y directivo de los minimarkets, dividido en dos roles clave: Administradores (dueños o gestores) y Empleados (personal de atención y almacén).  

**What (¿Qué?):** Deficiente gestión del inventario perecible que ocasiona mermas por productos vencidos, sumado a la falta de un sistema centralizado de control operativo y actualización de stock en tiempo real.  

**Where (¿Dónde?):** En las instalaciones, almacenes y puntos de venta de los minimarkets de Lima Metropolitana.  

**When (¿Cuándo?):** Ocurre de forma continua durante la operación diaria, intensificándose al momento de la recepción de mercadería, el despacho en caja y la rotación de productos en anaqueles.  

**Why (¿Por qué?):** Debido a la ausencia de herramientas digitales accesibles para el control de stock, la falta de asignación de permisos según el rol operativo y la dependencia de métodos manuales para identificar fechas de vencimiento y registrar operaciones.  

**How (¿Cómo?):** El Administrador gestiona el negocio sin visibilidad centralizada de reportes ni capacidad para lanzar ofertas estratégicas de liquidación. A su vez, el Empleado realiza el control de inventario mediante anotaciones físicas o de memoria, lo que dificulta detectar a tiempo los productos próximos a caducar e impide mantener el stock actualizado durante la jornada.  

**How Much (¿Cuánto?):** Pérdidas económicas constantes para el minimarket por mermas no detectadas a tiempo, descuadres de stock en el punto de venta y una reducción en el margen de ganancia al no poder liquidar estratégicamente la mercadería de baja rotación.

### 1.2.2 Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

### Preguntas para el Segmento 1: Administrador (Dueño / Gestor del Minimarket)

1. ¿Cómo controla actualmente lo que entra, sale y se vende en su minimarket?
2. ¿De qué manera le da permisos o tareas a sus empleados para que registren los productos?
3. ¿Cada cuánto revisa qué productos están por vencer y cómo se da cuenta de ello?
4. ¿Le ha pasado recientemente que perdió dinero por productos que se vencieron o se malograron? ¿Cómo fue?
5. ¿Qué hace actualmente con la mercadería que no se vende rápido para no perder esa inversión?
6. ¿Cómo sabe si el negocio está teniendo buenas ganancias o si una oferta funcionó?
7. ¿Cómo decide los precios de los productos y los cambios en su local?
8. ¿Usa algún programa, cuaderno o aplicación para llevar la cuenta de su negocio?
9. ¿Qué es lo más difícil al momento de confiarle el registro de las ventas o del stock a sus empleados?
10. ¿Qué tendría que tener un sistema web para que a usted le sirva de verdad y le evite pérdidas?

### Preguntas para el Segmento 2: Empleado (Personal Operativo / Atención y Almacén)

1. ¿Cuál es la rutina diaria que sigue para registrar la entrada de nueva mercadería y actualizar el stock disponible en anaqueles?
2. ¿De qué manera verifica en el día a día las fechas de caducidad de los productos mientras atiende o reacciona en el almacén?
3. ¿Cómo procede cuando detecta en el mostrador un producto que está vencido, dañado o con bajo stock?
4. ¿Qué dificultades experimenta al momento de registrar las ventas o transacciones diarias durante las horas de mayor afluencia de clientes?
5. ¿Cómo se comunica internamente con el administrador o dueño cuando identifica inconsistencias entre el stock físico y el registro?
6. ¿Qué herramientas o métodos manuales (cuadernos, hojas de cálculo, notas) utiliza actualmente para realizar el conteo de inventario?
7. ¿De qué forma aplica o registra las ofertas y descuentos especiales decididos por la administración al momento de cobrar en caja?
8. ¿Qué problemas o frustraciones suele tener con los sistemas actuales al momento de buscar la disponibilidad o precio de un producto?
9. ¿Cuánto tiempo le toma capacitarse o adaptarse cuando se introduce un cambio en la forma de registrar las operaciones diarias?
10. ¿Qué características debería tener una plataforma web para que su trabajo de registro y actualización de stock sea más rápido y sencillo?

### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping

## 2.4. Big Picture EventStorming

## 2.5. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. User Stories
## 3.2. Impact Mapping
## 3.3. Product Backlog

---

# Capítulo IV: Product Design

## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Design-Level EventStorming
### 4.6.2. Software Architecture Context Diagram
### 4.6.3. Software Architecture Container Diagrams
### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

## 4.8. Database Design
### 4.8.1. Database Diagrams

---

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint n
#### 5.2.1.1. Sprint Planning n
#### 5.2.1.2. Aspect Leaders and Collaborators
#### 5.2.1.3. Sprint Backlog n
#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews
### 5.3.1. Diseño de Entrevistas
### 5.3.2. Registro de Entrevistas
### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product

---

# Conclusiones

## Conclusiones y recomendaciones

---

# Video About-the-Team

---

# Bibliografía

---

# Anexos
