<body>
    <div style="text-align: center; font-weight: bolder">
        <p>Universidad Peruana de Ciencias Aplicadas - Ingeniería de Software - 6 Ciclo</p>
        <img src="./assets/cover/logo-upc.png" alt="logo of UPC"/>
        <p>1ACC0238 - Aplicaciones para Dispositivos Móviles</p>
        <p>Docente: Ing. Jorge Luis Mayta Guillermo</p>   
        <p>Informe de Trabajo Final<p>
        <p>Startup: CampusMov</p>
        <p>Producto: CarPool</p>
    </div>
    <div style="text-align: center; display: flex; flex-direction: column; align-items: center">
        <h3 style="font-weight: bolder">Team Members:</h3>
        <table style="width: fit-content">
            <tr>
                <th style="text-align:center;">Estudiante</th>
                <th style="text-align:center;">Código</th>
            </tr>
            <tr>
                <td>Gutiérrez Soto, Jhosepmyr Orlando</td>
                <td>202317638</td>
            </tr>
            <tr>
                <td>Hernández Tuiro, Eric Ernesto</td>
                <td>20221C857</td>
            </tr>
            <tr>
                <td>Riva Rodríguez, Elmer Augusto</td>
                <td>202220829</td>
            </tr><tr>
                <td>Sanchez Montero, Carlos</td>
                <td>202015274</td>
            </tr>
            <tr>
                <td>Moraloes Quispe, Brayan Smith</td>
                <td>20211f984</td>
            </tr>
        </table>
    </div>
    <p style="text-align: center">Marzo 2025</p>
</body>

<div style="page-break-before: always"></div>

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
|---------|-------|-------|--------------------------------|

<div style="page-break-before: always"></div>

# Project Report Collaboration Insights

* URL del repositorio del Project Report en la organización de GitHub del equipo:
* [https://github.com/CampusMov/Report](https://github.com/CampusMov/Report)

<div style="page-break-before: always"></div>

# Contenido

<!-- TOC -->
* [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
* [Project Report Collaboration Insights](#project-report-collaboration-insights)
* [Contenido](#contenido)
* [Student Outcome](#student-outcome)
  * [**ABET - EAC - Student Outcome 7**](#abet---eac---student-outcome-7)
* [Objetivos SMART](#objetivos-smart)
* [Capítulo I: Presentación](#capítulo-i-presentación)
  * [1.1. Startup Profile](#11-startup-profile)
    * [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    * [1.1.2. Perfiles de los integrantes del equipo](#112-perfiles-de-los-integrantes-del-equipo)
  * [1.2. Solution Profile](#12-solution-profile)
    * [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    * [1.2.2. Lean UX Process](#122-lean-ux-process)
      * [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      * [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      * [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      * [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  * [1.3. Segmentos objetivo](#13-segmentos-objetivo)
    * [*Estudiante conductor*](#estudiante-conductor)
      * [Perfil:](#perfil)
      * [Necesidades:](#necesidades)
    * [*Estudiante pasajero*](#estudiante-pasajero)
      * [Perfil:](#perfil-1)
      * [Necesidades:](#necesidades-1)
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
    * [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  * [2.4. Ubiquitous Language](#24-ubiquitous-language)
* [Capítulo III: Requirements specification](#capítulo-iii-requirements-specification)
  * [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  * [3.2. User Stories](#32-user-stories)
  * [3.3. Impact Mapping](#33-impact-mapping)
  * [3.4. Product Backlog](#34-product-backlog)
* [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  * [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    * [4.1.1. EventStorming](#411-eventstorming)
      * [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
      * [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      * [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    * [4.1.2. Context Mapping](#412-context-mapping)
    * [4.1.3. Software Architecture](#413-software-architecture)
      * [4.1.3.1. Software Architecture Context Level Diagrams](#4131-software-architecture-context-level-diagrams)
      * [4.1.3.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
      * [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
  * [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    * [4.2.1. Bounded Context:](#421-bounded-context)
      * [4.2.1.1. Domain Layer](#4211-domain-layer)
      * [4.2.1.2. Interface Layer](#4212-interface-layer)
      * [4.2.1.3. Application Layer](#4213-application-layer)
      * [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
      * [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      * [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
        * [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
        * [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
* [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
  * [5.1. Product Design](#51-product-design)
    * [5.1.1. Style Guidelines](#511-style-guidelines)
      * [5.1.1.1. General Style Guidelines](#5111-general-style-guidelines)
    * [5.1.2. Information Architecture](#512-information-architecture)
      * [5.1.2.1. Organization Systems](#5121-organization-systems)
      * [5.1.2.2. Labelling Systems](#5122-labelling-systems)
      * [5.1.2.3. SEO Tags and Meta Tags](#5123-seo-tags-and-meta-tags)
      * [5.1.2.4. Searching Systems](#5124-searching-systems)
      * [5.1.2.5. Navigation Systems](#5125-navigation-systems)
    * [5.1.3. Landing Page UI Design](#513-landing-page-ui-design)
      * [5.1.3.1. Landing Page Wireframe](#5131-landing-page-wireframe)
      * [5.1.3.2. Landing Page Mock-up](#5132-landing-page-mock-up)
    * [5.1.4. Mobile Applications UX/UI Design](#514-mobile-applications-uxui-design)
      * [5.1.4.1. Mobile Applications Wireframes](#5141-mobile-applications-wireframes)
      * [5.1.4.2. Mobile Applications Wireflow Diagrams](#5142-mobile-applications-wireflow-diagrams)
      * [5.1.4.3. Mobile Applications Mock-ups](#5143-mobile-applications-mock-ups)
      * [5.1.4.4. Mobile Applications User Flow Diagrams](#5144-mobile-applications-user-flow-diagrams)
      * [5.1.4.5. Mobile Applications Prototyping](#5145-mobile-applications-prototyping)
<!-- TOC -->

<div style="page-break-before: always"></div>

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

## **ABET - EAC - Student Outcome 7**

* Criterio: La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 7.

| Criterio específico                                                                                                                     | Acciones realizadas | Conclusiones |
|-----------------------------------------------------------------------------------------------------------------------------------------|---------------------|--------------|
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software. |                     |              |
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.  |                     |              |

<div style="page-break-before: always"></div>

# Objetivos SMART

En el siguiente cuadro se presentan los objetivos SMART de cada integrante del equipo ; donde cada objetivo debe ser específico, medible, alcanzable, relevante y con un tiempo definido.

| Estudiante                        | Objetivos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Gutiérrez Soto, Jhosepmyr Orlando | <p> **Objetivo 1**: Obtener la certificación oficial AWS Certified Solutions Architect – Associate en un plazo máximo de 6 meses después de graduarme, dedicando al menos 7 horas semanales a estudios avanzados mediante plataformas especializadas (como A Cloud Guru, Pluralsight o AWS Skill Builder), con el fin de consolidar mis conocimientos en arquitecturas escalables y seguras en la nube, y posicionarme como candidato fuerte para roles técnicos en empresas medianas o grandes que trabajen con infraestructura cloud. </p>  <p> **Objetivo 2**: Obtener una posición como Desarrollador Backend en una empresa internacional de tecnología, dentro de los primeros 9 meses posteriores a mi graduación, aplicando a al menos 7 ofertas semanales, mejorando continuamente mi portafolio con 3 proyectos open-source utilizando Java, Spring Boot, PostgreSQL y AWS, y participando en comunidades técnicas (como Meetup, Dev.to o GitHub Discussions) para aumentar mi visibilidad profesional y networking con desarrolladores senior. </p> |
| Riva Rodriguez, Elmer Augusto     | <p> **Objetivo 1**: Conseguir un puesto como Desarrollador Backend en una empresa de tecnología en un plazo máximo de 6 meses después de mi graduación. Para ello, mejoraré mi portafolio con al menos 3 proyectos avanzados utilizando Java y Spring Boot, mantendré un ritmo de 5 aplicaciones semanales a ofertas laborales y expandiré mi red de contactos asistiendo a eventos tecnológicos </p> <p> **Objetivo 2**: Iniciar una maestría en Inteligencia Artificial dentro de los 12 meses posteriores a mi graduación. Para ello, investigaré a cerca de al menos 3 universidades o programas en línea, completando las solicitudes necesarias, a la vez de dedicar al menos 3 horas semanales a la preparación de documentos. </p>| 
Brayan Smith Morales Quispe   | <p> **Objetivo 1**: Desarrollarme como freelance en el desarrollo Frontend usando tecnologias como Angular ya sea con modulos o componentes standalone, vue usando vite, desplegandolas en servicios cloud. Todo esto sera mostrado con mejora continua en mi portafolio.</p>  <p> **Objetivo 2**: Obtener certificaciones en Azure en un plazo de 6 meses dedicando 3 horas al dia en la plataforma de aprendizaje de microsoft, todo con el fin de mejorar mi perfil profesional y conocimientos en el campo de manejo de estas tecnologias.  </p>                                                                                                                                                                                                                                                                                                                     | 

<div style="page-break-before: always"></div>

# Capítulo I: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de los integrantes del equipo

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

Lima continúa siendo la ciudad con mayores niveles de congestión vehicular en América Latina. De acuerdo con el Índice de Congestión Vehicular 2023 de la firma TomTom, la capital peruana se ubicó en el primer lugar regional y el quinto a nivel mundial. En promedio, recorrer una distancia de 10 km en Lima toma 28 minutos con 30 segundos, representando un incremento de 1 minuto con 20 segundos respecto al 2022 (Asociación automotriz del Perú, 2024). Este aumento coloca a Lima entre las tres ciudades del mundo con mayor deterioro en tiempo de desplazamiento. Asimismo, este contexto urbano representa un reto cotidiano para los estudiantes universitarios, quienes enfrentan:
- Largas demoras en el tráfico.
- Transporte público ineficiente, inseguro y poco cómodo.
- Altos costos de movilidad.
- Pérdida de tiempo que afecta su productividad.

Por lo tanto, nuestra aplicación de carpooling universitario está dirigida a dos segmentos principales de usuarios dentro de la comunidad estudiantil de la Universidad Peruana de Ciencias Aplicadas, ubicada en Lima, Perú. Ambos comparten características demográficas similares, pero cumplen roles distintos dentro del servicio: estudiante conductor y estudiante pasajero. A continuación se describen sus perfiles y necesidades:

### *Estudiante conductor*

#### Perfil:

- Género: Masculino y femenino
- Edad: 18 a 27 años
- Ubicación: Lima, Perú
- Nivel educativo: Universitario (pregrado)
- Estado civil: Soltero
- Universidad: Universidad Peruana de Ciencias Aplicadas (UPC)
- Medio de transporte: Vehículo propio o familiar

#### Necesidades:

- Se moviliza diariamente hacia la universidad en auto propio, generalmente solo.
- Busca reducir gastos de movilidad (combustible, mantenimiento).
- Tiene disposición a compartir su ruta con otros estudiantes.
- Le motiva la posibilidad de socializar.

### *Estudiante pasajero*

#### Perfil:

- Género: Masculino y femenino
- Edad: 18 a 25 años
- Ubicación: Lima, Perú
- Nivel educativo: Universitario (pregrado)
- Estado civil: Soltero
- Universidad: Universidad Peruana de Ciencias Aplicadas (UPC)
- Medio de transporte: Transporte público, taxi, o movilidad por app

#### Necesidades:

- Enfrenta demoras, incomodidad e inseguridad en el transporte público.
- Busca una alternativa más rápida, económica y segura para llegar a la universidad.
- Valora compartir viajes con otros estudiantes.
- Está dispuesto a contribuir con un monto a cambio del servicio.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

 * Estudiante Pasajero
 ![UserPersonPajaero](/assets/needfinding/user-person-pasajero.png)

 * Estudiante Conductor
 ![UserPersonConductor](/assets/needfinding/user-persona-conductor.png)

### 2.3.2. User Task Matrix

![taskMatrix](/assets/needfinding/task-matrix.png)

 * __Frecuencia e importancia:__ Las tareas con mayor frecuencia e impotancia se enfocan en el ahorro de tiempo y dinero tanto como pasajero y conductor al dirigirse a clases. 
* __Diferencias:__ La diferencia mas notoria es al momento de coordinar viajes a la universidad con un amigo o compañeros. Teniendo diferentes puntos de vistas respecto al ambito social al momento de viajar a la universidad.

* **Coincidencias:** La coincidencias que destacan entrelos diferentes usuarios. Tanto como el pasajero como el conductor buscan  ahorrar dinero, tiempo y controlar sus gastos al momento de viajar a la universidad. Estas necesidades en comun refelajan una busqueda de una solucion respecto a los gastos de viajara a la universidad.

### 2.3.3. User Journey Mapping
* **Pasajero**
![userJorningMap](/assets/needfinding/user-jorning-map-pasajero.png)

Se presenta el User Journey Map para el segmento objetivo de pasajeros mostrandonos el recorrido del usuario en el transporte publico.

* **Conductor**

![userJourneyMapConductor](/assets/needfinding/user-journey-map-conductor.png)

Se presenta el User Journey Map para el segmento objetivo de conductor mostrandonos el recorrido su viaje a la universidad.


### 2.3.4. Empathy Mapping

* **Pasajero**
![EmpathyMapPasajero](/assets/needfinding/Passenger-empathyMap.png)

Se presenta el Empathy Map del segmento objetivo de estudiantes que cumplen el rol de pasajeros que buscan ahorrar tiempo y dinero al movilizarse a la universidad, en el cual se describe las ideas, motivaciones,frustaciones y demandas de los usuarios.

* **Conductor**
![EmpathyMapConductor](/assets/needfinding/Driver-empathyMap.png)

Se presenta el Empathy Map del segmento objetivo de estudiantes que cumplen el rol de conductor que buscan ahorrar tiempo y dinero al movilizarse a la universidad tratando de compartir su veihculo, en el cual se describe las ideas, motivaciones,frustaciones y demandas de los usuarios.

### 2.3.5. As-is Scenario Mapping

* **Conductor**
![asisConductor](/assets/needfinding/as-is-passenger.png)

* **Pasajero**
![asisPassenger](/assets/needfinding/as-is-driver.png)
## 2.4. Ubiquitous Language

# Capítulo III: Requirements specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Impact Mapping

## 3.4. Product Backlog

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming

#### 4.1.1.1. Candidate Context Discovery

#### 4.1.1.2. Domain Message Flows Modeling

#### 4.1.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture Context Level Diagrams

#### 4.1.3.2. Software Architecture Container Level Diagrams

#### 4.1.3.3. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.1. Bounded Context:

#### 4.2.1.1. Domain Layer

#### 4.2.1.2. Interface Layer

#### 4.2.1.3. Application Layer

#### 4.2.1.4. Infrastructure Layer

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

##### 4.2.1.6.2. Bounded Context Database Design Diagram

# Capítulo V: Solution UI/UX Design

## 5.1. Product Design

### 5.1.1. Style Guidelines

#### 5.1.1.1. General Style Guidelines

### 5.1.2. Information Architecture

#### 5.1.2.1. Organization Systems

#### 5.1.2.2. Labelling Systems

#### 5.1.2.3. SEO Tags and Meta Tags

#### 5.1.2.4. Searching Systems

#### 5.1.2.5. Navigation Systems

### 5.1.3. Landing Page UI Design

#### 5.1.3.1. Landing Page Wireframe

#### 5.1.3.2. Landing Page Mock-up

### 5.1.4. Mobile Applications UX/UI Design

#### 5.1.4.1. Mobile Applications Wireframes

#### 5.1.4.2. Mobile Applications Wireflow Diagrams

#### 5.1.4.3. Mobile Applications Mock-ups

#### 5.1.4.4. Mobile Applications User Flow Diagrams

#### 5.1.4.5. Mobile Applications Prototyping

<div style="page-break-before: always"></div>
