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
| Riva Rodriguez, Elmer Augusto     | <p> **Objetivo 1**: Conseguir un puesto como Desarrollador Backend en una empresa de tecnología en un plazo máximo de 6 meses después de mi graduación. Para ello, mejoraré mi portafolio con al menos 3 proyectos avanzados utilizando Java y Spring Boot, mantendré un ritmo de 5 aplicaciones semanales a ofertas laborales y expandiré mi red de contactos asistiendo a eventos tecnológicos </p> <p> **Objetivo 2**: Iniciar una maestría en Inteligencia Artificial dentro de los 12 meses posteriores a mi graduación. Para ello, investigaré a cerca de al menos 3 universidades o programas en línea, completando las solicitudes necesarias, a la vez de dedicar al menos 3 horas semanales a la preparación de documentos. </p>                                                                                                                                                                                                                                                                                                                     |

<div style="page-break-before: always"></div>

# Capítulo I: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de los integrantes del equipo

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

Se describe en los siguientes apartados el proceso de Lean UX que se ha seguido para la solución propuesta.

#### 1.2.2.1. Lean UX Problem Statements

El estado actual de **la movilidad de estudiantes universitarios en Lima** se ha centrado principalmente en **el uso individual de autos, transporte público congestionado y servicios de taxi costosos.**

Lo que los productos/servicios existentes no logran abordar es **la falta de una solución específica para coordinar viajes compartidos dentro de comunidades universitarias, lo que genera altos costos personales, tiempos de traslado excesivos y contribuye al tráfico urbano.**

Nuestro producto/servicio abordará esta brecha mediante **una plataforma que permita a estudiantes universitarios coordinar viajes compartidos seguros y confiables según sus rutas, horarios y preferencias.**

Nuestro enfoque inicial serán **estudiantes de universidades privadas con horarios definidos y largas distancias de traslado, empezando por Lima Metropolitana.**

Sabremos que hemos tenido éxito cuando veamos **una reducción promedio del 30% en costos de traslado por estudiante, un 25% de incremento en la ocupación vehicular y un aumento mensual en la retención de usuarios activos del 50%.**

#### 1.2.2.2. Lean UX Assumptions

Se han definido las siguientes suposiciones para el desarrollo de la solución:

**Users**

Se describe los siguientes perfiles de usuarios mediante Proto-Personas:

* **Valeria** - **La Estudiante Madrugadora**
  * **Role**: Estudiante Universitaria Pasajera
  * **Datos Relevantes**:
    * Vive en Surquillo, estudia en Monterrico.
    * Sale a la U a las 6:00 am.
    * Gasta S/ 10 diarios en transporte público.
    * Gasta 1h50 en transporte público.
    * Usa Android, Google Maps, Youtube y Yape.
  * **Objetivos y necesidades**:
    * Llegar puntual a clases sin gastar demasiado.
    * Viajar más tranquila y segura en la mañana.
    * Evitar el estrés del transporte público.
    * Reducir su tiempo promedio de viaje (actualmente 1h50).
    * Ahorrar al menos S/50 mensuales.
  * **Obstáculos**:
    * No tiene rutas claras de quiénes van cerca.
    * No se atreve a coordinar con desconocidos.
    * El transporte público es impredecible en tiempos y seguridad.
    * No tiene claridad para compensar al conductor de forma segura y confiable, ni sabe cómo confirmar que el viaje se completó
    * Teme que el conductor cancele o no cumpla el viaje acordado

* **Diego** - **El Conductor Buena Onda**
  * **Role**: Estudiante Universitario Conductor
  * **Datos Relevantes**:
    * Vive en San Isidro, maneja su auto al campus universitario de la UPC en Monterrico.
    * Sale a la U a las 6:30 am.
    * Gasta S/ 20 diarios en combustible.
    * Gasta 30 minutos en el tráfico.
    * Usa iPhone, Waze, Spotify y Yape.
  * **Objetivos y necesidades**:
    * Optimizar sus gastos en gasolina.
    * Aprovechar los asientos vacíos de su carro.
    * Ahorrar al menos S/100 mensuales.
  * **Obstáculos**:
    * No tiene claro cómo coordinar con otros estudiantes.
    * No sabe si los pasajeros serán puntuales.
    * No confía en la seguridad de compartir su auto.
    * No tiene un método integrado para cobrar a los pasajeros ni visualizar de manera clara cuánto está ahorrando por viaje.

**Business Outcomes**

Usando el User Journey Type - Pirate Metrics, se han definido los siguientes objetivos de negocio:

* **Acquisition**:
  * Lograr que entre el 15% y 25% de los visitantes se registren en la plataforma.
  * Asegurar que al menos el 60% completen su perfil con zona, horario y rol.
* **Activation**: 
  * Conseguir que entre el 40% y 60% de los nuevos usuarios conductores realicen su primer viaje dentro del primer mes.
  * Lograr que entre el 50% y 70% de usuarios pasajeros se unan a un grupo de carpool.
* **Retention**: 
  * Mantener una retención semanal entre el 50% y 60% de los usuarios activos.
  * Alcanzar una retención mensual sostenida entre el 30% y 40%.
* **Revenue**: 
  * Lograr que entre el 40% y 50% de los viajes generen comisión efectiva.
  * Alcanzar un ingreso promedio mensual por conductor activo entre S/8 y S/12 en la etapa inicial.
* **Referral**: 
  * Incentivar que entre el 15% y 25% de los usuarios inviten a nuevos compañeros
  * Lograr que entre el 10% y 15% de esos referidos se conviertan en usuarios activos.

**User Outcomes & Benefits**

* **Estudiante Universitaria Pasajera**
  * Funcional: Reducir su tiempo de viaje y el costo mensual de transporte.
  * Emocional: Sentirse segura, acompañada y tranquila en sus traslados matutinos. 
  * Aspiracional: Sentirse en control de su rutina diaria y más enfocada en su desarrollo académico.

* **Estudiante Universitario Conductor**
  * Funcional: Disminuir su gasto mensual en combustible y evita desvíos innecesarios.
  * Emocional: Sentirse valorado, seguro y en control al compartir su auto con confianza. 
  * Aspiracional: Posicionarse como alguien práctico, solidario y que cuida su economía sin sacrificar comodidad.

**Solutions**

Acorde a los problemas y necesidades de los usuarios, se han definido las siguientes soluciones:

* **Estudiante Universitaria Pasajera**
  * Problema 1: No tiene rutas claras de quiénes van cerca
    * Algoritmo de coincidencia de rutas y horarios. 
    * Filtro por facultad/zona para mostrar solo estudiantes de trayectos similares. 
    * Mapa interactivo en tiempo real de conductores que estén pasando cerca si aun no se unió a un grupo preformado.
  * Problema 2: No se atreve a coordinar con desconocidos
    * Sistema de calificaciones y comentarios por viaje.
    * Validación con correo institucional y perfil completo con foto y facultad.
    * Chat interno con opción de ver perfiles antes de unirse al grupo.
  * Problema 3: El transporte público es impredecible en tiempos y seguridad
    * Seguimiento en tiempo real del viaje.
    * Botón de emergencia con ubicación compartida.
    * Notificaciones automáticas: “Tu conductor está en camino” o “Viaje confirmado”.
  * Problema 4: No tiene claridad para compensar al conductor ni confirmar viaje
    * Integración con Yape u otro método de pago para aportar el costo compartido.
    * Confirmación automática de viaje completado para que tanto conductor como pasajera validen la transacción.
    * Resumen de aportes realizados por semana o mes para controlar sus gastos.
    * Ofrecer un precio sugerido basado en la distancia y el combustible, con posibilidad de ajuste por parte del conductor, pero con un tope para no desincentivar a los pasajeros.
    * Panel de gastos para el pasajero que muestra resumen de aportes realizados por semana o mes para controlar sus gastos.
  * Problema 5: Teme que el conductor cancele o no cumpla el viaje acordado
    * Penalizaciones para los conductores que no cumplan con el viaje acordado o cancelen sin previo aviso.
    * Chat interno para coordinar cambios de último momento y reducir cancelaciones sorpresivas.

* **Estudiante Universitario Conductor**
  * Problema 1: No tiene claro cómo coordinar con otros estudiantes
    * Panel con sugerencias de pasajeros compatibles
    * Calendario semanal para agendar viajes con un solo clic.
    * Historial de viajes con opción de invitar a los mismos pasajeros.
    * Grupos preformados y búsqueda individual para sincronizar horarios con mayor anticipación.
  * Problema 2: No sabe si los pasajeros serán puntuales
    * Reputación visible: puntualidad y asistencia previa.
    * Notificaciones automáticas a pasajeros: “Tu conductor sale en 10 minutos”.
    * Penalización/reporte por inasistencia o retraso frecuente.
    * Comunicación post-viaje para calificar la puntualidad del pasajero.
  * Problema 3: No confía en la seguridad de compartir su auto
    * Configuración de privacidad: solo permitir pasajeros verificados o conocidos.
    * Información visible del perfil del pasajero (foto, carrera, historial).
    * Botón de bloqueo/reportar usuario desde el grupo de carpool.
  * Problema 4: No tiene un método integrado para cobrar a los pasajeros ni visualizar sus ahorros
    * Integración con Yape para solicitar aportes directamente desde la app.
    * Confirmación de viaje completado que registre automáticamente la contribución de cada pasajero.
    * Panel o dashboard que muestre cuántos viajes ha hecho, cuánta gasolina ha compensado y su comisión acumulada.
    * Manejo de la comisión: se define un porcentaje (por ejemplo, 10%) que la plataforma retiene. Puede ser cobro quincenal o mensual al conductor, o retención inmediata.
    * Mostrar cuántos pasajeros va llevando y cuánto ahorra con 1, 2 o 3 pasajeros, incentivando así llenar el carro.
    * Bonus por carro lleno: si hay 3 (o más) pasajeros confirmados, el conductor recibe un pequeño incentivo adicional que sale de la comisión recaudada.

* **Soluciones transversales**
  * Sistema de referidos y recompensas:
    *  Ganar puntos o descuentos al invitar amigos, mayor probabilidad de coincidir con gente confiable.
    *  Distintivos (badges) por cantidad de viajes compartidos, calificaciones positivas o referencias exitosas.
  * Gamificación:
    * Otorgar insignias o niveles (Bronce, Plata, Oro) dependiendo del número de viajes, buena reputación y puntualidad.
  * Penalizaciones y reputación:
    * Reglas claras en caso de cancelaciones de último minuto, no pagos, retrasos frecuentes, etc. 
    * Comunicación post-viaje para recopilar feedback rápido sobre puntualidad y comodidad.

* **Riesgos**

Recuerda que los riesgos son eventos inciertos que pueden afectar el éxito del proyecto. Se han identificado los siguientes riesgos por cada hipótesis:

  * H1:
    * Deseabilidad y confianza:
      * Es posible que las pasajeras sigan sin confiar en “desconocidos” aunque sean estudiantes; la validación institucional puede no ser suficiente para romper barreras culturales.
      * El chat y las calificaciones podrían no bastar para generar la seguridad esperada (p. ej. necesitan ver reseñas de viajes reales, fotos, etc.).
      
  * H2:
    * Viabilidad económica:
      * El ahorro del 30% podría no ser real si la tarifa propuesta (o el aporte al conductor) termina siendo igual o mayor que el transporte público debido a comisiones o altos costos de gasolina.
    * Disponibilidad de conductores:
      * El factor más fuerte en reducir costos es encontrar conductores suficientes. Sin masa crítica de conductores, la oferta será limitada y tal vez no se logre el ahorro deseado.
  
  * H3:
    * Complejidad de penalizaciones:
      * Implementar y gestionar correctamente un sistema de penalizaciones puede ser conflictivo; si es muy severo, los usuarios se van, si es muy laxo, pierde eficacia.

  * H4:
    * Evasión de la plataforma:
      * Conductor y pasajero podrían acordar pagar en efectivo o por otro medio fuera de la app, evitando la comisión.
    * Integración técnica con Yape:
      * El desarrollo y la coordinación con el servicio de pago podría presentar problemas o limitaciones.

  * H5:
    * Deseabilidad:
      * Diego podría no encontrar suficiente valor en la plataforma para organizar sus viajes; tal vez use canales informales (WhatsApp, Facebook).
      * No haya suficientes pasajeros interesados en la misma ruta/horario, lo cual desincentive a Diego a hacer su primer viaje.
    * Factibilidad técnica:
      * Implementar el “panel de sugerencias” y el “calendario semanal” puede requerir un algoritmo de coincidencia robusto, y podría ser más complejo de lo previsto.
    * Viabilidad de negocio:
      * Incluso si se ofrece la herramienta de coordinación, ¿la tasa de adopción será la suficiente para sostener la plataforma en el primer mes?

  * H6:
    * Exactitud de los cálculos:
      * La estimación de ahorro de S/8–12 podría no ser realista si la app no logra captar la cantidad de viajes o pasajeros necesarios.
    * Volumen de pasajeros y viajes:
      * La plataforma podría no captar suficientes pasajeros o viajes para que Diego vea un ahorro significativo en gasolina.
     
  * H7:
    * Atracción del incentivo:
      * La recompensa puede no ser suficiente para motivar a la gente a invitar amigos.
    * Visibilidad y usabilidad del programa:
      * Si el programa de referidos no está bien integrado en la app, pocos lo usarán.

  * H8:
    * Onboarding efectivo:
      * El proceso inicial podría ser confuso, largo o poco atractivo, generando abandono temprano.
    * Disponibilidad real de grupos o viajes:
      * Si la persona se registra, pero no ve ningún viaje o grupo al que unirse, simplemente no se activa.
    * Expectativas incumplidas:
      * El usuario podría llegar con altas expectativas tras ser invitado, pero la oferta de rutas o la experiencia no cumple sus necesidades, y se da de baja rápido.
     
* **Experimentos**

Para validar las hipótesis, se han diseñado experimentos que permitan obtener datos concretos sobre la aceptación de la solución propuesta. 
A continuación, se describen los experimentos y las métricas asociadas a cada hipótesis:

  * H1: 
    * Experimento: El equipo realizará breves entrevistas con pasajeras, mostrando un wireframe de validación institucional, calificaciones y chat. Al final, se aplicará una mini encuesta sobre cuán seguras se sienten.
    * Métrica: Se apunta a que entre el 50% y 70% indiquen que sí se unirían a un carpool tras ver esa verificación.
  * H2:
    * Experimento: Se entrevistará a estudiantes, presentándoles un boceto que compare “costo actual” vs. “carpool con seguimiento en tiempo real”. Luego, se harán 2-3 preguntas cerradas sobre la viabilidad del ahorro.
    * Métrica: Se busca que al menos 60% afirmen que cambiarían a la opción de carpool, validando la percepción de un 30% de reducción de costos.
  * H3:
    * Experimento: Se explicará la idea de penalizaciones y notificaciones en entrevistas, mostrando un wireframe sencillo con reputación. Al final, se incluirá una breve encuesta sobre su disposición a usar la app.
    * Métrica: Se apunta a que 50–60% declaren que continuarían activos, confirmando la retención prevista.
  * H4:
    * Experimento: El equipo mostrará un boceto de “Pagar con Yape + confirmación” a conductores y pasajeros, y al final hará una mini encuesta sobre la preferencia de pago.
    * Métrica: Se requiere que entre 40–50% indiquen que sí usarían la opción integrada, sustentando el cobro dentro de la plataforma.
  * H5:
    * Experimento: Se entrevistará a conductores y se presentará un wireframe de “panel de sugerencias” y “calendario semanal”. Después, se preguntará si lo usarían para su primer viaje.
    * Métrica: Se espera que 80% declaren que sí lo considerarían útil, validando la coordinación anticipada.
  * H6:
    * Experimento: Se mostrará un boceto de “panel de ahorro” a conductores y se harán 2-3 preguntas cerradas sobre su motivación al ver cuántos pasajeros llevan y el combustible compensado.
    * Métrica: Se necesita que 60% indiquen sentirse motivados al visualizar su ahorro, validando la hipótesis.
  * H7:
    * Experimento: El equipo realizará entrevistas con usuarios, describiendo un sistema de referidos con recompensas y mostrando un wireframe simple de “badges” o descuentos. Se incluirá una mini encuesta para medir la intención de compartir invitaciones.
    * Métrica: SSe busca que 15–25% afirmen que invitarían a conocidos a la plataforma, confirmando el potencial de crecimiento por referidos.
  * H8:
    * Experimento: Se entrevistará a nuevos usuarios, presentándoles un boceto de “onboarding” (perfil, zona/horario, unirse a un grupo). Al final, se incluirá una breve encuesta sobre su disposición a completar el proceso.
    * Métrica: Se espera que 10–15% confirmen que se convertirían en usuarios activos tras probar ese flujo de inicio, validando la eficacia del onboarding.

#### 1.2.2.3. Lean UX Hypothesis Statements

De ese modo, se junta la información de los usuarios, los resultados de negocio y los beneficios de la solución para crear las hipótesis.
Asímismo, se clasifican según los 4 cuadrantes del Hypothesis Prioritization Canvas.

* Test (Alto valor, alto riesgo)
  * H1: Creemos que entre el 50% y 70% de los usuarios pasajeros se unirán a un grupo de carpool
    si Valeria obtiene mayor confianza al compartir ruta con estudiantes verificados
    con la validación institucional, sistema de calificaciones y chat previo al viaje.
  * H2: Creemos que reduciremos en un 30% el costo de traslado
    si Valeria obtiene una alternativa confiable al transporte público
    con un algoritmo de coincidencia de rutas, posibilidad de “viaje en curso” y el seguimiento en tiempo real del conductor.
  * H3: Creemos que mantendremos una retención semanal de 50–60%
    si Valeria y Diego obtienen seguridad y previsibilidad en sus viajes
    con notificaciones automáticas, reputación visible y penalización de impuntuales.
  * H4: Creemos que entre el 40% y 50% de los viajes generarán comisión efectiva
    si los conductores obtienen un método integrado de cobro y confirmación
    con una integración de Yape dentro de la app y notificaciones de viaje completado.

* Ship & Measure (Alto valor, bajo riesgo)
  * H5: Creemos que lograremos que entre el 40% y 60% de los nuevos usuarios conductores realicen su primer viaje dentro del primer mes
    si Diego obtiene una forma clara de coordinar con otros estudiantes
    con un panel de sugerencias de pasajeros, calendario semanal y grupos preformados. 
  * H6: Creemos que alcanzaremos un ingreso promedio mensual de S/8–12 por conductor 
    si Diego obtiene visibilidad de cuántos pasajeros lleva y cuánto ahorra en gasolina 
    con un panel de comisiones, registro de viajes y aportes recibidos.
  * H7: Creemos que incentivaremos que entre el 15% y 25% de los usuarios inviten a nuevos compañeros
    si tanto pasajeros como conductores obtienen recompensas al referir contactos confiables
    con un sistema de invitaciones, seguimiento de referidos y badges por referencias exitosas.
  * H8: Creemos que entre el 10% y 15% de los referidos se convertirán en usuarios activos
    si los usuarios invitados obtienen una experiencia de onboarding clara
    con completar su perfil, zona/horario y unirse a un grupo de carpool (o “viaje en curso”) desde el primer ingreso.
  
* Don't test. Usually Don't Build (Bajo valor, bajo riesgo)
  * Actualmente, no se han identificado hipótesis que aporten poco valor y tengan bajo riesgo.

* Discard 
  * Tampoco se ha identificado ninguna hipótesis con riesgo alto y valor bajo dentro de la información actual.

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
