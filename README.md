# **Informe Trabajo Final**

<p align="center">
  <img src="assets/upc_logo.png" alt="Logo de la UPC" />
</p>

<p align="center"><strong>Universidad Peruana de Ciencias Aplicadas</strong></p>

<p align="center"><strong>Ingeniería de Software</strong><br>
Fundamentos de Arquitectura de Software <br>
<strong>Profesor: Jorge Luis Delgado Vite</strong> </p>

<h2 align="center">INFORME</h2>

<h3 align="center">Startup: Grupo 2</h3>
<p align="center"><strong>Producto: Workstation</strong></p>

<h3 align="center">Team Members:</h3>

<div align="center">

| **Member**                       | **Code**   |
| -------------------------------- | ---------- |
| Rodrigo Liberato Saldana         | U202215623 |
| Renzo Miguel Llerena Delgado     | U202312399 |
| Henry Kevin Diaz Gutierrez       | U201819674 |
| Diego Sebastián Zúñiga Murillo   | U202310636 |
| Braulio Rodrigo Torrejon Navarro | U201711828 |

</div>

<p align="center"><strong>Septiembre 2025</strong></p>

# Registro de Versiones del Informe

| Versión | Fecha      | Autor(es)                                                                                                                                      | Descripción de la modificación                                                                                                     |
| ------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| TB1     | 25-04-2025 | Liberato Rodrigo, Renzo Miguel Llerena Delgado, Henry Kevin Diaz Gutierrez , Diego Sebastián Zúñiga Murillo y Braulio Rodrigo Torrejon Navarro | Los 3 capitulos del primer avance fueron completados, junto a las conclusiones e informacion necesaria para el avance del trabajo. |

# Project Report Collaboration Insights

![insights](https://media.discordapp.net/attachments/766316535290789908/1416270438958633052/image.png?ex=68c63c21&is=68c4eaa1&hm=3941bcc1e27ba6ca7d5d2cddd15afc5ab8324c40937426745902c2d3188b8943&=&format=webp&quality=lossless)

# Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)

---

## Capítulo I: Introducción

- [1.1 Start-up Profile](#11-start-up-profile)
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

---

## Capítulo II: Requirements Elicitation & Analysis

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

---

## Capítulo III: Requirements Specification

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

---
## Capítulo IV: Design

- [4.1 Design Concepts, ViewPoints & ER Diagrams](#41-design-concepts-viewpoints--er-diagrams)
  - [4.1.1 Principles Statements](#411-principles-statements)
  - [4.1.2 Approaches Statements Architectural Styles & Patterns](#412-approaches-statements-architectural-styles--patterns)
  - [4.1.3 Context Diagram](#413-context-diagram)
  - [4.1.4 Approach driven ViewPoints Diagrams](#414-approach-driven-viewpoints-diagrams)
  - [4.1.5 Relational/Non Relational Database Diagram](#415-relationalnon-relational-database-diagram)
  - [4.1.6 Design Patterns](#416-design-patterns)
  - [4.1.7 Tactics](#417-tactics)

- [4.2 Architectural Drivers](#42-architectural-drivers)
  - [4.1.8 Design Purpose](#418-design-purpose)
  - [4.1.9 Primary Functionality (Primary User Stories)](#419-primary-functionality-primary-user-stories)
  - [4.1.10 Quality Attribute Scenarios](#4110-quality-attribute-scenarios)
  - [4.1.11 Constraints](#4111-constraints)
  - [4.1.12 Architectural Concerns](#4112-architectural-concerns)

- [4.3 ADD Iterations](#43-add-iterations)
  - [4.2.1 Iteration 1: Workstation Office Recommendation](#421-iteration-1-workstation-office-recommendation)
    - [4.2.1.1 Architectural Design Backlog 1](#4211-architectural-design-backlog-n)
    - [4.2.1.2 Establish Iteration Goal by Selecting Drivers](#4212-establish-iteration-goal-by-selecting-drivers)
    - [4.2.1.3 Choose One or More Elements of the System to Refine](#4213-choose-one-or-more-elements-of-the-system-to-refine)
    - [4.2.1.4 Choose One or More Design Concepts That Satisfy the Selected Drivers](#4214-choose-one-or-more-design-concepts-that-satisfy-the-selected-drivers)
    - [4.2.1.5 Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces](#4215-instantiate-architectural-elements-allocate-responsibilities-and-define-interfaces)
    - [4.2.1.6 Sketch Views (C4 & UML) and Record Design Decisions](#4216-sketch-views-c4--uml-and-record-design-decisions)
    - [4.2.1.7 Analysis of Current Design and Review Iteration Goal (Kanban Board)](#4217-analysis-of-current-design-and-review-iteration-goal-kanban-board)


- [Avance de Conclusiones, Bibliografía y Anexos (links)](#avance-de-conclusiones-bibliografía-y-anexos-links)

## Capítulo I: Introducción

### 1.1. Start-up Profile

#### 1.1.1. Descripción de la Startup

WorkStation es una aplicación web innovadora diseñada para optimizar la reserva ágil y eficiente de espacios de trabajo en oficinas compartidas. Su misión es conectar a freelancers, profesionales remotos, startups y compañías de todo tamaño con espacios de coworking disponibles en su ciudad o en cualquier parte del mundo.

La plataforma permitirá a los usuarios explorar, comparar y reservar en tiempo real escritorios, salas de reuniones, oficinas privadas y otros recursos. Cada espacio ofrecerá información detallada sobre su ubicación, tarifas, horarios, disponibilidad, fotografías, servicios incluidos (como Wi-Fi, café, impresoras, entre otros) y valoraciones de la comunidad.

Considerando la flexibilidad y adaptabilidad como factores clave en el crecimiento de las startups y en la dinámica del trabajo independiente, WorkStation se presenta como una alternativa moderna frente a la rigidez de los contratos tradicionales, brindando una solución práctica, accesible y contemporánea para cubrir las necesidades de los equipos y profesionales de hoy.

#### 1.1.2. Perfiles de integrantes del equipo

| Foto                                                                                                                                                                                                                                                                                 | Alumno                         | Descripción                                                                                                                                                                                                                                                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![Rodrigo](https://media.discordapp.net/attachments/766316535290789908/1414761032928464907/rodrigo.png?ex=68c0be63&is=68bf6ce3&hm=ff615cb9f2f6cd66256a62ab4857639fcf3cd26cacefcbd283c385287daf8c64&=&format=webp&quality=lossless)                                                   | Liberato Saldaña Rodrigo       | Estudiante de Ingeniería de Software que planea enfocarse en Ciencia de Datos y Ciberseguridad. Planea dar apoyo activo al grupo y asumir el rol de líder para encaminar al equipo hacia el cumplimiento de sus metas.                                                                                                                           |
| ![Renzo](https://github.com/1ASI0732-Grupo-2/report/blob/develop/assets/img/Chapter-I/RenzoLlerena.png?raw=true)                                                                                                                                                                     | Renzo Miguel Llerena Delgado   | Me destaco por ser responsable, trabajador y tener un enfoque en la perfección y la calidad en todos mis proyectos. Disfruto trabajando en equipo, colaborando para alcanzar mis objetivos y siempre buscando superar expectativas. Me mantengo en constante aprendizaje, dispuesto a enfrentar desafíos con una actitud proactiva y resolutiva. |
| ![Henry](https://github.com/1ASI0732-Grupo-2/report/blob/develop/assets/img/Chapter-I/Henry.png?raw=true)                                                                                                                                                                            | Henry Kevin Diaz Gutierrez     | Soy estudiante de Ingenieria de Software en la UPC.Me caracterizo por ser creativo , cumplir con lo que se me brinda y ayudar a resolver problemas si se presenta.Desde siempre me intereso el tema de los videojuegos y de el tipo de diseño que se empleaba, eso hizo que me guste el desarrollo de software.                                  |
| ![Diego](https://media.discordapp.net/attachments/1082800870334419014/1415786757659693106/69ed58d9-a022-48a1-86b3-b7fa8ae451bb.png?ex=68c479ab&is=68c3282b&hm=04b6e642e588c672e684388b42f293d845cd831a6eaf6e0c60d29f8af4bf103f&=&format=webp&quality=lossless&width=574&height=1022) | Diego Sebastián Zúñiga Murillo | Estudiante en el sexto ciclo de la carrera de Ingenieria de Software que busca expandir sus conocimientos en diversas tecnologías, soy una persona participativa y colaborativa y siempre me adapto rápido a las situaciones de cambio, estoy preparado para afrontar las adversidades que este trabajo signifca para mi y como grupo            |
| ![Braulio](https://media.discordapp.net/attachments/1092294135525949540/1416127872682164314/image.png?ex=68c5b75b&is=68c465db&hm=8ff06e48619ca4e4c4c4cb601db661f18d69cb47a6ca4d8b39670620f8a9af73&=&format=webp&quality=lossless)                                                    | Braulio Torrejon Navarro       | Estudiante de Ingenieria de software del 7mo ciclo, planeo dar lo mejor de mi en este grupo, tambien deseo aprender mucho del curso para mi futuro profesional                                                                                                                                                                                   |

### 1.2. Solution Profile

#### 1.2.1. Antecedentes y problemática

| Aspecto                                           | Descripción                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Who (¿Quiénes somos los involucrados?)**        | Nosotros, como principales usuarios, somos freelancers, trabajadores remotos, startups, pequeñas empresas y nómadas digitales que necesitamos espacios de trabajo profesionales, cómodos y flexibles sin tener que alquilar oficinas a largo plazo. <br><br> También forman parte clave los dueños y administradores de espacios de coworking, quienes buscan mayor visibilidad, una gestión más ágil de sus reservas y captar nuevos clientes. |
| **What (¿Qué necesitamos?)**                      | Necesitamos una plataforma centralizada, intuitiva y fácil de usar que nos permita buscar, comparar, reservar y pagar espacios de coworking en distintas ubicaciones, con información clara y disponibilidad en tiempo real. <br><br> Hoy en día, el proceso suele ser manual, lento y disperso en múltiples canales poco estandarizados (páginas web propias, redes sociales, WhatsApp, etc.).                                                 |
| **Where (¿Dónde ocurre el problema?)**            | En ciudades con alta actividad profesional y creciente demanda de espacios flexibles, como Lima, Arequipa, Medellín, Bogotá o Ciudad de México. <br><br> Esta necesidad puede extenderse tanto a nivel nacional como internacional a medida que el trabajo remoto sigue consolidándose.                                                                                                                                                         |
| **When (¿Cuándo surge esta necesidad?)**          | La necesidad está presente en todo momento y puede surgir de forma imprevista. <br><br> A veces necesitamos espacios por horas, días o semanas, y en otras ocasiones soluciones de último minuto para reuniones o trabajo inmediato.                                                                                                                                                                                                            |
| **Why (¿Por qué tenemos esta necesidad?)**        | El mundo laboral cambió. La pandemia aceleró el trabajo remoto y la cultura freelance. <br><br> Necesitamos trabajar en entornos productivos y profesionales, pero sin asumir compromisos de largo plazo. Sin embargo, aún no existe una solución masiva y eficiente que reúna toda la oferta disponible y simplifique el proceso de reserva.                                                                                                   |
| **How (¿Cómo podemos solucionarlo?)**             | Con el desarrollo de una aplicación web llamada **WorkStation**, que nos permita explorar una amplia variedad de espacios de coworking, revisar disponibilidad, leer opiniones, aplicar filtros, reservar en tiempo real y pagar desde una sola interfaz.                                                                                                                                                                                       |
| **How Much (¿Cuánto cuesta y cómo se monetiza?)** | Los precios cambian según la ciudad, el tipo de espacio, los servicios y el tiempo de uso. <br><br> La plataforma mostrará tarifas claras y actualizadas. El modelo de negocio se basará en comisiones por reserva, planes de suscripción para coworkings y membresías premium para usuarios frecuentes.                                                                                                                                        |

#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

##### Dominio del Problema

El proyecto **WorkStation** se desarrolla en el ámbito de los **espacios de trabajo compartidos (coworking)**, una industria en crecimiento impulsada por el teletrabajo, el autoempleo y la economía digital. Sin embargo, la relación entre la **oferta** (espacios disponibles) y la **demanda** (profesionales o empresas en expansión) sigue siendo fragmentada, sobre todo en Perú, donde aún no existen plataformas de gran alcance que conecten ambas partes de forma eficiente.

#### Segmentos de Cliente

1. **Freelancers, startups y profesionales remotos**  
   Personas de 22 a 40 años que buscan espacios de trabajo flexibles y bien ubicados. Valoran la autonomía, la conectividad y la comodidad, y esperan gestionar sus reservas de forma rápida desde una plataforma digital.

2. **Dueños o administradores de coworkings**  
   Emprendedores o pequeñas empresas que necesitan visibilidad, gestión automatizada de reservas y mejores canales para ocupar sus instalaciones. Muchos aún dependen de procesos manuales o redes sociales.

#### Puntos de Dolor

- **Freelancers y startups**:

  - No cuentan con una oferta centralizada y confiable.
  - Carecen de filtros para comparar por ubicación, precio o servicios.
  - El proceso de reserva suele ser lento, informal y poco transparente.

- **Propietarios de coworkings**:
  - Alta dependencia de canales informales (WhatsApp, redes sociales).
  - Falta de herramientas para gestionar disponibilidad en tiempo real.
  - Pierden ingresos por baja visibilidad y reservas irregulares.

#### Brecha Detectada

En Perú aún no existe una plataforma consolidada que conecte en tiempo real a freelancers y startups con coworkings disponibles. Esto genera una experiencia ineficiente tanto para los usuarios como para los propietarios.

A diferencia de Estados Unidos o Europa —donde plataformas como **LiquidSpace** o **Deskpass** lideran el mercado— el ecosistema local carece de soluciones digitales adaptadas a las necesidades del país.

#### Visión y Estrategia

**Visión**  
Crear una plataforma web tipo **marketplace** que ofrezca a los usuarios una experiencia de reserva ágil, segura y personalizada, y a los propietarios una herramienta de gestión que maximice el uso de sus espacios.

**Estrategia**

- Desarrollar un **MVP** para validar pronto la propuesta de valor.
- Priorizar la usabilidad, accesibilidad y confianza en la plataforma.
- Generar alianzas con coworkings emergentes en Lima.
- Implementar un modelo de monetización basado en comisiones y herramientas analíticas.

#### Segmento Inicial

Para validar la propuesta, se enfocará primero en:

- **Usuarios meta**: Freelancers y profesionales digitales de 22 a 35 años en Lima Metropolitana, que trabajan de forma remota o independiente.
- **Aliados estratégicos**: Coworkings pequeños y medianos en distritos céntricos como Miraflores, Barranco y San Isidro, que no cuenten con sistemas propios de gestión o marketing digital.

##### 1.2.2.2. Lean UX Assumptions

- **Asumimos que los usuarios requieren flexibilidad y comodidad en sus espacios de trabajo**
- **Asumimos que los propietarios de espacios de coworking necesitan mayor visibilidad y eficiencia en la gestión de reservas**
- **Asumimos que la búsqueda y reserva de espacios de coworking es un proceso fragmentado y poco confiable**
- **Asumimos que los usuarios están dispuestos a pagar por una solución eficiente y confiable**
- **Asumimos que la digitalización mejorará la eficiencia operativa de los espacios de coworking**

##### 1.2.2.3. Lean UX Hypothesis Statements

| Nº    | Hipótesis                                                                                                                                                                                                                                   | Impacto Esperado                                                                      |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| **1** | Si ofrecemos una **plataforma centralizada, intuitiva y fácil de usar** para reservar espacios de coworking, entonces los **freelancers y pequeñas empresas** la preferirán por la flexibilidad y el acceso a diversas opciones de trabajo. | Mayor adopción de la plataforma por parte de profesionales independientes y startups. |
| **2** | Si los **propietarios de coworkings** obtienen más visibilidad y una herramienta para gestionar reservas de manera eficiente, entonces **aumentará la ocupación** de sus espacios y la **satisfacción de sus clientes**.                    | Incremento en la rentabilidad y fidelización de clientes.                             |
| **3** | Si los usuarios pueden **comparar precios, consultar disponibilidad en tiempo real y leer reseñas**, entonces tomarán decisiones de reserva con **mayor rapidez y confianza**.                                                              | Mejora significativa en la experiencia del cliente y en el nivel de conversión.       |
| **4** | Si la plataforma aplica un **modelo de comisión por reserva o membresía**, entonces se generarán **ingresos recurrentes** para la plataforma y beneficios para los propietarios.                                                            | Sostenibilidad financiera del modelo de negocio e incentivo para la adopción.         |
| **5** | Si se **digitaliza la gestión de reservas**, entonces los propietarios de coworkings podrán **reducir costos operativos** y **mejorar su rentabilidad** a largo plazo.                                                                      | Optimización de recursos y eficiencia en la operación diaria.                         |

##### 1.2.2.4. Lean UX Canvas

| Sección                                                                                      | Descripción                                                                                                                                                                                                                                                                                                                                                                                                                    |
| -------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **1. Business Problem**                                                                      | La conexión entre la creciente demanda de espacios de trabajo flexibles y la oferta de coworkings está fragmentada. Los usuarios no cuentan con plataformas confiables y los propietarios carecen de herramientas de gestión efectivas.                                                                                                                                                                                        |
| **2. Business Outcomes**                                                                     | - Incrementar ingresos mediante comisiones y membresías.<br>- Reducir el tiempo promedio de búsqueda y reserva.<br>- Ayudar a miles de peruanos a encontrar un lugar para trabajar con mejores resultados.                                                                                                                                                                                                                     |
| **3. Users**                                                                                 | - **Freelancers y trabajadores remotos** (22–40 años) que buscan espacios acogedores con servicios como Wi-Fi y salas de reuniones.<br>- **Startups y equipos pequeños** que necesitan lugares temporales para colaborar o reunirse.<br>- **Propietarios de coworkings** que desean captar más clientes y administrar reservas de forma sencilla.                                                                              |
| **4. User Benefits**                                                                         | - Acceso a espacios que se adapten a sus necesidades (precio, ubicación, servicios).<br>- Mayor actividad y ocupación para los propietarios, con menos esfuerzo.<br>- Más reservas frecuentes y recomendaciones de usuarios satisfechos.                                                                                                                                                                                       |
| **5. Solutions**                                                                             | - Motor de búsqueda con filtros por ciudad, precio y servicios.<br>- Sistema de reservas con calendario en tiempo real.<br>- Panel para propietarios con gestión de disponibilidad, estadísticas y reseñas.<br>- Notificaciones automáticas (email, push) para recordatorios y confirmaciones.                                                                                                                                 |
| **6. Hypotheses**                                                                            | - Centralizar la oferta de coworkings ahorrará tiempo y generará confianza.<br>- Digitalizar la gestión aumentará la ocupación y reducirá la carga operativa.<br>- Mostrar precios, disponibilidad y reseñas en tiempo real permitirá decisiones más rápidas y acertadas.<br>- Comisiones y membresías premium harán el modelo rentable.<br>- Una plataforma ágil y confiable se convertirá en el canal principal de reservas. |
| **7. What’s the most important thing we need to learn first?**                               | Validar si los usuarios realmente desean una plataforma centralizada de reservas, entender sus preferencias y comprobar si les resulta más cómoda frente a métodos tradicionales.                                                                                                                                                                                                                                              |
| **8. What’s the least amount of work we need to do to learn the next most important thing?** | Realizar entrevistas, recolectar feedback y pruebas de usabilidad para medir la relevancia de las reservas de espacios tanto para usuarios como para propietarios.                                                                                                                                                                                                                                                             |

### 1.3. Segmentos objetivo

En el proyecto nos enfocamos en dos segmentos principales de usuarios, directamente relacionados con el dominio del problema: los propietarios de espacios de coworking y los usuarios que buscan dichos espacios, como freelancers y startups. A continuación, se describen en detalle ambos perfiles.

### Propietarios de Inmuebles (Coworkings)

Corresponde a personas naturales o jurídicas que administran o alquilan espacios acondicionados para trabajo compartido, como oficinas, salas de reuniones, escritorios flexibles, entre otros.

#### Características Demográficas

- **Ubicación:** Principalmente zonas urbanas de alto flujo empresarial, como Miraflores, San Isidro, Surco (Lima).
- **Edad promedio de los administradores:** 30 a 55 años.
- **Nivel socioeconómico:** Medio-alto a alto.
- **Tipo de propiedad:** Empresas formales, pymes inmobiliarias o propietarios individuales.

#### Datos Relevantes

- En Lima existen más de 150 espacios de coworking activos (Andina, 2023).
- El 67% de estos espacios reporta dificultades para llenar su capacidad total, especialmente en horarios valle (CoworkIntel, 2022).
- La mayoría carece de una plataforma de reservas centralizada, y operan mediante WhatsApp, redes sociales o formularios web.

#### Necesidades Clave

- Mayor visibilidad de su espacio.
- Automatización del proceso de reservas.
- Optimización de la ocupabilidad de sus ambientes.
- Acceso a métricas sobre uso y satisfacción de clientes.

---

### Freelancers y Startups

Este grupo está compuesto por trabajadores independientes, equipos pequeños de desarrollo, marketing, diseño, entre otros, así como emprendedores en etapa inicial.

#### Características Demográficas

- **Edad:** Entre 20 y 40 años.
- **Ubicación:** Centros urbanos con alta conectividad.
- **Nivel educativo:** Técnico o universitario completo.
- **Ocupación:** Diseñadores, desarrolladores, consultores, creadores de contenido, equipos de startups.
- **Ingreso promedio mensual:** S/ 2,000 – S/ 5,000 (varía por actividad y clientes).

#### Datos Relevantes

- Se estima que más de 500,000 peruanos trabajan como freelancers (Statista, 2022), y esta cifra crece con el auge del trabajo remoto postpandemia.
- Según un estudio de WeWork (2021), el 78% de los trabajadores remotos en LATAM buscan espacios fuera de casa al menos una vez por semana.
- El 60% de los freelancers jóvenes en Lima considera los coworkings como espacios que fomentan productividad y networking (PUCP, 2023).

#### Necesidades Clave

- Acceso flexible a espacios profesionales sin necesidad de contrato a largo plazo.
- Precios accesibles, según uso (por horas o días).
- Información clara sobre servicios incluidos (wifi, café, salas, etc.).
- Reseñas de otros usuarios para tomar decisiones confiables.

---

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

WeWork, fundada en 2010 en Nueva York por Adam Neumann y Miguel McKelvey, empezó como una startup de espacios de coworking. Su modelo de negocio se basaba en alquilar oficinas a largo plazo, rediseñarlas como espacios colaborativos y flexibles, y alquilarlas a empresas, freelancers y emprendedores a corto plazo.

La compañía creció rápidamente, alcanzando una valoración de $47 mil millones en 2019. Sin embargo su estruendoso intento de salir a la bolsa fracaso debido a la mala gestión y al modelo insostenible que la compañía tenia, además uno de sus fundadores renuncio. Todo esto llevo que WeWork a declararse en bancarrota en noviembre de 2023. Actualmente, bajo la nueva dirección de SoftBank, busca reestructurarse y enfocarse en rentabilidad.

**Spaces:**
Spaces fue fundada en 2008 en Ámsterdam (Países Bajos) como una marca de espacios de coworking y oficinas flexibles, enfocada en diseño innovador y comunidad. En 2016, fue adquirida por IWG plc, lo que le permitió expandirse globalmente con mayor respaldo financiero.

**CoWorker:**

Coworker.com es una plataforma global de búsqueda y comparación de espacios de coworking, fundada en 2015 por Leanne Beesley y Sam Marks . A diferencia de WeWork o Spaces, Coworker no opera sus propios espacios, sino que funciona como un marketplace que conecta a usuarios con miles de espacios de coworking en todo el mundo.

La plataforma surgió para resolver un problema clave: la falta de transparencia y acceso a información sobre espacios de trabajo flexibles. Hoy, Coworker.com lista más de 20,000 espacios en 170+ países, ofreciendo reseñas, precios y disponibilidad en tiempo real.

**Oficinas YA!**

Oficinas YA! es una plataforma líder en América Latina especializada en la búsqueda, comparación y arrendamiento de oficinas y espacios de coworking. Fue fundada en 2015 en México y se ha expandido a otros países como Colombia, Argentina y Chile, con un enfoque en facilitar el proceso de encontrar espacios de trabajo flexibles para empresas y profesionales.

#### 2.1.1. Análisis competitivo

| **Competitive Analysis Landscape**        |                                                                                                                                                                                                                                                    |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **¿Por qué llevar a cabo este análisis?** | **Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.**                                                                                                                                                         |
|                                           | **Identificar que ventajas comerciales podemos obtener por parte de nuestros competidores. Funcionalidades, estrategias de marketing o productos que podriamos agregar, Gracias a esto lograr ser un competidor estable frente a estas companias** |

| **_Competidor_**          |                                                             | WorkStation                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | WeWork                                                                                                                                                                                                                                                                                                       | Spaces                                                                                                                                                                                                                 | Coworker                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Oficinas Ya!                                                                                                                                                                                                                                                                                              |
| ------------------------- | ----------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **_Logo_**                |                                                             | ![WorkStation](assets/img/Chpater-2/workstation.png.jpg)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | ![Wework](assets/img/Chpater-2/wework.png)                                                                                                                                                                                                                                                                   | ![Spaces](assets/img/Chpater-2/spaces.png)                                                                                                                                                                             | ![Coworker](assets/img/Chpater-2/coworker.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | ![OficinasYa](assets/img/Chpater-2/oficinasya.png)                                                                                                                                                                                                                                                        |
| **_Perfil_**              | Overview                                                    | Una aplicación web y móvil que ofrece servicios de su arrendaciones a empresas, freelances o startups a nivel mundial.                                                                                                                                                                                                                                                                                                                                                                                                                             | Una aplicación web y móvil que ofrece servicios de su arrendaciones a empresas, freelances o startups a nivel mundial.                                                                                                                                                                                       | Una aplicación web y móvil que ofrece servicios de su arrendaciones a empresas, freelances o startups a nivel mundial.                                                                                                 | Una aplicación web y móvil que ofrece servicios de su arrendaciones a empresas, freelances o startups a nivel mundial.                                                                                                                                                                                                                                                                                                                                                                                                        | Una aplicación web y móvil que ofrece servicios de su arrendaciones a empresas, freelances o startups a nivel mundial.                                                                                                                                                                                    |
|                           | **_Ventaja competitiva ¿Qué valor ofrece a los clientes?_** | Su propósito es conectar a freelancers, trabajadores remotos, startups y empresas de todos los tamaños con espacios de coworking disponibles en su ciudad o alrededor del mundo. La plataforma permitirá a los usuarios buscar, comparar y reservar escritorios, salas de reuniones, oficinas privadas y otros recursos disponibles en tiempo real. Cada espacio contará con información detallada como ubicación, precios, horarios, disponibilidad, fotos, servicios incluidos (Wi-Fi, café, impresoras, etc.), y valoraciones de otros usuarios | Además de servicios básicos como internet de alta velocidad, oficinas en buen estado, impresoras y cafetería ilimitada, también posee espacios flexibles y con diseños modernos, una comunidad global que permite el acceso a evento, networking y acceso a que los miembros del equipo conecten fácilmente. | Posee contratos cortos, membresías mensuales o planes flexibles que beneficien a los clientes. Oficinas con servicios adicionales, ergonómicos y decoración innovadora que ha resaltado al ganar un premio sobre eso.  | Sus funcionalidades mas resaltantes son la búsqueda inteligente que permite a los usuarios buscar y comprar precios de espacios coworking al rededor de mas de 170 paises. Ofrecen un sistema de reseñas y ratings para la comunidad. Asimismo brindan recursos para nómadas digitales, cómo guías de las ciudades de los mejores espacios coworking e información de visas o papeleo. Por ultimo, da la opción de una membresía llamada "Coworker Pass" que brinda acceso casi ilimitado a espacios y descuentos exclusivos. | Busqueda avanzada, como filtros o tipos de espacios. Asimismo birnda una visualizacion de fotos y videos 360. Ofrece oficinas virtuales, que brindan serivicio de gestion de correo y atencion personalizada de llamadas. UNa gran Flexibilidad de contratos desde horas hasta meses sin compromisos.<br> |
| **_Perfil de Marketing_** | **_Mercado objetivo_**                                      | Startups, emprendedores, freelancers, nomadas digitales o empresas tradicionales. Ademas de propietarios de inmuebles que deseen una optimizacion de ocupacion de sus ambientes.                                                                                                                                                                                                                                                                                                                                                                   | Startups, emprendedores, freelancers, nomadas digitales o empresas tradicionales.                                                                                                                                                                                                                            | Startups, emprendedores, freelancers, nómadas digitales.                                                                                                                                                               | Startups, emprendedores, freelancers, nómadas digitales o empresas tradicionales.                                                                                                                                                                                                                                                                                                                                                                                                                                             | Startups, emprendedores, freelancers, nómadas digitales o empresas tradicionales.                                                                                                                                                                                                                         |
|                           | **_Estrategias de marketing_**                              | Las propuestas que tenemos como marketing son las siguientes; anunciar la aplicación web por Google ads y redes sociales como Facebook, Instagram o en grupos de Telegram de Freelancers o Startups.                                                                                                                                                                                                                                                                                                                                               | Se promocionan por redes sociales queriendo expandir su estilo de vida creativo e innovacion en su comunidad de trabajo. Asimismo tienen eventos gracias a sus alianzas estrategicas con Microsoft y Salesforce. Por ultimo, algunos anuncios en Google Ads y SEO.                                           | Contenido en redes sociales, alianzas estratégicas, enfoque de diseño y experiencia y eventos que llaman a los clientes rápidamente.<br><br>                                                                           | La aplicación se promociona con optimización de búsquedas simples en el navegador, publica artículos y reportes acerca del coworking flexible, tiene una gran presencia en redes sociales y posee alianzas estratégicas con Selina, Outside o Airbnb for work.                                                                                                                                                                                                                                                                | Posee una presencia digital activa, con redes sociales y comunidades empresariales en Linkedin y Facebook. Tienen publicidad en Google Ads y remarketing. Por ultimo, tienen alianzas con espacios asociados en eventos conjuntos.                                                                        |
| **_Perfil de Producto_**  | **_Productos & Servicios_**                                 | Ofrecer la comunicación entre freelancers o startups con los propietarios de los inmuebles.                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Ofrecen sus propias oficinas para el uso de cualquier empresa, startup o que su mercado objetivo necesite.                                                                                                                                                                                                   | Ofrecen sus propias oficinas para el uso de cualquier empresa, startup o que su mercado objetivo necesite.                                                                                                             | Ofrecen oficinas de cualquier parte del mundo para el uso de cualquier empresa, startup o que su mercado objetivo necesite.                                                                                                                                                                                                                                                                                                                                                                                                   | Ofrecen oficinas de cualquier parte del mundo para el uso de cualquier empresa, startup o que su mercado objetivo necesite.                                                                                                                                                                               |
|                           | **_Precios & Costos_**                                      | Los precios variaran dependiendo de los propietarios, ellos decidirán el tiempo que puede estar disponible el inmueble y el precio. Asimismo, se incluirán descuentos dependiendo de las fechas o si alguno de las startups o freelancers posee una membresía con nuestra propuesta.                                                                                                                                                                                                                                                               | Los precios varian entre los diferentes paquetes que posee. Los escritorios compartidos varian entre $250 a $500. Mientras que las oficinas privadas desde $800 a $3000. Pero asimismo poseen planes de solo un dia, que varian entre $25 a $30.                                                             | Varian dependiendo de la ubicación, duracion del contrato o tipo de espacio. SIn embargo, Spaces posee una membrecia llamada "Spaces Global Pass" con acceso a multiples ubicaciones que varian desde $400 a $800.<br> | La búsqueda de espacios es gratuita y disponible para todos, sin embargo la membresía tiene un costo de $50 aproximadamente. <br><br>                                                                                                                                                                                                                                                                                                                                                                                         | La empresa cobra a los espacios una comisión del 10-20%, dependiendo del costo del inmueble.<br>                                                                                                                                                                                                          |
|                           | **_Canales de distribución (Web y/o Móvil)_**               | Los canales que usan son su aplicacion web.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Web/Móvil                                                                                                                                                                                                                                                                                                    | Los canales que usan son su aplicacion web y movil. Asimismo tienen ventas B2B, aliados coorporativos cmom aceleradoras, bancos y gremios empresariales.                                                               | Los canales que usan son su aplicacion web y movil. Sus redes de afiliados, como sus socios apoyan su distribucion.                                                                                                                                                                                                                                                                                                                                                                                                           | Los canales que usan son una aplicación web y móvil que ofrece servicios de su arrendaciones a empresas, freelances o startups a nivel mundial. Agentes telefónicos y aliados comerciales con inmobiliarias y desarrolladores de oficinas.                                                                |
| **_Análisis SWOT_**       | **_Fortalezas_**                                            | Startup innovadora, precios flexibles, diseno innovador y modelo escalable para futuras actualizaciones.                                                                                                                                                                                                                                                                                                                                                                                                                                           | Marca reconocida globalmente, flexibilidad y escalabilidad, red de comunidades profesionales y diseño innovador                                                                                                                                                                                              | Respaldo de IWG (solvencia financiera), diseño premium y experiencia de usuario, red global con sinergias (Regus, Signature) y modelo escalable y rentable                                                             | Modelo escalable sin costos de operar espacios físicos, base de datos global más amplia que competidores, ideal para nómadas digitales (mercado en crecimiento) y reseñas transparentes y comparación de precios                                                                                                                                                                                                                                                                                                              | Enfoque en Latinoamérica (conocimiento local), amplia red de espacios asociados, Asesoría personalizada sin costo y modelo sin costos fijos de operar espacios                                                                                                                                            |
|                           | **_Debilidades_**                                           | Pocos fondos, sin alianzas poderosas, bajos conocimientos del mercado y competidores mas experimentados en el rubro,                                                                                                                                                                                                                                                                                                                                                                                                                               | Dependencia de arrendamientos caros, alto endeudamiento, mala gestión financiera histórica y perdida de confianza post-bancarrota                                                                                                                                                                            | Menor reconocimiento global vs. WeWork, precios más altos que competidores locales, menor enfoque en "comunidad" que WeWork y crecimiento más lento que startups independientes                                        | Dependencia de espacios asociados (calidad variable), menor reconocimiento frente a marcas como WeWork, ingresos limitados si no aumenta volumen de reservas y Competencia con plataformas de reservas de espacios (ej. Deskpass)                                                                                                                                                                                                                                                                                             | Menor reconocimiento fuera de la región, dependencia de la calidad de los espacios listados, Competencia con plataformas globales (Coworker.com) y rentabilidad limitada si no escala el volumen de transacciones                                                                                         |
|                           | **_Oportunidades_**                                         | Expansion en un mercado emergente como lo seria Latino america, ideas frescas para revolucionar el mercado y futuras alianzas en camino.                                                                                                                                                                                                                                                                                                                                                                                                           | Modelo híbrido post-pandemia, expansión en mercados emergentes y alianzas con gobiernos para espacios públicos                                                                                                                                                                                               | Demanda de espacios híbridos post-pandemia, expansión en Asia y Latinoamérica y alianzas con grandes corporaciones                                                                                                     | Crecimiento del trabajo remoto y nómadas digitales, alianzas con gobiernos para promocionar destinos "workation" y expansión a mercados emergentes (Asia, Latinoamérica)                                                                                                                                                                                                                                                                                                                                                      | Crecimiento del trabajo híbrido en LATAM, alianzas con gobiernos para impulsar emprendimiento y expansión a ciudades secundarias con demanda creciente                                                                                                                                                    |
|                           | **_Amenazas_**                                              | Competencia, pocos recursos que no se puedan recuperar a corto plazo y cambios en tendencias laborales.                                                                                                                                                                                                                                                                                                                                                                                                                                            | Competencia (Spaces o locales independientes), crisis económicas reducen demanda y cambios en tendencias laborales (remote-first)                                                                                                                                                                            | Competencia de WeWork (reestructurada) y actores locales, recesión económica afecta demanda de espacios premium y cambio hacia el trabajo remoto permanente                                                            | Espacios que prefieren vender directamente (evitar comisiones), plataformas más grandes (ej. Airbnb) integrando coworking y saturación de marketplaces de coworking                                                                                                                                                                                                                                                                                                                                                           | Espacios que prefieren gestionar reservas directamente, entrada de competidores globales (ej. WeWork), crisis económicas que reduzcan la demanda de oficinas                                                                                                                                              |

#### 2.1.2. Estrategias y tácticas frente a competidores

| **_MATRIZ FODA y C.A.M.E_**                                                   | **Oportunidades:** Modelo hibrido post pandemia                                                                                                                                               | **Amenazas:** posibles cambios a trabajo remoto permanentemente                                                                                                |
| ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Fortalezas:** Innovacion, publico objetivo más amplio y mayor escalabilidad | Debido al modelo hibrido podríamos expandirnos debido a que nuestro publico objetivo llega a ser mas amplio que otros competidores, además de poder innovar en este mercado no tan explorado. | Tener en cuenta que habran mas espacios libres para otros rubros, por lo que se podrian usar de maneras diferentes en otras actividades que puedan ser utiles. |
| **Debilidades:** Sin alianzas poderosas como los competidores.                | Utilizar la oportunidad de modelo hibrido para promocionar nuestra aplicación a otras y así poder formar alianzas que puedan apoyar al crecimiento de nuestra startup                         | Debido al posible cambio a trabajo remoto permanente, las alianzas que se puedan tener en un futuro pueden seguir utilizandolas para otros rubros.             |

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

**PROPIETARIOS DE INMUEBLES**

- 1. Nombre completo
- 2. Edad
- 3. Distrito de residencia
- 4. Profesión
- 5. Actualmente, ¿tiene propiedades adicionales disponibles o sin uso en su vivienda actual?
- 6. ¿Qué hace con esa(s) propiedad(es)? ¿Tiene algo planeado para hacer?
- 7. ¿Qué piensa de los alquileres de oficina como espacios de coworking?
- 8. ¿Qué opinaría de una aplicación que conecta a dueños de espacios en alquiler con empresas que buscan alquilar estos espacios? Estaría dispuesto(a) a usarla?
- 9.  Que beneficios le gustaría tener a usted dentro de el trato entre usted y la compañía que trabaje en la propiedad?
- 10. Que comportamientos o hábitos no estarían dispuesto(a) a aceptar de la compañía/startup que trabaje en su propiedad?
- 11. Que funcionalidades le gustaría que tenga esta aplicación web?
- 12. ¿De que manera buscaría hacer este espacio uno seguro para ambos?

**FREELANCERS/STARTUPS**

- 1. Nombre completo
- 2. Edad
- 3. Distrito de residencia
- 4. Profesión
- 5. Actualmente, ¿desde donde trabaja?
- 6.  Cree que el lugar donde trabajan afecta la productividad de su trabajo?
- 7. Que es lo que busca en un lugar de trabajo?
- 8. ¿Ha escuchado hablar de los espacios de coworking?
- 9. ¿Qué opinaría de alquilar un espacio destinado para trabajar?
- 10. ¿Qué opinaría de una aplicación que le ofrezca la posibilidad de conectarlo con varios de estos espacios disponibles?
- 11. Que funcionalidades cree que debería tener una aplicación como esta?
- 12. ¿De que manera buscaría hacer este espacio uno seguro para ambas partes?

#### 2.2.2. Registro de entrevistas

##### Propietarios de Inmuebles

| **Campo**                     | **Detalle**                                                                                                                                                                                                                                                                                                                                   |
| ----------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nombre**                    | Alejandra Izaguirre                                                                                                                                                                                                                                                                                                                           |
| **Entrevistador**             | Rodrigo Liberato                                                                                                                                                                                                                                                                                                                              |
| **Edad**                      | 25                                                                                                                                                                                                                                                                                                                                            |
| **Resumen**                   | La entrevistada realizo una entrevista donde comparte sus expectativas acerca de una aplicacion que tenga la funcionalidad descrita con anterioridad y las funcionalidades que esperaria que tuviera, ademas de brindar informacion desde su experiencia para que la aplicacion siga un buen camino escuchando activamente a los usuarios.    |
| **Tiempo que empieza**        | 0:00 minutos                                                                                                                                                                                                                                                                                                                                  |
| **Duración de la entrevista** | 4:26 minutos                                                                                                                                                                                                                                                                                                                                  |
| **URL de la entrevista**      | [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202215623_upc_edu_pe/EZQz2DANI71MkOrpc1fJq3EBIRLd8PZ4sQAEEFybRm3YOg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=t6qB71) |

| **Campo**                     | **Detalle**                                                                                                                                                                                                                                                                                                   |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nombre**                    | Patricia Navarro                                                                                                                                                                                                                                                                                              |
| **Entrevistador**             | Braulio Torrejon                                                                                                                                                                                                                                                                                              |
| **Edad**                      | 50                                                                                                                                                                                                                                                                                                            |
| **Resumen**                   | En la entrevista se quiere que la gente que entraria a su propiedad respete lo que ella dice, que no alteren nada, que esten a la par de lo que ella dice al inicio, quiere que las personas sean personas ordenadas y en funcionalidades quiere seguirdad y poder ahi tener toda la información del contrato |
| **Tiempo que empieza**        | 0:00 minutos                                                                                                                                                                                                                                                                                                  |
| **Duración de la entrevista** | 4:57 minutos                                                                                                                                                                                                                                                                                                  |
| **URL de la entrevista**      | [Ver entrevista](https://drive.google.com/file/d/1xUJrZ8oBl1Qq0S6BJiDpcHgHXV1d9MYe/view?usp=sharing)                                                                                                                                                                                                          |

| **Campo**                     | **Detalle**                                                                                                                                                                                                                                                                                                                                                                           |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nombre**                    | Jeremy Uriel Reyes Correa                                                                                                                                                                                                                                                                                                                                                             |
| **Entrevistador**             | Diego Sebastian Zuñiga Murillo                                                                                                                                                                                                                                                                                                                                                        |
| **Edad**                      | 32                                                                                                                                                                                                                                                                                                                                                                                    |
| **Resumen**                   | El entrevistado expresa su necesidad de una aplicacion como "WorkStation" para cubrir el requisito de que las personas puedan usar lugares dedicados al trabajo, con la condicion de que sean ordenados y con total seguridad. El entrevistado menciona funcionalidades que le gustaría ver en una aplicacion así y nos da un enfoque para trabajar en el desarrollo de "WorkStation" |
| **Tiempo que empieza**        | 0:00 minutos                                                                                                                                                                                                                                                                                                                                                                          |
| **Duración de la entrevista** | 3:44 minutos                                                                                                                                                                                                                                                                                                                                                                          |
| **URL de la entrevista**      | [Ver entrevista](https://drive.google.com/file/d/1xet-bnrphJlHN9q8--i8BTqD-KbiidQo/view?usp=sharing)                                                                                                                                                                                                                                                                                  |

##### Freelancers/Startups

| **Campo**                     | **Detalle**                                                                                                                                                                                                                                                                                                                                         |
| ----------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nombre**                    | Renato Guillermo Calvo Yalan                                                                                                                                                                                                                                                                                                                        |
| **Entrevistador**             | Renzo Miguel Llerena Delgado                                                                                                                                                                                                                                                                                                                        |
| **Edad**                      | 21 años                                                                                                                                                                                                                                                                                                                                             |
| **Resumen**                   | El entrevistado compartio su necesidad de tener espacion coworking para trabajar con su equipo, ya que en su casa carece del espacio indicado para poder trabajar y también compartió su punto de vista sobre cómo debería ser nuestra propuesta bajo su propio criterio teniendo, por encima de todo, ubicaciones accesibles para el en San Isidro |
| **Tiempo que empieza**        | 0:00 minutos                                                                                                                                                                                                                                                                                                                                        |
| **Duración de la entrevista** | 4:29 minutos                                                                                                                                                                                                                                                                                                                                        |
| **URL de la entrevista**      | [Ver entrevista](https://drive.google.com/file/d/18nyxMf-ZdvX-bkOw9eGHqbmN1OXbzshb/view?usp=sharing)                                                                                                                                                                                                                                                |

| **Campo**                     | **Detalle**                                                                                                                                                                                                                                                                                                                                                                                      |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Nombre**                    | Jonatan David Escobar Laura                                                                                                                                                                                                                                                                                                                                                                      |
| **Entrevistador**             | Diego Sebastian Zuñiga Murillo                                                                                                                                                                                                                                                                                                                                                                   |
| **Edad**                      | 22 años                                                                                                                                                                                                                                                                                                                                                                                          |
| **Resumen**                   | Durante la entrevista, el participante señaló que necesita contar con un espacio de coworking para reunirse y trabajar con su equipo, ya que en casa las herramientas que tiene a mano no siempre son utiles a la hora de realizar su trabajo, el entrevistado reside en el distrito de Comas donde señala que tiene necesidad como él varias personas de un espacio para trabajar adecuadamente |
| **Tiempo que empieza**        | 0:00 minutos                                                                                                                                                                                                                                                                                                                                                                                     |
| **Duración de la entrevista** | 4:19 minutos                                                                                                                                                                                                                                                                                                                                                                                     |
| **URL de la entrevista**      | [Ver entrevista](https://drive.google.com/file/d/18sBgLuViOeTaP_g60ueuV6Y669vgPfMK/view?usp=sharing)                                                                                                                                                                                                                                                                                             |

| **Campo**                     | **Detalle**                                                                                                                                                                                                                                                                                                                                                                                          |
| ----------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nombre**                    | Jocelyn Damaly Almerco Rojas                                                                                                                                                                                                                                                                                                                                                                         |
| **Entrevistador**             | Henry Kevin Diaz Gutierrez                                                                                                                                                                                                                                                                                                                                                                           |
| **Edad**                      | 22 años                                                                                                                                                                                                                                                                                                                                                                                              |
| **Resumen**                   | Entrevisté a una desarrolladora de software de 22 años de San Juan de Lurigancho. La entrevistada señaló que el lugar de trabajo influye en su productividad y prefiere espacios tranquilos con buena conexión. Considera útil el coworking por horas o días y valora una aplicación que permita comparar opciones, reservar en línea y garantizar seguridad mediante verificación y calificaciones. |
| **Tiempo que empieza**        | 0:00 minutos                                                                                                                                                                                                                                                                                                                                                                                         |
| **Duración de la entrevista** | 3:12 minutos                                                                                                                                                                                                                                                                                                                                                                                         |
| **URL de la entrevista**      | [Ver entrevista](https://drive.google.com/file/d/1J5AS7eGplnLPDjFKJDMXJjuVzqm2OcxO/view?usp=sharing)                                                                                                                                                                                                                                                                                                 |

#### 2.2.3. Análisis de entrevistas

**Segmento 1: Propietarios de espacios de coworking**

Los entrevistados pertenecientes a este segmento manifestaron una preocupación recurrente por la seguridad, el orden y el respeto por las normas del lugar por parte de los usuarios. En particular, se hizo hincapié en la necesidad de que las personas que acceden a sus propiedades respeten las condiciones establecidas desde el inicio, sin alterar el entorno ni generar conflictos. La funcionalidad más valorada en la aplicación sería la capacidad de gestionar contratos, registrar condiciones de uso, y garantizar que los usuarios estén informados y comprometidos con las reglas del espacio.

Además, se destaca el interés de este segmento en que la aplicación permita una comunicación clara entre anfitriones y usuarios, así como herramientas que contribuyan a preservar el orden y brindar una experiencia segura y controlada. Las entrevistas también reflejan una disposición positiva a colaborar con el desarrollo del producto, aportando su experiencia directa para mejorar la propuesta de valor de la plataforma.

**Segmento 2: Usuarios que buscan espacios de coworking**

Este grupo estuvo conformado principalmente por profesionales jóvenes que residen en distritos urbanos como Comas y San Juan de Lurigancho, donde existe una demanda latente por espacios de trabajo adecuados. Los entrevistados señalaron que en sus hogares no cuentan con condiciones óptimas para desarrollar sus actividades laborales, y por ello consideran valioso disponer de espacios accesibles, bien equipados y funcionales para trabajar de manera individual o colaborativa.

La preferencia por espacios tranquilos, con buena conexión a internet y opciones de alquiler por horas o días, fue destacada como un factor decisivo. Asimismo, los usuarios esperan que la aplicación incluya funcionalidades clave como: búsqueda y comparación de espacios disponibles, reservas en línea, y mecanismos de verificación y calificación, que garanticen la seguridad y la calidad del servicio.

Este segmento demuestra una actitud proactiva hacia el uso de tecnología para facilitar sus dinámicas laborales, y valora especialmente las herramientas digitales que simplifican procesos y ofrecen transparencia en las transacciones.

**Conclusionesl analisis**

El análisis de las entrevistas indica que tanto los propietarios de espacios de coworking como los usuarios que buscan estos espacios comparten un interés común por la seguridad, el orden y la facilidad de uso. Sin embargo, cada segmento prioriza diferentes funcionalidades de la aplicación: mientras que los propietarios se enfocan en el control del entorno y cumplimiento de normas, los usuarios valoran la comodidad, accesibilidad y confianza en el servicio.

Esta información sugiere que el desarrollo de WorkStation debe considerar una doble experiencia de usuario, personalizada para anfitriones y para trabajadores, con herramientas específicas que respondan a las necesidades de cada grupo. Escuchar activamente las experiencias y recomendaciones de ambos perfiles será fundamental para construir una aplicación útil, escalable y alineada con las dinámicas reales del mercado.

### 2.3. Needfinding

#### 2.3.1. User Personas

Para esta sección hemos tomado en cuenta dos User Persona que corresponden a los dos segmentos objetivos nombrados anteriormente: los propietarios de inmuebles y los trabajadores independientes.

![User Persona 1](https://github.com/1ASI0732-Grupo-2/report/blob/develop/assets/img/Chapter-I/Propietario%20de%20inmueble.png)

![User Persona 2](https://github.com/1ASI0732-Grupo-2/report/blob/develop/assets/img/Chapter-I/Trabajador%20independiente%20_%20freelancer.png)

#### 2.3.2. User Task Matrix

Estamos considerando los segmentos objetivos "Propietario de Inmueble" y "Trabajador independiente" como fueron definidos anteriormente como User Persona

|                                                    | **Propietario de Inmueble** |              | **Trabajador independiente** |              |
| -------------------------------------------------- | --------------------------- | ------------ | ---------------------------- | ------------ |
| Tarea                                              | Importancia                 | Frecuencia   | Importancia                  | Frecuencia   |
| Ofrecer su local                                   | 🔴 Alta                     | 🔴 Frecuente | ❌ N/A                       | ❌ N/A       |
| Buscar espacios de trabajo                         | ❌ N/A                      | ❌ N/A       | 🔴 Alta                      | 🔴 Frecuente |
| Comparar entre las opciones de espacios de trabajo | 🟡 Media                    | 🔵 Rara      | 🔴 Alta                      | 🔴 Frecuente |
| Contactarse el trabajador con el propietario       | 🔴 Alta                     | 🟡 Ocasional | 🔴 Alta                      | 🟡 Ocasional |
| Acordar precio y forma de pago                     | 🔴 Alta                     | 🟡 Ocasional | 🔴 Alta                      | 🟡 Ocasional |
| Observar situación final del local                 | 🟡 Media                    | 🟡 Ocasional | 🟡 Media                     | 🟡 Ocasional |
| Recomendar la experiencia                          | 🔵 Baja                     | 🔵 Rara      | 🟡 Media                     | 🟡 Ocasional |

### Leyenda:

Importancia
🔴 Alta
🟡 Media
🔵 Baja

Frecuencia
🔴 Frecuente
🟡 Ocasional
🔵 Rara

❌ N/A = No aplica para este usuario

Entre las tareas encontradas, la que ambos User Persona coinciden en que es importante y frecuente son tanto el contactarse mutuamente como el acordar precio y forma de pago, se debe a que ambos buscan que el préstamo del servicio se concrete y bajo condiciones favorables para ambos. Además, cada User Persona tiene su tarea particular: para el propietario es importante ofrecer su local y para el freelancer es importante buscar espacios de trabajo. Por último tenemos un tarea particular frecuente para el freelancer la cual es comparar diferentes ofertas de espacios de trabajo para ver lo que más se ajuste a su presupuesto y cuente con las características necesarias. Mientras que para el propietario, esto lo hace rara vez cuando desee ver qué precios ponen sus competidores.

#### 2.3.3. User Journey Mapping

<p align="center">
  <img src="https://github.com/1ASI0732-Grupo-2/report/blob/develop/assets/img/Chapter-I/Customer Journey Map Brainstorm.png" alt="Customer Journey Map Brainstorm.png" />
</p>

#### 2.3.4. Empathy Mapping

<p align="center">
  <img src="https://github.com/1ASI0732-Grupo-2/report/blob/develop/assets/img/Chapter-I/Empathy Map Brainstorm.png" alt="Empathy Map Brainstorm.png" />
</p>

#### 2.3.5. As-is Scenario Mapping

**Freelancers**
![As-Is-Freelancer](https://github.com/1ASI0732-Grupo-2/report/blob/develop/assets/img/Chapter-I/as-is-freelancer.jpg)

**Propietarios de Inmuebles**
![As-Is-Propietario](https://github.com/1ASI0732-Grupo-2/report/blob/develop/assets/img/Chapter-I/as-is-propietario.jpg)

### 2.4. Ubiquitous Language

| Término      | Definición                                                                                                  |
| ------------ | ----------------------------------------------------------------------------------------------------------- |
| Workspace    | Un espacio físico disponible para alquiler como sitio de trabajo.                                           |
| Coworking    | Una modalidad de trabajo donde personas de distintas empresas comparten un mismo workspace.                 |
| Host         | La persona que ofrece su propiedad en alquiler.                                                             |
| Renter       | La persona que alquila este espacio.                                                                        |
| Booking      | Confirmación de un alquiler hecho por un Renter de un Workspace por un periodo de tiempo.                   |
| Rate         | La tarifa por día o por semana para alquilar el Workspace.                                                  |
| Amenities    | Adicionales que ofrezca el host como parte del Workspace. Por ejemplo, WiFi, café, aire acondicionado, etc. |
| Listing      | La publicación de un Workspace disponible incluyendo detalles como ubicación, fotos, Rates y Amenities.     |
| Check-in     | El momento en que comienza el uso del Workspace.                                                            |
| Check-out    | El momento en el que finaliza el uso del Workspace.                                                         |
| Cancellation | La anulación de una reserva, por parte de Host o Renter.                                                    |
| Contract     | El contrato que se realiza entre Renter y Host.                                                             |
| Review       | Las reseñas dadas del Renter al Host después del uso del Workspace, visibles para otros usuarios.           |

---

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping

# To-Be Scenario Mapping

| Actor       | Acción Deseada                               | Resultado Esperado                                               | Valor para el Negocio                         |
| ----------- | -------------------------------------------- | ---------------------------------------------------------------- | --------------------------------------------- |
| Propietario | Responde mensajes de freelancers             | Coordinan pago                                                   | Mejor experiencia de usuario                  |
| Freelancer  | Compara precios y lugares                    | Obtiene una mejor elección                                       | Ese cliente seguirá usando nuestro aplicativo |
| Propietario | Obtiene fotos de cómo están dejando el local | Siente seguridad del freelancer al que alquiló                   | Mayor confianza en el aplicativo              |
| Freelancer  | Lee reseñas del local y de su propietario    | Tiene la confianza de que será una experiencia sin incomodidades | Usuarios más confiados en volver a usarlo     |

### 3.2. User Stories

| User Story ID | Título                                                     | Descripción                                                                                                                                                                                    | Criterios de Aceptación                                                                                                                                                                                                                                                                                            | Epic ID |
| ------------- | ---------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------- |
| US-01         | Ubicacion de inmuebles                                     | Como freelancer, quiero encontrar la ubicacion de los inmuebles por localizacion para encontrar los lugares mas cercanos o convenientes                                                        | **Escenario 1**: Encontrar inmueble por ubicación <br><br> Dado que el freelancer busca un inmueble por ubicación <br><br> Entonces se muestra los inmuebles mas cercanos en la ubicacion <br><br>                                                                                                                 | EP-01   |
| US-02         | Disponibilidad de inmuebles                                | Como freelancer, quiero saber la disponibilidad actual del inmueble para hacer una eleccion correcta del tiempo que necesito el local                                                          | **Escenario 1**: Ver disponibilidad <br><br> Dado que el freelancer quiere ver la disponibilidad actual del inmueble, <br><br> Entonces se muestra la disponibilidad del inmueble para el freelancer                                                                                                               | EP-01   |
| US-03         | Filtros de busqueda                                        | Como freelancer quiero hacer una busqueda personalizada como cantidad de aforo, tipo de espacio y servicios disponibles para que pueda encontrar la mejor opcion para mi o mi equipo.          | **Escenario 1**: Busqueda de inmueble <br><br> Dado que el freelancer busca un tipo de espacio especifico <br><br> Entonces se muestran todas las opciones de los lugares con esas especificaciones                                                                                                                | EP-03   |
| US-04         | Valoraciones y opiniones                                   | Como freelancer quiero ver las valoraciones y opiniones de inmuebles sobre los espacios de trabajo para tomar una decisión informada.                                                          | **Escenario 1**: Review de un inmueble <br><br> Dado que el freelancer puede ver las valoraciones de otros usuarios de inmuebles. <br><br> Entonces puede tomar una mejor decision para encontrar el lugar adecuado                                                                                                | EP-02   |
| US-05         | Feeback constructivo                                       | Como propietario de inmueble, quiero recibir las opiniones o un feedback para reconocer posibles nuevas mejoras para el espacio de trabajo                                                     | **Escenario 1**: Recibe feedback <br><br> Dado que el propietario recibe recibir opiniones de los freelancers sobre su experiencia en el inmueble <br><br> Entonces puede hallar formas de mejorar su experiencia para futuros equipos o freelancers.                                                              | EP-04   |
| US-06         | Perfiles de inmuebles                                      | Como freelancer quiero encontrar la suficiente informacion para poder hacer una decision correcta detallada sobre cada inmueble, incluyendo fotos, ubicación, tarifas y servicios disponibles. | **Escenario 1**: Encontrar publicacion <br><br> Dado que el freelancer encuentra detalles como fotos, ubicación, tarifas y servicios disponibles <br><br> Entonces tendra una decision mas informada y adecuada para sus necesidades                                                                               | EP-03   |
| US-07         | Sistema de pagos seguros                                   | Como freelancer quiero tener la certeza de que la aplicacion web tenga un sistema de pago seguro                                                                                               | **Escenario 1**: Pago para la renta <br><br> Dado que el freelancer quiere pagar un mes adicional de renta <br><br> Entonces podra poder realizar el pago de manera segura a través de la aplicación                                                                                                               | EP-05   |
| US-08         | Sistema de devolucion                                      | Como freelancer, quiero tener la posibilidad de tener una devolucion de mi dinero si cancelo una reserva realizada antes del inicio de esta misma.                                             | **Escenario 1**: Devolucion de dinero dias antes de su uso registrado <br><br> Dado que el freelancer cancelo su reserva dias antes de su uso <br><br> Entonces el dinero que pago sera devuelto en los siguientes 15 dias.                                                                                        | EP-05   |
| US-09         | Publicacion de inmueble                                    | Como propietario de inmueble, quiero tener la facilidad de publicar un inmueble de manera sencilla y atractiva para que los freelancers lo encuentren llamativo                                | **Escenario 1**: Publicacion de inmueble <br><br> Dado que el propietario quiere publicar su inmueble con todos los datos necesarios <br><br> Entonces podra registrar toda la información necesaria, incluyendo fotos, descripción, ubicación, tarifas y servicios disponibles                                    | EP-04   |
| US-10         | Modificacion de inmueble                                   | Como propietario de inmueble quiero que se me permita actualizar la información de la publicación de manera sencilla y rápida para no arruinar la experiencia de freelancers.                  | **Escenario 1**: Modificacion de inmuebles <br><br> Dado que el propietario ha hecho remodelaciones en el lugar <br><br> Entonces podra modificar la informacion necesaria y de forma facil en la aplicacion web                                                                                                   | EP-04   |
| US-11         | Lugar libre de distracciones y ruidos                      | Como freelancer quiero estar en un lugar libre de distracciones y ruidos para obtener la mayor concentración y sacar provecho a mi tiempo de trabajo                                           | **Escenario 1**: Lugar libre de distracciones y ruidos<br><br>Dado que el freelancer desea aprovechar su tiempo y comodididad en el espacio alquilado<br><br>Entonces el local alquilado no tendrá ruidos molestos y si los tiene puede dejar una reseña sobre eso                                                 | EP-04   |
| US-12         | Precio altos                                               | Como freelancer, quiero comparar precios entre diferentes locales, para evitar precios y altos                                                                                                 | **Escenario 1**: Precios altos<br><br>Dado que el propietario coloca su precio que espera que le paguen<br><br> Entonces el usuario tendrá la posibilidad de comparar diferentes opciones de lugares, así obtener la que mejor le acomode                                                                          | EP-04   |
| US-13         | Alta demanda, la disponibilidad no abastece                | Como freelancer quiero saber la disponibilidad de los inmuebles, ya que hay horas de mayor necesidad                                                                                           | **Escenario 1**: Alta demanda, la disponibilidad no abastece<br><br>Dado que existe una demanda alta demanda de espacios de coworking en determinadas horas o dias<br><br> Entonces el aplicativo mostrará un cuadro donde se vea los horarios tomados y los horarios disponibles de los espacios                  | EP-04   |
| US-14         | No traigan personas externas                               | Como propietario quiero que el usuario no lleve a personas externas a mi local para que haya un uso correcto de mi local y siga las reglas                                                     | **Escenario 1**: No traigan a personas externas<br><br>Dado que el propietario no desea personas externas pues pueden causar desoren innecesario<br><br>Entonces se le reiteraría al freelancer esta reglas, o en caso contrario se le dejaría una reseña de mala conducta                                         | EP-04   |
| US-15         | Impuntualidad en pagos                                     | Como propietario quiero tener la certeza de que el usuario va a pagarme en el plazo establecido para evitar aquellos que son impuntuales                                                       | **Escenario 1**: Impuntualidad en pagos<br><br>Dado que el propietario quiere tener a tiempo el pago<br><br>Entonces se le reiteraría al freelancer esta reglas, o en caso contrario se le dejaría una reseña de impuntualidad                                                                                     | EP-04   |
| US-16         | Buena iluminación natural                                  | Como freelancer, quiero un ambiente con buena iluminación para que mejore mi rendimiento                                                                                                       | **Escenario 1**: Buena iluminación natural<br><br>Dado que el ambiente influye en el trabajo del freelancer<br><br>Entonces va a buscar un espacio que cumpla con esta característica                                                                                                                              | EP-04   |
| US-17         | Buena conexión a internet                                  | Como freelancer, quiero un ambiente con buena conexión a internet para que mejore mi rendimiento                                                                                               | **Escenario 1**: Buena conexión a internet<br><br>Dado que el freelancer quiere un tiempo de trabajo sin que el internet sea problema<br><br>Entonces el propietario va a poner claro la intensidad de los servicios telefónicas en ese local, o en lo contrario instalar wifi y ponerlo como caracteristica clave | EP-04   |
| US-18         | Tolerancia y respeto entre personas                        | Como freelancer, quiero que exista buena convivencia entre todos los que estemos en el coworking para sentirnos cómodos en el grupo                                                            | **Escenario 1**: Tolerancia y respeto entre personas<br><br>Dado que los freelancer compartirán espacios<br><br>Entonces esperan que todos estén comprometidos con cumplir normas básicas de convivencia                                                                                                           | EP-04   |
| US-19         | Fotos del estado del lugar al llegar y antes de entregarlo | Como propietario quiero que el freelancer mande una foto de cómo encontró el lugar y cómo lo está dejando para evitar malos entendidos                                                         | **Escenario 1**: Fotos del estado del lugar al llegar y al entregarlo<br><br>Dado que el propietario quiero tener la seguridad de que estén cuidadno su local<br><br>Entonces el freelancer va a mandar evidencia mediante fotos d cómo lo encontró y cómo lo está dejando                                         | EP-04   |
| US-20         | Un mapa para visualizar lugares                            | Como freelancer quiero un mapa para navegar a través de este y así elegir el distrito que más me convenga                                                                                      | **Escenario 1**: Mapa para visualizar lugares<br><br>Dado que el freelancer quiere hacer una búsqueda por distrito<br><br>Entonces implementar un mapa le va a facilitar la búsqueda porque asi puede ubicar mejor los puntos                                                                                      | EP-03   |
| US-21         | Amplitud del lugar                                         | Como freelancer quiero saber la amplitud del local a alquiler para ver si se acomodará a mis funciones a desempeñar                                                                            | **Escenario 1**: Amplitud del lugar<br><br>Dado que el freelancer tiene diferentes necesidades para sus actividades<br><br>Entonces el propietario debe especificar el tamaño, también se puede agregar un filtro de búsqueda por amplitud del local                                                               | EP-04   |
| US-22         | Fotos reales                                               | Como freelancer quiero ver imágenes de cómo se ve el local que voy a rentar para saber que es de mi agrado                                                                                     | **Escenario 1**: Fotos reales<br><br>Dado que el freelancer quiere ver de primera mano cómo es el local que va a alquilar<br><br>Entonces el propietario debe colocar fotos del local y actualizarlas periódicamente                                                                                               | EP-03   |
| US-23         | Servicios como estacionamiento, cafetería, entre otros     | Como freelancer quiero saber si el espacio de coworking cuenta con ciertos servicios para tomar una decisión en base a eso                                                                     | **Escenario 1**: Servicios como estacionamiento, cafetería, entre otros<br><br>Dado que el freelancer quiere tener algún servicio<br><br>Entonces habrá un filtro de búsqueda de los locales que sí cuenten con dicho servicio                                                                                     | EP-04   |
| US-24         | Cobro por hora, en vez de por día                          | Como propietario de inmueble quiero opciones en los horarios de alquiler de mi local para ofrecer opciones más flexibles                                                                       | **Escenario 1**: Cobro por hora, en vez de por día<br><br>Dado que el propietario quiere horarios y pagos más flexibles<br><br>Entonces se implementa la opción de alquilar el local por tiempos más pequeños y flexibles                                                                                          | EP-04   |
| US-25         | Sistema fácil de entender e intuitivo                      | Como propietario de inmuebles, quiero que esta propuesta de aplicación se fácil de entender para poder usarla a largo plazo                                                                    | **Escenario 1**: Sistema fácil de entender e intuitivo<br><br>Dado que el propietario tiene conocimientos básicos del uso de plataformas<br><br>Entonces se le brindará una plataforma que sea comprensible o algún tutorial interactivo para que se adapte                                                        | EP-01   |
| US-26         | Reserva rápida                                             | Como freelancer quiero que la aplicación tenga una carga rápida y esté actualizada para tener informacion precisa                                                                              | **Escenario 1**: Reserva rápida<br><br>Dado que el usuario quiere que su reserva se realice lo más pronto posible<br><br>Entonces la plataforma deberá procesar la solicitud de la manera más eficiente                                                                                                            | EP-02   |
| US-27         | Chat directo propietario y cliente                         | Como propietario quiero contactarme directamente con el usuario interesado para tener la certeza de que se concrete el acuerdo                                                                 | **Escenario 1**: Chat directo propietario y cliente<br><br>Dado que el propietario quiere tener una conversacion directa con quien va a alquilar su local<br><br>Entonces la plataforma deberá tener un chat directo entre propietarios y clientes                                                                 | EP-01   |
| US-28         | Calendario para ver la disponibilidad del espacio          | Como freelancer quiero ver en formato de calendario para navegar mejor a través de los días disponibles del inmueble                                                                           | **Escenario 1**: Calendario para ver la disponibilidad del espacio<br><br>Dado que el freelancer quiere tener un calendario para facilitar su búsqueda<br><br>Entonces se implemntará uno en la aplataforma al contratar el local                                                                                  | EP-01   |
| US-29         | Sistema de reseñas pra ambas partes                        | Como propietario, quiero saber opiniones de otros propietarios para estar más convencidos de alquilar mi local a ciertos usuarios                                                              | **Escenario 1**: Sistema de reseñas para ambas partes<br><br>Dado que tanto el freeelancer como el propietario quieren saber más contexto antes de hacer la contrata<br><br>Entonces la plataforma mostrará las reseñas                                                                                            | EP-03   |
| US-30         | Usuarios verficiados con LinkedIn o DNI                    | Como propietario quiero una forma de verificar la informacion del freelancer para estar informado de que su trabajo es serio y va con mis criterios                                            | **Escenario 1**: Usuarios verficiados con LinkedIn o DNI<br><br>DAdo que el porpietario quiere tener la seguridad de a quien está alquilando<br><br>Entonces la plataforma promoverá a sus usuarios a verificarse                                                                                                  | EP-05   |
| US-31         | Navegación por el landing page                             | Como usuario quiero explorar fácilmente el landing page para acceder a la información clave.                                                                                                   | **Escenario 1**: Acceso intuitivo al landing page<br><br> Dado que el usuario necesita navegar con facilidad<br><br> Entonces la página principal estará estructurada de forma simple y clara.                                                                                                                     | EP-05   |
| US-32         | Ver información del startup                                | Como usuario quiero conocer más sobre el proyecto para tomar una decisión informada.                                                                                                           | **Escenario 1**: Información sobre el startup<br><br> Dado que los usuarios desean más detalles<br><br> Entonces se incluirá una sección con datos relevantes de la startup.                                                                                                                                       | EP-05   |
| US-33         | Conocer los servicios                                      | Como usuario quiero revisar los servicios ofrecidos para decidir cuáles se ajustan a mis necesidades.                                                                                          | **Escenario 1**: Exploración de servicios<br><br> Dado que los usuarios necesitan opciones claras<br><br> Entonces la plataforma mostrará servicios categorizados.                                                                                                                                                 | EP-05   |
| US-34         | Contactar al equipo de soporte                             | Como usuario quiero una manera rápida de contactar al equipo para resolver dudas o problemas.                                                                                                  | **Escenario 1**: Contacto rápido con soporte<br><br> Dado que los usuarios pueden enfrentar problemas<br><br> Entonces se incluirá un botón de contacto directo en la interfaz.                                                                                                                                    | EP-05   |
| US-35         | Cambiar lenguaje entre Español e Inglés                    | Como usuario quiero la opción de cambiar el idioma de la plataforma para utilizar el idioma con el que me sienta más cómodo.                                                                   | **Escenario 1**: Cambio de idioma<br><br> Dado que algunos usuarios prefieren otro idioma<br><br> Entonces se incluirá un selector de idioma en la plataforma.                                                                                                                                                     | EP-05   |
| US-36         | Mostrar testimonios y casos de éxito                       | Como usuario quiero leer experiencias reales para ganar confianza en el proyecto.                                                                                                              | **Escenario 1**: Testimonios visibles<br><br> Dado que los usuarios buscan referencias confiables<br><br> Entonces se incluirán testimonios destacados en una sección dedicada.                                                                                                                                    | EP-05   |
| US-37         | Descargar información del proyecto                         | Como usuario quiero una opción para descargar un folleto informativo sobre el proyecto en formato digital.                                                                                     | **Escenario 1**: Folleto descargable<br><br> Dado que los usuarios prefieren tener información detallada<br><br> Entonces se incluirá una opción de descarga en la plataforma.                                                                                                                                     | EP-05   |
| US-38         | Registro de Propietarios                                   | Como propietario, quiero registrar mis datos para poder publicar oficinas y administrar mis espacios                                                                                           | **Escenario 1**: Registro exitoso de propietario <br><br> Dado que un nuevo propietario ingresa sus datos <br><br> Cuando envía el formulario <br><br> Entonces el sistema guarda los datos y retorna confirmación                                                                                                 | EP-02   |
| US-39         | Publicación de Oficinas                                    | Como propietario, quiero publicar detalles de mis oficinas disponibles para que los freelancers puedan verlas y reservarlas                                                                    | **Escenario 1**: Publicar una nueva oficina <br><br> Dado que el propietario tiene acceso al panel de oficinas <br><br> Cuando ingresa la información requerida <br><br> Entonces se publica la oficina con disponibilidad                                                                                         | EP-02   |
| US-40         | Mensajes entre usuarios                                    | Como usuario, quiero enviar y recibir mensajes para poder comunicarme con el propietario o el freelancer relacionado a una oficina                                                             | **Escenario 1**: Enviar un mensaje <br><br> Dado que un usuario accede a la conversación <br><br> Cuando redacta y envía un mensaje <br><br> Entonces el mensaje es visible para el receptor en tiempo real                                                                                                        | EP-02   |
| US-41         | Búsqueda avanzada de oficinas                              | Como freelancer, quiero filtrar oficinas por servicios, precio, capacidad y ubicación para encontrar la opción ideal                                                                           | **Escenario 1**: Búsqueda con filtros <br><br> Dado que el usuario ingresa criterios de búsqueda <br><br> Cuando ejecuta la búsqueda <br><br> Entonces el sistema retorna solo las oficinas que cumplen con los filtros seleccionados                                                                              | EP-02   |
| US-42         | Calificar experiencia de oficina                           | Como freelancer, quiero calificar la oficina y al propietario para ayudar a otros usuarios a tomar decisiones informadas                                                                       | **Escenario 1**: Enviar calificación <br><br> Dado que un freelancer finalizó su estancia <br><br> Cuando envía una calificación y comentario <br><br> Entonces esta se guarda y se refleja en el perfil del propietario y de la oficina                                                                           | EP-02   |

### Epics

| Epic ID | Título                      | Descripción                                                                                                                                                                 |
| ------- | --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP-01   | Desarrollo del Landing Page | Esta enfocado en la creacion de la pagina web inicial que se presentará al consumidor para luego ser redirigido a la aplicacion web                                         |
| EP-02   | Desarrollo del Backend      | Se enfoca en la lógica de negocio, estructuras de datos, endpoints y funcionalidades que permitirán las operaciones y servicios que la aplicacion web ofrece                |
| EP-03   | Desarrollo del Frontend     | Es enfocado en la interfaz de usuario, la experiencia del cliente y la implementación de las funcionalidades visuales que permitirán la interacción con la aplicación.      |
| EP-04   | Experiencia del desarrollo  | Esta enfocada en establecer las metas y la metodología de desarrollo, incluyendo las herramientas y procesos utilizados para asegurar la calidad y eficiencia del proyecto. |
| EP-05   | Seguridad de la aplicacion  | Esta enfocado en ofrecer un entorno seguro y confiable para los usuarios, garantizando la protección de datos y la privacidad en todas las transacciones.                   |

### 3.3. Impact Mapping

![ImpactMap](https://github.com/1ASI0732-Grupo-2/report/blob/develop/assets/img/Chapter-I/Plantilla%20de%20mapa%20de%20impacto.jpg)

### 3.4. Product Backlog

| ID  | Historia de Usuario                                                                                                                                | Prioridad |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| 1   | Como freelancer, quiero encontrar la ubicacion de los inmuebles por localizacion para encontrar los lugares mas cercanos o convenientes            | Alta      |
| 2   | Como freelancer, quiero saber la disponibilidad actual del inmueble para hacer una eleccion correcta del tiempo que necesito el local              | Alta      |
| 8   | Como freelancer, quiero tener la posibilidad de tener una devolucion de mi dinero si cancelo una reserva realizada antes del inicio de esta misma. | Media     |
| 7   | Como freelancer quiero tener la certeza de que la aplicacion web tenga un sistema de pago seguro                                                   | Alta      |

---

# Capítulo 4

## 4.1 Design Concepts, ViewPoints & ER Diagrams
### 4.1.1 Principles Statements
### 4.1.2 Approaches Statements Architectural Styles & Patterns
### 4.1.3 Context Diagram
### 4.1.4 Approach driven ViewPoints Diagrams
### 4.1.5 Relational/Non Relational Database Diagram
### 4.1.6 Design Patterns
### 4.1.7 Tactics

## 4.2 Architectural Drivers
### 4.1.8 Design Purpose
### 4.1.9 Primary Functionality (Primary User Stories)
### 4.1.10 Quality Attribute Scenarios
### 4.1.11 Constraints
### 4.1.12 Architectural Concerns

## 4.3 ADD Iterations
### 4.2.1 Iteration 1: Workstation Office Recommendation

#### 4.2.1.1 Architectural Design Backlog 1

Para esta primera iteracion del diseño de Arquitectura de Workstation, el equipo se centrará en enfocar las historias de usuario en el desarrollo de las recomendaciones de las oficinas dependiendo de su rating, ubicacion, necesidades o preferencias del usuario con un efoque funcional y escalable. Los principales atributos que se pudieron identificar fueron:

- Modificabilidad:
Para este punto lo que se busca es permitir ajustes o modificaciones en los espacios sin impactar el resto del sistema.
- Usabilidad:
La experiencia durante la busqueda en el contexto de Searching debe ser intuitiva y clara. El UI responsive, filtros dinamicos y catching eficiente
- Seguridad:
Para la seguridad se requiere una autenticacion con OAuth 2.0 por roles y proteccion contra inyeccion de consultas
- Interoperabilidad:
Por ultimo, la logica de recomendaciones se debe poder utilizar datos de diferentes fuentes, para ello el uso de microservicios.

**Historias de Usuario**

- Como **usuario**, quiero ver oficinas recomendadas con capacidad adecuada y alto rating para asegurar comodidad de mi equipo.
- Como **Propietario de oficina**, quiero que mi espacio sea recomendado a usuarios con necesidades compatibles para aumentar la tasa de reservas.
- Como **usuario**, quiero ver oficinas con detalles claros (ubicación, capacidad, costo y servicios) para comparar opciones fácilmente.
- Como **usuario**, quiero que el sistema me recomiende oficinas cercanas con buen rating y que se ajusten a mis preferencias, para ahorrar tiempo al elegir
- Como **usuario**, quiero ver el historial de mensajes con cada propietario, para tener contexto antes de tomar decisiones.
- Como **propietario de oficina**, quiero asegurar que el sistema de mensajería filtre spam o mensajes inapropiados.

**Tareas iniciales del backlog de la arquitectura**

| **Contexto**      | **Tarea**                                                                                      | **Descripción** |
|--------------------|------------------------------------------------------------------------------------------------|-----------------|
| **Usuarios**       | Diseñar entidad `User` con campos de perfil y preferencias                                     | Modelo con datos básicos (nombre, email, rol, preferencias de búsqueda). |
|                    | Implementar autenticación básica con JWT                                                       | Seguridad inicial para proteger endpoints. |
|                    | Exponer endpoint `GET /users/{id}/preferences`                                                 | Permitir que el motor de recomendaciones acceda a las preferencias. |
| **Property Owner** | Definir entidad `PropertyOwner`                                                                | Modelo con datos del propietario. |
|                    | Implementar CRUD de oficinas ligadas al propietario (`/owners/{id}/offices`)                   | Crear, editar y eliminar oficinas. |
|                    | Validar disponibilidad y capacidad en la creación de oficinas                                  | Evitar inconsistencias en reservas futuras. |
| **Offices**        | Modelar entidad `Office` con ubicación, capacidad, costo y servicios                           | Incluyendo soporte geoespacial. |
|                    | Crear endpoint básico `/offices` con filtros iniciales                                         | Filtrar por ubicación, capacidad y servicios. |
| **Rating**         | Crear entidad `Rating` (userId, officeId, score, comment)                                      | Asociar puntuaciones y comentarios. |
|                    | Implementar endpoint `POST /offices/{id}/ratings`                                              | Permitir registrar valoraciones. |
|                    | Implementar cálculo de promedio y normalización de puntuaciones                                | Exponerlo en `/offices/{id}` y en recomendaciones. |
| **Search**         | Diseñar servicio `RecommendationService` extensible                                            | Permitir agregar criterios de búsqueda sin romper arquitectura. |
|                    | Implementar endpoint `GET /search/recommendations`                                             | Recibir filtros y devolver resultados. |
|                    | Integrar Redis para caching de resultados frecuentes                                           | Mejorar performance de búsquedas comunes. |
| **Messaging**      | Modelar entidad `Message` (senderId, receiverId, officeId?, body, timestamp)                   | Permitir registrar comunicaciones. |
|                    | Implementar endpoint `POST /messages`                                                          | Enviar mensajes entre usuario ↔ propietario. |
|                    | Implementar endpoint `GET /messages/conversation/{userId}/{ownerId}`                           | Recuperar historial de conversación. |
|                    | Integrar notificaciones en tiempo real (WebSockets / SignalR / STOMP)                          | Recibir mensajes instantáneamente. |
|                    | Diseñar moderación inicial de contenido (spam/inapropiado)                                     | Garantizar seguridad y confianza en la mensajería. |


#### 4.2.1.2 Establish Iteration Goal by Selecting Drivers

En este punto, definiremos los Drivers necesarios para establecer la meta de esta iteración y de las siguientes. Asimismo, estas metas estarán alineadas a los atributos anteriormente mencionados para poder cumplir aquellos atributos de calidad y proporcionar un producto que cumpla con los estándares establecidos por el equipo.

**Meta de Modificabilidad**  
Diseñar la arquitectura del motor de recomendaciones de manera modular, permitiendo incorporar fácilmente nuevos criterios de recomendación sin necesidad de reestructurar el sistema completo.

**Meta de Usabilidad**  
Proporcionar una interfaz de búsqueda simple e intuitiva que permita a los usuarios encontrar oficinas basadas en ubicación, rating y servicios clave, ofreciendo resultados claros y ordenados que faciliten la toma de decisiones.

**Meta de Seguridad**  
Implementar un mecanismo básico de autenticación y autorización con JWT y OAuth 2.0, asegurando que solo usuarios registrados puedan acceder a funcionalidades sensibles como recomendaciones personalizadas, mensajería y valoraciones.

**Meta de Interoperabilidad**  
Definir APIs REST estandarizadas para los contextos de Usuarios, Oficinas, Ratings y Mensajería, permitiendo la integración futura con servicios externos (ej. pasarelas de pago, proveedores de geolocalización, o plataformas de terceros).

**Objetivo de la Iteración 1**  
Construir un MVP funcional que permita a los usuarios autenticados buscar y recibir recomendaciones de oficinas basadas en ubicación y rating, con capacidad de aplicar filtros iniciales (capacidad, servicios), registrar valoraciones y enviar mensajes básicos a propietarios. Esto sentará la base técnica y funcional para escalar el producto en siguientes iteraciones.

#### 4.2.1.3 Choose One or More Elements of the System to Refine

Luego de haber revisado y establecido los Drivers para nuestra solución, se eligió uno de estos con el fin de hacer un refinamiento. Este elemento es: el motor de recomendaciones (Search Context).

**Razón de la elección**  
El motor de recomendaciones es el núcleo funcional de la primera iteración y el principal diferenciador competitivo de la plataforma WorkStation. Refinarlo desde el inicio permite:

- **Alineación con los Drivers**:  
  - *Modificabilidad*: diseñar la lógica de recomendaciones como un servicio modular y extensible.  
  - *Usabilidad*: garantizar que los usuarios reciban resultados claros, ordenados y relevantes.  
  - *Seguridad*: restringir recomendaciones personalizadas solo a usuarios autenticados.  
  - *Interoperabilidad*: exponer las recomendaciones mediante un endpoint REST estandarizado que pueda integrarse con otros módulos o servicios externos en el futuro.

- **Impacto en la experiencia del usuario**: si las recomendaciones no son rápidas, precisas o fáciles de entender, el valor de la plataforma disminuye drásticamente.

- **Dependencia de otros contextos**: el motor requiere datos de *Usuarios* (preferencias), *Offices* (información de espacios) y *Rating* (calidad de oficinas), lo que lo convierte en un punto central que asegura la coherencia e integración inicial entre los bounded contexts.

Por estas razones, refinar el **motor de recomendaciones** garantiza que la primera iteración entregue valor tangible y escalable, sentando la base para las funcionalidades futuras.

#### 4.2.1.4 Choose One or More Design Concepts That Satisfy the Selected Drivers


#### 4.2.1.5 Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces


#### 4.2.1.6 Sketch Views (C4 & UML) and Record Design Decisions


#### 4.2.1.7 Analysis of Current Design and Review Iteration Goal (Kanban Board)





## Final

### Avance de Conclusiones, Bibliografía y Anexos (links)

### Conclusión TB1:

WorkStation llega a resolver un problema que todo freelancer o dueño de coworking conoce demasiado bien: la fragmentación caótica de la oferta y la demanda. Hoy, conseguir un espacio de trabajo es un vía crucis entre mensajes en WhatsApp, consultas en grupos de Facebook o páginas web que nunca actualizan la disponibilidad. Del otro lado, los propietarios lidian con reservas poco serias, pagos informales y un control limitado sobre lo que pasa en sus espacios. Esa desconexión hace perder tiempo, clientes y, sobre todo, dinero.

La propuesta es simple pero potente: un marketplace centralizado que no necesita alquilar ni operar oficinas propias, sino conectar a ambas partes de manera transparente y eficiente. Para los usuarios, WorkStation ofrece comodidad y confianza: búsqueda con filtros claros (precio, ubicación, servicios), disponibilidad actualizada en vivo y pagos seguros desde un solo lugar. Para los dueños de coworking, la app representa un tablero de control que incluye calendario, reglas visibles para inquilinos, reseñas verificadas y menos carga administrativa. En resumen, cada clic suma productividad y menos dolores de cabeza.

La magia está en convertir interacciones dispersas y poco confiables en un flujo digital directo y fluido: encontrar, comparar, reservar y pagar en minutos. Pasamos de la incertidumbre del clásico “¿hola, sigue disponible?” a una experiencia estandarizada de “reservado en 3 clics”, donde cada parte sabe exactamente qué esperar. Eso no solo eleva la satisfacción del usuario, también genera más ocupación y confianza para los hosts, logrando que el mercado del coworking en ciudades como Lima tenga por fin una solución a la altura del nuevo mundo laboral.
