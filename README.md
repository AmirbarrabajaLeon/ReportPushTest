# **Capítulo III: Requirements Specification**


### 3.1. To-Be Scenario Mapping  
Con el fin de crear el To-be Scenario Mapping, el equipo definió cómo se optimizaría el flujo de trabajo una vez que nuestra solución haya sido implementada para cada segmento objetivo. El propósito de este artefacto es analizar y mejorar los aspectos negativos identificados en el As-is Scenario.

### Segmento gerente:
![Imagen del segmento gerente](ruta/a/la/imagen-del-segmento-gerente)

### Segmento freelancer:
![Imagen del segmento freelancer](ruta/a/la/imagen-del-segmento-freelancer)


## 3.2. User Stories

# User Stories

## Epic 1

### E1-US01 - Registro de cuenta
**Descripción**: Como freelancer o gerente, quiero registrarme en la plataforma para gestionar mis proyectos.  
**Criterios de Aceptación**:  
**Escenario 1: Registro con Email**  
Dado que el usuario está en la página de registro,  
Cuando ingrese sus datos correctamente,  
Entonces la cuenta será creada.  
**Escenario 2: Registro con Google**  
Dado que el usuario está en la página de registro,  
Cuando elija registrarse con Google,  
Entonces se creará la cuenta vinculada a Google.  

---

### E1-US02 - Inicio de sesión
**Descripción**: Como freelancer, quiero iniciar sesión en la plataforma para gestionar mis proyectos y clientes.  
**Criterios de Aceptación**:  
**Escenario 1: Inicio de sesión correcto**  
Dado que el usuario tiene una cuenta,  
Cuando ingrese sus datos correctamente,  
Entonces iniciará sesión en la plataforma.  
**Escenario 2: Inicio de sesión incorrecto**  
Dado que el usuario tiene una cuenta,  
Cuando ingrese datos incorrectos,  
Entonces recibirá un mensaje de error.  

---

### E1-US03 - Gestión de proyectos
**Descripción**: Como freelancer, quiero gestionar mis proyectos para cumplir con los plazos establecidos.  
**Criterios de Aceptación**:  
**Escenario 1: Gestión de proyectos**  
Dado que el freelancer está en su panel,  
Cuando agregue un nuevo proyecto,  
Entonces podrá asignar fechas y plazos.  
**Escenario 2: Recordatorio de plazos**  
Dado que el freelancer tiene proyectos,  
Cuando se acerque el plazo de entrega,  
Entonces recibirá un recordatorio.  

---

### E1-US04 - Notificaciones de cliente
**Descripción**: Como freelancer, quiero recibir notificaciones cuando un cliente haga comentarios en un proyecto para poder responder rápidamente.  
**Criterios de Aceptación**:  
**Escenario 1: Notificación de comentario**  
Dado que el usuario tiene proyectos activos,  
Cuando un cliente deje un comentario,  
Entonces recibirá una notificación.  
**Escenario 2: Notificación de retroalimentación**  
Dado que el freelancer tiene proyectos,  
Cuando un cliente deje retroalimentación,  
Entonces será notificado.  

---

### E1-US05 - Control de pagos
**Descripción**: Como freelancer, quiero gestionar los pagos para que se realicen sin problemas.  
**Criterios de Aceptación**:  
**Escenario 1: Generación de factura**  
Dado que el freelancer ha completado un proyecto,  
Cuando genere la factura,  
Entonces la plataforma calculará automáticamente el monto a cobrar.  
**Escenario 2: Envío automático de factura**  
Dado que la factura se generó,  
Cuando se finalice,  
Entonces se enviará automáticamente al cliente.  

---

## Epic 2

### E2-US06 - Asignación
