<body>
    <div style="text-align: center; font-weight: bolder">
        <p>Universidad Peruana de Ciencias Aplicadas - Ingeniería de Software - 7 Ciclo</p>
        <img src="assets/0.cover/logo-upc.png" alt="logo of UPC"/>
        <p>1ASI0657 - Fundamentos de Arquitectura de Software</p>
        <p>Sección - 6331</p>
        <p>Docente: Ing. Jorge Luis Delgado Vite</p>   
        <p>Informe de Trabajo Final<p>
        <p>Startup: CampusMov</p>
        <p>Producto: UniRide</p>
    </div>
    <div style="text-align: center; display: flex; flex-direction: column; align-items: center">
        <h3 style="font-weight: bolder">Integrantes del equipo:</h3>
        <table style="width: fit-content">
            <tr>
                <th style="text-align:start;">Estudiante</th>
                <th style="text-align:center;">Código</th>
            </tr>
            <tr>
                <td style="text-align:start;">Gutiérrez Soto, Jhosepmyr Orlando</td>
                <td>202317638</td>
            </tr>
            <tr>
                <td style="text-align:start;">Hernández Tuiro, Eric Ernesto</td>
                <td>20221C857</td>
            </tr>
            <tr>
                <td style="text-align:start;">Ramirez Mestanza, Salim Ignacio</td>
                <td>20201E843</td>
            </tr>
            <tr>
                <td style="text-align:start;">Riva Rodríguez, Elmer Augusto</td>
                <td>202220829</td>
            <tr>
              <td style="text-align:start;">Sulca Gonzales, Paul Fernando</td>
              <td>20221C486</td>
            </tr>
        </table>
    </div>
    <p style="text-align: center">Septiembre 2025</p>
</body>

<div style="page-break-before: always"></div>

# Registro de Versiones del Informe

| Versión | Fecha      | Autor                             | Descripción de modificación |
|---------|------------|-----------------------------------|-----------------------------|

<div style="page-break-before: always"></div>

# Project Report Collaboration Insights

En esta sección se documenta la colaboración del equipo en la elaboración del informe, mostrando evidencias gráficas de la actividad en GitHub y su coherencia con el registro de versiones.

* URL del repositorio del Project Report en la organización de GitHub del equipo:
* [https://github.com/CampusMov/Report](https://github.com/CampusMov/Report)

<div style="page-break-before: always"></div>

# Contenido

<!-- TOC -->
* [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
* [Project Report Collaboration Insights](#project-report-collaboration-insights)
* [Contenido](#contenido)
* [Student Outcome](#student-outcome)
* [Capítulo I: Introducción](#capítulo-i-introducción)
  * [1.1. Startup Profile](#11-startup-profile)
    * [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    * [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  * [1.2. Solution Profile](#12-solution-profile)
    * [1.2.1. Nombre del producto](#121-nombre-del-producto)
    * [1.2.2. Antecedentes y problemática](#122-antecedentes-y-problemática)
    * [1.2.3. Lean UX Process](#123-lean-ux-process)
      * [1.2.3.1. Lean UX Problem Statement](#1231-lean-ux-problem-statement)
      * [1.2.3.2. Lean UX Assumptions](#1232-lean-ux-assumptions)
      * [1.2.3.3. Lean UX Hypothesis](#1233-lean-ux-hypothesis)
      * [1.2.3.4. Lean UX Canvas](#1234-lean-ux-canvas)
  * [1.3. Segmentos objetivos](#13-segmentos-objetivos)
* [Capítulo II: Requirements & Analysis](#capítulo-ii-requirements--analysis)
  * [2.1. Competidores](#21-competidores)
  * [2.2. Entrevistas](#22-entrevistas)
  * [2.3. Need finding](#23-need-finding)
    * [2.3.1. User personas](#231-user-personas)
    * [2.3.2. User Task Matrix](#232-user-task-matrix)
    * [2.3.3. Empathy Maps](#233-empathy-maps)
    * [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
* [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  * [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  * [3.2. User Stories](#32-user-stories)
  * [3.3. Impact Map](#33-impact-map)
  * [3.4. Product Backlog](#34-product-backlog)
* [Conclusiones](#conclusiones)
* [Bibliografía](#bibliografía)
* [Anexos](#anexos)
<!-- TOC -->

<div style="page-break-before: always"></div>

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

****ABET - EAC - Student Outcome 7****

**Criterio:** La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 7.

| **Criterio específico**                                                                                                                      | **Acciones realizadas** | **Conclusiones** |
|----------------------------------------------------------------------------------------------------------------------------------------------|-------------------------|------------------|  
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software..** |                         |                  |
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.**   |                         |                  |

<div style="page-break-before: always"></div>

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

CampusMov es una startup creada por estudiantes de la carrera de Ingeniería de Software. Nuestro objetivo es mejorar y optimizar la movilización de alumnos universitarios mediante la creación de software.

**Misión**

Desarrollar soluciones tecnológicas innovadoras que mejoren la experiencia de movilidad de los estudiantes universitarios, reduciendo el impacto del tráfico en su vida diaria y facilitando desplazamientos más eficientes, conectados y sostenibles dentro del entorno urbano.

**Visión**

Llegar a los universitarios de todo el país para mejorar su movilidad en ciudades con alto tráfico y ser reconocida como una empresa importante en el tráfico urbano en 5 años.


### 1.1.2. Perfiles de integrantes del equipo

| Foto del participante                                                    | Nombres y apellidos              | Código de estudiante | Carrera                | Conocimientos técnicos y habilidades                                                                                                                              |
|--------------------------------------------------------------------------|----------------------------------|----------------------|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![erick.png](assets/1.introduction/1.1.2.team-members/erick.png)         | Eric Ernesto Hernández Tuiro     | 20221C857            | Ingeniería de Software | Conocimientos en Java, C++, C#, Python, SQL, Angular, Vue.js, React y ASP .Net Core.                                                                              |
| ![elmer.png](assets/1.introduction/1.1.2.team-members/elmer.png)         | Elmer Augusto Riva Rodríguez     | 202220829            | Ingeniería de Software | Conocimientos en Angular, Vue, React, ASP .Net Core, Spring Boot y desarrollo de APIs RESTful. Experiencia en integración frontend-backend y metodologías ágiles. | 
| ![jhosepmyr.png](assets/1.introduction/1.1.2.team-members/jhosepmyr.png) | Jhosepmyr Orlando Gutiérrez Soto | 202317638            | Ingeniería de Software | Conocimientos en Micro servicios, Spring boot, ASP .NetCore, Angular, Vue.js, DDD, TDD, BDD, GitOps, Git Actions, Docker, Kubernetes y Google Kubernetes Engine.  |

## 1.2. Solution Profile

### 1.2.1. Nombre del producto

### 1.2.2. Antecedentes y problemática

### 1.2.3. Lean UX Process

#### 1.2.3.1. Lean UX Problem Statement

#### 1.2.3.2. Lean UX Assumptions

#### 1.2.3.3. Lean UX Hypothesis

#### 1.2.3.4. Lean UX Canvas

## 1.3. Segmentos objetivos

# Capítulo II: Requirements & Analysis

## 2.1. Competidores

## 2.2. Entrevistas

## 2.3. Need finding

### 2.3.1. User personas

### 2.3.2. User Task Matrix

### 2.3.3. Empathy Maps

### 2.3.4. As-is Scenario Mapping

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Impact Map

## 3.4. Product Backlog

# Conclusiones

# Bibliografía

# Anexos
