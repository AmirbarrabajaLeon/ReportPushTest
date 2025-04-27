# COURSE PROJECT

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Desarrollo de Aplicaciones Open Source - 4317</strong><br>
    <strong>Profesor: Alberto Wilmer Sánchez Seña</strong><br>
    <br>INFORME
</p>

<p align="center">
    <strong>Startup: Flow Senses </strong><br>
    <strong>Producto: Flow Senses </strong>
</p>

<div>
    <h3 align="center">Team Members:</h3>
    </div>
<div>
     <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Castro Sanchez, Amir Gabriel</td>
            <td>U202310680</td>
        </tr>
        <tr>
            <td>Moscoso Bejar, Angelo Stephano</td>
            <td> U20211G499</td>
        </tr>
        <tr>
            <td>Alvarez Ponce, Carlos Antonio</td>
            <td>U201919386</td>
        </tr>
        <tr>
            <td>Carranza Tesen, Joaquin Enrique</td>
            <td>U20191B935</td>
        </tr>
        <tr>
            <td>Osores Marchese, Pietro</td>
            <td>U202310971</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Abril 2025</strong>
</p>

<br>

---

# Project Report Collaboration Insights

| **Integrante** | **Responsabilidades** | **Aporte al Proyecto** |
| --- | --- | --- |
| **Pietro (TB1)** | Capítulo I y parte del Capítulo II: Perfil de la startup, antecedentes del problema, proceso Lean UX y segmentos objetivo. | Establecí la base del proyecto identificando el problema y validando la necesidad de la solución. Elaboré los perfiles, estructuré el análisis contextual y desarrollé el enfoque Lean UX completo para definir correctamente la solución. |
| **Stephano (TB1)** | Entrevistas, análisis cualitativo y herramientas de Needfinding: User personas, empathy maps, user journey, etc. | Validé las necesidades reales de los usuarios mediante entrevistas y mapas de empatía. Esto nos permitió tener una visión clara de sus expectativas y comportamientos, asegurando que la solución propuesta esté centrada en el usuario. |
| **Carlos (TB1)** | Diseño visual y arquitectura de información: Guías de estilo, etiquetado, navegación, SEO. | Me aseguré de que la interfaz del sistema sea clara, funcional y accesible. Organicé la arquitectura de información y definí los estándares visuales para mantener una experiencia consistente. |
| **Joaquín (TB1)** | Diseño UX/UI y arquitectura de software: Wireframes, prototipos, diagramas y base de datos. | Estructuré visual y técnicamente la aplicación. Me enfoqué en los flujos de navegación y lógica del sistema para asegurar que la experiencia de usuario sea fluida y que la arquitectura sea escalable. |
| **Amir (TB1)** | Implementación, configuración y despliegue: Sprint planning, entorno de desarrollo, documentación. | Me encargué de la implementación técnica y del despliegue del producto. Realicé la configuración del entorno, codifiqué los módulos funcionales y documenté cada fase de desarrollo para mantener un control estructurado. |


# Registro de Versiones

| **Versión** | **Fecha** | **Responsable** | **Descripción del Cambio** |
| --- | --- | --- | --- |
| 1.0 | 23/04/2025 | Equipo de Proyecto (Pietro, Stephano, Carlos, Joaquín, Amir) | Se desarrolló la primera versión del proyecto. Se completaron los siguientes capítulos: Introducción, Elicitación y Análisis de Requisitos, Especificación de Requisitos y Diseño del Producto. Incluye definiciones clave como perfiles, Lean UX, entrevistas, diseño de interfaces, arquitectura, base de datos y planificación de implementación. También se elaboraron los apartados de Student Outcome, Collaboration Insights y Registro de Versiones. |


# Contenido 
## Tabla de contenidos
### [Registro de versiones del informe](#registro-de-versiones-del-informe)
### [Project Report Collaboration Insights](#project-report-collaboration-insights)
### [Student Outcome](#student-outcome)
## [Capítulo I: Introducción](#capítulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

## [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)


  ## [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

## [Capítulo IV: Product Design](#capítulo-iv-product-design)
- [4.1. Style Guidelines](#41-style-guidelines)
  - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
  - [4.2.1. Organization Systems](#421-organization-systems)
  - [4.2.2. Labeling Systems](#422-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
  - [4.2.4. Searching Systems](#424-searching-systems)
  - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
  - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
  - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
  - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
  - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
  - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
  - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
  - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
  - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
  - [4.8.1. Database Diagram](#481-database-diagram)

## [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
  - [5.2.1. Sprint 1](#521-sprint-1)
    - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
    - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
    - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
    - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
    - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
    - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
    - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
    - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
 
## [Conclusiones](#conclusiones)

## [Bibliografía](#bibliografía)

## [Anexos](#anexos)


---

