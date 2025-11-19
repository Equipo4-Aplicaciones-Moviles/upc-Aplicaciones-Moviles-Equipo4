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

| Versión | Fecha      | Autor               | Descripción de modificación                                     |
|---------|------------|----------------------|-----------------------------------------------------------------|
| 0.1     | 08/09/2025 | Joseph Rodriguez     | Desarrollo del Capítulo 1 y Capítulo 2                         |
| 0.2     | 17/09/2025 | Joseph Rodriguez     | Desarrollo del Capítulo 2 (entrevistas, competidores, segmentación) |

## Project Report Collaboration Insights
**TB1** Desarrollo del reporte hasta el capítulo 2 para el sprint 1
<br>
<img width="1286" height="645" alt="image" src="https://github.com/user-attachments/assets/85884f83-6e93-496c-a74c-d26fde8b200f" />
<br>

- **URL de la organización del proyecto:** [https://github.com/Equipo5-Aplicaciones-Moviles](https://github.com/Equipo5-Aplicaciones-Moviles)

- **URL del repositorio del informe del proyecto:** [https://github.com/Equipo5-Aplicaciones-Moviles/upc-Aplicaciones-Moviles-Equipo5](https://github.com/Equipo5-Aplicaciones-Moviles/upc-Aplicaciones-Moviles-Equipo5)

<div style="page-break-after: always;"></div>

# Tabla de Contenidos

1. [cite_start][Student Outcome](#student-outcome) [cite: 287]
2. [cite_start][Objetivos SMART](#objetivos-smart) [cite: 294]
3. [cite_start][Capítulo I: Presentación](#capítulo-i-presentación) [cite: 115]
    - [1.1. [cite_start]Startup Profile](#11-startup-profile) [cite: 298]
    - [1.2. [cite_start]Solution Profile](#12-solution-profile) [cite: 300]
    - [1.3. [cite_start]Segmentos objetivo](#13-segmentos-objetivo) [cite: 309]
4. [cite_start][Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design) [cite: 136]
    - [2.1. [cite_start]Competidores](#21-competidores) [cite: 311]
    - [2.2. [cite_start]Entrevistas](#22-entrevistas) [cite: 328]
    - [2.3. [cite_start]Needfinding](#23-needfinding) [cite: 349]
    - [2.4. [cite_start]Requirements Specification](#24-requirements-specification) [cite: 385]
    - [2.5. [cite_start]Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design) [cite: 430]
    - [2.6. [cite_start]Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design) [cite: 478]
5. [cite_start][Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-uiux-design) [cite: 193]
    - [3.1. [cite_start]Product Design](#31-product-design) [cite: 517]
    - [3.1.3. [cite_start]Landing Page UI Design](#313-landing-page-ui-design) [cite: 553]
    - [3.1.4. [cite_start]Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design) [cite: 565]
6. [cite_start][Capítulo IV: Product Implementation & Validation](#capítulo-iv-product-implementation--validation) [cite: 593]
    - [4.1. [cite_start]Software Configuration Management](#41-software-configuration-management) [cite: 598]
    - [4.2. [cite_start]Landing Page & Mobile Application Implementation](#42-landing-page--mobile-application-implementation) [cite: 624]
        - [cite_start][Sprint 1](#421-sprint-1) [cite: 627]
        - [cite_start][Sprint 2](#422-sprint-2) [cite: 627]
        - [cite_start][Sprint 3](#423-sprint-3) [cite: 627]
    - [4.3. [cite_start]Validation Interviews](#43-validation-interviews) [cite: 721]
7. [cite_start][Conclusiones](#conclusiones) [cite: 738]
8. [cite_start][Videos](#videos) [cite: 744]
9. [cite_start][Glosario](#glosario) [cite: 757]
10. [cite_start][Bibliografía](#bibliografía) [cite: 766]
11. [cite_start][Anexos](#anexos) [cite: 768]

<div style="page-break-after: always;"></div>

## Student Outcome
El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 7**

**Criterio**: *La capacidad de adquirir y aplicar nuevos conocimientos según sea 
necesario, utilizando estrategias de aprendizaje apropiadas.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
[cite_start]del ABET – EAC - Student Outcome 7[cite: 2].

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|--------------------|--------------|
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software. | <ul><li><b>Sergio Aguirre</b><br><b>TB1:</b> Tomé el rol de líder del equipo, asigné tareas y apoyé al equipo; elaboré secciones del segmento objetivo 2 y User Stories.<br><b>TP1:</b> Consolidé el plan de la entrega, prioricé backlog y coordiné dependencias; revisé coherencia entre artefactos y narrativa del documento.<br><b>TB2:</b> Definí la estructura final del proyecto y los módulos de desarrollo; lideré sesiones de revisión de código y aseguré alineación con los estándares de arquitectura móvil. </li><li><b>María Elena Muñoz Machuca</b><br><b>TB1:</b> Realicé el context mapping, bounded context canvases y software architecture del bounded context de pagos y suscripciones.<br><b>TP1:</b> Profundicé la arquitectura de pagos/suscripciones, normalicé plantillas de documentación y aseguré alineamiento con objetivos de producto.<br><b>TB2:</b> Implementé mejoras en la arquitectura de la aplicación móvil, optimizando el uso de APIs y el flujo de datos entre componentes. Colaboré con el equipo de frontend en la integración del backend.</li><li><b>Víctor Manuel Rojas Reátegui</b><br><b>TB1:</b> Participé en reuniones y apoyé la definición de la estructura del proyecto.<br><b>TP1:</b> Formalicé la estructura de paquetes y convenciones, asistí en integración técnica y control de calidad del repositorio.<br><b>TB2:</b> Desarrollé la integración de las funcionalidades de la aplicación con bases de datos móviles, mejoré el control de versiones en el repositorio y optimicé la automatización de pruebas de integración.</li><li><b>Luis Montañez</b><br><b>TB1:</b> Coordiné la elaboración de entregables y la retroalimentación continua entre miembros.<br><b>TP1:</b> Estandaricé formatos del informe, verifiqué criterios de aceptación y consistencia visual/técnica.<br><b>TB2:</b> Supervisé la coherencia entre los requerimientos funcionales y el diseño final, asegurando que el código estuviera alineado con las expectativas del cliente y los requerimientos del proyecto.</li><li><b>Joseph Rodríguez</b><br><b>TB1:</b> Aporté ideas al prototipo, redacté partes del informe y asistí a reuniones de coordinación.<br><b>TP1:</b> Apoyé la construcción del prototipo, cerré gaps de contenido y controlé el avance cruzado de tareas.<b>TB2:</b> Fomenté la colaboración entre el equipo y promoví la adopción de mejores prácticas en el desarrollo del frontend; actualicé el prototipo móvil y realicé pruebas de usabilidad.</li></ul> | <ul><li><b>TB1:</b> Se actualizaron conocimientos técnicos y metodológicos mediante la elaboración de artefactos (context mapping, BCC, arquitectura), reforzando el desarrollo profesional y la base del proyecto.</li><li><b>TP1:</b> La profundización en arquitectura/estructura de código y la consolidación de entregables fortalecieron competencias de diseño, documentación y organización, elevando la calidad técnica del producto.</li><li><b>TB2:</b> La implementación de mejoras en la arquitectura, integración y pruebas fortalece los conocimientos técnicos y las capacidades de desarrollo en soluciones de software, alineando el proyecto con los estándares de calidad y el mercado móvil.</li></ul> |
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software. | <ul><li><b>Sergio Aguirre</b><br><b>TB1:</b> Coordiné trabajo en Trello, Miro y Figma.<br><b>TP1:</b> Gestioné tablero (priorización/seguimiento), sesiones de Miro (As-Is/To-Be) y validación de wireframes en Figma.</li><li><b>María Elena Muñoz Machuca</b><br><b>TB1:</b> Elaboré context mapping/BCC y arquitectura de pagos/suscripciones.<br><b>TP1:</b> Apliqué buenas prácticas de documentación, incorporé feedback iterativo y mantuve trazabilidad de decisiones.</li><li><b>Víctor Manuel Rojas Reátegui</b><br><b>TB1:</b> Elaboré wireframes de Landing Page y organicé ramas/estructura del repo.<br><b>TP1:</b> Definí naming/flujo Git (ramas, PRs, revisiones) y automatizé chequeos básicos.</li><li><b>Luis Montañez</b><br><b>TB1:</b> Planificación conjunta con plazos claros y distribución de tareas.<br><b>TP1:</b> Gestión de riesgos, seguimiento de hitos y soporte a integración entre frentes.</li><li><b>Joseph Rodríguez</b><br><b>TB1:</b> Cumplí tareas, definí objetivos realistas y mantuve comunicación constante.<br><b>TP1:</b> Aseguré continuidad de entregas, documenté aprendizajes y promoví retroalimentación continua.</li></ul> | <ul><li><b>TB1:</b> El uso de herramientas colaborativas y metodologías ágiles fortaleció hábitos de aprendizaje continuo y coordinación efectiva.</li><li><b>TP1:</b> La adopción disciplinada de Trello/Miro/Figma y flujo Git mejoró competencias individuales y colectivas, trazabilidad y eficiencia del equipo.</li></ul> |

# Objetivos SMART
#### Muñoz Machuca, Maria Elena
**Objetivo 1**<br>
Al culminar mi carrera, uno de mis principales objetivos es convertirme en desarrolladora de software full-stack, con dominio tanto de tecnologías de frontend como de backend. Para alcanzarlo, me propongo participar en proyectos completos que integren ambos enfoques. Mi meta es dedicar entre 8 y 10 horas semanales al estudio y práctica.<br>
**Objetivo 2**<br>
Otro de mis objetivos es desarrollar y diseñar soluciones tecnológicas que generen un impacto positivo en la vida de las personas. Para ello, me propongo crear al menos un proyecto propio que responda a un problema o necesidad social. [cite_start]Este propósito implica aprender y aplicar metodologías ágiles, de esta manera podré logar mi objetivos y mantener mi compromiso de mejorar la calidad de vida de las personas usando la tecnología[cite: 2].

#### Aguirre Castillo Sergio Cesar
**Objetivo 1**
Al culminar mi carrera, mi objetivo es convertirme en arquitecto de software especializado en diseño de sistemas distribuidos. Para ello, me propongo participar en proyectos académicos y profesionales donde pueda aplicar patrones de diseño y principios de arquitectura. Dedicaré un mínimo de 6 horas semanales al estudio de arquitectura de software y al uso de herramientas de modelado como UML y Structurizr.
**Objetivo 2**
Otro de mis objetivos es fortalecer mis habilidades de liderazgo en equipos de desarrollo. Para lograrlo, me propongo asumir roles de coordinación en al menos dos proyectos grupales y capacitarme en metodologías ágiles como Scrum y Kanban. [cite_start]Mediré mi progreso en función de la retroalimentación del equipo y la capacidad de cumplir con las metas establecidas en los proyectos[cite: 2].

#### Montañez Moreno, Luis Angel
**Objetivo 1**
Al finalizar mi carrera, mi objetivo es especializarme en desarrollo frontend, con dominio en frameworks modernos como React y Angular. Para alcanzarlo, dedicaré entre 5 y 7 horas semanales a cursos y prácticas de diseño de interfaces y usabilidad, aplicándolos en proyectos personales y académicos.
**Objetivo 2**
También me propongo contribuir al desarrollo de proyectos con impacto social mediante soluciones accesibles y responsivas. [cite_start]Para ello, me comprometo a diseñar al menos una aplicación web inclusiva antes de culminar mi carrera, siguiendo lineamientos de accesibilidad (WCAG) y buenas prácticas de UX/UI[cite: 2].

#### Rodriguez Parco Joseph Pablo
**Objetivo 1**
Mi objetivo principal al terminar la carrera es especializarme en desarrollo backend, enfocándome en tecnologías como .NET y Java. Para lograrlo, dedicaré al menos 6 horas semanales a proyectos y prácticas que refuercen mis conocimientos en bases de datos, APIs y servicios en la nube.
**Objetivo 2**
También quiero potenciar mis habilidades de trabajo en equipo y comunicación profesional. Para alcanzarlo, me propongo participar activamente en al menos tres proyectos colaborativos, asumiendo responsabilidades de integración de componentes y documentación. [cite_start]Mi progreso se medirá con la calidad de la comunicación y el cumplimiento de los objetivos en los plazos establecidos[cite: 2].

#### Rojas Reategui Victor Manuel
**Objetivo 1**
Mi objetivo al culminar la carrera es convertirme en ingeniero de software especializado en DevOps y despliegue de aplicaciones. Para lograrlo, me comprometo a dominar herramientas como Docker, Kubernetes y CI/CD pipelines, dedicando entre 5 y 8 horas semanales a la práctica en entornos reales o simulados.
**Objetivo 2**
Otro de mis objetivos es contribuir al despliegue eficiente y seguro de aplicaciones en la nube. [cite_start]Para ello, desarrollaré al menos un proyecto implementado en AWS o Azure antes de terminar la carrera, midiendo el éxito mediante pruebas de rendimiento, escalabilidad y seguridad[cite: 2].

<div style="page-break-after: always;"></div>

# Capítulo I: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup
OsitoPolar es una aplicación móvil orientada a mejorar la gestión y el mantenimiento de equipos de congelación en negocios que dependen críticamente del frío, como supermercados, minimarkets, laboratorios, restaurantes y empresas del sector alimentario o farmacéutico. [cite_start]La solución conecta a estos negocios con técnicos y proveedores especializados en refrigeración, permitiendo una gestión integral, preventiva y automatizada de sus sistemas de congelación[cite: 2].

La plataforma ofrece funcionalidades clave como monitoreo en tiempo real de temperatura, consumo energético y tiempo de uso, generación de reportes técnicos, alertas automatizadas por fallas, historial de rendimiento, y programación inteligente de mantenimientos. [cite_start]Estas herramientas permiten a los usuarios optimizar sus operaciones, evitar pérdidas económicas por fallas inesperadas y mantener un registro completo del estado y uso de sus equipos[cite: 2].

OsitoPolar no solo está diseñado para negocios que utilizan equipos de frío, sino también para empresas proveedoras de equipos y serviciós de refrigeración. [cite_start]A través de su módulo especializado, los técnicos pueden visualizar todos los equipos que atienden, gestionar sus visitas, acceder al historial técnico de cada unidad y generar reportes de forma automática[cite: 2].

[cite_start]**Misión:** Nuestra misión en OsitoPolar es proporcionar una solución tecnológica inteligente que permita a los negocios proteger su inventario y optimizar la gestión de sus equipos de refrigeración, ofreciendo al mismo tiempo herramientas especializadas para mejorar la eficiencia operativa de los técnicos y proveedores del sector[cite: 2].

[cite_start]**Visión:** Queremos ser la empresa lider en gestión y mantenimiento de equipos de refrigeración, empezando por Lima y prontamente expandirnos a más lugares del Perú[cite: 2].

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

| Las 5Ws y 2Hs | Pregunta                                           | Descripción                                                                                                                                                                                                                                                                                                                                                                                    |
|---------------|----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| What?         | ¿Cuál es el problema?                              | Actualmente, los negocios que dependen de equipos de congelación enfrentan grandes desafíos operativos ante fallas inesperadas o falta de mantenimiento. Las fallas térmicas, los altos consumos energéticos no detectados a tiempo y la ausencia de un monitoreo constante pueden derivar en la pérdida de productos, reducción de la calidad del servicio y pérdidas económicas importantes. |
| When?         | ¿Cuándo sucede este problema?                      | Estas situaciones ocurren principalmente durante horarios de operación continua, especialmente en momentos donde no hay personal técnico disponible de forma inmediata, o cuando no se ha realizado un seguimiento adecuado del estado del equipo a lo largo del tiempo.                                                                                                                       |
| Where?        | ¿Dónde se produce este suceso?                     | El problema afecta a negocios ubicados en todo el país, principalmente en Lima, donde la cadena de frío es esencial en sectores como alimentación, medicina y distribución. También impacta a empresas proveedoras de refrigeración que atienden múltiples clientes sin una plataforma centralizada de control.                                                                                |
| Who?          | ¿Quiénes están involucrados?                       | Están involucrados tanto los administradores y dueños de negocios que utilizan congeladoras como los técnicos y empresas proveedoras de servicios de refrigeración.                                                                                                                                                                                                                            |
| Why?          | ¿Cuál es la causa del problema?                    | La causa principal es la falta de soluciones tecnológicas accesibles que integren monitoreo, alertas, historial y programación automática en un solo lugar. Muchas empresas aún dependen de sistemas manuales o no tienen control de lo que sucede con sus equipos hasta que ocurre una falla crítica.                                                                                         |
| How?          | ¿Qué llevó a la persona a llegar a esta situación? | Lo que llevó a los negocios y técnicos a este punto ha sido la acumulación de imprevistos y la falta de digitalización en el mantenimiento preventivo, que genera una alta dependencia de intervenciones reactivas en vez de planificadas. Esto incrementa los costos, los tiempos de respuesta y el desgaste operativo.                                                                       |
| How much?     | ¿Cuánto es el impacto financiero?                  | [cite_start]Aunque el impacto económico varía según el tipo de negocio, la pérdida por una falla en un equipo de refrigeración puede ascender desde cientos hasta miles de soles en productos dañados, sin considerar el tiempo operativo perdido, la pérdida de clientes y la inversión en reparación o reposición de equipos. [cite: 2]                                                                           |

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements
El estado actual de la industria de la refrigeración comercial y técnica enfrenta importantes desafíos relacionados con la gestión, el mantenimiento y la trazabilidad de los equipos de congelación. Negocios que dependen críticamente del frío —como supermercados, minimarkets, laboratorios, restaurantes y empresas del sector alimentario o farmacéutico— aún lidian con la falta de monitoreo en tiempo real y con procesos de mantenimiento reactivos. Esto genera pérdidas económicas, ineficiencia energética y riesgos para el inventario.

**Cambiar el problema**
Hemos identificado una brecha significativa: las soluciones actuales no abordan de manera integral la necesidad de una plataforma confiable y automatizada que permita la gestión centralizada, predictiva y transparente de los sistemas de refrigeración. [cite_start]La ausencia de un historial técnico accesible, reportes detallados y alertas preventivas limita la capacidad de respuesta ante fallas y reduce la eficiencia del servicio técnico[cite: 2].

[cite_start]**¿Cómo podríamos reducir las fallas imprevistas y optimizar el mantenimiento de los sistemas de refrigeración comercial mediante una plataforma digital que conecte negocios y técnicos especializados?** [cite: 2]

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
- [cite_start]Implementar inteligencia artificial que permita trazar estrategias de mantenimiento inteligente, rutas eficientes para los técnicos y recomendaciones proactivas ante posibles fallos[cite: 2].

**User Outcomes**
* **¿Quién será nuestro usuario?**
    * Negocios que dependen críticamente del uso de sistemas de refrigeración como supermercados, minimarkets, restaurantes, laboratorios y empresas del rubro alimentario y farmacéutico.
    * Técnicos especializados en refrigeración que brindan mantenimiento a dichos sistemas.
    * Proveedores de equipos de refrigeración que desean ofrecer un servicio posventa más eficiente.
* **¿Dónde encaja nuestro producto en su vida?**
    * En situaciones donde los negocios necesitan garantizar la continuidad operativa de sus equipos de frío, evitando pérdidas económicas por fallas imprevistas.
    * En el día a día de técnicos de refrigeración que deben gestionar múltiples clientes, visitas y mantenimientos.
    * En la operación diaria de los negocios que necesitan registros y reportes precisos del desempeño de sus sistemas de refrigeración.
* **¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**
    * El principal desafío es asegurar que los datos de monitoreo (temperatura, consumo energético, fallas, etc.) sean precisos, actualizados y confiables. **Solución**: Se debe integrar sensores calibrados y sistemas de verificación automática que validen las lecturas antes de almacenarlas.
    * Otro problema puede ser la adopción inicial de la plataforma por parte de usuarios no tecnológicos. [cite_start]**Solución**: Esto se abordará con una interfaz sencilla, explicaciones paso a paso y soporte técnico accesible[cite: 2].

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hipótesis 1: Eficiencia operativa y reducción de fallas inesperadas**
Creemos que **al ofrecer una plataforma integral que unifique las funciones de monitoreo, mantenimiento y gestión técnica de equipos de refrigeración**, aumentaremos la eficiencia operativa de los negocios y proveedores del sector, reduciendo la complejidad y el riesgo de fallas inesperadas.  
[cite_start]Sabremos que hemos tenido éxito **cuando observemos una reducción del 30% en las incidencias por fallas térmicas reportadas** y **un aumento del 25% en la planificación de mantenimientos preventivos dentro de la plataforma** durante los primeros seis meses[cite: 2].

**Hipótesis 2: Control de pérdidas operativas y consumo energético**
Creemos que **al proporcionar herramientas de análisis de rendimiento y alertas automatizadas**, los negocios podrán actuar de forma preventiva y reducir costos innecesarios asociados al consumo energético y pérdidas operativas.  
[cite_start]Sabremos que hemos tenido éxito **cuando observemos una disminución del 20% en los costos energéticos mensuales promedio** y **un incremento del 30% en el uso de los reportes de monitoreo en tiempo real** por parte de los usuarios activos[cite: 2].

**Hipótesis 3: Mejora en el servicio técnico personalizado y predictivo**
Creemos que **al implementar reportes automáticos e históricos de rendimiento por equipo**, los técnicos y proveedores podrán ofrecer un servicio más personalizado y predictivo, aumentando la calidad del soporte brindado.  
[cite_start]Sabremos que hemos tenido éxito **cuando más del 70% de los técnicos califiquen positivamente los reportes automáticos en encuestas internas** y **cuando los clientes reporten un aumento del 25% en su satisfacción con la rapidez del servicio técnico.** [cite: 2]

**Hipótesis 4: Trazabilidad y protección de la información técnica**
Creemos que **al garantizar la trazabilidad completa y la protección de los datos técnicos en la plataforma**, construiremos confianza entre los negocios y los proveedores de servicios.  
[cite_start]Sabremos que hemos tenido éxito **cuando logremos reducir en un 40% los errores administrativos o pérdidas de información** y **aumentar en un 30% la retención de usuarios técnicos y empresariales activos.** [cite: 2]

**Hipótesis 5: Transición hacia una gestión moderna de refrigeración**
Creemos que **al ofrecer una solución digital intuitiva y especializada tanto para negocios como para técnicos**, facilitaremos la transición hacia una gestión moderna y eficiente de la refrigeración.  
[cite_start]Sabremos que hemos tenido éxito **cuando alcancemos una tasa de adopción del 60% de usuarios nuevos dentro de los tres primeros meses** y **una tasa de retención del 80% tras seis meses de uso continuo de la plataforma.** [cite: 2]

#### 1.2.2.4. Lean UX Canvas
El presente Lean UX Canvas se ha desarrollado para ofrecer una visión estratégica y concisa de la solución OsitoPolar. [cite_start]Este marco nos permite alinear rápidamente los objetivos de negocio con las necesidades de nuestros usuarios y las hipótesis clave que guían nuestro desarrollo[cite: 2].

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
    * [cite_start]Administradores interesados en implementar tecnología para optimizar sus operaciones y mantener la calidad del inventario[cite: 2].

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
    * [cite_start]Profesionales que desean brindar un servicio más personalizado y predictivo a sus clientes[cite: 2].

<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Development and Software Solution Design

## 2.1. Competidores

**Competidor 1: ServiceTitan**
ServiceTitan es una plataforma de gestión de servicios basada en la nube que ofrece soluciones de software para empresas de servicios, incluidos técnicos de HVAC, fontaneros y electricistas. Proporciona funcionalidades de programación, gestión de trabajos, facturación y más. [cite_start]Esta plataforma es conocida por su facilidad de uso y por ayudar a las empresas a optimizar sus operaciones de servicio técnico en tiempo real[cite: 2].

**Competidor 2: CoolMaster**
CoolMaster es una solución de software diseñada específicamente para el sector de refrigeración comercial. Ofrece monitoreo remoto de sistemas de refrigeración, alertas tempranas de fallas y gestión eficiente del consumo energético. [cite_start]La plataforma está orientada a optimizar la eficiencia operativa de negocios que dependen críticamente de sistemas de frío, como supermercados y centros de distribución[cite: 2].

**Competidor 3: TempGenius**
TempGenius es un software de monitoreo de temperatura y humedad en tiempo real para diversas industrias, incluida la de la refrigeración comercial. Permite a los usuarios realizar un seguimiento de sus equipos de refrigeración mediante sensores conectados a la nube, generar reportes y recibir alertas automáticas por variaciones en los niveles de temperatura. [cite_start]Su principal enfoque es mejorar la visibilidad y control de las operaciones de refrigeración para evitar pérdidas económicas[cite: 2].

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
- [cite_start]**Colaboraciones con Proveedores Locales**: Formaremos alianzas estratégicas con proveedores locales[cite: 2].

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
14. [cite_start]¿Qué le haría dejar de usar una aplicación de este tipo? [cite: 2]

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
14. [cite_start]¿Qué beneficios cree que podría tener la implementación de una solución digital como OsitoPolar a su empresa? [cite: 2]

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
- **Resumen:** Adriana es una emprendedora que administra una bodega tipo mini market en San Martín de Porres. [cite_start]Su actividad diaria depende del correcto funcionamiento de sus equipos de refrigeración... (etc.) [cite: 2]

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
- [cite_start]**Resumen:** Luis es un empresario del rubro gastronómico especializado en cevichería... (etc.) [cite: 2]

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
- [cite_start]**Resumen:** Wilder es técnico especializado en refrigeración y aire acondicionado... (etc.) [cite: 2]

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
- [cite_start]**Resumen:** Jackeline tiene 13 años de experiencia en el rubro de servicios y mantenimiento de refrigeración... (etc.) [cite: 2]

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
- [cite_start]**Resumen:** Santiago es dueño de una empresa de instalación y mantenimiento de sistemas de refrigeración industrial... (etc.) [cite: 2]

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
(Gráficos circulares con estadísticas) [cite_start][cite: 2]

## 2.3. Needfinding

### 2.3.1. User Personas
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
  </table>

### 2.3.3. User Journey Mapping
**Segmento objetivo #1: Negocios que utilizan equipos de refrigeración**
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter02/JourneyMap-segment-1.png"
       alt="Segmento 1 del Journey Map: Etapa de Descubrimiento de necesidades del usuario."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Segmento 1 del Journey Map.
  </figcaption>
</figure>

**Segmento objetivo #2: EMPRESAS PROVEEDORAS DE SERVICIOS**
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
20. [cite_start]**Notification (Notificación):** Mensajes enviados automáticamente para informar sobre mantenimientos, fallas o cambios importantes[cite: 2].

## 2.4. Requirements Specification
### 2.4.1. User Stories

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
| US-27 | Solicitar demostración del producto | Como visitante, quiero solicitar una demostración del producto para evaluar su funcionamiento antes de adquirirlo. | **Escenario 1: Solicitud de demo** <br/> Dado que el visitante desea una demostración del producto, cuando envía una solicitud de demostración, entonces el sistema registra la información en la base de datos y genera una confirmación automática enviada al correo registrado. | [cite_start]EP-07 | [cite: 2]

#### 2.4.1.1. Spike Story
**Spike Story ID: SS-01**
**Como** equipo de desarrollo (web, móvil y backend),
**Quiero** investigar y prototipar las tecnologías móviles más adecuadas para la plataforma OsitoPolar (Kotlin para Android, Flutter con Dart y/o Kotlin Multiplatform),
[cite_start]**Para que** podamos complementar los conocimientos adquiridos en el curso con investigación práctica y seleccionar el enfoque más viable para el desarrollo móvil. [cite: 2]

**Spike Story ID: SS-02**
**Como** equipo de desarrollo (backend, frontend y móvil),
**Quiero** investigar y prototipar la integración de Stripe para la gestión de planes de suscripción y pagos,
[cite_start]**Para** que podamos garantizar un flujo de pago seguro, escalable y conforme con PCI-DSS dentro de OsitoPolar. [cite: 2]

**Spike Story ID: SS-03**
**Como** equipo de desarrollo,
**Quiero** investigar y prototipar un sistema de notificaciones en tiempo real para OsitoPolar,
[cite_start]**Para** que los usuarios reciban alertas inmediatas de fallas, mantenimientos y pagos confirmados. [cite: 2]

**Spike Story ID: SS-04**
**Como** equipo de desarrollo (web, móvil y backend),
**Quiero** investigar y prototipar el uso de Jetpack Compose para desarrollar la pantalla de catálogo de equipos en la versión móvil de OsitoPolar,
[cite_start]**Para** que podamos evaluar su facilidad de uso, rendimiento y compatibilidad con las funcionalidades actuales, seleccionando un enfoque viable para el desarrollo móvil. [cite: 2]

**Spike Story ID: SS-05**
**Como** equipo de desarrollo (web, móvil y backend),
**Quiero** investigar y prototipar el uso de Jetpack Compose para implementar la pantalla de autenticación (login y registro) en la versión móvil de OsitoPolar,
[cite_start]**Para** que podamos evaluar su seguridad, usabilidad y compatibilidad con el backend existente, seleccionando un enfoque viable para el desarrollo móvil. [cite: 2]

### 2.4.2. Impact Mapping
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/Impact-Mapping.png"
       alt="Diagrama de Impact Mapping: Objetivo, actores, impactos y entregables clave."
       style="max-width: 80%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Impact Mapping.
  </figcaption>
</figure>

### 2.4.3. Product Backlog
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
| 34 | US-34 | Registrar evaluación de servicio vía endpoint REST         | [cite_start]8 | [cite: 2]

## 2.5. Strategic-Level Domain-Driven Design

### 2.5.1. EventStorming
[cite_start]Con el objetivo de realizar un modelado colaborativo y estratégico del dominio de OsitoPolar, se llevó a cabo una sesión de EventStorming, una técnica visual centrada en eventos del dominio que permite identificar flujos de negocio, entidades relevantes, actores y límites naturales del sistema. [cite: 2]
<img width="1734" height="525" alt="image" src="https://github.com/user-attachments/assets/f3937874-d931-48db-b5a1-192ddef51340" />

#### 2.5.1.1. Candidate Context Discovery
| Bounded Context | Descripción breve | Tipo |
|-----------------|-------------------|------|
| **Gestion de equipos** | Registro, monitoreo y alertas en tiempo real de equipos de refrigeración. | Core |
| **Gestión de Mantenimientos** | Programación, asignación y ejecución de mantenimientos preventivos/correctivos. | Core |
| **Gestión de Usuarios** | Autenticación, perfiles de dueños, técnicos y proveedores. | Supporting |
| **Pagos y Suscripciones** | Planes premium, historial de facturación, renovación automática. | Supporting |
| **Reportes y Dashboard** | Generación de métricas, exportación de reportes y visualización de indicadores. | Generic |
| **Notificaciones** | Envío de alertas y recordatorios vía correo, SMS o push. | [cite_start]Generic | [cite: 2]

#### 2.5.1.2. Domain Message Flows Modeling
Para visualizar la colaboración entre los contextos, se utilizó Domain Storytelling.

Caso 1: Registro y Monitoreo de un Equipo:
- El usuario registra un nuevo equipo de refrigeración.
- El contexto de Gestión de Equipos guarda los datos.
- El sistema conecta con sensores IoT y comienza el monitoreo.
- Si se detecta una falla, se dispara un evento al contexto de Gestión de Mantenimientos.
- [cite_start]El sistema asigna un técnico disponible y envía una notificación al usuario. [cite: 2]

<img width="303" height="1536" alt="Image 18 sept 2025, 10_53_31 p m" src="https://github.com/user-attachments/assets/54b42e86-190d-4225-87f5-f22728a0cbf6" />

#### 2.5.1.3. Bounded Context Canvases
**Bounded Context 1: My Equipment**
**Context Overview:** Gestiona la administración central de los equipos de refrigeración registrados por los usuarios, permitiendo su monitoreo en tiempo real y la vinculación con servicios relacionados.
**Design Critique:** Es un contexto *Core*, base del dominio. Requiere robustez en manejo de datos en tiempo real.

**Bounded Context 2: Service Requests**
**Context Overview:** Coordina las solicitudes de servicio generadas por los usuarios, que pueden derivar en órdenes de trabajo o mantenimientos programados.
**Design Critique:** Es un contexto *Supporting*, facilita la coordinación y canaliza las necesidades de los usuarios.

**Bounded Context 3: Work Orders**
**Context Overview:** Administra el ciclo de vida de los mantenimientos preventivos y correctivos, desde su creación hasta el cierre.
**Design Critique:** Es un *Core Context*, indispensable para la continuidad del servicio.

**Bounded Context 4: View Maintenance**
**Context Overview:** Proporciona a los usuarios una interfaz para consultar mantenimientos realizados y programados.
**Design Critique:** Es un contexto *Supporting*, orientado a consulta e informes.

**Bounded Context 5: Notifications**
**Context Overview:** Gestiona la emisión de alertas y recordatorios, garantizando que los usuarios estén informados de fallas, mantenimientos y cambios en el sistema.
**Design Critique:** Es un contexto *Supporting*, vital para la experiencia de usuario y escalabilidad.

**Bounded Context 6: View Equipment**
**Context Overview:** Facilita la visualización del inventario de equipos y sus características técnicas para usuarios y proveedores.
[cite_start]**Design Critique:** Es un *Generic Context*, soporte esencial para mejorar usabilidad y experiencia del usuario. [cite: 2]

### 2.5.2. Context Mapping
[cite_start]Luego de definir los Bounded Contexts y modelar sus colaboraciones, se realizó una sesión de Context Mapping para visualizar las relaciones estructurales dentro del dominio de OsitoPolar. [cite: 2]

### 2.5.3. Software Architecture
#### 2.5.3.1. Software Architecture Context Level Diagrams
![OsitoPolar-SystemContext.png]( assets/chapter04/Domain-Driven%20Software%20Architecture/OsitoPolar-SystemContext.png)

#### 2.5.3.2. Software Architecture Container Level Diagrams
![OsitoPolar-Container.png](<assets/chapter03/ContainerDiagrama.png>)

#### 2.5.3.3. Software Architecture Deployment Diagrams
![OsitoPolar-Component-MiEquipo.png]( assets/chapter03/DeploymentDiagram.png)
![OsitoPolar-Component-Notificaciones.png]( assets/chapter04/Domain-Driven%20Software%20Architecture/OsitoPolar-Component-Notificaciones.png)
![OsitoPolar-Component-OrdenesTrabajo.png]( assets/chapter04/Domain-Driven%20Software%20Architecture/OsitoPolar-Component-OrdenesTrabajo.png)

## 2.6. Tactical-Level Domain-Driven Design

### 2.6.1. Bounded Context: Mi Equipo
#### 2.6.1.1. Domain Layer
| Clase  | Tipo | Propósito | Atributos / Métodos |
| :---- | :---- | :---- | :---- |
| Equipment | Aggregate | Equipo de refrigeración | Id, Name, Type, Model, Manufacturer, Cost |
| EnergyConsumption | Entity | Consumo de energía | Current, Unit, Average, UpdateCurrent(), UpdateAverage |
| RentalInfo | Entity | Información de renta de equipos | StartDate, EndDate, MonthlyFee, ProviderId |
| Location | Entity | Ubicación | Name, Address, Coordinates |

#### 2.6.1.2. Interface Layer
| Clase | Tipo | Propósito | Atributos / Métodos |
| :---- | :---- | :---- | :---- |
| EquipmentController | Controller | Gestiona las peticiones relacionadas con los equipment | GetAllEquipments(), GetEquipmentById(), CreateEquipment(), UpdateEquipmentOperations(), UpdateEquipment(), DeleteEquipment() |

#### 2.6.1.3. Application Layer
| Clase | Tipo | Propósito | Métodos |
| :---- | :---- | :---- | :---- |
| EquipmentCommandService | Command Handler | Ejecuta la lógica para gestionar un Equipment | Handle(command::CreateEquipmentCommand, command: UpdateEquipmentTemperatureCommand, UpdateEquipmentLocationCommand) |

#### 2.6.1.4. Infrastructure Layer
| Clase | Tipo | Propósito | Tecnologías |
| :---- | :---- | :---- | :---- |
| EquipmentRepository | Repository | Implementación de EquipmentRepository con acceso a base de datos | PostgreSQL |

#### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams
<img width="3870" height="3211" alt="mi_equipo_component1" src="https://github.com/user-attachments/assets/709cd005-84e4-4a14-8e6d-4dd3a8c2772b" />

#### 2.6.1.6. Bounded Context Software Architecture Code Level Diagrams
#### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams
<img width="1538" height="850" alt="image" src="https://github.com/user-attachments/assets/2b1b243e-27c0-41d7-a1a5-1f6ff0a01e7e" />

#### 2.6.1.6.2. Bounded Context Database Design Diagram
<img width="1091" height="623" alt="image" src="https://github.com/user-attachments/assets/79d43335-bed1-4203-9d34-3298314f8d43" />

### 2.6.2. Bounded Context: Gestión de Solicitudes
(Contenido completo Tactical para Gestión de Solicitudes: Domain, Interface, App, Infra, Diagramas) [cite_start][cite: 2]

### 2.6.3. Bounded Context: Órdenes de Trabajo
(Contenido completo Tactical para Órdenes de Trabajo: Domain, Interface, App, Infra, Diagramas) [cite_start][cite: 2]

### 2.6.4. Bounded Context: Ver Mantenimientos
(Contenido completo Tactical para Ver Mantenimientos: Domain, Interface, App, Infra, Diagramas) [cite_start][cite: 2]

### 2.6.5. Bounded Context: Notificaciones
#### 2.6.5.1. Domain Layer
| Clase                     | Tipo                  | Propósito                                                                 | Atributos / Métodos                                                                 |
|----------------------------|-----------------------|---------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| **Payment** | Entity               | Representa un pago realizado por un usuario para adquirir o renovar una suscripción. | Id, UserId, SubscriptionId, Amount: Price, StripeSession, CustomerEmail, Description, `UpdatePaymentStatus()` |
| **Subscription** | Entity               | Representa un plan de suscripción contratado por un usuario o proveedor.  | Id, PlanName, Price, BillingCycle, MaxEquipment, MaxClients, Features (List<Feature>), `UpdatePlan()` |
[cite_start]... (Resto de clases) [cite: 2]

### 2.6.6. Bounded Context: Ver Equipos
(Contenido completo Tactical para Ver Equipos: Domain, Interface, App, Infra, Diagramas) [cite_start][cite: 2]

<div style="page-break-after: always;"></div>

# Capítulo III: Solution UI/UX Design

## 3.1. Product Design
En esta sección se presenta el diseño del producto **Osito Polar** como una parte esencial de la arquitectura del sistema. [cite_start]El diseño busca alinear las funcionalidades principales con las necesidades detectadas durante el análisis y modelado del dominio, garantizando una experiencia fluida, intuitiva y estéticamente consistente[cite: 2].

### 3.1.1. Style Guidelines
#### 3.1.1.1. General Style Guidelines
#### Paleta de colores principal
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
- [cite_start]**Botones:** Medium [cite: 2]

### 3.1.2. Information Architecture
#### 3.1.2.1. Organization Systems
Se aplican distintos sistemas de organización según la sección o funcionalidad:
- **Jerárquico:** En la navegación principal (Catálogo → Categorías → Detalle de componente), y en la gestión de builds guardadas del usuario.  
- **Secuencial:** En el flujo de creación de una build.
- **Matricial:** En la comparación de builds o especificaciones.

#### 3.1.2.2. Labelling Systems
Las etiquetas de texto fueron cuidadosamente seleccionadas para ser **claras, cortas y coherentes**.
- **Botones:** Agregar, Guardar Build, Comparar, Eliminar, Filtrar, Ver Detalles.  

#### 3.1.2.3. SEO Tags and Meta Tags
**Landing Page – SEO**
- **Title:** Osito Polar – Crea y Personaliza tus Builds  
- **Meta Description:** Plataforma intuitiva para armar y compartir builds de PC personalizados con validación de compatibilidad.

#### 3.1.2.4. Searching Systems
El sistema de búsqueda está diseñado para ser **rápido, predictivo y flexible**.
- Campo de búsqueda global con **autocompletado** y **sugerencias dinámicas**.

#### 3.1.2.5. Navigation Systems
**Landing Page**: Menú superior o hamburguesa con secciones: **Inicio**, **Sobre Nosotros**, **FAQ**, **Contacto**.
[cite_start]**Aplicación móvil**: Barra inferior con íconos principales: **Catálogo**, **Mis Builds**, **Crear**, **Comunidad**, **Perfil**[cite: 2].

### 3.1.3. Landing Page UI Design
#### 3.1.3.1. Landing Page Wireframe
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter04/LandingPageWireframe.png"
       alt="Wireframe de la Landing Page: Diseño de baja fidelidad de la página principal."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Wireframe de la Landing Page.
  </figcaption>
</figure>

#### 3.1.3.2. Landing Page Mock-up
(Imágenes Mockups Landing 1 a 11) [cite_start][cite: 2]

### 3.1.4. Mobile Applications UX/UI Design

#### 3.1.4.1. Mobile Applications Wireframes
## Cliente
(Imágenes Wireframes Cliente 1-8)
## Empresa
(Imágenes Wireframes Empresa 9-17) [cite_start][cite: 2]

#### 3.1.4.2. Mobile Applications Wireflow Diagrams
### User Goal 1
<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter03/flujos/taskflow1.png"
       alt="Diagrama de Taskflow 1: Flujo de tareas para una acción específica del usuario."
       style="max-width: 70%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Taskflow 1.
  </figcaption>
</figure>
(Task Flow 1, Wireflow 1)
### User Goal 2
(Task Flow 2, Wireflow 2)
### User Goal 3
(Task Flow 3, Wireflow 3)
### User Goal 4
(Task Flow 4, Wireflow 4) [cite_start][cite: 2]

#### 3.1.4.3. Mobile Applications Mock-ups
## Cliente
(Mockups Cliente 18-42)
## Empresa
(Mockups Empresa 43-48) [cite_start][cite: 2]

#### 3.1.4.4. Mobile Applications User Flow Diagrams
### User Goal 1
<img src="assets/chapter03/flujos/UserGoal1.png" alt="User Goal 1">
### User Goal 2
<img src="assets/chapter03/flujos/UserGoal2.png" alt="User Goal 2">
### User Goal 3
[cite_start]<img src="assets/chapter03/flujos/UserGoal3.png" alt="User Goal 3"> [cite: 2]

#### 3.1.4.5. Mobile Applications Prototyping

<div style="page-break-after: always;"></div>

# Capítulo IV: Product Implementation & Validation

## 4.1. Software Configuration Management
### 4.1.1. Software Development Environment Configuration
### 4.1.2. Source Code Management
### 4.1.3. Source Code Style Guide & Conventions
### 4.1.4. Software Deployment Configuration

## 4.2. Landing Page & Mobile Application Implementation

### 4.2.1. Sprint 1
#### 4.2.1.1. Sprint Planning 1
| **Sprint #** | **Sprint 1** |
|-------------------------------|-------------|
| **Sprint Planning Background**| En el sprint decidimos reunirnos para verificar el progreso de cada uno de los participantes y el progreso desde el punto de vista grupal, luego de ello buscamos formas y acciones de mejora. |
| **Date** | 6/10/25    |
| **Time** | 21:00 horas |
| **Location** | Via Discord |
| **Prepared By** | Luis Angel Montañez Moreno |
| **Attendees** | Joseph Rodriguez, Sergio Aguirre, Victor Rojas, Maria Muñoz, Luis Montañez |
| **Sprint 1 Goal** | Nuestro enfoque está en implementar la landing page de Osito Polar y además de la aplicación móvil para Android siguiendo la estrategia nativa. Esta ofrecerá a los nuevos usuarios una interfaz clara, informativa y fácil de navegar que comunique los beneficios, servicios y características de la solución. Creemos que esto permitirá a los usuarios comprender de manera sencilla el valor que aporta, generando una primera experiencia positiva y sentando las bases para futuras funcionalidades. |
| **Sprint 1 Velocity** | 15 |
| **Sum of Story Points** | [cite_start]21 | [cite: 2]

#### 4.2.1.2. Sprint Backlog 1
Sprint # | Sprint 1 | | | | | | |
---------|----------|---------|-------|-----|----|----|---|
User Story | Work-Item / Task
ID | Title | ID | Title | Description | Estimation (Hours) | Assigned To | Status
US06| Agregar equipos | UT07 | Implementar estructura | Crear los componentes, entidades y servicios de los equipos | 4 | Sergio Aguirre | Done
[cite_start]... (Resto de tabla) [cite: 2]

#### 4.2.1.3. Development Evidence for Sprint Review
| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---------|----------|----------------|-----------|-------------|--------------|
| https://github.com/Equipo5-Aplicaciones-Moviles/OsitoPolar-App-Movil | login | c416779 | Feature: Add:Login / Add:Register / Add:Contact | Feature: Add:Login / Add:Register / Add:Contact | 09/10/25     |
[cite_start]... (Resto de tabla) [cite: 2]

#### 4.2.1.4. Testing Suite Evidence for Sprint Review
Suite de pruebas con xUnit, FluentAssertions y Moq. 21 pruebas unitarias (100% exitosas), 10 pruebas de integración implementadas. Cobertura: 94.7% en servicios críticos, 88.5% en lógica de dominio. Ejecución en 0.57 segundos.
<img width="844" height="597" alt="image" src="https://github.com/user-attachments/assets/80afee16-8b8f-4ad8-a40a-f78b155ef646" />
[cite_start]<img width="843" height="238" alt="image" src="https://github.com/user-attachments/assets/293107ca-e389-4b6e-8ec4-7dacd438daa1" /> [cite: 2]

#### 4.2.1.5. Execution Evidence for Sprint Review
#### 4.2.1.6. Services Documentation Evidence for Sprint Review
#### 4.2.1.7. Software Deployment Evidence for Sprint Review
<img width="1202" height="607" alt="image" src="https://github.com/user-attachments/assets/8c830c06-9dc1-46a3-83e0-38a753051518" />

**Landing page deployment:**
Para desplegar la landing page, es necesario cumplir con ciertos requisitos previos, como contar con una cuenta personal, una organización y un repositorio donde se alojarán los archivos. Una vez cumplidos estos requisitos, se pueden seguir los pasos detallados a continuación para realizar el despliegue:
1. Verificar que los archivos principales se encuentren en la raíz (root) del repositorio.
2. Asegurarse de que los archivos sigan las siguientes convenciones de nombres: "index.html" para la página principal, "styles.css" para los estilos, "script.js" para los scripts principales, "languages.js" para gestionar los textos en diferentes idiomas (español e inglés), y una carpeta llamada "assets/images" para las imágenes.
3. Subir los archivos al repositorio mediante un commit.
4. Acceder a la sección Settings > Pages y seleccionar el branch correspondiente, en este caso, "main".
5. Configurar la carpeta raíz (root) como la fuente de la página.
6. Esperar a que GitHub realice las verificaciones necesarias. [cite_start]Una vez finalizado el proceso, se generará un enlace que permitirá acceder a la landing page desplegada. [cite: 2]

#### 4.2.1.8. Team Collaboration Insights during Sprint

### 4.2.2. Sprint 2
#### 4.2.2.1. Sprint Planning 2
| **Sprint #** | **Sprint 2** |
|-------------------------------|-------------|
| **Sprint Planning Background**| En el sprint decidimos reunirnos para verificar el progreso de cada uno de los participantes y el progreso desde el punto de vista grupal, luego de ello buscamos formas y acciones de mejora. |
| **Date** | 8/11/25    |
| **Time** | 20:00 horas |
| **Location** | Via Discord |
| **Prepared By** | Sergio Aguirre |
| **Attendees** | Joseph Rodriguez, Sergio Aguirre, Victor Rojas, Maria Muñoz, Luis Montañez |
| **Sprint 2 Goal** | En este sprint, nos enfocamos en avanzar en el desarrollo de la aplicación móvil de Osito Polar para Android e iOS utilizando Flutter. Además, se ha completado el despliegue del backend al 100%, lo que asegura que ambos sistemas estén totalmente integrados y funcionales. Este avance nos permitirá ofrecer una experiencia de usuario más completa, asegurando la estabilidad y escalabilidad de la aplicación para las siguientes etapas del proyecto. |
| **Sprint 2 Velocity** | 15 |
| **Sum of Story Points** | [cite_start]21 | [cite: 2]

#### 4.2.2.2. Sprint Backlog 2
Sprint # | Sprint 2 | | | | | | |
---------|----------|---------|-------|-----|----|----|---|
User Story | Work-Item / Task
ID | Title | ID | Title | Description | Estimation (Hours) | Assigned To | Status
US06| Agregar equipos | UT01 | Implementar estructura | Crear los componentes, entidades y servicios de los equipos | 4 | Sergio Aguirre | Done
[cite_start]... (Resto de tabla) [cite: 2]

#### 4.2.2.3. Development Evidence for Sprint Review
| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---------|----------|----------------|-----------|-------------|--------------|
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | 22ea4bf | Feature: implement adding technician | Feature: adding technician | 12/11/25     |
[cite_start]... (Resto de tabla) [cite: 2]

#### 4.2.2.4. Testing Suite Evidence for Sprint Review
| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---------|----------|----------------|-----------|-------------|--------------|
| https://github.com/Equipo4-Aplicaciones-Moviles/OsitoPolar-Provider | technician_management | 22ea4bf | Feature: implement adding technician | Feature: adding technician | 12/11/25     |
[cite_start]... (Resto de tabla) [cite: 2]

#### 4.2.2.5. Execution Evidence for Sprint Review
**Pantalla inicial** <img src="assets/TF/pantalla1.jpg" height="400"><br>
**Pantalla de inicio de sesión** <img src="assets/TF/pantalla2login.jpg" height="400"><br>
**Pantalla de registro de usuario** <img src="assets/TF/pantalla3register.jpg" height="400"><br>
[cite_start]... (Resto de pantallas) [cite: 2]

#### 4.2.2.6. Services Documentation Evidence for Sprint Review
**OsitoPolarPlatform.api**
<img src="assets/TF/ositopolarswagger.jpg" height="400"><br>
<img src="assets/TF/workorders.jpg" height="400"><br>
[cite_start]... (Resto de imágenes) [cite: 2]

#### 4.2.2.7. Software Deployment Evidence for Sprint Review
#### 4.2.2.8. Team Collaboration Insights during Sprint

### 4.2.3. Sprint 3
(Tabla Sprint Backlog 3) [cite_start][cite: 2]

## 4.3. Validation Interviews

### 4.3.1. Diseño de Entrevistas
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
[cite_start]... (Resto de preguntas) [cite: 2]

<h3>Preguntas para el Segmento 2: Empresas Proveedoras de Servicios</h3>
<h4>Recepción y Gestión de Solicitudes</h4>
<ul>
  <li>¿Puedes describir cómo es el proceso de recibir una nueva solicitud de servicio en la app y qué aspectos destacarías, tanto positivos como áreas de mejora?</li>
  [cite_start]... (Resto de preguntas) [cite: 2]
</ul>

### 4.3.2. Registro de Entrevistas
En esta sección tenemos el análisis de las entrevistas por segmentos objetivos.

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
| **Gestión de Cartera de Clientes** | Ordenada; propone **carpetas** para clientes enterprise y **push** por vencimiento de mantenimiento programado. [cite_start]| [cite: 2]

### 4.3.3. Evaluaciones según heurísticas
**UX Heuristics & Principles Evaluation** **Usability – Inclusive Design – Information Architecture**

**Información del Proyecto**
- **Carrera:** Ingeniería de Software
- **Curso:** Aplicaciones Web
- **Auditor:** Inteligencia Artesanal
- **Cliente:** Inteligencia Artesanal
- **Site o App a Evaluar:** OsitoPolar (aplicación móvil iOS/Android)

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

### Escala de Severidad
| Nivel | Descripción |
|------:|-------------|
| 1 | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| 2 | Problema menor: puede ocurrir con más frecuencia o es más difícil de superar para el usuario. Debería tener una prioridad baja para resolverse en la próxima versión. |
| 3 | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlo. Debería tener alta prioridad para corregirse. |
| 4 | Problema muy grave: error que impide al usuario continuar utilizando la herramienta. Debe corregirse antes del lanzamiento. |

### Tabla Resumen
| # | Problema                                                                                          | Escala de severidad | Heurística/Principio violado                           | Tarea evaluada                                  |
|---|---------------------------------------------------------------------------------------------------|:-------------------:|--------------------------------------------------------|-------------------------------------------------|
| 1 | Formulario de solicitud no exige **datos técnicos mínimos** (foto, lectura de temperatura, síntoma) | 3 | Prevención de errores / Ayuda y documentación          | Recepción y gestión de solicitudes              |
| 2 | Sin **exportación** de reportes (PDF/Excel)                                                        | 2 | Control del usuario / Flexibilidad                     | Historial y reportes técnicos                   |
| 3 | No se pueden **modificar rutas**/reagrupar visitas por zona con facilidad                          | 2 | Flexibilidad y eficiencia de uso                       | Gestión de técnicos                             |
| 4 | Falta **ranking/KPIs** y **gráficos comparativos** por técnico                                     | 2 | Visibilidad del estado del sistema                     | Gestión de técnicos                             |
| 5 | Reportes sin **sugerencias automáticas** (ahorro/diagnóstico)                                      | 3 | Ayuda y documentación / Reconocimiento antes que recuerdo | Visualización de reportes                    |
| 6 | No existen **alertas automáticas** para **mantenimientos programados** | 3 | Prevención de errores / Eficiencia                      | Cartera de clientes                             |
| 7 | Sin **carpetas/etiquetas** personalizadas para clientes con alta carga                             | 2 | Flexibilidad y eficiencia de uso                       | Cartera de clientes                             |
| 8 | Falta **silenciamiento programado** de **notificaciones push** por horarios                        | 2 | Control y libertad del usuario                         | Monitoreo y alertas (push)                      |
| 9 | **Reprogramación** de citas no está disponible en **un toque** | 2 | Minimizar la carga / Eficiencia                         | Solicitudes de servicio                          |
|10 | **Registro de equipos** podría ser más veloz (duplicar como **plantilla** / **autocompletar** por marca) | 1 | Eficiencia de uso / Consistencia y estándares          | Registro y gestión de equipos                   |
|11 | Falta **resumen diario** de alertas por **WhatsApp/Email** además del push                         | 1 | Flexibilidad / Acceso a la información                  | Monitoreo y alertas                              |
|12 | Ausencia de **chat breve** para coordinar con técnico desde la solicitud                           | 2 | Visibilidad/Feedback / Correspondencia con el mundo real | Solicitudes de servicio                       |

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
4. [cite_start]**Gestión avanzada por cliente** con **alertas de mantenimiento programado** y **carpetas/etiquetas** personalizadas. [cite: 2]

<div style="page-break-after: always;"></div>

# Conclusiones
Conclusiones y recomendaciones.
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

Este trabajo ha demostrado que OsitoPolar no solo resuelve un problema real, sino que tiene el potencial de transformar la forma en que se gestiona la refrigeración comercial y técnica en el Perú. [cite_start]Los próximos pasos deberán enfocarse en escalar esta solución de manera sostenible y centrada en el usuario. [cite: 2]

# Videos
- Video App Validation
- Video About the Product
- Video About the Team

# Glosario

# Bibliografía
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
- W3Schools. (s.f.). *HTML style guide and coding conventions*. [cite_start]Recuperado el 10 de julio de 2025, de https://www.w3schools.com/html/html5_syntax.asp [cite: 2]

# Anexos
- Organización GitHub: [https://github.com/Inteligencia-Artesanal-Aplicaciones-Web](https://github.com/Equipo5-Aplicaciones-Moviles/upc-Aplicaciones-Moviles-Equipo5)
- [cite_start]Miro : https://miro.com/app/board/uXjVJGeldZw=/ [cite: 2]
