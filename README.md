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


# Student Outcome

| **Criterio específico** | **Acciones realizadas (Responsables y Aportes)** | **Conclusión** |
| --- | --- | --- |
| **2.c1. Diseñar soluciones en ingeniería de software (productos, procesos y/o servicios) que satisfagan necesidades específicas considerando el impacto en salud pública, seguridad, bienestar, así como factores globales, culturales, sociales, ambientales y económicos** | **—Pietro (TB1):** Me encargué de definir el perfil de la startup y de los usuarios, así como de identificar el problema central y plantear hipótesis dentro del proceso Lean UX. Esto me permitió diseñar una solución centrada en las necesidades reales de las personas, considerando su entorno social y económico.                              — **Stephano (TB1):** Diseñé y apliqué entrevistas, además de realizar el Needfinding con herramientas como user personas y empathy maps. Esto me ayudó a comprender en profundidad a los usuarios, sus comportamientos y contextos culturales, permitiéndome contribuir con una solución más empática y contextualizada.      — **Carlos (TB1):** Elaboré las guías de estilo y la arquitectura de información del sistema. Mi enfoque fue asegurar que el diseño sea accesible y comprensible para distintos usuarios, respetando criterios de claridad, estructura y adaptabilidad.                              — **Joaquín (TB1):** Me ocupé del diseño UX/UI de las aplicaciones web, incluyendo wireframes, mockups y diagramas de flujo. Busqué que las soluciones fueran intuitivas y funcionales, tomando en cuenta la escalabilidad y eficiencia del sistema.                                        — **Amir (TB1):** Me encargué de la configuración del entorno de desarrollo, implementación y despliegue del software. Me aseguré de que la solución fuese técnicamente viable y estuviera lista para ser usada de manera segura y estable. | Diseñamos soluciones centradas en el usuario, tomando en cuenta el contexto social, económico y técnico. Cada decisión fue sustentada por análisis reales y prácticas que garantizan funcionalidad, accesibilidad e impacto positivo. |
| **2.c2. Validar que el diseño de la solución de software considere aspectos en salud pública, seguridad, bienestar, así como factores globales, culturales, sociales, ambientales y económicos** | **—Pietro (TB1):** Validé el problema y las hipótesis con base en el contexto social de los usuarios, asegurándome de que el diseño tuviera sentido y respondiera a una necesidad real, considerando variables sociales y económicas.                             — **Stephano (TB1):** Validé la propuesta con usuarios reales mediante entrevistas y herramientas como empathy maps y user journey. Esto me permitió asegurar que la solución se alinee con las emociones, necesidades y entornos de los usuarios.              — **Carlos (TB1):** Me aseguré de que la interfaz cumpla estándares de diseño accesible e inclusivo, permitiendo a todo tipo de usuario interactuar con facilidad, sin importar sus limitaciones o entorno.               — **Joaquín (TB1):** Validé los prototipos y flujos de navegación, asegurándome de que la experiencia sea coherente, fluida y adaptada al contexto del usuario.                  — **Amir (TB1):** Aporté validando la funcionalidad técnica de la solución durante su implementación y despliegue. Verifiqué que el sistema sea seguro, estable y cumpla con lo propuesto en las etapas de diseño. | Validamos que nuestra solución de software sea funcional, accesible y coherente con la realidad de los usuarios. El diseño fue comprobado en cada etapa, considerando el impacto social, cultural y técnico. |


# Capitulo I: Introduccion

---

## 1.1. StartUp Profile

---

1.1.1. Descripcion del startup

**Flow Sense** es una startup tecnológica innovadora que ofrece una solución integral para la gestión del tiempo, la productividad y la eficiencia laboral, diseñada para cubrir las necesidades tanto de empresas como de trabajadores independientes. La plataforma combina el poder de las tecnologías emergentes, como sensores IoT, inteligencia artificial e integración con asistentes de voz, para brindar herramientas inteligentes, automatizadas y altamente personalizadas que se adaptan al ritmo y estilo de cada usuario. En el caso de las empresas, Flow Sense permite una supervisión en tiempo real del personal y del entorno de trabajo, la automatización eficiente de turnos y una mejora continua en la productividad gracias al análisis de datos obtenidos desde el espacio físico a través de sensores conectados. Por otro lado, para freelancers y profesionales independientes, Flow Sense se convierte en un asistente digital confiable que registra automáticamente las horas trabajadas, organiza tareas y clientes, genera facturas inteligentes y se integra con dispositivos personales, facilitando así una gestión moderna y sin fricciones del trabajo diario.

La **misión** de Flow Sense es transformar la manera en que las personas y las organizaciones gestionan su tiempo y productividad, ofreciendo soluciones tecnológicas intuitivas, inteligentes y accesibles que se adapten a distintos estilos de trabajo, promoviendo el equilibrio entre eficiencia y bienestar.

### **1.1.2. Perfiles de integrantes del equipo**


- **Pietro Osores Marchese** – Soy estudiante de Ingeniería de Software con un fuerte interés en la innovación tecnológica y el diseño centrado en el usuario. Me considero una persona organizada, con habilidades para liderar y analizar problemas de forma estructurada. En este proyecto, me encargué de definir los perfiles del equipo, analizar los antecedentes del problema y desarrollar todo el enfoque Lean UX, estableciendo así las bases conceptuales de nuestra solución.
- **Amir Castro** – CTO: Responsable del desarrollo tecnológico, con experiencia en arquitectura de software, IoT y AI.
- **Carlos [Apellido]** – UX/UI Designer: Diseñador centrado en la experiencia de usuario, encargado de construir interfaces intuitivas y accesibles.
- **Stephano Moscoso** –Tengo 20 años estoy estudiando actualmente en la Univeridad Peruana de Ciencias Aplicadas. Me ha interasado mucho la creación de paginas web para diversos objetivos. Manejo algunos lenguajes de programación como javascript, C++, C+, Python, entre otros. Considero que tengo las habilidades de comunicación efectiva, organización, proactividad, resolución de problemas, entre otras. Espero aportar de manera satisfactoria en mi grupo para terminar de manera exitosa el proyecto.
- **Joaquín Carranza** – Hola, soy Joaquín Carranza. Tengo 24 años y actualmente curso el sexto ciclo de la carrera de Ingeniería de Software. Me gusta la tecnología y la forma en que ayuda a las personas a resolver problemas de manera más rápida y eficiente. Me interesa especialmente el manejo de datos y la ciberseguridad. Siento que puedo aportar a mi equipo ideas desde otra perspectiva, ya que siempre me cuestiono cómo se podría mejorar el producto o hacia qué objetivo estamos apuntando.

## **1.2.2. Lean UX Process**

El enfoque Lean UX nos ha permitido definir con claridad los problemas clave, entender las suposiciones tanto del negocio como de los usuarios, y plantear hipótesis que guiarán el diseño de nuestro producto, minimizando el desperdicio de recursos y optimizando el aprendizaje continuo.

---

### **1.2.2.1. Lean UX Problem Statements**

**Problem Statement**

Nuestro propósito es desarrollar una aplicación inteligente que ayude a empresas y freelancers a gestionar su tiempo de trabajo de forma automatizada y eficiente, a través de sensores y herramientas de análisis del entorno laboral.

Hemos observado que muchas empresas tienen dificultades para supervisar en tiempo real la productividad y bienestar de su personal, mientras que los freelancers enfrentan retos para organizar su jornada laboral, registrar sus horas y facturar a sus clientes adecuadamente.

Este problema refleja una necesidad urgente de mejorar la organización, automatización y transparencia en la gestión del tiempo laboral. La pregunta que nos planteamos es:

**¿Cómo podemos diseñar una solución tecnológica que permita a empresas y freelancers registrar, supervisar y optimizar el uso del tiempo de trabajo de manera eficiente, precisa y adaptada a las nuevas dinámicas laborales?**

---

### **1.2.2.2. Lean UX Assumptions**

### **Business Assumptions**

**Necesidades de los Clientes**

Creemos que las empresas necesitan herramientas que les brinden control, monitoreo en tiempo real y reportes sobre el tiempo y desempeño del personal. Por su parte, los freelancers buscan una plataforma que les ayude a organizar sus proyectos, gestionar múltiples clientes, registrar automáticamente sus horas y facturar sin complicaciones.

**Solución Propuesta**

Flow Sense es una aplicación web con soporte para dispositivos IoT y asistentes de voz, orientada a dos segmentos:

- **Para empresas:** permite supervisar el entorno laboral, automatizar turnos, detectar patrones de productividad y bienestar con ayuda de sensores.
- **Para freelancers:** ofrece funciones de gestión de proyectos, clientes, registro automático del tiempo trabajado y facturación inteligente.

**Valor Principal**

- **Para Empresas:** Visibilidad completa del entorno laboral, mayor eficiencia operativa y bienestar del personal gracias a la automatización y el análisis de datos.
- **Para Freelancers:** Organización total de su jornada laboral, mejor gestión de clientes y finanzas, sin perder el enfoque creativo y productivo.

**Beneficios Adicionales**

- Automatización de tareas repetitivas.
- Integración con asistentes de voz y dispositivos personales.
- Análisis del bienestar mediante patrones detectados por sensores.
- Sugerencias inteligentes de productividad basadas en IA.

**Adquisición de Clientes**

La estrategia se enfocará en LinkedIn, campañas B2B, convenios con coworkings, comunidades de freelancers y ferias tecnológicas.

**Modelo de Ingresos**

- **Empresas:** Suscripción mensual por empleado y por módulo utilizado.
- **Freelancers:** Modelo freemium con planes premium que ofrecen reportes avanzados, facturación automática, y exportación de datos.

**Competencia**

Competimos con plataformas como Clockify, Toggl, Factorial y Notion. Nos diferenciamos por:

- Enfoque dual (empresas y freelancers).
- Automatización avanzada mediante sensores.
- Integración profunda con dispositivos personales.
- Análisis del entorno de trabajo y estado emocional del usuario.

**Riesgos Principales**

- Baja adopción inicial del producto.
- Preocupaciones por la privacidad y el uso de sensores.
- Resistencia al cambio en procesos ya establecidos.

**Estrategias para Mitigar Riesgos**

- Onboarding guiado y sencillo.
- Controles de privacidad personalizados.
- Pruebas gratuitas con testimonios validados.

---

### **User Assumptions**

**¿Quién es el usuario?**

- **Empresas:** Supervisores, gerentes de RRHH y líderes de equipos.
- **Freelancers:** Profesionales independientes del sector digital.

**¿Dónde encaja nuestro producto en sus vidas?**

- Empresas lo usan como sistema de monitoreo y productividad.
- Freelancers lo integran como su asistente de trabajo diario.

**¿Qué problema resuelve nuestro producto?**

- Automatiza procesos tediosos como el control de horas, planificación y facturación.
- Mejora la visibilidad del estado de los equipos y la salud laboral.

**¿Cuándo y cómo es usado nuestro producto?**

- Empresas: diariamente desde el panel web de administración.
- Freelancers: desde cualquier dispositivo conectado, en sesiones de trabajo activas.

**¿Qué características son importantes?**

- Registro automático del tiempo.
- Facturación y reportes inteligentes.
- Dashboard con métricas de bienestar y eficiencia.
- Integración con asistentes de voz y sensores personales.

---

### **Feature Assumptions**

- Detección automática de inicio y fin de jornada mediante sensores.
- Facturación automática vinculada al tiempo registrado.
- Panel de métricas personalizable.
- Alertas sobre rendimiento, pausas y bienestar.
- Soporte para dispositivos como Alexa, Google Assistant y smartwatches.

---

### **Business Outcomes**

- 500 empresas y 1000 freelancers registrados en los primeros 6 meses.
- Retención mensual del 70% en ambos segmentos.
- Reducción del 40% en tareas administrativas para empresas.
- Aumento del 20% en la facturación mensual promedio de freelancers.

---

### **Users**

Los usuarios principales son empresas con equipos presenciales o híbridos, y freelancers del entorno digital. Ambos buscan mejorar su organización, productividad y bienestar laboral mediante tecnología inteligente.

---

### **User Outcomes & Benefits**

**Para Empresas:**

- Mayor control de la operación en tiempo real.
- Automatización de procesos clave.
- Prevención de fatiga y baja productividad.

**Para Freelancers:**

- Control y registro completo del tiempo trabajado.
- Mejora en la planificación personal.
- Facturación clara, precisa y rápida.

---

### **1.2.2.3. Lean UX Hypothesis Statements**

**Hipótesis 01:**

Creemos que al ofrecer una aplicación con registro automático de horas y facturación inteligente para freelancers, reduciremos el tiempo que dedican a tareas administrativas.

**Sabremos que hemos tenido éxito** cuando los usuarios reporten un ahorro de al menos 30 minutos diarios en tareas repetitivas.

**Hipótesis 02:**

Creemos que al integrar sensores y asistentes de voz en el entorno empresarial, las empresas podrán mejorar la supervisión sin afectar el bienestar de sus empleados.

**Sabremos que hemos tenido éxito** cuando se reduzcan los reportes de estrés y se incremente la productividad promedio.

**Hipótesis 03:**

Creemos que al facilitar dashboards con reportes en tiempo real, los supervisores podrán tomar decisiones más informadas y rápidas.

**Sabremos que hemos tenido éxito** cuando el 80% de los supervisores indique que la aplicación les permite actuar proactivamente ante problemas.

**Hipótesis 04:**

Creemos que al proporcionar una experiencia intuitiva y flexible, lograremos que los freelancers adopten Flow Sense como su herramienta principal.

**Sabremos que hemos tenido éxito** cuando el tiempo medio de uso diario supere los 20 minutos y se incrementen las suscripciones premium.

**Hipótesis 05:**

Creemos que al fomentar la integración con dispositivos personales, Flow Sense se volverá una extensión natural del día a día del usuario.

**Sabremos que hemos tenido éxito** cuando más del 60% de usuarios activen al menos una integración con su dispositivo o asistente personal.

---

### **1.2.2.4. Lean UX Canvas**

![Image](https://github.com/user-attachments/assets/6746607f-0e05-47c2-997d-1a401f571b47)

---

### **1.3. Segmentos Objetivo**

- **Empresas medianas y grandes** con necesidad de control operativo, turnos rotativos y supervisión híbrida.
- **Freelancers** en áreas como diseño, desarrollo, consultoría y marketing, que necesitan optimizar su tiempo y facturación.


---

