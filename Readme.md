# <span style="color:red;">Chapter III: Requirements Specification</span>
----
## 3.1. To-Be Scenario Mapping.
To-Be scenario map cuando las empresas están buscando un buen restaurante para sus empleados

![To-be-business](/assets/To-Be-Scenario.png)

## 3.2. User Stories.

### Epics:

| Epics ID  | Titulo    | Descripcón|
|-----------|-----------|-----------|
| EP001 | Landing page | Como Empresa/Restaurante Quiero una página (app) Para saber acerca de la aplicación y poder ingresar a ella |
| EP002 | Perfil de usuarios | Como Empresa/Restaurante Quiero configurar mi perfil de usuario Para poder ingresar a la aplicación y usar el aplicativo |
| EP003 | Gestión de pedidos | Como Empresa/restaurante Quiero poder gestionar que pedidos tengo Para estar al pendiente del historial que estoy contratando |
| EP004 | Pagos y promociones | Como Empresa Quiero realizar pagos y ver promociones de los restaurantes Para continuar con las solicitudes |


#### User stories: 
Aqui se describira los user stories de la aplicación web y de la landing page.

| Epic/Story ID | Título | Descripción | Criterios de aceptación | Relación con (Epic ID)  |
|-----------|-----------|-----------|-----------|-----------|
| E1-US100 | Barra de navegación en landing page| Como empresa/restaurante Quiero una barra de navegación en el landing page Para tener accesos directos a la información del aplicativo | **Scenario: El empresario o gerente del restaurante quiere tener más información del app**<br>  **Given** que el empresario o el gerente del restaurante se encuentra en el landing page **Y**se dirige a la barra de navegación <br>**When** presione algún link de navegación que le interese<br>**Then** es dirigido a la sección que ha seleccionado**Scenario: El empresario o gerente del restaurante quiere tener más información del app desde su movil** <br>**Given** que el empresario o el gerente del restaurante se encuentra en el landing page **Y** este se encuentre en su dispositivo móvil <br>**When** esté presione la opción de mostrar la información del aplicativo **y** los links de navegación <br>**Then** se mostrará la información y los links de navegación a la vista en el dispositivo móvil.| EP001 |
| E1-US101 | Dirigir del landing page al aplicativo | Como empresa/restaurante Quiero dirigirme a la aplicación Para poder utilizarla | **Scenario: La aplicación sigue en desarrollo**<br>**Given** que el empresario o el gerente del restaurante se encuentra en el landing page **y** se dirige a la barra de navegación <br>**When**este presiones el botón del aplicativo <br>**Then** le saldrá un comunicado que aún está en proceso. <br> **Scenario: Es enviado a la aplicación desde el landing page** <br> **Given** que el empresario o el gerente del restaurante se encuentra en el landing page **y** que el empresario o el gerente del restaurante se encuentra en el landing page<br> **When**este presiones el botón del aplicativo<br> **Then** será dirigido a la aplicación| EP001 |
| E1-US102 | Sección de tipos de restaurante en la búsqueda | Como empresario Quiero visualizar una sección de los tipos de restaurante Para poder visualizar cual podría escoger | **Scenario: Visualiza los tipos de restaurante**<br>**Given** que el empresario se encuentra en el landing page<br>**When*encuentre la barra que le muestra los tipos de restaurantes<br> **Then** podrá visualizar de una manera más cómoda lo que desea escoger<br> **Scenario: Logra visualizar** <br> **Given** que el empresario está visualizando los restaurantes<br> **When**esté seleccionando los parámetros que prefiera<br> **Then** podrá visualizar de nuevo la sección de los restaurantes pero con su preferencia. | EP001 |
| E1-US103 | Sección de tipos de platos que muestran los restaurantes en su búsqueda | Como empresario Quiero visualizar una sección de los tipos de plato Para poder visualizar cuál restaurantes conviene según sus platos | **Scenario: Visualiza los tipos de platos de los restaurantes**<br>**Given** que el empresario se encuentra en el landing page<br>**When**encuentra la barra que le muestre los tipos de platos del restaurante<br> **Then** podrá visualizar los restaurantes según su tipo de plato. | Celda EP001|
| E1-US104 | Sección de comentarios en landing page | Como empresario/restaurante Quiero visualizar los comentarios que tengan sobre el aplicativo Para que los usuarios sepan lo confiable que es el aplicativo | **Scenario: El empresario o gerente del restaurante se encuentran en los comentarios del landing page**<br>**Given** que el empresario o el gerente del restaurante se encuentra en la landing page<br>**When** esté bajando **y** e encuentre en la parte inferior de la landing page<br>**Then** podrá visualizar los comentarios que pongan para el aplicativo | EP001 |
| E1-US105 | Sección de footer a la aplicación en landing page   | Como empresario/restaurante Quiero visualizar la sección de footer de la página Para acceder a los enlaces que presenta la página | **Scenario: El empresario/restaurante se encuentran en la sección del footer**<br>**Given** que el empresario o gerente del restaurante se encuentra en la landing page<br>**When** este bajando y se encuentre en el footer **And** seleccione algún enlace que le interese<br>**Then** será dirigido a la sección que haya seleccionado| EP001  |
| E2-US100 | Registrar las cuentas| Como empresario/resturante Quiero poder registrar mi cuenta Para acceder a lo que brinda el aplicativo| **Scenario: Registrar cuenta**<br>**Given** que el empresario o el gerente del restaurante ingresa a la aplicación **Y** se encuentre en la sección de registro cuenta<br>**When** seleccione si es restaurante o empresario **And** ingreselos datos de su cuenta **And** estos estén validados<br>**Then** la cuenta se creará con satisfacción| EP002|
| E2-US101 | Iniciar Sesión| Como empresario/restaurante Quiero iniciar sesion en mi cuenta Para acceder al aplicativo. |  **Scenario: Los usuarios inician sesión satisfactoriamente**<br>**Given** que el empresario o el gerente del restaurante está en el apartado de iniciar sesión<br>**When** ingrese todos sus datos **And** le de click en iniciar sesión<br>**Then** podrá acceder a su cuenta de la aplicación  | EP002|
| E2-US102 |Recuperación de la contraseña |Como empresario/restaurante Quiero poder recuperar mi contraseña Para poder iniciar sesión|  **Scenario: Solicitud de recuperación de contraseña**<br>**Given** que el empresario o el gerente del restaurante este en el apartado de recuperar contraseña**When** ingrese el correo o la modalidad que escogió para recuperar contraseña **And** escriba o coloque el correo<br>**Then** podrá recuperar su contraseña perdida |EP002|
  | E2-US103 |Edición del perfil | Como empresario/restaurante Quiero poder editar mi perfil Para poder actualizar mi perfil.|  **Scenario: Edición del perfil en el aplicativo**<br>**Given** que el empresario o el gerente del restaurante este en su perfil<br>**When** el cliente localice el boton de editar **And** este haya apretado el botón de editar<br>**Then** podrá editar su cuenta en la aplicación | EP003 |
| E2-US104 | Cerrar sesión|Como empresario/restaurante Quiero poder cerrar sesion de mi cuenta Para no dejar mi sesion prendida en cualquier lugar|  **Scenario: Cerrando sesión de mi cuenta**<br>**Given** que el empresario o gerente del restaurante este en su la barra **When** éste encuentre el apartado de cerrar sesión **And**cuando este le de click en cerrar sesión <br>**Then** podra cerrar sesión con éxito desde cualquier lugar en el que se encuentre | EP003 |
| E3-US101 | Barra de gestion de pedidos|Como empresario Quiero poder tener una opción de gestión Para poder gestionar mis pedidos|  **Scenario: Entrando a la gestión de pedidos**<br>**Given** que el empresario esté en su perfil <br> **When** éste acceda a las barras de opciones **And** este de click en pedidos<br>**Then** podrá acceder a todo su historial y pedidos activos | EP003 |
| E3-US102 | Agregar artículos |Como restaurante Quiero poder agregar artículos a mi perfil Para que puedan ver las nuevas opciones que presento |  **Scenario:Agregando artucilos**<br>**Given** que el gerente del restaurante está en su perfil <br> **When** éste acceda a las opciones de editar **And**este presione click en editar<br>**Then** podrá editar los detalles que desea cambiar| EP003 |
| E3-US103 |Editando artículos| Como restaurante Quiero poder editar los artículos ya escritos Para poder actualizar mis servicios|  **Scenario: Editando mis artículos**<br>**Given** que el gerente del restaurante ya dio click en editar **And** esté editando sus artículos<br> **When** este haya terminado de editar lo que era necesario para su perfil **And**presione el botón de guardar <br>**Then** habra guardado con satisfacción sus cambios. | EP003|
| E3-US104 | Revisión de las notificaciones |Como empresario/restaurante Quiero poder revisar las notificaciones Para saber quien ha solicitado/aceptar mis servicios |  **Scenario: Visualizar las notificaciones**<br>**Given**que el empresario o gerente del restaurante este en su perfil <br> **When** este se encuentre en la sección de notificaciones **And**presione el botón para de notificaciones <br>**Then**podrá visualizar las notificaciones que le hayan llegado a su cuenta |EP004|
| E4-US100 |Promociones que ofrecen los restaurantes | Como empresa Quiero visualizar las promociones que ofrecen los restaurantes Para ver cual me convenga|  **Scenario: Promociones ofrecidas por el restaurante**<br>**Given** que el empresario ya ha tenido varios pedidos en los restaurantes <br> **When** éste ingrese a su perfil **And** en la parte de notificaciones observa en su bandeja <br>**Then** podrá visualizar las promociones que les ofrezcan los restaurantes | EP004 |
| E4-US101 |Pago del restaurante| Como empresa Quiero realizar los pagos a los restaurantes Para continuar con mis pedidos|  **Scenario: Pagando los encargos**<br>**Given** que el empresario se encuentre en su cuenta <br> **When** este se encuentre en sección de pagos **And** este llene los datos y el método de pago **And** haya puesto el monto acordado con el restaurante<br>**Then** podrá realizar la transacción a la empresa según el método de pago seleccionado | EP004 |




## 3.3. Impact Mapping.
**Empresas**

![Impact-map-business](/assets/Impact-map-empresas.png)

**Restaurantes**

![Impact-map-business](/assets/Impact-map-empresas.png)
## 3.4. Product Backlog.

![Product-backlog](/assets/Product-backlog.png)
