# Capítulo V: Introducción

## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
El entorno de desarrollo fue configurado utilizando herramientas ampliamente adoptadas en proyectos open source.

### Herramientas por tipo de actividad

| Actividad                         | Herramienta(s) utilizada(s)                    | Tipo     | Enlace de referencia                                                                 |
|-----------------------------------|------------------------------------------------|----------|----------------------------------------------------------------------------------------|
| Project Management                | Trello, GitHub Projects                        | SaaS     | [Trello](https://trello.com) / [GitHub Projects](https://github.com)                 |
| Requirements Management           | Google Docs, Google Sheets                     | SaaS     | [Google Docs](https://docs.google.com)                                               |
| Product UX/UI Design              | Figma                                          | SaaS     | [Figma](https://figma.com)                                                           |
| Software Development              | WebStorm, Visual Studio Code, Node.js, Git, Angular    | Local    | [WebStorm](https://www.jetbrains.com/webstorm/) / [VS Code](https://code.visualstudio.com) / [Node.js](https://nodejs.org) / [Git](https://git-scm.com) / [Angular](https://angular.dev)|
| Software Deployment               | Vercel, Netlify, Railway, Render               | SaaS     | [Vercel](https://vercel.com) / [Netlify](https://www.netlify.com) / [Railway](https://railway.app) |
| Software Documentation            | Google Docs, Markdown, Swagger, Structurizer   | SaaS/Local| [Google Docs](https://docs.google.com) / [Swagger](https://swagger.io)               |

### 5.1.2. Source Code Management.
Se utilizó Git como sistema de control de versiones y GitHub como plataforma de hospedaje. El proyecto fue dividido en múltiples repositorios:

Landing Page: https://github.com/flow-sense/landing (link de ejemplo)

Web Services: https://github.com/flow-sense/api (link de ejemplo)

Frontend Web App: https://github.com/flow-sense/frontend (link de ejemplo)

Se adoptó el workflow GitFlow, basado en el modelo de Vincent Driessen (“A successful Git branching model”), para organizar las ramas de trabajo. Este flujo permite una separación clara entre las versiones estables, los desarrollos activos y las correcciones urgentes. Las ramas empleadas son:

- main: contiene la versión estable y liberada del producto. Cada merge a esta rama representa una versión deployada.

- develop: rama principal de desarrollo donde se integran los feature branches.

- feature/<nombre>: para cada nueva funcionalidad, se crea una rama individual. Ejemplo: feature/login-auth, feature/task-tracking.

- release/<version>: rama temporal que permite realizar pruebas y ajustes antes de pasar a producción. Ejemplo: release/v1.1.0.

- hotfix/<descripcion>: ramas para corregir errores críticos encontrados en producción. Ejemplo: hotfix/fix-null-user.

Cada release se nombra siguiendo Semantic Versioning 2.0.0, utilizando el formato MAJOR.MINOR.PATCH:

- Cambios incompatibles: 2.0.0

- Nuevas funcionalidades compatibles: 2.1.0

- Correcciones de bugs: 2.1.1

Se usaron etiquetas (tags) en Git para marcar los releases formales: v1.0.0, v1.1.0-beta, etc.

Además, para mantener un historial claro y legible en el repositorio, se aplicó la convención [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/), con el siguiente formato:

| **<'tipo'>(alcance): descripcion breve** |
|------------------------------------------|

Donde el <"tipo"> puede ser: feat, fix, docs, style, refactor, test, chore, entre otros.

**Ejemplos de commits:**

- feat(auth): implement Google login integration

- fix(api): prevent crash on empty request body

- refactor(ui): simplify dashboard component hierarchy

### 5.1.3. Source Code Style Guide & Conventions

Para mantener la consistencia del código fuente se adoptaron las siguientes guías y convenciones:

- **HTML/CSS**: [W3 HTML Style Guide](https://www.w3schools.com/html/html5_syntax.asp), [Google HTML/CSS Guide](https://google.github.io/styleguide/htmlcssguide.html)
- **JavaScript/TypeScript**: [Google TypeScript Style Guide](https://google.github.io/styleguide/tsguide.html), ESLint + Prettier
- **Java**: [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html), aplicado si se emplea Spring Boot
- **Especificaciones BDD (si aplica)**: [Gherkin Syntax](https://cucumber.io/docs/gherkin/)

Además, se adoptaron las siguientes prácticas:
- Uso del idioma inglés para nombrar funciones, variables, clases y archivos.
- Aplicación de principios SOLID y clean code.
- Separación modular del código, fomentando la reutilización de componentes y funciones puras.
 
### 5.1.4. Software Deployment Configuration

El proceso de despliegue fue automatizado usando plataformas como **Vercel**, **Netlify** o **Railway**. El frontend y la landing page fueron desplegados directamente desde los repositorios de GitHub mediante integración continua (CI). Para el backend se configuró un entorno en Railway o Render.

#### Pasos generales de despliegue:

1. Un push a las ramas `main` o `release/*` activa un proceso de despliegue automático.
2. Se incluyeron archivos de configuración según la plataforma:
   - `vercel.json` para Vercel
   - `netlify.toml` para Netlify
   - `Dockerfile` en caso de uso de contenedores
3. Las variables de entorno fueron configuradas directamente en la plataforma correspondiente (por ejemplo, claves de API, bases de datos, credenciales).
4. Las APIs fueron desplegadas y expuestas mediante HTTPS, y documentadas utilizando herramientas como **Swagger** o **Postman**.

## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

Durante esta etapa se priorizaron funcionalidades esenciales que permiten cubrir el flujo base tanto para usuarios del segmento freelancer como para visitantes de la Landing Page. El sprint tuvo una duración estimada de una semana y se trabajó bajo un enfoque ágil tipo Scrum.

El equipo dedicó especial atención a la identificación del Sprint Goal, siguiendo el enfoque propuesto por Scrum.org, basado en outcome, impact, customer y event. El objetivo se redactó con un enfoque en negocio y usuario, en formato SMART:

Sprint 1 Goal:

`Our focus is on delivering a functional and user-friendly landing page. We believe it delivers immediate understanding and engagement to new users. This will be confirmed when visitors can easily navigate, explore plans, read testimonials, and switch between freelancer and company information.`

Los objetivos principales del Sprint 1 fueron:

Implementar navegación fluida y accesible entre secciones de la Landing Page.

Desarrollar la función de alternar información entre empresas y freelancers.

Desplegar la sección de testimonios y tecnologías utilizadas.

Optimizar el diseño y estructura de la página.

Estas decisiones se basaron en las siguientes User Stories priorizadas:

E8-US22 Navegación fluida entre secciones

E8-US23 Alternar entre información para clientes

E8-US24 Comparativa de planes

E8-US25 Mostrar tecnologías utilizadas

E8-US26 Ver testimonios de otros usuarios

E8-US27 Cambiar información según segmento

#### 5.2.1.1. Sprint Planning 1.

### Sprint Planning Meeting Summary

| Elemento                             | Detalle                                                                                                                 |
| ------------------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| **Sprint #**                         | Sprint 1                                                                                                                |
| **Sprint Planning Background**       | Inicio de desarrollo de la Landing Page y funcionalidades clave                                                         |
| **Date**                             | 2025-04-18                                                                                                              |
| **Time**                             | 05:00 PM                                                                                                                |
| **Location**                         | Reunión virtual vía Google Meet                                                                                         |
| **Prepared By**                      | Amir Castro                                                                                                             |
| **Attendees**                        | Pietro Osores, Joaquín, Stephano, Carlos                                                                                |
| **Sprint 0 – Review Summary**        | Se finalizó la planificación general del proyecto y diseño UI inicial.                                                  |
| **Sprint 0 – Retrospective Summary** | Se identificó la necesidad de roles claros y mayor documentación interna.                                               |
| **Sprint 1 – Goal**                  | Tener un MVP funcional de la Landing Page que permita navegación, cambio de información y visualización de testimonios. |
| **Sprint 1 – Velocity**              | 20 Story Points (estimado)                                                                                              |
| **Sprint 1 – Sum of Story Points**   | 20 Story Points         

#### 5.2.1.2. Aspect Leaders and Collaborators.

### Leadership and Collaboration Matrix (LACX)

| Team Member          | GitHub Username | Gestión de Proyectos | Landing Page | Despliegue | IA/Data Analysis |
| -------------------- | --------------- | -------------------- | ------------ | ---------- | ---------------- |
| Pietro \[Apellido]   | \[A COMPLETAR]  | L                    | C            | C          | C                |
| Amir \[Apellido]     | \[A COMPLETAR]  | C                    | C            | L          | L                |
| Carlos \[Apellido]   | \[A COMPLETAR]  | C                    | L            | C          | C                |
| Stephano \[Apellido] | \[A COMPLETAR]  | C                    | L            | C          | C                |
| Joaquín \[Apellido]  | \[A COMPLETAR]  | L                    | C            | C          | L                |

> **L**: Leader (responsable del aspecto)  
> **C**: Collaborator (colaborador activo)

#### 5.2.1.3. Sprint Backlog 1.

Durante el Sprint 1, el objetivo principal fue construir una base funcional mínima para el sistema, abordando funcionalidades clave como registro, inicio de sesión, gestión de proyectos y asignación de tareas. Se trabajó con una herramienta de control de tareas basada en tableros tipo Kanban (por ejemplo Trello), en donde cada User Story se descompuso en uno o más work-items o tareas técnicas.

### Sprint Backlog - Sprint 1
En esta sección se muestran los tasks que se realizaron en el presente sprint y se adjunta una captura en Trello y el link al tablero.

Link de Trello: [https://trello.com/invite/b/6725085eef376b7a366078a5/ATTI35c5a7b65f9c3eade04684aff95452e5810D9665/backlog]

![image](https://github.com/user-attachments/assets/0296d3ac-00d0-46cd-98eb-961a2b17e848)

| User Story ID | User Story Title                   | Task ID | Work-Item / Task                        | Description                                                    | Estimation (hrs) | Assigned To | Status    |
| ------------- | ---------------------------------- | ------- | --------------------------------------- | -------------------------------------------------------------- | ---------------- | ----------- | --------- |
| E8-US22       | Navegación fluida entre secciones  | TSK-01  | Implementar navegación con anclajes     | Menú que permite navegar entre secciones                       | 4                | Carlos      | Done |
| E8-US23       | Alternar información para clientes | TSK-02  | Configurar botón de alternar            | Cambia contenido entre empresas y freelancers                  | 3                | Amir        | Done    |
| E8-US24       | Comparativa de planes              | TSK-03  | Crear tabla comparativa de planes       | Tabla que muestra diferencias entre planes                     | 3                | Carlos      | Done      |
| E8-US25       | Mostrar tecnologías utilizadas     | TSK-04  | Diseño de sección de tecnologías        | Íconos y descripciones de tecnologías utilizadas               | 2                | Stephano    | Done      |
| E8-US26       | Ver testimonios de otros usuarios  | TSK-05  | Maquetar sección de testimonios         | Testimonios dinámicos y alternables                            | 3                | Joaquín     | Done |
| E8-US27       | Cambiar información según segmento | TSK-06  | Configurar CTA dinámico                 | Botón que cambia entre información para empresas y freelancers | 3                | Pietro        | Done     |

#### 5.2.1.4. Development Evidence for Sprint Review.
Después de finalizar el Sprint 1, hemos logrado implementar algunas de las secciones de nuestra Landing Page, aunque con algunos desperfectos en cuanto a diseño. A continuación, te invitamos a explorar nuestros avances a través de imágenes que muestran el resultado obtenido.

*Seccion de navegacion* : Nos ayudara a redirigirnos a secciones especificas de la lading page y Banner que contendra un boton (Call to Action) que te llevara a registrarte a nuestra aplicación.

![image](https://github.com/user-attachments/assets/6b423628-1a00-458c-99d8-433be0d35a5f)

*Funcionality*: Seccion donde los visitantes de la lading page podrán ver como es que funciona nuestra aplicacion y que les ofrece.

![image](https://github.com/user-attachments/assets/8937f486-207b-4790-b23f-d5b9a0ee6e64)

*Ventajas*: sección de las ventajas para nuestro usuarios

![image](https://github.com/user-attachments/assets/d40476c8-a3bf-4f53-aa01-fcb44e904004)


*Seccion de testimonios*: sección de testimonios

![image](https://github.com/user-attachments/assets/c37b9324-6e02-42fd-acb6-be57e824349f)


*footer*: contenido extra, como telefono,correo y redes para que puedan comunicarse con la empresa devinsons.

![image](https://github.com/user-attachments/assets/8a44b971-2a40-4821-9e2a-190769713a50)


#### 5.2.1.5. Execution Evidence for Sprint Review.

Durante este sprint 1 el equipo se enfocó en el desarrollo de la landing page por lo cual no se requirio pruebas de testing.

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

En el primer sprint, hemos realizado el diseño, la programación y el despligue de la Landing Page que presentará nuesta apliación web "FlowSenses"

<table> 
  <tr>
    <td> <strong>End Point </strong></td>
    <td align="center"> <strong>Funciones</strong> </td>
  </tr>

  <tr>
    <td> https://1asi0729-2510-4317-g5-flow-senses.github.io/LandingPage/ </td>
    <td> Desplegar Landing Page de FlowSenses</td>
  </tr>
</table>

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.


#### 5.2.1.8. Team Collaboration Insights during Sprint.

![image](https://github.com/user-attachments/assets/d22050d7-56cb-4b38-a9e7-2e27a832051d)

![image](https://github.com/user-attachments/assets/cdee531a-e551-4689-a800-f5b360fcf5e3)


