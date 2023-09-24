# <center>Universidad Peruana de Ciencias Aplicadas</center>
<center> <img src="https://media.discordapp.net/attachments/1146639921830973516/1149598476179623966/descarga.jpg"></center>

## <center>Ingeniería de Software</center>
### <center>Aplicaciones Web - SI730 </center>
## Informe de TB1
- **Sección:** SW51
- **Docente:** Juan Carlos Tinoco Licas
- **Ciclo:** 2023-02
- **Nombre del grupo:** Team 4
- **Nombre de la Startup:** LoyalSlip

## Integrantes
| Alumno                           | Código     |
|----------------------------------|------------|
| Leonardo Paul López Huarcaya     | U202124304 |
| Sandro Fourfive Alarcon Rondon   | U202114140 |
| Louis Piero Alfaro Coveñas       | U20191b299 |
| José Carlos Isaac Ampudia Flores | U202112936 |
| Jean Pierre Morin Fuentes        | U202115348 |

## <center>Setiembre 2023</center>

<br><br>

## Registros de versiones del Informe

|   Version     |   Fecha   | Autor                   |   Descripción de la modificación|
|:-------------:|:---------:|:------------------------|:------------------------|
|1              |   28/08/2023    | Ampudia Flores          |- Implementó el diseño del figma tanto para desktop como para movil, además la codificacción de la Landing Page desplegable. |
|1              |   29/08/2023   | Alarcon Rondon          |- Implementó los diagramas en el modelo C4, como la configuracion de como se realizo el desarrollo del presente trabajo, en el cual se utilizó Github con el apoyo de Gitflow |
|1              |   30/08/2023        | Morin Fuentes           |- Implementó los Style Guidelines el cual sirvió para la elaboración del diseño del prototipo con la herramienta Figma. |
|1              |  06/09/2023  | Louis Alfaro Coveñas    |- Implementó el apartado del sistema de busquedas y navegación de nuestra website, del mismo modo los diagramas de clases con la base de datos. |
|1              |  08/09/2023 | Leonardo López Huarcaya |- Implementó el Sprint Planing 1, como el Sprint Backlog 1, no logró completar el Development Evidence for Sprint Review. |

<br>

Link del video y diapositiva: https://drive.google.com/drive/folders/1FBHclUB6UtwnrinxLWHTFOUb5ycSQL3-?usp=sharing 

# Índice

## 1. Capítulo I: Introducción

- [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3 Segmentos objetivo](#13-segmentos-objetivo)

## 2. Capítulo II: Requirements Elicitation & Analysis

- [2.1 Competidores](#21-competidores)
    - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3 Needfinding](#23-needfinding)
    - [2.3.1 User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4 Empathy Mapping](#234-empathy-mapping)
    - [2.3.5 As-is Scenario Mapping](#235-as-is-scenario-mapping)

## 3. Capítulo III: Requirements Specification

- [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2 User Stories](#32-user-stories)
- [3.3 Impact Mapping](#33-impact-mapping)
- [3.4 Product Backlog](#34-product-backlog)

## 4. Capítulo IV: Product Design

- [4.1 Style Guidelines](#41-style-guidelines)
    - [4.1.1 General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2 Web Style Guidelines](#412-web-style-guidelines)
- [4.2 Information Architecture](#42-information-architecture)
    - [4.2.1 Organization Systems](#421-organization-systems)
    - [4.2.2 Labeling Systems](#422-labeling-systems)
    - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4 Searching Systems](#424-searching-systems)
    - [4.2.5 Navigation Systems](#425-navigation-systems)
- [4.3 Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1 Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2 Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1 Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2 Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3 Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4 Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5 Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6 Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1 Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2 Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3 Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7 Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1 Class Diagrams](#471-class-diagrams)
    - [4.7.2 Class Dictionary](#472-class-dictionary)
- [4.8 Database Design](#48-database-design)
    - [4.8.1 Database Diagram](#481-database-diagram)

## 5. Capítulo V: Product Implementation, Validation & Deployment

- [5.1 Software Configuration Management](#51-software-configuration-management)
    - [5.1.1 Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2 Source Code Management](#512-source-code-management)
    - [5.1.3 Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4 Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2 Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1 Sprint n](#52x-sprint-n)
        - [5.2.1.1 Sprint Planning 1](#52x1-sprint-planning-n)
        - [5.2.1.2 Sprint Backlog 1](#52x2-sprint-backlog-n)
        - [5.2.1.3 Development Evidence for Sprint Review](#52x3-development-evidence-for-sprint-review)
        - [5.2.1.4 Testing Suite Evidence for Sprint Review](#52x4-testing-suite-evidence-for-sprint-review)
        - [5.2.1.5 Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)
        - [5.2.1.6 Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)
        - [5.2.1.7 Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)
        - [5.2.1.8 Team Collaboration Insights during Sprint](52x8-team-collaboration-insights-during-sprint)



<br>

# Student Outcome
<table align="center">
    <tr>
      <th>Criterio específico</th>
      <th>Acciones Realizadas</th>
      <th>Conclusiones</th>
    </tr>
    <tr>
          <td>Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.</td>
          <td><strong>Ampudia, José</strong><br>
          <strong>TB1:</strong><br>
          Asistió a todas las reuniones organizadas por el equipo de trabajo, brindando ideas innovadoras y soluciones para el desarrollo del proyecto.
          Realizó todas las tareas asignadas por el Team Leader del equipo, cumpliendo de manera óptima y respetando el tiempo de entrega.<br><br>
          - Colaboró con la implementación del Lean UX Assumptions e Hypothsys, como también en la implementación del diseño del prototipo del proyecto y la Landing Page desplegada, el cual se usó un repositorio de Github, con el uso de HTML, CSS y JavaScript.<br><br>
          <strong>Morin, Jean</strong><br>
          <strong>TB1:</strong><br>
          Asistió a todas las reuniones organizadas por el equipo de trabajo, aportando ideas claras para el desarrollo del proyecto. Realizó todas sus tareas encomendadas por el Team Leader cumpliendo a tiempo.<br><br>
          - Colaboró con la implementacion del Solution Profile, Lean UX Problem Statements, como tambien en el desarrollo del Needfinding, To-be Scenario Mapping, los Style Guidelines, el Team Collaboration Insights during Sprint y avance de conclusiones.<br><br>
          <strong>Alarcon, Sandro</strong><br>
          <strong>TB1:</strong><br>
          Asistió a todas las reuniones organizadas por el equipo de trabajo, aportando ideas claras para el desarrollo del proyecto. Realizó todas sus tareas encomendadas por el Team Leader cumpliendo a tiempo.<br><br>
          -Colaboró con la implementacion del Startup Profile, el análisis competitivo, el desarrollo de los diagramas DDD, como también el Software Configuration Management, especialmente en Software Development Environment Configuration y Source Code Management.<br><br>
          <strong>Alfaro, Louis</strong><br>
          <strong>TB1:</strong><br>
          Asistió parcialmente a reuniones claves organizadas por el equipo de trabajo, aportando parcialmente ideas para la solución del proyecto. No realizó sus tareas establecidas a tiempo, lo cual perjudicó de forma clara el avance óptimo del proyecto.<br><br>
          -Colaboró con la implementacion Lean UX Canvas, Segmento Objetivo, Registro de entrevistas, User Journey Mapping, Empathy Mapping, Product Backlog.<br><br>
          <strong>López, Leonardo</strong><br>
          <strong>TB1:</strong><br>
          Asistió parcialmente a reuniones claves organizadas por el equipo de trabajo, aportando parcialmente ideas para la solución del proyecto. No realizó sus tareas establecidas a tiempo, lo cual perjudicó de forma clara el avance óptimo del proyecto.<br><br>
          -Colaboró con la implementacion del Lean UX Problem Statements, As-is Scenario Mapping, User Stories, Sprint Planing 1, Sprint Backlog 1, no cumplió con el Development Evidence for Sprint Review.
        </td>
        <td><strong>TB1:</strong><br>
        Para la elaboración de nuestro proyecto, fue necesaria la comunicación en equipo, una de las herramientas claves fue Discord y WhatsApp, en el que se designó los temas para cada integrante del equipo.</td>
  </tr>
  <tr>
    <td>Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.</td>
    <td><strong>Ampudia, José</strong><br>
    <strong>TB1:</strong><br>
          Tiene conocimiento de varios lenguajes de programación, entre ellos está, HTML, CSS, JAVA SCRIPT, además, el manejo de base de datos, en el que incluye modelo relacional y no relacional.<br><br>
          <strong>Morin, Jean</strong><br>
          <strong>TB1</strong><br>
          Tiene conocimiento de varios lenguajes de programación, entre ellos está, HTML, CSS, JAVA SCRIPT, como también C++, python y otros.
          <br><br>
          <strong>Alarcon, Sandro</strong><br>
          <strong>TB1</strong><br>
          Tiene conocimiento de varios lenguajes de programación, entre ellos está, HTML, CSS, JAVA SCRIPT, el uso de Python e implementacion de algoritmos y manejo del modelo C4.
          <br><br>
          <strong>Alfaro, Louis</strong><br>
          <strong>TB1</strong><br>
          Tiene conocimiento de varios lenguajes de programación, entre ellos está, HTML, CSS, JAVA SCRIPT, y c++, entre otros.
          <br><br>
          <strong>López, Leonardo</strong><br>
          <strong>TB1</strong><br>
          Posee conocimientos en C++, HTML, CSS y Java Script, como tambien otros lenguajes.
    </td>
    <td><strong>TB1:</strong><br>La capacidad de manejar varios lenguajes de programación es bastante importante, lo cual influyó mucho para la elaboración del trabajo, dentro de ellos está el conocimiento de los lenguajes de HTML, CSS y Java Script, para la implementación de la Landing Page de manera correcta, por otro lado, la capacidad de poder manejar os diagramas de modelado C4, lo cual nos ayudó a mostrar de diferentes maneras el enfoque que tendrá nuestro proyecto final, no dejemos de lado la herramienta Figma, que nos sirvió para realizar el diseño del proyecto, y de esta manera poder ayudarnos para la implementación de la Landing Page.</td>
  </tr>
</table>

<br><br>

# Capitulo 1: Introducción
<div align="justify">

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup
Nuestra aplicacación **"LOYALSIPS"** de nuestro equipo **"TechSolutions"** ha sido creado con la finalidad de mejorar el sistema de administracion para el sector de bares y mejorar la experiencia del cliente por medio de  beneficios como descuentos, y promociones. 

 #### Misión

La misión de nuestra App es generar facilidad de interacción entre clientes y bares, como también mejorar las herrramientas de gestión para-ambos sectores.  

#### Visión

Nuestra visión es que la aplicación que desarrollemos marque un nuevo hito entre las aplicaciones similares que existen y que nuestros usuarios nos respaldan considerando a ésta una de las mejores del rubro. 

### 1.1.2 Perfiles de integrantes del equipo

<table style="border-collapse: collapse; width: 100%;">
  <tr>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Foto</th>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Miembro</th>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Habilidades</th>
    <th style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Codigo</th>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1145902674265505832/rostro.jpeg?width=466&height=621" alt="Foto 1" width="60" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Ampudia Flores, Jose Carlos Isaac</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Actualmente soy estudiante del 6to ciclo de la carrera de Ingeniería de Software en la UPC. Cuento con conocimientos en programación orientado a objetos en el lenguaje de C++, manejo de base de datos relacional y no relacional. Además he elaborado algunos videojuegos y programas para trabajos de la universidad.</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">u202112936</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1145902797229916192/ba.jpg?width=621&height=621" alt="Foto 2" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Alarcon Rondon, Sandro Fourfive</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Actualmente soy estudiante de la UPC y curso en el 6to ciclo en la carrera de Ing. de Software. Tengo experiencia en el desarrollo de sitios web y conocimientos en los lenguajes de programación C++ y  CSS</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">u202114140</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1145900517415981216/WhatsApp_Image_2023-08-28_at_20.58.40.jpeg?width=466&height=621" alt="Foto 3" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Morin Fuentes, Jean Pierre</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Estoy cursando el 6to ciclo de la carrera de ingeniería de software, tengo conocimiento del lenguaje de programación C++ y he aprendido lo básico de HTML, tengo conocimiento de páginas webs.</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">u202115348</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639921830973515/1149466066397962350/image.png?width=316&height=485" alt="Foto 4" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Louis Alfaro Coveñas</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Soy una persona que le fascina la tecnología en sus múltiples aspectos y, además, le gusta trabajar en equipo. En base a mis skills, destacan el tema de liderazgo, conocimientos de marcos de trabajos ágiles, programación en lenguajes tales como C++, HTML, CSS y manejo de base de datos como MySQL, SQL Server y MongoDB.</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">u202110458</td>
  </tr>
  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639921830973515/1149466156269309983/image.png?width=298&height=434" alt="Foto 5" width="50" height="50" style="border-radius: 25%;">
    </td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Leonardo Paul Lopez Huarcaya</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">Actualmente estudiando la carrera de Ingeniería de Software. Yo como estudiante de esta carrera hasta el momento ya sé manejar el código en C++, python y un poco de java, manejando estructuras, ciclos repetitivos y más. Soy entusiasta, perseverante y gracias a ello podré siempre mantener al equipo unido para cumplir con todas las actividades a tiempo.</td>
    <td style="border: 1px solid #dddddd; padding: 8px; text-align: center;">u20201b895</td>
  </tr>
</table>

# Capitulo 1: Introducción

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup


#### Misión

La misión de nuestra App es generar facilidad de interacción entre clientes y bares, como también mejorar las herrramientas de gestión para-ambos sectores.  

#### Visión

Nuestra visión es que la aplicación que desarrollemos marque un nuevo hito entre las aplicaciones similares que existen y que nuestros usuarios nos respaldan considerando a ésta una de las mejores del rubro. 
 
## 1.2. Solution Profile

Nuestra solucion ante la problemática que explicaremos mediante el uso de las 5"W" y 2"H" será la creacion de una website, cuando nuestros clientes quieran salir a tomar podran usar nuestra aplicacion y podran generar puntos en la app para tener descuentos, asi se motivara a seguir comprando por nuestra app.

### 1.2.1 Antecedentes y problemática

***What? - ¿Qué?***

En la actualidad, las personas cuando van algun bar a tomar un trago, sienten que los precios son un poco elevados, no encuentran ofertas, muchas veces no los atienden rapido o tambien no encuentran una mesa para sentarse. 

Para aportar ayuda a solucionar este problema se va a realizar una website simple a la vista de los clientes, asi ellos podran encontrar ofertas en los tragos y tambien que puedan reservar una mesa con un debido tiempo de anticipacion.

Uno de los beneficios que tendran nuestros clientes al momento de usar nuestra website es que podran acumular puntos para asi tener un descuento especial. Esto hara que nuestros clientes vuelvan a usar nuestra website y se sientan comodos con lo que les ofrecemos.

***When? – ¿Cuándo?***

Esta problematica ocurre cuando las personas que se desean divertirse algun dia de la semana o un feriado largo, se dan con la sorpresa que los precios estan muy caros o que los bares estan repletos.

***Where? – ¿Dónde?***

El problema surge en varios lugares. Sin embargo, nos vamos a centrar en los Bares de Lima Metropolitana porque se tiene mas conocimiento sobre la localidad.

***Who? - ¿Quién?***

La aplicacion servira para todos los residente de Lima Metropolitana con intencion de poder ir a un bar y que se sientan comodos con la atencion brindada en el bar como tambien en nuestra website

***Why? - ¿Por qué?***

La razon de realizar el proyecto es que uno de los principales factores que pudimos detectar en la poblacion de Lima Metropolitana fue que las personas cuando van a un bar muchas veces estan llenos, no hay ningun tipo de oferta y que se demoran demasiado para atenderlos. Entonces, nosotros al ver esta problematica decidimos inovar una website que te permida comprar tus tragos y que puedas reservar una mesa con anticipacion, asi los clientes se evitaran malos momentos en los bares.

***How? - ¿Cómo?***

Tener una base de datos con informacion facil y didactica con la que los usuarios puedan elegir sus tragos o bebidas en los bares y tambien que puedan hacer reservas de mesas cuando lo vean conveniente.

***How much? - ¿Cuánto?***

Se ha investigado que en el Perú el 55.8% de personas salen todos los fines de semana a relajarse en discotecas y bares. 

Ademas, en el Perú muy pocas personas utilizan una website para reservar espacios en los bares y tampoco para comprar bebidas o tragos.


  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1149362286729887814/image.png"width="403" height="296">
    </td>
  </tr>
<br>

### 1.2.2 Lean UX Proccess

#### 1.2.2.1 Lean UX Problem Statements
Después de analizar la problemática y los factores que la ocasionan, podemos tener un panorama de cómo solucionar la necesidad del usuario declarando supuestos, lo cual corresponde al siguiente paso de la Lean UX. Por ello, es necesario tener un conocimiento previo de las empresas que tienen características similares a las nuestras y cómo estas se han desarrollado con el paso del tiempo.
Con una investigación rigurosa que hicimos podemos declarar que existe una competencia indirecta. Esta competencia vendrían a ser las apps sobre la gestión online de bares.


#### 1.2.2.2. Lean UX Assumptions.
##### ***<u>FEATURES</u>***
-	Registro de los clientes hacia la website para tener la facilidad de poder supervisar los puntos acumulados, además de visualizar el catálogo de productos con los que pueden ser canjeados.
-	Bonificar a los clientes de un respectivo bar a través de puntos que los clientes irán ganando por cada cierta compra de productos al bar, este acuerdo lo define el bar.
-	Los clientes tendrán la facilidad de recibir correos electrónicos para que se mantengan informados sobre los puntos que van acumulando u ofertas.
-	Existirá un área donde el cliente podrá calificar nuestro website, esto nos ayudará a mejorar nuestro servicio.
-	El servicio también proporcionará al bar un sistema de control de inventario que podrá controlar que productos están agotándose, de tal manera que el encargado solicite nuevos productos por medio de la revisión del website que nosotros implementemos.

##### ***<u>BUSINESS OUTCOMES</u>***
1.	**¿Qué estamos tratando de lograr?**

Incrementar las ganancias de los bares por medio de que los clientes sean más fieles al bar, de tal forma que las ventas del bar sean mayores.

2.	**¿Qué tipo de objetivos tienen?**

El objetivo principal es facilitar al bar a incrementar sus ganancias y de la misma forma apoyar en el control de inventario para facilitar el trabajo de los encargados en dicho rubro. Además, se tiene como objetivo secundario, que no solo 1 bar use nuestro servicio, sino muchos.

3.	**¿Qué tipos de usuarios necesita?**

Nuestros usuarios serán los empresarios de los bares, e indirectamente los clientes de los bares, que consumirán nuestro servicio.

##### ***<u>USER BENEFITS</u>***
-	Facilidad y flexibilidad del sitio web para el beneficio del usuario.
-	Notificar por medio de correo electrónico al usuario sobre sus puntos ganados y posibles canjes.

##### ***<u>SUPUESTOS DEL NEGOCIO</u>***

1.	**Creemos que nuestros clientes necesitan:** Recibir ofertas o eventos que se realizarán en el bar para que puedan motivarse a ir.

2.	**Creemos que podemos solucionar con:** Envío de notificaciones a los clientes por medio de sus correos electrónicos o números de celular.
3.	**Mis clientes iniciales son (o serán):** Empresarios de bares, e indirectamente, los clientes de los bares, es decir, personas mayores de 18 años.

4.	**El valor #1 que un cliente quiere de mi servicio es:** Que nuestro servicio sea sencillo de entender y usar.

5.	**Voy a adquirir la mayoría de mis clientes a través de:** Recomendación de los empresarios por nuestro servicio útil, además con el uso de anuncios en internet.

6.	**Mi competencia principal del mercado será:** Sitios web dedicadas a facilitar la venta del sector de bares.

7.	**Lo venceremos por medio de:** Nuestro sitio web se diferenciará porque además de proporcionar puntos al cliente por cada compra realizada, proporcionará al bar un servicio de control de inventario, por lo que la empresa del bar estará ligada a nuestro servicio, sirviéndoles de gran apoyo.

8.	**Nuestro principal riesgo de producto es:** que el sitio web sea algo confuso de entender para los clientes que no están acostumbrados a la tecnología de hoy en día.

9.	**Lo resolveremos a través de:** Implementar un sitio web amigable y sencillo de usar para el usuario y empresario.

10.	**Creemos que:** Nuestro servicio será de gran ayuda en generar más ganancias a las empresas de licorería, como son los bares, lo cual motivará a los clientes a consumir más en dicho bar. 

##### ***<u>SUPUESTOS DEL USUARIO</u>***
1.	**¿Dónde encaja nuestro producto en su trabajo o vida?**

Creemos que nuestro proyecto aporta de manera esencial a las empresas de licorería que deseen generar más ganancias por medio de que los clientes preferirán el bar por el sitio web de puntos de bonificación.

2.	**¿Qué problemas tiene nuestro producto y como se pueden resolver?**

Un problema de nuestro proyecto es que en algún momento exista una saturación por exceso de usuarios usando la aplicación en simultáneo, lo cual lo resolveremos aumentando nuestro servicio cloud en los meses de uso más frecuentes.


##### ***<u>USUARIO</u>***

1.	**¿Quién es el usuario?**

Los empresarios de los bares, y todas las personas mayores de 18 años.

2.	**¿Cuándo y cómo será usado nuestro producto?**

Nuestro producto será usado diariamente, porque es cierto que los bares tienen clientes de manera diaria, es por eso que mientras el bar esté en funcionamiento, por ende, estarán usando nuestro servicio, de tal forma que el usuario podrá visualizar en el sitio web sus puntos y poder ver qué productos pueden ser canjeados por dichos puntos.

##### ***<u>CARACTERÍSITCAS</u>***

1.	**¿Qué características son importantes?**

Que el sitio web sea sencillo, interactivo y fácil de usar, de tal forma que las funciones no sean recargadas y cumplan el objetivo principal que es el acumulador de puntos y servicio de control.

2.	**¿Cómo debe verse nuestro producto y como debe comportarse?**

Debe tener un diseño minimalista, pero a la vez atractivo, con colores que combinen con el propósito del servicio, el comportamiento debe ser sencillo y eficaz, sin tanto rodeo, para evitar confundir al cliente.

#### 1.2.2.3. Lean UX Hypothesis Statements.  

**Hipótesis 1:**

**Creemos que** implementando un sitio web, este podrá ser usado tanto en dispositivos Android como IOS, sin la necesidad de crear una aplicación para cada sistema operativo. Por parte de las empresas tendrán la misma facilidad con el control de inventario.

**Sabremos que** hemos tenido éxito.

Cuando en el primer trimestre de ser lanzado nuestro servicio, la empresa obtenga mejoras considerables en las ganancias.


**Hipótesis 2:**
**Creemos que** implementar un sistema de control de inventario para la empresa, ayudará a esta misma a facilitar el trabajo de los encargados, de tal forma que sea más fácil llevar un control.

**Sabremos que** hemos tenido éxito.

Cuando en el primer año que nuestro producto sea lanzado, sea solicitado por más empresas de licorería, de tal forma que sea un producto que favorezca al incremento de ganancias para muchos bares y no solo a uno.
## 1.2.2.4 Lean UXCanvas
<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149520349759799386/image.png"width="" height="">
    </td>
  </tr>
<br>

## 1.3 Segmentos Objetivos
**Clientes Frecuentes**: Este es uno de los segmentos más importantes. Los clientes que visitan tu bar con regularidad son ideales para la fidelización. Puedes ofrecer recompensas específicas para mantener su lealtad y aumentar su frecuencia de visita.

**Amantes de la Música en Vivo**: Si ofreces música en vivo o actuaciones en tu bar, puedes dirigirte a aquellos que disfrutan de estos eventos. Ofrece recompensas como acceso gratuito a conciertos o asientos prioritarios.

**Empresarios de bares**: En bares más grandes o cadenas de establecimientos, el dueño o empresario puede pasar más tiempo en una oficina o área de gestión dedicada. Desde allí, pueden supervisar y coordinar las operaciones de varios locales y trabajar en estrategias de negocio a largo plazo.

# Capítulo II: Requirements Elicitation & Analysis -  

## 2.1. Competidores. -  

### 2.1.1. Análisis competitivo


<table >
  <tr > 
    <th colspan="4"> Competitive Analysis Landscape </th>    
  </tr> 
  
  <tr> 
    <td  >¿Qué llevar cabo en este análisis? </td> 
    <td >Debido al analisis de los competidores del mercado actual, hemos logrado identificar las fortalezas y debilidades de nuestros competidores. Esto nos ayuda a identificar que estrategias tomar para posicionarnos dentro del mercado y como diferenciarnos de ellos.  </td>    
  </tr> 
  
  <tr> 
    <td colspan="4" align="center" >¿Quienes son nuestros principales competidores y que nos diferencia de ellos? </td>    
  </tr>
  
  <tr> 
    <td  ></td>  
    <td  ></td> 
    <td ><img src="https://media.discordapp.net/attachments/1146639921830973516/1149503395309293608/GEIfFwe57gAAAABJRU5ErkJggg.png" height="40">  </td>  
    <td  ><img src="https://media.discordapp.net/attachments/1146639921830973516/1149503543036878991/8hCjmUnM9rUizlTrbq884vVgiAIgiAIgiAIgiAIgiAIgiAIgiAIghDmP63uaBSiYBMwAAAAAElFTkSuQmCC.png" height="80"> </td>
    <td  > <img src="https://media.discordapp.net/attachments/1146639921830973516/1149503462976000161/yelp-logo_768x512.png?width=635&height=423" height="40">	</td>  
    <td > <img src="https://media.discordapp.net/attachments/1146639921830973516/1149513853357543464/WhatsApp_Image_2023-08-31_at_8.00.27_PM.jpeg?width=486&height=423" height="80"> </td>  
  </tr> 
  
  
  
  <tr> 
    <td > PERFIL </td> 
    <td > Overview </td>  
    <td > Drink go es una aplicacion que busca agilizar y facilitar la forma de consumir en las barras de los eventos musicales. Esta aplicación te evitará usar pulseras, tokens o efectivo para pagar tu bebida. Puedes obtener puntos por cada compra, y Podrás canjearlos por entradas, camisetas, etc. </td> 
    <td > Kyte es un sistema de punto de venta para bares para cualquiera que busque digitalizar, puede manejar su establecimiento y vender en línea o de forma presencial sin perderse y con más libertad, ya que puede controlar su negocio desde su celular, tableta o computadora.  </td>
    <td > Yelp es una aplicación que permite a los usuarios encontrar puntos de ventas de bares, restaurantes, etc. Permite a los clientes conocer información a cerca de estos lugares, atención, promociones, reseñas y más.  </td>
    <td >  Loyalsips es una aplicacion que permite a los dueños de bares, administrar y promover sus negocios, como tambien permite a los clientes conocer a cerca de los bares, y recibir promociones, anuncios y  premios. </td>
  </tr> 


<tr> 
    <td > PERFIL </td> 
    <td > Ventaja competitiva 

¿Que valor ofrece a los clientes? </td>  
    <td > Agilización de procesos en tiempo de atención y obtencion de recompensas al cliente y de la administración de inventario para bares.  </td> 
    <td > Gestión digitalizada para vender, y administrar inventario de negocio.   </td>
    <td > Comunicación interactiva de los usuarios dentro la plataforma. </td>
    <td >  Administracion para la gestion de inventario y ventas para el bar y recompensas y premios para los clientes.  </td>
  </tr> 


<tr> 
    <td > Perfil de Marketing </td> 
    <td > Mercado Objetivo </td>  
    <td > Bares que busquen agilizar procesos de ventas y promover el consumo a clientes.

</td> 
    <td > 
Bares que busquen gestionar el inventario y sus ventas. 


  </td>
    <td > 
Bares que busquen darse a conocer en el rubro con alta interaccion con los usuarios. 



</td>
    <td >  
Bares que necesiten gestionar el inventario, y sus eventos.

</td>
  </tr> 
  
  
  <tr> 
    <td > Perfil de Marketing </td> 
    <td > Estrategias de Marketing </td>  
    <td > Marketing a través de campañas digitales en redes sociales, realizar eventos, promociones y ofrecer recompensas. </td> 
    <td > Promocionar por medio de Google Ads para encontrar en los resultados de los navegadores.  </td>
    <td > Promocionar por medio de Google Ads para encontrar en los resultados de los navegadores. 

Campañas digitales en redes sociales,  </td>
    <td > Marketing a través de campañas digitales en redes sociales, realizar eventos, promociones y ofrecer recompensas. 

Uso de Google Ads para encontrar en los resultados de los navegadores </td>
  </tr> 

  
<tr> 
    <td > Perfil de Producto </td> 
    <td > Productos y servicios  </td>  
    <td >Servicio de gestion de ventas en la aplicacion.  </td> 
    <td > Servicio de gestion de ventas en la aplicacion. 

 

Servicio de gestion inventario.  </td>
    <td > Servicio de gestion de reservas.  </td>
    <td > Servicio de gestion inventario. 

 

Servicio de gestion publicitaria en la aplicacion. </td>
  </tr> 




<tr> 
    <td > Perfil de Producto </td> 
    <td >  Precio y costo </td>  
    <td >Descarga Gratis  

Comision por venta entre 3.5% a 5.5%. </td> 
    <td > Descarga Gratis con funciones limiadas. 

 

Suscripciones premium de  

US$ 7.99/Mes 

US$ 11.99/Mes 

US$ 19.99/Mes con mayor opcion de funciones. </td>
    <td > Descarga Gratis 

 Anucios dentro es oscilan entre $0,30 y $4.  </td>
    <td >  Descarga Gratis 

Suscripciones premium de  

US$ 7 /Mes 

US$ 10/Mes 

 

CPC entre $0,10 y $1,5. </td>
  </tr> 

<tr> 
    <td > Perfil de Producto </td> 
    <td > Canales de distribucion  </td>  
    <td >Móvil </td> 
    <td >Web y movil  </td>
    <td > Web y movil  </td>
    <td > Web y movil  </td>
  </tr> 
  
  <tr> 
    <td > Perfil de Producto </td> 
    <td > Canales de distribucion  </td>  
    <td >Móvil </td> 
    <td >Web y movil  </td>
    <td > Web y movil  </td>
    <td > Web y movil  </td>
  </tr> 



<tr> 
    <td > Análisis SWOT  </td> 
    <td > Fortalezas  </td>  
    <td >Uso rápido y fácil de la aplicación.   </td> 
    <td >Facil manejo y control de funcionalidades para el bar. </td>
    <td >La interaccion constante de los usuarios en la plataforma.  </td>
    <td > Uso de herramientas publicitarias para promocionar bares.  </td>
  </tr> 

<tr> 
    <td > Análisis SWOT  </td> 
    <td > Debilidades   </td>  
    <td >Baja tasa de interacion de los usuarios en Perú </td> 
    <td >Baja interacción con los usuarios, soporte bajo nivel de asistencia. </td>
    <td >No disponible en Perú  </td>
    <td >Sistema de filtrado de busquedas.  </td>
  </tr> 


<tr> 
    <td > Análisis SWOT  </td> 
    <td > Oportunidades   </td>  
    <td >Integracion de mayor funcionalidades de publicidad para los bares. </td> 
    <td >Incrementar el numero de usuarios en su plataforma.  </td>
    <td >Crecimiento de personas interesadas en conocer nuevos lugares en Perú. </td>
    <td >Crecimiento de publico objetivo interesados en la aplicacion  </td>
  </tr> 

<tr> 
    <td > Análisis SWOT  </td> 
    <td > Amenazas   </td>  
    <td >Solo contar con el movil para interactuar con la aplicacion. </td> 
    <td >Soporte rápido para personas que sean de Brasil.  </td>
    <td >Sotware con problemas de mantenimiento  </td>
    <td >Tiempo de respuesta del servidor.  </td>
  </tr> 


</table>



### 2.1.2. Estrategias y tácticas frente a competidores.
-	Nosotros superaremos a la competencia al tener un completo grupo de profesionales que estarán constantemente actualizando productos con los que pueden ser canjeados por puntos.

-	Nuestro servicio permitirá que los clientes acumulen puntos, además, simultáneamente brindaremos un servicio de control de inventario de los productos del bar, con la finalidad de facilitar el trabajo a los encargados de ese rubro.

-	Se implementarán actualizaciones cada cierto plazo, de manera que se solucione todos los inconvenientes y quejas con respecto a nuestros usuarios. 

-	Seremos un servicio mucho más completo, ofrecemos más funciones que la competencia para el uso de nuestros usuarios y por parte del empresario. 

-	Nuestro servicio será mucho más accesible al estar disponible en todos los dispositivos ya que será un sitio web responsive.

-	Tendremos mucho más alcance con nuestra publicidad y alianzas estratégicas. 

-	Implementaremos un sector en el que los usuarios puedan comentar algunas sugerencias con respecto a la aplicación, es decir, podrán comentar o calificar con un rango de estrellas, el cual sea de su preferencia, para mantenernos informados y realizar mejoras a nuestro servicio.

## 2.2. Entrevistas.



### 2.2.1. Diseño de entrevistas.
  **USUARIOS:**

1.	***¿Cómo fue tu experiencia en el último bar que visitaste?***
2.	***¿El bar al que fuiste poseía una plataforma digital?***
3.	***¿Alguna vez imaginaste poder acumular puntos por cada compra realizada en un bar? ¿Qué piensas de eso?***
4.	***¿Qué tipos de reclamos o recompensas te motivarían a acumular muchos más puntos en los bares que visitas?***
5.	***Qué te parece más atractivo: ¿descuentos en bebidas, canjear un producto por una cierta cantidad de puntos acumulados u otras ofertas?***
6.	***¿Has participado en programas que ofrezcan puntos al cliente por cada compra en los bares que has visitado?***
7.	***¿Qué aspectos crees que hicieran único al programa de fidelización, porque es lo que es, en este caso, el acumulador de puntos, desde tu perspectiva como cliente?***
8.	***¿Cómo preferirías recibir notificaciones o actualizaciones sobre los puntos que vas ganando u ofertas de los productos?***
9.	***¿Hay algo extra que te gustaría compartir o sugerir con respecto a este programa de fidelización que nosotros vamos a desarrollar?***

**EMPRESA:**
1.	***¿Alguna vez imaginaste generar más ganancias con plataformas digitales que ayuden a tu negocio a ser más innovador?***
2.	***¿Crees que un sistema de acumulación de puntos a los clientes podría beneficiar a tu negocio?***
3.	***Además, tengo entendido que el hecho de controlar lo vendido en un bar es algo trabajoso, sobre todo, verificar que los productos se están agotando, ¿cómo vienes desarrollando esta labor con respecto a tu bar?***
4.	***¿Conoces bares que manejen este sistema tecnológico? ¿Por qué crees que el ámbito tecnológico ayudaría a tu negocio?***
5.	***Tanto el sistema de control de inventarios como el de acumular puntos a los clientes para que posteriormente sean canjeados por nuevos productos y ofertas, ¿De que manera crees que estos sistemas ayudarían a tu negocio?***
6.	***¿Estarías dispuesto a ofrecer descuentos o promociones especiales a los clientes que acumulen puntos? Teniendo en cuenta que esto generará una alianza entre el cliente y tu negocio, motivándolo a ir más seguido e ir motivando a demás personas.***
7.	***¿Qué método de comunicación preferirías para mantenerte informado sobre las novedades del servicio y actualizaciones?***
8.	***¿Existe algo extra que te gustaría compartir o sugerir con respecto a este programa que vamos a desarrollar? ¿Crees que es algo innovador en el sector de los bares?***

## 2.2.2. Registro de entrevistas.
Se registró la primera entrevistada de los 2 segmentos objetivos que en este caso es del segmento Empresario de un bar
<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149526847856590918/image.png"width="" height="">
    </td>
  </tr>
<br>
https://youtu.be/T5lmt_ndV2Q

Se registró la primera entrevistada de los 2 segmentos objetivos que en este caso es del segmento Cliente frecuente de un bar
<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149527278355750972/image.png"width="" height="">
    </td>
  </tr>
<br>
https://youtu.be/6ZyfneZ99rg

## 2.2.3. Análisis de entrevistas.
1. Entrevista con Angie Alexandra Lopez Quevedo, Joven Dueña de Bar Angie Alexandra Lopez Quevedo, una joven dueña de un bar de 25 años, compartió sus pensamientos sobre la implementación de tecnología en su negocio y su interés en mejorar el stock y el marketing para atraer a más clientes. Angie reconoce que no tiene experiencia en tecnología pero cree que podría ser beneficiosa para gestionar el stock y mejorar las estrategias de marketing de su bar. Además, está a favor de utilizar herramientas de acumulación de puntos para atraer a nuevos clientes, aunque no conoce bares que utilicen este sistema en su área. Cree que la tecnología está en constante evolución en el Perú y puede contribuir a un mejor manejo de la economía de su bar. En cuanto a la comunicación, Angie prefiere utilizar correos electrónicos, ya que le resulta más conveniente y le permite priorizar sus respuestas. Está muy interesada en implementar software que le ayude a gestionar el stock y a mejorar la economía de su bar. En resumen, Angie está abierta a la idea de incorporar tecnología en su bar, especialmente para el control de stock y el marketing. Ve el potencial en herramientas como la acumulación de puntos para atraer clientes y está dispuesta a aprender sobre estas soluciones tecnológicas para mejorar su negocio en constante crecimiento en el Perú.


2. Entrevista con Alek Ramirez, Joven Cliente Frecuente de un Bar Alek Ramirez, un joven cliente frecuente de 22 años de un bar tradicional, compartió su experiencia reciente en el bar y expresó su entusiasmo por la idea de implementar un sistema de puntos en establecimientos similares. Destacó la amabilidad en la atención recibida durante su última visita al bar y considera que un sistema de puntos sería muy beneficioso para recompensar a los clientes habituales. Alek sugiere que un sistema de puntos podría permitirle obtener tragos gratuitos o canjear bebidas a cambio de una cierta cantidad de puntos acumulados, lo que sería un incentivo adicional para seguir siendo un cliente frecuente. Además, menciona que hasta ahora no ha encontrado bares que utilicen este tipo de sistema para el control de stocks y puntos, lo que despierta su interés por la innovación en este campo. El cliente enfatiza la importancia de personalizar el sistema de puntos, basándose en las preferencias de los clientes y sus consumos habituales. También prefiere la comunicación a través del correo electrónico, lo que facilita su interacción con el bar y la gestión de sus recompensas. En resumen, Alek recomienda que el sistema de puntos en el bar sea más personalizable y basado en los gustos y consumos individuales de los clientes. Está emocionado por la posibilidad de obtener recompensas como tragos gratuitos o canjes de productos a cambio de puntos acumulados y considera que esta iniciativa podría incentivar aún más su lealtad como cliente frecuente.

## 2.3. Needfinding.

<div align='justify'>
En esta sección se presentan los artefactos del proceso de análisis de la información recopilada de nuestros segmentos objetivos. Se incluyen las secciones de User Personas, User Task Matrix, User Journey Mappin, Empathy Mapping y As-Is Scenario Mapping. 
</div>

### 2.3.1. User Personas.

En esta sección presentaremos dos fichas de User Persona para nuestro producto,
el cual se enfoca en el cliente que va consumir algun trago y en la Empresa. Estas
fichas están basadas en las principales características y necesidades identificadas
en el análisis de entrevistas y de la competencia.


#### 2.3.1.1 Segmento Objetivo 1: Cliente

  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1147987398639235173/User_Person_Cliente.png?width=419&height=592"width="403" height="569">
      </div>
    </td>
  </tr>

#### 2.3.1.2 Segmento Objetivo 1: Empresario
<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1147997558657007706/User_Person_Empresario.png?width=419&height=592"width="403" height="569"></div>
    </td>
  </tr>

### 2.3.2. User Task Matrix.

Esta sección llamada User Task Matrix es una herramienta que nos sirve para
poder entender las tareas y objetivos que cada User Persona desea lograr a la
hora de utilizar nuestro producto. En esta sección, se presentarán las matrices de
tareas para los User Personas previamente definidos.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1148008883084853418/Eisenhower_Matrix.jpg?width=1301&height=600"width="1301" height="600"></div>
    </td>
  </tr>

### 2.3.3. User Journey Mapping.
## Usuario Cliente

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149556210438246462/journey.JPG?width=1245&height=676"width="" height=""></div>
    </td>
  </tr>

## Usuario Empresario

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149557741933830155/usuario.JPG?width=1280&height=676"width="" height=""></div>
    </td>
  </tr>

Link de Miro -> https://miro.com/app/board/uXjVMnMLrn0=/?share_link_id=713054034361

### 2.3.4. Empathy Mapping.

## Usuario Cliente
<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149566378664284230/empathy2.JPG?width=1067&height=676"width="" height=""></div>
    </td>
  </tr>

## Usuario Empresario

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149566363904512001/empathy.JPG?width=1041&height=676"></div>
    </td>
  </tr>

Link del miro -> https://miro.com/app/board/uXjVMqvoKoU=/?share_link_id=430670075921

### 2.3.5. As-Is Scenario Mapping.
### Usuario (Cliente):
<br>
<table>
  <tr>
    <th><strong>Fases</strong></th>
    <th style="text-align: justify;"><strong>Abrir el sitio Web</strong></th>
    <th style="text-align: justify;"><strong>Ganar puntaje</strong></th>
    <th style="text-align: justify;"><strong>Ver puntaje</strong></th>
    <th style="text-align: justify;"><strong>Reclamar Puntos</strong></th>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>Hace</strong></td>
    <td style="text-align: justify;">Aun no hay un sitio web al que acceder.</td>
    <td style="text-align: justify;">Al realizar compras de licores no acumula puntos.</td>
    <td style="text-align: justify;">No se puede ver los puntajes.</td>
    <td style="text-align: justify;">Debido a que no se implemento un sistema de puntuación, no puede reclamar nada aun.</td>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>Piensa</strong></td>
    <td style="text-align: justify;">Me gustaria tener una app para poder reservar mas rapido y asimismo que ofrescan promociones </td>
    <td style="text-align: justify;">Me gustaria ganar puntos por las compras, para poder conjearlas mas adelante</td>
    <td style="text-align: justify;">Me gustaria poder ver mis puntos para administralos yo mismo</td>
    <td style="text-align: justify;">Que grandioso canjear puntos, para asi ser cliente de este local.</td>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>Siente</strong></td>
    <td style="text-align: justify;">Frustracion por que aun el bar no tiene un sistema digital.</td>
    <td style="text-align: justify;">Desepcionado ya que el bar no realizan ninguna promoción</td>
    <td style="text-align: justify;">Desilucionado ya que no puedo monitorear algo que no hay</td>
    <td style="text-align: justify;">Desanimado ya que al no haver ninguna promocion no me siento con ganas de volver al bar</td>
  </tr>
</table>

---
<br>

### Empresa (Dueño del Bar):
<table>
  <tr>
    <th><strong>Fases</strong></th>
    <th style="text-align: justify;"><strong>Abrir el sitio Web</strong></th>
    <th style="text-align: justify;"><strong>Ver puntaje</strong></th>
    <th style="text-align: justify;"><strong>Reclamar puntos</strong></th>
    <th style="text-align: justify;"><strong>Control de inventario</strong></th>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>Hace</strong></td>
    <td style="text-align: justify;">No hay ningun sitio web al que poder acceder</td>
    <td style="text-align: justify;">No se pueden visualizar los puntos de ningun cliente</td>
    <td style="text-align: justify;">Aun no se pueden dar promociones por los puntos.</td>
    <td style="text-align: justify;">Se tiene que contar los productos uno a uno y supervisar mensualemnte nuestros almacenes</td>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>Piensa</strong></td>
    <td style="text-align: justify;">Seria increible tener un sitio web de mi bar para brindar servicios mas eficientes</td>
    <td style="text-align: justify;">Me agrada la idea de tener un sistema de puntos para mis clientes </td>
    <td style="text-align: justify;">Me interesa poder dar a mis clientes las promociones con los puntos</td>
    <td style="text-align: justify;">Me facinaria poder tener mi control de inventario digital para ser mas eficiente con la administración</td>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>Siente</strong></td>
    <td style="text-align: justify;">Tristeza ya que no tiene un apartado virtual para sus clientes y el mismo</td>
    <td style="text-align: justify;">Desanimado ya que al no tener ninguna promocion puede que pierda a sus lientes</td>
    <td style="text-align: justify;">Desesperado ya que los clientes pueden buscar otros lugares donde haya una atencion mas eficiente </td>
    <td style="text-align: justify;">Cansado ya que al momento de realizar las cuentas de su almacen, pierde mucho tiempo, aveces se confunde y ocasiona varios conflictos con los empleados</td>
  </tr>
</table>

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.
Esta herramiente conocida como To-be Scenario Mapping nos permitió definir las necesidades de nuestros usuarios y de los gerentes de los bares. En esta sección se presentarán los diagramas de To-be Scenario Mapping para los User Personas previamente definidos. Lo esencial es identificar los aspectos a negativos y positivos de nuestro aplicativo para poder mejorarlos y así poder brindar un mejor servicio a nuestros usuarios y gerentes de bares.

**Usuario (Cliente):**

<div align='center'>
<img src="https://media.discordapp.net/attachments/1145898392631918606/1154673174961717328/to-be_-_cliente.png?">
</div><br>

Link para ver el [diagrama](https://miro.com/app/board/uXjVO8jKyt8=/?share_link_id=663854831408)

---
<br>

**Empresa (Dueño del Bar):**

<div align='center'>
<img src="https://media.discordapp.net/attachments/1145898392631918606/1154673174710071327/to-be_-_empresa.png?">
</div><br>

Link para ver el [diagrama](https://miro.com/app/board/uXjVO8jKyt8=/?share_link_id=663854831408)

---

## 3.2. User Stories

| Epic/Story ID | Título | Descripción  | Criterios de Aceptación | Relacionado con (Epic ID) |
|----------|----------|----------|-----------|-----------|
| HU01    | Crear cuenta común   | **Como** usuario del servicio web, **quiero** una sección de creación de cuenta **para** tener y acceder  con una cuenta propia. (los 2 segmento) | **Escenario 1:** Crear cuenta con un usuario y contraseña <br> **Dado** que el usuario desea crear una cuenta Cuando entre a la página del servicio <br>**Y** seleccione la opción “Crear cuenta”. <br>**Entonces** la plataforma brindará un formulario con los apartados “nombre”, “correo”, “nombre usuario” y “contraseña” <br>**Y** al validar los datos enviados se creará una cuenta en la plataforma. |Epic 1|
| HU02    | Crear cuenta con otras plataformas   | **Como** usuario del servicio web, **quiero** una sección de diversos métodos **para** la creación de cuenta.(los 2 segmento)| **Escenario 1:** Crear cuenta con otra plataforma <br>**Dado** que el usuario desea crear una cuenta <br>**Cuando** entre a la página del servicio <br>**Y** seleccione un icono de “Crear cuenta con:”<br> **Entonces** la plataforma validara si escogió “gmail”, “facebook”, “instagram” o “twitter”<br> **Y** verifique la cuenta, la plataforma creará una cuenta vinculada.|Epic 1|
| HU03  | Entrar a la página como invitado   | **Como** usuario del servicio web, **quiero** una sección de entrar como invitado **para** la que no sea necesario la creación de cuenta. (los 2 segmento)|**Escenario 1:** Entrar a la plataforma como invitado <br>**Dado** que el usuario desea ingresar a la plataforma <br>**Cuando** entre a la página del servicio <br> **Y** seleccione la opción de “Ingresar como invitado” <br>**Entonces** la plataforma validará a esa cuenta como usuario, limitando algunas funcionalidades |Epic 1 |
| HU04  | Catálogo de Bares   | **Como** usuario del servicio web, **quiero** una sección de catálogos de bares que cuentan con diversos filtros **para** poder seleccionar con facilidad los bares cercanos, por el costo u otros. (segmento cliente)|**Escenario 1:** Catálogo de bares <br>**Dado** que el usuario desea ver los bares registrados en la plataforma <br>**Cuando** ingrese a la página del servicio <br>**Y** seleccione la opción de “Ver bares” <br>**Entonces** la plataforma mostrará un catálogo de bares registrados, con una breve descripción e imágenes. <br><br>**Escenario 2:** Catálogo de bares con filtros <br>**Dado** que el usuario desea ver los bares registrados en la plataforma <br>**Cuando** ingrese a la página del servicio <br>**Y** seleccione la opción de “Ver bares” <br>**Y** en la sección de filtros en la casilla de “lugares” y seleccione “barranco”. <br>**Entonces** la plataforma mostrará un catálogo de bares registrados, con una breve descripción e imágenes del distrito de barranco. <br><br>**Escenario 3:** Catálogo de bares con filtros <br>**Dado** que el usuario desea ver los bares registrados en la plataforma <br>**Cuando** ingrese a la página del servicio <br>**Y** seleccione la opción de “Ver bares” <br>**Y** en la sección de filtros en la casilla de “los más visitados” <br>**Entonces** la plataforma mostrará un catálogo de bares registrados con altas demandas en el último mes, con una breve descripción e imágenes.|Epic 2 |
| HU05  | Añadir bar   | **Como** usuario del servicio web, **quiero** registrar mi bar **para** que los clientes puedan interactuar con él.(segmento negociante)|**Escenario 1:** Registrar bar <br>**Dado** que el usuario desea registrar su bar en la plataforma <br>**Cuando** ingrese a la página del servicio **Y** seleccione la opción de “Registrar Bar” <br>**Entonces** la plataforma emitirá un formulario más complejo con los siguientes ítems a completar: “Nombre del bar”, “Dirección”, “capacidad”, “imagen de la licencia de funcionamiento”, “imágenes del local”, “números de contacto”, “correos de contacto”, ”descripción” y una contraseña para que pueda modificar o eliminar su bar.<br>**Y** al validar estos datos se registrará el local.|Epic 2|
| HU06  | Modificar mi Bar   | **Como** usuario del servicio web, **quiero** modificar datos de su bar **para** que los clientes puedan tener los datos actualizados.(segmento negociante)|**Escenario 1:** Modificar mi bar <br>**Dado** que el usuario desea modificar datos de su bar en la plataforma <br>**Cuando** ingrese a la página del servicio <br>**Y** seleccione la opción de “Mi Bar” <br>**Y** valide el nombre y la contraseña del bar <br>**Entonces** la plataforma ingresara a la sección de mi bar con campos editables <br>**Y** al momento de registrar se guardarán todos los cambios realizados.|Epic 2|
| HU07  | Eliminar mi Bar   | **Como** usuario del servicio web, quiero eliminar mi bar registrado para que los clientes ya no miren el servicio. (segmento negociante)|**Escenario 1:** Eliminar mi bar <br>**Dado** que el usuario desea eliminar su servicio de bar en la plataforma <br>**Cuando** ingrese a la página del servicio <br>**Y** seleccione la opción de “Mi Bar” <br>**Y** valide el nombre y la contraseña del bar <br>**Y** seleccione eliminar mi bar <br>**Entonces** la plataforma emitirá una confirmación a su correo y un campo de sus motivos por el cual lo hace (opcional). <br>**Y** se eliminará el servicio de bar.|Epic 2|
| HU08  | Mostrar mesas disponibles    | **Como** usuario del servicio web, **quiero** ver las mesas disponibles en los bares **para** poder reservar y no perder tiempo en la espera de alguna. (segmento cliente)|**Escenario 1:** Mostrar mesas mediante la plataforma <br>**Dado** que el usuario desea ver las mesas de var mediante la plataforma <br>**Cuando** ingrese a la página del servicio <br>**Y** entre al catálogo de bar,seleccione uno <br>**Y** seleccione la opción reservar <br>**Y** ingrese una fecha y hora de reserva <br>**Entonces** la plataforma mostrará las mesas disponibles para esa fecha con datos adicionales (sillas, ubicación e imágenes).|Epic 3|
| HU09  | Reservar mesas   | **Como** usuario del servicio web, **quiero** reservar el bar vía online y rápido **para** no perder tanto tiempo.(segmento cliente)|**Escenario 1:** Reservar mesas <br>**Dado** que el usuario desea reservar mesas de var mediante la plataforma <br>**Cuando** ingrese a la página del servicio <br>**Y** entre al catálogo de bar,seleccione uno <br>**Y** seleccione la opción reservar <br>**Y** ingrese una fecha y hora de reserva <br>**Y** ingrese a una mesa  <br>**Y** presione en reservar (pagando o no de acuerdo a lo que solicitó el dueño) <br>**Entonces** la plataforma notificará al dueño y éste confirmará mediante su correo la reserva del lugar. <br>**Y** el sitio web marcará como reservado la mesa.<br><br>**Escenario 2:** Reservar mesas <br>**Dado** que el usuario desea reservar mesas de var mediante la plataforma <br>**Cuando** ingrese a la página del servicio <br>**Y** entre al catálogo de bar,seleccione uno <br>**Y** seleccione el número de teléfono asociado. <br>**Entonces** la plataforma mostrará los números registrados del bar para que se comuniquen directamente. |Epic 3|
| HU10  | Almacén de los productos  | **Como** usuario del servicio web, **quiero** tener un centro de datos de mis productos del bar en tiempo real **para** mantener los stock de todos los productos y poder organizarlo mejor. (segmento negociante)|**Escenario 1:**  Agregar productos <br>**Dado** que el usuario desea agregar productos a su almacén digital. <br>**Cuando** ingrese a la página del servicio<br> **Y** entre a “mi bar” con su usuario y contraseña.<br>**E** ingrese a “mi almacén”  <br>**Y** ingrese agregar producto <br>**Entonces** la plataforma pedirá el nombre, fecha de vencimiento, código de barra y cantidad del producto para el registro de este en la plataforma.|Epic 4|
| HU11  | Administrar los productos   | **Como** usuario del servicio web, **quiero** administrar todos los movimientos de mis productos **para** así poder supervisar mejor y más rápido la parte administrativa. (segmento negociante)|**Escenario 1:**  Venta de producto <br>**Dado** que el usuario desea administrar mejor su negocio cuando requiera vender un producto <br>**Cuando** ingrese a “mi bar”<br>**E** ingrese a generar venta  <br>**Y** escanee mediante el o los productos que venderá  <br>**Entonces** la plataforma mostrará el precio individual y acumulado de acuerdo a la cantidad <br>**Y** emitirá una boleta o factura sobre la venta. <br>**Y** actualizará el almacén digital.<br><br>**Escenario 2:** Rendición de cuenta <br>**Dado** que el usuario desea administrar mejor su negocio, cuando requiera sacar el balance de un determinado tiempo <br>**Cuando** ingrese a “mi bar” <br>**E** ingrese a generar “balance de ventas” <br>**Y** seleccione un intervalo de fechas. <br>**Entonces** la plataforma mostrará todas las ventas de ese mes, mostrando cuánto se vendió cada día y el total de esas fechas.|Epic 4|
## 3.3. Impact Mapping
La herramienta Impact Mapping representa de forma visual las metas que nos planteamos para llegar a cada sector de nuestro publico. 
### User Bar:
<tr>
    <td>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149524347619389551/image.png?width=289&height=423"width="403" height="569"></div>
    </td>
</tr>
<br>

Realizamos el impact Mapping para el usuario Bar, que representa a los dueños bares, y según los User Stories realizadas por nuestro equipo, desarrollamos alternivas para solucionar y satisfacer sus necesidades. 

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149524152261283901/image.png?width=401&height=423"width="403" height="569"></div>
    </td>
</tr>
<br>

Hemos llevado a cabo un proceso de Impact Mapping dirigido al usuario llamado "cliente", quien representa a los clientes que consumen en bares. A partir de las historias de usuario generadas por nuestro equipo, hemos elaborado diferentes opciones para abordar y satisfacer sus requerimientos. 

 


Link de Miro:
 https://miro.com/welcomeonboard/Mk5wZzhZdGppbjl0Y0VZWllDeWtlZ3g3emt6R1NvTHhqdDJ5dUt6MGNoYWRORm5GTHpyNTZOa3paSVRpZ1hJeXwzMDc0NDU3MzU3MTA0ODcyOTA0fDI=?share_link_id=659519633230  

Link de Uxpressiar:
https://uxpressia.com/w/6aurq/p/428Tr/i/RkESc  

## 3.4. Product Backlog.
<table>
  <tr>
    <th><strong>#Orden </strong></th>
    <th style="text-align: justify;"><strong>User Story ID </strong></th>
    <th style="text-align: justify;"><strong>Título</strong></th>
    <th style="text-align: justify;"><strong>Descripción</strong></th>
    <th style="text-align: justify;"><strong>Story Points (1 / 2 / 3 / 5 / 8)</strong></th>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>1</strong></td>
    <td style="text-align: justify;">US1</td>
    <td style="text-align: justify;">Crear cuenta común</td>
    <td style="text-align: justify;">Como usuario, quiero poder crear una cuenta en la plataforma utilizando mi dirección de correo electrónico y una contraseña, para poder acceder a las funciones de la plataforma y personalizar mi experiencia.</td>
    <td style="text-align: justify;"> 3 </td>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>2</strong></td>
    <td style="text-align: justify;">“US2”</td>
    <td style="text-align: justify;">Crear cuenta con otras plataformas </td>
    <td style="text-align: justify;">Como usuario, quiero tener la opción de registrarme en la plataforma utilizando las credenciales de otras redes sociales o servicios (por ejemplo, Facebook o Google), para simplificar el proceso de registro y acceso</td>
    <td style="text-align: justify;"> 5 </td>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>3</strong></td>
    <td style="text-align: justify;">US3 </td>
    <td style="text-align: justify;">Entrar a la página como invitado</td>
    <td style="text-align: justify;">Como usuario, quiero tener la opción de explorar la plataforma como invitado, sin necesidad de registrarse o iniciar sesión, para conocer las características básicas antes de comprometerme con una cuenta.</td>
    <td style="text-align: justify;"> 2 </td>
  </tr>
<tr>
    <td style="text-align: justify;"><strong>4</strong></td>
    <td style="text-align: justify;">US4</td>
    <td style="text-align: justify;">Catálogo de Bares</td>
    <td style="text-align: justify;">Como usuario, quiero poder explorar un catálogo de bares disponibles en la plataforma, para conocer las opciones cercanas a mi ubicación o preferencias.</td>
    <td style="text-align: justify;"> 4 </td>
  </tr>
<tr>
    <td style="text-align: justify;"><strong>5</strong></td>
    <td style="text-align: justify;">US5</td>
    <td style="text-align: justify;">Añadir bar</td>
    <td style="text-align: justify;">Como propietario de un bar, quiero poder agregar mi bar a la plataforma proporcionando detalles como el nombre del bar, ubicación, horario de apertura y cierre, tipo de cocina, y otros detalles relevantes.</td>
    <td style="text-align: justify;"> 8 </td>
  </tr>
<tr>
    <td style="text-align: justify;"><strong>6</strong></td>
    <td style="text-align: justify;">US6</td>
    <td style="text-align: justify;">Modificar mi Bar</td>
    <td style="text-align: justify;"> Como propietario de un bar, quiero tener la capacidad de editar la información de mi bar en la plataforma, incluyendo detalles como el horario de funcionamiento, el menú, la ubicación, etc.</td>
    <td style="text-align: justify;"> 6 </td>
  </tr>
<tr>
    <td style="text-align: justify;"><strong>7</strong></td>
    <td style="text-align: justify;">US7</td>
    <td style="text-align: justify;">Eliminar mi Bar</td>
    <td style="text-align: justify;">Como propietario de un bar, quiero poder eliminar mi bar de la plataforma si ya no está en funcionamiento o si ya no deseo estar listado en ella.</td>
    <td style="text-align: justify;"> 4 </td>
  </tr>
<tr>
    <td style="text-align: justify;"><strong>8</strong></td>
    <td style="text-align: justify;">US8</td>
    <td style="text-align: justify;">Mostrar mesas disponibles</td>
    <td style="text-align: justify;">Como usuario, quiero ver la disponibilidad de mesas en los bares registrados en la plataforma para planificar mi visita.</td>
    <td style="text-align: justify;"> 3 </td>
  </tr>
<tr>
    <td style="text-align: justify;"><strong>9</strong></td>
    <td style="text-align: justify;">US9</td>
    <td style="text-align: justify;">Reservar mesas</td>
    <td style="text-align: justify;">Como usuario, quiero poder reservar una mesa en un bar seleccionado, proporcionando detalles como la fecha, hora, número de personas y preferencias específicas.
</td>
    <td style="text-align: justify;"> 7 </td>
  </tr>
<tr>
    <td style="text-align: justify;"><strong>10</strong></td>
    <td style="text-align: justify;">US10</td>
    <td style="text-align: justify;">Almacén de los productos</td>
    <td style="text-align: justify;">Como propietario de un bar, quiero gestionar un almacén de productos en la plataforma, para tener un registro de los productos disponibles en mi establecimiento.</td>
    <td style="text-align: justify;"> 5 </td>
  </tr>
<tr>
    <td style="text-align: justify;"><strong>11</strong></td>
    <td style="text-align: justify;">US11</td>
    <td style="text-align: justify;">Administrar los productos</td>
    <td style="text-align: justify;">Como propietario de un bar, quiero poder agregar, editar y eliminar productos en mi almacén, incluyendo detalles como el nombre del producto, precio, descripción y cantidad en stock.</td>
    <td style="text-align: justify;"> 6 </td>
  </tr>
</table>

# CAPÍTULO IV: PRODUCT DESIGN

## 4.1 Style Guidelines.

Nuestro producto de aplicación web que se diseñara es LoyalSips, la cual ofrece al cliente una solución tecnológica para que el problema de separar mesas en un bar o que los precios de los bares sean muy altos, en nuestra web podra reservar un espacio comodo y tambien encontrara ofertas de bebidas, un plus que tiene nuestra web es que cada vez que el cliente compre un trago se le incluiran puntos para que pueda canjear un trago cuando llegue a los puntos requeridos Para los estilos utilizados se tomará en cuenta la satisfacción del cliente y su experiencia.
Los colores que se están utilizando para nuestra solución (Landing Page y Web site) son los siguientes: <br><br>

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1149549523522289684/image.png"width="403" height="87"></div>
    </td>
  </tr>

<br>
<br>
Por otro lado Usamos el tipo de letra San Francisco.
<br>
<br>
<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1149548371288277044/image.png"width="288" height="447"></div>
    </td>
  </tr>

## 4.1.2 Web Style Guidelines.

Para el diseño de la web se establecieron los colores ya antes mencionados, Turquesa, negro y morado. El estilo de letra que se utilizará en la aplicación web es San Francisco. Para todo esto hemos tenido en cuenta que cada cliente tiene un distinto dispositivo, por esta razón hemos decidido hacer nuestra web con los principios responsive.

## 4.2. Information Architecture.

En esta seccion se enfoca en la organizacion del contenido de la website LoyalSips en buscar el 100% de satisfacion en nuestros clientes durante la navegacion de nuestra website.
A continuacion, podemos ver los topicos de Labelling Systems, Organization Systems, Seo Tags and Meta Tags, Searching Systems y Navigation Systems.

### 4.2.1. Organization Systems.

En la organizacion visual tenemos:

* Fomar jerarquica:
  Esta forma de organización se implementará en la pantalla de inicio del usuario, para
  esto la secciones de “Revervacion de mesas” y “Ofertas de bebidas” poseen una mayor jerarquía por ser de importancia para el usuario, por otro lado, “Registro de compras” tendrán una menor jerarquía en el inicio. Esta manera de organización se mantendran segmentadas.<br><br>

  <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1148313906264150197/Untitled_1.jpg?width=475&height=592"width="475" height="592"></div>
    </td>
  </tr>
<br>



* Organizacion matricial
  
  La organizacion matricial se incluira a travez de las Bedidas mas compradas y el Registro de compras.

* Esquemas de Organizacion
   
   En nuestra aplicacion habra una organizacion separada por todos los usuarios.

   En la segmentacion de los usuarios: En el apartado de las Bebidas mas compradas se organizara de acuerdo al precio del mas alto al mas bajo. Para el Registro de las compras, esta organizacion se dara cada vez que el usuario compre una bebida mediante la app asi su podra generar puntos y podra canjear una bebida gratis. Ademas el usuario tendra todo su registro guardado para que no tenga ningun confusion.



### 4.2.2. Labeling Systems.

Para el sistema de etiquetado hemos utilizado, en su mayoría, un lenguaje formal de
fácil identificación para los usuarios. Tenemos: 

<table>
  <tr>
    <th><strong>Apartados</strong></th>
    <th style="text-align: justify;"><strong>Abrir el sitio Web</strong></th>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>Login</strong></td>
    <td style="text-align: justify;">El empresario se registra como empresario y se muestra una interfaz distinta a la del usuario</td>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>Reservacion de mesas</strong></td>
    <td style="text-align: justify;">“Que satisfacción ingresar a un sitio web de manera rápida”</td>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>Ofertas de bebidas</strong></td>
    <td style="text-align: justify;">Siente satisfacción porque puede observar los clientes asociados al sitio web de forma entendible. </td>
  </tr>
    <tr>
    <td style="text-align: justify;"><strong>Bebidas mas compradas</strong></td>
    <td style="text-align: justify;">Siente satisfacción porque puede observar los clientes asociados al sitio web de forma entendible. </td>
  </tr>
    <tr>
    <td style="text-align: justify;"><strong>Registro de compras</strong></td>
    <td style="text-align: justify;">Siente satisfacción porque puede observar los clientes asociados al sitio web de forma entendible. </td>
  </tr>
</table>

## 4.2.3. SEO Tags and Meta Tags

«meta charset="UTF-8">
«meta name="Author"lang="es" content= "The Crackelets Group' «meta name="tittle" content="Evento social"»
«meta name="description"
content="Sitio web acerca de preferencia de bares">
«meta name-"application-name" content="The big fun">
ameta
name="keywords"
content="bar,party,availability,music,drinks,girls,stock,places"-
«meta name="viewport" content="*width=device-width, initial-scale=1.0">

## 4.2.4. Searching Systems.
<p> En esta sección se presentarán los sistemas de búsqueda que se implementaran en la aplicación y la página web. Al hacer uso de esos sistemas, los usuarios podrán encontrar la información que requieren de diversas maneras.</p>

<p><b>Para el sitio Web:</b></p>

* Motor de Búsqueda Eficiente: Hemos implementado un motor de búsqueda altamente eficiente en nuestro sitio web. Los usuarios pueden acceder a él desde cualquier página, ya que está ubicado de manera destacada en la parte superior.  
* Búsqueda en Tiempo Real: Utilizamos la búsqueda en tiempo real para proporcionar resultados instantáneos a medida que los usuarios escriben su consulta. Esto agiliza la experiencia de búsqueda.
*  Filtros y Categorías: Los usuarios pueden refinar sus búsquedas utilizando filtros avanzados. Pueden seleccionar la ubicación, el tipo de bar, el rango de precios y otras categorías para encontrar exactamente lo que desean.
* Resultados Relevantes: Hemos mejorado nuestros algoritmos de clasificación para garantizar que los resultados sean altamente relevantes. Los bares y ofertas más populares se muestran primero.
* Búsqueda por Voz: También hemos agregado la función de búsqueda por voz, lo que permite a los usuarios buscar simplemente hablando con su dispositivo, lo que hace que la búsqueda sea aún más fácil y conveniente.

<p><b>Para la aplicacion movil</b></p>

* Búsqueda Rápida en la App: En nuestra aplicación móvil, hemos colocado una barra de búsqueda en la parte superior de la pantalla de inicio. Los usuarios pueden acceder rápidamente a la función de búsqueda desde cualquier lugar de la aplicación. 
* Sugerencias Inteligentes: Nuestro sistema de búsqueda predictiva ofrece sugerencias inteligentes a medida que los usuarios escriben, lo que les ayuda a encontrar resultados más rápido. 
* Búsqueda por Categorías: Los usuarios pueden explorar bares por categorías como "cervecerías", "clubes nocturnos" o "happy hour". Esto facilita la búsqueda de experiencias específicas. 
* Historial y Favoritos: Hemos agregado una función de historial de búsqueda y la capacidad de marcar bares como favoritos. Esto permite a los usuarios acceder rápidamente a las búsquedas anteriores y guardar sus lugares preferidos. 
* Resultados Personalizados: A lo largo del tiempo, nuestro sistema aprende las preferencias de los usuarios y adapta los resultados de búsqueda para que sean más relevantes según su historial de búsqueda y comportamiento. 
* Notificaciones Relevantes: Los usuarios pueden configurar notificaciones de búsqueda para recibir alertas sobre nuevos bares o ofertas que coincidan con sus intereses. 
* Búsqueda sin conexión: Incluso cuando no tienen conexión a Internet, los usuarios pueden realizar búsquedas previas y ver resultados guardados en su dispositivo. Los datos se sincronizan automáticamente cuando vuelven a estar en línea. 


## 4.2.5. Navigation Systems.

<p>En el siguiente punto, nuestro equipo mostrará los sistemas de navegación implementados en TechSolutions para que los usuarios puedan manipular de manera rápida, efectiva y segura en nuestro aplicativo. </p>
<p>Para ello en el sitio web de 'LoyalSips', hemos implementado un sistema de navegación intuitivo con un menú de encabezados ubicado en la parte superior de la página principal. Cada encabezado representa una sección clave, como 'Inicio', 'Bares', 'Ofertas', 'Registro' y 'Contacto', permitiendo a los usuarios acceder de manera rápida y sencilla a la información relevante. Además, proporcionamos enlaces útiles en el pie de página para acceder a detalles adicionales como 'Política de Privacidad' y 'Términos y Condiciones' </p>
<p> En el caso del aplicativo móvil de 'LoyalSips', hemos decidido diseñar un sistema de navegación eficiente que se basa en un menú principal desplegable desde la parte superior de la pantalla. Este menú ofrece opciones esenciales, como 'Inicio', 'Buscar Bares', 'Mis Puntos', 'Ofertas' y 'Perfil', para que los usuarios accedan fácilmente a diferentes áreas de la aplicación. Además, permitimos la navegación por categorías y la aplicación de filtros para una experiencia de usuario más personalizada. Los botones de acción rápida en las páginas de detalle facilitan la toma de decisiones, y un botón de 'Volver' garantiza una navegación sin problemas.</p>

## 4.3. Landing Page UI Design.
Esta sección tendrá un enfoque sobre el diseño de nuestra Landing Page utilizando conceptos del diseño general y el diseño de la interfaz. Para el desarrollo del diseño, se utilizó el software de Figma para el desarrollo del Mock-Ups y Wireframes.

### 4.3.1. Landing Page Wireframe.
Para la elaboración de los wireframes de la Landing Page tanto en el sector de móvil como para escritorio se usaron los principios, elementos de diseño, en el que engloba la arquitectura de información y el diseño inclusivo.

Para la elaboración de los Wireframes de la Landing page, se tomó en cuenta los elementos y principios de diseño, esto se puede apreciar para la creación de formas usando los elementos de dirección y línea, las cuales lo usamos para difenciar tanto las imágenes como los componentes que forman parte del landing page.

En este caso, se puede observar los distintos elementos que se usaron para diferenciar un componente de otro, así como las fuentes de las letras, sobre todo, detalle muy importante, que los colores están en escala de grises dado que es un boceto, lo cual puede cambiar para la elaboración del Mock-up.

**Landing Page Wireframes - Desktop**

  <tr>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1155250239272398968/1.jpg?width=1032&height=671"width="" height="">
      </div>
  </tr>
<br>
  <tr>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1155251603817889832/3.jpg?width=934&height=671"width="" height="">
      </div>
  </tr>
<br>
  <tr>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1155251493444784218/2.jpg?width=934&height=671"width="" height="">
      </div>
  </tr>
<br>
  <tr>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1155257632530112542/AABOUT.jpg?width=934&height=671"width="" height="">
      </div>
  </tr>
<br>
  <tr>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1155254341305901108/9.jpg?width=934&height=671"width="" height="">
      </div>
  </tr>
<br>


El link del [diseño de escritorio](https://www.figma.com/file/xDKLEzeKlPV6A8uBfSIIbC/Sanity-Sketching-Kit-(Community)?type=design&node-id=397%3A3611&mode=design&t=jL9xPnI96j5KRImq-1)



<br>

**Landing Page Wireframes - Mobile**

<tr>
  <div align='center'>
    <img src="https://media.discordapp.net/attachments/1145898392631918606/1155314365663293440/Section_1.png">
  </div>
</tr>
<br>


Link del [Diseño Movil](https://www.figma.com/file/N8EmdAUWapHigf4Lk8sGHr/Web-Application-Wireframes?type=design&node-id=0%3A1&mode=design&t=DfFWWAqT7hgXSXLE-1) 



### 4.3.2. Landing Page Mock-up.
Para la elaboración del Mock-up del Landing page tanto para el apartado de escritorio como para móvil se usaron principios, elementos de diseño, diseño inclusivo y arquitectura de información que se planteó en puntos anteriores.

**Landing Page Desktop Mock-up.**

  <tr>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1155322587421888532/desktop-mock-up.png?">
      </div>
  </tr>

<br>

Link del [figma de escritorio](https://www.figma.com/file/WvBHU5rWPbgabHex3Er6jj/Landing-Page---LoyalSips?type=design&node-id=0%3A1&mode=design&t=E225PHq1IOJ3VIcx-1)

---

**Landing Page Mobile Mock-up.**

Segmento Empresarial:

 <tr>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1155323529294778378/empresa-mobile-mock-up.png?">
      </div>
  </tr>
  <br>

  Segmento Cliente:

   <tr>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1155323548945092650/cliente-mobile-mock-up.png?">
      </div>
    </td>
  </tr>
  <br>

Link del [figma móvil](https://www.figma.com/file/T8vhVw6cu3LuuV1K3KXdwR/Section-Mobile-Mock-up?type=design&node-id=0%3A1&mode=design&t=263fweJAWpHGIleT-1) 

Para su diseño se aplicaron los 5 principios del diseño:

* Balance: Se equilibraron las imágenes grandes con texto a su costado para una
mejor relación para la vista.

* Contraste: Para contrastar secciones con fondos de color claros que en nuestro caso sería el turquesa y morado, utilizamos el color negro para una mejor diferencia entre ellos.

* Alineación: Para este principio alineamos nuestros elementos a la izquierda y a la derecha así intercalando para que la vista no sea de una misma dirección, todos los elementos están dentro de pequeñas secciones.

* Proximidad: Este principio se aplicó en la creación de botones, ya que estas tienen una cierta elevación para diferenciar que están flotando.

* Espacio: Los elementos de nuestro diseño no están todos juntos, ellos tienen un espacio establecido para cada sección y no se alborote todos en una sola parte, de esta forma brindar un sitio limpio y entendible para el usuario.



## 4.4. Web Applications UX/UI Design.

En esta sección, presentaré una propuesta visual y de interacción para las aplicaciones que forman parte de la experiencia del usuario en nuestros productos digitales. El objetivo es crear una experiencia atractiva, funcional y eficiente que satisfaga las necesidades de nuestros usuarios y refleje la identidad de nuestra marca.

### 4.4.1. Web Applications Wireframes.

Se muestra el diseño visual y la interacción que poseen los wireframes en nuestro proyecto digital.

A continuación, se muestra el diseño visual y la interacción que poseen los wireframes en nuestro proyecto digital.

<div align='center'>

<b>Sector del Empresarial:</b>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150000600885501982/Imagen15.jpg?width=1119&height=625"width="700" height="">
    </td>
  </tr>

<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150000468148367411/Imagen3.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>

<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150000930893332480/Imagen4.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>

<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150001432314007653/Imagen5.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150001605953982494/Imagen6.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150001849252974622/Imagen7.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150001990273867957/Imagen8.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150002091054608385/Imagen9.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150002191118110790/Imagen10.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150002275113242654/Imagen11.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150002536674238564/Imagen12.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150002634703519744/Imagen13.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150002743549894757/Imagen14.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>
<b>Sector del cliente:</b>
<br>
<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150002903013150791/Imagen16.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150002973276114964/Imagen17.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150003129300045884/Imagen18.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>


 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150003223688654848/Imagen19.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150003328797921372/Imagen20.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>


<br>

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1150003424256065607/Imagen21.jpg?width=1116&height=625"width="700" height="">
    </td>
  </tr>
</div>

---


### 4.4.2. Web Applications Wireflow Diagrams.
En este apartado se mostrará los flujos de navegación entre pantallas de nuestra aplicación que visualizará tanto el segmento del empresario como el sector del cliente.

**Segmento objetivo Empresarial:**

**User Goal:** Como soy empresario, quiero elegir el sector de empresa y poder registrarme como empresario.

<div align='center'>
 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149817454575493150/Captura_de_pantalla_2023-09-08_055016.png">
    </td>
  </tr>

<br><br>

**User Goal:** Como empresario, quiero iniciar sesión con una cuenta previamente creada.

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149818179695165563/Captura_de_pantalla_2023-09-08_055353.png">
    </td>
  </tr>
  <br><br>

**User Goal:** Como empresario, ver mis datos en la aplicación.
 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149818555605454919/Captura_de_pantalla_2023-09-08_055535.png">
    </td>
  </tr>
  <br><br>

**User Goal:** Como empresario, deseo buscar al cliente con un respectivo puntaje.
 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149818876222255214/Captura_de_pantalla_2023-09-08_055850.png">
    </td>
  </tr>
  <br><br>

**User Goal:** Como empresario, deseo registrar un producto en el sistema para poder llevar un control del stock.
 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149818771037491200/Captura_de_pantalla_2023-09-08_060509.png">
    </td>
  </tr>
  <br><br>

**User Goal:** Como empresario, deseo buscar un producto en el sistema para poder saber el stock y llevar un control seguro.
 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149819610011533372/Captura_de_pantalla_2023-09-08_060832.png">
    </td>
  </tr>
</div>  
<br>

Link para visualizar los [wireframes diagrams](https://overflow.io/s/O6IYMWFP) 

---

### Segmento objetivo Usuario:
**User Goal:** Como soy cliente consumidor, quiero elegir el sector de cliente y poder registrarme como cliente.

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149820520892747868/Captura_de_pantalla_2023-09-08_061524.png">
      </div>
    </td>
  </tr>
  <br><br>

**User Goal:** Como cliente, quiero iniciar sesión con una cuenta previamente creada.

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149820740019949578/Captura_de_pantalla_2023-09-08_062053.png">
      </div>
    </td>
  </tr>
  <br><br>

**User Goal:** Como cliente, deseo ver mis datos en la aplicación.

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149820940545437706/Captura_de_pantalla_2023-09-08_062432.png">
      </div>
    </td>
  </tr>
  <br><br>

**User Goal:** Como cliente, deseo elegir en que bar me encuentro para conocer sus ofertas y mi puntaje.

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149821221635112970/Captura_de_pantalla_2023-09-08_063007.png">
      </div>
    </td>
  </tr>
  <br><br>

**User Goal:** Como cliente, deseo ver qué productos puedo canjear con respecto a mi puntaje acumulado.

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149821517945917500/Captura_de_pantalla_2023-09-08_063350.png">
      </div>
    </td>
  </tr>
  <br><br>

**User Goal:** Como cliente, quiero elegir un producto que me guste para canjearlo.

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149821817746362549/Captura_de_pantalla_2023-09-08_064205.png">
      </div>
    </td>
  </tr>
  <br><br>


**User Goal:** Como cliente, deseo poder ver las ofertas de la semana del bar.

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149822088157339790/Captura_de_pantalla_2023-09-08_064743.png">
      </div>
    </td>
  </tr>
  <br><br>

Link para visualizar los [wireframes diagrams](https://overflow.io/s/O6IYMWFP)

---

### 4.4.3. Web Applications Mock-ups.
Para la implementación de los Mock-ups de las aplicaciones web, se siguieron los principios de diseño, elementos de diseño, diseño inclusivo y arquitectura de información que se planteó en puntos anteriores. El cual implican los siguientes aspectos:

- **Sencillez:** Se utilizó un diseño simple y limpio para que el usuario pueda navegar fácilmente por la aplicación.

- **Consistencia:** Se utilizó un diseño consistente en para mejorar la experiencia de usuario. Esto ayuda a los usuarios a identificar elementos familiares y entender mejor la jerarquía de la información.

- **Jerarquía Visual:** Se utilizó un diseño que permite a los usuarios identificar fácilmente los elementos más importantes de la aplicación. Esto ayuda a los usuarios a comprender mejor la información y a tomar decisiones más rápidas.

- **Feedback:** Se utilizó un diseño que proporciona comentarios visuales a los usuarios para que sepan que sus acciones se han realizado correctamente. Esto ayuda a los usuarios a comprender mejor el sistema y a evitar errores.

- **Diseño Inclusivo:** Se utilizó un diseño que permite a los usuarios personalizar la aplicación según sus necesidades. Esto ayuda a los usuarios a sentirse más cómodos y a disfrutar de una experiencia de usuario más agradable.

- **Accesibilidad:** Se utilizó un diseño que permite a los usuarios acceder a la aplicación desde cualquier dispositivo. Esto ayuda a los usuarios a utilizar la aplicación en cualquier momento y lugar.



Para el **sector Empresarial** se realizó el diseño que se muestra a continuación:


 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149822816519196702/Captura_de_pantalla_2023-09-08_070404.png">
      </div>
    </td>
  </tr>
  <br><br>

  ***A continuación, se presenta el registro para EMPRESARIOS y el código de verificación.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149823111554928670/Captura_de_pantalla_2023-09-08_070707.png"></div>
    </td>
  </tr>
  <br><br>

***A continuación, se muestra la edición del perfil del empresario.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149823420104704181/Captura_de_pantalla_2023-09-08_071758.png">
      </div>
    </td>
  </tr>
  <br><br>


***A continuación, se muestra el sector principal de la aplicación para el sector empresarial.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149823995579990066/Captura_de_pantalla_2023-09-08_164949.png"></div>
    </td>
  </tr>
  <br><br>

***A continuación, se muestra el perfil del empresario.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149824239642349708/Captura_de_pantalla_2023-09-08_072014.png"></div>
    </td>
  </tr>
  <br><br>

***A continuación, se muestra la visualización de clientes con su respectivo puntaje y los productos disponibles para el cliente.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149824395406233640/Captura_de_pantalla_2023-09-08_072222.png"></div>
    </td>
  </tr>
  <br><br>

***A continuación, se muestra el producto elegido por el usuario que desea canjear.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149824550851321856/Captura_de_pantalla_2023-09-08_072353.png"></div>
    </td>
  </tr>
  <br><br>


***A continuación, se muestra el proceso de registrar un producto en la app móvil.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149824704320909482/Captura_de_pantalla_2023-09-08_072607.png"></div>
    </td>
  </tr>
  <br><br>

***A continuación, se muestra el proceso de buscar un producto en el inventario y conocer el stock del producto buscado.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149824887649747054/Captura_de_pantalla_2023-09-08_072804.png"></div>
    </td>
  </tr>

---
Para el sector del **Cliente** se realizó el diseño que se muestra a continuación:

***A continuación, se muestra el registro para CLIENTES, con el respectivo código de verificación.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149825424222847066/Captura_de_pantalla_2023-09-08_073410.png"></div>
    </td>
  </tr>
  <br><br>


***A continuación, se muestra la edición del perfil del cliente.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149825569119272970/Captura_de_pantalla_2023-09-08_073610.png"></div>
    </td>
  </tr>
  <br><br>


***A continuación, se muestra el sector principal de la aplicación para el sector del cliente.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149825726229512343/Captura_de_pantalla_2023-09-08_073759.png"></div>
    </td>
  </tr>
  <br><br>

***A continuación, se muestra el perfil del cliente.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149826008367771678/Captura_de_pantalla_2023-09-08_073849.png"></div>
    </td>
  </tr>
  <br><br>

  ***A continuación, se muestra la visualización de el apartado principal del usuario o cliente, en el que puede consultar su puntaje, realizar canjes y ver productos en oferta del bar en el que se encuentre.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149826364703256627/Captura_de_pantalla_2023-09-08_074057.png"></div>
    </td>
  </tr>
  <br><br>

***A continuación, se presenta la sección de canjear productos, en el que el usuario puede ver qué productos están disponibles de acuerdo a su puntaje.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149826517245906954/Captura_de_pantalla_2023-09-08_074233.png"></div>
    </td>
  </tr>
  <br><br>

***A continuación, se presenta el proceso de elección de un producto por el cliente y el proceso de canje del producto elegido por el cliente.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149826780568498216/Captura_de_pantalla_2023-09-08_074435.png"></div>
    </td>
  </tr>
  <br><br>

***A continuación, se muestra la sección de ofertas de la semana en la interfaz del usuario, para que el cliente tenga la libertad de elegir el producto de su preferencia.***

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149827250842259530/Captura_de_pantalla_2023-09-08_074806.png"></div>
    </td>
  </tr>

----

### 4.4.4. Web Applications User Flow Diagrams.
En esta sección se muestra los user flows diagrams de los Mock-ups previamente creados anteriormente. A continuación, se mostrarán los flujos de la aplicación para el mayor entendimiento de todos.

Link del [User Flow diagrams](https://overflow.io/s/RV6NU7NK) 

**Segmento objetivo Empresarios:**

***User Goal: Como soy empresario, quiero elegir el sector de empresa y poder registrarme como empresario.***

Explicación: El usuario empresario ingresa a la aplicación y elige el sector de empresa, luego se registra como empresario y se le envía un código de verificación para poder ingresar a la aplicación.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149828110045429851/Captura_de_pantalla_2023-09-08_081316.png"></div>
    </td>
  </tr>
  <br><br>

***User Goal: Como empresario, quiero iniciar sesión con una cuenta previamente creada.***

Explicación: En caso el usuario ya se haya registrado a nuestro aplicativo, el usuario empresario puede iniciar sesión con su cuenta previamente creada dando click en el botón de iniciar sesión, colocando su correo y contraseña.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149828260415422474/Captura_de_pantalla_2023-09-08_081915.png"></div>
    </td>
  </tr>
  <br><br>

***User Goal: Como empresario, ver mis datos en la aplicación.***

Explicación: Entendemos que el usuario empresario desea ver sus datos en la aplicación, por ello, se muestra el nombre del bar, la descripción que el empresario lo haya registrado, la ubicación del bar y el horario de atención.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149828409493557329/Captura_de_pantalla_2023-09-08_082048.png"></div>
    </td>
  </tr>
  <br><br>

***User Goal: Como empresario, deseo buscar al cliente con un respectivo puntaje.***

Explicación: El usuario empresario deberá hacer click en el boton de ver puntos de los clientes, seguidamente, se mostrará una ventana en el que el usuario empresario podrá rellenar los datos de los clientes que desea buscar, por ejemplo, el nombre del cliente, el apellido y el DNI, al hacer click en buscar cliente, se muestra el cliente con su respectivo puntaje. Además, se muestran los productos disponibles que están para dicho cliente, recordemos que los productos disponibles pueden variar de acuerdo a la cantidad de puntos de cada cliente.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149828670345723974/Captura_de_pantalla_2023-09-08_082603.png"></div>
    </td>
  </tr>
  <br><br>


***User Goal: Como empresario, deseo registrar un producto en el sistema para poder llevar un control del stock.***

Explicación: Para registrar un producto, el usuario deberá hacer click en el botón de registrar producto, que se encuentra en la parte inferior en el sector de Control de inventario, una vez hecho esto, se mostrará una ventana en la que el usuario deberá rellenar los datos del producto, como por ejemplo, el código del producto, el nombre, la categoría, en caso es Ron, Vino o Whisky, el precio y la cantidad añadida. Al hacer click en registrar producto, se mostrará el producto registrado en el sistema.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149829025880080424/Captura_de_pantalla_2023-09-08_083350.png"></div>
    </td>
  </tr>
  <br><br>

***User Goal: Como empresario, deseo buscar un producto en el sistema para poder saber el stock y llevar un control seguro.***

Explicación: Para buscar un producto, el usuario deberá hacer click en el botón de buscar producto, que se encuentra en la parte inferior en el sector de Control de inventario, una vez hecho esto, se mostrará una ventana en la que el usuario deberá rellenar los datos del producto, como por ejemplo, el código del producto, el nombre, la categoría, en caso es Ron, Vino o Whisky, el precio y la cantidad añadida. Al hacer click en buscar producto, se mostrará el producto buscado, con la cantidad en stock, de modo que ayude a llevar un meor control de los productos que se encuentran en el bar.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149829280671481936/Captura_de_pantalla_2023-09-08_083841.png"></div>
    </td>
  </tr>
  <br><br>

**Segmento objetivo Usuarios:**

Link para visualizar los [Web Application User Flow diagrams.](https://overflow.io/s/T9LJPXN7)

***User Goal: Como soy cliente consumidor, quiero elegir el sector de cliente y poder registrarme como cliente.***

Explicación: Si el usuario es cliente de un bar, ingresa a la aplicación y elige el sector de cliente, luego se registra como cliente y se le envía un código de verificación para poder ingresar a la aplicación.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149830044420677802/Captura_de_pantalla_2023-09-08_085230.png"></div>
    </td>
  </tr>
  <br><br>

***User Goal: Como cliente, quiero iniciar sesión con una cuenta previamente creada.***

Explicación: En caso el usuario ya se haya registrado a nuestro aplicativo, el usuario cliente puede iniciar sesión con su cuenta previamente creada dando click en el botón de iniciar sesión, colocando su correo y contraseña, lo que llevará a la pantalla principal del usuario o cliente.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149830239761997968/Captura_de_pantalla_2023-09-08_085338.png"></div>
    </td>
  </tr>
  <br><br>

***User Goal: Como cliente, deseo ver mis datos en la aplicación.***

Explicación: Entendemos que el usuario cliente desea ver sus datos en la aplicación, por ello, se muestra el nombre del cliente, el apellido, fecha de nacimiento, el género del cliente y el número de celular. Si el usuario desea cerrar sesión, puede hacerlo dando click en el botón de cerrar sesión, lo que lo llevará a la pantalla de inicio de sesión.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149830398713532426/Captura_de_pantalla_2023-09-08_085432.png"></div>
    </td>
  </tr>
  <br><br>
  
***User Goal: Como cliente, deseo elegir en que bar me encuentro para conocer sus ofertas y mi puntaje.***

Explicación: Se mostrará la pantalla principal para que el usuario tenga la libertad de elegir en qué bar se encuentra, en caso seleccione un respectivo bar, lo lleva a otra sección en el que el usuario podrá ver sus puntos y las ofertas de la semana del bar en el que se encuentra. Además, se muestra un botón de canjear productos, en el que el usuario puede canjear los productos que desee de acuerdo a su puntaje acumulado y un boron de ver productos en oferta, en el que podrá ver las ofertas de la semana. En caso el usuario desee cambiar de bar, puede hacerlo dando click en el boton regresar, lo que lo llevará a la pantalla principal para que el usuario pueda elegir otro bar en el que se encuentre.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149830572672299048/Captura_de_pantalla_2023-09-08_085716.png"></div>
    </td>
  </tr>
  <br><br>

***User Goal: Como cliente, deseo ver qué productos puedo canjear con respecto a mi puntaje acumulado.***

Explicación: Se muestra la pantalla principal del usuario en el bar respectivo en el que se encuentra, también se muestra una barra, que representa el puntaje acumulado que va teniendo el usuario cliente, en caso el usuario desee canjear un producto, deberá hacer click en el botón de canjear productos, lo que lo llevará a la sección de canjear productos, en el que el usuario podrá ver los productos que puede canjear con respecto a su puntaje acumulado.


<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149830844194766988/Captura_de_pantalla_2023-09-08_085943.png"></div>
    </td>
  </tr>
  <br><br>

***User Goal: Como cliente, quiero elegir un producto que me guste para canjearlo.***

Explicación: Cuando el cliente se encuentre en la sección canjear productos, se podrá ver los productos que puede canjear con respecto a su puntaje acumulado. Para canjear un producto, deberá hacer click en el producto de su agrado, seguidamente se mostrará el producto con una imagen grande y sus detalles, seguidamente se muestran mensajes de alerta el cual explican al usuario que deberá acercarse al personal del bar para verificar que el canje del producto sea válido, una vez verificado el canje, el usuario puede reclamar su producto, y el puntaje acumulado se reducirá de acuerdo al producto canjeado. Una vez el producto sea canjeado, se mostrará la sección principal del aplicativo.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149831496916541470/Captura_de_pantalla_2023-09-08_090557.png"></div>
    </td>
  </tr>
  <br><br>

***User Goal: Como cliente, deseo poder ver las ofertas de la semana del bar.***

Explicación: Para ver las ofertas, se mostrará en la pantalla principal, un botón de ver productos en oferta, en el que el usuario podrá ver las ofertas de la semana del bar en el que se encuentra, al hacer click en el botón de ver productos en oferta, se dirigirá a una sección en el que se muestran los productos en ofertas con su respectivo descuento que el bar ofrece.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149831610284376064/Captura_de_pantalla_2023-09-08_090645.png"></div>
    </td>
  </tr>
  <br><br>

---

## 4.5. Web Applications Prototyping.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639922271363083/1149832165748654200/Captura_de_pantalla_2023-09-08_172204.png"></div>
    </td>
  </tr><br>

Link del [prototipo en Figma](https://www.figma.com/proto/vE2mliJXJbycAVSDC0Tn3g/Landing-Page---Movil?page-id=0%3A1&type=design&node-id=18-31&viewport=482%2C573%2C0.23&t=fF9wq2WzqPvgenwU-1&scaling=scale-down&starting-point-node-id=18%3A31&mode=design)   

Link del video de explicación del [prototipo en Figma](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112936_upc_edu_pe/ETCf0pqiD-dAisJ0yxKBQSYBlSeYgXx3HWFYcxpUxUMSAw?e=eoQ4LJ)

## 4.6. Domain-Driven Software Architecture.  

En esta seccion, se presentarán los diagramas de arquitectura de software desarrollados para nuestra aplicacion web. Hemos considerado el enfoque Domain-Driven, de tal forma podemos reflejar la estructura del diseño empleado para nuestro proyecto. 

 

### 4.6.1. Software Architecture Context Diagram.  

En la seccion de Software Architecture Context Diagram, es una representación visual que muestra cómo un sistema de software interactúa con su entorno. Este diagrama ayuda a comprender las relaciones y dependencias del sistema en su entorno, siendo una herramienta clave en el diseño de la arquitectura de software. 

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149676634962665502/structurizr-SystemContext-001.png?width=743&height=423"width="675" height="592"></div>
    </td>
  </tr>

### 4.6.2. Software Architecture Container Diagrams. 

Sobre Software Architecture Container Diagrams, son representaciones visuales que muestran cómo un sistema de software se divide en contenedores, que son unidades lógicas de alto nivel que contienen componentes y servicios relacionados. Nos premite  comprender la estructura general de un sistema y cómo interactúan sus partes principales, siendo una parte importante de la documentación de la arquitectura de software. 

 <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149676634664882297/structurizr-Container-001_1.png?width=651&height=423"width="675" height="592"></div>
    </td>
  </tr>

### 4.6.3. Software Architecture Components Diagrams.  

Con respecto a Software Architecture Components Diagrams, son representaciones visuales que ilustran cómo los sistemas de software se componen en diferentes módulos o componentes, mostrando las relaciones y dependencias entre ellos. 

Bussiness Logic:  

  <tr>
    <td style="border: 1px solid #dddddd; padding: 8GITpx;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149676634367074404/structurizr-Component-001.png?width=532&height=423"width="475" height="592"></div>
    </td>
  </tr>


https://github.com/Alarsandro/Point-bar-c4/blob/main/point-bar.dsl  


## 4.7.1. Class Diagrams.

<tr>
    <td>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149584168917946368/diagrama_de_clases.JPG">
    </td></div>
</tr>

## 4.7.2. Class Dictionary.

**Cliente Fidelizado - Bar (Agregación)**: La relación entre "Cliente Fidelizado" y "Bar" podría ser una relación de agregación, ya que un cliente fidelizado está asociado a un bar en particular, y un bar puede tener varios clientes fidelizados. Esto significa que la clase "Bar" sería el "todo" y la clase "Cliente Fidelizado" sería una de las "partes".
<tr>
    <td>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149584862387372102/1.JPG">
    </td></div>
</tr>

**Bar - Producto (Agregación)**: La relación entre "Bar" y "Producto" también podría ser una relación de agregación, ya que un bar contiene una lista de productos en su stock, y los productos son partes de ese bar.

<tr>
    <td>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149586435335262218/2.JPG">
    </td></div>
</tr>

**Producto - Producto de Venta (Dependencia)**: La relación entre "Producto" y "Producto de Venta" es una dependencia, ya que la clase "Producto de Venta" implementa una interfaz que permite calcular el precio de venta de un producto. La clase "Producto de Venta" depende de la clase "Producto" para realizar este cálculo, pero no existe una relación de agregación o composición directa entre ellas.

<tr>
    <td>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149587448423260170/3.JPG">
    </td></div>
</tr>

**Venta - Cliente Fidelizado (Dependencia)**: La relación entre "Venta" y "Cliente Fidelizado" es una dependencia, ya que una venta está asociada a un cliente fidelizado. La venta depende del cliente fidelizado para registrar quién realizó la compra, pero no hay una relación de agregación o composición entre ellas.

<tr>
    <td>
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149588690654478397/4.JPG">
    </td></div>
</tr>


## 4.8 Database Design

El diseño de bases de datos para el sistema de gestión de datos de "LOYALSIPS" implica la creación de una estructura de base de datos que permita almacenar y gestionar eficientemente información relacionada con los bares, como menús, inventarios, pedidos, clientes y boletas. Esto implica la definición de tablas que representen entidades clave, como Tablas, Reservas, Mesas, Bar, Orden, Cliente, Boleta, Bebidas y Almacén, y la creación de relaciones entre estas tablas para reflejar cómo se relacionan los datos.

En el diseño de bases de datos para bares, se deben considerar elementos como las claves primarias y foráneas para mantener la integridad de los datos, las restricciones de base de datos para garantizar la consistencia y la normalización de datos para evitar la duplicación innecesaria de información.

### 4.8.1. Database Diagram
<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/969784880017842216/1149495852549799956/Diagrama_de_Clases_Point_Bar-2023-09-07_19-00.png?width= " height=auto></div>
    </td>
</tr>

---

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management. -  

### 5.1.1. Software Development Environment Configuration. 

En la sección de Software Development Environment Configuration, implica la presentación de conjunto de herramientas, software y configuraciones necesarios para que los desarrolladores trabajen eficientemente en la creación, prueba y mantenimiento de software. Además. esto incluye la instalación de herramientas de desarrollo, configuración de sistemas operativos, gestión de dependencias, configuración de bases de datos y más. Garantiza que los desarrolladores tengan un entorno adecuado para sus proyectos y es fundamental para un desarrollo de software efectivo. Para ello, dividimos en los siguientes puntos: 

 

 - Project Mangement 

- Requirements Management 

- Product UX/UI Design 

- Software Development 

- Software Testing 

- Software Documentation 


Además, es necesario mencionar la clasificacion de estos, ya que pueden ser elementos de las secciones como "Ruta de Referencia" o "Ruta de Descarga".
 

### - Project Mangement 

Project Mangement tiene como objetivo en la gestión de proyectos, mejorar los procesos y tambien, el entorno para obtener los resultados requeridos. 

Para el proyecto no hemos utilizado un software que gestione el proyecto. 

 

### - Requirements Management 

Requirements Management implica la recopilación, documentación y seguimiento de los requisitos del software. 

Para el proyecto no hemos utilizado un software que gestione el proyecto. 

 

### - Product UX/UI Design 

Es la fase que diseña la apariencia y la interacción del software para garantizar una experiencia de usuario atractiva y eficiente. 

Uxpressia es una herramienta eficiente que nos ha ayudado en el diseño del Impact Mapping de nuestro proyecto. Uxpressia: https://uxpressia.com/  

Para ello, hemos utilizado Miro, el cual nos ayuda a diseñar la estructura de la interfaz para nuestro proyecto. Miro: https://miro.com/app/dashboard/  

Para este propósito, hemos empleado Figma, una herramienta que nos permite diseñar la estructura de la interfaz de nuestro proyecto de manera efectiva. Figma: https://www.figma.com/ 

Lucid Chart es una herramienta eficiente con respecto al desarrollo del diseño de modelados. Lucid Chart : https://www.lucidchart.com/  

 

### - Software Development 

Con respecto a Software Development, el cual nos permite tener un entorno adecuado para desarrollar el proyecto en código. 

Para el desarrollo de continuo de nuestro equipo y mantener los avances del proyecto utilizamos Github. Github: https://github.com/  

Visual Studio Code es un editor de código gratuito y altamente extensible de Microsoft, multiplataforma, con depuración integrada y soporte para múltiples lenguajes de programación. Visual Studio Code: https://code.visualstudio.com/  

WebStorm es un IDE  de JetBrains especializado en desarrollo web. Ofrece herramientas avanzadas para escribir, depurar y administrar proyectos web en lenguajes como JavaScript, HTML y CSS. WebStorm: https://www.jetbrains.com/webstorm/promo/?source=google&medium=cpc&campaign=9641686239&term=webstorm&content=523833970754&gad=1&gclid=CjwKCAjwo9unBhBTEiwAipC115R9P8mt3UWuHjEycEIKW2WnOgU7I5V0Wq2Xg3PHMHUtD6VGXCwBkxoCuZgQAvD_BwE  

El lenguaje de programacion JavaScript implica utilizar frameworks, bibliotecas y herramientas para crear aplicaciones web. JavaScript: https://support.microsoft.com/es-es/topic/c%C3%B3mo-habilitar-javascript-en-windows-88d27b37-6484-7fc0-17df-872f65168279  

CSS, da estilo y diseño a páginas web, controlando colores, fuentes, márgenes y la apariencia de elementos HTML para mejorar la presentación visual. CSS: https://developer.mozilla.org/es/docs/Web/CSS  

HTML es el lenguaje de marcado utilizado para crear y estructurar contenido en la web, definiendo elementos y su función en una página, como títulos, párrafos e imágenes. HTML: https://developer.mozilla.org/es/docs/Web/HTML  

 

### - Software Testing 

Software Testing es la fase del desarrollo de software en la que se realizan pruebas exhaustivas para identificar y corregir errores, asegurando que la aplicación funcione correctamente y cumpla con los requisitos. 

En nuestro proyecto no hemos utilizado este tipo de herramienta. 

### - Software Documentation 

Es el mantenimiento de documentos que describen la estructura y cual es el uso del software. Esto incluye manuales de usuario, documentación técnica y guías para desarrolladores.  

Para ello, tenemos la misma documentación actual que explica como funciona. 


### 5.1.2. Source Code Management.
Para la siguiene sección, Source Code Management nos hace referencia a la funcion de seguimiento de modificaciones que los integrantes del equipo ejerce durante el desarollo del proyecto hasta su conclusion de este mismo. Para ello, cabe mencionar la importacia de un repositorio o sistema  de control de versiones el cual es Github. 

Landing Page,  

Web Services,  

Frontend Web Applications. 

### Gitflow 

Es modelo para la creación de ramas en Git, el cual cumple una función importante el desarrollo del proyecto. Mediante un control de versiones ultilizamos las ramas. Una muestra en imagen de lo mencionado para entender mejor. 
<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://expressus.io/uploads/beautiful-gitflow-workflow-diagram.png" height="500">
    </td></div>
</tr>
Entonces, al tener en cuenta el desarrollo del trabajo manteniendo un control de versiones con Gitflow 

 

La rama principal, conocida como "Master" o "Principal", es la base desde la cual se derivan y combinan todas las demás ramas. Contiene la versión más reciente y las versiones anteriores creadas por los desarrolladores, y sirve como el registro oficial de las publicaciones históricas. 

La rama "Develop" se crea a partir de la rama principal, Main y contiene todas las características estables. A través de esta rama, el equipo puede integrar nuevas funciones. 

Las ramas de soporte, a diferencia de las principales, tienen una vida útil limitada y se eliminan cuando se fusionan con sus ramas principales correspondientes. 

La rama "Feature" se deriva de "Develop" y se fusiona de nuevo en ella. Se utiliza para desarrollar nuevas funciones que se integrarán en una versión futura. Esta rama existe mientras se está desarrollando la función, y cuando se completa, se fusiona nuevamente con "Develop". 

 

 

**Convenciones para nombrar las ramas de características:** 

- Rama de característica: feature/nombre 

Ejemplos: 

 feature/Chapter1-StartupProfile, 

feature/TS- 

 

**Conventional Commits (Compromisos Convencionales):** 

Los compromisos (commits) deben tener la siguiente estructura: 

<tipo>[ámbito opcional]: <descripción> 

[cuerpo opcional] 

[notas de pie opcionales] 

Es importante destacar que todo debe estar en minúsculas. 

  

**Tipos de compromisos (commits):** 

- feat: Cuando se agrega una nueva característica. 

- fix: Cuando se corrige un error. 

   - `build`: Aplicado cuando se afectan componentes de compilación como herramientas, dependencias o la versión del proyecto. 

   - `chore`: Para modificaciones internas o privadas del código. 

   - `docs`: Referente a cambios en la documentación. 

   - `refactor`: Utilizado cuando se reescribe o reestructura el código sin cambiar su comportamiento. 

   - `perf`: Relacionado con cambios que mejoran el rendimiento. 

   - `style`: En caso de cambios que solo afectan el estilo del código (espacios en blanco, formato, etc.). 

   - `test`: Indicado para la adición de pruebas. 

  

- **Ámbito (Scope) (opcional)**: Proporciona información contextual adicional. Es recomendable, pero no obligatorio, para hacer el compromiso más específico. 

  

- **Descripción**: Parte obligatoria del formato del compromiso. Debe utilizar un enfoque imperativo y no escribir en mayúsculas. 

  

- **Cuerpo (Body) (opcional)**: Proporciona información adicional sobre la motivación del cambio y se usa para contrastarlo con el comportamiento anterior. Es opcional y debe seguir un enfoque imperativo. Ideal para mencionar identificadores de problemas y relaciones. 

  

- **Notas de pie (Footers) (opcional)**: Pueden contener información sobre cambios importantes, como referencias a problemas por su ID o detalles sobre cambios que rompen la compatibilidad (BREAKING CHANGES). Esta sección es opcional. 

  

**Ejemplos de compromisos siguiendo estas convenciones:** 

  

1. `feat(welcome): agregar sección de bienvenida` 

2. `build(release): aumentar la versión a 1.0.0` 

3. style: remove empty line 

4. feat(sign up): add the button to sign up 

5. feat!: send an email to the costumer when product is shipped 

6. feat: remove ticket listendpoint 

***refers to JIRA-1337*** 

**BREAKING CHANGES:** *ticket enpoints no longer supports list all entites.*

Asimismo, como ya se ha mencionado, la gestión de nuestro código fuente se realizará a través de GitHub. El IDE utilizado, en este caso Android Studio, deberá vincularse directamente con el repositorio creado por la empresa, Digitalholics. De esta manera, cada commit que realice un participante será subido y cargado directamente al GitHub de la organización. A continuación, se indicarán las pautas para realizar el proceso de vinculación de manera correcta: 

Activar el control de versiones del IDE 

Dado que se empleará GitHub para esta gestión, la opción que deberá estar marcada o seleccionada debe ser una que señale que el sistema de control se dará mediante Git. Para realizar esto, debe dirigirse a la pestaña de VCS' dentro de Android Studio. Después, seleccionar la opción de 'Enable Version Control Integration'. 

Con respecto a los conventional commits de nuestro proyecto, como grupo para desarrollar el presente trabajo hemos trabajado de la siguiente forma con respecto a la documentación: 

**Iniciamos creando una copia en nuestro repositorio**

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149698952137027584/image.png?width=467&height=193" height="100"></div>
    </td>
</tr>

<br>

**Es necesario utilizar el enlace de nuestro repositorio actual para nuestro trabajo.** 


<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149699170643492955/image.png?width=374&height=161" height="100"></div>
    </td>
</tr>

<br>

**En el entorno de trabajo para continuar con el proyecto, aplicamos los siguientes comandos:** 

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149699233176367124/image.png?width=400&height=78" height="100"></div>
    </td>
</tr>

<br>

**Para el desarrollo de los nuevos branches, hemos utilizado la siguiente nomenclatura para tener control e idea de lo que se desarrolla.**  



<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149699293695983626/image.png?width=408&height=64" height="100"></div>
    </td>
</tr>

<br>

**Despues, agregamos en el archivo MD todo los cambios que desarrollamos y así utilizar los siguientes comandos:** 

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149699329884438558/image.png?width=339&height=95" height="100"></div>
    </td>
</tr>

<br>

**Una vez utilizado el comando y colocando la descripción del trabajo, guardamos en la nueva rama.** 

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149699369642238194/image.png?width=471&height=151" height="100"></div>
    </td>
</tr>

<br>

**Verificamos y hacemos pull a la rama develop.** 

**Aprobamos y unimos los cambios.**
<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149699406052991036/image.png?width=474&height=179" height="100"></div>
    </td>
</tr>
<br><br>

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149699443285839954/image.png?width=474&height=278" height="100"></div>
    </td>
</tr>
<br><br>

**Es necesario para mantener un orden para cada rama creada, borrarla despues de utilizarla.** 

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149699471953907792/image.png?width=414&height=45" height="50"></div>
    </td>
</tr>
<br><br>

**Es asi como nosotros verificamos el cambio en la linea de trabajo:**

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
    <div align='center'>
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149699509165756458/image.png?width=375&height=116" height="300"></div>
    </td>
</tr>

## 5.1.3. Source Code Style Guide & Conventions.
Utilizaremos la guía de estilos y convenciones de codificación en C#, que replicamos
en JavaScript por su similitud, ofrecida por Microsoft.
Y para el HTML/CSS utilizaremos la guía de estilos desarrollado por la fundación Mozilla:
Asimismo, utilizaremos las siguientes tecnologías:

• IDEs:

➢ Visual Studio Enterprise 2022 (https://code.visualstudio.com/download )

➢ VSCode (https://code.visualstudio.com/download )

➢ WebStorm (https://www.jetbrains.com/eses/webstorm/download/#section=windows )

• DevOps:

➢ GitHub (https://docs.github.com/es )

• Lenguajes:

➢ C# (https://docs.microsoft.com/en-us/dotnet/csharp/ )

➢ JavaScript (https://developer.mozilla.org/es/docs/Web/JavaScript )

➢ CSS (https://developer.mozilla.org/es/docs/Web/CSS )

➢ HTML (https://developer.mozilla.org/es/docs/Web/HTML )
www.easycloud.ga
113

• Frameworks:

➢ Vue2 (https://vuejs.org/guide/introduction.html )

➢ Vite (https://vitejs.dev/guide/ )

➢ASP.NET core (https://docs.microsoft.com/enus/aspnet/core/?view=aspnetcore-6.0 )

• Librerías:

Boostrap (https://getbootstrap.com/docs/4.1/gettingstarted/introduction/ )

• Herramientas:

➢ Figma (https://www.figma.com/best-practices/guide-to-developerhandoff/components-styles-and-documentation/ )

➢ Pivotal Tracker (https://www.pivotaltracker.com/help/api/#top )

➢ Microsoft Teams (https://www.microsoft.com/es-ww/microsoftteams/download-app )

➢ NodeJS. (https://nodejs.org/es/download/ )

También, las siguientes reglas:

• Convenciones de idioma:

➢Todo texto utilizado debe ser internalizado en español e inglés.

➢ El nombre de variables, funciones y demás artefactos escritos en código deben ser inglés.

• Tecnologías:

➢ Seguiremos utilizando las tecnologías consideradas para el desarrollo de la
aplicación durante los siguientes Sprints, como: C#, JavaScript, Html y CSS.

• Herramientas:

➢ Seguiremos utilizando las tecnologías consideradas para el desarrollo de la
aplicación, durante los siguientes sprints, como: Rider, Visual Studio,
Github, Git, WebStorm.


## 5.1.4. Software Deployment Configuration.

Para la configuración del despliegue, utilizaremos lo siguiente:
Landing Page:

• Infraestructura

•Proveedor: Azure

• Servicio: Static Web App

• DNS provider: freenom.com

• Automatización: Git Actions

• URL (Landing Page Desplegada): https://easycloud.tv/

Backend:

• Infraestructura

• Proveedor: Azure

• Servicio: Static Web App

• DNS provider: freenom.com

• Automatización: Git Actions

• URL (Web App Desplegada): https://easycloud.tv/

Frontend:

• Infraestructura

• Proveedor: Azure

• Servicio: Static Web App

• DNS provider: freenom.com

• Automatización: Git Actions

• URL (Web App Desplegada): https://easycloud.tv/

## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1.


|              Sprint #             |                                                                                                                                                                                      Sprint 1                                                                                                                                                                                      |
|:---------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|   **Sprint Planning Background**  |                                                                                                                                                                                                                                                                                                                                                                                    |
|                Date               |                                                                                                                                                                                     2020-09-06                                                                                                                                                                                     | 
|                Time               |                                                                                                                                                                                      02:45 PM                                                                                                                                                                                      | 
|              Location             |                                                                                                                                                                              Mediante Sala de Discord                                                                                                                                                                              | 
|            Prepared By            |                                                                                                                                                                           López Huarcaya, Leonardo Paul                                                                                                                                                                            | 
|  Attendees (to planning meeting)  |                                                                                                                                                       Leonardo Lopez/ Sandro Alarcon/ Louis Alfaro/Jose Ampudia/ Jean Morin                                                                                                                                                        | 
|    Sprint n – 1 Review Summary    |                                                                                                                                                                                                                                                                                                                                                                                    | 
| Sprint n – 1 Retrospective Summary |                                                                                                                                                                                                                                                                                                                                                                                    | 
|  **Sprint Goal & User Stories**   |                                                                                                                                                                                                                                                                                                                                                                                    |
|           Sprint 1 Goal           | Desarrollar y lanzar una infrasestructura y documentación del del sistema de gestión de bares que permita a los propietarios registrar menús, gestionar pedidos y realizar un seguimiento de las ventas, con un enfoque en la usabilidad y la estabilidad, con el objetivo de tener una solución funcional lista para pruebas de usuario al final de esta iteración de dos semanas |
|         Sprint n Velocity         |                                                                                                                                                                     Para este sprint se estimo 20 Story Points                                                                                                                                                                     |
|        Sum of Story Points        |                                                                                                                                                                 La suma total de Story Points de este sprint es 18                                                                                                                                                                 |




#### 5.2.1.2. Sprint Backlog 1.

|            Sprint #            |    Sprint 1    | | |                   ||
|:------------------------------:|:----------:|:--:|:--:|:-----------------:|:--:|
|  |  Work-Item / Task   |
|User Story ID| id |Description| Estimation(Hours) |    Assigned To    | Status(To-do/ In-Process/To-Review/Done)|
|US01 |T1 |Crear cuenta común |3 h |  Leonardo Lopez   | To do|
|US02 |T2 |Crear cuenta con otras plataformas |3 h |  Ampudia Flores   | To do|
|US03 |T3 |Entrar a la página como invitado |3 h |  Alarcon Rondon   | To do|
|US04 |T4 |Catálogo de Bares|5 h |   Morin Fuente    | To do|
|US05 |T5 |Añadir bar|5 h |   Louis Alfaro    | To do|
|US06 |T6 |Modificar mi Bar|4 h | Ampudia Flores | To do|
|US07 |T7 |Eliminar mi Bar |5 h |  Leonardo Lopez   | To do|
|US08 |T8 |Mostrar mesas disponibles |2 h |    Morin Fuente     | To do|
|US09 |T9 |Reservar mesas |3 h |   Morin Fuente    | To do|
|US10 |T10 |Almacén de los productos|5 h |  Alarcon Rondon   | To do|
|US11 |T11 |Administrar los productos  |7 h |   Louis Alfaro    | To do|



#### 5.2.1.3. Development Evidence for Sprint Review.
Por el momento esta sección aun no ha sido implementada, para las siguientes entregas estará completa.

#### 5.2.1.4. Testing Suite Evidence for Sprint Review.
Para la entrega del Sprint 1, se tuvo pensado alcanzar el desarrollo completo del despliegue del Landing page. En esta sección presentamos la implementación del Landing page, tratando de alcanzar el diseño original que se realizó en Figma, de tal modo que el usuario tenga una buena experiencia de usuario.

| Repository                                          | Branch                | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|----------------------------------------------------|-----------------------|-----------|----------------|---------------------|---------------------|
| [LoyalSips-LandingPage](https://github.com/IsaacAmp24/LoyalSips-LandingPage.git) | Feature/TS-LandingPage | feature:home-section add     | Initial commit | Se creó el proyecto | 08/09/2023          |
<br>

#### 5.2.1.5. Execution Evidence for Sprint Review.
En el sprint 1, se logró implementar del despliegue de la Landing page. En el que se muestra diferentes secciones que anteriormente fueron diseñadas en el Figma, de este modo se muestran las secciones en el que pueden saber mas de la empresa.

- 1. **Sección About us**
      
      En esta sección se muestra donde el usuario puede ver más acerca de nosotros y lo que ofrecemos.
    <br>
      <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1150176709635739770/image.png?width=1409&height=579"600="" height="">
    </td>
  </tr>
  <br><br>

  - 2. **Sección Services**
  En esta sección se muestra el servicio que ofrecemos, pero al tener 2 segmentos objetivos, tenemos servicios para clientes y servicios para las empresas.
  <br>
        <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1150181153958023179/image.png?width=1409&height=261"600="" height="">
    </td>
  </tr>
  <br><br>
  
    - 3. **Sección Reviews**
  En esta sección se muestra los comentarios o las reseñas de nuestros usuarios, tanto empresas como clientes, de este modo nosotros podremos mejorar e innovar en nuestro sitio web.

  <br>
        <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1150181289304006747/image.png?width=1409&height=353"600="" height="">
    </td>
  </tr>
  <br><br>

    - 4. **Sección Contact**
  En esta sección se muestra un formulario en el que los usuarios, tanto cliente como usuario puede realizar envios de mensajes para contactarnos directamente con nosotros.

  <br>
        <tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1150181591591682230/image.png?width=1237&height=625"600="" height="">
    </td>
  </tr>
  <br><br>

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
Esta sección aun no ha sido completada para la evidencia de la documentación, pero estamos trabajando internamente para completarlo.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para el desarrollo del Landing Page TechSolution se ha utilizado los siguientes lenguajes:

* Html: HyperText Markup Language, este lenguaje no ayudo a elaborar las estructuras de nuestra Langing Page.
* Css: Cascading Style Sheet, es un lenguaje de diseño grafico que nos ayudo en los estilos de nuestro documento realizado en Html.
  
Para el despliegue del Landing Page se ha utilizado las siguientes herramientas:

* Git: Sistema de control de versiones que nos ayudo a trabajar en equipo durante la elaboracion del Markdown
* GitHub: Plataforma de desarrollo colaborativo que nos ayudo a guardar nuestros proyecto con sus respectivas versiones
* Git Flow: Modelo de flujo de trabajo que nos permitio ver el avance de cada uno de los integrantes del grupo con respecto al trabajo elaborado.


#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para el desarrollo del Landing Page TechSolution se ha utilizado los siguientes lenguajes:

* Html: HyperText Markup Language, este lenguaje no ayudo a elaborar las estructuras de nuestra Langing Page.
* Css: Cascading Style Sheet, es un lenguaje de diseño grafico que nos ayudo en los estilos de nuestro documento realizado en Html.
  
Para el despliegue del Landing Page se ha utilizado las siguientes herramientas:

* Git: Sistema de control de versiones que nos ayudo a trabajar en equipo durante la elaboracion del Markdown
* GitHub: Plataforma de desarrollo colaborativo que nos ayudo a guardar nuestros proyecto con sus respectivas versiones
* Git Flow: Modelo de flujo de trabajo que nos permitio ver el avance de cada uno de los integrantes del grupo con respecto al trabajo elaborado.

#### 5.2.1.8 Team Collaboration Insights during Sprint.

| Alumno                           | Código     |
|----------------------------------|------------|
| Leonardo Paul López Huarcaya     | U202124304 |
| Sandro Fourfive Alarcon Rondon   | U202114140 |
| Louis Piero Alfaro Coveñas       | U20191b299 |
| José Carlos Isaac Ampudia Flores | U202112936 |
| Jean Pierre Morin Fuentes        | U202115348 |

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://cdn.discordapp.com/attachments/969784880017842216/1149785189308969130/image.png?raw=true" width="925" height="463"">
    </td>
</tr>

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://raw.githubusercontent.com/Jeanpi-MF/Pictures/main/Capture1.PNG" width="910" height="332"">
    </td>
</tr>


## Conclusiones y recomendaciones.

1. Por medio del proceso de interacción con los entrevistados - mediante en el enfoque de las entrevistas -, nos ha permitido enmarcar y centrar una pequeña muestra acerca de nuestro público objetivo el cual va dirigido nuestro “Startup”, logrando recapitular información valiosa acerca sus intereses, sensaciones, perspectivas y expectativas que esperan tanto los consumidores como los dueños de los diversos bares que hay hoy en día en la ciudad de Lima y en el Perú acerca de lo que vamos a ofrecerles.
2. Entendemos y apreciamos la flexibilidad de las metodologías ágiles, por ende estamos dispuestos a adaptarnos rápidamente a los cambios y responder de manera ágil a las necesidades cambiantes de nuestro proyecto.
3. Con respecto al analisis competitivo desarrollado, podemos concluir que las aplicaciones dirigidas para el sector Bares
Es un nicho que no cuenta con demasiados competidores que enfoquen a mejorar la experiencia de usuario para los clientes y dueños de bares.

## Video About-the-Team.

https://drive.google.com/file/d/1ET_5D6EqUCFAp90LES0_h5k-oqez2F-x/view?usp=sharing

## Bibliografía
## Anexos
<div align="center">Anexos A: Historial de vinculos</div>
<br>

1. Github: https://github.com/Aplicaciones-Web-Point-bar/LoyalSips-TB1-Origin.git 
2. Link del Canvas: https://www.figma.com/file/8PtySG7keKnCbG7BYaLbix/Untitled?type=design&node-id=0%3A1&mode=design&t=USyZ41BwmZ7jge1P-1 
3. Link del Lean Ux Canva: https://www.figma.com/file/8PtySG7keKnCbG7BYaLbix/Untitled?type=design&node-id=0%3A1&mode=design&t=USyZ41BwmZ7jge1P-1
4. Link de Miro: https://miro.com/welcomeonboard/Mk5wZzhZdGppbjl0Y0VZWllDeWtlZ3g3emt6R1NvTHhqdDJ5dUt6MGNoYWRORm5GTHpyNTZOa3paSVRpZ1hJeXwzMDc0NDU3MzU3MTA0ODcyOTA0fDI=?share_link_id=659519633230 
Uxpressiar: https://uxpressia.com/w/6aurq/p/428Tr/i/RkESc 
5. El link del apartado de escritorio: https://www.figma.com/file/xDKLEzeKlPV6A8uBfSIIbC/Sanity-Sketching-Kit-(Community)?type=design&node-id=317-2245&mode=design&t=V3E4RrnPyXstUB4s-0 
6. Link del figma móvil: https://www.figma.com/file/vE2mliJXJbycAVSDC0Tn3g/Landing-Page---Movil?type=design&node-id=0%3A1&mode=design&t=qizxCWqTKyWhjUIy-1 
7. Link del figma de escritorio: https://www.figma.com/file/WvBHU5rWPbgabHex3Er6jj/Landing-Page---LoyalSips?type=design&node-id=0%3A1&mode=design&t=E225PHq1IOJ3VIcx-1
8. Link para visualizar los wireframes diagrams: https://overflow.io/s/O6IYMWFP
9. El link del user Flow diagrams es el siguiente: https://overflow.io/s/RV6NU7NK 
10. Link del prototipo en Figma: https://www.figma.com/proto/vE2mliJXJbycAVSDC0Tn3g/Landing-Page---Movil?page-id=0%3A1&type=design&node-id=18-31&viewport=482%2C573%2C0.23&t=fF9wq2WzqPvgenwU-1&scaling=scale-down&starting-point-node-id=18%3A31&mode=design 

</div>