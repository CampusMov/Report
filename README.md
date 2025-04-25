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

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language

# Capítulo III: Requirements specification

En esta sección se traduce los hallazgos de las investigaciones y el análisis de As-Is Scenario en los requisitos concretos del producto. 
Aquí se define qué necesita hacer el sistema, para quién y bajo qué condiciones, organizando la especificación en cuatro sub-secciones: 
To-Be Scenario Mapping, User Stories, Impact Mapping y Product Backlog.

## 3.1. To-Be Scenario Mapping

En esta sección se proyecta la experiencia futura de los usuarios mediante los To-Be Scenario Mapping. 
Para ello se realizó el proceso de preparación, lluvia de ideas individual, revisión y consolidación en equipo, así como el nombrado de fases. 

A continuación, se muestran las capturas para cada User Persona con las filas Phases, Doing, Thinking y Feeling.

<div style="text-align: center">
    <img src="assets/requirements/to-be-passenger.png" alt="ToBePassenger" style="width: 90%;"/>
    <img src="assets/requirements/to-be-driver.png" alt="ToBeDriver" style="width: 90%;"/>
</div>

## 3.2. User Stories

En esta sección se traducen los escenarios To-Be en Epics y User Stories. 
Cada historia define un rol, un objetivo y un beneficio, y se acompaña de criterios de aceptación en formato Gherkin. 
Se presenta una única tabla que agrupa todas las historias (producto digital, landing page y Technical Stories) con su relación a los Epics correspondientes.

| Epic / Story ID | Título                                                      | Descripción                                                                                                                                         | Criterios de aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Relacionado con (Epic ID) |
|:----------------|:------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------|
| EP-01           | Gestión de viajes compartidos                               | Como Driver o Passenger quiero gestionar todo el flujo de un Carpool para optimizar el emparejamiento, seguimiento y finalización de los trayectos. |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                           |
| EP-02           | Tarifación y comisiones                                     | Como Driver o Passenger quiero calcular y registrar Fares y Commissions para asegurar la trazabilidad de los pagos y el equilibrio económico.       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                           |
| EP-03           | Gestión de perfiles de usuario                              | Como Passenger o Driver quiero crear, ver y editar mi Profile para mantener mis datos personales y académicos precisos y confiables.                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                           |
| EP-04           | Identidad y acceso                                          | Como estudiante quiero registrarme, autenticarme e iniciar sesión, y gestionar Roles para acceder de forma segura a la plataforma.                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                           |
| EP-05           | Reputación e incentivos                                     | Como estudiante quiero que el sistema calcule mi ReputationScore y gestione Incentives e Infractions para fomentar un buen comportamiento.          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                           |
| EP-06           | Comunicación en viaje                                       | Como Driver o Passenger quiero un Chat en tiempo real dentro del Carpool para coordinar detalles sin compartir información personal.                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                           |
| EP-07           | Métricas de usuario                                         | Como Driver o Passenger quiero consultar mis Analytics para evaluar mi desempeño, ahorro de tiempo y beneficios económicos.                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                           |
| EP-08           | Notificaciones                                              | Como estudiante quiero recibir Notifications basadas en eventos de dominio para estar informado de cambios críticos y poder actuar a tiempo.        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                           |
| EP-09           | Landing Page                                                | Como visitante quiero explorar el sitio web estático para conocer Beneficios, Sobre la App, Videos y descargar la aplicación desde mi dispositivo.  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                           |
| US-01           | Inicio de sesión                                            | Como Passenger quiero iniciar sesión en UniRide para acceder de forma segura a las funcionalidades de Carpool.                                      | Escenario de aceptación 1: Given usuario en la vista de login When ingresa credenciales válidas Then se autentica y va al dashboard<br>Escenario de aceptación 2: Given usuario en la vista de login When ingresa credenciales inválidas Then muestra “Credenciales incorrectas” y no avanza<br>Escenario de aceptación 3: Given usuario ya autenticado When cierra y reabre la app Then mantiene la sesión iniciada                                                                  | EP-04                     |
| US-02           | Creación de cuenta con correo institucional                 | Como Usuario quiero crear una cuenta con mi correo “.edu” para asegurar que solo miembros universitarios accedan.                                   | Escenario de aceptación 1: Given registro con correo “.edu” When verifica Then envía invitación por email<br>Escenario de aceptación 2: Given registro con correo no “.edu” When verifica Then muestra “Debe usar correo institucional”<br>Escenario de aceptación 3: Given usuario recibió invitación When hace clic en enlace Then va a la página de crear contraseña                                                                                                               | EP-04                     |
| US-03           | Completar perfil de usuario                                 | Como Passenger quiero completar mi Profile con foto, PersonInfo y AcademicInformation para generar confianza.                                       | Escenario de aceptación 1: Given correo validado When rellena todos los campos obligatorios Then Profile se guarda correctamente<br>Escenario de aceptación 2: Given foto inválida When intenta subir Then muestra error y no deja guardar<br>Escenario de aceptación 3: Given faltan campos obligatorios When guarda Then alerta “Faltan datos” y no guarda                                                                                                                          | EP-03                     |
| US-04           | Visualizar y editar mi perfil                               | Como Passenger quiero ver y actualizar mi Profile para mantener mi información precisa y actualizada.                                               | Escenario de aceptación 1: Given usuario autenticado When accede a perfil Then muestra datos actuales<br>Escenario de aceptación 2: Given cambios válidos When guarda Then actualiza Profile y confirma<br>Escenario de aceptación 3: Given datos inválidos When guarda Then muestra “Campos inválidos” y no guarda                                                                                                                                                                   | EP-03                     |
| US-05           | Guardar y actualizar horarios frecuentes                    | Como Passenger quiero almacenar ClassSchedules recurrentes para no ingresarlos manualmente cada vez.                                                | Escenario de aceptación 1: Given ningún choque When guarda horario Then confirma “Horario creado con éxito”<br>Escenario de aceptación 2: Given horario existente When edita Then confirma “Horario actualizado con éxito”<br>Escenario de aceptación 3: Given existe conflicto When guarda Then muestra “Conflicto de horarios” y no guarda                                                                                                                                          | EP-03                     |
| US-06           | Registro de vehículos                                       | Como Driver quiero registrar mi Vehicle (VIN, matrícula, specs) para que Passenger identifique el auto.                                             | Escenario de aceptación 1: Given datos completos When registra Then Vehicle se asocia al Profile y confirma “Vehículo registrado”<br>Escenario de aceptación 2: Given campos faltantes When registra Then alerta “Faltan campos” y no guarda                                                                                                                                                                                                                                          | EP-03                     |
| US-07           | Guardar y gestionar paraderos favoritos                     | Como Passenger quiero guardar mis FavoriteStops para seleccionarlos fácilmente al planificar un Carpool.                                            | Escenario de aceptación 1: Given lugar seleccionado When guarda Then crea FavoriteStop y confirma<br>Escenario de aceptación 2: Given FavoriteStop existente When intenta guardar de nuevo Then muestra “Ya existe este favorito”<br>Escenario de aceptación 3: Given FavoriteStop guardado When elimina Then confirma “Favorito eliminado”                                                                                                                                           | EP-03                     |
| US-08           | Creación de un viaje de Carpool                             | Como Driver quiero crear un Carpool con origen, destino, hora y asientos para que Passenger pueda unirse si hay espacio.                            | Escenario de aceptación 1: Given datos completos When activa Then confirma “Carpool activado con éxito”<br>Escenario de aceptación 2: Given availableseats=0 When activa Then muestra “No hay asientos disponibles”<br>Escenario de aceptación 3: Given datos incompletos When activa Then alerta “Completa los detalles”                                                                                                                                                             | EP-01                     |
| US-09           | Visualización de información del viaje antes de unirse      | Como Passenger quiero ver Driver, hora, ruta, tarifa, asientos y rating antes de unirme para decidir con información.                               | Escenario de aceptación 1: Given Passenger autenticado When visualiza Carpool Then muestra todos los datos básicos solicitados                                                                                                                                                                                                                                                                                                                                                        | EP-01                     |
| US-10           | Configuración de distancia máxima para solicitudes          | Como Driver quiero fijar un radio máximo para solicitudes de Passenger y evitar solicitudes lejanas.                                                | Escenario de aceptación 1: Given Driver en ajustes When establece radio Then filtra solicitudes dentro del radio<br>Escenario de aceptación 2: Given Passenger fuera del radio When solicita Then rechaza la solicitud automáticamente                                                                                                                                                                                                                                                | EP-01                     |
| US-11           | Rastreo en tiempo real del viaje                            | Como Passenger quiero ver en un mapa la ubicación actual del Carpool en curso para confirmar el itinerario.                                         | Escenario de aceptación 1: Given Carpool en curso When abre seguimiento Then muestra posición en tiempo real<br>Escenario de aceptación 2: Given fallo de ubicación When abre seguimiento Then muestra “No se puede rastrear ubicación”                                                                                                                                                                                                                                               | EP-01                     |
| US-12           | Cancelar Carpool antes de iniciar                           | Como Driver quiero cancelar un Carpool antes de iniciar para liberar Passenger y evitar esperas innecesarias.                                       | Escenario de aceptación 1: Given Carpool programado When cancela Then estado=“Cancelled” y notifica Passenger<br>Escenario de aceptación 2: Given Carpool en curso When intenta cancelar Then alerta “No se puede cancelar un viaje en curso”                                                                                                                                                                                                                                         | EP-01                     |
| US-13           | Unirse a un Carpool en curso                                | Como Passenger quiero unirme a un Carpool activo si está cerca para aprovechar rutas en curso.                                                      | Escenario de aceptación 1: Given Carpool activo lejos When solicita unirse Then notifica al Driver<br>Escenario de aceptación 2: Given Driver acepta When confirma Then añade Passenger y actualiza asientos<br>Escenario de aceptación 3: Given asientos=0 When solicita Then muestra “No hay asientos”                                                                                                                                                                              | EP-01                     |
| US-14           | Emparejamiento automático                                   | Como Passenger quiero que el sistema empareje Carpools según ruta, horario y proximidad para optimizar mi espera.                                   | Escenario de aceptación 1: Given Passenger busca When ejecuta emparejamiento Then muestra opciones compatibles<br>Escenario de aceptación 2: Given sin coincidencias When busca Then muestra “No hay resultados disponibles”                                                                                                                                                                                                                                                          | EP-01                     |
| US-15           | Iniciar recorrido y notificar a los pasajeros               | Como Driver quiero iniciar el Carpool desde mi ubicación para notificar a los Passenger que el viaje ha comenzado.                                  | Escenario de aceptación 1: Given Driver en punto de inicio When inicia Then estado=“InProgress” y envía notificación<br>Escenario de aceptación 2: Given Driver no en punto When inicia Then alerta “No puedes iniciar hasta llegar al punto de inicio”                                                                                                                                                                                                                               | EP-01                     |
| US-16           | Visualización y selección en lista de espera                | Como Driver quiero ver la lista de espera ordenada por solicitud para aceptar o rechazar Passenger según cupo.                                      | Escenario de aceptación 1: Given asientos disponibles When accede a lista Then muestra pasajeros ordenados por fecha<br>Escenario de aceptación 2: Given Passenger seleccionado When acepta Then actualiza lista y notifica al Passenger                                                                                                                                                                                                                                              | EP-01                     |
| US-17           | Confirmar pasajeros para el viaje                           | Como Driver quiero aceptar o rechazar PassengerRequests según cupo para gestionar la lista de espera.                                               | Escenario de aceptación 1: Given Passenger en lista When acepta Then actualiza lista, notifica y reordena<br>Escenario de aceptación 2: Given Passenger en lista When rechaza Then notifica rechazo y actualiza lista                                                                                                                                                                                                                                                                 | EP-01                     |
| US-18           | Actualización de ruta al aceptar nuevos Passenger           | Como Driver quiero que la ruta se reproyecte automáticamente al confirmar nuevos puntos de recogida.                                                | Escenario de aceptación 1: Given Passenger nuevo aceptado When confirma Then recalcula ruta e incluye nuevo WayPoint<br>Escenario de aceptación 2: Given Passenger cancelado When procesa Then elimina WayPoint y vuelve a optimizar ruta                                                                                                                                                                                                                                             | EP-01                     |
| US-19           | Confirmar pago de tarifa                                    | Como Driver quiero confirmar el pago de cada Fare al finalizar el Carpool para registrar la transacción.                                            | Escenario de aceptación 1: Given Carpool finalizado y Passenger marcó pago When confirma Then cambia Fare a “Final” y registra movimiento                                                                                                                                                                                                                                                                                                                                             | EP-02                     |
| US-20           | Generar comisión automática                                 | Como sistema quiero calcular y registrar la Commission cuando Driver confirma un pago para llevar control de ingresos.                              | Escenario de aceptación 1: Given Driver confirma Fare When procesa Then crea Commission y suma al balance<br>Escenario de aceptación 2: Given confirmación duplicada When procesa Then no genera otra Commission                                                                                                                                                                                                                                                                      | EP-02                     |
| US-21           | Consulta de estado de cuenta de comisiones                  | Como Driver quiero ver un resumen actualizado de mis Commissions y dueDate para planificar mis pagos.                                               | Escenario de aceptación 1: Given Commission pendientes When abre “Estado de cuenta” Then muestra total adeudado, movimientos y dueDate<br>Escenario de aceptación 2: Given sin Commission When abre Then indica “No existen comisiones pendientes”                                                                                                                                                                                                                                    | EP-02                     |
| US-22           | Cálculo automático de tarifa sugerida                       | Como Passenger quiero que la App proponga un Fare estimado según distancia y ruta para decidir antes de unirme.                                     | Escenario de aceptación 1: Given Passenger elige origen y destino When solicita tarifa Then muestra FareAmount con base, descuento y total                                                                                                                                                                                                                                                                                                                                            | EP-02                     |
| US-23           | Registrar calificación y comentario                         | Como Passenger quiero calificar con estrellas y comentario al finalizar el Carpool para dar feedback al Driver.                                     | Escenario de aceptación 1: Given Carpool finalizado When ingresa rating y comentario Then guarda valoración<br>Escenario de aceptación 2: Given ya valoró When intenta volver a valorar Then rechaza y notifica “Ya calificado”                                                                                                                                                                                                                                                       | EP-01                     |
| US-24           | Penalizar cancelación tardía                                | Como Passenger quiero recibir advertencias o sanciones por cancelaciones fuera de tiempo para respetar a otros Users.                               | Escenario de aceptación 1: Given primera cancelación tardía When confirma Then genera 1 strike y envía advertencia<br>Escenario de aceptación 2: Given strike activo When repite Then suspende temporalmente<br>Escenario de aceptación 3: Given periodo sin strikes When vence Then resetea strikes a 0<br>Escenario de aceptación 4: Given máximo strikes When excede Then bloquea cuenta permanentemente                                                                           | EP-01                     |
| US-25           | Archivar chat al terminar el viaje                          | Como Passenger quiero que el Chat se archive al cerrar el Carpool para mantener la conversación limpia pero disponible.                             | Escenario de aceptación 1: Given Carpool finalizado When detecta fin Then Chat.status=“archived”<br>Escenario de aceptación 2: Given Chat archivado When intenta enviar mensaje Then bloquea envío y notifica “Chat archivado”                                                                                                                                                                                                                                                        | EP-06                     |
| US-26           | Recibir notificaciones críticas                             | Como User quiero recibir Notifications basadas en eventos de dominio para actuar oportunamente ante cambios del Carpool.                            | Escenario de aceptación 1: Given evento de dominio When ocurre Then crea Notification y envía push/visual                                                                                                                                                                                                                                                                                                                                                                             | EP-08                     |
| US-27           | Recordatorio de salida de viaje                             | Como Passenger quiero recibir una notificación 15 min antes de la salida para prepararme y evitar retrasos.                                         | Escenario de aceptación 1: Given faltan 15 min para salida When detecta Then envía “Tu viaje sale en 15 min, prepárate”                                                                                                                                                                                                                                                                                                                                                               | EP-08                     |
| US-28           | Notificación de confirmación de viaje                       | Como Passenger quiero recibir una push cuando se acepte mi solicitud para saber que mi plaza está asegurada.                                        | Escenario de aceptación 1: Given solicitud enviada When Driver acepta Then envía push “Tu viaje ha sido aceptado”                                                                                                                                                                                                                                                                                                                                                                     | EP-08                     |
| US-29           | Recordatorio de pago de comisión                            | Como Driver quiero recibir una push el día límite de pago de mi Commission para evitar recargos.                                                    | Escenario de aceptación 1: Given Commission pendiente y dueDate When coincide fecha Then envía “Recuerda pagar tu comisión hoy”                                                                                                                                                                                                                                                                                                                                                       | EP-02                     |
| US-30           | Finalizar el viaje y certificar los pagos                   | Como Driver quiero finalizar el Carpool solo cuando todos los pagos estén confirmados para cerrar el viaje.                                         | Escenario de aceptación 1: Given todos pagaron y Carpool en destino When finaliza Then estado=“finalizado” y notifica a Passenger<br>Escenario de aceptación 2: Given pagos incompletos When intenta finalizar Then impide acción y muestra error                                                                                                                                                                                                                                     | EP-02                     |
| US-31           | Emparejamiento basado en ruta y horario                     | Como Passenger quiero que el sistema empareje Carpools según ruta, destino y horarios compatibles para optimizar mi viaje.                          | Escenario de aceptación 1: Given parámetros definidos When busca emparejamiento Then muestra opciones adecuadas<br>Escenario de aceptación 2: Given sin coincidencias When busca Then muestra “No hay resultados disponibles”                                                                                                                                                                                                                                                         | EP-01                     |
| US-32           | Habilitar chat al confirmarse el viaje                      | Como Passenger quiero un Chat 1-a-1 en cuanto la solicitud es aceptada para coordinar detalles sin compartir datos.                                 | Escenario de aceptación 1: Given solicitud aceptada When pulsa “Chat” Then abre canal WebSocket y muestra conversación                                                                                                                                                                                                                                                                                                                                                                | EP-06                     |
| US-33           | Enviar y recibir mensajes de texto                          | Como Passenger quiero poder enviar y recibir mensajes de texto en el Chat para coordinar puntos de recogida.                                        | Escenario de aceptación 1: Given WebSocket activo When envía mensaje ≤250 caracteres Then persiste y confirma “✓ enviado”<br>Escenario de aceptación 2: Given mensaje entrante When llega Then muestra notificación y actualiza ícono “nuevo mensaje”<br>Escenario de aceptación 3: Given mensaje >250 When intenta enviar Then bloquea envío y muestra “Límite 250 caracteres”                                                                                                       | EP-06                     |
| US-34           | Rastreo en tiempo real                                      | Como Passenger quiero ver la ubicación actual del Carpool en un mapa para asegurar el itinerario.                                                   | Escenario de aceptación 1: Given Carpool en curso When accede a seguimiento Then muestra posición en tiempo real sobre mapa<br>Escenario de aceptación 2: Given error de ubicación When accede Then notifica “No se puede rastrear ubicación”                                                                                                                                                                                                                                         | EP-01                     |
| US-35           | Penalizar rechazo repetido de solicitudes                   | Como Driver quiero que el sistema cuente rechazos consecutivos de PassengerRequests y aplique sanciones progresivas.                                | Escenario de aceptación 1: Given 2 rechazos consecutivos When ocurre un tercer rechazo Then envía advertencia<br>Escenario de aceptación 2: Given 4 rechazos consecutivos When ocurre un quinto Then suspende cuenta temporalmente<br>Escenario de aceptación 3: Given no rechazos en periodo definido When vence periodo Then resetea contador a 0                                                                                                                                   | EP-05                     |
| US-36           | Gestión de capacidad máxima del Carpool                     | Como Driver quiero que el sistema notifique cuando la capacidad máxima de un Carpool se cubra y evite nuevas solicitudes.                           | Escenario de aceptación 1: Given último asiento confirmado When alcanza capacidad Then estado=“Full” y deja de mostrarse en listados<br>Escenario de aceptación 2: Given Carpool lleno When un Passenger intenta unirse Then rechaza y notifica “Carpool lleno”<br>Escenario de aceptación 3: Given asiento liberado When se libera Then vuelve a mostrarse y permite solicitudes                                                                                                     | EP-01                     |
| US-37           | Explorar sección “Beneficios”                               | Como Visitor quiero explorar la sección “Beneficios” para conocer las ventajas de usar UniRide antes de descargar la App.                           | Escenario de aceptación 1: Given Visitor en desktop When hace click en “Beneficios” en la navbar Then la página hace scroll suavemente a la sección “Beneficios” y muestra títulos, iconos y descripciones de cada ventaja.<br>Escenario de aceptación 2: Given Visitor en móvil When abre el menú hamburguesa y toca “Beneficios” Then el menú se colapsa correctamente y se desplaza a la misma sección sin errores.                                                                | EP-09                     |
| US-38           | Navegación responsiva                                       | Como Visitor quiero navegar cómodamente en cualquier dispositivo para acceder a todas las secciones de la landing page.                             | Escenario de aceptación 1: Given Visitor en desktop When pasa el cursor sobre los enlaces de la navbar Then el enlace activo se resalta y al hacer click enlaza correctamente.<br>Escenario de aceptación 2: Given Visitor en móvil When toca el icono del menú hamburguesa Then el menú se despliega y permite seleccionar secciones sin superposiciones ni scroll horizontal.                                                                                                       | EP-09                     |
| US-39           | Ver sección “Sobre la App” y “Videos”                       | Como Visitor quiero ver la sección “Sobre la App” y reproducir videos acerca del equipo y la aplicación para entender el producto.                  | Escenario de aceptación 1: Given Visitor desplaza la página hasta “Sobre la App” When llega a la sección Then se muestra el texto descriptivo con estilo legible.<br>Escenario de aceptación 2: Given Visitor continúa hasta “Videos” When hace click en cualquier miniatura Then el video se reproduce correctamente en un modal o reproductor embebido.                                                                                                                             | EP-09                     |
| US-40           | Botones de call-to-action para descarga                     | Como Visitor quiero disponer de botones visibles de descarga (App Store y Play Store) para instalar la App con un solo click.                       | Escenario de aceptación 1: Given Visitor accede a la sección final When la página carga Then se muestran dos botones claros con iconos de App Store y Play Store.<br>Escenario de aceptación 2: Given Visitor hace click en el botón correspondiente a su SO When se procesa la acción Then el navegador redirige a la tienda de apps correcta (App Store o Play Store).                                                                                                              | EP-09                     |
| US-41           | Ver sección “Testimonios”                                   | Como Visitor quiero leer testimonios de usuarios satisfechos para generar confianza en el servicio.                                                 | Escenario de aceptación 1: Given Visitor en landing page When hace scroll a “Testimonios” Then aparece un carrusel con fotos y opiniones<br>Escenario de aceptación 2: Given Visitor en móvil When toca flecha del carrusel Then avanza al siguiente testimonio                                                                                                                                                                                                                       | EP-09                     |
| US-42           | Ver sección “Preguntas Frecuentes” (FAQ)                    | Como Visitor quiero consultar la sección de FAQ para resolver dudas comunes sin tener que buscar soporte.                                           | Escenario de aceptación 1: Given Visitor en desktop When expande una pregunta Then se despliega la respuesta sin afectar otras<br>Escenario de aceptación 2: Given Visitor en móvil When toca el título de una pregunta Then se despliega con animación suave                                                                                                                                                                                                                         | EP-09                     |
| US-43           | Enviar mensaje vía formulario de contacto                   | Como Visitor quiero usar el formulario de contacto para enviar preguntas específicas y recibir respuesta por email.                                 | Escenario de aceptación 1: Given Visitor completa nombre, correo y mensaje When pulsa “Enviar” Then muestra “Gracias, responderemos pronto”<br>Escenario de aceptación 2: Given Visitor deja campos vacíos When pulsa “Enviar” Then resalta los campos obligatorios y muestra error “Por favor completa todos los campos”                                                                                                                                                             | EP-09                     |
| US-44           | Ver sección “Equipo”                                        | Como Visitor quiero conocer al equipo detrás de UniRide para confiar en la profesionalidad del proyecto.                                            | Escenario de aceptación 1: Given Visitor en desktop When llega a “Equipo” Then ve fotos, nombres y roles de cada miembro<br>Escenario de aceptación 2: Given Visitor en móvil When hace scroll por la sección Entonces cada tarjeta de miembro se ajusta al ancho de la pantalla                                                                                                                                                                                                      | EP-09                     |
| TS-01           | Exponer endpoint para crear Carpools                        | Como Desarrollador quiero exponer `POST /api/carpools` para que los Conductores creen Carpools vía API.                                             | Escenario de aceptación 1: Given Driver autenticado When envía POST `/api/carpools` con origen, destino, fecha/hora y asientos > 0 Then responde 201 Created y retorna `carpoolId` y detalles<br>Escenario de aceptación 2: Given asientos = 0 When envía la petición Then responde 400 Bad Request y mensaje “No hay asientos disponibles”<br>Escenario de aceptación 3: Given datos incompletos When envía la petición Then responde 400 Bad Request y lista de campos obligatorios | EP-01                     |
| TS-02           | Exponer endpoint para leer Carpools                         | Como Desarrollador quiero exponer `GET /api/carpools/{id}` para que los Passengers obtengan los detalles de un Carpool.                             | Escenario de aceptación 1: Given `carpoolId` válido When solicita GET `/api/carpools/{id}` Then responde 200 OK y payload con Driver, ruta, horario, tarifa y asientos disponibles<br>Escenario de aceptación 2: Given `carpoolId` inexistente When solicita GET Then responde 404 Not Found y mensaje “Carpool no encontrado”                                                                                                                                                        | EP-01                     |
| TS-03           | Exponer endpoint para cancelar Carpools                     | Como Desarrollador quiero exponer `POST /api/carpools/{id}/cancel` para que los Conductores cancelen un Carpool antes de iniciarlo.                 | Escenario de aceptación 1: Given Carpool programado When invoca POST `/cancel` Then responde 200 OK y cambia estado a Cancelled<br>Escenario de aceptación 2: Given Carpool en curso When invoca `/cancel` Then responde 400 Bad Request y mensaje “No se puede cancelar un Carpool en curso”                                                                                                                                                                                         | EP-01                     |
| TS-04           | Exponer endpoint para unirse a Carpools                     | Como Desarrollador quiero exponer `POST /api/carpools/{id}/join` para que los Passengers soliciten unirse a un Carpool.                             | Escenario de aceptación 1: Given Carpool disponible y asientos > 0 When POST `/join` Then responde 202 Accepted y notifica al Driver<br>Escenario de aceptación 2: Given asientos = 0 When POST `/join` Then responde 409 Conflict y mensaje “No hay asientos disponibles”                                                                                                                                                                                                            | EP-01                     |
| TS-05           | Exponer endpoint para iniciar Carpools                      | Como Desarrollador quiero exponer `POST /api/carpools/{id}/start` para que los Conductores inicien formalmente el Carpool.                          | Escenario de aceptación 1: Given Driver en ubicación de inicio When POST `/start` Then responde 200 OK, cambia estado a InProgress y envía Notification<br>Escenario de aceptación 2: Given Driver no en ubicación When POST `/start` Then responde 400 Bad Request y mensaje “Debe estar en el punto de inicio”                                                                                                                                                                      | EP-01                     |
| TS-06           | Exponer endpoint para gestionar PassengerRequests           | Como Desarrollador quiero exponer `POST /api/carpools/{id}/accept-passenger` y `/reject-passenger` para que los Conductores manejen solicitudes.    | Escenario de aceptación 1: Given solicitud pendiente When POST `/accept-passenger` Then responde 200 OK, añade Passenger y notifica<br>Escenario de aceptación 2: Given solicitud pendiente When POST `/reject-passenger` Then responde 200 OK y notifica rechazo                                                                                                                                                                                                                     | EP-01                     |
| TS-07           | Exponer endpoint para cancelar la solicitud de un Passenger | Como Desarrollador quiero exponer `DELETE /api/carpools/{id}/join` para que los Passengers cancelen su solicitud antes del inicio.                  | Escenario de aceptación 1: Given solicitud pendiente When DELETE `/join` Then responde 200 OK y elimina PassengerRequest<br>Escenario de aceptación 2: Given Carpool en curso When DELETE `/join` Then responde 400 Bad Request y mensaje “No se puede cancelar después de iniciado”                                                                                                                                                                                                  | EP-01                     |
| TS-08           | Permitir unirse a Carpools activos                          | Como Desarrollador quiero que `POST /api/carpools/{id}/join` admita Peticiones incluso si el Carpool está en curso.                                 | Escenario de aceptación 1: Given Carpool en curso y dentro del radio When POST `/join` Then responde 202 Accepted y notifica al Driver<br>Escenario de aceptación 2: Given fuera del radio When intenta unirse Then responde 400 Bad Request y mensaje “Fuera de zona permitida”                                                                                                                                                                                                      | EP-01                     |
| TS-09           | Exponer endpoint para finalizar Carpools                    | Como Desarrollador quiero exponer `POST /api/carpools/{id}/finalize` para que los Conductores cierren el Carpool una vez completado.                | Escenario de aceptación 1: Given Carpool en destino y todos los Fares confirmados When POST `/finalize` Then responde 200 OK y estado a Finalized<br>Escenario de aceptación 2: Given alguno sin pago When POST `/finalize` Then responde 409 Conflict y mensaje “No todos los pagos están confirmados”                                                                                                                                                                               | EP-02                     |
| TS-10           | Exponer endpoint para confirmar pagos                       | Como Desarrollador quiero exponer `POST /api/payments/confirm` para que los Conductores registren el pago de cada PassengerRequest.                 | Escenario de aceptación 1: Given Carpool finalizado y PassengerRequest señalada When POST `/payments/confirm` Then responde 200 OK, cambia estado de Fare a Final y genera Commission<br>Escenario de aceptación 2: Given Carpool no finalizado When POST `/payments/confirm` Then responde 400 Bad Request y mensaje “No se puede confirmar antes de finalizar”                                                                                                                      | EP-02                     |
| TS-11           | Implementar WebSocket para Chat                             | Como Desarrollador quiero habilitar WebSocket en `/ws/carpools/{id}/chat` para que Conductores y Passengers intercambien mensajes en tiempo real.   | Escenario de aceptación 1: Given Carpool aceptado When cliente se conecta Then WebSocket handshake se establece<br>Escenario de aceptación 2: Given conexión activa When envía mensaje ≤ 250 caracteres Then persiste en DB y broadcast<br>Escenario de aceptación 3: Given mensaje > 250 caracteres When intenta enviar Then cierra con error “Límite 250 caracteres”                                                                                                                | EP-06                     |
| TS-12           | Procesamiento de mensajes WebSocket                         | Como Desarrollador quiero implementar la lógica para enviar, recibir y notificar mensajes a través de WebSocket.                                    | Escenario de aceptación 1: Given mensaje válido When llega al servidor Then se entrega al receptor y confirma<br>Escenario de aceptación 2: Given receptor desconectado When se envía mensaje Then lo almacena y envía push al reconectar<br>Escenario de aceptación 3: Given error de red When envía mensaje Then reintenta y notifica fallo                                                                                                                                         | EP-06                     |
| TS-13           | Exponer endpoint para actualizar Profile                    | Como Desarrollador quiero exponer `PUT /api/users/{id}/profile` para que los Users editen su Profile vía API.                                       | Escenario de aceptación 1: Given datos válidos When PUT `/profile` Then responde 200 OK y retorna Profile actualizado<br>Escenario de aceptación 2: Given email inválido When PUT Then responde 400 Bad Request y mensaje “Formato de email inválido”                                                                                                                                                                                                                                 | EP-03                     |
| TS-14           | Exponer endpoint para leer Profile                          | Como Desarrollador quiero exponer `GET /api/users/{id}/profile` para que los Users vean perfiles públicos.                                          | Escenario de aceptación 1: Given `userId` existe When GET `/profile` Then responde 200 OK y payload con foto, nombre y bio<br>Escenario de aceptación 2: Given `userId` no existe When GET Then responde 404 Not Found y mensaje “Usuario no encontrado”                                                                                                                                                                                                                              | EP-03                     |
| TS-15           | Exponer endpoint para gestionar Vehicles                    | Como Desarrollador quiero exponer `POST` y `GET /api/users/{id}/vehicles` para que los Conductores registren y consulten Vehicles.                  | Escenario de aceptación 1: Given datos completos When POST `/vehicles` Then responde 201 Created y retorna `vehicleId`<br>Escenario de aceptación 2: Given datos incompletos When POST Then responde 400 Bad Request y lista de campos faltantes<br>Escenario de aceptación 3: Given `userId` válido When GET `/vehicles` Then responde 200 OK y lista de Vehicles                                                                                                                    | EP-03                     |
| TS-16           | Exponer endpoint para gestionar FavoriteStops               | Como Desarrollador quiero exponer `POST` y `GET /api/users/{id}/favorites/stops` para que los Passengers gestionen sus paraderos favoritos.         | Escenario de aceptación 1: Given `stopId` válido When POST `/favorites/stops` Then responde 201 Created y retorna `favoriteId`<br>Escenario de aceptación 2: Given duplicado When POST Then responde 409 Conflict y mensaje “Ya existe este favorito”<br>Escenario de aceptación 3: Given `userId` válido When GET `/favorites/stops` Then responde 200 OK y lista de FavoriteStops                                                                                                   | EP-03                     |
| TS-17           | Exponer endpoints para ReferralCodes                        | Como Desarrollador quiero exponer `POST /api/referrals/generate` y `POST /api/referrals/{code}/redeem` para gestionar códigos de invitación.        | Escenario de aceptación 1: Given User autenticado When POST `/generate` Then responde 200 OK y retorna `referralCode` único<br>Escenario de aceptación 2: Given referido válido When POST `/redeem` Then responde 200 OK, asigna recompensa y notifica<br>Escenario de aceptación 3: Given autoreferencia When POST `/redeem` Then responde 400 Bad Request y mensaje “Código no válido”                                                                                              | EP-05                     |
| TS-18           | Exponer endpoint para estadísticas de rechazos              | Como Desarrollador quiero exponer `GET /api/drivers/{id}/rejection-stats` para que los Conductores consulten sus rechazos consecutivos.             | Escenario de aceptación 1: Given Driver con datos When GET `/rejection-stats` Then responde 200 OK con `rejectionCount` y fechas<br>Escenario de aceptación 2: Given sin rechazos When GET Then responde 200 OK con `rejectionCount=0`<br>Escenario de aceptación 3: Given suspensión activa When GET Then incluye `suspensionStatus` en el payload                                                                                                                                   | EP-05                     |
| TS-19           | Integración con GeoServiceAdapter                           | Como Desarrollador quiero integrar un servicio de geolocalización externo para calcular distancia y ETA de rutas.                                   | Escenario de aceptación 1: Given credenciales válidas When invoca GeoServiceAdapter con origen y destino Then devuelve `distanceKm` y `durationMinutes`<br>Escenario de aceptación 2: Given falla de red When invoca el servicio Then lanza excepción manejable y retorna mensaje de error                                                                                                                                                                                            | EP-01                     |
| TS-20           | Implementar EventBusAdapter                                 | Como Desarrollador quiero exponer un EventBusAdapter para publicar eventos de dominio y desacoplar NotificationService, Analytics y otros.          | Escenario de aceptación 1: Given evento `CarpoolStarted` When publica Then llega a NotificationEventConsumer<br>Escenario de aceptación 2: Given error de conexión When publica Then lanza excepción y registra en log                                                                                                                                                                                                                                                                | EP-08                     |
| TS-21           | Implementar SchedulerAdapter                                | Como Desarrollador quiero integrar un SchedulerAdapter para programar recordatorios automáticos (PaymentDue, TripReminder).                         | Escenario de aceptación 1: Given commissionDueDate configurada When scheduler dispara Then envía Notification “Recuerda pagar tu comisión”<br>Escenario de aceptación 2: Given 15 min antes de inicio When scheduler dispara Then envía Notification “Tu viaje sale en 15 min”                                                                                                                                                                                                        | EP-08                     |

## 3.3. Impact Mapping

En esta sección se alinean las funcionalidades con Business Goals SMART mediante el Impact Mapping. 
Se identifican los Business Goals, los Actores implicados, los Impacts esperados, los Deliverables propuestos y las User Stories asociadas.
Se incluyen capturas extraídas de UxPressia para elaborar el mapa.

<div style="text-align: center">
    <img src="./assets/requirements/ImpactMap1.png" alt="Impact Map" style="width: 80%; height: auto;">
</div>

## 3.4. Product Backlog

En esta sección se priorizan y estiman las User Stories para el Product Backlog. 
Se presenta una tabla con el orden de ejecución, el identificador, el título y los puntos de historia, así como una captura y el enlace público al backlog en la herramienta elegida. 
La priorización se fundamenta en el valor de negocio, garantizando la inclusión de las historias de la landing page desde el primer sprint.

| #   | User Story Id | Título                                                   | Story Points |
|-----|---------------|----------------------------------------------------------|--------------|
| 1   | US-43         | Explorar sección “Beneficios”                            | 2            |
| 2   | US-44         | Navegación responsiva                                    | 2            |
| 3   | US-45         | Ver sección “Sobre la App” y “Videos”                    | 2            |
| 4   | US-46         | Botones de call-to-action para descarga                  | 1            |
| 5   | US-49         | Ver sección “Testimonios”                                | 1            |
| 6   | US-50         | Ver sección “Preguntas Frecuentes” (FAQ)                 | 2            |
| 7   | US-51         | Enviar mensaje vía formulario de contacto                | 2            |
| 8   | US-53         | Ver sección “Equipo”                                     | 1            |
| 9   | US-08         | Creación de un viaje de Carpool                          | 5            |
| 10  | TS-01         | Exponer endpoint para crear Carpools                     | 2            |
| 11  | US-09         | Visualización de información del viaje antes de unirse   | 2            |
| 12  | TS-02         | Exponer endpoint para leer Carpools                      | 2            |
| 13  | US-10         | Configuración de distancia máxima para solicitudes       | 2            |
| 14  | US-11         | Rastreo en tiempo real del viaje                         | 5            |
| 15  | US-12         | Cancelar Carpool antes de iniciar                        | 2            |
| 16  | TS-03         | Exponer endpoint para cancelar Carpools                  | 2            |
| 17  | US-13         | Unirse a un Carpool en curso                             | 3            |
| 18  | TS-04         | Exponer endpoint para unirse a Carpools                  | 2            |
| 19  | TS-08         | Permitir unirse a Carpools activos                       | 3            |
| 20  | US-14         | Emparejamiento automático                                | 5            |
| 21  | TS-19         | Integración con GeoServiceAdapter                        | 3            |
| 22  | US-15         | Iniciar recorrido y notificar a los pasajeros            | 3            |
| 23  | TS-05         | Exponer endpoint para iniciar Carpools                   | 3            |
| 24  | US-16         | Visualización y selección en lista de espera             | 3            |
| 25  | US-17         | Confirmar pasajeros para el viaje                        | 3            |
| 26  | TS-06         | Exponer endpoint para gestionar PassengerRequests        | 2            |
| 27  | US-18         | Generar comisión automática                              | 3            |
| 28  | US-19         | Consulta de estado de cuenta de comisiones               | 2            |
| 29  | US-20         | Confirmar pago de tarifa                                 | 3            |
| 30  | TS-10         | Exponer endpoint para confirmar pagos                    | 3            |
| 31  | US-21         | Cálculo automático de tarifa sugerida                    | 2            |
| 32  | US-22         | Registrar calificación y comentario                      | 2            |
| 33  | US-23         | Penalizar cancelación tardía                             | 3            |
| 34  | US-24         | Archivar chat al terminar el viaje                       | 1            |
| 35  | US-25         | Recibir notificaciones críticas                          | 2            |
| 36  | TS-20         | Implementar EventBusAdapter                              | 3            |
| 37  | US-27         | Recordatorio de salida de viaje                          | 1            |
| 38  | TS-21         | Implementar SchedulerAdapter                             | 3            |
| 39  | US-28         | Notificación de confirmación de viaje                    | 1            |
| 40  | US-29         | Recordatorio de pago de comisión                         | 1            |
| 41  | US-30         | Finalizar el viaje y certificar los pagos                | 3            |
| 42  | TS-09         | Exponer endpoint para finalizar Carpools                 | 3            |
| 43  | US-31         | Emparejamiento basado en ruta y horario                  | 3            |
| 44  | US-32         | Habilitar chat al confirmarse el viaje                   | 2            |
| 45  | US-33         | Enviar y recibir mensajes de texto                       | 3            |
| 46  | TS-11         | Implementar WebSocket para Chat                          | 5            |
| 47  | TS-12         | Procesamiento de mensajes WebSocket                      | 5            |
| 48  | US-35         | Penalizar rechazo repetido de solicitudes                | 3            |
| 49  | TS-18         | Exponer endpoint para estadísticas de rechazos           | 2            |
| 50  | US-36         | Gestión de capacidad máxima del Carpool                  | 2            |
| 51  | TS-07         | Exponer endpoint para cancelar solicitudes               | 2            |
| 52  | TS-13         | Exponer endpoint para actualizar Profile                 | 2            |
| 53  | TS-14         | Exponer endpoint para leer Profile                       | 2            |
| 54  | TS-15         | Exponer endpoint para gestionar Vehicles                 | 2            |
| 55  | TS-16         | Exponer endpoint para gestionar FavoriteStops            | 2            |
| 56  | TS-17         | Exponer endpoints para ReferralCodes                     | 3            |

La herramienta utilizada para gestionar el Product Backlog es [Jira](https://www.atlassian.com/software/jira) y el enlace público es [UniRide Product Backlog](https://uni-ride.atlassian.net/jira/software/projects/HU/settings/details), donde se pueden ver las historias de usuario, su estado y los puntos de historia asignados.

<div style="text-align: center">
    <img src="./assets/requirements/backlog-jira.png" alt="Product Backlog" style="width: 80%; height: auto;">
</div>

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
