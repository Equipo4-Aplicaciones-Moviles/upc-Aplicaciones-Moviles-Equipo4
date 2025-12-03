<div align="center">
  <img src="assets/chapter01/upc-logov.png" alt="UPC Logo" height="200">
  <h1>Universidad Peruana de Ciencias Aplicadas</h1>
  <h2>Ingeniería de Software</h2>
  <h2>Periodo: 202520</h2>
  <h2>1ACC0238 | Aplicaciones para Dispositivos Móviles</h2>
  <h2>NRC: 12614</h2>
  <h2>Docente: David Gerardo Quevedo Velasco</h2>
  <h1>Informe del Trabajo Final</h1>
  <h2>Startup: CoolingWorks</h2>
  <h2>Producto: OsitoPolar</h2>
  <h2>Integrantes</h2>
  <ul style="list-style: none;">
  <br>U202310425 Aguirre Castillo Sergio Cesar<br>
  <br>U202223811 Montañez Moreno, Luis Angel<br>
  <br>U202317442 Muñoz Machuca, Maria Elena<br>
  <br>U202223286 Rodriguez Parco Joseph Pablo<br>
  <br>U202123655 Rojas Reategui Victor Manuel<br>
  </ul>
  <h3>Noviembre 2025</h3>
</div>

<div style="page-break-after: always;"></div>

## Registro de Versiones del Informe

| Versión | Fecha      | Autor                | Descripción de modificación                                     |
|---------|------------|----------------------|-----------------------------------------------------------------|
| 0.1     | 08/09/2025 | Joseph Rodriguez     | Desarrollo del Capítulo 1 y Capítulo 2                          |
| 0.2     | 17/09/2025 | Joseph Rodriguez     | Desarrollo del Capítulo 2 (entrevistas, competidores, segmentación) |
| 0.3     | 06/10/2025 | Luis Montañez        | Inclusión de evidencias del Sprint 1 e implementación de Landing Page |
| 0.4     | 08/11/2025 | Sergio Aguirre       | Desarrollo del Capítulo 3 y evidencias del Sprint 2 |
| 1.0     | 27/11/2025 | Victor Rojas         | Inclusión de evidencias del Sprint 3, validaciones y conclusiones finales |

## Project Report Collaboration Insights
**TB1** Desarrollo del reporte hasta el capítulo 2 para el sprint 1
<br>
<img width="1286" height="645" alt="image" src="https://github.com/user-attachments/assets/85884f83-6e93-496c-a74c-d26fde8b200f" />
<br>

- **URL de la organización del proyecto:** [https://github.com/Equipo5-Aplicaciones-Moviles](https://github.com/Equipo5-Aplicaciones-Moviles)
- **URL del repositorio del informe del proyecto:** [https://github.com/Equipo5-Aplicaciones-Moviles/upc-Aplicaciones-Moviles-Equipo5](https://github.com/Equipo5-Aplicaciones-Moviles/upc-Aplicaciones-Moviles-Equipo5)

<div style="page-break-after: always;"></div>

# Chapter I: Presentation
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1. Antecendentes y Problemática](#121-antecedentes-y-problemática)
  - [1.2.2. Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos Objetivos](#13-segmentos-objetivos)

# Chapter II: Requirements Development and Software Solution Design
- [2.1. Competitores](#21-competitores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-Estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-Entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-Registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-Análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.3.5. Ubiquitous Language](#235-ubiquitous-language)
- [2.4. Requirements Specification](#24-requirements-specification)
  - [2.4.1. User Stories](#241-user-stories)
  - [2.4.2. Impact Mapping](#242-impact-mapping)
  - [2.4.3. Product Backlog](#243-product-backlog)
- [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)
  - [2.5.1. EventStorming](#251-eventstorming)
    - [2.5.1.1. Candidate Context Discovery](#2511-candidate-context-discovery)
    - [2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)
    - [2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)
  - [2.5.2. Context Mapping](#252-context-mapping)
  - [2.5.3. Software Architecture](#253-software-architecture)
    - [2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
    - [2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)
    - [2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)
- [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)
  
  - [2.6.1. Bounded Context: Mi equipo](#261-bounded-context-mi-equipo)
    - [2.6.1.1. Domain Layer](#2611-domain-layer)
    - [2.6.1.2. Interface Layer](#2612-interface-layer)
    - [2.6.1.3. Application Layer](#2613-application-layer)
    - [2.6.1.4. Infrastructure Layer](#2614-infrastructure-layer)
    - [2.6.1.5. Bounded Context Software Architecture Component Level Diagrams](#2615-bounded-context-software-architecture-component-level-diagrams)
    - [2.6.1.6. Bounded Context Software Architecture Code Level Diagrams](#2616-bounded-context-software-architecture-code-level-diagrams)
      - [2.6.1.6.1. Bounded Context Domain Layer Class Diagrams](#26161-bounded-context-domain-layer-class-diagrams)
      - [2.6.1.6.2. Bounded Context Database Design Diagram](#26162-bounded-context-database-design-diagram)
  - [2.6.2. Bounded Context: Gestión de Solicitudes](#262-bounded-context-gestión-de-solicitudes)
    - [2.6.2.1. Domain Layer](#2621-domain-layer)
    - [2.6.2.2. Interface Layer](#2622-interface-layer)
    - [2.6.2.3. Application Layer](#2623-application-layer)
    - [2.6.2.4. Infrastructure Layer](#2624-infrastructure-layer)
    - [2.6.2.5. Bounded Context Software Architecture Component Level Diagrams](#2625-bounded-context-software-architecture-component-level-diagrams)
    - [2.6.2.6. Bounded Context Software Architecture Code Level Diagrams](#2626-bounded-context-software-architecture-code-level-diagrams)
      - [2.6.2.6.1. Bounded Context Domain Layer Class Diagrams](#26261-bounded-context-domain-layer-class-diagrams)
      - [2.6.2.6.2. Bounded Context Database Design Diagram](#26262-bounded-context-database-design-diagram)
  - [2.6.3. Bounded Context: Órdenes de Trabajo](#263-bounded-context-órdenes-de-trabajo)
    - [2.6.3.1. Domain Layer](#2631-domain-layer)
    - [2.6.3.2. Interface Layer](#2632-interface-layer)
    - [2.6.3.3. Application Layer](#2633-application-layer)
    - [2.6.3.4. Infrastructure Layer](#2634-infrastructure-layer)
    - [2.6.3.5. Bounded Context Software Architecture Component Level Diagrams](#2635-bounded-context-software-architecture-component-level-diagrams)
    - [2.6.3.6. Bounded Context Software Architecture Code Level Diagrams](#2636-bounded-context-software-architecture-code-level-diagrams)
      - [2.6.3.6.1. Bounded Context Domain Layer Class Diagrams](#26361-bounded-context-domain-layer-class-diagrams)
      - [2.6.3.6.2. Bounded Context Database Design Diagram](#26362-bounded-context-database-design-diagram)
  - [2.6.4. Bounded Context: Ver Mantenimientos](#264-bounded-context-ver-mantenimientos)
    - [2.6.4.1. Domain Layer](#2641-domain-layer)
    - [2.6.4.2. Interface Layer](#2642-interface-layer)
    - [2.6.4.3. Application Layer](#2643-application-layer)
    - [2.6.4.4. Infrastructure Layer](#2644-infrastructure-layer)
    - [2.6.4.5. Bounded Context Software Architecture Component Level Diagrams](#2645-bounded-context-software-architecture-component-level-diagrams)
    - [2.6.4.6. Bounded Context Software Architecture Code Level Diagrams](#2646-bounded-context-software-architecture-code-level-diagrams)
      - [2.6.4.6.1. Bounded Context Domain Layer Class Diagrams](#26461-bounded-context-domain-layer-class-diagrams)
      - [2.6.4.6.2. Bounded Context Database Design Diagram](#26462-bounded-context-database-design-diagram)
  - [2.6.5. Bounded Context: Notificaciones](#265-bounded-context-notificaciones)
    - [2.6.5.1. Domain Layer](#2651-domain-layer)
    - [2.6.5.2. Interface Layer](#2652-interface-layer)
    - [2.6.5.3. Application Layer](#2653-application-layer)
    - [2.6.5.4. Infrastructure Layer](#2654-infrastructure-layer)
    - [2.6.5.5. Bounded Context Software Architecture Component Level Diagrams](#2655-bounded-context-software-architecture-component-level-diagrams)
    - [2.6.5.6. Bounded Context Software Architecture Code Level Diagrams](#2656-bounded-context-software-architecture-code-level-diagrams)
      - [2.6.5.6.1. Bounded Context Domain Layer Class Diagrams](#26561-bounded-context-domain-layer-class-diagrams)
      - [2.6.5.6.2. Bounded Context Database Design Diagram](#26562-bounded-context-database-design-diagram)
  - [2.6.6. Bounded Context: Ver Equipos](#266-bounded-context-ver-equipos)
    - [2.6.6.1. Domain Layer](#2661-domain-layer)
    - [2.6.6.2. Interface Layer](#2662-interface-layer)
    - [2.6.6.3. Application Layer](#2663-application-layer)
    - [2.6.6.4. Infrastructure Layer](#2664-infrastructure-layer)
    - [2.6.6.5. Bounded Context Software Architecture Component Level Diagrams](#2665-bounded-context-software-architecture-component-level-diagrams)
    - [2.6.6.6. Bounded Context Software Architecture Code Level Diagrams](#2666-bounded-context-software-architecture-code-level-diagrams)
      - [2.6.6.6.1. Bounded Context Domain Layer Class Diagrams](#26661-bounded-context-domain-layer-class-diagrams)
      - [2.6.6.6.2. Bounded Context Database Design Diagram](#26662-bounded-context-database-design-diagram)



# Chapter III: Solution UI/UX Design
- [3.1. Product Design](#31-product-design)
  - [3.1.1. Style Guidelines](#311-style-guidelines)
    - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
  - [3.1.2. Information Architecture](#312-information-architecture)
    - [3.1.2.1. Organization Systems](#3121-organization-systems)
    - [3.1.2.2. Labelling Systems](#3122-labelling-systems)
    - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
    - [3.1.2.4. Searching Systems](#3124-searching-systems)
    - [3.1.2.5. Navigation Systems](#3125-navigation-systems)
  - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
    - [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)
    - [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)
  - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)
    - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
    - [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)
    - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
    - [3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)
    - [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)

# Chapter IV: Product Implementation & Validation
- [4. Product Implementation & Validation](#4-product-implementation--validation)
- [4.1. Software Configuration Management](#41-software-configuration-management)
  - [4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)
  - [4.1.2. Source Code Management](#412-source-code-management)
  - [4.1.3. Source Code Style Guide & Conventions](#413-source-code-style-guide--conventions)
  - [4.1.4. Software Deployment Configuration](#414-software-deployment-configuration)
- [4.2. Landing Page & Mobile Application Implementation](#42-landing-page--mobile-application-implementation)
  - [4.2.1. Sprint n](#421-sprint-n)
    - [4.2.1.1. Sprint Planning n](#4211-sprint-planning-n)
    - [4.2.1.2. Sprint Backlog n](#4212-sprint-backlog-n)
    - [4.2.1.3. Development Evidence for Sprint Review](#4213-development-evidence-for-sprint-review)
    - [4.2.1.4. Testing Suite Evidence for Sprint Review](#4214-testing-suite-evidence-for-sprint-review)
    - [4.2.1.5. Execution Evidence for Sprint Review](#4215-execution-evidence-for-sprint-review)
    - [4.2.1.6. Services Documentation Evidence for Sprint Review](#4216-services-documentation-evidence-for-sprint-review)
    - [4.2.1.7. Software Deployment Evidence for Sprint Review](#4217-software-deployment-evidence-for-sprint-review)
    - [4.2.1.8. Team Collaboration Insights during Sprint](#4218-team-collaboration-insights-during-sprint)
- [4.3. Validation Interviews](#43-validation-interviews)
  - [4.3.1. Interview Design](#431-interview-design)
  - [4.3.2. Interview Records](#432-interview-records)
  - [4.3.3. Heuristic Evaluations](#433-heuristic-evaluations)

# Conclusions
- [Conclusions and Recommendations](#conclusions-and-recommendations)

# Videos
- [Video App Validation](#video-app-validation)
- [Video About the Product](#video-about-the-product)
- [Video About the Team](#video-about-the-team)

# Glosario
- [Glosario](#glosario)

# Bibliografia
- [Bibliografia](#bibliografia)

# Anexos (haz hiper vinculos ese indice)
- [Anexos](#anexos-haz-hiper-vinculos-ese-indice)


<div style="page-break-after: always;"></div>

## Student Outcome
El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 7**

**Criterio**: *La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 7.

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|--------------------|--------------|
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software. | <ul><li><b>Sergio Aguirre</b><br><b>TB1:</b> Tomé el rol de líder del equipo, asigné tareas y apoyé al equipo; elaboré secciones del segmento objetivo 2 y User Stories.<br><b>TP1:</b> Consolidé el plan de la entrega, prioricé backlog y coordiné dependencias; revisé coherencia entre artefactos y narrativa del documento.<br><b>TB2:</b> Definí la estructura final del proyecto y los módulos de desarrollo; lideré sesiones de revisión de código y aseguré alineación con los estándares de arquitectura móvil. </li><li><b>María Elena Muñoz Machuca</b><br><b>TB1:</b> Realicé el context mapping, bounded context canvases y software architecture del bounded context de pagos y suscripciones.<br><b>TP1:</b> Profundicé la arquitectura de pagos/suscripciones, normalicé plantillas de documentación y aseguré alineamiento con objetivos de producto.<br><b>TB2:</b> Implementé mejoras en la arquitectura de la aplicación móvil, optimizando el uso de APIs y el flujo de datos entre componentes. Colaboré con el equipo de frontend en la integración del backend.</li><li><b>Víctor Manuel Rojas Reátegui</b><br><b>TB1:</b> Participé en reuniones y apoyé la definición de la estructura del proyecto.<br><b>TP1:</b> Formalicé la estructura de paquetes y convenciones, asistí en integración técnica y control de calidad del repositorio.<br><b>TB2:</b> Desarrollé la integración de las funcionalidades de la aplicación con bases de datos móviles, mejoré el control de versiones en el repositorio y optimicé la automatización de pruebas de integración.</li><li><b>Luis Montañez</b><br><b>TB1:</b> Coordiné la elaboración de entregables y la retroalimentación continua entre miembros.<br><b>TP1:</b> Estandaricé formatos del informe, verifiqué criterios de aceptación y consistencia visual/técnica.<br><b>TB2:</b> Supervisé la coherencia entre los requerimientos funcionales y el diseño final, asegurando que el código estuviera alineado con las expectativas del cliente y los requerimientos del proyecto.</li><li><b>Joseph Rodríguez</b><br><b>TB1:</b> Aporté ideas al prototipo, redacté partes del informe y asistí a reuniones de coordinación.<br><b>TP1:</b> Apoyé la construcción del prototipo, cerré gaps de contenido y controlé el avance cruzado de tareas.<b>TB2:</b> Fomenté la colaboración entre el equipo y promoví la adopción de mejores prácticas en el desarrollo del frontend; actualicé el prototipo móvil y realicé pruebas de usabilidad.</li></ul> | <ul><li><b>TB1:</b> Se actualizaron conocimientos técnicos y metodológicos mediante la elaboración de artefactos (context mapping, BCC, arquitectura), reforzando el desarrollo profesional y la base del proyecto.</li><li><b>TP1:</b> La profundización en arquitectura/estructura de código y la consolidación de entregables fortalecieron competencias de diseño, documentación y organización, elevando la calidad técnica del producto.</li><li><b>TB2:</b> La implementación de mejoras en la arquitectura, integración y pruebas fortalece los conocimientos técnicos y las capacidades de desarrollo en soluciones de software, alineando el proyecto con los estándares de calidad y el mercado móvil.</li></ul> |
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software. | <ul><li><b>Sergio Aguirre</b><br><b>TB1:</b> Coordiné trabajo en Trello, Miro y Figma.<br><b>TP1:</b> Gestioné tablero (priorización/seguimiento), sesiones de Miro (As-Is/To-Be) y validación de wireframes en Figma.</li><li><b>María Elena Muñoz Machuca</b><br><b>TB1:</b> Elaboré context mapping/BCC y arquitectura de pagos/suscripciones.<br><b>TP1:</b> Apliqué buenas prácticas de documentación, incorporé feedback iterativo y mantuve trazabilidad de decisiones.</li><li><b>Víctor Manuel Rojas Reátegui</b><br><b>TB1:</b> Elaboré wireframes de Landing Page y organicé ramas/estructura del repo.<br><b>TP1:</b> Definí naming/flujo Git (ramas, PRs, revisiones) y automatizé chequeos básicos.</li><li><b>Luis Montañez</b><br><b>TB1:</b> Planificación conjunta con plazos claros y distribución de tareas.<br><b>TP1:</b> Gestión de riesgos, seguimiento de hitos y soporte a integración entre frentes.</li><li><b>Joseph Rodríguez</b><br><b>TB1:</b> Cumplí tareas, definí objetivos realistas y mantuve comunicación constante.<br><b>TP1:</b> Aseguré continuidad de entregas, documenté aprendizajes y promoví retroalimentación continua.</li></ul> | <ul><li><b>TB1:</b> El uso de herramientas colaborativas y metodologías ágiles fortaleció hábitos de aprendizaje continuo y coordinación efectiva.</li><li><b>TP1:</b> La adopción disciplinada de Trello/Miro/Figma y flujo Git mejoró competencias individuales y colectivas, trazabilidad y eficiencia del equipo.</li></ul> |

# Objetivos SMART
#### Muñoz Machuca, Maria Elena
**Objetivo 1**<br>
Al culminar mi carrera, uno de mis principales objetivos es convertirme en desarrolladora de software full-stack, con dominio tanto de tecnologías de frontend como de backend. Para alcanzarlo, me propongo participar en proyectos completos que integren ambos enfoques. Mi meta es dedicar entre 8 y 10 horas semanales al estudio y práctica.<br>

**Objetivo 2**<br>
Otro de mis objetivos es desarrollar y diseñar soluciones tecnológicas que generen un impacto positivo en la vida de las personas. Para ello, me propongo crear al menos un proyecto propio que responda a un problema o necesidad social. Este propósito implica aprender y aplicar metodologías ágiles, de esta manera podré logar mi objetivos y mantener mi compromiso de mejorar la calidad de vida de las personas usando la tecnología.

#### Aguirre Castillo Sergio Cesar
**Objetivo 1**<br>
Al culminar mi carrera, mi objetivo es convertirme en arquitecto de software especializado en diseño de sistemas distribuidos. Para ello, me propongo participar en proyectos académicos y profesionales donde pueda aplicar patrones de diseño y principios de arquitectura. Dedicaré un mínimo de 6 horas semanales al estudio de arquitectura de software y al uso de herramientas de modelado como UML y Structurizr.<br>

**Objetivo 2**<br>
Otro de mis objetivos es fortalecer mis habilidades de liderazgo en equipos de desarrollo. Para lograrlo, me propongo asumir roles de coordinación en al menos dos proyectos grupales y capacitarme en metodologías ágiles como Scrum y Kanban. Mediré mi progreso en función de la retroalimentación del equipo y la capacidad de cumplir con las metas establecidas en los proyectos.

#### Montañez Moreno, Luis Angel
**Objetivo 1**<br>
Al finalizar mi carrera, mi objetivo es especializarme en desarrollo frontend, con dominio en frameworks modernos como React y Angular. Para alcanzarlo, dedicaré entre 5 y 7 horas semanales a cursos y prácticas de diseño de interfaces y usabilidad, aplicándolos en proyectos personales y académicos.<br>

**Objetivo 2**<br>
También me propongo contribuir al desarrollo de proyectos con impacto social mediante soluciones accesibles y responsivas. Para ello, me comprometo a diseñar al menos una aplicación web inclusiva antes de culminar mi carrera, siguiendo lineamientos de accesibilidad (WCAG) y buenas prácticas de UX/UI.

#### Rodriguez Parco Joseph Pablo
**Objetivo 1**<br>
Mi objetivo principal al terminar la carrera es especializarme en desarrollo backend, enfocándome en tecnologías como .NET y Java. Para lograrlo, dedicaré al menos 6 horas semanales a proyectos y prácticas que refuercen mis conocimientos en bases de datos, APIs y servicios en la nube.<br>

**Objetivo 2**<br>
También quiero potenciar mis habilidades de trabajo en equipo y comunicación profesional. Para alcanzarlo, me propongo participar activamente en al menos tres proyectos colaborativos, asumiendo responsabilidades de integración de componentes y documentación. Mi progreso se medirá con la calidad de la comunicación y el cumplimiento de los objetivos en los plazos establecidos.

#### Rojas Reategui Victor Manuel
**Objetivo 1**<br>
Mi objetivo al culminar la carrera es convertirme en ingeniero de software especializado en DevOps y despliegue de aplicaciones. Para lograrlo, me comprometo a dominar herramientas como Docker, Kubernetes y CI/CD pipelines, dedicando entre 5 y 8 horas semanales a la práctica en entornos reales o simulados.<br>

**Objetivo 2**<br>
Otro de mis objetivos es contribuir al despliegue eficiente y seguro de aplicaciones en la nube. Para ello, desarrollaré al menos un proyecto implementado en AWS o Azure antes de terminar la carrera, midiendo el éxito mediante pruebas de rendimiento, escalabilidad y seguridad.

<div style="page-break-after: always;"></div>

# Capítulo I: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup
OsitoPolar es una aplicación móvil orientada a mejorar la gestión y el mantenimiento de equipos de congelación en negocios que dependen críticamente del frío, como supermercados, minimarkets, laboratorios, restaurantes y empresas del sector alimentario o farmacéutico. La solución conecta a estos negocios con técnicos y proveedores especializados en refrigeración, permitiendo una gestión integral, preventiva y automatizada de sus sistemas de congelación.

La plataforma ofrece funcionalidades clave como monitoreo en tiempo real de temperatura, consumo energético y tiempo de uso, generación de reportes técnicos, alertas automatizadas por fallas, historial de rendimiento, y programación inteligente de mantenimientos. Estas herramientas permiten a los usuarios optimizar sus operaciones, evitar pérdidas económicas por fallas inesperadas y mantener un registro completo del estado y uso de sus equipos.

OsitoPolar no solo está diseñado para negocios que utilizan equipos de frío, sino también para empresas proveedoras de equipos y serviciós de refrigeración. A través de su módulo especializado, los técnicos pueden visualizar todos los equipos que atienden, gestionar sus visitas, acceder al historial técnico de cada unidad y generar reportes de forma automática.

**Misión:** Nuestra misión en OsitoPolar es proporcionar una solución tecnológica inteligente que permita a los negocios proteger su inventario y optimizar la gestión de sus equipos de refrigeración, ofreciendo al mismo tiempo herramientas especializadas para mejorar la eficiencia operativa de los técnicos y proveedores del sector.

**Visión:** Queremos ser la empresa lider en gestión y mantenimiento de equipos de refrigeración, empezando por Lima y prontamente expandirnos a más lugares del Perú.

### 1.1.2. Perfiles de integrantes del equipo

| **Integrante** | **Joseph Pablo Rodriguez Parco** |
|----------------|----------------------------------|
| **Código del Estudiante** | U202223286 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Estudiante de Ingeniería de Software con afinidad por proyectos Web, Interesado en ML, Data Science y aprender por sobre todas las cosas. |
| **Foto** | <img src="assets/chapter01/Joseph-Rodriguez-Picture.png" alt="Joseph" width="200" height="200"> |

---

| **Integrante** | **Aguirre Castillo, Sergio Cesar** |
|----------------|----------------------------------|
| **Código del Estudiante** | U202310425 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Soy Aguirre Castillo, Sergio Cesar, tengo 20 años y actualmente curso el sexto ciclo de la carrera de Ingeniería de Software. Me caracterizo por mi sentido de responsabilidad y mi habilidad para trabajar en equipo. Disfruto colaborar con mis compañeros y aportar al cumplimiento de objetivos en el ámbito académico y en proyectos grupales. Poseo experiencia en diversos lenguajes de programación, como C++, Python y Java, además de conocimientos en bases de datos SQL y NoSQL. |
| **Foto** | <img width="200" height="280" alt="image" src="https://github.com/user-attachments/assets/147f7060-da83-498e-afa2-d446d2244da5" />|

---

| **Integrante** | **Victor Manuel Rojas Reategui** |
|----------------|----------------------------------|
| **Código del Estudiante** | U202123655 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Soy Victor Rojas y voy en el 5to ciclo de la carrera de Ingeniería de Software. Me gusta lo rápido que cambia la tecnología en la actualidad, por lo que este curso me ayudará a expandir mis conocimientos y a explorar nuevas aplicaciones de mi carrera que no había experimentado antes. |
| **Foto** | <img src="assets/chapter01/Victor-Rojas-Picture.jpg" alt="Victor" width="200" height="200"> |

---

| **Integrante** | **Maria Elena Muñoz Machuca** |
|----------------|----------------------------------|
| **Código del Estudiante** | U202317442 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Soy estudiante de la Universidad Peruana de Ciencias Aplicadas (UPC) y soy de la carrera de Ingeniería de Software cursando el sexto ciclo de la carrera. Mi objetivo es aprender más sobre desarrollo de software asi como adquirir experiencia en otros lenguajes de programación. |
| **Foto** | <img src="assets/chapter01/Maria-Muñoz.png" alt="Maria" width="200" height="200"> |

---

| **Integrante** | **Luis Angel Montañez Moreno** |
|----------------|----------------------------------|
| **Código del Estudiante** | U202223811 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Soy un estudiante de 5to ciclo de la carrera de Ingeniería de Software que le gusta aprender sobre la tecnología y cómo su uso puede mejorar nuestra vida cotidiana. Mi objetivo es seguir adquiriendo conocimientos en lenguajes de programación para ser más competente en el mundo profesional. |
| **Foto** | <img src="assets/chapter01/Luis Montanez.jpg" alt="Luis" width="200" height="200"> |

## 1.2. Solution Profile

### 1.2.1. Antecedentes y Problemática

| Las 5Ws y 2Hs | Pregunta | Descripción |
|---|---|---|
| What? | ¿Cuál es el problema? | Actualmente, los negocios que dependen de equipos de congelación enfrentan grandes desafíos operativos ante fallas inesperadas o falta de mantenimiento. Las fallas térmicas, los altos consumos energéticos no detectados a tiempo y la ausencia de un monitoreo constante pueden derivar en la pérdida de productos, reducción de la calidad del servicio y pérdidas económicas importantes. |
| When? | ¿Cuándo sucede este problema? | Estas situaciones ocurren principalmente durante horarios de operación continua, especialmente en momentos donde no hay personal técnico disponible de forma inmediata, o cuando no se ha realizado un seguimiento adecuado del estado del equipo a lo largo del tiempo. |
| Where? | ¿Dónde se produce este suceso? | El problema afecta a negocios ubicados en todo el país, principalmente en Lima, donde la cadena de frío es esencial en sectores como alimentación, medicina y distribución. También impacta a empresas proveedoras de refrigeración que atienden múltiples clientes sin una plataforma centralizada de control. |
| Who? | ¿Quiénes están involucrados? | Están involucrados tanto los administradores y dueños de negocios que utilizan congeladoras como los técnicos y empresas proveedoras de servicios de refrigeración. |
| Why? | ¿Cuál es la causa del problema? | La causa principal es la falta de soluciones tecnológicas accesibles que integren monitoreo, alertas, historial y programación automática en un solo lugar. Muchas empresas aún dependen de sistemas manuales o no tienen control de lo que sucede con sus equipos hasta que ocurre una falla crítica. |
| How? | ¿Qué llevó a la persona a llegar a esta situación? | Lo que llevó a los negocios y técnicos a este punto ha sido la acumulación de imprevistos y la falta de digitalización en el mantenimiento preventivo, que genera una alta dependencia de intervenciones reactivas en vez de planificadas. Esto incrementa los costos, los tiempos de respuesta y el desgaste operativo. |
| How much? | ¿Cuánto es el impacto financiero? | Aunque el impacto económico varía según el tipo de negocio, la pérdida por una falla en un equipo de refrigeración puede ascender desde cientos hasta miles de soles en productos dañados, sin considerar el tiempo operativo perdido, la pérdida de clientes y la inversión en reparación o reposición de equipos. |

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements
El estado actual de la industria de la refrigeración comercial y técnica enfrenta importantes desafíos relacionados con la gestión, el mantenimiento y la trazabilidad de los equipos de congelación. Negocios que dependen críticamente del frío —como supermercados, minimarkets, laboratorios, restaurantes y empresas del sector alimentario o farmacéutico— aún lidian con la falta de monitoreo en tiempo real y con procesos de mantenimiento reactivos. Esto genera pérdidas económicas, ineficiencia energética y riesgos para el inventario.

**Cambiar el problema**
Hemos identificado una brecha significativa: las soluciones actuales no abordan de manera integral la necesidad de una plataforma confiable y automatizada que permita la gestión centralizada, predictiva y transparente de los sistemas de refrigeración. La ausencia de un historial técnico accesible, reportes detallados y alertas preventivas limita la capacidad de respuesta ante fallas y reduce la eficiencia del servicio técnico.

**¿Cómo podríamos reducir las fallas imprevistas y optimizar el mantenimiento de los sistemas de refrigeración comercial mediante una plataforma digital que conecte negocios y técnicos especializados?**

#### 1.2.2.2. Lean UX Assumptions

**Business Outcomes**
- Aumentar en al menos un 15% la cantidad de usuarios activos dentro de la aplicación.
- Lograr una mayor visibilidad de la plataforma OsitoPolar a través de redes sociales, especialmente entre negocios de alimentos y técnicos de refrigeración.
- Generar confianza y seguridad en los usuarios respecto al monitoreo y mantenimiento automatizado de sus sistemas de refrigeración.
- Mantener informado al usuario final sobre incidentes recientes como fallas térmicas, cortes de energía o uso irregular de los equipos.
- Alcanzar una base sólida de usuarios dispuestos a pagar por una membresía premium que incluya mantenimiento predictivo, reportes personalizados y soporte técnico prioritario.
- Establecer alianzas estratégicas con plataformas como Google Maps o servicios de geolocalización para ampliar el alcance de cobertura y optimizar la programación de visitas técnicas.
- Fomentar la participación activa de los usuarios mediante encuestas, valoraciones de técnicos y comentarios sobre el desempeño de los equipos.
- Diseñar una interfaz limpia, simple e intuitiva que garantice una experiencia fluida y atractiva para nuevos usuarios, evitando la sobrecarga visual o de funcionalidades.
- Implementar inteligencia artificial que permita trazar estrategias de mantenimiento inteligente, rutas eficientes para los técnicos y recomendaciones proactivas ante posibles fallos.

**User Outcomes**

## ¿Quién será nuestro usuario?

- **Negocios que dependen críticamente del uso de sistemas de refrigeración** como supermercados, minimarkets, restaurantes, laboratorios y empresas del rubro alimentario y farmacéutico.
- **Técnicos especializados en refrigeración** que brindan mantenimiento a dichos sistemas.
- **Proveedores de equipos de refrigeración** que desean ofrecer un servicio posventa más eficiente.

## ¿Dónde encaja nuestro producto en su vida?

- En situaciones donde los negocios necesitan garantizar la continuidad operativa de sus equipos de frío, evitando pérdidas económicas por fallas imprevistas.
- En el día a día de técnicos de refrigeración que deben gestionar múltiples clientes, visitas y mantenimientos.
- En la operación diaria de los negocios que necesitan registros y reportes precisos del desempeño de sus sistemas de refrigeración.

## ¿Qué problemas tiene nuestro producto y cómo se pueden resolver?

- El principal desafío es asegurar que los datos de monitoreo (temperatura, consumo energético, fallas, etc.) sean precisos, actualizados y confiables.  
  **Solución**: Se debe integrar sensores calibrados y sistemas de verificación automática que validen las lecturas antes de almacenarlas.
- Otro problema puede ser la adopción inicial de la plataforma por parte de usuarios no tecnológicos.  
  **Solución**: Esto se abordará con una interfaz sencilla, explicaciones paso a paso y soporte técnico accesible.

## ¿Cómo y Cuándo es usado nuestro producto?

- Se accede desde la aplicación web, tanto desde computadoras como dispositivos móviles.
- Se utiliza diariamente para monitorear el estado de los equipos de frío, recibir alertas, programar mantenimientos o revisar el historial técnico.
- También se activa automáticamente en segundo plano cuando se integran sensores de monitoreo con la plataforma.

## ¿Qué problemas tiene nuestro producto?

- En sus etapas iniciales, puede carecer de ciertas integraciones con hardware de terceros.
- Algunos usuarios pueden requerir capacitación para comprender todas las funcionalidades avanzadas.
- También podría haber desafíos para que los técnicos adopten el uso digital en lugar del método tradicional.

## ¿Qué características son importantes para la app?

- Monitoreo en tiempo real de temperatura, consumo energético y tiempo de uso.
- Alertas automáticas por fallas detectadas en los equipos.
- Historial técnico completo con reportes exportables en PDF.
- Calendario de mantenimiento preventivo con notificaciones programadas.
- Módulo exclusivo para técnicos con gestión de visitas y clientes.
- Soporte técnico inteligente y recomendaciones predictivas mediante IA.
- Registro de múltiples ubicaciones y usuarios con distintos roles.
- Interfaz intuitiva y minimalista para garantizar fácil adopción.

## ¿Cómo debe verse nuestro producto y cómo comportarse?

- **Interfaz amigable y confiable**: Los usuarios deben sentirse seguros al usar la aplicación. La interfaz debe ser clara, ordenada y fácil de navegar, sin sobrecargar de información, con gráficos e indicadores intuitivos.
- **Diseño centrado en tareas críticas**: Desde el primer acceso, los usuarios deben poder ver si hay fallas, cuándo es la próxima visita técnica, y acceder rápidamente a los reportes y al historial de sus equipos.
- **Accesibilidad multiplataforma**: Disponible en web y móvil, adaptable para usuarios que están en oficina o en campo. Notificaciones inmediatas ante cualquier problema detectado.
- **Simplicidad**: La app debe permitirles ver sus clientes, equipos en riesgo y visitas programadas, todo desde un panel centralizado. Pueden agendar visitas y generar reportes técnicos en segundos.

## ¿Qué valor busca el cliente?

- **Gestión técnica simplificada**: Los proveedores y técnicos buscan dejar de ser reactivos. OsitoPolar los vuelve proactivos con mantenimiento predictivo, historiales claros y clientes organizados.
- **Seguridad operativa y cero sorpresas**: Los negocios quieren evitar pérdidas por fallas en frío. OsitoPolar les da monitoreo constante, alertas automáticas y control total sobre sus equipos.
- **Eficiencia energética y trazabilidad**: Los dueños quieren saber si sus equipos consumen de más, si están rindiendo mal, o si un componente ya debería ser reemplazado. El sistema lo identifica antes que ocurra el fallo.

## ¿Qué beneficios adicionales obtendrá el cliente?

- Visibilidad total del estado de sus equipos, desde cualquier lugar, en cualquier momento.
- Soporte técnico más ágil gracias al historial previo y alertas automáticas.
- Menores costos operativos gracias a mantenimientos a tiempo y mayor eficiencia energética.
- Reportes personalizados y exportables.
- Automatización de visitas técnicas cuando se detectan patrones de falla.

## ¿Cómo atraeremos usuarios?

- **Marketing dirigido a nichos clave**: Supermercados, restaurantes y empresas de frío serán contactados directamente mediante LinkedIn, correos y llamadas estratégicas.
- **Alianzas con proveedores de equipos**: Trabajaremos con empresas que venden congeladoras o cámaras frigoríficas para que incluyan OsitoPolar en sus paquetes posventa.
- **Prueba gratuita de versiones de pago**: Un modelo de 14 días gratis con monitoreo limitado para mostrar el valor de la plataforma en tiempo real.

## ¿Cómo generaremos ingresos?

- **Suscripción mensual de negocios**: Por el uso de la plataforma, según número de equipos, tipo de reportes y funcionalidades.
- **Modelo freemium**: Habrá una versión gratuita que brindará algunas funciones limitadas, pero con anuncios, lo que generará ingresos adicionales.
- **Publicidad dirigida (opcional)**: Marcas de refrigeración podrían pagar por visibilidad dentro de la plataforma si se llega a una masa crítica de técnicos y negocios.

## ¿Cuál es nuestra competencia y cómo la superamos?

- **Competencia**: Las principales competidoras son aplicaciones relacionadas con la gestión de datos y orientada al servicio técnico de mantenimiento de equipos de refrigeración.
- **Nuestra ventaja**: OsitoPolar fue diseñado exclusivamente para negocios que dependen de equipos de frío. No somos una herramienta genérica, somos expertos en el nicho. No solo registramos visitas o mantenimientos, también detectamos anomalías en tiempo real, generamos alertas y automatizamos acciones.

## ¿Cuál es nuestro mayor riesgo?

- **Adopción lenta por parte del personal tradicional**: Algunos proveedores aún dependen de agendas físicas o Excel y podrían resistirse al cambio.
- **Falta de adopción inicial**: La dificultad para convencer a los primeros usuarios de que la app es útil y confiable puede retrasar su adopción.
- **Desconfianza en la precisión de los sensores**: Si los datos no son confiables, la plataforma pierde valor

## ¿Cómo lo resolveremos?

- **Algoritmos de validación**: Implementaremos algoritmos de IA que verifiquen la información y filtren los reportes ambiguos o antiguos, garantizando solo datos confiables y actuales.
- **Capacitación y soporte**: Para resolver la falta de adopción, ofreceremos tutoriales interactivos, videos explicativos y soporte técnico accesible para que los usuarios se familiaricen con las funciones.
- **Estrategia progresiva de integraciones**: Comenzaremos con los equipos más usados y luego ampliaremos compatibilidad mediante APIs y alianzas con fabricantes.
- **Sensores certificados**: Solo se integrarán sensores probados.


#### 1.2.2.3. Lean UX Hypothesis Statements

**Hipótesis 1: Eficiencia operativa y reducción de fallas inesperadas**
Creemos que **al ofrecer una plataforma integral que unifique las funciones de monitoreo, mantenimiento y gestión técnica de equipos de refrigeración**, aumentaremos la eficiencia operativa de los negocios y proveedores del sector, reduciendo la complejidad y el riesgo de fallas inesperadas.  
Sabremos que hemos tenido éxito **cuando observemos una reducción del 30% en las incidencias por fallas térmicas reportadas** y **un aumento del 25% en la planificación de mantenimientos preventivos dentro de la plataforma** durante los primeros seis meses.

**Hipótesis 2: Control de pérdidas operativas y consumo energético**
Creemos que **al proporcionar herramientas de análisis de rendimiento y alertas automatizadas**, los negocios podrán actuar de forma preventiva y reducir costos innecesarios asociados al consumo energético y pérdidas operativas.  
Sabremos que hemos tenido éxito **cuando observemos una disminución del 20% en los costos energéticos mensuales promedio** y **un incremento del 30% en el uso de los reportes de monitoreo en tiempo real** por parte de los usuarios activos.

**Hipótesis 3: Mejora en el servicio técnico personalizado y predictivo**
Creemos que **al implementar reportes automáticos e históricos de rendimiento por equipo**, los técnicos y proveedores podrán ofrecer un servicio más personalizado y predictivo, aumentando la calidad del soporte brindado.  
Sabremos que hemos tenido éxito **cuando más del 70% de los técnicos califiquen positivamente los reportes automáticos en encuestas internas** y **cuando los clientes reporten un aumento del 25% en su satisfacción con la rapidez del servicio técnico.**

**Hipótesis 4: Trazabilidad y protección de la información técnica**
Creemos que **al garantizar la trazabilidad completa y la protección de los datos técnicos en la plataforma**, construiremos confianza entre los negocios y los proveedores de servicios.  
Sabremos que hemos tenido éxito **cuando logremos reducir en un 40% los errores administrativos o pérdidas de información** y **aumentar en un 30% la retención de usuarios técnicos y empresariales activos.**

**Hipótesis 5: Transición hacia una gestión moderna de refrigeración**
Creemos que **al ofrecer una solución digital intuitiva y especializada tanto para negocios como para técnicos**, facilitaremos la transición hacia una gestión moderna y eficiente de la refrigeración.  
Sabremos que hemos tenido éxito **cuando alcancemos una tasa de adopción del 60% de usuarios nuevos dentro de los tres primeros meses** y **una tasa de retención del 80% tras seis meses de uso continuo de la plataforma.**

#### 1.2.2.4. Lean UX Canvas
El presente Lean UX Canvas se ha desarrollado para ofrecer una visión estratégica y concisa de la solución OsitoPolar. Este marco nos permite alinear rápidamente los objetivos de negocio con las necesidades de nuestros usuarios y las hipótesis clave que guían nuestro desarrollo.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter01/lean-ux-canvas.png"
       alt="Lean UX Canvas: Un lienzo para aplicar principios de Lean UX al diseño."
       style="max-width: 80%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Lean UX Canvas.
  </figcaption>
</figure>

## 1.3. Segmentos objetivo

**Segmento Objetivo #1: Negocios que utilizan equipos de refrigeración**
* **Aspectos demográficos:**
    * **Tipo de negocio**: Pequeñas, medianas y grandes empresas
    * **Rubro**: Alimentario, farmacéutico, restauración y comercio minorista
    * **Nivel de necesidad**: Alta dependencia de sistemas de refrigeración
* **Aspectos geográficos:**
    * **Nacionalidad**: Peruana
    * **Zona geográfica**: Urbana
    * **Departamento**: Lima (con proyección de expansión nacional)
* **Aspectos psicográficos:**
    * Empresas que buscan evitar pérdidas económicas por fallas en refrigeración.
    * Negocios que requieren control eficiente del consumo energético.
    * Administradores interesados en implementar tecnología para optimizar sus operaciones y mantener la calidad del inventario.

**Segmento Objetivo #2: Empresas proveedoras de servicios y equipos de refrigeración**
* **Aspectos demográficos:**
    * **Tipo de empresa**: Técnicos independientes, PYMES y proveedores especializados en refrigeración.
    * **Rol**: Técnicos de mantenimiento, instaladores, empresas de soporte técnico.
* **Aspectos geográficos:**
    * **Nacionalidad**: Peruana
    * **Zona geográfica**: Urbana
    * **Departamento**: Lima (con visión de expansión a nivel nacional)
* **Aspectos psicográficos:**
    * Técnicos que desean organizar sus visitas de forma eficiente y centralizada.
    * Empresas que buscan mejorar la trazabilidad de sus servicios y ofrecer reportes automáticos.
    * Profesionales que desean brindar un servicio más personalizado y predictivo a sus clientes.

<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Development and Software Solution Design

## 2.1. Competidores

**Competidor 1: ServiceTitan**
ServiceTitan es una plataforma de gestión de servicios basada en la nube que ofrece soluciones de software para empresas de servicios, incluidos técnicos de HVAC, fontaneros y electricistas. Proporciona funcionalidades de programación, gestión de trabajos, facturación y más. Esta plataforma es conocida por su facilidad de uso y por ayudar a las empresas a optimizar sus operaciones de servicio técnico en tiempo real.

**Competidor 2: CoolMaster**
CoolMaster es una solución de software diseñada específicamente para el sector de refrigeración comercial. Ofrece monitoreo remoto de sistemas de refrigeración, alertas tempranas de fallas y gestión eficiente del consumo energético. La plataforma está orientada a optimizar la eficiencia operativa de negocios que dependen críticamente de sistemas de frío, como supermercados y centros de distribución.

**Competidor 3: TempGenius**
TempGenius es un software de monitoreo de temperatura y humedad en tiempo real para diversas industrias, incluida la de la refrigeración comercial. Permite a los usuarios realizar un seguimiento de sus equipos de refrigeración mediante sensores conectados a la nube, generar reportes y recibir alertas automáticas por variaciones en los niveles de temperatura. Su principal enfoque es mejorar la visibilidad y control de las operaciones de refrigeración para evitar pérdidas económicas.

### 2.1.1. Análisis competitivo

<table> 
  <tr>
    <th colspan="7"> Competitive Analysis Landscape </th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar acabo este análisis? </td>
    <td colspan="5"> Pregunta </td>
  </tr>
  <tr>
    <td colspan="5"> Respuesta </td>
  </tr>
  <tr>
    <td colspan="2"> Productos </td>
    <td> OsitoPolar </td>
    <td> ServiceTitan </td>
    <td> CoolMaster </td>
    <td> TempGenius </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td> OsitoPolar es una plataforma integral de monitoreo y gestión para sistemas de refrigeración, que conecta negocios con técnicos especializados. Ofrece monitoreo en tiempo real, alertas automáticas, mantenimiento preventivo, y trazabilidad de cada equipo. </td>
    <td> ServiceTitan es una plataforma de gestión de servicios basada en la nube que ofrece soluciones de software para empresas de servicios, incluidos técnicos de HVAC, fontaneros y electricistas. </td>
    <td> CoolMaster es una solución de software diseñada específicamente para el sector de refrigeración comercial. Ofrece monitoreo remoto de sistemas de refrigeración, alertas preventivas y gestión energética. </td>
    <td> TempGenius es un software de monitoreo de temperatura y humedad en tiempo real para diversas industrias, incluida la refrigeración comercial. Permite a los usuarios gestionar y recibir alertas automáticas sobre sus equipos. </td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td> Ofrece una solución automatizada y centralizada para negocios que necesitan monitorear y gestionar sus equipos de refrigeración. Permite a los técnicos optimizar sus visitas y el mantenimiento preventivo, mejorando la eficiencia operativa. </td>
    <td> Ofrece una plataforma todo-en-uno para la gestión de servicios con características como la programación de citas, facturación y seguimiento en tiempo real de proyectos. </td>
    <td> Ofrece soluciones específicas para la gestión de sistemas de refrigeración, con funcionalidades avanzadas de monitoreo, alertas y análisis de consumo energético. </td>
    <td> Ofrece monitoreo preciso en tiempo real de la temperatura y humedad, con alertas automáticas, y un enfoque especial en la fiabilidad y precisión de los datos. </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td> Mercado Objetivo </td>
    <td> Negocios que dependen de sistemas de refrigeración, como supermercados, minimarkets, laboratorios, restaurantes, entre otros. También incluye técnicos de refrigeración y proveedores de equipos. </td>
    <td> Empresas de servicios como HVAC, fontaneros, electricistas, y otros proveedores de servicios técnicos. </td>
    <td> Negocios que dependen de sistemas de refrigeración como supermercados, laboratorios, restaurantes y otros en el sector alimentario y farmacéutico. </td>
    <td> Usuarios de diversas industrias, especialmente en áreas que requieren monitoreo continuo de temperatura y humedad, como el sector alimentario y farmacéutico. </td>
  </tr>
  <tr>
    <td> Estrategias de Marketing </td>
    <td> Marketing digital, colaboraciones estratégicas con empresas del sector alimentario y farmacéutico, demostraciones gratuitas y promociones en redes sociales. </td>
    <td> Marketing digital, colaboraciones con empresas de servicios y promoción en plataformas de negocio. </td>
    <td> Marketing dirigido a negocios en el sector alimentario y farmacéutico, con énfasis en la reducción de fallas y el ahorro energético. </td>
    <td> Marketing en redes sociales, promociones para nuevos usuarios y colaboraciones con industrias reguladas como la farmacéutica y alimentaria. </td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td> Productos & Servicios </td>
    <td> Gestión de equipos de refrigeración en tiempo real, alertas automáticas, mantenimiento preventivo, reportes técnicos automáticos y trazabilidad de cada equipo. </td>
    <td> Plataforma de gestión de servicios que incluye programación de citas, gestión de personal, facturación, y seguimiento de proyectos en tiempo real. </td>
    <td> Plataforma de monitoreo y gestión de sistemas de refrigeración, con alertas preventivas, informes automáticos y análisis de rendimiento energético. </td>
    <td> Plataforma de monitoreo de temperatura y humedad en tiempo real, con alertas automáticas, reportes detallados y gestión de datos históricos. </td>
  </tr>
  <tr>
    <td> Precios & Costos </td>
    <td> Modelo basado en comisiones bajas por cada reserva o cita pagada para negocios, con una versión gratuita para usuarios. </td>
    <td> Suscripción mensual o anual, con tarifas adicionales por características avanzadas o soporte personalizado. </td>
    <td> Varía según el plan y características seleccionadas, con opciones para negocios grandes o pequeños. </td>
    <td> Varía según la cantidad de equipos monitoreados y las características seleccionadas, con modelos de suscripción mensual o anual. </td>
  </tr>
  <tr> 
    <td>Canales de distribución (Web y/o Móvil)</td>
    <td> Plataforma en línea y aplicación móvil disponible para dispositivos iOS y Android. </td>
    <td> Plataforma en línea y aplicación móvil disponible para dispositivos iOS y Android. </td>
    <td> Plataforma en línea y aplicación móvil. </td>
    <td> Aplicación móvil disponible en tiendas de aplicaciones y plataforma en línea. </td>
  </tr>
  <tr>
    <td rowspan="4"> Análisis SWOT </td>
    <td> Fortalezas </td>
    <td> Monitoreo en tiempo real, alertas automáticas y mantenimiento preventivo para evitar fallas críticas. Función de trazabilidad completa de los equipos. </td>
    <td> Amplia funcionalidad para gestión de servicios y seguimiento en tiempo real de proyectos. </td>
    <td> Especialización en el monitoreo y la gestión de sistemas de refrigeración, con enfoque en ahorro energético. </td>
    <td> Precisión en el monitoreo de temperatura y humedad, con alertas automáticas y un enfoque flexible en diferentes industrias. </td>
  </tr>
  <tr>
    <td> Debilidades </td>
    <td> Dependencia de la adopción inicial por parte de los usuarios, lo que podría afectar la expansión. </td>
    <td> Puede ser más complejo de usar para pequeñas empresas sin experiencia en gestión de software. </td>
    <td> Enfoque limitado al sector de refrigeración, lo que puede dificultar la expansión a otros mercados. </td>
    <td> Puede resultar costoso para pequeñas empresas debido a las suscripciones y los costos adicionales por dispositivos. </td>
  </tr>
  <tr>
    <td> Oportunidades </td>
    <td> Expansión en el sector de la gestión de refrigeración, con foco en la eficiencia operativa y la reducción de costos. </td>
    <td> Expansión a nuevos mercados, introducción de nuevos servicios, mejorar la experiencia del usuario. </td>
    <td> Expansión a nuevos mercados, mejora continua de características y funciones, colaboraciones estratégicas con otros servicios. </td>
    <td> Expansión a nuevos mercados, introducción de nuevas características y servicios, colaboraciones estratégicas con marcas de belleza. </td>
  </tr>
  <tr>
    <td> Amenazas </td>
    <td> Competencia de aplicaciones ya establecidas en la gestión de refrigeración y mantenimiento. </td>
    <td> Competencia de otras plataformas de gestión de servicios que ofrecen características similares. </td>
    <td> Alta competencia en el mercado de soluciones para refrigeración y dependencia de la infraestructura de clientes. </td>
    <td> Competencia de otras plataformas de monitoreo de temperatura y humedad, con características similares y precios más bajos. </td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores
Hemos identificado diversas estrategias y tácticas para diferenciarse y competir efectivamente con otros actores del mercado de la gestión y monitoreo de sistemas de refrigeración. A continuación se detallan las principales:

**1. Estrategias de Diferenciación:**
- **Automatización y Mantenimiento Preventivo**: A diferencia de los competidores, **OsitoPolar** se enfoca en ofrecer una solución integral con monitoreo en tiempo real, alertas automáticas y un sistema de mantenimiento preventivo.
- **Trazabilidad Completa de Equipos**: Ofrecemos una plataforma que proporciona un historial técnico detallado de cada equipo, algo que competidores como **ServiceTitan** no ofrecen de forma especializada.
- **Interfaz Intuitiva y Fácil de Usar**: A diferencia de **CoolMaster**, **OsitoPolar** prioriza la simplicidad de uso, lo que facilita la adopción rápida.

**2. Tácticas de Marketing:**
- **Marketing Digital y Demostraciones Gratuitas**: Enfocaremos nuestras campañas en redes sociales, demostraciones en vivo, y colaboraciones con negocios del sector.
- **Fidelización de Usuarios a Largo Plazo**: Implementaremos programas de fidelización y un sistema de recompensas.

**3. Estrategias de Precios:**
- **Modelo Freemium**: Ofrecemos una versión básica gratuita para atraer a pequeños negocios.
- **Comisiones Bajas por Reserva**: Para los negocios, aplicamos comisiones reducidas por cada cita reservada.

**4. Expansión y Adaptabilidad:**
- **Enfoque Regional Inicial y Expansión Nacional**: **OsitoPolar** comenzará en Lima con planes de expansión a otras ciudades del Perú.
- **Colaboraciones con Proveedores Locales**: Formaremos alianzas estratégicas con proveedores locales.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Segmento 1: Negocios que utilizan equipos de refrigeración**
1. ¿Qué edad tiene?
2. ¿De dónde es y a qué se dedica?
3. ¿Qué tipo de negocio tiene y qué productos necesita mantener en frío?
4. ¿Cuántos equipos de refrigeración tiene actualmente?
5. ¿Ha tenido pérdidas por fallas en sus equipos? ¿Qué impacto tuvo?
6. ¿Cómo monitorea hoy el estado (temperatura, consumo, fallas) de esos equipos?
7. ¿Con qué frecuencia realiza mantenimiento y quién se encarga?
8. ¿Utiliza alguna herramienta digital para la gestión de estos equipos?
9. ¿Qué tan útil le parecería recibir alertas automáticas por fallas o variaciones de temperatura?
10. ¿Le interesaría tener un historial técnico y reportes automáticos por cada equipo?
11. ¿Estaría dispuesto a pagar una suscripción si esto evita pérdidas y mejora la eficiencia?
12. ¿Qué funcionalidades sí o sí debería tener una herramienta de este tipo para que usted la use?
13. ¿Preferiría acceder a la herramienta desde su celular o computadora?
14. ¿Qué le haría dejar de usar una aplicación de este tipo?

**Segmento 2: Empresas proveedoras de servicios y equipos de refrigeración**
1. ¿Qué edad tiene?
2. ¿De dónde es?
3. ¿A qué se dedica específicamente y hace cuánto trabaja en el rubro?
4. ¿Cuántos clientes o negocios atiende regularmente?
5. ¿Cómo organiza sus visitas técnicas y mantenimientos?
6. ¿Lleva un historial técnico de los equipos que repara? ¿Cómo lo gestiona?
7. ¿Cuáles son las principales dificultades que enfrenta su empresa al coordinar servicios técnicos?
8. ¿Cómo coordina hoy sus rutas o visitas? ¿Utiliza alguna herramienta o lo hace manualmente?
9. ¿Qué tan útil le sería tener una app donde pueda ver todos los equipos que provee o atiende?
10. ¿Le interesaría recibir alertas sobre fallas en los equipos de sus clientes en el momento en el que suceden?
11. ¿Qué tanto valora poder generar reportes automáticos y mantener trazabilidad de cada intervención?
12. ¿Estaría dispuesto a usar una plataforma que le ayude a organizarse mejor y escalar su servicio?
13. ¿Ha probado alguna solución parecida antes? ¿Por qué la dejó de usar (si la dejó)?
14. ¿Qué beneficios cree que podría tener la implementación de una solución digital como OsitoPolar a su empresa?

### 2.2.2. Registro de entrevistas

## Segmento objetivo #1: Negocios que utilizan equipos de refrigeración

### Entrevista 1:
- **Nombres y apellidos:** Adriana Moloche
- **Edad:** 32
- **Distrito:** San Martín de Porres
- **Dispositivo móvil:** iPhone 11
- **Navegador preferido:** Safari
- **Marcas/influencias:** Tiendas de conveniencia Tambo, refrigeradores Samsung

![Interview-1-segment-1.png]( assets/chapter02/Interview-1-segment-1.png)

- **Inicio:** 0:02
- **Duración:** 3:18 min
- **URL:** [https://bit.ly/4j6lCpZ](https://bit.ly/4j6lCpZ)
- **Resumen:** Adriana es una emprendedora que administra una bodega tipo mini market en San Martín de Porres. Su actividad diaria depende del correcto funcionamiento de sus equipos de refrigeración, ya que conserva productos perecibles como embutidos, bebidas y lácteos. Durante la entrevista, manifestó haber experimentado pérdidas económicas debido a fallas inesperadas en sus congeladoras, y recalcó la ausencia de mecanismos digitales que le ayuden a prevenir esos eventos. Actualmente, revisa la temperatura manualmente y realiza mantenimientos periódicos cada 20 días, lo cual considera una tarea rutinaria pero propensa a errores. Se mostró muy interesada en la idea de contar con una solución tecnológica que le notifique fallas de manera automática, que le brinde un historial técnico detallado y reportes por cada servicio realizado. Además, resaltó la importancia de tener opciones de suscripción accesibles, adaptadas a negocios pequeños como el suyo. Mencionó que estaría dispuesta a pagar por el servicio si se le garantiza una reducción significativa en las pérdidas operativas. Para ella, una herramienta como OsitoPolar representa una alternativa innovadora que podría profesionalizar su gestión sin exigir conocimientos técnicos complejos.

### Entrevista 2:
- **Nombres y apellidos:** Luis Mamani Torres
- **Edad:** 37
- **Distrito:** Comas
- **Dispositivo móvil:** Samsung Galaxy A53
- **Navegador preferido:** Chrome
- **Marcas/influencias:** Locales gastronómicos con alta calificación, Sheraton, equipos de refrigeración industrial LG

![Interview-2-segment-1.jpg]( assets/chapter02/Interview-2-segment-1.jpg)

- **Inicio:** 0:25
- **Duración:** 9:03 min
- **URL:** [https://bit.ly/45c4QlW](https://bit.ly/45c4QlW)
- **Resumen:** Luis es un empresario del rubro gastronómico especializado en cevichería, con experiencia previa como coordinador de cocina en hoteles de prestigio como el Sheraton. Actualmente administra un solo local en el distrito de Comas, donde emplea equipos de refrigeración para conservar insumos altamente sensibles como pescados y mariscos. Recalcó que en su rubro la cadena de frío es esencial, ya que un solo error podría implicar pérdidas económicas y riesgos sanitarios. Aunque reconoce que puede gestionar su negocio manualmente por su tamaño actual, también admite que una herramienta como OsitoPolar sería vital si decidiera expandirse. Indicó que empresas del sector avícola cuentan con sistemas similares, aunque menos sofisticados. En ese sentido, considera que OsitoPolar presenta una propuesta más completa y especializada. Destacó que funcionalidades como alertas automáticas, reportes de consumo y planificación de mantenimiento le permitirían optimizar sus operaciones, especialmente si tuviera varios locales. A pesar de no usar una solución digital actualmente, Luis mostró una actitud muy abierta a la adopción de tecnología si esta garantiza eficiencia y prevención de pérdidas.

##### Segmento objetivo #2: Empresas proveedoras de servicios y equipos de refrigeración

### Entrevista 1:
- **Nombres y apellidos:** Wilder Canchan
- **Edad:** 45
- **Distrito:** Los Olivos
- **Dispositivo móvil:** Xiaomi Redmi Note 10
- **Navegador preferido:** Chrome
- **Marcas/influencias:** Empresas de refrigeración comercial, Coldex, Miray

![Interview-1-segment-2.png]( assets/chapter02/Interview-1-segment-2.png)

- **Inicio:** 0:43
- **Duración:** 7:03 min
- **URL:** [https://bit.ly/4jS816Q](https://bit.ly/4jS816Q)
- **Resumen:** Wilder es técnico especializado en refrigeración y aire acondicionado, con más de 7 años de experiencia atendiendo aproximadamente a 25 clientes al mes. Durante la entrevista, comentó que su principal dificultad radica en la coordinación con los clientes para las visitas técnicas, especialmente por errores en la ubicación o en los horarios acordados. Actualmente, gestiona sus servicios vía telefónica y utiliza Google Maps como apoyo para las rutas. Consideró que una plataforma como OsitoPolar le permitiría centralizar su operación, recibir alertas sobre fallas, y mejorar tanto la planificación de su agenda como la comunicación con los clientes. También destacó la posibilidad de llevar un historial técnico de cada equipo atendido, lo cual le ayudaría a prepararse mejor antes de cada visita. En su opinión, el uso de una app profesional elevaría la imagen de su empresa, mejorando la confianza y fidelización del cliente.

### Entrevista 2:
- **Nombres y apellidos:** Jackeline Bravo
- **Edad:** 36
- **Distrito:** Comas
- **Dispositivo móvil:** iPhone 12
- **Navegador preferido:** Safari
- **Marcas/influencias:** Microsoft Office, empresas con software de gestión integrado, servicios de refrigeración premium

![Interview-2-segment-2.png]( assets/chapter02/Interview-2-segment-2.png)

- **Inicio:** 0:30
- **Duración:** 5:48 min
- **URL:** [https://bit.ly/43iyR14](https://bit.ly/43iyR14)
- **Resumen:** Jackeline tiene 13 años de experiencia en el rubro de servicios y mantenimiento de refrigeración, y se desempeña en el área administrativa de una empresa que atiende tanto a clientes fijos como temporales. Actualmente, gestiona los reportes técnicos con Excel y planifica las rutas a través de cronogramas manuales y aplicaciones móviles como Google Maps. Destacó que una herramienta como OsitoPolar podría marcar una diferencia sustancial en la organización de su equipo, ya que centralizaría toda la información de los equipos atendidos y permitiría la visualización en tiempo real del estado de cada unidad. Subrayó la importancia de poder ingresar datos desde el lugar de trabajo, facilitando el flujo de información y reduciendo errores administrativos. También recalcó el valor de las alertas automáticas, ya que permitirían actuar de forma inmediata ante cualquier incidente. Concluyó que una solución digital como esta no solo optimizaría procesos, sino que elevaría el estándar del servicio ofrecido.

### Entrevista 3:
- **Nombres y apellidos:** Santiago Vique
- **Edad:** 48
- **Distrito:** San Martín de Porres
- **Dispositivo móvil:** Samsung Galaxy S21
- **Navegador preferido:** Firefox
- **Marcas/influencias:** Grupo Backus, Grupo Mambrino, sistemas de refrigeración industrial europeos

![Interview-3-segment-2.png]( assets/chapter02/Interview-3-segment-2.png)

- **Inicio:** 0:11
- **Duración:** 7:09 min
- **URL:** [https://bit.ly/43gc8T9](https://bit.ly/43gc8T9)
- **Resumen:** Santiago es dueño de una empresa de instalación y mantenimiento de sistemas de refrigeración industrial. Cuenta con más de una década de experiencia y trabaja con clientes de gran envergadura como el Grupo Backus y Mambrino. En la entrevista, señaló que una de sus principales dificultades es la falta de información previa sobre las fallas de los equipos al momento de coordinar servicios, lo que repercute en la preparación del personal técnico y en la eficiencia de las visitas. Actualmente emplea archivos PDF y hojas de cálculo, lo cual limita el acceso ágil y compartido de los datos. Opinó que OsitoPolar facilitaría la organización de rutas, mejoraría la trazabilidad del historial técnico de cada unidad, y permitiría preparar los materiales de forma más precisa antes de la atención. También valoró que una app así agilizaría la comunicación con los clientes, lo que podría traducirse en una mejora sustancial en la calidad del servicio. Finalmente, destacó que la digitalización le permitiría optimizar recursos, reducir tiempos de respuesta y aumentar la satisfacción del cliente.

### 2.2.3. Análisis de entrevistas

Basándonos en las entrevistas, hemos llevado a cabo un análisis en el que destacamos los puntos compartidos y tendencias comunes entre los usuarios.

**Hallazgos para el Segmento #1: NEGOCIOS QUE UTILIZAN EQUIPOS DE REFRIGERACIÓN**
- Los entrevistados administran negocios donde la refrigeración es crítica para la calidad de sus productos.
- Monitorean manualmente las temperaturas y el consumo de energía sin utilizar herramientas digitales.
- Han experimentado pérdidas económicas directas debido a fallas en los equipos de refrigeración.
- Muestran interés en recibir alertas por fallas, variaciones de temperatura o consumo energético.

**Insights del Segmento #1**
1. **Necesidad de confianza y prueba previa:** los negocios muestran cautela frente a nuevas soluciones tecnológicas.
2. **Fuerte motivación por prevenir pérdidas:** las pérdidas económicas y de producto son el principal detonante.
3. **Oportunidad de diferenciación:** existe un vacío de herramientas accesibles y simples para pymes.
4. **Valor percibido proporcional al tamaño del negocio:** los negocios más grandes asocian mayor retorno con el monitoreo digital.

**Hallazgos para el Segmento #2: EMPRESAS PROVEEDORAS DE SERVICIOS**
- Algunos tienen más de 10 años de experiencia en el rubro.
- Todos los entrevistados tienen como motivación principal brindar equipos de calidad y mejorar la eficiencia del servicio.
- Todos mencionan que la coordinación de rutas es una dificultad.
- La mayoría de los entrevistados utilizan métodos tradicionales como Excel.

**Insights del Segmento #2**
1. **Necesidad de digitalización inmediata:** los técnicos y proveedores están listos para adoptar una herramienta.
2. **Ineficiencia en la coordinación:** el uso de canales dispersos genera pérdida de tiempo.
3. **Alta disposición a adoptar tecnología:** aunque no utilizan soluciones integrales, reconocen su valor.
4. **Oportunidad de posicionamiento B2B:** la falta total de soluciones específicas en el mercado local.

**Análisis estadístico**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/pie_chart-1-segment-2.png"
       alt="Segmento 2 del Gráfico Circular: Distribución de datos clave."
       style="max-width: 75%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Gráfico Circular - Segmento 2.
  </figcaption>
</figure>

- Más del 50% de los empresarios tiene un número mayor a 10 años de experiencia en el rubro.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/pie_chart-2-segment-2.png"
       alt="Segmento 2 del segundo Gráfico Circular: Proporción de satisfacción del usuario."
       style="max-width: 75%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> Gráfico Circular 2 - Segmento 2.
  </figcaption>
</figure>

- Los empresarios tienen diferentes frecuencias de ciertas dificultades, a pesar de que tienen casi los mismos problemas.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/pie_chart-3-segment-2.png"
       alt="Segmento 2 del tercer Gráfico Circular: Datos demográficos de usuarios."
       style="max-width: 75%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 3:</strong> Gráfico Circular 3 - Segmento 2.
  </figcaption>
</figure>

- El 67% de los empresarios creen que el cliente es parcialmente causante de su problema de mayor frecuencia. Algunos de ellos han expresado su inconformidad respecto a los clientes que no explican bien las fallas de sus equipos.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/pie_chart-4-segment-2.png"
       alt="Segmento 2 del cuarto Gráfico Circular: Preferencias de los usuarios por características."
       style="max-width: 75%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 4:</strong> Gráfico Circular 4 - Segmento 2.
  </figcaption>
</figure>

- El 100% está interesado en recibir notificaciones sobre fallos que ocurren en equipos de refrigeración. Ellos creen que con dicha funcionalidad podrían hacer un mantenimiento preventivo más eficiente y lograr la satisfacción del cliente.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/pie_chart-5-segment-2.png"
       alt="Segmento 2 del quinto Gráfico Circular: Fuentes de información preferidas por los usuarios."
       style="max-width: 75%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 5:</strong> Gráfico Circular 5 - Segmento 2.
  </figcaption>
</figure>

- Ni uno de los empresarios ha usado una plataforma digital que se asemeje a la que se muestran interesados. Ellos usaron aplicaciones para mejorar la eficiencia de su trabajo como WhatsApp y Maps o programas como Microsoft Excel. Sin embargo, estos no poseen todas las funcionalidades que necesitan.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/pie_chart-6-segment-2.png"
       alt="Segmento 2 del sexto Gráfico Circular: Nivel de satisfacción general del producto."
       style="max-width: 75%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 6:</strong> Gráfico Circular 6 - Segmento 2.
  </figcaption>
</figure>

- Cada empresario tiene una meta deseada de mayor prioridad diferente al resto a pesar de que todos ellos comparten los mismos deseos y esperan que una plataforma digital pueda ayudarles a obtenerlos.

## 2.3. Needfinding

### 2.3.1. User Personas
En esta sección se presentan las fichas de User Personas construidas a partir de los datos recogidos del análisis de entrevistas al segmento #1: "Negocios que utilizan equipos de refrigeración" y al segmento #2: "Empresas proveedoras de servicios y equipos de refrigeración". Estas fichas permiten representar de forma clara y estratégica los perfiles del segmento objetivo, considerando sus metas, habilidades, motivaciones y dificultades. Al integrar tanto la perspectiva del usuario como las tendencias del sector, estas representaciones sirven como una herramienta clave para el diseño de soluciones digitales centradas en el usuario y alineadas con las oportunidades del mercado.

##### Segmento objetivo #1: Negocios que utilizan equipos de refrigeración
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/UserPersona-Carolina_Garcia.png" 
       alt="User Persona: Carolina García, descripción detallada del perfil de usuario." 
       style="max-width: 90%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> User Persona - Carolina García.
  </figcaption>
</figure>

##### Segmento objetivo #2: Empresas proveedoras de servicios y equipos de refrigeración
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/UserPersona-Luis-Rojas.png"
       alt="User Persona: Luis Rojas, descripción detallada de sus características y necesidades."
       style="max-width: 90%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> User Persona - Luis Rojas.
  </figcaption>
</figure>

### 2.3.2. User Task Matrix

En esta sección se presenta el User Task Matrix, construido a partir de los User Persona que representan a los dos segmentos clave identificados:

Segmento 1: Negocios que utilizan equipos de refrigeración (representado por Carolina García).

Segmento 2: Empresas proveedoras de servicios y equipos de refrigeración (representado por Luis Rojas).

Las tareas fueron identificadas a partir del análisis cualitativo de entrevistas, y cada una fue evaluada según su frecuencia y nivel de importancia para los respectivos perfiles.



<table>
  <tr>
    <th rowspan="2">Tarea / Task</th>
    <th colspan="2">Carolina García</th>
    <th colspan="2">Luis Rojas</th>
  </tr>
  <tr>
    <th>Frecuencia</th>
    <th>Importancia</th>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
  <tr>
    <td>Detectar o identificar fallas en los equipos</td>
    <td>Baja</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Coordinar servicios de mantenimiento</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Planificar rutas de llegada al punto de atención</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Baja</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Realizar mantenimiento preventivo o solicitarlo</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Gestionar datos de los equipos de refrigeración</td>
    <td>Baja</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Gestionar costos por pérdidas de productos</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Evaluar la calidad de los equipos y servicios brindados</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Monitorear el desempeño de los técnicos</td>
    <td>Baja</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Monitorear el desempeño de los equipos brindados</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Baja</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Usar reportes técnicos para tomar decisiones</td>
    <td>Baja</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Comunicar fallas al técnico o proveedor</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
</table>

### 2.3.3. User Journey Mapping
**Segmento objetivo #1: Negocios que utilizan equipos de refrigeración**

Este User Journey Map representa el recorrido actual de Carolina García. El mapa ilustra su experiencia completa desde que maneja continuamente los datos registrados de la empresa hasta su seguimiento luego de la realización de la venta o servicio.
Esta sección refleja la situación actual sin intervención de soluciones tecnológicas, mostrando los puntos de contacto, tareas clave, emociones y posibles fricciones que enfrenta en su día a día. Este recorrido permite entender los desafíos que enfrenta Carolina.
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/JourneyMap-segment-1.png"
       alt="Segmento 1 del Journey Map: Etapa de Descubrimiento de necesidades del usuario."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Segmento 1 del Journey Map.
  </figcaption>
</figure>

**Segmento objetivo #2: EMPRESAS PROVEEDORAS DE SERVICIOS**

Este User Journey Map representa el recorrido actual de Luis Rojas. El mapa ilustra su experiencia completa desde que maneja continuamente los datos registrados de la empresa hasta su seguimiento luego de la realización de la venta o servicio.
Esta sección refleja la situación actual sin intervención de soluciones tecnológicas, mostrando los puntos de contacto, tareas clave, emociones y posibles fricciones que enfrenta en su día a día. Este recorrido permite entender los desafíos que enfrenta Luis.
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/JourneyMap-segment-2.png"
       alt="Segmento 2 del Journey Map: Etapa de Consideración y Evaluación."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> Segmento 2 del Journey Map.
  </figcaption>
</figure>

### 2.3.4. Empathy Mapping
**Segmento objetivo #1**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/EmpathyMap-segment-1.png"
       alt="Segmento 1 del Mapa de Empatía: Qué piensa y siente el usuario."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Segmento 1 del Mapa de Empatía.
  </figcaption>
</figure>

**Segmento objetivo #2**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/EmpathyMap-segment-2.png"
       alt="Segmento 2 del Mapa de Empatía: Qué ve y qué oye el usuario."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> Segmento 2 del Mapa de Empatía.
  </figcaption>
</figure>

### 2.3.5. Ubiquitous Language
1. **User (Usuario):** Negocios y técnicos del rubro de refrigeración que utilizan OsitoPolar para gestionar equipos de congelación, coordinar mantenimientos y optimizar sus operaciones.
2. **User Profile (Perfil de Usuario):** Datos e información operativa que OsitoPolar recopila de cada usuario para personalizar su experiencia.
3. **Smart Dashboard (Panel Inteligente):** Interfaz central donde los usuarios monitorean el estado de sus equipos, reciben alertas y gestionan sus servicios.
4. **Performance Report (Reporte de Rendimiento):** Informe técnico con historial de uso, consumo energético, temperatura y fallas de cada equipo.
5. **Maintenance Schedule (Agenda de Mantenimientos):** Calendario inteligente para programar mantenimientos preventivos o correctivos.
6. **Failure Alert (Alerta de Falla):** Notificación automática ante anomalías críticas como sobrecalentamiento o cortes de energía.
7. **Equipment Inventory (Inventario de Equipos):** Registro de todos los equipos de congelación con sus datos técnicos y ubicación.
8. **Service Provider (Proveedor de Servicio):** Técnico o empresa que brinda mantenimiento, instalación o reparación de equipos de refrigeración.
9. **Technical History (Historial Técnico):** Registro detallado de todas las intervenciones realizadas a un equipo.
10. **Work Order (Orden de Trabajo):** Documento digital con las tareas asignadas a un técnico para una visita de servicio.
11. **Service Coordination (Coordinación de Servicio):** Proceso de conexión entre clientes y proveedores según disponibilidad, ubicación y necesidad.
12. **Automatic Report Generation (Generación Automática de Reportes):** Función que crea informes técnicos sin intervención manual.
13. **Real-Time Monitoring (Monitoreo en Tiempo Real):** Supervisión constante del estado operativo del equipo (temperatura, consumo, uso).
14. **Service Zone (Zona de Servicio):** Área donde un proveedor puede atender equipos con rapidez y eficiencia.
15. **Client Portfolio (Cartera de Clientes):** Lista de negocios atendidos por un proveedor, con sus datos y equipos registrados.
16. **Cold Equipment (Equipo de Congelación):** Unidad de refrigeración usada para conservar productos, como congeladoras, cámaras o vitrinas.
17. **Energy Consumption (Consumo Energético):** Registro del uso eléctrico de los equipos para detectar anomalías y optimizar recursos.
18. **Preventive Maintenance (Mantenimiento Preventivo):** Servicio planificado para evitar fallas y extender la vida útil del equipo.
19. **Corrective Maintenance (Mantenimiento Correctivo):** Servicio realizado para solucionar una falla existente en un equipo.
20. **Notification (Notificación):** Mensajes enviados automáticamente para informar sobre mantenimientos, fallas o cambios importantes.

## 2.4. Requirements Specification
### 2.4.1. User Stories
Las historias de usuario desarrolladas en este proyecto fueron elaboradas en conjunto por el equipo de desarrollo de OsitoPolar, considerando las necesidades y funcionalidades clave tanto para los clientes (dueños de equipos de refrigeración) como para los empresarios (proveedores de equipos y servicios de mantenimiento y refrigeración). Las historias fueron organizadas bajo épicas que agrupan funcionalidades similares. Los criterios de aceptación de todas las historias siguen la sintaxis Gherkin.
El trabajo fue realizado de manera colaborativa, priorizando la comprensión del problema desde la perspectiva del usuario final. Para facilitar la organización, priorización y trazabilidad de las tareas, se utilizó la plataforma Trello


| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|-----------------|--------|-------------|-------------------------|---------------------------|
| US-01 | Registrar usuario | Como nuevo usuario, quiero registrarme para acceder a la plataforma y empezar a gestionar mis equipos de refrigeración. | **Escenario 1: Registro exitoso** <br/> Dado que el usuario accede al sistema por primera vez, cuando proporciona la información requerida para su registro, entonces el sistema valida los datos ingresados, los guarda de forma segura y permite el acceso al usuario. <br/><br/> **Escenario 2: Correo ya registrado** <br/> Dado que el usuario intenta registrarse con un correo ya existente, cuando envía la solicitud de registro, entonces el sistema verifica la existencia del correo en la base de datos y responde con un mensaje de error indicando que el correo ya está en uso. | EP-01 |
| US-02 | Iniciar sesión | Como usuario registrado, quiero iniciar sesión para acceder a mis funciones personalizadas. | **Escenario 1: Inicio de sesión válido** <br/> Dado que el usuario ya está registrado, cuando ingresa sus credenciales correctas, entonces el sistema autentica su identidad y permite el acceso a su cuenta. <br/><br/> **Escenario 2: Credenciales inválidas** <br/> Dado que el usuario ingresa credenciales incorrectas, cuando intenta acceder, entonces el sistema muestra un mensaje indicando error en usuario o contraseña. | EP-01 |
| US-35 | Ver barra de navegación dinámica | Como usuario, quiero que la barra de navegación muestre opciones según mi perfil, para acceder fácilmente a las funciones relevantes. | **Escenario 1: Personalización por rol** <br/> Dado que el usuario inicia sesión, cuando el sistema identifica su rol, entonces la barra de navegación muestra únicamente las opciones correspondientes a dicho perfil. | EP-01 |
| US-06 | Agregar equipos | Como técnico, quiero registrar nuevos equipos en el sistema para mantener actualizado el inventario. | **Escenario 1: Registro exitoso** <br/> Dado que el técnico accede al módulo de equipos, cuando ingresa la información requerida del nuevo dispositivo, entonces el sistema valida y guarda los datos en la base de registros. | EP-02 |
| US-31 | Controlar encendido y apagado del equipo | Como usuario, quiero encender o apagar mis equipos desde la aplicación para gestionar su funcionamiento remotamente. | **Escenario 1: Encendido o apagado remoto** <br/> Dado que el usuario selecciona un equipo, cuando solicita encenderlo o apagarlo, entonces el sistema envía la orden y actualiza su estado. | EP-02 |
| US-32 | Ajustar temperatura del equipo | Como usuario, quiero ajustar la temperatura de mis equipos para mantener condiciones óptimas. | **Escenario 1: Ajuste de temperatura** <br/> Dado que el usuario accede a la configuración del equipo, cuando define un nuevo valor de temperatura, entonces el sistema actualiza el parámetro y lo guarda correctamente. | EP-02 |
| US-17 | Visualizar equipos entregados | Como usuario, quiero visualizar los equipos entregados para monitorear su uso y mantenimiento. | **Escenario 1: Consulta de equipos entregados** <br/> Dado que el usuario accede al módulo de equipos, cuando solicita ver el listado de equipos entregados, entonces el sistema muestra la información registrada con su estado actual. | EP-02 |
| US-03 | Solicitar servicio de reparación | Como cliente, quiero solicitar un servicio de reparación para resolver fallas en mis equipos. | **Escenario 1: Solicitud registrada** <br/> Dado que el cliente detecta una falla en su equipo, cuando envía una solicitud de reparación, entonces el sistema registra la información y la asigna a un técnico disponible. | EP-03 |
| US-08 | Solicitar mantenimiento preventivo | Como cliente, quiero solicitar mantenimiento preventivo para evitar fallas futuras. | **Escenario 1: Programación de mantenimiento** <br/> Dado que el cliente desea realizar mantenimiento, cuando envía la solicitud, entonces el sistema la registra y agenda según disponibilidad. | EP-03 |
| US-04 | Ver estado del servicio | Como cliente, quiero ver el estado de mis solicitudes para hacer seguimiento a su progreso. | **Escenario 1: Consulta de estado** <br/> Dado que el cliente tiene solicitudes activas, cuando revisa el detalle de una solicitud, entonces el sistema muestra su estado actual y fecha estimada de finalización. | EP-03 |
| US-11 | Asignar técnico | Como administrador, quiero asignar técnicos a las solicitudes para asegurar atención oportuna. | **Escenario 1: Asignación de técnico** <br/> Dado que existe una solicitud pendiente, cuando el administrador asigna un técnico disponible, entonces el sistema actualiza el registro y notifica a ambos. | EP-03 |
| US-13 | Hacer seguimiento de solicitudes | Como técnico, quiero actualizar el estado de las solicitudes asignadas para mantener la trazabilidad del servicio. | **Escenario 1: Actualización de estado** <br/> Dado que el técnico atiende una solicitud, cuando cambia su estado (en proceso, finalizado, cancelado), entonces el sistema actualiza la información y notifica al cliente. | EP-03 |
| US-05 | Ver reporte de servicio realizado | Como cliente, quiero visualizar el reporte de los servicios realizados para tener evidencia del trabajo. | **Escenario 1: Consulta de reporte** <br/> Dado que el cliente tiene servicios finalizados, cuando solicita el reporte, entonces el sistema muestra los detalles del trabajo realizado. | EP-04 |
| US-09 | Ver consumo energético | Como usuario, quiero visualizar el consumo energético de mis equipos para optimizar su uso. | **Escenario 1: Visualización de consumo** <br/> Dado que el usuario accede al módulo de consumo, cuando selecciona un equipo, entonces el sistema muestra el consumo histórico y actual del dispositivo. | EP-04 |
| US-12 | Ver historial de servicios | Como usuario, quiero ver el historial de servicios realizados a mis equipos para controlar su mantenimiento. | **Escenario 1: Historial de servicios** <br/> Dado que el usuario tiene servicios anteriores, cuando consulta el historial de servicios, entonces el sistema presenta la lista de servicios previos, con la fecha, el técnico y el tipo de servicio realizado. | EP-04 |
| US-07 | Recibir alerta de falla | Como usuario, quiero recibir alertas cuando ocurra una falla en mis equipos. | **Escenario 1: Alerta generada** <br/> Dado que el sistema detecta una falla en uno de los equipos, cuando se cumple una condición anómala, entonces el sistema genera una alerta, la registra y la envía al usuario correspondiente. | EP-05 |
| US-10 | Ver alertas automáticas para empresarios | Como empresario, quiero recibir alertas automáticas de mis equipos para actuar rápidamente ante fallas. | **Escenario 1: Generación automática de alerta** <br/> Dado que el sistema monitorea los equipos de los empresarios, cuando detecta una condición crítica, entonces el sistema genera automáticamente una alerta y la envía al empresario. | EP-05 |
| US-18 | Recibir notificaciones de eventos importantes | Como usuario, quiero recibir notificaciones sobre eventos importantes del sistema. | **Escenario 1: Envío de notificación** <br/> Dado que ocurre un evento relevante, cuando se cumple una condición definida, entonces el sistema genera y envía la notificación correspondiente. | EP-05 |
| US-19 | Evaluar servicio recibido | Como cliente, quiero evaluar la calidad del servicio recibido para expresar mi nivel de satisfacción. | **Escenario 1: Evaluación exitosa** <br/> Dado que el cliente ha recibido un servicio, cuando envía una evaluación de satisfacción, entonces el sistema registra la calificación, la asocia con el servicio y actualiza los indicadores de satisfacción. | EP-06 |
| US-23 | Ver información de la empresa | Como visitante, quiero visualizar información sobre la empresa para conocer sus servicios y valores. | **Escenario 1: Consulta de información institucional** <br/> Dado que el visitante accede al sistema, cuando solicita información sobre la empresa, entonces el sistema recupera los datos almacenados de la empresa y los presenta como resultado de la consulta. | EP-07 |
| US-24 | Consultar servicios ofrecidos | Como visitante, quiero ver los servicios que ofrece la empresa para evaluar si cubren mis necesidades. | **Escenario 1: Visualización de servicios** <br/> Dado que el visitante desea conocer los servicios ofrecidos, cuando realiza la consulta de los servicios disponibles, entonces el sistema consulta la base de datos y devuelve el catálogo actualizado con las descripciones de cada servicio. | EP-07 |
| US-25 | Contactar a la empresa | Como visitante, quiero enviar un mensaje a la empresa para solicitar más información. | **Escenario 1: Envío de mensaje de contacto** <br/> Dado que el visitante desea comunicarse con la empresa, cuando envía una solicitud de contacto, entonces el sistema almacena la información de la solicitud y notifica al área correspondiente. | EP-07 |
| US-26 | Visualizar testimonios de clientes | Como visitante, quiero ver testimonios de otros clientes para confiar en el servicio. | **Escenario 1: Consulta de testimonios** <br/> Dado que el visitante accede a la sección de testimonios, cuando se carga la página, entonces el sistema muestra comentarios validados de clientes reales. | EP-07 |
| US-27 | Solicitar demostración del producto | Como visitante, quiero solicitar una demostración del producto para evaluar su funcionamiento antes de adquirirlo. | **Escenario 1: Solicitud de demo** <br/> Dado que el visitante desea una demostración del producto, cuando envía una solicitud de demostración, entonces el sistema registra la información en la base de datos y genera una confirmación automática enviada al correo registrado. | EP-07 |

#### 2.4.1.1. Spike Story
**Spike Story ID:** SS-01

**Como** equipo de desarrollo (web, móvil y backend),  
**Quiero** investigar y prototipar las tecnologías móviles más adecuadas para la plataforma OsitoPolar (Kotlin para Android, Flutter con Dart y/o Kotlin Multiplatform),  
**Para que** podamos complementar los conocimientos adquiridos en el curso con investigación práctica y seleccionar el enfoque más viable para el desarrollo móvil.

---

### Criterios de Aceptación (en formato Given-When-Then)

1. **Revisa la documentación oficial de las tecnologías móviles**
  - Dado que el equipo no domina completamente las tecnologías móviles,
  - Cuando el desarrollador revisa la documentación de Kotlin Android, Flutter y Kotlin Multiplatform (KMP),
  - Entonces el desarrollador identifica y documenta sus características principales, fortalezas y limitaciones en un informe compartido.

2. **Evalúa la Compatibilidad con la Plataforma Web/Backend**
  - Dado que OsitoPolar ya cuenta con frontend en Vue y backend en .NET ASP,
  - Cuando el desarrollador evalúa la integración móvil con APIs RESTful y WebSockets,
  - Entonces el informe detalla los requisitos de interoperabilidad y cómo cada tecnología móvil facilita la comunicación con el backend existente.

3. **Analiza la Curva de Aprendizaje y Conocimientos del Equipo**
  - Dado que el equipo tiene conocimientos base del curso y experiencia previa limitada en móviles,
  - Cuando se contrastan los contenidos del curso con los requerimientos de cada framework,
  - Entonces el informe documenta qué tecnologías son más rápidas de adoptar y qué brechas de conocimiento deberán cubrirse.

4. **Evalúa la Experiencia de Usuario y Capacidades de UI**
  - Dado que la aplicación debe ofrecer una experiencia fluida a empresas y técnicos,
  - Cuando el desarrollador analiza las capacidades de Flutter (UI multiplataforma), Kotlin Android (UI nativa) y KMP (UI específica por plataforma),
  - Entonces el informe documenta ventajas y limitaciones en diseño de interfaces, usabilidad y consistencia visual.

5. **Identifica Implicaciones de Seguridad**
  - Dado que OsitoPolar manejará datos sensibles (monitoreo IoT, fallas de equipos, datos de clientes),
  - Cuando se investigan las prácticas de seguridad soportadas por cada tecnología (almacenamiento seguro, comunicación cifrada, autenticación con backend),
  - Entonces el informe incluye un resumen de riesgos y medidas recomendadas.

6. **Evalúa el Impacto en el Rendimiento**
  - Dado que la app debe procesar datos de IoT en tiempo real,
  - Cuando el desarrollador investiga benchmarks de rendimiento (uso de memoria, consumo de batería, latencia de red),
  - Entonces el informe documenta hallazgos y potenciales cuellos de botella en cada tecnología.

7. **Verifica Costos y Recursos**
  - Dado que se busca optimizar costos de desarrollo y mantenimiento,
  - Cuando el desarrollador analiza dependencias externas, soporte en la comunidad, compatibilidad con librerías y esfuerzo de mantenimiento,
  - Entonces el informe detalla costos asociados (tiempo de desarrollo, curva de aprendizaje, soporte a largo plazo).

8. **Prototipa un Flujo Mínimo**
  - Dado que se necesita validar la viabilidad práctica,
  - Cuando el desarrollador construye un proof-of-concept mínimo (ej. pantalla de login y consumo de un endpoint IoT desde el backend),
  - Entonces el PoC queda registrado en una rama del repositorio y documentado en el informe.

9. **Estima el Esfuerzo de Implementación**
  - Dado que el equipo necesita planificar futuros sprints,
  - Cuando el desarrollador desglosa la implementación móvil en tareas (pantallas principales, consumo de APIs, integración IoT, seguridad),
  - Entonces se presenta una estimación aproximada de puntos de historia para cada alternativa tecnológica.

10. **Documenta y Comparte los Hallazgos**
- Dado que el Spike está completo,
- Cuando el desarrollador compila todos los hallazgos en un informe,
- Entonces el documento incluye pros/contras, recomendación inicial y próximos pasos, y se revisa en una sesión de equipo.

---

### Definition of Done (DoD)
- El PoC mínimo estará registrado en una rama del repositorio.
- Los hallazgos se utilizan para crear o refinar historias de implementación en el backlog.
- El Spike está limitado a 8–16 horas y se completa dentro del sprint.

**Spike Story ID: SS-02**

**Como** equipo de desarrollo (backend, frontend y móvil),
**Quiero** investigar y prototipar la integración de Stripe para la gestión de planes de suscripción y pagos,
**Para** que podamos garantizar un flujo de pago seguro, escalable y conforme con PCI-DSS dentro de OsitoPolar.

**Criterios de Aceptación (Given-When-Then)**

Revisa la Documentación de Stripe
- Dado que el equipo no domina completamente Stripe,
- Cuando el desarrollador revisa Stripe Checkout, PaymentIntents y Webhooks,
- Entonces documenta las opciones disponibles y selecciona el flujo más adecuado para suscripciones recurrentes.

Evalúa la Integración con Backend .NET 8
- Dado que OsitoPolar usa ASP.NET Core con EF Core,
- Cuando se analice la librería Stripe.net,
- Entonces el informe detalla los pasos de configuración y compatibilidad con el modelo de pagos.

Analiza la Seguridad y Cumplimiento
- Dado que los pagos manejan datos sensibles,
- Cuando se evalúe el uso de tokens,
- Entonces se documentan riesgos y medidas de mitigación.

Evalúa el Impacto en la Experiencia del Usuario
- Dado que la app debe ofrecer una experiencia fluida,
- Cuando se investigue la experiencia de usuario en web y móvil con Stripe Checkout vs. UI personalizada,
- Entonces se documentan ventajas y desventajas de cada enfoque.

Prototipa un Flujo Mínimo de Pago
- Dado que se necesita validar la viabilidad,
- Cuando se construye un PoC con creación de sesión de pago y confirmación vía webhook,
- Entonces queda registrado en el repositorio y documentado en el informe.

Estima Esfuerzo y Costos
- Dado que la implementación requiere planificación,
- Cuando se desglosen tareas (backend, frontend, móvil),
- Entonces se presenta una estimación en puntos de historia y costos de uso de Stripe.

Documenta y Comparte Hallazgos
- Dado que el Spike está completo,
- Cuando se compila el informe,
- Entonces se incluyen pros/contras, la recomendación inicial y los siguientes pasos.



**Spike Story ID: SS-03**
**Como** equipo de desarrollo,
**Quiero** investigar y prototipar un sistema de notificaciones en tiempo real para OsitoPolar,
**Para** que los usuarios reciban alertas inmediatas de fallas, mantenimientos y pagos confirmados.

Criterios de Aceptación (Given-When-Then)
- Revisa Tecnologías Disponibles
- Dado que el backend es .NET 8,
- Cuando se investigue SignalR, WebSockets y colas de mensajería,
- Entonces se documentan ventajas y limitaciones de cada enfoque.

Evalúa Integración con Frontend y Móvil
- Dado que existen clientes web y móviles,
- Cuando se analicen librerías de integración (ej. SignalR Client para Flutter),
- Entonces se documentan requisitos de interoperabilidad.

Analiza Persistencia de Notificaciones
- Dado que los usuarios necesitan historial,
- Cuando se diseñe el flujo de datos,
- Entonces se incluye persistencia en la base de datos.

Evalúa Impacto en Rendimiento
- Dado que se esperan múltiples notificaciones simultáneas,
- Cuando se realicen pruebas de carga,
- Entonces se documentan cuellos de botella potenciales.

Prototipa un Flujo Mínimo
- Dado que se debe validar,
- Cuando se implemente un PoC con envío de una notificación en tiempo real,
- Entonces queda registrado y documentado.

Documenta y Comparte Hallazgos
- Dado que el Spike está completo,
- Cuando se compile el informe,
- Entonces se presentan pros/contras y la recomendación inicial.

**Spike Story ID: SS-04**
**Como** equipo de desarrollo (web, móvil y backend),
**Quiero** investigar y prototipar el uso de Jetpack Compose para desarrollar la pantalla de catálogo de equipos en la versión móvil de OsitoPolar,
**Para** que podamos evaluar su facilidad de uso, rendimiento y compatibilidad con las funcionalidades actuales, seleccionando un enfoque viable para el desarrollo móvil.

Criterios de Aceptación (Given-When-Then)
Escenario 1
- Dado que tenemos acceso a la documentación oficial de Jetpack Compose y Android SDK,
- Cuando investiguemos las características principales de Jetpack Compose (como composición declarativa, animaciones y LiveData integration),
- Entonces deberíamos documentar al menos 3 ventajas y 3 desafíos específicos para su implementación en el catálogo de equipos.

<br>Escenario 2
- Dado que configuramos un entorno de desarrollo con Android Studio y Jetpack Compose,
- Cuando creemos un prototipo básico que muestre una lista de equipos con tarjetas (cards) y un botón "Request",
- Entonces el prototipo debe compilar y ejecutarse en un emulador Android sin errores críticos, mostrando al menos 3 equipos del catálogo actual.

<br>Escenario 3
- Dado que probamos el prototipo en el emulador,
- Cuando evaluemos el rendimiento (tiempo de carga de la lista y respuesta al botón "Request"),
- Entonces deberíamos registrar métricas de rendimiento (e.g., tiempo de carga < 2 segundos) y compararlos con los requisitos de usabilidad de OsitoPolar.

<br>Escenario 4
- Dado que evaluamos la experiencia de desarrollo con Jetpack Compose,
- Cuando finalicemos la investigación,
- Entonces deberíamos presentar un informe con una recomendación sobre su viabilidad para el catálogo, justificando con pros, contras y estimaciones de esfuerzo para la implementación completa.

**Spike Story ID: SS-05**
**Como** equipo de desarrollo (web, móvil y backend),
**Quiero** investigar y prototipar el uso de Jetpack Compose para implementar la pantalla de autenticación (login y registro) en la versión móvil de OsitoPolar,
**Para** que podamos evaluar su seguridad, usabilidad y compatibilidad con el backend existente, seleccionando un enfoque viable para el desarrollo móvil.

Criterios de Aceptación (Given-When-Then)
<br>Escenario 1
- Dado que tenemos acceso a la documentación de Jetpack Compose y las bibliotecas de autenticación de Android,
- Cuando investiguemos las capacidades de Jetpack Compose para formularios de login/registro (como encriptación básica y manejo de estado),
- Entonces deberíamos documentar al menos 3 ventajas y 3 desafíos específicos para su uso en la autenticación.

<br>Escenario 2
- Dado que configuramos un entorno de desarrollo con Android Studio y Jetpack Compose,
- Cuando creemos un prototipo que incluya pantallas de login (email y contraseña) y registro (email, contraseña, nombre),
- Entonces el prototipo debe compilar y ejecutarse en un emulador Android sin errores críticos, mostrando ambas pantallas con campos funcionales.

<br>Escenario 3
- Dado que probamos el prototipo en el emulador,
- Cuando ingresemos credenciales válidas (e.g., email "user@example.com", contraseña "password123") y válidas,
- Entonces deberíamos confirmar que el login/registro simulado se completa y muestra un mensaje de éxito en menos de 1 segundo.

<br> Escenario 4
- Dado que evaluamos la experiencia de usuario y desarrollo con Jetpack Compose para autenticación,
- Cuando finalicemos la investigación,
- Entonces deberíamos presentar un informe con una recomendación sobre su viabilidad para la autenticación, justificando con pros, contras y estimaciones de esfuerzo para la implementación completa.




### 2.4.2. Impact Mapping

El siguiente Impact Mapping fue desarrollado en UXPressia de manera colaborativa por el equipo de OsitoPolar para alinear los objetivos de negocio con los requerimientos funcionales de la plataforma.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/Impact-Mapping.png"
       alt="Diagrama de Impact Mapping: Objetivo, actores, impactos y entregables clave."
       style="max-width: 80%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Impact Mapping.
  </figcaption>
</figure>

### 2.4.3. Product Backlog

A continuación, presentaremos el Product Backlog, el cual contiene todas las funcionalidades y características necesarias para el desarrollo de la plataforma. Este listado incluye tanto las historias de usuario como las tareas técnicas que facilitarán el progreso del proyecto. Para priorizar las tareas, se ha utilizado la escala Fibonacci (1, 2, 3, 5, 8, 13, 21), la cual ayuda a estimar el esfuerzo relativo requerido para completar cada tarea. Además, hemos asignado cada item a un sprint, de acuerdo con su relevancia y dependencias.

Escala de Story Points (Fibonacci):

1: Tareas pequeñas que se pueden completar rápidamente.

2: Tareas de tamaño moderado.

3: Tareas que requieren más tiempo y esfuerzo.

5: Tareas complejas o con dependencia de otras tareas.

8: Tareas muy complejas o que afectan a múltiples áreas.


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/Product-Backlog.png"
       alt="Diagrama de Product Backlog: Lista priorizada de funcionalidades y requisitos del producto."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Product Backlog.
  </figcaption>
</figure>

| # Orden | User Story ID | Título                                         | Story Points (1 / 2 / 3 / 5 / 8) |
|----------|---------------|------------------------------------------------|----------------------------------|
| 1  | US-01 | Visualizar propuesta de valor principal en la Landing Page | 3 |
| 2  | US-02 | Explorar soluciones específicas del rubro                  | 5 |
| 3  | US-03 | Solicitar una demostración fácilmente                      | 5 |
| 4  | US-04 | Conocer misión y visión de OsitoPolar                      | 2 |
| 5  | US-05 | Contactar con el equipo de ventas                          | 3 |
| 6  | US-06 | Descargar la aplicación móvil desde la web                 | 5 |
| 7  | US-07 | Acceder fácilmente al inicio de sesión desde la web        | 3 |
| 8  | US-08 | Registrarse en la plataforma                               | 5 |
| 9  | US-09 | Iniciar sesión en la plataforma                            | 3 |
| 10 | US-10 | Agregar equipos de refrigeración                           | 5 |
| 11 | US-11 | Solicitar servicio de reparación                           | 5 |
| 12 | US-12 | Solicitar mantenimiento preventivo                         | 5 |
| 13 | US-13 | Visualizar estado de servicio                              | 3 |
| 14 | US-14 | Visualizar reporte de servicio realizado                   | 3 |
| 15 | US-15 | Recibir alertas automáticas por fallas                     | 8 |
| 16 | US-16 | Visualizar consumo energético de los equipos               | 5 |
| 17 | US-17 | Recibir notificaciones sobre eventos importantes           | 8 |
| 18 | US-18 | Evaluar servicio recibido                                  | 3 |
| 19 | US-19 | Registrar técnicos                                         | 5 |
| 20 | US-20 | Asignar técnico a solicitud de servicio                    | 5 |
| 21 | US-21 | Configurar alertas de mantenimiento preventivo             | 8 |
| 22 | US-22 | Visualizar clientes y servicios asociados                  | 5 |
| 23 | US-23 | Realizar seguimiento a servicios y técnicos                | 8 |
| 24 | US-24 | Generar reportes de desempeño de técnicos                  | 5 |
| 25 | US-25 | Visualizar equipos entregados a clientes                   | 5 |
| 26 | US-26 | Visualizar perfil de los técnicos                          | 5 |
| 27 | US-27 | Recibir alertas de solicitudes de servicio de clientes     | 8 |
| 28 | US-28 | Registrar nuevo equipo mediante API                        | 5 |
| 29 | US-29 | Crear solicitud de mantenimiento mediante API              | 5 |
| 30 | US-30 | Registrar intervención técnica mediante API                | 5 |
| 31 | US-31 | Eliminar técnico asignado mediante API                     | 5 |
| 32 | US-32 | Registrar alerta manual mediante API                       | 3 |
| 33 | US-33 | Implementar notificaciones automáticas mediante API        | 8 |
| 34 | US-34 | Registrar evaluación de servicio vía endpoint REST         | 8 |

## 2.5. Strategic-Level Domain-Driven Design

### 2.5.1. EventStorming
Con el objetivo de realizar un modelado colaborativo y estratégico del dominio de OsitoPolar, se llevó a cabo una sesión de EventStorming, una técnica visual centrada en eventos del dominio que permite identificar flujos de negocio, entidades relevantes, actores y límites naturales del sistema.
Objetivo: Comprender cómo los usuarios (dueños de negocios y técnicos) interactúan con la plataforma, desde una perspectiva orientada a eventos.

Herramientas utilizadas:

- Herramienta visual: Miro
- Plataforma de reunión: Discord
- Duración: 1 hora
- Participantes: 5 miembros del equipo

Actividades realizadas:

Identificación de eventos de dominio
Ejemplos: Usuario registra un equipo de refrigeración, Sistema detecta alerta de temperatura, Técnico recibe notificación de mantenimiento, Usuario confirma visita, Sistema genera historial técnico.

Agrupación de eventos por flujo de valor
Se estructuraron flujos ideales (happy paths), como la programación exitosa de un mantenimiento, y flujos de error (unhappy paths), como alertas no atendidas a tiempo.

Identificación de puntos críticos (Pivotal Points):
- La detección automática de fallas en equipos.
- La asignación de técnicos disponibles.
- La confirmación de visitas por parte de los clientes.

Detección de puntos de dolor (Pain Points):
- Fallas no detectadas a tiempo.
- Pérdida de historial técnico.
- Mala coordinación entre clientes y técnicos.

Asignación de comandos y actores:
- Registrar Equipo (Usuario)
- Generar Alerta (Sistema)
- Asignar Técnico (Administrador del servicio)
- Confirmar Mantenimiento (Técnico/Usuario)

Políticas del sistema:
- Validación de roles y permisos.
- Restricciones comerciales (técnico asignado solo dentro de su zona).
- Autenticación segura de usuarios.

Modelos de lectura (Read Models):
- Dashboard con estado de equipos en tiempo real.
- Historial técnico por equipo.
- Reportes de incidencias y mantenimientos.

Sistemas externos:
- Integración con sensores IoT para monitoreo en tiempo real.
- Pasarela de pagos (para suscripciones premium).
- Servicios de mensajería para notificaciones (email/SMS).

Identificación de Aggregates:
- EquipoRefrigeracion (agregado raíz que encapsula historial, alertas y mantenimientos).
- Usuario (propietario, técnico o proveedor).

Mantenimiento (con asignación, estado y resultados).

<img width="1734" height="525" alt="image" src="https://github.com/user-attachments/assets/f3937874-d931-48db-b5a1-192ddef51340" />

#### 2.5.1.1. Candidate Context Discovery
Durante esta etapa se aplicó la técnica Start With Value, con el objetivo de identificar primero el valor principal que la aplicación debe ofrecer: evitar pérdidas económicas y mejorar la eficiencia de los mantenimientos de equipos de refrigeración.

Candidate Bounded Contexts Identificados
| Bounded Context | Descripción breve | Tipo |
|-----------------|-------------------|------|
| **Gestion de equipos** | Registro, monitoreo y alertas en tiempo real de equipos de refrigeración. | Core |
| **Gestión de Mantenimientos** | Programación, asignación y ejecución de mantenimientos preventivos/correctivos. | Core |
| **Gestión de Usuarios** | Autenticación, perfiles de dueños, técnicos y proveedores. | Supporting |
| **Pagos y Suscripciones** | Planes premium, historial de facturación, renovación automática. | Supporting |
| **Reportes y Dashboard** | Generación de métricas, exportación de reportes y visualización de indicadores. | Generic |
| **Notificaciones** | Envío de alertas y recordatorios vía correo, SMS o push. | Generic |

   ##### 2.5.1.2. Domain Message Flows Modeling
 Para visualizar la colaboración entre los contextos, se utilizó Domain Storytelling.

Caso 1: Registro y Monitoreo de un Equipo:
- El usuario registra un nuevo equipo de refrigeración.
- El contexto de Gestión de Equipos guarda los datos.
- El sistema conecta con sensores IoT y comienza el monitoreo.
- Si se detecta una falla, se dispara un evento al contexto de Gestión de Mantenimientos.
- El sistema asigna un técnico disponible y envía una notificación al usuario.

Bounded Contexts involucrados:
- Gestión de Equipos
- Gestión de Mantenimientos
- Notificaciones

<img width="303" height="1536" alt="Image 18 sept 2025, 10_53_31 p m" src="https://github.com/user-attachments/assets/54b42e86-190d-4225-87f5-f22728a0cbf6" />

Caso 2: Programación de un Mantenimiento
- El sistema detecta que un equipo requiere mantenimiento preventivo.
- El contexto de Gestión de Mantenimientos genera una orden.
- El usuario confirma la programación.
- El técnico asignado recibe la orden y registra el resultado.
- Se actualiza el historial en el contexto de Gestión de Equipos.

Bounded Contexts involucrados:
- Gestión de Mantenimientos
- Gestión de Usuarios
- Gestión de Equipos

<img width="330" height="1536" alt="Image 18 sept 2025, 10_53_49 p m png2" src="https://github.com/user-attachments/assets/247f78b4-a54d-4679-be9c-b130928a1a04" />

##### 2.5.1.3. Bounded Context Canvases

En esta sección se presentan los diseños de los *Candidate Bounded Contexts* identificados para **OsitoPolar**, modelados con el formato del *Bounded Context Canvas*.

---

### **Bounded Context 1: My Equipment**

**Context Overview:** Gestiona la administración central de los equipos de refrigeración registrados por los usuarios, permitiendo su monitoreo en tiempo real y la vinculación con servicios relacionados.

**Business Rules:**
- Cada *Cold Equipment* debe estar vinculado a un *User*.
- No se puede eliminar un equipo con solicitudes o mantenimientos abiertos.

**Ubiquitous Language:** User, Cold Equipment, Smart Dashboard, Equipment Inventory, Real-Time Monitoring.

**Capability Analysis:**
- Registrar, editar y eliminar equipos.
- Mostrar equipos asociados al usuario.
- Generar datos de estado para otros contextos.

**Capability Layering:**
- **Application:** APIs para gestión y consulta de equipos.  
- **Domain:** validaciones de inventario y reglas de asociación.  
- **Infrastructure:** persistencia y conexión con IoT.

**Dependencies Capture:** Depende de *View Equipment* (para visualización avanzada), *Work Orders* (para mantenimientos) y *Notifications* (para alertas).

**Design Critique:** Es un contexto *Core*, base del dominio. Requiere robustez en manejo de datos en tiempo real.

---

### **Bounded Context 2: Service Requests**

**Context Overview:** Coordina las solicitudes de servicio generadas por los usuarios, que pueden derivar en órdenes de trabajo o mantenimientos programados.

**Business Rules:**
- Una *Service Request* debe estar ligada a un *User* y un *Equipment*.
- Solo usuarios autenticados pueden crear solicitudes.

**Ubiquitous Language:** Service Coordination, Request, User Profile, Client Portfolio.

**Capability Analysis:**
- Crear solicitudes de servicio.  
- Consultar estado de las solicitudes.  
- Cancelar o modificar solicitudes abiertas.

**Capability Layering:**
- **Application:** APIs de registro y consulta de solicitudes.  
- **Domain:** reglas de validación y flujo de aprobación.  
- **Infrastructure:** persistencia y coordinación con órdenes.

**Dependencies Capture:** Depende de *My Equipment* (datos de equipos) y de *Work Orders* (para convertir solicitudes en órdenes).

**Design Critique:** Es un contexto *Supporting*, facilita la coordinación y canaliza las necesidades de los usuarios.

---

### **Bounded Context 3: Work Orders**

**Context Overview:** Administra el ciclo de vida de los mantenimientos preventivos y correctivos, desde su creación hasta el cierre.

**Business Rules:**
- Una *Work Order* debe asignarse a un *Service Provider*.  
- No se puede cerrar una orden sin registrar un resultado técnico.

**Ubiquitous Language:** Work Order, Preventive Maintenance, Corrective Maintenance, Service Provider, Technical History, Maintenance Schedule.

**Capability Analysis:**
- Crear, asignar y gestionar órdenes de trabajo.  
- Actualizar y cerrar órdenes.  
- Consultar historial de órdenes completadas.

**Capability Layering:**
- **Application:** APIs de gestión de órdenes.  
- **Domain:** reglas de ciclo de vida.  
- **Infrastructure:** persistencia y coordinación con técnicos.

**Dependencies Capture:** Depende de *Service Requests* (para solicitudes aprobadas), *My Equipment* (para equipos vinculados) y *Notifications* (avisos de cambios).

**Design Critique:** Es un *Core Context*, indispensable para la continuidad del servicio.

---

### **Bounded Context 4: View Maintenance**

**Context Overview:** Proporciona a los usuarios una interfaz para consultar mantenimientos realizados y programados.

**Business Rules:**
- Solo usuarios autorizados pueden acceder al historial de un equipo.  
- El historial debe incluir *Technical History* y resultados de órdenes.

**Ubiquitous Language:** Maintenance Schedule, Technical History, Report.

**Capability Analysis:**
- Consultar mantenimientos preventivos y correctivos.  
- Generar reportes automáticos de historial.

**Capability Layering:**
- **Application:** APIs y vistas para consulta.  
- **Domain:** reglas de acceso y filtrado.  
- **Infrastructure:** integración con repositorio histórico.

**Dependencies Capture:** Depende de *Work Orders* (resultados y estado) y *My Equipment* (asociación de equipos).

**Design Critique:** Es un contexto *Supporting*, orientado a consulta e informes.

---

### **Bounded Context 5: Notifications**

**Context Overview:** Gestiona la emisión de alertas y recordatorios, garantizando que los usuarios estén informados de fallas, mantenimientos y cambios en el sistema.

**Business Rules:**
- Una *Failure Alert* debe enviarse en tiempo real.  
- Cada *Notification* debe registrarse en un historial.

**Ubiquitous Language:** Notification, Failure Alert, Automatic Report Generation, Service Zone.

**Capability Analysis:**
- Generar y enviar notificaciones.  
- Configurar preferencias de usuario.  
- Consultar historial de notificaciones.

**Capability Layering:**
- **Application:** APIs de envío y gestión de notificaciones.  
- **Domain:** reglas de disparo y personalización.  
- **Infrastructure:** integración con mensajería externa.

**Dependencies Capture:** Depende de *My Equipment* (eventos de equipos) y *Work Orders* (avisos de mantenimientos).

**Design Critique:** Es un contexto *Supporting*, vital para la experiencia de usuario y escalabilidad.

---

### **Bounded Context 6: View Equipment**

**Context Overview:** Facilita la visualización del inventario de equipos y sus características técnicas para usuarios y proveedores.

**Business Rules:**
- Solo se muestran equipos activos en el inventario.  
- Los datos técnicos deben estar completos para ser visibles.

**Ubiquitous Language:** Equipment Inventory, Cold Equipment, Energy Consumption, Performance Report.

**Capability Analysis:**
- Listar y filtrar equipos.  
- Acceder a especificaciones técnicas.

**Capability Layering:**
- **Application:** vistas y filtros de equipos.  
- **Domain:** validaciones de visualización.  
- **Infrastructure:** consultas optimizadas a base de datos.

**Dependencies Capture:** Depende de *My Equipment* (registro y datos actualizados).

**Design Critique:** Es un *Generic Context*, soporte esencial para mejorar usabilidad y experiencia del usuario.

### 2.5.2. Context Mapping
Luego de definir los Bounded Contexts y modelar sus colaboraciones, se realizó una sesión de Context Mapping para visualizar las relaciones estructurales dentro del dominio de OsitoPolar.
Este proceso permitió evaluar:
- Nivel de criticidad (Core, Supporting, Generic).
- Funcionalidades clave.
- Dependencias cruzadas.
- Oportunidades de aislamiento o colaboración.

**Preguntas clave consideradas**
¿Qué pasaría si Notificaciones se integrara en Mi Equipo en lugar de ser un contexto separado?
¿Qué pasaría si Ver Mantenimientos se absorbiera en Órdenes de Trabajo?
¿Qué pasaría si se creara un contexto separado para Service Providers (técnicos, zonas, cartera de clientes)?
¿Qué pasaría si Ver Equipos se integrara directamente en Mi Equipo para reducir redundancias?

**Alternativas exploradas**
**Alternativa 1: Fusionar Notificaciones + Mi Equipo**
Pros: reduce dependencias, notificaciones más inmediatas.
Contras: rompe separación de responsabilidades.
Decisión: Rechazada. Se mantiene independiente.

**Alternativa 2: Absorber Ver Mantenimientos en Órdenes de Trabajo**
Pros: simplifica arquitectura y flujo de datos.
Contras: dificulta consultas históricas optimizadas.
Decisión: Rechazada. Ver Mantenimientos se mantiene separado para consultas especializadas.

**Alternativa 3: Crear contexto de Service Providers**
Pros: aísla la gestión de técnicos, zonas y cartera de clientes.
Contras: agrega complejidad inicial.
Decisión: Aprobada para el roadmap futuro.

**Alternativa 4: Integrar Ver Equipos en Mi Equipo**
Pros: simplifica modelo y reduce redundancia.
Contras: limita escalabilidad de la visualización.
Decisión: Rechazada. Se mantiene desacoplado para mejorar rendimiento de búsquedas.


### 2.5.3. Software Architecture
  ##### 2.5.3.1. Software Architecture Context Level Diagrams
Este diagrama muestra cómo interactúan los usuarios (Clientes y Empresas Proveedoras) con OsitoPolar. Los usuarios usan la plataforma para gestionar y monitorear equipos de refrigeración. Además, OsitoPolar se conecta con los servicios de correo para enviar notificaciones y con el servicio de pago para procesar transacciones.

![OsitoPolar-SystemContext.png]( assets/chapter04/Domain-Driven%20Software%20Architecture/OsitoPolar-SystemContext.png)

  #### 2.5.3.2. Software Architecture Container Level Diagrams
Este diagrama ilustra los diferentes contenedores dentro de OsitoPolar y cómo interactúan entre sí. Los contenedores representan las diferentes capas y servicios que componen la plataforma, como la interfaz de usuario (webapp), la API y la base de datos.

![OsitoPolar-Container.png](<assets/chapter03/ContainerDiagrama.png>)

  #### 2.5.3.3. Software Architecture Deployment Diagrams
**Mi Equipo Bounded Context**

Este diagrama representa los componentes encargados de la gestión de equipos. Los usuarios pueden agregar equipos, monitorearlos en tiempo real y ver el estado de los mismos.

![OsitoPolar-Component-MiEquipo.png]( assets/chapter03/DeploymentDiagram.png)

**Notificaciones Bounded Context**

Este diagrama describe los componentes que gestionan las notificaciones, esenciales para mantener a los usuarios informados sobre el estado de los equipos y otros eventos importantes.

![OsitoPolar-Component-Notificaciones.png]( assets/chapter04/Domain-Driven%20Software%20Architecture/OsitoPolar-Component-Notificaciones.png)

**Ordenes de trabajo Bounded Context**

Este diagrama se centra en la gestión de las órdenes de trabajo. Aquí se muestran los componentes involucrados en el proceso de crear, gestionar y completar órdenes de trabajo.

![OsitoPolar-Component-OrdenesTrabajo.png]( assets/chapter04/Domain-Driven%20Software%20Architecture/OsitoPolar-Component-OrdenesTrabajo.png)
### 2.6. Tactical-Level Domain-Driven Design

#### 2.6.1. Bounded Context: Mi Equipo
##### 2.6.1.1. Domain Layer
Esta capa representa el núcleo del sistema y las reglas de negocio del dominio.

| Clase  | Tipo | Propósito | Atributos / Métodos |
| :---- | :---- | :---- | :---- |
| Equipment | Aggregate | Equipo de refrigeración | Id, Name, Type, Model, Manufacturer, Cost |
| EnergyConsumption | Entity | Consumo de energía | Current, Unit, Average, UpdateCurrent(), UpdateAverage |
| RentalInfo | Entity | Información de renta de equipos | StartDate, EndDate, MonthlyFee, ProviderId |
| Location | Entity | Ubicación | Name, Address, Coordinates |

##### 2.6.1.2. Interface Layer

Encargada de exponer funcionalidades al usuario o consumidores externos.

| Clase | Tipo | Propósito | Atributos / Métodos |
| :---- | :---- | :---- | :---- |
| EquipmentController | Controller | Gestiona las peticiones relacionadas con los equipment | GetAllEquipments(), GetEquipmentById(), CreateEquipment(), UpdateEquipmentOperations(), UpdateEquipment(), DeleteEquipment() |

##### 2.6.1.3. Application Layer

Define los flujos de negocio mediante comandos y eventos.

| Clase | Tipo | Propósito | Métodos |
| :---- | :---- | :---- | :---- |
| EquipmentCommandService | Command Handler | Ejecuta la lógica para gestionar un Equipment | Handle(command::CreateEquipmentCommand, command: UpdateEquipmentTemperatureCommand, UpdateEquipmentLocationCommand) |

##### 2.6.1.4. Infrastructure Layer

Provee la implementación concreta de servicios como base de datos, brokers, etc.

| Clase | Tipo | Propósito | Tecnologías |
| :---- | :---- | :---- | :---- |
| EquipmentRepository | Repository | Implementación de EquipmentRepository con acceso a base de datos | PostgreSQL |

#### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams
<img width="3870" height="auto" alt="mi_equipo_component1" src="https://github.com/user-attachments/assets/709cd005-84e4-4a14-8e6d-4dd3a8c2772b" />

#### 2.6.1.6. Bounded Context Software Architecture Code Level Diagrams
A continuación, se detallan los diagramas de arquitectura de código que brindan mayor profundidad sobre la implementación interna del bounded context de Mi Equipo. Esta vista se enfoca en clases, métodos, atributos y relaciones a nivel de código fuente.
#### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams
<img width="1538" height="auto" alt="image" src="https://github.com/user-attachments/assets/2b1b243e-27c0-41d7-a1a5-1f6ff0a01e7e" />

#### 2.6.1.6.2. Bounded Context Database Design Diagram
<img width="1091" height="auto" alt="image" src="https://github.com/user-attachments/assets/79d43335-bed1-4203-9d34-3298314f8d43" />

 
#### 2.6.2. Bounded Context: Gestión de Solicitudes

##### 2.6.2.1. Domain Layer

Esta capa representa el núcleo del sistema y las reglas de negocio del dominio.

| Clase  | Tipo | Propósito | Atributos / Métodos |
| :---- | :---- | :---- | :---- |
| ServiceRquest | Aggregate | Representa a la solicitud de servicio | Id, OrderNumber, Title, Description, IssueDetails, RequestTime, Status, Priority, Urgency, IsEmergency, ServiceType |
| EPriority | Value Object | Representa a la prioridad de una solicitud | Low, Medium, High, Critical |
| EServiceType | Value Object | Representa el tipo de servicio de una solicitud | PreventiveMaintenance, CorrectiveMaintenance, Installation, Diagnostic |

##### 2.6.2.2. Interface Layer

Encargada de exponer funcionalidades al usuario o consumidores externos.

| Clase  | Tipo | Propósito | Métodos |
| :---- | :---- | :---- | :---- |
| ServiceRequestController | Controller | Gestiona las peticiones relacionadas ServiceRequest | CreateServiceRequest(), GetAllServiceRequests(), GetServiceRequestById(), UpdateServiceRequest(), AssignTechnician(), AddCustomerFeedback(), UpdateServiceRequestStatus() |

##### 2.6.2.3. Application Layer

Define los flujos de negocio mediante comandos y eventos.

| Clase | Tipo | Propósito | Métodos |
| :---- | :---- | :---- | :---- |
| ServiceRequestCommandService | Command Handler | Ejecuta la lógica para gestionar un ServiceRequest | Handle(command::CreateServiceRequestCommand, command: UpdateServiceRequestCommand, AssignTechnicianToServiceRequestCommand, AddCustomerFeedbackToServiceRequestCommand() |

##### 2.6.2.4. Infrastructure Layer

Provee la implementación concreta de servicios como base de datos, brokers, etc.

| Clase | Tipo | Propósito | Tecnologías |
| :---- | :---- | :---- | :---- |
| ServiceRequestRepository | Repository | Implementación de ServiceRequestRepository con acceso a base de datos | PostgreSQL |

##### 2.6.2.5. Bounded Context Software Architecture Component Level Diagrams
<img width="4620" height="auto" alt="gestion_solicitudes_component" src="https://github.com/user-attachments/assets/589e930b-82c7-48fd-9c49-7fe81b7c3a19" />

##### 2.6.2.6. Bounded Context Software Architecture Code Level Diagrams
A continuación, se detallan los diagramas de arquitectura de código que brindan mayor profundidad sobre la implementación interna del bounded context de Gestión de Solicitudes. Esta vista se enfoca en clases, métodos, atributos y relaciones a nivel de código fuente.
###### 2.6.2.6.1. Bounded Context Domain Layer Class Diagrams
<img width="1817" height="auto" alt="image" src="https://github.com/user-attachments/assets/b686ba99-f84c-4900-be14-d455b16d9b9f" />

###### 2.6.2.6.2. Bounded Context Database Design Diagram
<img width="542" height="auto" alt="image" src="https://github.com/user-attachments/assets/e394d39c-dc41-46ed-9066-a52dbd2e81e8" />

           

#### 2.6.3. Bounded Context: Órdenes de Trabajo

##### 2.6.3.1. Domain Layer

Esta capa representa el núcleo del sistema y las reglas de negocio del dominio.

| Clase  | Tipo | Propósito | Atributos / Métodos |
| :---- | :---- | :---- | :---- |
| WorkOrder | Aggregate | Representa a la orden de trabajo | Id, WorkOrderNumber, ServiceRequestId, Title, Description, CreationTime, Status, Cost, EquipmentId |
| EWorkOrderStatus | Value Object | Representa al estado de una orden de trabajo | Created, Assigned, InProgress, OnHold, Completed, Resolved, Cancelled |

##### 2.6.3.2. Interface Layer

Encargada de exponer funcionalidades al usuario o consumidores externos.

| Clase  | Tipo | Propósito | Métodos |
| :---- | :---- | :---- | :---- |
| WorkOrdersController | Controller | Gestiona las peticiones relacionadas con los WorkOrders | CreateWorkOrder(), GetAllWorkOrders(), GetWorkOrderById(), UpdateWorkOrderStatus(), AddWorkOrderResolutionDetails() |

##### 2.6.3.3. Application Layer

Define los flujos de negocio mediante comandos y eventos.

| Clase | Tipo | Propósito | Métodos |
| :---- | :---- | :---- | :---- |
| WorkOrderCommandService | Command Handler | Ejecuta la lógica para gestionar un WorkOrder | Handle(command::CreateWorkOrderCommand, command: UpdateWorkOrderStatusCommand, AssignTechnicianToWorkOrderCommand, AddWorkOrderResolutionDetailsCommand) |

##### 2.6.3.4. Infrastructure Layer

Provee la implementación concreta de servicios como base de datos, brokers, etc.

| Clase | Tipo | Propósito | Tecnologías |
| :---- | :---- | :---- | :---- |
| WorkOrderRepository | Repository | Implementación de WorkOrderRepository con acceso a base de datos | PostgreSQL |

#### 2.6.3.5. Bounded Context Software Architecture Component Level Diagrams
<img width="4620" height="auto" alt="orden_trabajo_component" src="https://github.com/user-attachments/assets/c4700d59-dc40-4338-ae11-6ddf359ad468" />

#### 2.6.3.6. Bounded Context Software Architecture Code Level Diagrams
A continuación, se detallan los diagramas de arquitectura de código que brindan mayor profundidad sobre la implementación interna del bounded context de Órdenes de Trabajo. Esta vista se enfoca en clases, métodos, atributos y relaciones a nivel de código fuente.
#### 2.6.3.6.1. Bounded Context Domain Layer Class Diagrams
<img width="1805" height="auto" alt="image" src="https://github.com/user-attachments/assets/cf16b776-74cf-4c03-af58-38d6be9fca31" />

#### 2.6.3.6.2. Bounded Context Database Design Diagram
<img width="622" height="auto" alt="image" src="https://github.com/user-attachments/assets/409402e0-9d5f-40e2-90c3-c8bfd29e5444" />

 

#### 2.6.4. Bounded Context: Ver Mantenimientos

##### 2.6.4.1. Domain Layer

Esta capa representa el núcleo del sistema y las reglas de negocio del dominio.

| Clase  | Tipo | Propósito | Atributos / Métodos |
| :---- | :---- | :---- | :---- |
| Technician | Entity | Representa a un técnico que ve los mantenimientos | Id, Name, Specialization, Phone, Email, Rating, Availability, CompanyId |


##### 2.6.4.2. Interface Layer

Encargada de exponer funcionalidades al usuario o consumidores externos.

| Clase  | Tipo | Propósito | Métodos |
| :---- | :---- | :---- | :---- |
| TechniciansController | Controller | Gestiona las peticiones relacionadas a los Technicians | CreateTechnician(), GetAllTechnicians(), GetTechnicianById(), GetTechnicianAverageRating() |

##### 2.6.4.3. Application Layer

Define los flujos de negocio mediante comandos y eventos.

| Clase | Tipo | Propósito | Métodos |
| :---- | :---- | :---- | :---- |
| TechnicianCommandService | Command Handler | Ejecuta la lógica para gestionar un Technician | Handle(command: CreateTechnicianCommand, command: UpdateTechnicianCommand |

##### 2.6.4.4. Infrastructure Layer

Provee la implementación concreta de servicios como base de datos, brokers, etc.

| Clase | Tipo | Propósito | Tecnologías |
| :---- | :---- | :---- | :---- |
| TechnicianRepository | Repository | Implementación de TechnicianRepository con acceso a base de datos | PostgreSQL |

##### 2.6.4.5. Bounded Context Software Architecture Component Level Diagrams
<img width="4620" height="auto" alt="ver_mantenimientos_component" src="https://github.com/user-attachments/assets/cc9a9843-3bbf-4fa8-b894-3c0f667caeda" />

##### 2.6.4.6. Bounded Context Software Architecture Code Level Diagrams
A continuación, se detallan los diagramas de arquitectura de código que brindan mayor profundidad sobre la implementación interna del bounded context de Ver Mantenimientos. Esta vista se enfoca en clases, métodos, atributos y relaciones a nivel de código fuente.
###### 2.6.4.6.1. Bounded Context Domain Layer Class Diagrams
<img width="1327" height="auto" alt="image" src="https://github.com/user-attachments/assets/d17df10e-5038-45b5-847e-20237f81cbb5" />

###### 2.6.4.6.2. Bounded Context Database Design Diagram
<img width="871" height="auto" alt="image" src="https://github.com/user-attachments/assets/7c0cba94-db9f-4329-9de0-87a4dfa55863" />

     

#### 2.6.5. Bounded Context: Notificaciones
#### 2.6.5.1. Domain Layer

   | Clase                     | Tipo                  | Propósito                                                                 | Atributos / Métodos                                                                 |
|----------------------------|-----------------------|---------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| **Payment**               | Entity               | Representa un pago realizado por un usuario para adquirir o renovar una suscripción. | Id, UserId, SubscriptionId, Amount: Price, StripeSession, CustomerEmail, Description, `UpdatePaymentStatus()` |
| **Subscription**          | Entity               | Representa un plan de suscripción contratado por un usuario o proveedor.  | Id, PlanName, Price, BillingCycle, MaxEquipment, MaxClients, Features (List<Feature>), `UpdatePlan()` |
| **Price**                 | Value Object         | Define un valor monetario y su moneda asociada.                           | Amount, Currency                                                                    |
| **Feature**               | Value Object         | Representa una característica incluida en un plan de suscripción.         | Name                                                                                |
| **PaymentStatus**         | Value Object / Enum  | Representa el estado de un pago.                                          | Processing, Succeeded, Failed, Cancelled                                            |
| **StripeSession**         | Value Object         | Encapsula la sesión de pago en Stripe y su estado.                        | SessionId, `MarkAsProcessing()`, `MarkAsSucceeded()`, `MarkAsFailed()`, `MarkAsCancelled()` |
| **BillingCycle**          | Value Object / Enum  | Define la periodicidad de facturación.                                    | Monthly, Yearly                                                                     |
| **IPaymentRepository**    | Repository Interface | Abstracción para acceder a datos de pagos.                                | `AddAsync()`, `FindById()`, `FindByUserId()`, `FindByStripeSessionId()`             |
| **ISubscriptionRepository** | Repository Interface | Abstracción para acceder a datos de suscripciones.                        | `FindByIdAsync()`, `FindByUserTypeAsync()`                                          |
| **ISubscriptionCommandService** | Domain Service  | Gestiona operaciones sobre suscripciones.                                 | `Handle(CreateSubscriptionCommand)`, `Handle(UpgradePlanCommand)`, `Handle(DeleteSubscriptionCommand)` |

    
  #### 2.6.5.2. Interface Layer
  
Expone las funcionalidades a usuarios y sistemas externos.

| Clase                    | Tipo            | Propósito                                                                | Métodos                                                                 |
|---------------------------|-----------------|--------------------------------------------------------------------------|-------------------------------------------------------------------------|
| **SubscriptionsController** | REST Controller | Gestiona las peticiones HTTP relacionadas con suscripciones.              | `CreateSubscription()`, `GetAllSubscriptions()`, `GetSubscriptionById()`, `UpgradeSubscription()`, `DeleteSubscription()` |
| **Resources**            | DTOs (Request/Response) | Representan los contratos expuestos en la API.                            | CreateSubscriptionResource, UpgradeSubscriptionResource, SubscriptionResource |
| **Assemblers**           | Mapper          | Convierte entre recursos ↔ comandos ↔ entidades.                          | CreateSubscriptionCommandFromResourceAssembler, UpgradeSubscriptionCommandFromResourceAssembler, SubscriptionResourceFromEntityAssembler |

---

  
  #### 2.6.5.3. Application Layer
  Orquesta los flujos de negocio mediante commands, queries y servicios de aplicación.

| Clase                    | Tipo                | Propósito                                                                 | Métodos                                                                 |
|---------------------------|---------------------|---------------------------------------------------------------------------|-------------------------------------------------------------------------|
| **PaymentCommandService** | Application Service | Gestiona creación de sesiones de pago y actualización de estado desde Stripe. | `Handle(CreatePaymentSessionCommand)`, `Handle(ProcessPaymentWebhookCommand)` |
| **SubscriptionCommandService** | Application Service | Gestiona la lógica de crear, actualizar y eliminar suscripciones.          | `Handle(CreateSubscriptionCommand)`, `Handle(UpgradePlanCommand)`, `Handle(DeleteSubscriptionCommand)` |
| **SubscriptionQueryService** | Query Service     | Ejecuta consultas de lectura de suscripciones.                            | `Handle(GetPlansQuery)`, `Handle(GetSubscriptionByIdQuery)`              |
| **Commands**              | DTOs               | Expresan intenciones de modificar el dominio.                             | CreateSubscriptionCommand, UpgradePlanCommand, DeleteSubscriptionCommand, CreatePaymentSessionCommand, ProcessPaymentWebhookCommand |
| **Queries**               | DTOs               | Expresan intenciones de consultar información.                            | GetPlansQuery, GetSubscriptionByIdQuery                                 |

---

   #### 2.6.5.4. Infrastructure Layer
   Implementa persistencia, integración con Stripe y configuración externa.

| Clase                    | Tipo             | Propósito                                                                 | Tecnologías                     |
|---------------------------|------------------|---------------------------------------------------------------------------|---------------------------------|
| **PaymentRepository**    | Repository       | Implementación de `IPaymentRepository` con EF Core.                       | EF Core, LINQ                   |
| **SubscriptionRepository** | Repository     | Implementación de `ISubscriptionRepository` con EF Core.                  | EF Core                         |
| **StripeService (IStripeService)** | External Service | Gestiona la comunicación con la API de Stripe.                           | Stripe API                      |
| **StripeSettings**       | Configuración    | Contiene claves y secretos de Stripe.                                     | PublishableKey, SecretKey, WebhookSecret |
| **UnitOfWork**           | Infraestructura  | Coordina transacciones.                                                   | EF Core                         |
| **AppDbContext**         | Persistence      | DbContext para persistir Payment y Subscription.                          | EF Core                         |


   
   #### 2.6.5.5. Bounded Context Software Architecture Component Level Diagrams
En esta sección explicaremos el bounded context SubscriptionsAndPayments.<br>
**App Web OsitoPolar**<br>
•	Tipo: Container<br>
•	Función: Aplicación web usada por usuarios y proveedores para gestionar planes de suscripción y pagos.<br>
•	Interacción: Realiza llamadas HTTP a la API de SubscriptionsAndPayments.<br>
**SubscriptionsController**<br>
•	Tipo: REST Controller.<br>
•	Función: Expone endpoints REST para gestionar suscripciones.<br>
•	Interacción: Invoca servicios de aplicación (ISubscriptionCommandService, ISubscriptionQueryService).<br>
PaymentsController <br>
•	Tipo: REST Controller.<br>
•	Función: Expone endpoints REST para iniciar sesiones de pago y procesar webhooks de Stripe.<br>
•	Interacción: Invoca PaymentCommandService.<br>
CreateSubscriptionCommandHandler <br>
•	Tipo: Application Service.<br>
•	Función: Orquesta la creación de un nuevo plan de suscripción.<br>
•	Interacción: Construye una instancia válida de Subscription. Persiste mediante ISubscriptionRepository.<br>
UpgradeSubscriptionCommandHandler<br>
•	Tipo: Application Service.<br>
•	Función: Gestiona la actualización de un plan de suscripción existente.<br>
•	Interacción: Recupera y actualiza el Subscription en ISubscriptionRepository.<br>
DeleteSubscriptionCommandHandler<br>
•	Tipo: Application Service.<br>
•	Función: Gestiona la eliminación de un plan de suscripción.<br>
•	Interacción: Elimina un Subscription de ISubscriptionRepository.<br>
PaymentCommandService<br>
•	Tipo: Application Service.<br>
•	Función: Orquesta la creación de pagos y el procesamiento de webhooks de Stripe.<br>
•	Interacción:<br>
o	Crea sesión de pago con IStripeService.<br>
o	Construye entidad Payment.<br>
o	Persiste con IPaymentRepository.<br>
o	Si el pago es exitoso, dispara comando UpgradePlanCommand en ISubscriptionCommandService.<br>
StripeService<br>
•	Tipo: Infrastructure Service.<br>
•	Función: Encapsula la integración con Stripe para crear sesiones de checkout y validar eventos de webhook<br>
•	Interacción: Recibe solicitudes desde PaymentCommandService.<br>
Repositories<br>
•	IPaymentRepository<br>
o	Tipo: Repository.<br>
o	Función: Maneja la persistencia de la entidad Payment.<br>
o	Interacción: Usado por PaymentCommandService.<br>
ISubscriptionRepository<br>
o	Tipo: Repository.<br>
o	Función: Maneja la persistencia de la entidad Subscription.<br>
o	Interacción: Usado por ISubscriptionCommandService<br><br>
![alt text](assets/chapter02/component-diagram-p&s.png)


   #### 2.6.5.6. Bounded Context Software Architecture Code Level Diagrams
A continuación, se detallan los diagramas de arquitectura de código que brindan mayor profundidad sobre la implementación interna del bounded context de Pagos y Suscripciones. Esta vista se enfoca en clases, métodos, atributos y relaciones a nivel de código fuente.

   #### 2.6.5.6.1. Bounded Context Domain Layer Class Diagrams
**Capa de Dominio:** Contiene las entidades (Payment, Subscription) y objetos de valor (Price, Feature, PaymentStatus, StripeSession, BillingCycle).
**Capa de Repositorio:** Maneja la persistencia de datos (IPaymentRepository, ISubscriptionRepository).<br>
**Capa de Servicio:** Coordina las operaciones de negocio (ISubscriptionCommandService, PaymentCommandService).<br>
**Capa de Comandos:** Encapsula acciones específicas (CreateSubscriptionCommand, UpgradePlanCommand, DeleteSubscriptionCommand, CreatePaymentSessionCommand, ProcessPaymentWebhookCommand).<br>
![alt text](assets/chapter02/class-diagram-p&s.png)

   
   #### 2.6.5.6.2. Bounded Context Database Design Diagram
   ![alt text](assets/chapter02/database-diagram-p&s.png)


#### 2.6.6. Bounded Context: Ver Equipos
##### 2.6.6.1. Domain Layer
El contexto Ver Equipos representa la funcionalidad que permite a los usuarios del sistema OsitoPolar visualizar y  consultar la información de los equipos de refrigeración registrados.

Las principales entidades de dominio son:
- Equipo: unidad de refrigeración registrada (atributos: idEquipo, nombre, tipo, ubicación, estado, fechaRegistro).
- Sensor (Value Object): mide métricas como temperatura, voltaje o consumo de energía.
- RegistroMantenimiento (Entity): historial técnico de cada equipo con fecha, técnico responsable y observaciones.
- Alerta (Domain Event): notificación que se dispara cuando un sensor registra valores fuera del rango esperado.

Servicios de dominio:
- EquipoService: encapsula lógica de negocio para listar, filtrar y detallar equipos.
- AlertaService: gestiona la emisión de eventos cuando se generan anomalías.
  


   #### 2.6.6.2. Interface Layer
Esta capa define cómo los usuarios interactúan con el sistema y expone la lógica de negocio a través de interfaces:
- Pantalla móvil “Ver Equipos”: módulo de la app donde los usuarios visualizan los equipos, estado y métricas.
- EquiposController (REST API): expone endpoints como:
  - GET /equipos → lista de equipos.
  - GET /equipos/{id} → detalle de un equipo específico.
  - GET /equipos/{id}/sensores → métricas de sensores asociados.
    
Seguridad: acceso restringido mediante autenticación JWT.

   #### 2.6.6.3. Application Layer
Orquesta los casos de uso del contexto “Ver Equipos”:

- ListarEquiposHandler: obtiene todos los equipos registrados.
- ConsultarEquipoHandler: devuelve información detallada de un equipo.
- FiltrarEquiposHandler: busca equipos por estado, tipo o ubicación.
- GenerarReporteEquipoHandler: compila historial de sensores y mantenimientos.

Se utiliza un enfoque CQRS para separar operaciones de lectura (queries) de escritura (commands).

   #### 2.6.6.4. Infrastructure Layer
La capa de infraestructura implementa la persistencia y las integraciones externas:

- EquipoRepositoryImpl: implementación concreta para almacenar y consultar equipos (PostgreSQL).
- SensorDataAdapter: integra la captura de datos en tiempo real desde dispositivos IoT.
- NotificaciónService: envío de alertas vía email o notificaciones push.
- ORM (Hibernate/JPA o Sequelize): para el mapeo objeto-relacional.
  
  #### 2.6.6.5. Bounded Context Software Architecture Component Level Diagrams
El diagrama de componentes del contexto “Ver Equipos” se organiza en cuatro capas:

- Interface Layer → Pantalla móvil y API REST.
- Application Layer → Handlers de casos de uso.
- Domain Layer → Entidades (Equipo, Sensor, RegistroMantenimiento, Alerta) y servicios de dominio.
- Infrastructure Layer → Repositorios, adaptadores IoT y notificaciones.

<img width="1335" height="590" alt="image" src="https://github.com/user-attachments/assets/ac7ab40a-df1f-48a6-af81-d95656258a78" />


   #### 2.6.6.6. Bounded Context Software Architecture Code Level Diagrams
   #### 2.6.6.6.1. Bounded Context Domain Layer Class Diagrams
El siguiente diagrama de clases muestra las principales entidades y relaciones:

- Equipo (Entity) → relación 1..* con Sensor.
- Equipo (Entity) → relación 1..* con RegistroMantenimiento.
- Alerta (Domain Event) → asociada a Equipo y generada por AlertaService.
- EquipoService → utiliza EquipoRepository.

<img width="469" height="529" alt="image" src="https://github.com/user-attachments/assets/8031265c-17b8-41f9-8e6b-90273ca3f08d" />


   - 2.6.6.6.2. Bounded Context Database Design Diagram        
La base de datos del contexto “Ver Equipos” está compuesta por las siguientes tablas:

- Equipos: idEquipo (PK), nombre, tipo, ubicación, estado, fechaRegistro.
- Sensores: idSensor (PK), idEquipo (FK), tipo, valorActual, unidad.
- RegistrosMantenimiento: idRegistro (PK), idEquipo (FK), fecha, técnico, detalle.
- Alertas: idAlerta (PK), idEquipo (FK), tipo, severidad, fechaGenerada.

<img width="1712" height="520" alt="image" src="https://github.com/user-attachments/assets/6b81b3d0-cb3a-48f6-ad5d-0b024c6382c7" />

# Chapter III: Solution UI/UX Design
- 3.1. Product Design

En esta sección se presenta el diseño del producto **Osito Polar** como una parte esencial de la arquitectura del sistema. El diseño busca alinear las funcionalidades principales con las necesidades detectadas durante el análisis y modelado del dominio, garantizando una experiencia fluida, intuitiva y estéticamente consistente.

**Osito Polar** está centrado en brindar una plataforma moderna e interactiva que combina diseño minimalista con funcionalidad avanzada. El sistema permite a los usuarios interactuar con un entorno visual claro, limpio y coherente con los principios de usabilidad, accesibilidad y consistencia visual.

La arquitectura del producto contempla una **aplicación móvil desarrollada en Kotlin**, respaldada por un **backend en Spring Boot** y una **base de datos relacional en PostgreSQL**. Estas decisiones tecnológicas garantizan escalabilidad, rendimiento y mantenibilidad a largo plazo.

---
  - 3.1.1. Style Guidelines

El objetivo de esta sección es establecer una guía visual clara y compartida por todo el equipo de desarrollo y diseño, asegurando una experiencia consistente en todas las pantallas y plataformas.  
Se definen los criterios para colores, tipografía, iconografía, botones, espaciados y usabilidad.

---
 - 3.1.1.1. General Style Guidelines

#### Paleta de colores principal

La estética de **Osito Polar** se basa en un estilo **minimalista y moderno**, utilizando tonos suaves con acentos contrastantes para transmitir profesionalismo y confianza.

| Color | Hex | Uso principal |
|--------|------|----------------|
| Azul Polar | `#2B6CB0` | Color primario para botones, íconos y acentos. |
| Blanco Nieve | `#FFFFFF` | Fondo principal de vistas y componentes. |
| Negro Profundo | `#000000` | Tipografía principal y elementos de contraste. |
| Gris Claro | `#F5F5F5` | Fondos secundarios o tarjetas neutras. |
| Gris Oscuro | `#333333` | Textos secundarios o subtítulos. |

#### Tipografía

El proyecto emplea una tipografía sans-serif moderna que asegura claridad y legibilidad:

- **Fuente principal:** Poppins (o Montserrat, según la versión final del Figma)
- **Títulos:** Bold o Semi-Bold  
- **Texto general:** Regular  
- **Botones:** Medium  

#### Iconografía y botones

- Iconos minimalistas en **negro o azul polar**, alineados con el estilo limpio del producto.  
- Bordes con **radio de 8px** para transmitir suavidad visual.  
- Botones primarios con fondo azul polar y texto blanco.  
- En estado *hover*: fondo blanco con borde azul y texto azul.  
- Uso consistente del espaciado interno y márgenes para crear ritmo visual.  

#### Estilo visual general

- Diseño **limpio y espacioso**, aprovechando el uso de “espacio en blanco”.  
- **Tarjetas** para agrupar contenido (componentes, builds, o información de usuario).  
- **Sombras ligeras** (`box-shadow: 0 2px 4px rgba(0,0,0,0.1)`) para destacar elementos interactivos.  
- Animaciones suaves al pasar el cursor o al presionar botones.  

#### Usabilidad y accesibilidad

- Contraste de texto y fondo que cumpla estándares **WCAG AA**.  
- Soporte para navegación por teclado (tabulador y foco visible).  
- Uso de atributos **aria-*** para lectores de pantalla.  
- Botones con altura mínima de **44px** para accesibilidad táctil.  
- Estructura visual compatible con distintos tamaños de pantalla.

---
  - 3.1.2. Information Architecture
    
La arquitectura de la información de **Osito Polar** fue diseñada para facilitar la navegación, el descubrimiento de funcionalidades y la organización jerárquica de los datos.  
Tanto la landing page como la aplicación móvil siguen principios de jerarquía, consistencia y categorización.

---
  - 3.1.2.1. Organization Systems

Se aplican distintos sistemas de organización según la sección o funcionalidad:

- **Jerárquico:**  
  En la navegación principal (Catálogo → Categorías → Detalle de componente), y en la gestión de builds guardadas del usuario.  

- **Secuencial:**  
  En el flujo de creación de una build: seleccionar categoría → seleccionar componente → validar compatibilidad → guardar.  

- **Matricial:**  
  En la comparación de builds o especificaciones, donde se visualizan datos tabulados.  

- **Categorización temática:**  
  Guías y tutoriales agrupados por temas como Overclocking, Ensamblaje o Mantenimiento.  

- **Por audiencia:**  
  Contenido separado para usuarios principiantes, intermedios o expertos.

---
  - 3.1.2.2. Labelling Systems

Las etiquetas de texto fueron cuidadosamente seleccionadas para ser **claras, cortas y coherentes** con la experiencia del usuario.

**Ejemplos de etiquetas:**

- **Botones:** Agregar, Guardar Build, Comparar, Eliminar, Filtrar, Ver Detalles.  
- **Secciones:**  
  - Catálogo → Componentes  
  - Builds → Mis Builds, Builds Populares  
  - Comunidad → Comentarios, Valoraciones  
  - Guías → Tips, Tutoriales, Guías Técnicas  
- **Filtros de búsqueda:** Nombre, Tipo, Fabricante, Compatibilidad, Categoría.

La iconografía refuerza las etiquetas mediante símbolos intuitivos y colores distintivos.

---
  - 3.1.2.3. SEO Tags and Meta Tags

Se definen metadatos para optimizar la visibilidad tanto en motores de búsqueda (SEO) como en tiendas de aplicaciones (ASO).

#### Landing Page – SEO

- **Title:** Osito Polar – Crea y Personaliza tus Builds  
- **Meta Description:** Plataforma intuitiva para armar y compartir builds de PC personalizados con validación de compatibilidad.  
- **Keywords:** build pc, componentes, hardware, compatibilidad, builds personalizadas  
- **Author:** Equipo Osito Polar  

#### Mobile App – ASO

- **App Title:** Osito Polar  
- **Subtitle:** Tu asistente inteligente para armar PCs.  
- **Description:** Con Osito Polar puedes crear builds personalizadas, analizar compatibilidad de componentes, guardar configuraciones y compartirlas con la comunidad.  
- **App Keywords:** hardware, build pc, compatibilidad, tecnología, comunidad gamer  
---

  - 3.1.2.4. Searching Systems

El sistema de búsqueda está diseñado para ser **rápido, predictivo y flexible**.

- Campo de búsqueda global con **autocompletado** y **sugerencias dinámicas**.  
- Filtros y ordenamientos avanzados (por precio, nombre, marca, compatibilidad, eficiencia).  
- Etiquetas destacadas (chips) para filtros activos.  
- Historial de búsqueda y recomendaciones personalizadas.

---

  - 3.1.2.5. Navigation Systems

#### Landing Page
- Menú superior o hamburguesa con secciones: **Inicio**, **Sobre Nosotros**, **FAQ**, **Contacto**.  
- Botones **CTA (Call To Action)** visibles: *Explorar Builds*, *Comenzar Build*, *Descargar App*.  
- Transiciones suaves entre secciones mediante anclas y scroll dinámico.

#### Aplicación móvil
- Barra inferior con íconos principales: **Catálogo**, **Mis Builds**, **Crear**, **Comunidad**, **Perfil**.  
- Botón flotante (+) para crear rápidamente una nueva build.  
- Breadcrumbs y pasos visibles en el flujo de creación.  
- Estado activo resaltado en cada pestaña para orientar al usuario.

---

  - 3.1.3. Landing Page UI Design

El diseño de la landing page de **Osito Polar** fue desarrollado en **Figma**, priorizando la claridad visual, la jerarquía informativa y la usabilidad.  
El enlace oficial al diseño es el siguiente:  
[🔗 Ver en Figma](https://www.figma.com/design/THgrVQALngRCsSDgrhme2M/Osito-Polar-Figma?node-id=2-87&p=f)

---

  - 3.1.3.1. Landing Page Wireframe
El wireframe de la página de inicio de OsitoPolar organiza los elementos clave para ofrecer una navegación intuitiva. Incluye un encabezado con el logo y un menú de navegación, seguido de una propuesta de valor clara con botones de acción destacados como "Solicitar Demo" y "¿Cómo Funciona?". La página cuenta con secciones para describir a los usuarios objetivo, las funcionalidades clave del sistema, y los beneficios que ofrece OsitoPolar. Al final, se encuentra un formulario de contacto para que los usuarios soliciten una demo, junto con enlaces legales en el pie de página.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/LandingPageWireframe.png"
       alt="Wireframe de la Landing Page: Diseño de baja fidelidad de la página principal."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Wireframe de la Landing Page.
  </figcaption>
</figure>


  - 3.1.3.2. Landing Page Mock-up
El Landing Page Mock-up de OsitoPolar muestra un diseño limpio y organizado, con una estructura intuitiva que guía a los usuarios a través de la plataforma. Incluye una propuesta de valor destacada en la parte superior, seguida de secciones clave como las funcionalidades del sistema, los beneficios para empresas y proveedores, y una explicación clara de cómo funciona el servicio. También cuenta con testimonios de clientes, detalles sobre la empresa y un formulario para solicitar una demo, todo con un enfoque en facilitar la conversión de visitantes a usuarios activos.

- Esta es la primera sección, llamada "Inicio". En esta se puede ver la propuesta de valor que ofrece nuestra plataforma junto con un "Call to Action" que se agregará a futuro.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup1.png"
       alt="Mockup 1 de la Landing Page: Diseño visual de la sección superior."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Mockup 1 - Inicio - Landing Page.
  </figcaption>
</figure>


- Esta segunda sección hace una breve descripción de a quiénes está dirigido la plataforma.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup2.png"
       alt="Mockup 2 de la Landing Page: Diseño visual de la sección de características."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> Mockup 2  - ¿Para quién es? - Landing Page.
  </figcaption>
</figure>


- En "Funcionalidades Clave" se presentan las principales funcionalidades que ofrece la plataforma.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup3.png"
       alt="Mockup 3 de la Landing Page: Diseño visual de la sección de testimonios."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 3:</strong> Mockup 3 - Funcionalidades - Landing Page.
  </figcaption>
</figure>


- En "Beneficios" se presentan los beneficios que ofrece la plataforma para empresas y proveedores.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup4.png"
       alt="Mockup 4 de la Landing Page: Diseño visual de la sección de precios."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 4:</strong> Mockup 4 - Beneficios para negocios - Landing Page.
  </figcaption>
</figure>


- En "Beneficios" se presentan los beneficios que ofrece la plataforma para proveedores.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup5.png"
       alt="Mockup 5 de la Landing Page: Diseño visual de la sección de preguntas frecuentes."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 5:</strong> Mockup 5 - Beneficios para proveedores - Landing Page.
  </figcaption>
</figure>


- En "Como funciona" se describe el flujo del funcionamiento de la plataforma.
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup6.png"
       alt="Mockup 6 de la Landing Page: Diseño visual del pie de página."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 6:</strong> Mockup 6 - ¿Como funciona? - Landing Page.
  </figcaption>
</figure>


- En "Sobre Nosotros" se presenta nuestra Misión y Visión como startup. 

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup7.png"
       alt="Mockup 7 de la Landing Page: Vista detallada de un elemento interactivo."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 7:</strong> Mockup 7 - Sobre Nosotros - Landing Page.
  </figcaption>
</figure>


- En "Lo que dicen nuestros clientes" se visualizan las reseñas de los usuarios que usaron nuestra plataforma.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup8.png"
       alt="Mockup 8 de la Landing Page: Vista detallada de un formulario de contacto."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 8:</strong> Mockup 8 - Lo que dicen nuestros clientes - Landing Page.
  </figcaption>
</figure>


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup9.png"
       alt="Mockup 9 de la Landing Page: Sección de llamada a la acción."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 9:</strong> Mockup 9 - Lo que dicen nuestros clientes - Landing Page.
  </figcaption>
</figure>


<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup10.png"
       alt="Mockup 10 de la Landing Page: Vista de la navegación superior."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 10:</strong> Mockup 10 - Lo que dicen nuestros clientes - Landing Page.
  </figcaption>
</figure>


- En "Contacto" se presenta un formulario de contacto para que los usuarios puedan solicitar una demo.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/Landing%20Page%20Mockups/mockup11.png"
       alt="Mockup 11 de la Landing Page: Vista de la sección de beneficios clave."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 11:</strong> Mockup 11 - Contacto - Landing Page.
  </figcaption>
</figure>


    
  - 3.1.4. Mobile Applications UX/UI Design
    - 3.1.4.1. Mobile Applications Wireframes
### 3.1.4. Mobile Applications UX/UI Design
#### 3.1.4.1. Mobile Applications Wireframes

---

## Cliente

### **1. Inicio – Clientes**
<img src="assets/chapter03/Inicio-Clientes.png"
     alt="Wireframe de la pantalla de inicio para clientes."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 1:</strong> Pantalla de inicio del cliente. Muestra accesos rápidos a funciones principales como equipos, estado de cuenta y soporte.
</figcaption>

Esta vista aplica principios de **jerarquía visual** mediante íconos grandes y textos claros, facilitando la navegación. Se aplica **diseño inclusivo** con colores contrastantes y legibles, y una **arquitectura de información** simple que prioriza tareas frecuentes del usuario.

---

### **2. Mis Equipos – Clientes**
<img src="assets/chapter03/MisEquipos-Clientes.png"
     alt="Wireframe de la vista Mis Equipos para clientes."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 2:</strong> Vista de los equipos registrados por el cliente.
</figcaption>

La pantalla presenta una **organización por tarjetas** que mejora la lectura visual y promueve la claridad informativa. Los botones y etiquetas mantienen consistencia cromática y textual, favoreciendo la **accesibilidad**. La disposición sigue una **arquitectura jerárquica vertical**, guiando la vista del usuario.

---

### **3. Control de Equipo – Cliente**
<img src="assets/chapter03/ControlEquipo-Cliente.png"
     alt="Wireframe de la vista Control de Equipo para clientes."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 3:</strong> Control de los equipos del cliente.
</figcaption>

Se aplican **principios de proximidad y alineación**, agrupando los valores del sensor en áreas visualmente coherentes. El uso de íconos facilita la **comprensión inclusiva** para usuarios no técnicos. La **arquitectura de información** permite monitorear el estado de cada dispositivo en tiempo real.

---

### **4. Estado de Cuenta – Clientes**
<img src="assets/chapter03/EstadoCuenta-Clientes.png"
     alt="Wireframe del estado de cuenta del cliente."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 4:</strong> Estado de cuenta del cliente con detalle de pagos y saldo.
</figcaption>

El diseño enfatiza la **claridad visual** mediante una tabla estructurada con contraste y jerarquía tipográfica. Se prioriza la **legibilidad** y el acceso rápido a la información financiera, alineado con principios de **usabilidad y diseño inclusivo**.

---

### **5. Notificaciones – Clientes**
<img src="assets/chapter03/Notificaciones-Clientes.png"
     alt="Wireframe de la vista de notificaciones para clientes."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 5:</strong> Notificaciones relevantes para el cliente.
</figcaption>

La pantalla emplea **contraste y consistencia** para resaltar los mensajes prioritarios. Se asegura la **legibilidad** con tipografía simple y jerarquía clara, mientras que la **arquitectura informativa** categoriza las alertas según su importancia.

---

### **6. Mi Cuenta – Clientes**
<img src="assets/chapter03/Micuenta-Clientes.png"
     alt="Wireframe de la vista Mi Cuenta para clientes."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 6:</strong> Configuración del perfil y preferencias del cliente.
</figcaption>

El diseño se basa en **equilibrio visual** y **alineación de elementos**, permitiendo una interacción cómoda. Los campos están organizados por categorías, lo que refuerza la **arquitectura de información** y facilita el acceso inclusivo.

---

### **7. Contacto – Clientes**
<img src="assets/chapter03/Contacto-Clientes.png"
     alt="Wireframe de la vista Contacto del cliente."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 7:</strong> Sección de contacto con soporte técnico.
</figcaption>

El uso de **formularios claros y botones contrastantes** demuestra la aplicación de **principios de accesibilidad** y **retroalimentación visual**. La estructura de los campos responde a una **arquitectura secuencial**, guiando paso a paso al usuario.

---

### **8. Registro – Clientes**
<img src="assets/chapter03/Registro Clientes.png"
     alt="Wireframe de la pantalla de registro para clientes."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 8:</strong> Registro de nuevos clientes en la aplicación.
</figcaption>

Se aplica **simplicidad visual** para reducir la carga cognitiva. Los campos tienen buena separación y etiquetas descriptivas, lo que favorece la **inclusión digital** y la correcta **navegación jerárquica** dentro del flujo de alta de usuarios.

---

## Empresa

### **9. Inicio – Empresa**
<img src="assets/chapter03/Inicio-Empresa.png"
     alt="Wireframe de la vista de inicio para empresas."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 9:</strong> Pantalla inicial del panel empresarial.
</figcaption>

El diseño utiliza **distribución modular** para mostrar métricas clave. Se mantiene una paleta sobria y profesional, promoviendo **jerarquía y legibilidad**, junto con una **arquitectura informativa** centrada en el control de operaciones.

---

### **10. Inicio de Sesión – Empresa**
<img src="assets/chapter03/Inicio de Sesión - Empresa.png"
     alt="Wireframe de inicio de sesión para empresas."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 10:</strong> Pantalla de autenticación empresarial.
</figcaption>

La vista aplica **contraste y equilibrio** para guiar la atención al formulario. Los campos y botones son accesibles, cumpliendo **criterios inclusivos** y reforzando una **arquitectura de acceso simple**.

---

### **11. Mis Clientes/Técnicos – Empresa**
<img src="assets/chapter03/MisClientes,Técnicos-Empresa.png"
     alt="Wireframe de la vista de gestión de clientes y técnicos para empresas."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 11:</strong> Módulo de gestión de clientes y técnicos.
</figcaption>

Se aplican principios de **alineación y repetición**, unificando la estructura de tarjetas. Se promueve la **accesibilidad** mediante contraste y tipografía uniforme, y la **arquitectura de información** separa claramente los roles.

---

### **12. Órdenes de Trabajo – Empresa**
<img src="assets/chapter03/ÓrdenesDeTrabajo-Empresa.png"
     alt="Wireframe del módulo de órdenes de trabajo para empresas."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 12:</strong> Sección de órdenes de trabajo activas y completadas.
</figcaption>

La disposición prioriza la **legibilidad jerárquica**, usando bloques diferenciados para cada estado. Se aplican principios de **contraste y proximidad**, junto con una **arquitectura de información** que favorece el seguimiento eficiente.

---

### **13. Solicitudes – Empresa**
<img src="assets/chapter03/Solicitudes-Empresa.png"
     alt="Wireframe del módulo de solicitudes empresariales."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 13:</strong> Solicitudes y requerimientos de clientes.
</figcaption>

La pantalla aplica **diseño centrado en tareas**, priorizando la acción principal. La interfaz mantiene **claridad visual** y estructura por secciones, sustentando la **arquitectura informativa** del módulo operativo.

---

### **14. Estado de Cuenta – Empresa**
<img src="assets/chapter03/EstadoCuenta-Empresa.png"
     alt="Wireframe de estado de cuenta empresarial."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 14:</strong> Estado de cuenta y facturación de la empresa.
</figcaption>

Se prioriza la **usabilidad y simplicidad**, usando columnas claras y buena separación de datos. La **tipografía contrastante** y la **disposición estructurada** evidencian principios de diseño limpio e inclusivo.

---

### **15. Mi Cuenta – Empresa**
<img src="assets/chapter03/MiCuenta-Empresa.png"
     alt="Wireframe de la vista Mi Cuenta empresarial."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 15:</strong> Configuración de perfil y plan empresarial.
</figcaption>

El diseño presenta **organización modular**, destacando la jerarquía entre información del plan y configuración. Se aplican **principios de accesibilidad** y **consistencia visual** para garantizar una experiencia inclusiva.

---

### **16. Notificaciones – Empresa**
<img src="assets/chapter03/Notificaciones-Empresa.png"
     alt="Wireframe del módulo de notificaciones empresariales."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 16:</strong> Panel de notificaciones empresariales.
</figcaption>

Se aplican **principios de contraste, repetición y proximidad**. Las alertas están jerarquizadas según prioridad, reforzando la **arquitectura de información** y garantizando una **lectura accesible**.

---

### **17. Contacto – Empresa**
<img src="assets/chapter03/Contacto-Empresa.png"
     alt="Wireframe de la vista de contacto para empresas."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 17:</strong> Formulario de contacto empresarial.
</figcaption>

La vista evidencia **claridad y estructura secuencial**, guiando al usuario en cada paso. Se aplican **principios de accesibilidad y contraste**, y una **arquitectura jerárquica** que optimiza la interacción con el soporte técnico.

---

  - 3.1.4.2. Mobile Applications Wireflow Diagrams
En esta sección se presentan los Wireflows para cada objetivo del usuario, teniendo en cuenta los User Personas relevantes. Cada diagrama ilustra el flujo de interacción del usuario y cómo las acciones realizadas afectan las pantallas dentro de la aplicación.


### **User Goal 1**: 
Como dueño de un negocio que utiliza equipos de refrigeración quiero estar pendiente del estado de cada equipo registrado.

**Task Flow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/flujos/taskflow1.png"
       alt="Diagrama de Taskflow 1: Flujo de tareas para una acción específica del usuario."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Taskflow 1.
  </figcaption>
</figure>


**Wireflow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/flujos/Wireflow1.png"
       alt="Diagrama de Wireflow 1: Combinación de wireframes y flujo de interacción del usuario."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 2:</strong> Wireflow 1.
  </figcaption>
</figure>


### **User Goal 2**:
Como dueño de un negocio que utiliza equipos de refrigeración quiero lograr administrar los nuevos equipos que registre.

**Task Flow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/flujos/taskflow2.png"
       alt="Diagrama de Taskflow 2: Flujo de tareas para un proceso de usuario."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 3:</strong> Taskflow 2.
  </figcaption>
</figure>


**Wireflow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/flujos/Wireflow2.png"
       alt="Diagrama de Wireflow 2: Representación visual del flujo de usuario entre pantallas."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 4:</strong> Wireflow 2.
  </figcaption>
</figure>


### **User Goal 3**:
Como dueño de un negocio que utiliza equipos de refrigeración quiero revisar las estadísticas completas de mis equipos.

**Task Flow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/flujos/taskflow3.png"
       alt="Diagrama de Taskflow 3: Secuencia de tareas para una interacción compleja."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 5:</strong> Taskflow 3.
  </figcaption>
</figure>


**Wireflow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/flujos/Wireflow3.png"
       alt="Diagrama de Wireflow 3: Detalle del flujo de usuario con elementos de la interfaz."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 6:</strong> Wireflow 3.
  </figcaption>
</figure>


### **User Goal 4**:
Como proveedor de equipos de refrigeración quiero estar pendiente de los ordenes de pedios de mis clientes.

**Task Flow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/flujos/taskflow4.png"
       alt="Diagrama de Taskflow 4: Flujo de tareas para la interacción del usuario con el sistema."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 9:</strong> Taskflow 4.
  </figcaption>
</figure>


**Wireflow**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/flujos/Wireflow4.png"
       alt="Diagrama de Wireflow 4: Resumen visual del flujo de interacción y las pantallas clave."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 10:</strong> Wireflow 4.
  </figcaption>
</figure>

    
  ### 3.1.4.3. Mobile Applications Mock-ups
---

##  Cliente

### **Inicio – Clientes**
<img src="assets/chapter03/mockupss/Inicio-Clientes-1.png"
     alt="Mockup de la pantalla de inicio para clientes."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 18:</strong> Mockup 18 - Inicio del cliente.
</figcaption>
El diseño presenta una jerarquía visual clara mediante el uso de íconos y tipografía contrastante. Los elementos principales están centrados para priorizar la interacción rápida e intuitiva. La arquitectura de información organiza las funciones esenciales en bloques reconocibles y de fácil acceso.

---

### **Mis Equipos – Clientes (v1)**
<img src="assets/chapter03/mockupss/MisEquipos-Clientes-2.png"
     alt="Mockup Mis Equipos cliente versión 1."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 19:</strong> Mockup 19 - Mis Equipos (v1).
</figcaption>
El uso de tarjetas independientes y márgenes amplios mejora la legibilidad del contenido. Los colores y botones refuerzan la accesibilidad visual del usuario. La arquitectura de información estructura la lista de equipos de manera vertical para favorecer la exploración progresiva.

---

### **Mis Equipos – Clientes (v2)**
<img src="assets/chapter03/mockupss/MisEquipos-Clientes-3.png"
     alt="Mockup Mis Equipos cliente versión 2."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 20:</strong> Mockup 20 - Mis Equipos (v2).
</figcaption>
Los componentes mantienen una disposición equilibrada, generando consistencia visual. La tipografía uniforme y los botones amplios promueven la inclusión y accesibilidad. La arquitectura jerarquiza la información según relevancia: primero el equipo, luego las acciones asociadas.


---

### **Mis Equipos – Clientes (v5)**
<img src="assets/chapter03/mockupss/MisEquipos-Clientes-6.png"
     alt="Mockup Mis Equipos cliente versión 5 con indicador de acción rápida."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 23:</strong> Mockup 23 - Mis Equipos (v5).
</figcaption>
Los indicadores visuales permiten identificar rápidamente el estado de cada dispositivo. El diseño prioriza accesos táctiles grandes y colores de alto contraste. La arquitectura de información muestra los datos técnicos de manera ordenada y comprensible.

---

### **Control de Equipo – Cliente (v1)**
<img src="assets/chapter03/mockupss/ControlEquipo-Cliente-1.png"
     alt="Mockup Control de Equipo cliente versión 1 con botón Back y analíticas."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 24:</strong> Mockup 24 - Control de Equipo (v1).
</figcaption>
Los valores y gráficas se presentan con equilibrio visual y alineación precisa. Se prioriza la inclusión mediante tipografía grande y botones accesibles. La arquitectura divide la información en secciones analíticas e informativas para una lectura eficiente.

---

### **Analytics – Cliente (con datos)**
<img src="assets/chapter03/mockupss/Analytics-Cliente-1.png"
     alt="Mockup de panel Analytics con gráficos y KPIs."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 27:</strong> Mockup 27 - Analytics (con datos).
</figcaption>
Los gráficos utilizan colores distintivos para resaltar tendencias. La legibilidad se garantiza mediante etiquetas claras y coherentes. La estructura jerarquiza los indicadores de desempeño, permitiendo un análisis progresivo de la información.

---

### **Add Equipment – Cliente**
<img src="assets/chapter03/mockupss/AddEquipment-Cliente.png"
     alt="Mockup de formulario para agregar equipo del cliente."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 28:</strong> Mockup 28 - Add Equipment.
</figcaption>
El formulario aplica alineación vertical y márgenes amplios para reducir carga cognitiva. Los campos son claros y de fácil interacción, garantizando accesibilidad. La estructura divide la información en secciones lógicas: identificación, consumo y ubicación.

---

### **Manage Equipments – Cliente (lista)**
<img src="assets/chapter03/mockupss/ManageEquipment-Cliente.png"
     alt="Mockup de listado de equipos administrables del cliente."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 29:</strong> Mockup 29 - Manage Equipments (lista).
</figcaption>
El contraste de botones primarios y secundarios establece jerarquía visual. Los tamaños amplios y tipografía uniforme facilitan la interacción inclusiva. La arquitectura organiza la lista por estado operativo, optimizando la navegación entre registros.

---

### **Manage Equipments – Cliente (confirmación)**
<img src="assets/chapter03/mockupss/ManageEquipment-Cliente-2.png"
     alt="Mockup de confirmación de eliminación de equipo."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 30:</strong> Mockup 30 - Confirmación de eliminación.
</figcaption>
El diálogo resalta la acción principal mediante color y contraste. Se emplea lenguaje directo y tipografía clara para accesibilidad cognitiva. La arquitectura de información presenta la acción y su confirmación en un flujo coherente.

---

### **Manage Equipments – Cliente (feedback)**
<img src="assets/chapter03/mockupss/ManageEquipment-Cliente-1.png"
     alt="Mockup de feedback de eliminación exitosa en Manage Equipments."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 31:</strong> Mockup 31 - Feedback de acción completada.
</figcaption>
El mensaje de confirmación usa jerarquía tipográfica para indicar éxito. Los colores y el ícono generan una respuesta visual clara e inmediata. La información se presenta centrada y de manera secuencial, reduciendo el esfuerzo del usuario.

---

### **Estado de Cuenta – Clientes**
<img src="assets/chapter03/mockupss/EstadoCuenta-Clientes-1.png"
     alt="Mockup del estado de cuenta del cliente con items y estado."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 32:</strong> Mockup 32 - Estado de Cuenta (cliente).
</figcaption>
La tabla utiliza líneas y contraste para una lectura ordenada y fluida. Se prioriza la inclusión visual mediante fuentes grandes y colores claros. La arquitectura de información presenta primero el saldo general y luego los detalles específicos.

---

### **Mi Cuenta – Clientes (v1)**
<img src="assets/chapter03/mockupss/Micuenta-Clientes-2.png"
     alt="Mockup Mi Cuenta cliente versión simple."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 33:</strong> Mockup 33 - Mi Cuenta (simple).
</figcaption>
El diseño equilibra texto e iconografía para una lectura clara y directa. Los espacios amplios y la alineación centrada mejoran la usabilidad. La información del perfil se agrupa jerárquicamente, facilitando la gestión de datos personales.

---

### **Mi Cuenta – Clientes (v2)**
<img src="assets/chapter03/mockupss/Micuenta-Clientes-3.png"
     alt="Mockup Mi Cuenta cliente con ofertas de upgrade de plan."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 34:</strong> Mockup 34 - Mi Cuenta (con planes).
</figcaption>
Se aplican tarjetas de color con equilibrio y consistencia visual. Los textos informativos son legibles y contrastados, favoreciendo la accesibilidad. La arquitectura divide la vista entre información personal y opciones de mejora de plan.

---

### **Notificaciones – Clientes**
<img src="assets/chapter03/mockupss/Notificaciones-Clientes-1.png"
     alt="Mockup de notificaciones del cliente con acciones de lectura."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 35:</strong> Mockup 35 - Notificaciones (cliente).
</figcaption>
Las alertas se presentan con un formato uniforme y jerárquico. El alto contraste mejora la visibilidad en distintas condiciones de luz. La estructura prioriza las notificaciones más recientes y relevantes para una comprensión inmediata.

---

### **Contacto – Clientes (v1-v5)**
<img src="assets/chapter03/mockupss/Contacto-Clientes-6.png"
     alt="Mockups Contacto cliente versiones 2-6."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 36-40:</strong> Mockups 36–40 - Contacto (v1 a v5).
</figcaption>
Las diferentes versiones mantienen coherencia visual y orden lógico de la información. Se prioriza el contraste de íconos y texto para garantizar legibilidad. La arquitectura agrupa información de contacto, ubicación y redes de manera progresiva y accesible.

---

### **Registro – Clientes (v1-v2)**
<img src="assets/chapter03/mockupss/Registro Clientes-3.png"
     alt="Mockups registro clientes versiones 2 y 3."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 41-42:</strong> Mockups 41–42 - Registro (v1 y v2).
</figcaption>
El flujo de autenticación emplea formularios simplificados con botones de acción visibles. Las etiquetas descriptivas y la jerarquía visual mejoran la experiencia del usuario. La arquitectura guía la interacción desde el ingreso de datos hasta la validación final.

---

## Empresa

### **Inicio – Empresa**
<img src="assets/chapter03/mockupss/Inicio-Empresa-1.png"
     alt="Mockup pantalla de inicio para empresa."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 43:</strong> Mockup 43 - Inicio (empresa).
</figcaption>
El diseño profesional usa tipografía clara y bloques informativos equilibrados. El contraste visual resalta métricas y accesos directos. La arquitectura estructura los módulos de gestión según su prioridad operativa.

---

### **Inicio de Sesión – Empresa**
<img src="assets/chapter03/mockupss/Inicio de Sesión - Empresa-1.png"
     alt="Mockup Sign In de empresa."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 44:</strong> Mockup 44 - Inicio de Sesión (empresa).
</figcaption>
El diseño presenta equilibrio entre formulario e identidad visual de marca. La inclusión se garantiza mediante campos amplios y botones de alto contraste. La arquitectura de información organiza el flujo de acceso de manera lineal y sencilla.

---

### **Mis Equipos – Empresa**
<img src="assets/chapter03/mockupss/MisEquipos-Empresa-1.png"
     alt="Mockup Mis Equipos para empresa."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 45:</strong> Mockup 45 - Mis Equipos (empresa).
</figcaption>
Los equipos se agrupan visualmente por estado y disponibilidad. Los botones grandes y etiquetas descriptivas aseguran una interacción inclusiva. La información se dispone en tarjetas jerárquicas que optimizan la revisión técnica.

---

### **Mis Clientes / Técnicos – Empresa**
<img src="assets/chapter03/mockupss/MisClientes,Técnicos-Empresa-1.png"
     alt="Mockup gestión de clientes y técnicos para empresa."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 46:</strong> Mockup 46 - Mis Clientes y Técnicos.
</figcaption>
Se aplica alineación vertical y uso repetitivo de componentes para reforzar la consistencia. El contraste y la tipografía uniforme garantizan accesibilidad visual. La arquitectura de información separa los apartados de clientes y técnicos de forma clara.

---

### **Órdenes de Trabajo – Empresa**
<img src="assets/chapter03/mockupss/ÓrdenesDeTrabajo-Empresa-1.png"
     alt="Mockup de listado de órdenes de trabajo para empresa."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 47:</strong> Mockup 47 - Órdenes de Trabajo (empresa).
</figcaption>
El diseño agrupa órdenes por estado con un código de color fácilmente identificable. La iconografía y el espaciado facilitan la lectura en pantallas pequeñas. La arquitectura prioriza la visualización rápida de tareas activas y completadas.

---

### **Solicitudes – Empresa**
<img src="assets/chapter03/mockupss/Solicitudes-Empresa-1.png"
     alt="Mockup de solicitudes para empresa con aceptar/denegar."
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
<figcaption style="font-size: 0.9em; color: #555;">
  <strong>Figura 48:</strong> Mockup 48 - Solicitudes (empresa).
</figcaption>
El contraste cromático resalta las acciones principales de aprobación o rechazo. El uso de íconos intuitivos promueve accesibilidad cognitiva

---

  ### 3.1.4.3. Mobile Applications Mock-ups

---

### User Goal 1: 
- Como dueño de un negocio que utiliza equipos de refrigeración quiero estar pendiente del estado de cada equipo registrado.
<img src="assets/chapter03/flujos/UserGoal1.png"
     alt="User Goal 1"
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">

### User Goal 2:
- Como dueño de un negocio que utiliza equipos de refrigeración quiero revisar las estadisticas completas de mis equipos.
<img src="assets/chapter03/flujos/UserGoal2.png"
     alt="User Goal 2"
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">

### User Goal 3:
- Como dueño de un negocio que utiliza equipos de refrigeración quiero lograr administrar los nuevos equipos que registre.
 <img src="assets/chapter03/flujos/UserGoal3.png"
     alt="User Goal 3"
     style="max-width: 70%; height: auto; display: block; margin: 0 auto;">

   
    - 3.1.4.5. Mobile Applications Prototyping

# Capítulo IV: Product Implementation & Validation

### 4.2.1. Sprint 1
#### 4.2.1.1. Sprint Planning 1
A continuación, se presenta la planificación del sprint. En esta sección se expone la reunión inicial correspondiente, en la cual se establecieron los objetivos, se definieron los acuerdos y se revisaron los aspectos fundamentales que orientarían el desarrollo del sprint.

| **Sprint #**                    | **Sprint 1** |
|-------------------------------|-------------|
| **Sprint Planning Background**| En el sprint decidimos reunirnos para verificar el progreso de cada uno de los participantes y el progreso desde el punto de vista grupal, luego de ello buscamos formas y acciones de mejora. |
| **Date**                      | 6/10/25    |
| **Time**                      | 21:00 horas |
| **Location**                  | Via Discord |
| **Prepared By**               | Luis Angel Montañez Moreno |
| **Attendees**                 | Joseph Rodriguez, Sergio Aguirre, Victor Rojas, Maria Muñoz, Luis Montañez |
| **Sprint 1 Review Summary**     | Esta sección se dedicó a mejorar el código de Landing Page, desarrollar la aplicación móvil en Android Studio y la conexión con el Backend. |
| **Sprint 1 Retrospective Summary** | Todos los integrantes mencionaron tener aciertos en partes del código y en otras partes poder mejorar sus habilidades.  |
| **Sprint Goal & User Stories** |  |
| **Sprint 1 Goal**               | Nuestro enfoque está en implementar la landing page de Osito Polar y además de la aplicación móvil para Android siguiendo la estrategia nativa. Esta ofrecerá a los nuevos usuarios una interfaz clara, informativa y fácil de navegar que comunique los beneficios, servicios y características de la solución. Creemos que esto permitirá a los usuarios comprender de manera sencilla el valor que aporta, generando una primera experiencia positiva y sentando las bases para futuras funcionalidades. |
| **Sprint 1 Velocity**              | 15 |
| **Sum of Story Points**        | 21 |

#### 4.2.1.2. Sprint Backlog 1
Sprint # | Sprint 1 | | | | | | |
---------|----------|---------|-------|-----|----|----|---|
User Story | Work-Item / Task
ID | Title | ID | Title | Description | Estimation (Hours) | Assigned To | Status
US06| Agregar equipos | UT07 | Implementar estructura | Crear los componentes, entidades y servicios de los equipos | 4 | Sergio Aguirre | Done
US06| Agregar equipos | UT08 | Implementar operaciones CRUD |  Implementar las operaciones CREATE, READ, UPDATE AND DELETE de los equipos y cada uno de sus atributos | 3 | Maria Muñoz | Done
US06| Agregar equipos | UT09 | Agregar detalle | Implementar detalle de cada equipo | 3 | Victor Rojas | Done
US02| Iniciar sesión | UT10 | Funcionalidad de login | Implementar inicio de sesión | 3 | Luis Montañez | Done
US01| Registrar usuario | UT11 | Funcionalidad de registro | Implementar registro de un nuevo usuario | 3 | Joseph Rodriguez | Done
US23 | Visualizar propuesta de valor principal | UT-01 | Crear la sección 'Hero' | Añadir la sección donde se muestra nuestra propuesta de valor principal y las entidades que confían en nosotros | 4 | Joseph Rodriguez | Done
US23 | Visualizar propuesta de valor principal | UT02 | Añadir estilos CSS | Aplicar estilos según el diseño aprobado | 3 | Maria Muñoz | Done
US23 | Visualizar propuesta de valor principal | UT03 | Agregar efectos y validaciones según el diseño | Agregar efectos y validaciones según el diseño | 3 | Sergio Aguirre | Done
US24 | Explorar soluciones específicas para mi rubro | UT04 | Crear la sección "Beneficios" | Añadir la sección donde se visualizan las soluciones específicas a cada segmento (beneficio) | 2 | Victor Rojas | Done
US24 | Explorar soluciones específicas para mi rubro | UT05 | Añadir estilos CSS | Aplicar estilos según el diseño aprobado de "Beneficios" | 2 | Luis Montañez | Done
US24 | Explorar soluciones específicas para mi rubro | UT06 | Añadir interacciones con JS | Agregar efectos y validaciones según el diseño de Beneficios | 3 | Joseph Rodriguez | Done

<img src="assets/TF/backlog1.jpg" alt="backlog1" width="1000" height="auto">
link de Trello: https://trello.com/invite/b/692f781cba1286ca0c3a9a2f/ATTI2ac02e1ea3f375b9e1ccd8051faebc69F69AC868/osito-polar-sprint-backlog-1



#### 4.2.1.3. Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---------|----------|----------------|-----------|-------------|--------------|
| https://github.com/Equipo5-Aplicaciones-Moviles/OsitoPolar-App-Movil | login | c416779 | Feature: Add:Login / Add:Register / Add:Contact | Feature: Add:Login / Add:Register / Add:Contact | 09/10/25     |
| https://github.com/Equipo5-Aplicaciones-Moviles/OsitoPolar-App-Movil | login | cb74a69 | Initial import Android project | Initial import Android project | 09/10/25     |
| https://github.com/Equipo5-Aplicaciones-Moviles/OsitoPolar-App-Movil | rental | c8ddbe4 | feature: add rent equipment and account | feature: add rent equipment and account | 09/10/25     |
| https://github.com/Equipo5-Aplicaciones-Moviles/OsitoPolar-App-Movil | equipments | 44b786c | feature: add my machines | feature: add my machines | 10/10/25     |
| https://github.com/Equipo5-Aplicaciones-Moviles/OsitoPolar-App-Movil | equipments | ecd7da0 | feature: add drawer clients | feature: add drawer clients | 09/10/25     |
| https://github.com/Equipo5-Aplicaciones-Moviles/OsitoPolar-App-Movil | equipment | c45e1fe | feature: add preview in management | feature: add preview in management | 09/10/25     |
| https://github.com/Equipo5-Aplicaciones-Moviles/OsitoPolar-App-Movil | equipment | d2c0298 | feature: add equipment | feature: add equipment | 09/10/25     |
| https://github.com/Equipo5-Aplicaciones-Moviles/OsitoPolar-App-Movil | equipment | 7f4266c | feature: add rental equipment | feature: add rental equipment | 09/10/25     |
| https://github.com/Equipo5-Aplicaciones-Moviles/OsitoPolar-App-Movil | equipment | 45abbaa | feature: add equipment detail screen | feature: add equipment detail screen | 09/10/25     |
| https://github.com/Equipo5-Aplicaciones-Moviles/OsitoPolar-App-Movil | equipment | 91f8d44 | feature: add equipment dto | feature: add equipment dto | 09/10/25     |


#### 4.2.1.4. Testing Suite Evidence for Sprint Review

Suite de pruebas con xUnit, FluentAssertions y Moq. 21 pruebas unitarias (100% exitosas), 10 pruebas de integración implementadas. Cobertura: 94.7% en servicios críticos, 88.5% en lógica de dominio. Ejecución en 0.57 segundos.

<img width="844" height="597" alt="image" src="https://github.com/user-attachments/assets/80afee16-8b8f-4ad8-a40a-f78b155ef646" />

<img width="843" height="238" alt="image" src="https://github.com/user-attachments/assets/293107ca-e389-4b6e-8ec4-7dacd438daa1" />

Framework Pattern Driven Refactoring Report

#### 4.2.1.7. Software Deployment Evidence for Sprint Review

<img width="1202" height="607" alt="image" src="https://github.com/user-attachments/assets/8c830c06-9dc1-46a3-83e0-38a753051518" />

### Landing page deployment:
Para desplegar la landing page, es necesario cumplir con ciertos requisitos previos, como contar con una cuenta personal, una organización y un repositorio donde se alojarán los archivos. Una vez cumplidos estos requisitos, se pueden seguir los pasos detallados a continuación para realizar el despliegue:

1. Verificar que los archivos principales se encuentren en la raíz (root) del repositorio.
2. Asegurarse de que los archivos sigan las siguientes convenciones de nombres: "index.html" para la página principal, "styles.css" para los estilos, "script.js" para los scripts principales, "languages.js" para gestionar los textos en diferentes idiomas (español e inglés), y una carpeta llamada "assets/images" para las imágenes.
3. Subir los archivos al repositorio mediante un commit.
4. Acceder a la sección Settings > Pages y seleccionar el branch correspondiente, en este caso, "main".
5. Configurar la carpeta raíz (root) como la fuente de la página.
6. Esperar a que GitHub realice las verificaciones necesarias. Una vez finalizado el proceso, se generará un enlace que permitirá acceder a la landing page desplegada.

Adicionalmente, se implementó un archivo "languages.js" que contiene los textos en español e inglés. Este archivo es consumido por el script "main.js", el cual permite realizar el cambio de idioma dinámicamente en la landing page.ations Implementation

La URL que nos entrega Github Pages para acceder a la landing page es la siguiente:

### Github Pages:
#### 4.2.1.8. Team Collaboration Insights during Sprint

### 4.2.2. Sprint 2
#### 4.2.2.1. Sprint Planning 2
A continuación, se presenta la planificación del segundo sprint. En esta sección se expone la reunión inicial correspondiente, en la cual se establecieron los objetivos, se definieron los acuerdos y se revisaron los aspectos fundamentales que orientarían el desarrollo del sprint.

| **Sprint #**                    | **Sprint 2** |
|-------------------------------|-------------|
| **Sprint Planning Background**| En el sprint decidimos reunirnos para verificar el progreso de cada uno de los participantes y el progreso desde el punto de vista grupal, luego de ello buscamos formas y acciones de mejora. |
| **Date**                      | 8/11/25    |
| **Time**                      | 20:00 horas |
| **Location**                  | Via Discord |
| **Prepared By**               | Sergio Aguirre |
| **Attendees**                 | Joseph Rodriguez, Sergio Aguirre, Victor Rojas, Maria Muñoz, Luis Montañez |
| **Sprint 2 Review Summary**     | Esta sección se dedicó a avanzar el código en flutter de la aplicación móvil y que el backend esté completamente desplegado. |
| **Sprint 2 Retrospective Summary** | Todos los integrantes mencionaron tener aciertos en partes del código y en otras partes poder mejorar sus habilidades.  |
| **Sprint Goal & User Stories** |  |
| **Sprint 2 Goal**               | En este sprint, nos enfocamos en avanzar en el desarrollo de la aplicación móvil de Osito Polar para Android e iOS utilizando Flutter. Además, se ha completado el despliegue del backend al 100%, lo que asegura que ambos sistemas estén totalmente integrados y funcionales. Este avance nos permitirá ofrecer una experiencia de usuario más completa, asegurando la estabilidad y escalabilidad de la aplicación para las siguientes etapas del proyecto. |
| **Sprint 2 Velocity**              | 15 |
| **Sum of Story Points**        | 21 |

#### 4.2.2.2. Sprint Backlog 2

Sprint # | Sprint 2 | | | | | | |
---------|----------|---------|-------|-----|----|----|---|
User Story | Work-Item / Task
ID | Title | ID | Title | Description | Estimation (Hours) | Assigned To | Status
US06| Agregar equipos | UT01 | Implementar estructura | Crear los componentes, entidades y servicios de los equipos | 4 | Sergio Aguirre | Done
US06| Agregar equipos | UT02 | Implementar operaciones CRUD |  Implementar las operaciones CREATE, READ, UPDATE AND DELETE de los equipos y cada uno de sus atributos | 3 | Maria Muñoz | Done
US06| Agregar equipos | UT03 | Agregar detalle | Implementar detalle de cada equipo | 3 | Luis Montañez | Done
US02| Iniciar sesión | UT04 | Funcionalidad de login | Implementar inicio de sesión | 3 | Victor Rojas | Done
US01| Registrar usuario | UT05 | Funcionalidad de registro | Implementar registro de un nuevo usuario | 3 | Joseph Rodriguez | Done
US11| Asignar técnico | UT06 | Agregar técnico | Crear los componentes, entidades y servicios de los técnicos | 4 | Maria Muñoz | Done
US11| Asignar técnico | UT07 | Agregar técnico | Implementar las operaciones CREATE, READ, UPDATE AND DELETE de los técnicos y cada uno de sus atributos | 3 | Maria Muñoz | Done
US17| Visualizar equipos entregados | UT08 | Funcionalidad de visualización de equipos | Implementar la vista de los equipos que ya han sido entregados | 3 | Joseph Rodriguez | Done

<img src="assets/TF/backlog2.jpg" alt="backlog2" width="1000" height="auto">
link de Trello: https://trello.com/invite/b/692f7b1a04415c0e07643de9/ATTI707e69d8af5a0d84514ab740c99e58e19319BEFB/osito-polar-sprint-backlog-2


#### 4.2.2.3. Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---------|----------|----------------|-----------|-------------|--------------|
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | 22ea4bf | Feature: implement adding technician | Feature: adding technician | 12/11/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | 7bc2b0f | feature/service-requests into develop | feature/service-requests into develop | 12/11/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | c288201 | implement publish and unpublish equipment | implement publish and unpublish equipment | 11/12/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | 1da2d84 | feat: implement signin and register flow | feat: implement signin and register flow | 11/11/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | 968ad92 | implement get all service requests | feature: implement get all service requests | 10/11/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | 1efe93f | implement update equipment functionality with provider integration | implement update equipment functionality with provider integration | 10/11/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | c4ae565 | implement add equipment form and provider integration | feature: implement add equipment form and provider integration | 09/11/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | development | 70998c9 | feature: complete provider login Flow with dependency injection and shared prefs | feature: complete provider login Flow with dependency injection and shared prefs | 09/11/25     |

#### 4.2.2.4. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---------|----------|----------------|-----------|-------------|--------------|
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | 22ea4bf | Feature: implement adding technician | Feature: adding technician | 12/11/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | 7bc2b0f | feature/service-requests into develop | feature/service-requests into develop | 12/11/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | c288201 | implement publish and unpublish equipment | implement publish and unpublish equipment | 11/12/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | 1da2d84 | feat: implement signin and register flow | feat: implement signin and register flow | 11/11/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | 968ad92 | implement get all service requests | feature: implement get all service requests | 10/11/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | 1efe93f | implement update equipment functionality with provider integration | implement update equipment functionality with provider integration | 10/11/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | c4ae565 | implement add equipment form and provider integration | feature: implement add equipment form and provider integration | 09/11/25     |
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | development | 70998c9 | feature: complete provider login Flow with dependency injection and shared prefs | feature: complete provider login Flow with dependency injection and shared prefs | 09/11/25     |

#### 4.2.2.5. Execution Evidence for Sprint Review

**Pantalla inicial**  
<img src="assets/TF/pantalla1.jpg" height="400"><br>

**Pantalla de inicio de sesión**  
<img src="assets/TF/pantalla2login.jpg" height="400"><br>

**Pantalla de registro de usuario**  
<img src="assets/TF/pantalla3register.jpg" height="400"><br>

**Pantalla de Inicio**  
<img src="assets/TF/pantall4inicio.jpg" height="400"><br>

**Pantalla de Inventario**  
<img src="assets/TF/pantalla5inventario.jpg" height="400"><br>

**Pantalla de nuevo equipo**  
<img src="assets/TF/pantalla6nuevoequipo.jpg" height="400"><br>

**Pantalla de técnicos y clientes**  
<img src="assets/TF/pantalla7tecnicos.jpg" height="400"><br>

**Nuevo técnico**  
<img src="assets/TF/pantalla8nuevotecnico.jpg" height="400"><br>


#### 4.2.2.6. Services Documentation Evidence for Sprint Review

**OsitoPolarPlatform.api**

<img src="assets/TF/ositopolarswagger.jpg" height="400"><br>
<img src="assets/TF/workorders.jpg" height="400"><br>
<img src="assets/TF/profiles.jpg" height="400"><br>
<img src="assets/TF/equipments.jpg" height="400"><br>
<img src="assets/TF/technicians.jpg" height="400"><br>

#### 4.2.2.7. Software Deployment Evidence for Sprint Review
#### 4.2.2.8. Team Collaboration Insights during Sprint

### 4.2.3 Sprint 3

#### 4.2.3.1. Sprint Planning 3
A continuación, se presenta la planificación del tercer sprint. En esta sección se expone la reunión inicial correspondiente, en la cual se establecieron los objetivos, se definieron los acuerdos y se revisaron los aspectos fundamentales que orientarían el desarrollo del sprint.

| **Sprint #**                    | **Sprint 3** |
|-------------------------------|-------------|
| **Sprint Planning Background**| En el sprint decidimos reunirnos para verificar el progreso de cada uno de los participantes y el progreso desde el punto de vista grupal, luego de ello buscamos formas y acciones de mejora. |
| **Date**                      | 28/11/25    |
| **Time**                      | 20:00 horas |
| **Location**                  | Via Discord |
| **Prepared By**               | Sergio Aguirre |
| **Attendees**                 | Joseph Rodriguez, Sergio Aguirre, Victor Rojas, Maria Muñoz, Luis Montañez |
| **Sprint 3 Review Summary**     | Esta sección se dedicó a terminar las aplicaciones móviles tanto en flutter como en Android Studio y también que el backend esté completamente desplegado. |
| **Sprint 3 Retrospective Summary** | Todos los integrantes mencionaron tener aciertos en partes del código y en otras partes poder mejorar sus habilidades.  |
| **Sprint Goal & User Stories** |  |
| **Sprint 3 Goal**               | En este sprint, nos enfocamos en terminar la aplicación móvil de Osito Polar para Android e iOS utilizando Flutter. También se mejoró la aplicación para Android Studio. Además, se ha completado el despliegue del backend al 100%, lo que asegura que ambos sistemas estén totalmente integrados y funcionales. Este último sprint nos permitirá ofrecer la experiencia de usuario más completa, asegurando la estabilidad y escalabilidad de las aplicaciones móviles. |
| **Sprint 3 Velocity**              | 15 |
| **Sum of Story Points**        | 25 |

#### 4.2.3.3. Sprint Backlog 1

Sprint # | Sprint 3 | | | | | | |
---------|----------|---------|-------|-----|----|----|---|
User Story | Work-Item / Task
ID | Title | ID | Title | Description | Estimation (Hours) | Assigned To | Status
US05| Ver reporte de servicio realizado | UT01 | Implementar estructura | Crear los componentes, entidades y servicios de los reportes | 4 | Sergio Aguirre | In process
US05| Ver reporte de servicio realizado | UT02 | Implementar operaciones CRUD |  Implementar las operaciones CREATE, READ, UPDATE AND DELETE de los servicios realizados y cada uno de sus atributos | 3 | Maria Muñoz | In process
US09| Ver consumo energético | UT03 | Visualizar detalle de consumo | Implementar detalle del consumo energético para cada equipo e refrigeración | 3 | Luis Montañez | In process
US12| Ver historial de servicios | UT04 | Visualizar detalle de historial | Implementar visualizar el historial completo de los servicios realizados | 3 | Victor Rojas | In process
US31| Controlar encendido y apagado del equipo | UT05 | Funcionalidad de actualización de estado de equipo | Implementar encendido y apagado para equipos | 3 | Joseph Rodriguez | In process
US32| Ajustar temperatura del equipo | UT06 | Establecer temperatura óptima | Cambiar valores de temperatura de los equipos | 4 | Maria Muñoz | In process

<img src="assets/TF/backlog3.jpg" alt="backlog3" width="1000" height="auto">
link de Trello: https://trello.com/invite/b/692f7d038185a0f6b03f7c71/ATTId60a74a9af6f028c14403598e82c1558E82E2A6F/osito-polar-sprint-backlog-3

#### 4.3. Validation Interviews
#### 4.3.1. Diseño de Entrevistas

En esta sección se presentan los detalles de las entrevistas de validación realizadas.

### 5.3.1. Diseño de Entrevistas.

<h4>Objetivo de la Entrevista</h4>
<p>Validar la usabilidad, efectividad y propuesta de valor de la <strong>aplicación móvil OsitoPolar</strong> para los segmentos clave. Se evaluará si las funcionalidades cubren las necesidades operativas reales y si los flujos táctiles (tap, swipe, notificaciones push) son intuitivos para usuarios con distintos perfiles técnicos.</p>

<h4>Elementos de Validación</h4>
<ul>
  <li><strong>Onboarding / Pantalla de inicio (App):</strong> Claridad de la propuesta de valor, permisos (cámara/galería para fotos y QR, ubicación, notificaciones), acceso a funcionalidades clave y llamados a la acción.</li>
  <li><strong>Aplicación Móvil:</strong> Flujos críticos como registro de equipos (con escaneo QR/foto), solicitud de servicios, visualización de reportes, asignación de técnicos y recepción de alertas <em>push</em>.</li>
</ul>

<h4>User Flows a Validar</h4>

<h5>Para el Segmento: Negocios con Equipos de Refrigeración</h5>
<ol>
  <li>Registro y configuración inicial en el móvil</li>
  <li>Monitoreo y alertas <em>push</em></li>
  <li>Solicitud de servicios desde la app</li>
  <li>Visualización de reportes en el dispositivo</li>
  <li>Evaluación del servicio</li>
</ol>

<h5>Para el Segmento: Empresas Proveedoras de Servicios</h5>
<ol>
  <li>Recepción de solicitudes (inbox/push)</li>
  <li>Gestión y asignación de técnicos</li>
  <li>Historial técnico desde la app</li>
  <li>Generación y envío de reportes</li>
  <li>Gestión de cartera de clientes</li>
</ol>

<h4>Formato de Registro de Entrevista</h4>
<ul>
  <li>Nombre completo</li>
  <li>Edad</li>
  <li>Distrito de residencia</li>
  <li>Rol en su empresa</li>
  <li>Dispositivo utilizado para la prueba (Android/iOS)</li>
</ul>

<h3>Preguntas para el Segmento 1: Negocios que utilizan Equipos de Refrigeración</h3>
<ul>
  <li>¿De qué manera te resultó útil la información del <strong>onboarding</strong> de la app?</li>
</ul>

<h4>Registro y Gestión de Equipos</h4>
<ul>
  <li>¿Qué tan fácil fue registrar tus equipos de refrigeración desde el celular (foto/QR)?</li>
  <li>¿La información solicitada fue clara y necesaria?</li>
  <li>¿Hubo algún paso que te generó dudas?</li>
</ul>

<h4>Monitoreo y Alertas</h4>
<ul>
  <li>¿Cómo sentiste el proceso para acceder al estado de tus equipos en el móvil?</li>
  <li>¿De qué manera te sirvió la sección de alertas <em>push</em> de los equipos?</li>
  <li>¿Cómo afectarían estas alertas tu toma de decisiones?</li>
</ul>

<h4>Solicitudes de Servicio</h4>
<ul>
  <li>¿Cómo fue tu experiencia solicitando un servicio desde la app?</li>
  <li>¿La opción para programar mantenimiento estaba visible y disponible? ¿Qué te pareció su implementación?</li>
  <li>¿Cómo fue tu proceso al solicitar un tipo de servicio?</li>
</ul>

<h4>Visualización de Reportes</h4>
<ul>
  <li>¿De qué manera te ayudaron los reportes de los equipos a conocer su estado?</li>
  <li>¿Cómo te sirvieron los reportes de consumo energético para detectar posibles problemas?</li>
  <li>¿Qué agregarías o mejorarías en estos reportes (comparativas, recomendaciones, exportación)?</li>
</ul>

<h4>Evaluación del Servicio</h4>
<ul>
  <li>¿Fue sencillo dejar una evaluación después del servicio desde el móvil? ¿Cómo fue tu experiencia al usar esta funcionalidad?</li>
  <li>¿De qué manera consideras útil poder modificar tu evaluación si hubo cambios posteriores?</li>
</ul>

<h3>Preguntas para el Segmento 2: Empresas Proveedoras de Servicios</h3>

<h4>Recepción y Gestión de Solicitudes</h4>
<ul>
  <li>¿Puedes describir cómo es el proceso de recibir una nueva solicitud de servicio en la app y qué aspectos destacarías, tanto positivos como áreas de mejora?</li>
  <li>¿Cómo describirías tu experiencia al asignar un técnico a una solicitud de servicio desde el móvil, y qué elementos del procedimiento te resultaron más útiles o desafiantes?</li>
  <li>¿Cómo ha sido tu experiencia al realizar el seguimiento del estado de los servicios en tiempo real desde la app, y qué características consideras más valiosas o cuáles mejorarías?</li>
</ul>

<h4>Gestión de Técnicos</h4>
<ul>
  <li>¿Cómo describirías el procedimiento para asignar técnicos a las solicitudes de servicio en la app, y qué sugerencias tendrías para optimizar esta funcionalidad?</li>
  <li>¿Qué información sobre el desempeño de los técnicos encuentras en la app y cómo te ayuda? ¿Qué aspectos adicionales te gustaría ver (KPIs, rankings, rutas)?</li>
  <li>¿De qué manera el sistema de métricas de desempeño ha impactado en la gestión de tus técnicos, y qué mejoras sugerirías para hacerlo más útil?</li>
</ul>

<h4>Historial y Reportes Técnicos</h4>
<ul>
  <li>¿Cómo ha sido tu experiencia al acceder al historial técnico de los equipos atendidos desde el móvil, y qué aspectos te parecen efectivos o cuáles cambiarías?</li>
  <li>¿Cómo describirías la utilidad y claridad de los reportes generados por la app para tus clientes, y qué elementos crees que podrían mejorarse?</li>
  <li>¿Puedes contarme cómo es el proceso de generación automática de reportes en la app y qué aspectos consideras que funcionan bien o podrían optimizarse?</li>
</ul>

<h4>Gestión de Cartera de Clientes</h4>
<ul>
  <li>¿Cómo describirías tu experiencia al visualizar y gestionar la lista de clientes y sus servicios en la app, y qué funcionalidades destacarías o mejorarías?</li>
  <li>¿Qué tan sencillo o complejo ha sido filtrar información por estado del servicio o tipo de equipo en el móvil, y qué sugerencias tendrías para mejorar esta funcionalidad?</li>
</ul>

#### 4.3.2. Registro de Entrevistas
<h4>Objetivo de la Entrevista</h4>
<p>Validar la usabilidad, efectividad y propuesta de valor de la <strong>aplicación móvil OsitoPolar</strong> para los segmentos clave. Se evaluará si las funcionalidades cubren las necesidades operativas reales y si los flujos táctiles (tap, swipe, notificaciones push) son intuitivos para usuarios con distintos perfiles técnicos.</p>

<h4>Elementos de Validación</h4>
<ul>
  <li><strong>Onboarding / Pantalla de Inicio (App):</strong> Claridad en la propuesta de valor, permisos (cámara/galería para fotos y QR, notificaciones), accesos a funcionalidades clave, llamados a la acción.</li>
  <li><strong>Aplicación Móvil:</strong> Flujos críticos como registro de equipos (con escaneo de código/QR y fotos), solicitud de servicios, visualización de reportes, asignación de técnicos y recepción de alertas <em>push</em>.</li>
</ul>

<h4>User Flows a Validar</h4>

<h5>Para el Segmento: Negocios con Equipos de Refrigeración</h5>
<ol>
  <li>Registro y configuración inicial</li>
  <li>Monitoreo y alertas (push)</li>
  <li>Solicitud de servicios</li>
  <li>Visualización de reportes</li>
  <li>Evaluación del servicio</li>
</ol>

<h5>Para el Segmento: Empresas Proveedoras de Servicios</h5>
<ol>
  <li>Recepción de solicitudes (push/inbox)</li>
  <li>Gestión de técnicos</li>
  <li>Historial técnico</li>
  <li>Generación de reportes</li>
  <li>Gestión de cartera de clientes</li>
</ol>

<h4>Formato de Registro de Entrevista</h4>
<ul>
  <li>Nombre completo</li>
  <li>Edad</li>
  <li>Distrito de residencia</li>
  <li>Rol en su empresa</li>
  <li>Dispositivo utilizado para la prueba (Android/iOS)</li>
</ul>

<h3>Preguntas para el Segmento 1: Negocios que utilizan Equipos de Refrigeración</h3>
<ul>
  <li>¿De qué manera te pareció útil la información del onboarding en la app?</li>
</ul>
<h4>Registro y Gestión de Equipos</h4>
<ul>
  <li>¿Qué tan fácil fue registrar tus equipos de refrigeración desde el celular (foto/QR)?</li>
  <li>¿La información solicitada fue clara y necesaria?</li>
  <li>¿Hubo algún paso que te generó dudas?</li>
</ul>

<h4>Monitoreo y Alertas</h4>
<ul>
  <li>¿Cómo sentiste el proceso para acceder al estado de tus equipos en el móvil?</li>
  <li>¿De qué manera te sirvió la sección de alertas <em>push</em> de los equipos?</li>
  <li>¿Cómo afectarían estas alertas tu toma de decisiones?</li>
</ul>

<h4>Solicitudes de Servicio</h4>
<ul>
  <li>¿Cómo fue tu experiencia solicitando un servicio desde la app?</li>
  <li>¿La opción para programar mantenimiento estaba visible y disponible? ¿Qué te pareció su implementación?</li>
  <li>¿Cómo fue tu proceso al solicitar un tipo de servicio?</li>
</ul>

<h4>Visualización de Reportes</h4>
<ul>
  <li>¿De qué manera te ayudaron los reportes de los equipos a conocer su estado?</li>
  <li>¿Cómo es que los reportes de consumo energético te sirvieron para detectar posibles problemas?</li>
  <li>¿Qué agregarías o mejorarías en estos reportes?</li>
</ul>

<h4>Evaluación del Servicio</h4>
<ul>
  <li>¿Fue sencillo dejar una evaluación después del servicio desde el móvil? ¿Cómo fue tu experiencia al usar esta funcionalidad?</li>
  <li>¿De qué manera consideras útil poder modificar tu evaluación si hubo cambios posteriores?</li>
</ul>

<h3>Preguntas para el Segmento 2: Empresas Proveedoras de Servicios</h3>

<h4>Recepción y Gestión de Solicitudes</h4>
<ul>
  <li>¿Puedes describir cómo es el proceso de recibir una nueva solicitud de servicio en la app y qué aspectos destacarías, tanto positivos como áreas de mejora?</li>
  <li>¿Cómo describirías tu experiencia al asignar un técnico a una solicitud de servicio, y qué elementos del procedimiento te resultaron más útiles o desafiantes?</li>
  <li>¿Cómo ha sido tu experiencia al realizar el seguimiento del estado de los servicios en tiempo real, y qué características consideras más valiosas o cuáles mejorarías?</li>
</ul>

<h4>Gestión de Técnicos</h4>
<ul>
  <li>¿Cómo describirías el procedimiento para asignar técnicos a las solicitudes de servicio, y qué sugerencias tendrías para optimizar esta funcionalidad?</li>
  <li>¿Qué información sobre el desempeño de los técnicos encuentras en la app, y cómo te ayuda o qué aspectos adicionales te gustaría ver?</li>
  <li>¿De qué manera el sistema de métricas de desempeño ha impactado en la gestión de tus técnicos, y qué mejoras sugerirías para hacerlo más útil?</li>
</ul>

<h4>Historial y Reportes Técnicos</h4>
<ul>
  <li>¿Cómo ha sido tu experiencia al acceder al historial técnico de los equipos atendidos, y qué aspectos te parecen efectivos o cuáles cambiarías?</li>
  <li>¿Cómo describirías la utilidad y claridad de los reportes generados para tus clientes, y qué elementos crees que podrían mejorarse?</li>
  <li>¿Puedes contarme cómo es el proceso de generación automática de reportes en la app y qué aspectos consideras que funcionan bien o podrían optimizarse?</li>
</ul>

<h4>Gestión de Cartera de Clientes</h4>
<ul>
  <li>¿Cómo describirías tu experiencia al visualizar y gestionar la lista de clientes y sus servicios, y qué funcionalidades destacarías o mejorarías?</li>
  <li>¿Qué tan sencillo o complejo ha sido filtrar información por estado del servicio o tipo de equipo, y qué sugerencias tendrías para mejorar esta funcionalidad?</li>
</ul>


---

### 5.3.2. Registro de Entrevistas.
En esta sección tenemos el análisis de las entrevistas por segmentos objetivos.

<br>


<br><br>

| Entrevista 1: Negocio que utiliza máquinas de refrigeración (App móvil) |  |
|---|---|
| **Nombre Entrevistado** | **Luis Salazar Cotrina** |
| **Edad** | 28 |
| **Profesión** | Restaurante familiar – Comida criolla |
| **Departamento** | Lima |
| **Dispositivo utilizado** | **Móvil (iOS)** |
| <img width=620 src="assets/chapter-05/E1.jpng"/> | [Entrevista 1](#) |
| **Duración de la Entrevista** | 0:00 - 6:05 |
| **Análisis de la Entrevista** |  |
| **Registro y Gestión de Equipos** | Organizó varias congeladoras por **zona** con **tags**; sugiere **duplicar** equipo como plantilla. |
| **Monitoreo y Alertas** | Sección “**clave**”; detectó **escarcha** por aumento de consumo. Pide **resumen diario** (además del push). |
| **Solicitudes de Servicio** | Programó mantenimiento con CTA visible desde el **home**; sugiere **reprogramar** con un tap. |
| **Visualización de Reportes** | Halló anomalías en **horas valle**; útil **panel semanal** para ahorro energético. |
| **Evaluación del Servicio** | Transparente; pudo **modificar rating** tras segunda visita. |

<br>

| Entrevista 2: Proveedores de equipos de refrigeración (App móvil) |  |
|---|---|
| **Nombre Entrevistado** | **Piero Medina Rojas** |
| **Edad** | 30 |
| **Profesión** | Coordinador de servicios |
| **Departamento** | Lima |
| **Dispositivo utilizado** | **Móvil (Android)** |
| <img width=620 src="assets/chapter-05/E2.jpg"/> | [Entrevista 2](#) |
| **Duración de la Entrevista** | 0:00 - 7:10 |
| **Análisis de la Entrevista** |  |
| **Recepción y Gestión de Solicitudes** | Inbox móvil **claro** (cliente, equipo, **ETA sugerido**). Falta **detalle técnico obligatorio** (fotos, lectura de temperatura) para evitar llamadas. |
| **Gestión de Técnicos** | Asignación **intuitiva** por **especialidad** y **ubicación**. Pide **rutas por zona** y **ranking** interno con KPIs. |
| **Historial y Reportes Técnicos** | Acceso ágil por equipo/cliente; solicita **exportación PDF/Excel** y **campos personalizables**. |
| **Gestión de Cartera de Clientes** | Vista ordenada (estado, facturación, servicios). Pide **alertas automáticas** para mantenimientos y **etiquetas** por cliente. |

<br>

| Entrevista 3: Proveedores de equipos de refrigeración (App móvil) |  |
|---|---|
| **Nombre Entrevistado** | **Sandra Ramos Delgado** |
| **Edad** | 23 |
| **Profesión** | Supervisora operativo |
| **Departamento** | Lima |
| **Dispositivo utilizado** | **Móvil (iOS)** |
| <img width=1000 src="assets/chapter-05/E3.jpg"/> | [Entrevista 3](#) |
| **Duración de la Entrevista** | 0:00 - 6:05 |
| **Análisis de la Entrevista** |  |
| **Recepción y Gestión de Solicitudes** | Panel **visual y rápido**; sugiere campos técnicos **obligatorios** (foto etiqueta, temperatura medida) en la solicitud. |
| **Gestión de Técnicos** | Útil ver **especialidades**; pide **multi-asignación por zona** y **capacidad diaria** por técnico. |
| **Historial y Reportes Técnicos** | Usa el historial para evitar errores repetidos; solicita **gráficos comparativos** (consumo/temperatura) por período. |
| **Gestión de Cartera de Clientes** | Ordenada; propone **carpetas** para clientes enterprise y **push** por vencimiento de mantenimiento programado. |

<br>

| Entrevista 4: Proveedores de equipos de refrigeración (App móvil) |  |
|---|---|
| **Nombre Entrevistado** | **Giancarlo Rodriguez Pastor** |
| **Edad** | 26 |
| **Profesión** | Supervisor operativo |
| **Departamento** | Lima |
| **Dispositivo utilizado** | **Móvil (Android)** |
| <img width=1000 src="assets/chapter-05/fotoentrevista1.jpg"/> | [Entrevista 4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202223811_upc_edu_pe/IQBQ8RnA8EfyRY3gUcS-2zDHATy9aSJ6EMdTlVbBVSZbDU8?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=7hh1k6) |
| **Duración de la Entrevista** | 0:00 - 11:12 |
| **Análisis de la Entrevista** |  |
| **Recepción y Gestión de Solicitudes** | Panel **visual y rápido**; sugiere campos técnicos **obligatorios** como foto en la creación de un nuevo equipo. |
| **Gestión de Técnicos** | Útil ver **especialidades**; pide **multi-asignación por zona** y **capacidad diaria** por técnico. |
| **Historial y Reportes Técnicos** | Usa el historial para evitar errores repetidos; solicita **gráficos comparativos** (consumo/temperatura) por período. |
| **Gestión de Cartera de Clientes** | Ordenada; propone **carpetas** para clientes enterprise, **fotos** y **push** por vencimiento de mantenimiento programado. |

<br>

| Entrevista 5: Proveedores de equipos de refrigeración (App móvil) |  |
|---|---|
| **Nombre Entrevistado** | **Ingrid Pacheco Uribe** |
| **Edad** | 25 |
| **Profesión** | Supervisor operativo |
| **Departamento** | Lima |
| **Dispositivo utilizado** | **Móvil (IOS)** |
| <img width=1000 src="assets/chapter-05/fotoentrevista2.jpg"/> | [Entrevista 5](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202223811_upc_edu_pe/IQDKzhqwoyDnR7vH-daZppEgAbuTKxdHXvEELZmnxxAWkNQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=KPA7rg) |
| **Duración de la Entrevista** | 0:00 - 10:58 |
| **Análisis de la Entrevista** |  |
| **Recepción y Gestión de Solicitudes** | Panel **visual y rápido**; sugiere campos técnicos **obligatorios** (foto etiqueta, temperatura medida) en la solicitud. |
| **Gestión de Técnicos** | Útil ver **especialidades**; pide **ordenar por nombre o por especialidad** . |
| **Historial y Reportes Técnicos** | Usa el historial para evitar errores repetidos; solicita **Historial por equipo** (consumo/temperatura) en un período. |
| **Gestión de Cartera de Clientes** | Ordenada; propone **edición** para clientes en sus datos y **push** por vencimiento de mantenimiento programado. |

<br>

| Entrevista 6: Proveedores de equipos de refrigeración (App móvil) |  |
|---|---|
| **Nombre Entrevistado** | **Giusephi Carlos Lavado** |
| **Edad** | 25 |
| **Profesión** | Supervisor de planta |
| **Departamento** | Lima |
| **Dispositivo utilizado** | **Móvil (IOS)** |
| <img width=1000 src="assets/chapter-05/fotoentrevista3.jpg"/> | [Entrevista 6](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202223811_upc_edu_pe/IQACSe8PTr90QLxKymrskpiaATLKxd_lC1O_rwzh8mQficE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=5icPCQ) |
| **Duración de la Entrevista** | 0:00 - 10:25 |
| **Análisis de la Entrevista** |  |
| **Recepción y Gestión de Solicitudes** | Panel **visual y rápido**; sugiere menos campos técnicos **obligatorios** y más facilidad para crear una solicitud |
| **Gestión de Técnicos** | Útil ver **especialidades**; pide **multi-asignación por zona** por técnico. |
| **Historial y Reportes Técnicos** | Usa el historial para evitar errores repetidos; solicita **cambiar temperatura** para cada equipo. |
| **Gestión de Cartera de Clientes** | Ordenada; propone **carpetas** para clientes enterprise y **push** por vencimiento de mantenimiento programado. |

#### 4.3.3. Evaluaciones según heurísticas
**UX Heuristics & Principles Evaluation**  
**Usability – Inclusive Design – Information Architecture**

**Información del Proyecto**
- **Carrera:** Ingeniería de Software
- **Curso:** Aplicaciones Web
- **Auditor:** Inteligencia Artesanal
- **Cliente:** Inteligencia Artesanal
- **Site o App a Evaluar:** OsitoPolar (aplicación móvil iOS/Android)

---

### Tareas a Evaluar

**Para el Segmento Negocios que utilizan equipos de refrigeración (App móvil):**
1. Registro y gestión de equipos (foto/QR, tags, plantillas)
2. Monitoreo y alertas (push, silenciamiento por horario)
3. Solicitudes de servicio técnico (programar/reprogramar, chat breve)
4. Visualización de reportes (consumo/estado, recomendaciones)

**Para el Segmento Empresas proveedoras de servicios y equipos de refrigeración (App móvil):**
1. Recepción y gestión de solicitudes (inbox/push con datos técnicos)
2. Asignación y gestión de técnicos (especialidad/zona, capacidad diaria)
3. Visualización de historial y reportes técnicos (exportación, campos personalizables)
4. Gestión de cartera de clientes (alertas de mantenimiento, carpetas/etiquetas)

---

### Escala de Severidad

| Nivel | Descripción |
|------:|-------------|
| 1 | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| 2 | Problema menor: puede ocurrir con más frecuencia o es más difícil de superar para el usuario. Debería tener una prioridad baja para resolverse en la próxima versión. |
| 3 | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlo. Debería tener alta prioridad para corregirse. |
| 4 | Problema muy grave: error que impide al usuario continuar utilizando la herramienta. Debe corregirse antes del lanzamiento. |

---

### Tabla Resumen

| # | Problema                                                                                          | Escala de severidad | Heurística/Principio violado                           | Tarea evaluada                                  |
|---|---------------------------------------------------------------------------------------------------|:-------------------:|--------------------------------------------------------|-------------------------------------------------|
| 1 | Formulario de solicitud no exige **datos técnicos mínimos** (foto, lectura de temperatura, síntoma) | 3 | Prevención de errores / Ayuda y documentación          | Recepción y gestión de solicitudes              |
| 2 | Sin **exportación** de reportes (PDF/Excel)                                                        | 2 | Control del usuario / Flexibilidad                     | Historial y reportes técnicos                   |
| 3 | No se pueden **modificar rutas**/reagrupar visitas por zona con facilidad                          | 2 | Flexibilidad y eficiencia de uso                       | Gestión de técnicos                             |
| 4 | Falta **ranking/KPIs** y **gráficos comparativos** por técnico                                     | 2 | Visibilidad del estado del sistema                     | Gestión de técnicos                             |
| 5 | Reportes sin **sugerencias automáticas** (ahorro/diagnóstico)                                      | 3 | Ayuda y documentación / Reconocimiento antes que recuerdo | Visualización de reportes                    |
| 6 | No existen **alertas automáticas** para **mantenimientos programados**                             | 3 | Prevención de errores / Eficiencia                      | Cartera de clientes                             |
| 7 | Sin **carpetas/etiquetas** personalizadas para clientes con alta carga                             | 2 | Flexibilidad y eficiencia de uso                       | Cartera de clientes                             |
| 8 | Falta **silenciamiento programado** de **notificaciones push** por horarios                        | 2 | Control y libertad del usuario                         | Monitoreo y alertas (push)                      |
| 9 | **Reprogramación** de citas no está disponible en **un toque**                                     | 2 | Minimizar la carga / Eficiencia                         | Solicitudes de servicio                          |
|10 | **Registro de equipos** podría ser más veloz (duplicar como **plantilla** / **autocompletar** por marca) | 1 | Eficiencia de uso / Consistencia y estándares          | Registro y gestión de equipos                   |
|11 | Falta **resumen diario** de alertas por **WhatsApp/Email** además del push                         | 1 | Flexibilidad / Acceso a la información                  | Monitoreo y alertas                              |
|12 | Ausencia de **chat breve** para coordinar con técnico desde la solicitud                           | 2 | Visibilidad/Feedback / Correspondencia con el mundo real | Solicitudes de servicio                       |

---

### Descripción de Problemas

**Problema #1**
- **Tarea Evaluada:** Recepción y gestión de solicitudes  
- **Recomendación:** Hacer obligatorios **foto**, **lectura de temperatura** y **descripción breve** del síntoma; plantillas por tipo de falla.

**Problema #2**
- **Tarea Evaluada:** Historial y reportes técnicos  
- **Recomendación:** Añadir **exportación PDF/Excel** y **compartir** desde móvil; permitir filtros por rango de fechas y cliente.

**Problema #3**
- **Tarea Evaluada:** Gestión de técnicos  
- **Recomendación:** Habilitar **arrastrar/soltar** para reordenar rutas, **agrupación por zona**, y vista de **mapa** con turnos.

**Problema #4**
- **Tarea Evaluada:** Gestión de técnicos  
- **Recomendación:** Dashboard con **KPI** (SLA, 1ª visita resuelta, NPS/CSAT), **ranking** mensual y **gráficos** por tipo de equipo.

**Problema #5**
- **Tarea Evaluada:** Visualización de reportes  
- **Recomendación:** Motor de **recomendaciones** (p. ej., “alto consumo nocturno → sugerir horario eco, revisión de sellos”).

**Problema #6**
- **Tarea Evaluada:** Gestión de cartera de clientes  
- **Recomendación:** **Alertas** automáticas por **mantenimiento programado** (push/email/WhatsApp) con confirmación de cita.

**Problema #7**
- **Tarea Evaluada:** Gestión de cartera de clientes  
- **Recomendación:** **Carpetas/Tags** por cliente enterprise, estado y tipo de equipo; búsquedas guardadas.

**Problema #8**
- **Tarea Evaluada:** Monitoreo y alertas (push)  
- **Recomendación:** **Modo silencioso** por horario/zonas (ej. madrugada) y excepciones por alertas críticas.

**Problema #9**
- **Tarea Evaluada:** Solicitudes de servicio  
- **Recomendación:** **Reprogramar en 1 toque**, manteniendo historial; notificar automáticamente a cliente y técnico.

**Problema #10**
- **Tarea Evaluada:** Registro y gestión de equipos  
- **Recomendación:** **Duplicar como plantilla**, **autocompletar** modelo al seleccionar marca, y robustecer **escaneo QR** en baja luz.

**Problema #11**
- **Tarea Evaluada:** Monitoreo y alertas  
- **Recomendación:** **Resumen diario** de eventos vía **WhatsApp/Email** configurable por usuario.

**Problema #12**
- **Tarea Evaluada:** Solicitudes de servicio  
- **Recomendación:** **Chat breve** in-app entre cliente y técnico/coordinador con mensajes predefinidos (llegada, reprogramación, foto).

---

### User Flows a Validar

**Para el Segmento Negocios que utilizan equipos de refrigeración (App móvil):**
1. **Registro de vitrinas/congeladoras** con **foto/QR**, uso de **tags** y **duplicado como plantilla**.  
2. **Gestión y visualización de alertas** por temperatura/puerta abierta con **silenciamiento programado** y **resumen diario**.  
3. **Solicitud y evaluación de técnicos** desde la misma interfaz, con **reprogramación en 1 toque** y **chat breve**.  
4. **Consulta de reportes** de consumo/estado con **recomendaciones automáticas**.

**Para el Segmento Empresas proveedoras de servicios y equipos de refrigeración (App móvil):**
1. **Recepción detallada** de solicitudes (con **foto + temperatura + descripción** obligatorias).  
2. **Asignación eficiente** de técnicos por **especialidad/zona** y **capacidad diaria**, con **reordenamiento de rutas**.  
3. **Revisión de historial técnico** y **descarga/exportación** de reportes (PDF/Excel) con **campos personalizables**.  
4. **Gestión avanzada por cliente** con **alertas de mantenimiento programado** y **carpetas/etiquetas** personalizadas.

---

## Conclusiones

A lo largo del desarrollo del modelo de negocio digital OsitoPolar, hemos logrado validar la necesidad real y urgente de soluciones tecnológicas en el sector de refrigeración, tanto en los negocios que dependen de estos equipos como en las empresas proveedoras de servicios técnicos.
El proceso de investigación, entrevistas y análisis ha revelado importantes hallazgos que refuerzan la relevancia de nuestra propuesta de valor.

Desde el análisis de entrevistas, logramos comprobar:
- Existe una falta generalizada de control y monitoreo sobre los equipos de refrigeración, lo cual genera pérdidas económicas importantes.
- La mayoría de los negocios revisa de manera manual el estado de sus equipos, mientras que los técnicos/empresarios trabajan con herramientas desorganizadas (WhatsApp, Excel, llamadas).
- Todos los entrevistados manifestaron interés por una solución digital que centralice la información, agilice la atención y brinde trazabilidad técnica.

Las hipótesis planteadas durante el proceso Lean UX fueron validadas:
- Los usuarios consideran útil una herramienta con alertas automáticas, historial técnico y reportes.
- Existe disposición a pagar por el servicio, siempre que el valor sea percibido claramente en ahorro de pérdidas o tiempo.
- La diferencia competitiva de OsitoPolar —automatización, trazabilidad y facilidad de uso— fue bien recibida y genera ventaja frente a competidores más rígidos o complejos.

Se logró validar las necesidades de nuestros usuarios objetivos y diseñar un producto más alineado a ellos gracias a múltiples herramientas como el User Persona, User Task Matrix, As-Is y To-Be Scenarios.
A partir de esto hemos desarrollado historias de usuario que nos servirán para tener en cuenta las funcionalidades que implementaremos en las siguientes tareas. Hemos diseñado también nuestra Landing Page y Web Aplication en herramientas de diseño colaborativas.

Algunas recomendaciones que tomamos en cuenta que podrían impulsar el desarrollo y crecimiento en el mercado de OsitoPolar son:
- Desarrollar un MVP centrado en funciones clave: alertas, historial técnico, gestión de citas y reportes.
- Realizar pruebas piloto en campo con usuarios reales antes del lanzamiento masivo.
- Consolidar alianzas con proveedores locales, para lograr una adopción más rápida y posicionar la plataforma como un estándar del sector.

Este trabajo ha demostrado que OsitoPolar no solo resuelve un problema real, sino que tiene el potencial de transformar la forma en que se gestiona la refrigeración comercial y técnica en el Perú. Los próximos pasos deberán enfocarse en escalar esta solución de manera sostenible y centrada en el usuario.


## Bibliografía

- Axios. (s.f.). *Axios: Promise based HTTP client for the browser and node.js*. Recuperado el 10 de julio de 2025, de https://axios-http.com/docs/intro

- Cohn, M. (s.f.). *User stories articles*. Mountain Goat Software. Recuperado el 10 de julio de 2025, de https://www.mountaingoatsoftware.com/blog/tag/user-stories

- Conventional Commits. (s.f.). *Conventional commits*. Recuperado el 10 de julio de 2025, de https://www.conventionalcommits.org/

- Google. (s.f.). *Firebase Hosting*. Recuperado el 10 de julio de 2025, de https://firebase.google.com/docs/hosting?hl=es-419

- Google. (s.f.). *Google HTML/CSS style guide*. Recuperado el 10 de julio de 2025, de https://google.github.io/styleguide/htmlcssguide.html

- Nielsen Norman Group. (s.f.). *Front-end style-guides: Definition, requirements, component checklist*. Recuperado el 10 de julio de 2025, de https://www.nngroup.com/articles/front-end-style-guides/

- Nielsen Norman Group. (s.f.). *The four dimensions of tone of voice*. Recuperado el 10 de julio de 2025, de https://www.nngroup.com/articles/tone-of-voice-dimensions/

- Nvie. (s.f.). *A successful Git branching model*. Recuperado el 10 de julio de 2025, de https://nvie.com/posts/a-successful-git-branching-model/

- Preston-Werner, T. (s.f.). *Semantic versioning 2.0.0*. Recuperado el 10 de julio de 2025, de https://semver.org/

- PrimeVue. (s.f.). *PrimeVue: The most complete UI component library for Vue.js*. Recuperado el 10 de julio de 2025, de https://primevue.org

- Render. (s.f.). *Deployments*. Recuperado el 10 de julio de 2025, de https://render.com/docs/deploys

- REST API Tutorial. (s.f.). *What is REST?*. Recuperado el 10 de julio de 2025, de https://www.restapitutorial.com/introduction/whatisrest

- RESTfulAPI.net. (s.f.). *REST API tutorial*. Recuperado el 10 de julio de 2025, de https://restfulapi.net

- Stripe. (s.f.). *Payments overview*. Recuperado el 10 de julio de 2025, de https://docs.stripe.com/payments?payments=popular

- UXPressia. (s.f.). *User vs. buyer persona: Differences and free template*. Recuperado el 10 de julio de 2025, de https://uxpressia.com/blog/user-persona-vs-buyer-persona-difference

- W3Schools. (s.f.). *HTML style guide and coding conventions*. Recuperado el 10 de julio de 2025, de https://www.w3schools.com/html/html5_syntax.asp

## Anexos

- Organización GitHub: [https://github.com/Inteligencia-Artesanal-Aplicaciones-Web](https://github.com/Equipo5-Aplicaciones-Moviles/upc-Aplicaciones-Moviles-Equipo5)
- Miro : https://miro.com/app/board/uXjVJGeldZw=/
