# <center>Universidad Peruana de Ciencias Aplicadas</center>
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

### Setiembre 2023

<br><br>

## Registros de versiones del Informe

|   Version     |   Fecha   |   Autor   |   Descripción de la modificación|
|:-------------:|:---------:|:---------|:------------------------|
|1              |           |Ampudia Flores|- Implementó  |
|1              |           |Alarcon Rondon|- Implementó  |
|1              |           |Morin Fuentes |- Implementó  |
|1              |           |Louis|- Implementó  |
|1              |           |Leonardo|- Implementó  |

<br><br>

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
    - [5.2.X Sprint n](#52x-sprint-n)
        - [5.2.X.1 Sprint Planning n](#52x1-sprint-planning-n)
        - [5.2.X.2 Sprint Backlog n](#52x2-sprint-backlog-n)
        - [5.2.X.3 Development Evidence for Sprint Review](#52x3-development-evidence-for-sprint-review)
        - [5.2.X.4 Testing Suite Evidence for Sprint Review](#52x4-testing-suite-evidence-for-sprint-review)
        - [5.2.X.5 Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)
        - [5.2.X.6 Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)
        - [5.2.X.7 Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)
        - [5.2.X.8 Team Collaboration Insights during Sprint](52x8-team-collaboration-insights-during-sprint)



<br>

# Student Outcome
| Criterio específico | Acciones Realizadas | Conclusiones |
|:--------------------|:-------------------:|:------------:|
|Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.|Tareas| Conclusion|
|Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.|Tareas|Conclusion|
<br><br>

# Capitulo 1: Introducción

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

# Capítulo II: Requirements Elicitation & Analysis - SANDRO 

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
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1147987398639235173/User_Person_Cliente.png?width=419&height=592"width="403" height="569">
    </td>
  </tr>

#### 2.3.1.2 Segmento Objetivo 1: Empresario
<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1147997558657007706/User_Person_Empresario.png?width=419&height=592"width="403" height="569">
    </td>
  </tr>

### 2.3.2. User Task Matrix.

Esta sección llamada User Task Matrix es una herramienta que nos sirve para
poder entender las tareas y objetivos que cada User Persona desea lograr a la
hora de utilizar nuestro producto. En esta sección, se presentarán las matrices de
tareas para los User Personas previamente definidos.

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1148008883084853418/Eisenhower_Matrix.jpg?width=1301&height=600"width="1301" height="600">
    </td>
  </tr>

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
    <td style="text-align: justify;">Si el usuario, abre el sitio web tendrá que registrarse, seguidamente se mostrará la interfaz principal. En caso ya se encuentre registrado, se muestra la interfaz principal.</td>
    <td style="text-align: justify;">Realiza compras de licores, de esta manera el cliente generará puntaje a medida que compre licor.</td>
    <td style="text-align: justify;">Verifica sus puntos obtenidos en el sitio web, el cual se mostrará en una barra y consulta al personal del bar.</td>
    <td style="text-align: justify;">Consulta al personal sobre el proceso de reclamo de puntos cuando la barra de puntaje haya llegado al máximo.</td>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>Piensa</strong></td>
    <td style="text-align: justify;">“Me agrada no esperar mucho tiempo al ingresar al sitio web”</td>
    <td style="text-align: justify;">“¡Vaya!, estoy ganando muchos puntos, lo reclamaré cuando la barra se llene por completo"</td>
    <td style="text-align: justify;">Me gusta poder ver mi puntaje y poder saber qué productos puedo reclamar, la visualización por forma de barra es atractiva.</td>
    <td style="text-align: justify;">Me agrada poder canjear mis puntos de manera sencilla con la dependienta del bar.</td>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>Siente</strong></td>
    <td style="text-align: justify;">Siente satisfacción porque el registro de usuario es sencillo y no toma mucho tiempo.</td>
    <td style="text-align: justify;">El usuario se siente contento por conocer su puntaje y saber que puede reclamar tragos.</td>
    <td style="text-align: justify;">El usuario siente satisfacción porque la barra se visualiza muy bien y entendible.</td>
    <td style="text-align: justify;">Se siente contento porque puede reclamar productos con los puntos obtenidos.</td>
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
    <td style="text-align: justify;">El empresario se registra como empresario y se muestra una interfaz distinta a la del usuario</td>
    <td style="text-align: justify;">Los encargados del bar en el sector del sitio web visualizan los puntajes de cada cliente</td>
    <td style="text-align: justify;">El usuario se acerca a ver sus puntos, el empresario pide el nombre del cliente y lo busca en el sitio web, en el que puede observar su puntaje y poder reclamar por los productos disponibles.</td>
    <td style="text-align: justify;">Usa nuestro sitio web, en la interfaz de empresario, existe una sección para controlar inventario, el empresario ingresa a dicha sección y puede controlar sus productos.</td>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>Piensa</strong></td>
    <td style="text-align: justify;">“Que satisfacción ingresar a un sitio web de manera rápida”</td>
    <td style="text-align: justify;">Me parece un sistema entendible, en el que puedo ver los puntos de cada cliente de manera ordenada. </td>
    <td style="text-align: justify;">Me parece muy bien poder hacer esta operación de manera automática, es un sistema innovador. </td>
    <td style="text-align: justify;">Me gusta la eficiencia y la reducción de errores en el control de inventario.</td>
  </tr>
  <tr>
    <td style="text-align: justify;"><strong>Siente</strong></td>
    <td style="text-align: justify;">Siente satisfacción porque puede observar los clientes asociados al sitio web de forma entendible. </td>
    <td style="text-align: justify;">El encargado siente satisfacción por la facilidad de entender rápidamente el sitio web.</td>
    <td style="text-align: justify;">Se siente contento porque de esta manera los clientes crean una fidelización con el bar, haciendo que los clientes vuelvan de manera continua.  </td>
    <td style="text-align: justify;">Siente felicidad porque observa una reducción de problemas relacionados con el stock del producto.</td>
  </tr>
</table>

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
    <td >
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149524347619389551/image.png?width=289&height=423"width="403" height="569">
    </td>
</tr>

Realizamos el impact Mapping para el usuario Bar, que representa a los dueños bares, y según los User Stories realizadas por nuestro equipo, desarrollamos alternivas para solucionar y satisfacer sus necesidades. 

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1146639921830973516/1149524152261283901/image.png?width=401&height=423"width="403" height="569">
    </td>
</tr>

Hemos llevado a cabo un proceso de Impact Mapping dirigido al usuario llamado "cliente", quien representa a los clientes que consumen en bares. A partir de las historias de usuario generadas por nuestro equipo, hemos elaborado diferentes opciones para abordar y satisfacer sus requerimientos. 

 


Link de Miro y Uxpressiar -> https://miro.com/welcomeonboard/Mk5wZzhZdGppbjl0Y0VZWllDeWtlZ3g3emt6R1NvTHhqdDJ5dUt6MGNoYWRORm5GTHpyNTZOa3paSVRpZ1hJeXwzMDc0NDU3MzU3MTA0ODcyOTA0fDI=?share_link_id=659519633230  

https://uxpressia.com/w/6aurq/p/428Tr/i/RkESc  

# 4 CAPÍTULO IV: PRODUCT DESIGN

## 4.1 Style Guidelines.

Nuestro producto de aplicación web que se diseñara es LoyalSips, la cual ofrece al cliente una solución tecnológica para que el problema de separar mesas en un bar o que los precios de los bares sean muy altos, en nuestra web podra reservar un espacio comodo y tambien encontrara ofertas de bebidas, un plus que tiene nuestra web es que cada vez que el cliente compre un trago se le incluiran puntos para que pueda canjear un trago cuando llegue a los puntos requeridos Para los estilos utilizados se tomará en cuenta la satisfacción del cliente y su experiencia.
Los colores que se están utilizando para nuestra solución (Landing Page y Web site) son los siguientes: <br><br>

<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1149549523522289684/image.png"width="403" height="87">
    </td>
  </tr>
<br>
<br>
Por otro lado Usamos el tipo de letra San Francisco.
<br>
<br>
<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1149548371288277044/image.png"width="288" height="447">
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
      <img src="https://media.discordapp.net/attachments/1145898392631918606/1148313906264150197/Untitled_1.jpg?width=475&height=592"width="475" height="592">
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

## 4.8 Database Design

El diseño de bases de datos para el sistema de gestión de datos de "LOYALSIPS" implica la creación de una estructura de base de datos que permita almacenar y gestionar eficientemente información relacionada con los bares, como menús, inventarios, pedidos, clientes y boletas. Esto implica la definición de tablas que representen entidades clave, como Tablas, Reservas, Mesas, Bar, Orden, Cliente, Boleta, Bebidas y Almacén, y la creación de relaciones entre estas tablas para reflejar cómo se relacionan los datos.

En el diseño de bases de datos para bares, se deben considerar elementos como las claves primarias y foráneas para mantener la integridad de los datos, las restricciones de base de datos para garantizar la consistencia y la normalización de datos para evitar la duplicación innecesaria de información.

### 4.8.1. Database Diagram
<tr>
    <td style="border: 1px solid #dddddd; padding: 8px;">
      <img src="https://media.discordapp.net/attachments/969784880017842216/1149495852549799956/Diagrama_de_Clases_Point_Bar-2023-09-07_19-00.png?width= "80" height=auto>
    </td>
</tr>

#### 5.2.X.7. Software Deployment Evidence for Sprint Review.

Para el desarrollo del Landing Page TechSolution se ha utilizado los siguientes lenguajes:

* Html: HyperText Markup Language, este lenguaje no ayudo a elaborar las estructuras de nuestra Langing Page.
* Css: Cascading Style Sheet, es un lenguaje de diseño grafico que nos ayudo en los estilos de nuestro documento realizado en Html.
  
Para el despliegue del Landing Page se ha utilizado las siguientes herramientas:

* Git: Sistema de control de versiones que nos ayudo a trabajar en equipo durante la elaboracion del Markdown
* GitHub: Plataforma de desarrollo colaborativo que nos ayudo a guardar nuestros proyecto con sus respectivas versiones
* Git Flow: Modelo de flujo de trabajo que nos permitio ver el avance de cada uno de los integrantes del grupo con respecto al trabajo elaborado.