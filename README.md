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

| **Member**               | **Code**   |
| ------------------------ | ---------- |
| Rodrigo Liberato Saldana | U202215623 |
| Henry Kevin Diaz Gutierrez | U201819674 |
| Diego Sebastián Zúñiga Murillo | U202310636 |
| Braulio Rodrigo Torrejon Navarro | U201711828  |
|                          |            |

</div>

<p align="center"><strong>Septiembre 2025</strong></p>

# Registro de Versiones del Informe

# Project Report Collaboration Insights

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

- [Avance de Conclusiones, Bibliografía y Anexos (links)](#avance-de-conclusiones-bibliografía-y-anexos-links)

## Capítulo I: Introducción

### 1.1. Start-up Profile

#### 1.1.1. Descripción de la Startup

WorkStation es una aplicación web innovadora diseñada para optimizar la reserva ágil y eficiente de espacios de trabajo en oficinas compartidas. Su misión es conectar a freelancers, profesionales remotos, startups y compañías de todo tamaño con espacios de coworking disponibles en su ciudad o en cualquier parte del mundo.

La plataforma permitirá a los usuarios explorar, comparar y reservar en tiempo real escritorios, salas de reuniones, oficinas privadas y otros recursos. Cada espacio ofrecerá información detallada sobre su ubicación, tarifas, horarios, disponibilidad, fotografías, servicios incluidos (como Wi-Fi, café, impresoras, entre otros) y valoraciones de la comunidad.

Considerando la flexibilidad y adaptabilidad como factores clave en el crecimiento de las startups y en la dinámica del trabajo independiente, WorkStation se presenta como una alternativa moderna frente a la rigidez de los contratos tradicionales, brindando una solución práctica, accesible y contemporánea para cubrir las necesidades de los equipos y profesionales de hoy.

#### 1.1.2. Perfiles de integrantes del equipo

| Foto                                                                                                                                                                                                                               | Alumno                   | Descripción                                                                                                                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Rodrigo](https://media.discordapp.net/attachments/766316535290789908/1414761032928464907/rodrigo.png?ex=68c0be63&is=68bf6ce3&hm=ff615cb9f2f6cd66256a62ab4857639fcf3cd26cacefcbd283c385287daf8c64&=&format=webp&quality=lossless) | Liberato Saldaña Rodrigo | Estudiante de Ingeniería de Software que planea enfocarse en Ciencia de Datos y Ciberseguridad. Planea dar apoyo activo al grupo y asumir el rol de líder para encaminar al equipo hacia el cumplimiento de sus metas. |
|  ![Diego](https://media.discordapp.net/attachments/1082800870334419014/1415786757659693106/69ed58d9-a022-48a1-86b3-b7fa8ae451bb.png?ex=68c479ab&is=68c3282b&hm=04b6e642e588c672e684388b42f293d845cd831a6eaf6e0c60d29f8af4bf103f&=&format=webp&quality=lossless&width=574&height=1022)                                                                                                                                                                                                                                  | Diego Sebastián Zúñiga Murillo |  Estudiante en el sexto ciclo de la carrera de Ingenieria de Software que busca expandir sus conocimientos en diversas tecnologías, soy una persona participativa y colaborativa y siempre me adapto rápido a las situaciones de cambio, estoy preparado para afrontar las adversidades que este trabajo signifca para mi y como grupo                                                                                                                                                |
|                                                                                                                                                                                                                                    |                          |                                                                                                                                                                                                                        |
|                                                                                                                                                                                                                                    |                          |                                                                                                                                                                                                                        |
|                                                                                                                                                                                                                                    |                          |                                                                                                                                                                                                                        |

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

---

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

#### 2.1.1. Análisis competitivo

#### 2.1.2. Estrategias y tácticas frente a competidores

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

#### 2.2.2. Registro de entrevistas

#### 2.2.3. Análisis de entrevistas

### 2.3. Needfinding

#### 2.3.1. User Personas

#### 2.3.2. User Task Matrix

#### 2.3.3. User Journey Mapping

#### 2.3.4. Empathy Mapping

#### 2.3.5. As-is Scenario Mapping

### 2.4. Ubiquitous Language

---

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping

## 🗺️ 3.1. To-Be Scenario Mapping

| Actor       | Acción Deseada                                                  | Resultado Esperado                                                | Valor para el Negocio                                  |
|-------------|------------------------------------------------------------------|--------------------------------------------------------------------|--------------------------------------------------------|
| Propietario | Responde mensajes de freelancers                                | Coordinan pago                                                     | Mejor experiencia de usuario                           |
| Propietario | Compara precios y lugares                                       | Hace una mejor elección                                            | Mejores usuarios usando nuestro aplicativo             |
| Propietario | Obtiene fotos de cómo están dejando el local                    | Siente seguridad del freelancer al que alquiló                     | Mejora la confianza en el aplicativo                   |
| Freelancer  | Obtiene las llaves del local y se lo da a su propietario        | Tiene la confianza de que este servicio se prestará sin incomodidades | Usuarios más confiados en volver a usarlo             |

---


### 3.2. User Stories

### 3.3. Impact Mapping

### 3.4. Product Backlog

---

## Final

### Avance de Conclusiones, Bibliografía y Anexos (links)
