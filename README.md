# PilarBus
Aplicación móvil y plataforma web para consultar recorridos de colectivos en tiempo real en Pilar.
## 1. Justificación metodológica
Para desarrollar el proyecto PilarBus se selecciona la metodología ágil Scrum, debido a que se trata de un proyecto con requisitos cambiantes y un alto nivel de incertidumbre.

La aplicación deberá permitir a los ciudadanos consultar recorridos de colectivos en tiempo real. Sin embargo, durante su desarrollo pueden surgir nuevas necesidades a partir de las opiniones de los usuarios.

Scrum permite organizar el trabajo en períodos cortos llamados Sprints, que generalmente duran entre dos y cuatro semanas.

Al finalizar cada Sprint, el equipo presenta una versión funcional del producto, recibe comentarios y realiza las mejoras necesarias.

Ventajas de utilizar Scrum:
- Permite adaptarse rápidamente a los cambios.
- Facilita la comunicación entre los integrantes.
- Permite detectar errores durante el desarrollo.
- Entrega resultados funcionales en períodos cortos.
- Incorpora las opiniones de los usuarios.
- Mejora la organización y distribución de tareas.
¿Por qué no utilizar Cascada?

El modelo Cascada requiere definir y aprobar prácticamente todos los requisitos antes de comenzar el desarrollo. Esto sería una desventaja para PilarBus porque sus funcionalidades pueden cambiar semanalmente.

Por lo tanto, Scrum es más adecuado porque permite desarrollar, probar y mejorar la aplicación continuamente.
## 2. Estimación de Esfuerzo y Costos (Ágil)

Para estimar el esfuerzo necesario para desarrollar las principales funcionalidades del proyecto **PilarBus**, se utilizará la técnica de **Story Points (Puntos de Historia)** junto con la dinámica de **Planning Poker**.

Esta técnica permite calcular la complejidad, el esfuerzo y la dificultad de cada funcionalidad, sin depender exclusivamente de las horas de trabajo.

Se utilizará la escala de Fibonacci (1, 2, 3, 5, 8, 13 y 21), donde los números más altos representan funcionalidades que requieren mayor esfuerzo y complejidad.

### 2.1. Estimación de las funcionalidades principales

| Funcionalidad | Story Points |
|---|---:|
| Registro e inicio de sesión de usuarios | 5 |
| Consulta de recorridos y horarios de colectivos | 8 |
| Visualización de colectivos en tiempo real | 13 |
| Notificaciones sobre desvíos y demoras | 8 |
| Integración con información de tarjetas SUBE | 13 |
| Sistema de reclamos y sugerencias | 5 |
| Panel de administración de recorridos | 8 |
| Actualización y gestión de información del transporte | 8 |
| **Total** | **68 SP** |

### 2.2. Aplicación de Planning Poker

Para realizar la estimación se propone utilizar Planning Poker, una técnica en la que se presentan las funcionalidades del sistema y se asignan puntos según su complejidad.

En este caso, al tratarse de un trabajo individual, se utiliza la escala de Fibonacci como referencia para realizar una estimación razonada de cada funcionalidad.

Por ejemplo:

- El registro de usuarios recibe 5 puntos porque requiere validaciones y administración de cuentas.
- La consulta de recorridos recibe 8 puntos porque necesita organizar y mostrar información del transporte.
- La visualización de colectivos en tiempo real recibe 13 puntos porque requiere obtener, procesar y actualizar información constantemente.
- La integración con SUBE recibe 13 puntos debido a su mayor complejidad de integración.

### 2.3. Planificación del esfuerzo

El proyecto tiene un esfuerzo estimado de **68 Story Points**.

Se establece una velocidad de trabajo estimada de 17 Story Points por Sprint, considerando Sprints de dos semanas.

| Sprint | Esfuerzo estimado | Duración |
|---|---:|---|
| Sprint 1 | 17 SP | 2 semanas |
| Sprint 2 | 17 SP | 2 semanas |
| Sprint 3 | 17 SP | 2 semanas |
| Sprint 4 | 17 SP | 2 semanas |
| **Total** | **68 SP** | **8 semanas** |

De esta manera, se estima que el proyecto podría completarse en aproximadamente 8 semanas, distribuidas en cuatro Sprints.

Esta planificación es orientativa y puede modificarse según los resultados de cada Sprint y las prioridades del proyecto.

### 2.4. Estimación de costos

Para calcular los costos se consideran los siguientes aspectos:

- Análisis y planificación de los requerimientos.
- Diseño de la aplicación móvil y web.
- Desarrollo de las funcionalidades principales.
- Pruebas y corrección de errores.
- Integración de los servicios de información.
- Mantenimiento y posibles modificaciones.

Se establece un presupuesto académico estimado de **$14.000.000 de pesos argentinos** para el desarrollo del proyecto.

Este monto es una estimación de referencia y no representa un presupuesto comercial definitivo. Los costos reales dependerán de los recursos humanos, tecnológicos y económicos necesarios.

### 2.5. Adaptación a los cambios de requisitos

La estimación ágil permite adaptarse mejor a los cambios porque no establece un plan completamente rígido desde el comienzo del proyecto.

En PilarBus pueden surgir nuevos requisitos, como modificaciones en los recorridos, cambios en los horarios, nuevas alertas o mejoras solicitadas por los usuarios.

Cuando esto sucede, el Product Backlog se actualiza, se revisan las prioridades y se vuelven a estimar las funcionalidades afectadas.

Esto permite:

- Incorporar nuevas funcionalidades según las necesidades de los usuarios.
- Modificar las prioridades sin tener que reorganizar todo el proyecto.
- Ajustar los tiempos y esfuerzos de cada Sprint.
- Detectar dificultades antes de que afecten a todo el desarrollo.
- Mejorar continuamente el producto mediante la retroalimentación.
##  3 Gestión visual: CLICKUP
Se utilizará clickup como herramienta de gestión visual para organizar las tareas del proyecto.

El tablero tendrá cuatro columnas principales:
- To Do: tareas pendientes.
- In Progress: tareas que se están realizando.
- Under Review: Revicion de tareas realizadas.
- Done: tareas terminadas.
Se establecerá un límite WIP (Work In Progress) de tres tareas en la columna In Progress.

Esto significa que solamente podrán existir tres tareas en ejecución al mismo tiempo. De esta manera se evita la sobrecarga de trabajo, se mejora la concentración y se reducen los cuellos de botella.
### tablero kanban https://app.clickup.com/90171190153/v/li/901718187602
Las tarjetas incluyen las etiquetas Desarrollador, Backend, Diseñador y Tester, según corresponda.
## 4.Control de Versiones y CI/CD (GitHub)

Para el proyecto **PilarBus** se utiliza GitHub como herramienta para almacenar y organizar la documentación del proyecto.

**Repositorio:** https://github.com/williampuma639-lab/PilarBus

### 4.1. Git y GitHub

Git es un sistema de control de versiones que permite registrar los cambios realizados en los archivos. GitHub permite almacenar esos archivos en línea y mantener un historial del proyecto.

### 4.2. Ramas (Branches)

Las ramas permiten trabajar sobre diferentes modificaciones sin afectar la versión principal.

Se propone utilizar:
- **main:** versión principal y estable.
- **feature:** ramas para incorporar mejoras y modificaciones.

### 4.3. Commits

Los commits son registros de los cambios realizados en el repositorio. Permiten conocer las modificaciones y consultar versiones anteriores.

Ejemplos: creación del repositorio, actualización del README y modificación de la documentación.

### 4.4. Pull Requests

Son solicitudes que permiten revisar los cambios realizados en una rama antes de incorporarlos a la rama principal. En este proyecto, el responsable puede revisar sus propios cambios al tratarse de un trabajo individual.

### 4.5. CI/CD

CI/CD significa Integración Continua y Entrega Continua. Permite automatizar verificaciones y facilitar la publicación de nuevas versiones.

En PilarBus se propone utilizar GitHub Actions para realizar controles automáticos y, en una futura etapa de desarrollo, facilitar la publicación de la aplicación.
