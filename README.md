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

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories
| Epic / Story ID | Título                                                                              | Descripción                                                                                                                                                                                                                                                              | Criterios de aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|-----------------|-------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| HU-10           | Reputation & Incentives                                                             |                                                                                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| HU-100          | Generar un chat directo con el conductor (TS)                                       | Como Desarrollador Quiero habilitar un canal de chat 1‑a‑1 entre chofer y estudiante cuando una solicitud de viaje es aceptada Para que puedan coordinar detalles sin compartir datos personales, usando WebSocket para comunicación en tiempo real                      | Escenario 1: Acceso al chat tras emparejamiento Given que el estudiante ha sido emparejado para un viaje exitosamente And se encuentra en la sección de detalles del viaje When presiona el botón “Chat” Then el sistema establece una conexión WebSocket entre el estudiante y el chofer And se muestra la conversación de chat 1‑a‑1 correspondiente a ese viaje And ambos pueden enviar y recibir mensajes en tiempo real sin compartir datos personales                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| HU-103          | Permitir el envio y recepción de mensajes (TS)                                      | Como desarrollador Quiero permitir el envío y recepción de mensajes de texto a través de WebSocket en el chat Para que los estudiantes puedan coordinar puntos de recogida, retrasos y detalles del viaje directamente, sin necesidad de compartir información personal. | Escenario 1: Envío y recepción exitosos Given que el chat WebSocket está activo y conectado When el estudiante envía un mensaje de texto con menos de 250 caracteres Then el servidor registra el mensaje correctamente en la base de datos o sistema de mensajería And emite una respuesta de confirmación al cliente para mostrar una notificación visual de éxito ("✓ enviado") Escenario 2: Notificación de nuevos mensajes Given que el estudiante está registrado en el viaje y tiene una sesión activa When el otro estudiante (chofer o pasajero) envía un mensaje mediante el WebSocket Then el sistema envía una notificación push (PUSH) al receptor del mensaje And actualiza visualmente el ícono del chat con la indicación de "nuevo mensaje" Escenario 3: Longitud de mensaje excedida Given que el chat WebSocket está activo When el estudiante intenta enviar un mensaje con más de 250 caracteres Then el sistema bloquea el envío del mensaje And retorna un mensaje de error como {{"Mensaje demasiado largo. Límite: 250 caracteres"}} And no se realiza ninguna operación de almacenamiento o envío                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| HU-104          | Aviso de llegada al recojo (TS)                                                     | Como Desarrollador Quiero implementar un sistema que notifique al pasajero cuando el conductor esté a menos de 3 minutos de su punto de recogida Para que el pasajero pueda prepararse con anticipación y evitar retrasos                                                | Escenario 1: Aviso a pocos minutos de llegar Given que el pasajero está registrado en un viaje activo And el sistema tiene acceso a la ubicación del conductor y del punto de recogida del pasajero When el sistema detecta que el tiempo estimado de llegada (ETA) del conductor al punto de recogida es menor a 3 minutos Then el sistema envía una notificación push al pasajero con el mensaje: “Tu conductor está a punto de llegar. Por favor, prepárate.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| HU-105          | Confirmación de pago(TS)                                                            | Como Desarrollador Quiero permitir que el conductor confirme el pago de cada pasajero al finalizar el viaje Para registrar la transacción y asegurar la trazabilidad del cobro                                                                                           | Escenario 1: Confirmación exitosa del pago por parte del conductor Given que el viaje ya ha llegado a su destino And el pasajero ha marcado que ya realizó el pago desde su aplicación When el conductor confirma el pago del pasajero mediante el endpoint: {{POST /payments/confirm}} con el cuerpo { "tripId": "viaje001", "passengerId": "pasajero123", "driverId": "conductor456" } Then el sistema:  Valida que el viaje ha finalizado  Verifica que el pasajero ha indicado el pago Escenario 2: Error si el viaje aún no ha finalizado Given que el conductor intenta confirmar el pago antes de llegar al destino When realiza una solicitud al endpoint {{/payments/confirm}} Then el sistema responde con el siguiente cuerpo { "message": "No se puede confirmar el pago antes de finalizar el viaje.", "status": "error" }                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| HU-11           | Inicio de sesión                                                                    | Como usuario quiero iniciar sesión en la aplicación UniRide para acceder a las funcionalidades que me permiten movilizarme y gestionar mis viajes de forma segura.                                                                                                       | Criterio 1: Inicio de sesión exitoso con credenciales válidas  Given que el usuario está en la pantalla de inicio de sesión.  When el usuario ingresa su correo electrónico y contraseña correctos  And presiona "Iniciar sesión".  Then el sistema valida las credenciales.  And el sistema redirige al usuario a la página principal de la aplicación.  And el sistema muestra un mensaje de bienvenida al usuario. Criterio 2: Inicio de sesión fallido por credenciales incorrectas  Given que el usuario está en la pantalla de inicio de sesión.  When el usuario ingresa su correo electrónico y contraseña incorrectos.  Then el sistema muestra un mensaje de error indicando que las credenciales son incorrectas.  And el sistema no permite al usuario acceder a la aplicación. Escenario 3: Sesión de usuario persistente  Given que el usuario ha iniciado sesión correctamente.  When el usuario cierra la aplicación y la vuelve a abrir.  Then el sistema mantiene al usuario conectado  And lo redirige directamente a la pantalla principal sin pedirle que ingrese nuevamente sus credenciales.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| HU-19           | Panel de métricas personales                                                        | Como estudiante, quiero ver un panel que resuma mis métricas clave (viajes realizados, cancelaciones, promedio de estrellas, kilómetros recorridos), para entender de un vistazo mi nivel de actividad y reputación en la plataforma.                                    | Criterio 1 – Panel mostrado con datos válidos Given el usuario ha iniciado sesión correctamente y existen registros de viajes asociados When accede a la sección “Mis métricas” Then el sistema muestra:  El número total de viajes realizados (como pasajero y/o conductor)  El número total de cancelaciones  El promedio de estrellas con una precisión de al menos un decimal  La suma total de kilómetros recorridos And cada métrica se visualiza con un formato claro, legible y actualizado Criterio 2 – Sin historial todavía Given el usuario ha iniciado sesión y no tiene registros de viajes asociados When accede a la sección “Mis métricas” Then el sistema muestra el mensaje “Aún no tienes métricas disponibles” And no se muestran valores numéricos ni gráficos Criterio 3 – Acceso desde el menú principal o perfil Given que el usuario está autenticado y navega por la aplicación When selecciona la opción “Mis métricas” desde el menú principal o su perfil Then el sistema lo redirige correctamente a la vista de métricas personales                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| HU-20           | Creación de cuenta con correo institucional                                         | Como nuevo usuario, quiero crear una cuenta usando mi correo institucional de la universidad para garantizar que las personas que se registren en la aplicación son parte de la comunidad universitaria y mejorar la seguridad en la plataforma.                         | Escenario 1: Verificación de correo institucional  Given el usuario está en la página de registro.  When el usuario ingresa su correo institucional válido.  And presiona "Verificar".  Then el sistema debe verificar que el correo sea válido y termine con ".edu". Escenario 2: Envío de invitación por correo electrónico  Given el correo del usuario ha sido verificado con éxito.  When el sistema envía la invitación al correo del usuario con el enlace de "Crear cuenta".  Then el sistema debe enviar un correo electrónico con un enlace y un botón "Crear cuenta" al correo del usuario. Escenario 3: Acceso a la página de creación de contraseña  Given el usuario ha recibido el correo con el enlace de "Crear cuenta".  When el usuario hace clic en el enlace de "Crear cuenta" en su correo electrónico.  Then el sistema debe redirigir al usuario a la página de creación de contraseña. Escenario 4: Creación de contraseña exitosa  Given el usuario está en la página de creación de contraseña.  When el usuario ingresa una contraseña válida y la confirma correctamente.  Then el sistema debe guardar la contraseña y permitir que el usuario continúe con el registro. Escenario 5: Correo institucional no válido  Given el usuario ingresa un correo no institucional o que no termina en ".edu".  When el sistema intenta verificar el correo institucional ingresado.  Then el sistema debe mostrar un mensaje de error indicando que el correo debe ser un correo institucional válido con dominio ".edu". Escenario 6: Enlace de invitación expirado o inválido  Given el usuario hace clic en el enlace de "Crear cuenta" después de que haya expirado o no sea válido.  When el sistema verifica el estado del enlace de "Crear cuenta".  Then el sistema debe redirigir al usuario a la página de inicio de sesión y mostrar un mensaje indicando que el enlace ha expirado o no es válido. Escenario 7: Fallo en la creación de contraseña  Given el usuario ha ingresado una contraseña y la ha confirmado.  When las contraseñas no coinciden o la contraseña no cumple con los requisitos de seguridad.  Then el sistema debe mostrar un mensaje de error indicando que las contraseñas no coinciden o que la contraseña no es segura y pedirle al usuario que intente de nuevo. |
| HU-22           | Habilitar chat al confirmarse el viaje                                              | Como estudiante, quiero un canal 1‑a‑1 en cuanto la solicitud de viaje es aceptada, para poder coordinar detalles sin compartir datos personales.                                                                                                                        | Escenario 1: Acceso al chat  Given que el estudiante ha sido emparejado para un viaje.  And se encuentra en la seccion del viaje.  When presiona “Chat“.  Then el sistema muestra la conversion del chat.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |


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
