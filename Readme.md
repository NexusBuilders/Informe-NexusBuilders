# <span style="color:red;">CAPÍTULO 5: PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT</span>




## 5.1. Software Configuration Management.

A continuación, se detallarán los distintos productos de software utilizados en el proyecto. Esta información será útil para que los desarrolladores actuales y futuros puedan colaborar de manera efectiva en todas las etapas del proyecto.

###       5.1.1 Software Development Environment Configuration.

#### Project Management

* **Meet y WhatsApp ([https://meet.google.com/](https://meet.google.com/) ) ([https://www.whatsapp.com/?lang=es](https://www.whatsapp.com/?lang=es))**
        Meet y WhatsApp han sido las herramientas principales utilizadas para la comunicación entre los miembros del grupo, mientras que WhatsApp ha sobresalido debido a sus características adicionales para la organización de grupos de estudio y trabajo.

* **Trello ([https://trello.com/es](https://trello.com/es))**
        Trello ha desempeñado un papel fundamental en la gestión y organización de las tareas del proyecto, facilitando tanto la estructuración de las actividades a realizar como el desarrollo y seguimiento del product backlog.


#### Product UX/UI

* **UXPressia ([https://uxpressia.com/](https://uxpressia.com/) )**
        Se usó UXPressia para el desarrollo de los diagramas user person, user journey mapping, empathy mapping e impact map durante el desarrollo del proyecto.

* **Figma ([https://www.figma.com/](https://www.figma.com/) )**
        Se utilizó Figma para el desarrollo de los wireframes y prototipos del landing page y aplicación web, tanto como para los dispositivos de escritorio como de móvil durante el desarrollo del proyecto.

* **Miro ([https://miro.com/es/](https://miro.com/es/) )**
        Se usó Miro en el desarrollo de los escenarios mapping y escenario mapping en ambos casos para ambos segmentos del objetivo en el desarrollo del proyecto.


#### Software Development

* **Visual Studio Code ([https://code.visualstudio.com/](https://code.visualstudio.com/))**
        Se utilizó visual Studio Code para el desarrollo del landing page en el proyecto, además también se usó para el desarrollo del C4.

* **Github y Git bash ([https://github.com/](https://github.com/) ) ([https://git-scm.com/downloads](https://git-scm.com/downloads) )**
        Github y Git bash nos permitió ver el control de las versiones del código y el desarrollo colaborativo de desarrollo del proyecto.


#### Software Documentation

* **Google Drive ([https://drive.google.com/](https://drive.google.com/drive/my-drive?hl=es-419) )**
        Se utilizó Google Drive para poder subir los archivos de documentación y presentación. También se uso Google Docs para poder desarrollar colaborativamente los informes.

* **Google Meets y Zoom ([https://meet.google.com/](https://meet.google.com/) ) ([https://zoom.us/es](https://zoom.us/es) )**
        Se usó Google Meets más que nada para las videoconferencias de reunión del equipo y el Zoom para las grabaciones de las entrevistas, y las presentaciones del trabajo en el desarrollo de este.

* **LucidChart([https://www.lucidchart.com/](https://www.lucidchart.com/) )**
        LucidChart se utilizó para el desarrollo de los diagramas de flujo para ver el diseño de los prototipos de la aplicación web y también para el diagrama de clases.

* **Structurizr([https://structurizr.com/](https://structurizr.com/) )**
        Se utilizó Structurizr para el desarrollo del diagrama C4 en los tres niveles diagrama de contexto, contenedores y componentes. Sin embargo, también se usó Visual Studio Code para el desarrollo de este.

* **Vertabello([https://vertabelo.com/](https://vertabelo.com/))**
        Vertabello ha sido implementado para el desarrollo de base de datos y diagramas en el desarrollo del proyecto.


###       5.1.2. Source Code Management.	

Se creó una organización en Github con los miembros del grupo y un repositorio para el landing page.

* Organización: 
* Repositorio Landing Page:
* Despliegue del Landing Page en Netlify: 


 ####   Commit Conventions

Para los commits en Github se han utilizado los estándares convencionales versión 1.1.0 ([https://www.conventionalcommits.org/en/v1.0.0/](https://www.conventionalcommits.org/en/v1.0.0/)) según la estructura:

&lt;type> [optional]: &lt;description>

* Type: representa el tipo de commit, sea tipo feature (feat), fix (fix) o docs (docs).
* Optional scope: es opcional y representa el alcance del commit.
* Description: descripción del commit y acciones realizadas.


### 5.1.3. Source Code Style Guide & Conventions.
#### HTML Style Guide and Coding Conventions:
* Utilizamos indentación de dos espacios.
* Los nombres de las etiquetas HTML deben estar en minúsculas.
* Los atributos de las etiquetas HTML deben estar en minúsculas.
* Añadimos comentarios claros y concisos en el código HTML para mejorar la comprensión.

#### Google HTML/CSS Style Guide:
* Utilizamos guiones medios para los nombres de clases (por ejemplo, .container-fluid).
* Limitamos la longitud de las líneas de código a 80 caracteres.
* Utilizamos nombres descriptivos para las clases y los IDs.

#### JavaScript Style Guide:
* Utilizamos el estilo de codificación de Google para JavaScript.
* Utilizamos camelCase para nombrar variables y funciones.
* Utilizamos indentación de dos espacios.
* Utilizamos comillas simples para strings.
* Añadimos comentarios descriptivos para explicar el propósito de las funciones y secciones de código.

#### TypeScript Style Guide:
* Utilizamos el estilo de codificación de Google para TypeScript.
* Utilizamos PascalCase para los nombres de las clases.
* Utilizamos camelCase para los nombres de las variables y funciones.
* Java Style Guide:
* Utilizamos el estilo de codificación de Google para Java.
* Utilizamos nombres descriptivos para los paquetes, clases, métodos y variables.
* Utilizamos indentación de cuatro espacios.

#### Gherkin Conventions for Readable Specifications:
* Utilizamos un lenguaje claro y conciso para describir el comportamiento esperado de la aplicación.


### 5.1.4. Software Deployment Configuration.
#### Landing Page.
Para desplegar nuestra landing page primero creamos un repositorio de GitHub.
![CrearRepositorio](/assets/img/CrearRepositorio.png)

En github nos dirigimos a Settings a la sección de Pages donde se encuentra la configuración para el despliegue de la Landing Page. Ahí seleccionamos como branch el main y como ruta “/(root).
![GithubPages](/assets/img/GithubPages.png)

Finalmente, podemos confirmar que el despliegue se realizó correctamente dirigiéndonos a la sección “Environments” y ver el sitio web desplegado.
![Environments](/assets/img/Environments.png)

##   5.2. Landing Page, Services & Applications Implementation.

###  5.2.1. Sprint 1.

En esta primera reunión nos enfocaremos en fijar una meta para el spring 1, en la cual determinaremos la capacidad de velocidad del grupo en referencia a la cantidad de User Stories que podemos hacer y la cantidad de Story Points que serán necesarios para culminar de forma exitosa este spring.


         

#### 5.2.1.1 Sprint Planning 1.

<table>
  <tr>
   <td>
<strong>Sprint #</strong>
   </td>
   <td>Sprint 1
   </td>
  </tr>
  <tr>
   <td colspan="2" ><strong>Sprint Planning backlog</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Date</strong>
   </td>
   <td>2024-03-19
   </td>
  </tr>
  <tr>
   <td><strong>Time</strong>
   </td>
   <td>05:00 PM
   </td>
  </tr>
  <tr>
   <td><strong>Location</strong>
   </td>
   <td>Reunión virtual vía Zoom
   </td>
  </tr>
  <tr>
   <td><strong>Prepared by</strong>
   </td>
   <td>Vasquez Goicochea, Erick Alessander
   </td>
  </tr>
  <tr>
   <td><strong>Attendees (to planning meeting)</strong>
   </td>
   <td>Vasquez Goicochea, Erick Alessander / Araujo Ingunza, Renzo José / Córdova Valdivia, Sebastián / Huamán Monzón, Juan Diego / Torres Alva, Alejandro
   </td>
  </tr>
  <tr>
   <td><strong>Sprint n - 1 Review Summary</strong>
   </td>
   <td>No existe un sprint anterior, ya que este es el primero.
   </td>
  </tr>
  <tr>
   <td><strong>Sprint n - 1 Retrospective Summary</strong>
   </td>
   <td>No existe un sprint anterior, ya que este es el primero.
   </td>
  </tr>
  <tr>
   <td colspan="2" ><strong>Sprint Goal and User Stories</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Sprint 1 Goal</strong>
   </td>
   <td>La meta de este sprint es lograr diseñar e implementar la landing page de nuestro aplicativo
   </td>
  </tr>
  <tr>
   <td><strong>Sprint 1 Velocity</strong>
   </td>
   <td>8 story points
   </td>
  </tr>
  <tr>
   <td><strong>Sum of Story Points</strong>
   </td>
   <td>5  story points
   </td>
  </tr>
</table>


####  5.2.1.2 Sprint Backlog n.

En este primer sprint nos enfocaremos en los Users Stories necesarios para la culminación de la Landing Page. Cada integrante del grupo colaborará realizando cierta cantidad de User Stories para finalizar el sprint en el tiempo correspondiente.


<table>
  <tr>
   <td>
    <strong>Sprint #</strong>
   </td>
   <td colspan="7" >
    Sprint 1
   </td>
  </tr>
  <tr>
   <td colspan="2" >
    <strong>User Story</strong>
   </td>
   <td colspan="6" >
    <strong>Work-Item / Task</strong>
   </td>
  </tr>
  <tr>
   <td>
    <strong>ID</strong>
   </td>
   <td>
    <strong>Title</strong>
   </td>
   <td>
    <strong>ID</strong>
   </td>
   <td>
    <strong>Title</strong>
   </td>
   <td>
    <strong>Description</strong>
   </td>
   <td>
Estimación (Hrs)
   </td>
   <td>
    Assigned to
   </td>
   <td><p style="text-align: right">
<strong>Status (To-do / InProcess / To-Review / Done)</strong></p>

   </td>
  </tr>
  <tr>
   <td>
     
<p>

     
<p>

    E1-US100
   </td>
   <td><strong>Como </strong>empresa/restaurante
<p>
<strong>Quiero </strong>una barra de navegación en el landing page
<p>
<strong>Para </strong>tener accesos directos a la información del aplicativo
   </td>
   <td>
     
<p>

     
<p>

    1
   </td>
   <td>Barra de navegación en landing page
   </td>
   <td>
    Desarrollo e implementación de estilos a la sección Registrar cuenta del Landing Page.
   </td>
   <td>
     
<p>

     
<p>

    2
   </td>
   <td>
     
<p>

     
   </td>
   <td>
     
<p>

    Done
   </td>
  </tr>
  <tr>
   <td>
     
<p>

    E1-US101
<p>

     
   </td>
   <td><strong>Como </strong>empresa/restaurante
<p>
<strong>Quiero </strong>dirigirme a la aplicación
<p>
<strong>Para </strong>poder utilizarla
   </td>
   <td>
     
<p>

    2
   </td>
   <td>
     
<p>
Dirigir del landing page al aplicativo
<p>

     
   </td>
   <td>
    Desarrollo e implementación de estilos a la sección Búsqueda de estudiantes del Landing Page.
<p>

     
   </td>
   <td>
     
<p>

     
<p>

    2
   </td>
   <td>
     
<p>

     
   </td>
   <td>
     
<p>

    InProcess
   </td>
  </tr>
  <tr>
   <td>
     
<p>

    E1-US104
   </td>
   <td><strong>Como </strong>empresario/restaurante
<p>
<strong>Quiero </strong>visualizar los comentarios que tengan sobre el aplicativo
<p>
<strong>Para </strong>que los usuarios sepan lo confiable que es el aplicativo
   </td>
   <td>
     
<p>

    3
   </td>
   <td>Sección de comentarios en landing page
   </td>
   <td>
    Desarrollo e implementación de estilos a la sección Perfil de usuario del Landing Page.
<p>

     
   </td>
   <td>
     
<p>

     
<p>

    2
   </td>
   <td>
     
<p>

     
   </td>
   <td>
     
<p>

    Done
   </td>
  </tr>
  <tr>
   <td>
     
<p>

    E1-US105
   </td>
   <td><strong>Como </strong>empresario/restaurante
<p>
<strong>Quiero</strong> visualizar la sección de footer de la página
<p>
<strong>Para</strong> acceder a los enlaces que presenta la página
   </td>
   <td>
     
<p>

    4
   </td>
   <td>
     
<p>
Sección de footer a la aplicación en landing page
<p>

     
   </td>
   <td>
    Desarrollo e implementación de estilos a la sección Recursos del Landing Page.
<p>    
<p>   
   </td>
   <td>    
<p>   
<p>
    3
   </td>
   <td>  
<p>    
   </td>
   <td>
<p>
    Done
   </td>
  </tr>
</table>

![Trello](/assets/img/SprintTrello.png)
link del trello:
https://trello.com/invite/b/2njuP2u9/ATTI245b5a0954ef9162edfae690b1e19c6aE05B6263/sprint1

#### 5.2.1.3. Development Evidence for Sprint Review.

#### 5.2.1.4. Testing Suite Evidence for Sprint Review.
Para esta entrega solo se desarrolló la Landing Page, por lo que esta sección no se implementó.

#### 5.2.1.5. Execution Evidence for Sprint Review.
![Github](/assets/img/GithubPages.png)
![Trello](/assets/img/LandingPage.png)

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
Para esta entrega solo se desarrolló la Landing Page, por lo que no se empleó ningún servicio adicional.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
Para realizar el despliegue automático de la Landing Page se utilizó la herramienta Github Pages desde un repositorio público. El link de nuestra Landing Page es el siguiente: 
https://github.com/NexusBuilders/LandingPage-EasyFood

#### 5.2.1.8. Team Collaboration Insights during Sprint.
Para realizar los commits de nuestro primer Sprint se usó la herramienta de Git y Visual Studio Code. Se puede visualizar los commits en el cual todos los integrantes fueron parte del proyecto.


## <span style="color:red;">CONCLUSIONES</span>
#### TB1: 

## <span style="color:red;">BIBLIOGRAFÍA</span>
* Tudela, J. (10 de Enero de 2023) "Ubiquitous Language." Open Practice Library, Recuperado el 10 de Abril de 2024. URL: https://openpracticelibrary.com/practice/ubiquitous-language/#:~:text=What%20Is%20Ubiquitous%20Language%3F,but%20not%20limited%20to%20that 
* Tune. N. (15 de Agosto de 2015) “Domain-Driven Architecture Diagrams. Medium.” Tune, Recuperado el 10 de Abril de 2024. URL: https://medium.com/nick-tune-tech-strategy-blog/domain-driven-architecture-diagrams-139a75acb578 

## <span style="color:red;">ANEXOS</span>


