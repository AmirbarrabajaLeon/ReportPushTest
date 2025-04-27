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
=======
## **Capítulo II: Requirements Elicitation & Analysis**

### **2.1. Competidores**

### **2.1.1. Análisis Competitivo**

| **Competidor** | **Fortalezas** | **Debilidades** |
| --- | --- | --- |
| Toggl Track | UI amigable, seguimiento de tiempo, integraciones | Falta de automatización, sin IoT |
| Clockify | Gratuito, multiusuario | Interfaz básica, sin análisis predictivo |
| Harvest | Facturación integrada | Limitado en automatización e IA |
| RescueTime | Seguimiento automático | No personalizable, no apto para empresas |
| ActivTrak | Análisis avanzado, ideal para empresas | Alto costo, difícil implementación para pymes |

---
### **2.2. Entrevistas**




### **2.1.2. Estrategias y tácticas frente a competidores**

- **Diferenciación tecnológica**: Incorporar sensores IoT para recolección automática de datos en tiempo real, una característica no ofrecida por los competidores.
- **Experiencia unificada**: Combinar seguimiento de tiempo, gestión de clientes y facturación en una sola app fácil de usar.
- **Modelo freemium escalable**: Atraer freelancers con versión gratuita con funciones clave y ofrecer planes premium con más automatización.
- **Estrategia B2B personalizada**: Implementar soluciones modulares y adaptables para empresas de distintos tamaños.
- **Enfoque en bienestar laboral**: No solo medir, sino mejorar el clima organizacional mediante recomendaciones basadas en datos.

## 2.2.1. Diseño de entrevistas

### Preguntas Generales:
- ¿Cuál es tu nombre?
- ¿Qué edad tienes?
- ¿Dónde vives actualmente?
- ¿A qué te dedicas?

---

### Segmento 1: Gerentes (Empresas)
1. ¿Qué desafíos enfrentas actualmente al gestionar la productividad y el bienestar de tus empleados?
2. ¿Cómo supervisas el cumplimiento de horarios y tareas en tu equipo? ¿Qué herramientas utilizas?
3. ¿Cómo manejas el bienestar laboral de tus empleados? ¿Realizas alguna medición o encuesta para conocer su estado emocional o físico?
4. ¿Qué tipo de datos te gustaría tener en tiempo real sobre la productividad de tus empleados?
5. ¿Qué tan importante es para ti contar con un sistema que te ofrezca visibilidad y control sin tener que supervisar manualmente cada detalle?
6. ¿Cómo crees que la integración de datos en tiempo real podría mejorar la eficiencia y la toma de decisiones en tu empresa?
7. ¿Qué tan dispuestos están tus empleados a utilizar nuevas herramientas tecnológicas para mejorar su productividad y bienestar?
8. ¿Qué función consideras esencial para optimizar la gestión de tiempo y productividad de tu equipo?

---

### Segmento 2: Freelancers (Profesionales independientes del rubro digital)
1. ¿Cuáles son los principales retos que enfrentas al gestionar tu tiempo y proyectos como freelancer?
2. ¿Cómo administras actualmente tu relación con los clientes, especialmente en cuanto a plazos, tareas y pagos?
3. ¿Utilizas alguna herramienta para organizar tus proyectos y tareas? ¿Qué te gusta o no te gusta de ellas?
4. ¿Cuánto valoras el tener control total sobre tu horario y trabajo, y cómo gestionas esa flexibilidad?
5. ¿Cómo prefieres recibir pagos por tu trabajo y qué tipo de sistema de facturación usas actualmente?
6. ¿Qué funcionalidades te gustaría que tuviera una herramienta para freelancers para ayudarte a ser más eficiente?
7. ¿Qué tan importante es para ti que tu plataforma te ayude a realizar un seguimiento del tiempo invertido en cada proyecto o tarea?
8. ¿Estás dispuesto a pagar por una herramienta que te ayude a gestionar todo tu trabajo y clientes de manera más eficiente? ¿Por qué?
9. ¿Te gustaría tener alguna funcionalidad que te permita tener acceso a análisis sobre tu rendimiento y áreas a mejorar?
10. ¿Qué tan útil sería para ti una plataforma que integre todas tus necesidades laborales (planificación, facturación, comunicación con clientes)?

---

## Entrevistas Segmento 1: Gerentes

### Resumen de la Entrevista - Ingrid Leiva
- **Entrevistado:** Ingrid Leiva
- **Edad:** 41 años
- **Ocupación:** Propietaria de empresa de catering
- **Ubicación:** Comas, Lima, Perú

**Resumen de la entrevista:**

Ingrid Leiva, de 41 años, es dueña y jefa de su propio negocio de catering. Su empresa brinda servicios de catering para eventos y ella supervisa tanto la logística como el bienestar de su equipo. Ingrid enfrenta desafíos con la gestión de los horarios de entrada y salida de sus empleados, ya que algunos no llegan a tiempo. Actualmente, tiene implementado un sistema de control de asistencia con tarjetas, pero sigue buscando una solución más eficiente que le brinde mayor visibilidad en tiempo real sobre el estado de su personal.

Ingrid también se ocupa del bienestar emocional de su equipo mediante actividades como juegos y dinámicas, con la ayuda de una psicóloga, para identificar posibles problemas entre sus empleados. Ingrid está abierta a integrar tecnologías que proporcionen visibilidad en tiempo real sobre la ubicación y productividad de su personal, lo que le permitiría optimizar los tiempos de trabajo y mejorar la supervisión sin necesidad de estar presente todo el tiempo.

Ingrid considera fundamental contar con un sistema que gestione los horarios de trabajo de manera eficiente y optimice los tiempos. Además, subrayó la importancia de integrar la tecnología para mejorar la productividad de su equipo y aumentar la rentabilidad de su negocio.

**Link de la entrevista:** [Enlace Entrevista Ingrid](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211g499_upc_edu_pe/ES1lbUGmzaZBgHztGdCRqIMBEwWiFm7n1clXRJijo9frDg?e=E3Y9rK&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

**Foto de evidencia de la entrevista:**  
![Entrevista Ingrid](https://github.com/user-attachments/assets/260c2186-986a-49af-9ce9-bcdedef1f699)
>>>>>>> feature/chapter-2


---


<<<<<<< HEAD
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
=======
### Resumen de la entrevista -  Anderson Gonza
- **Entrevistado:** Anderson Gonza Morales
- **Edad:** 28 años
- **Ocupación:** Supervisor en empresa de servicios logísticos
- **Ubicación:** Lima, Perú

**Resumen de la entrevista:**

Anderson Gonza, de 28 años, es supervisor en una empresa de servicios logísticos en Lima. Su principal reto es mantener motivado a su equipo en un entorno de trabajo exigente, donde el ritmo puede afectar el ánimo y la productividad de los empleados.

Para gestionar horarios y tareas, usa hojas de control, aplicativos internos y realiza supervisiones presenciales. Sobre el bienestar del equipo, conversa con ellos cuando detecta algo inusual, y la empresa aplica encuestas de clima laboral dos veces al año.

Le gustaría contar con datos en tiempo real sobre avance de tareas, tiempos muertos y señales de agotamiento. Esto le permitiría actuar rápidamente y mejorar la planificación sin necesidad de supervisar todo manualmente.

Anderson cree que su equipo está dispuesto a probar nuevas herramientas si son sencillas y útiles. Considera clave una función que muestre el progreso de cada tarea, lo que facilitaría la gestión de equipos grandes y mejoraría la eficiencia general.

**Link de la entrevista:** [Enlace Entrevista Anderson]([https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211g499_upc_edu_pe/EXn_e16u88tFlf8dm4JUEPQBFJEgLYT2OOubvaLpRp0r_Q?e=PZHETL](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20191b935_upc_edu_pe/Ed_kAsD-gwxBpQRQzMU61VMBSsJGslMwKjqvCIFAnxkGDA?e=a2XHlx))

**Foto de evidencia de la entrevista:**  
![Entrevista Anderson](https://github.com/user-attachments/assets/830ae84f-3d7c-41d8-93f5-7369a007df40)

---

## Entrevistas Segmento 2: Freelancers

### Resumen de la Entrevista - Letizia Aguilar López
- **Entrevistado:** Letizia Aguilar López
- **Edad:** 23 años
- **Ocupación:** Community Manager (Freelancer)
- **Ubicación:** San Miguel, Lima, Perú

**Resumen de la entrevista:**

Letizia Aguilar López, de 23 años, es Community Manager y trabaja de manera freelance. Reside en el distrito de San Miguel, Lima. En su trabajo, enfrenta desafíos relacionados con la tecnología y la gestión del tiempo, ya que las plataformas de redes sociales a veces presentan errores en la configuración de contenido audiovisual, lo que retrasa su proceso. Utiliza WhatsApp para comunicarse directamente con los clientes y ClickUp para gestionar sus tareas, aunque señala que la plataforma puede resultar compleja para nuevos usuarios debido a su amplia gama de opciones y herramientas.

Letizia valora tener control sobre su horario y trabajo, ya que le permite organizar su tiempo de manera flexible, algo crucial como freelancer. La gestión del tiempo es esencial para ella, pues los retrasos en las tareas generan complicaciones. Además, le gustaría que las herramientas que utilice proporcionen un seguimiento detallado sobre el tiempo invertido en cada tarea, lo que le ayudaría a mejorar la eficiencia tanto a nivel personal como de equipo. También destacó la importancia de la retroalimentación para identificar áreas de mejora.

En cuanto a la facturación, Letizia usa billeteras digitales como YAPE y BCP para gestionar los pagos, por lo que valora la agilidad de los sistemas de pago. Además, expresó su interés en colaborar con ilustradores y en tener un contacto directo con ellos a través de una plataforma que permita chats en vivo o videollamadas. Finalmente, mencionó que le gustaría que la plataforma centralice todas sus necesidades laborales, desde la gestión de tareas hasta la facturación, eliminando la necesidad de usar varias herramientas al mismo tiempo.

**Link de la entrevista:** [Enlace Entrevista Letizia](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211g499_upc_edu_pe/EY1mS3V1TnlCjECGfDkXUAUBoVj7q7pWOKDLfxtNyTjCMA?e=V7dHYl)

**Foto de evidencia de la entrevista:**  
![Entrevista Letizia](https://github.com/user-attachments/assets/a3f7e359-5a36-4767-9953-c47524e30e3f)


---


### Resumen de la Entrevista - Rodrigo Valencia
- **Entrevistado:** Rodrigo Valencia
- **Edad:** 22 años
- **Ocupación:** Freelancer de Animación Digital
- **Ubicación:** Comas, Lima, Perú

**Resumen de la entrevista:**

Rodrigo es freelancer en animación digital y enfrenta varios retos relacionados con la sobrecarga de trabajo y la gestión de proyectos complejos con plazos ajustados. Su principal dificultad es gestionar el tiempo de manera eficiente, ya que a menudo se ve presionado por la exigencia de los clientes respecto a los plazos de entrega.

En cuanto a la gestión de sus relaciones con los clientes, Rodrigo destaca que el tipo de proyecto y su complejidad determina el tiempo que le tomará completarlo, lo que impacta en los pagos y en la negociación de plazos. Además, utiliza Excel como su principal herramienta de organización, aunque reconoce que le gustaría contar con una herramienta que lo ayude a administrar mejor el tiempo y los plazos de entrega, específicamente una plataforma que tenga recordatorios o temporizadores para gestionar el tiempo restante de cada tarea.

Rodrigo valora profundamente tener control sobre su horario y trabajo, ya que siendo su propio jefe, tiene la libertad de organizar sus tareas. También utiliza PayPal como método de pago digital para recibir sus ingresos. En términos de herramientas, le gustaría una plataforma que centralice todas sus tareas y comunicaciones con los clientes, lo que lo ayudaría a ser más eficiente y mantener su flujo de trabajo organizado.

En resumen, Rodrigo busca una herramienta eficiente que lo ayude a gestionar mejor su tiempo, tareas y proyectos, con características como un temporizador o recordatorio de plazos y una integración para el seguimiento de sus pagos y relaciones con clientes. Está dispuesto a invertir en una plataforma que le ofrezca estos beneficios, ya que esto lo ayudaría a manejar su carga de trabajo y a mejorar su productividad.

**Link de la entrevista:** [Enlace Entrevista Rodrigo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211g499_upc_edu_pe/EXn_e16u88tFlf8dm4JUEPQBFJEgLYT2OOubvaLpRp0r_Q?e=PZHETL)

**Foto de evidencia de la entrevista:**  
![Entrevista Rodrigo](https://github.com/user-attachments/assets/2e9e4a28-1798-496c-9aef-53e5e55f5f1b)


---

### Resumen de la Entrevista - Diego Ramos
- **Entrevistado:** Diego Ramos
- **Edad:** 24 años
- **Ocupación:** Freelancer Programador Web
- **Ubicación:** La Molina, Lima, Perú

**Resumen de la entrevista:**

Diego trabaja como programador web freelancer y enfrenta desafíos similares a los de Rodrigo en términos de gestión del tiempo. Sin embargo, sus dificultades están más centradas en la alta demanda de los clientes y la carga de trabajo que implica cumplir con plazos ajustados, lo que a veces lo obliga a pedir extensiones. Su mayor preocupación es la calidad del producto final y el tiempo que debe dedicar a cada proyecto, ya que cualquier error puede retrasar aún más la entrega.

Para gestionar sus tareas, Diego utiliza el calendario de iPhone, aunque menciona que la herramienta es limitada cuando tiene horarios complejos, ya que no permite personalizar las tareas o agregar recordatorios más específicos. A pesar de esto, valora tener control sobre su horario, ya que un buen manejo del tiempo es crucial en su trabajo como programador, donde los detalles importan mucho.

En cuanto a los pagos, Diego usa paypal para recibir sus pagos, y le gustaría contar con una herramienta que le ayude a mejorar la comunicación con sus clientes, recibir actualizaciones automáticas sobre el avance de los proyectos y optimizar la organización de su agenda. Además, mencionó que una plataforma que también le permita tener un análisis del rendimiento sería útil para mejorar su productividad y crecimiento profesional.

En resumen, Diego busca una herramienta integral que le permita gestionar su tiempo, recibir retroalimentación de los clientes en tiempo real y organizar mejor su carga de trabajo. Le interesa especialmente una plataforma que le ayude a optimizar la comunicación, realizar un seguimiento detallado de su trabajo y, además, proporcionarle un análisis de su rendimiento para crecer profesionalmente.

**Link de la entrevista:** [Enlace Entrevista Diego](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211g499_upc_edu_pe/EXn_e16u88tFlf8dm4JUEPQBFJEgLYT2OOubvaLpRp0r_Q?e=PZHETL)

**Foto de evidencia de la entrevista:**  
![Entrevista Diego](https://github.com/user-attachments/assets/89bb042a-4f46-46fb-82b3-1b6bfde312f8)

---



## **Análisis de entrevistas**

### **Objetivas**

| **Características**                            | **Gerente (Ingrid y Anderson)**                                              | **Freelancer (Letizia, Rodrigo, y Diego)**                                       |
|-----------------------------------------------|------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| **Interés en gestionar tiempos de trabajo**   | 80% de los gerentes mencionan la importancia de gestionar tiempos y productividad de su equipo. Ingrid destaca la optimización del tiempo de su equipo. Anderson también resalta la importancia de evitar supervisión manual de cada detalle. | 100% busca optimizar sus tiempos de trabajo y obtener pagos por horas trabajadas. Letizia y Rodrigo valoran la gestión del tiempo en su trabajo freelance debido a los plazos establecidos. |
| **Uso de plataformas tecnológicas para gestión** | 100% de los gerentes usan herramientas para gestionar el personal, aunque Ingrid menciona que busca soluciones más eficientes. Anderson usa aplicaciones internas, pero su enfoque sigue siendo manual en muchos casos. | 90% utiliza plataformas tecnológicas para gestionar proyectos y tareas. Letizia usa ClickUp, aunque la encuentra compleja para nuevos usuarios. Rodrigo usa Excel, pero le gustaría tener mejores herramientas para controlar el tiempo. Diego no mencionó específicamente ninguna plataforma tecnológica, pero indicó que le gustaría tener una herramienta de control de tiempo. |
| **Necesidad de interacción con otros profesionales** | 100% necesita interactuar con su equipo y otros profesionales. Ingrid subraya la importancia de la comunicación para gestionar tareas. Anderson también menciona la necesidad de interacciones continuas para mejorar el ambiente laboral. | 100% necesita interactuar con otros freelancers y clientes. Letizia usa WhatsApp para la comunicación directa con sus clientes, y Rodrigo subraya la importancia de una buena relación con ellos. |
| **Búsqueda de un sistema eficiente para pagos** | 90% busca un sistema que le permita controlar pagos y facturación de su equipo. Ingrid enfatiza la necesidad de un control más eficiente, mientras que Anderson menciona que los pagos y la gestión de tareas deben estar conectados de forma más clara. | 66% prefiere recibir pagos rápidos y sin complicaciones. Letizia utiliza billeteras digitales como YAPE y BCP, y Rodrigo usa PayPal como sistema de pago. Diego no menciona explícitamente el sistema de pago, pero resalta la importancia de optimizar el flujo de trabajo. |
| **Interés en bienestar y salud emocional** | 90% se preocupa por el bienestar emocional de su equipo. Ingrid implementa dinámicas de bienestar con psicólogos, mientras que Anderson se preocupa por el estado emocional de su equipo, aunque de forma más personalizada. | 40% menciona explícitamente bienestar emocional, aunque todos valoran un entorno saludable. Letizia, Rodrigo, y Diego mencionan la importancia de un ambiente sano, pero no enfocan específicamente en el bienestar emocional. |

---

### **Subjetivas**

| **Características**                            | **Gerente**                                              | **Freelancer**                                       |
|-----------------------------------------------|------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| **Interés en obtener ganancias**              | 100% considera que es vital que su equipo logre maximizar la productividad y las ganancias. Ingrid enfatiza la rentabilidad y eficiencia, mientras que Anderson también busca optimizar la productividad de su equipo. | 100% desea obtener una ganancia adecuada por su trabajo freelance. Letizia, Rodrigo, y Diego mencionan que la motivación detrás de su trabajo es obtener ganancias apropiadas por sus servicios. |
| **Uso de sistemas de pago transparentes**     | 100% está dispuesta a utilizar plataformas que gestionen pagos de manera eficiente y clara. Ingrid y Anderson coinciden en que un sistema transparente es crucial para la eficiencia laboral. | 66% busca plataformas que ofrezcan pagos seguros y rápidos. Letizia y Rodrigo mencionan que el uso de billeteras digitales como YAPE y PayPal es crucial para la rapidez y seguridad de los pagos. |
| **Interés en planes de suscripción**          | 70% preferiría tener acceso a opciones de suscripción o pagos periódicos para sus empleados. Ingrid está abierta a explorar sistemas que optimicen la gestión de su personal y sus gastos. Anderson también ve valor en suscripciones como parte de su gestión. | 90% cree que los planes de suscripción son una buena opción para generar ingresos adicionales. Letizia y Rodrigo están interesados en plataformas que ofrezcan suscripciones o pagos mensuales, ya que les facilitaría los pagos recurrentes. |
| **Búsqueda de información sobre su área**     | 90% busca información sobre tendencias en gestión de equipos y productividad. Ingrid se mantiene actualizada sobre mejores prácticas en la gestión de su equipo. Anderson también valora la actualización constante sobre gestión y productividad. | 66% busca contenido sobre su área específica (ilustración, marketing, desarrollo web). Letizia y Rodrigo investigan constantemente sobre nuevas tendencias y mejores prácticas en su campo de freelance. |
| **Preferencia por una interfaz intuitiva**    | 90% le gustaría tener una plataforma fácil de usar para gestionar tiempos y tareas del equipo. Ingrid enfatiza la simplicidad en la plataforma para mejorar la eficiencia en la gestión de su equipo. Anderson también valora herramientas fáciles de usar. | 90% también valora plataformas sencillas y amigables para gestionar su trabajo. Letizia subraya que una herramienta sencilla y accesible es clave para su eficiencia, al igual que Rodrigo, quien prefiere plataformas claras y fáciles de entender. |

---



# 2.3. Needfinding

## 2.3.1. User Personas 

### Segmento 1: Gerente
![User Persona Gerente](https://github.com/user-attachments/assets/886b8660-4432-48d7-9b8f-e2abbea3484b)


### Segmento 2: Freelancer  
![User Persona Freelancer](https://github.com/user-attachments/assets/e3c71aec-4306-43db-ba76-27fe83f60070)


## 2.3.2. User Task Matrix  
A continuación se pueden apreciar los User Task Matrix de los segmentos objetivos.

### User Persona: Freelancer  
**Segmento Objetivo**: Freelancer entre 18 años a más  

| **Task**                         | **Frequency** | **Importance** |
|----------------------------------|---------------|----------------|
| Registrar nuevos clientes        | High          | High           |
| Gestionar proyectos y asignar tareas | High          | High           |
| Controlar tiempo de trabajo      | High          | High           |
| Recibir retroalimentación de clientes | Medium        | High           |
| Buscar y establecer nuevos contratos | Medium        | High           |


### User Persona: Gerente  
**Segmento Objetivo**: Gerentes entre 30 años a más  

| **Task**                         | **Frequency** | **Importance** |
|----------------------------------|---------------|----------------|
| Asignar tareas a empleados       | High          | High           |
| Supervisar el progreso del equipo| High          | High           |
| Gestionar horarios de los empleados | High          | High           |
| Ver la productividad en tiempo real | Medium        | High           |
| Realizar pagos a empleados       | Medium        | High           |

# 2.3.3. User Journey Mapping  
A continuación estarán los User Journey Mapping de los segmentos objetivos.

### Segmento gerente:
![Journey Ingrid](https://github.com/user-attachments/assets/8c2d9ce2-2aeb-452d-b226-868621609b97)



### Segmento freelancer:
![Journey Letizia](https://github.com/user-attachments/assets/743676ba-3202-43b4-9b5b-6ad59226ae27)




# 2.3.4. Empathy Mapping  
A continuación estarán los Empathy Mapping de los segmentos objetivos.

### Segmento gerente:
![Empathy Mapping Gerente](https://github.com/user-attachments/assets/45a39392-10f3-435c-809f-8cba68caafb8)


### Segmento freelancer:
![Empathy Mapping](https://github.com/user-attachments/assets/3b1eb95b-cdfa-4f3c-a61c-177ecfabe8bb)



# 2.3.5. As-is Scenario Mapping  
A continuación estarán los As-is Scenario Mapping de los segmentos objetivos.

### Segmento gerente:
![As-Is Gerente](https://github.com/user-attachments/assets/59ed1115-afe6-4d92-883f-15d11e7fa2a1)


### Segmento freelancer:
![As-Is Freelancer](https://github.com/user-attachments/assets/47603c12-14cd-4d50-9e69-3aca1bc003cd)



# 2.4. Ubiquitous Language

### Flow Sense Platform (Plataforma Flow Sense):  
Una plataforma tecnológica diseñada para la gestión del tiempo, la productividad y la eficiencia laboral, destinada a freelancers y empresas. Ofrece herramientas personalizadas como la automatización de tareas, el seguimiento de tiempo y la integración con asistentes de voz.

### Freelancer (Freelancer):  
Profesional independiente que gestiona proyectos y tareas de manera autónoma, utilizando plataformas como Flow Sense para optimizar su tiempo y productividad.

### Team Management (Gestión de Equipo):  
Proceso mediante el cual los gerentes o líderes de equipo asignan tareas, supervisan el progreso y gestionan el tiempo de sus empleados o colaboradores mediante plataformas digitales.

### Time Tracking (Seguimiento de Tiempo):  
Función que permite a los usuarios registrar automáticamente el tiempo invertido en tareas y proyectos, para mejorar la gestión del tiempo y aumentar la productividad.

### Task Assignment (Asignación de Tareas):  
El proceso de distribuir tareas específicas entre los miembros de un equipo para asegurar la organización y cumplimiento de plazos.

### Real-Time Tracking (Seguimiento en Tiempo Real):  
Herramienta que permite a los gerentes o freelancers monitorear la ubicación y el progreso de los proyectos en tiempo real, mejorando la visibilidad y control.

### Workload Management (Gestión de Carga de Trabajo):  
El proceso de equilibrar y distribuir las tareas entre el equipo de trabajo de manera eficiente para evitar la sobrecarga y asegurar la productividad.

### Client Communication (Comunicación con el Cliente):  
El proceso de interactuar con clientes para asegurar que sus necesidades sean atendidas, sus expectativas gestionadas y los proyectos completados a tiempo.

### Payment Integration (Integración de Pagos):  
Herramienta que permite a los freelancers y gerentes recibir pagos mediante plataformas de pago digital como PayPal o billeteras electrónicas, facilitando la gestión financiera.

### Project Management (Gestión de Proyectos):  
La organización y planificación de tareas, fechas de entrega y recursos necesarios para completar un proyecto, asegurando que se cumplan los objetivos en los plazos establecidos.

### Performance Monitoring (Monitoreo de Desempeño):  
El proceso mediante el cual se evalúa el progreso y rendimiento de los empleados o freelancers para mejorar la eficiencia y productividad a través de métricas y datos en tiempo real.

### Time Optimization (Optimización del Tiempo):  
El uso de herramientas y estrategias para mejorar la eficiencia en el uso del tiempo, permitiendo a los freelancers y gerentes realizar más tareas en menos tiempo.

### Automatic Billing (Facturación Automática):  
Sistema que genera y envía automáticamente las facturas a los clientes después de completar un trabajo o proyecto, simplificando la gestión financiera.

### Team Collaboration (Colaboración en Equipo):  
La interacción y cooperación entre miembros del equipo, facilitada por plataformas que permiten compartir tareas, avances y feedback de manera eficiente.

### Productivity Analytics (Análisis de Productividad):  
Herramientas que permiten analizar el rendimiento laboral de los empleados o freelancers, proporcionando datos sobre eficiencia, tareas completadas y áreas de mejora.

### Client Feedback (Retroalimentación del Cliente):  
Comentarios proporcionados por los clientes sobre el trabajo realizado, que ayudan a los freelancers y gerentes a mejorar la calidad del servicio y ajustar sus estrategias de trabajo.

### Team Performance (Desempeño del Equipo):  
Evaluación de la eficiencia y efectividad de un equipo en el cumplimiento de sus metas y tareas, basado en indicadores como la productividad, cumplimiento de plazos y calidad del trabajo.

### User Retention (Retención de Usuarios):  
Estrategias y herramientas utilizadas para mantener a los usuarios activos en la plataforma mediante la satisfacción continua de sus necesidades y la mejora constante de la experiencia del usuario.

### Time Efficiency (Eficiencia del Tiempo):  
El grado en que los usuarios pueden completar tareas y proyectos en el menor tiempo posible sin comprometer la calidad, optimizado mediante el uso de plataformas de gestión de tiempo.

### Team Collaboration Tools (Herramientas de Colaboración de Equipo):  
Herramientas digitales que permiten a los miembros de un equipo colaborar de manera efectiva, compartiendo tareas, actualizaciones y documentos, todo en tiempo real.

