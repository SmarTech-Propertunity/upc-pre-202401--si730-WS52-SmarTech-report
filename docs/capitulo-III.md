# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

###### Tabla 7.
*Mapa de Escenario To-Be para nuestro primer user persona.*
<img src="/assets/img/To-Be segmento 1.jpg" alt="To-Be segmento 1" width="1200" >


###### Tabla 8.
*Mapa de Escenario To-Be para nuestro segundo user persona.*
<img src="/assets/img/To-Be segmento 2.jpg" alt="To-Be segmento 2" width="1200" >



## 3.2. User Stories
###### Tabla 9.
*Tabla de épicas establecidas para las historias de usuarios.*
<table border="1" style="text-align: left;">
	<tbody>
		<tr>
			<td colspan="1">Código</td>
            <td colspan="1">Título</td>
            <td colspan="1">Epic</td>
		</tr>
		<tr>
            <td colspan="1">EP001</td>
            <td colspan="1"> Implementación de la experiencia UI/UX de la landing page</td>
            <td colspan="1">
            <strong>Como</strong> usuario de internet<strong> quiero</strong> acceder a la landing page<strong> para</strong> informarme sobre la plataforma web
</td>
		</tr>
        <tr>
            <td colspan="1">EP002</td>
            <td colspan="1">Manejo de cuentas</td>
            <td colspan="1">
            <strong>Como</strong> usuario de la plataforma <strong>quiero </strong>ingresar a la plataforma web</strong> <strong>para </strong> para gestionar mi cuenta
            </td>
		</tr>
        <tr>
            <td colspan="1">EP003</td>
            <td colspan="1"> Implementación de interfaz de usuario en la plataforma web </td>
            <td colspan="1">
            <strong>Como</strong> usuario de la plataforma <strong>quiero </strong>visualizar una interfaz amigable y didáctica <strong>para</strong>entender lo que ofrece la plataforma a primera vista
            </td>
		</tr>
        <tr>
            <td colspan="1">EP004</td>
            <td colspan="1"> Optimización de la Navegación de la plataforma web</td>
            <td colspan="1">
            <strong>Como</strong> usuario de la plataforma <strong>quiero</strong> manipular diferentes herramientas de búsqueda y atajos <strong>para</strong> optimizar mi tiempo de navegación dentro de la plataforma
            </td>
		</tr>
        <tr>
            <td colspan="1">EP005</td>
            <td colspan="1">Publicación de propiedad </td>
            <td colspan="1">
            <strong>Como</strong> usuario de la plataforma <strong>quiero</strong> acceder a un apartado donde pueda ingresar la información de mi propiedad <strong>para</strong> que se publique dentro de la plataforma
            </td>
		</tr>
        <tr>
            <td colspan="1">EP006</td>
            <td colspan="1">Consulta de propiedad</td>
            <td colspan="1">
            <strong>Como</strong> usuario de la plataforma <strong>quiero</strong> contar con un apartado de consulta de propiedad <strong>para</strong> informarme, verificar si la propiedad está acorde a mis intereses y presupueste, y posteriormente decidir si contactarme con el anunciante
            </td>
		</tr>
	</tbody>
</table>

---

###### Tabla 10.
*Tabla de las historias de usuarios.*

| User<br>Story<br>ID | Título | Descripción | Criterios de Aceptación | Relacionado<br>con Epic |
|---------------------|--------|-------------|-------------------------|-------------------------|
| US01 | Agregar una sección con descripciones detalladas sobre la startup | **Como** usuario general de la aplicación web, **quiero** tener disponible la informaación sobre la startup de Propertunity, **para** saber que los motiva, q.ue metas poseen y que clase de productos ofrecen | **Dado que** me encuentro dentro de la landing page de Propertunity, **cuando** me dirija a la sección de nosotros, **entonces** podré revisar la descripción, la misión y visión de la startup| Epic 001 |
| US02 | Agregar una sección con descripciones detalladas sobre las suscripciones | **Como** usuario general de la aplicación web, **quiero** poder revisar a detalles las suscripciones que ofrece la aplicación web de Propertunity, **para** saber si las funcionalidades agregadas que entrega serviran para cumplir con mis necesidades **y** saber cuanto llegaria a gastar en la suscripción. | **Dado que** me encuentro dentro de la landing page de Propertunity, **cuando** me dirija a la sección de suscripciones, **entonces** podré revisar de forma resumida todos los planes que ofrece la aplicación web, sus costos, y las funcionalidades extra que proporciona. | Epic 001 |
| US03 | Incorporar una lista con las principales características y funcionalidades | **Como** usuario general de la aplicación web, **quiero** revisar las principales características y funcionalidades de la aplicación web de Propertunity, **para** ser capaz de saber que funciones pueden ser útiles según mis necesidades **y** diferenciar a Propertunity de la competencia. | **Dado que** me encuentro dentro de la landing page de Propertuniy, **cuando** baje la pantalla hasta la sección de funcionalidades, **entonces** podré apreciar una lista o colección mostrando las principales características, funcionalidades, diferencias ante la competencia y valores agregados de Propertunity. | Epic 001 |
| US04 | Proporcionar testimonios con casos de uso real de la aplicación web | **Como** usuario general de la aplicación web, **quiero** poder visualizar indicios de otros usuarios quienes ya usaron el producto antes que yo, **para** poder tener la certeza y garantía de que lo que promocionan es un producto funcional y de confianza. | **Dado que** que ya me encuentro dentro de la landing page de la aplicación web, **cuando** baje la pantalla hasta la sección que diga testimonios, **entonces** podré ver de manera detallada los testimonios o experiencias de otros usuarios con su uso en la aplicación web. | Epic 001 |
| US05 | Implementación de un cuestionario de contacto | **Como** usuario general de la aplicación web, **quiero** ser capaz de contactarme directamente con el personal de apoyo al cliente que trabaja para Propertunity, **para** poder resolver cualquier duda que tenga sobre el aplicativo **y** pueda conseguir más informacación. | **Dado que** me encuentro dentro de la landing page de la aplicación web, **cuando** me dirija a la sección de contacto, **entonces** podre revisar el cuestionario de contacto **y** podré ingresar mi nombre, mi correo y mis dudas para que puedan ser resueltas rapidamente. | Epic 001 |
| US06 | Integrar una barra de navegación sencilla | **Como** usuario general de la aplicación web, **quiero** que haya una barra de navegación en alguna sección de la landing page, **para** que pueda revisar todo lo que me ofrece la página **y** pueda dirigirme directamente a cada sección de la página. | **Dado que** me encuentro dentro de la landing page de Propertunity, **cuando** me dirija a la sección superior al encabezado principal de la página, **entonces** podré revisar la barra de navegación de toda la landing page **y** podré darle click a alguno de los enlaces para dirigirme a una sección especifica de la página con facilidad. | Epic 001 |
| US07 | Implementar un apartado de registro de cuenta | **Como** usuario general de la aplicación, **quiero** poder crear una cuenta dentro de la aplicación web con el uso de datos pertinentes, **para** poder ingresar a la aplicación desde cualquier dispositivo y guardar mis datos personales básicos y necesarios. | **Dado que** me encuentro dentro de la aplicación web, **cuando** me dirija al apartado de ingreso a la aplicación mediante una cuenta **y** presione el botón de registro, **entonces** podré ingresar todos los datos pertinentes y necesarios en un cuestionario **y** crear mi cuenta de la aplicación. | Epic 002 |
| US08 | Implementar un apartado de inicio de sesión | **Como** usuario general de la aplicación web, **quiero** poder iniciar sesión con una cuenta ya creada y registrada en la aplicación web, **para** poder acceder a mis datos, registros, etc., desde cualquier dispositivo. | **Dado que** me encuentro dentro de la aplicación web, **cuando** me me dirija al apartado de ingreso a la aplicación mediante una cuenta **y** presione el botón de inicio de sesión, **entonces** podré ingresar todos los datos que he guardado y que sean necesarios en el cuestionario de inicio de sesión **y** podré ingresar a mi cuenta. | Epic 002 |
| US09 | Integrar un sistema que permita modificar el perfil de un usuario | **Como** usuario general de la aplicación web, **quiero** ser capaz de modificar mi perfil a gusto y/o cambiar ciertos aspectos (como foto de perfil, nombre, estado civil, correo electrónico, cambio de contraseña) , **para** mantener mi cuenta actualizada en todo momento **y/o** cambiar datos erroneos. | **Dado que** ya inicie sesión en la aplicación web de Propertunity **y** me encuentro en la página principal, **cuando** me dirija a la pestaña de perfil a través de la barra de navegación **y** presione el botón de "modificar perfil", **entonces** la aplicación me brindara todas las opciones y herramientas necesarias para realizar las modificaciones en mi pefil. | Epic 002 |
| US10 | Agregar una opción para cerrar sesión de una cuenta | **Como** usuario general de la aplicación web, **quiero** poder cerrar sesión en una de mis cuentas dentro de la aplicación web de Propertunity, **para** poder cambiar a otra cuenta dentro de la misma aplicación **y/o** para cerrar mi cuenta en un dispositivo que sea de uso público. | **Dado que** ya inicie sesión en la aplicación web de Propertunity **y** me encuentro en la página principal, **cuando** me dirija a la pestaña de perfil a través de la barra de navegación **y** presione el botón de "cerrar sesión" al final de la página, **entonces** la sesión de mi cuenta se cerrara **y** la aplicación me llevara a la sección de ingreso mediante registro o inicio de sesión.| Epic 002 |
| US11 | Agregar una opción para eliminar una cuenta | **Como** usuario general de la aplicación web, **quiero** ser capaz de eliminar una de mis cuentas dentro de la aplicación web de Propertunity, **para** poder crear una nueva cuenta con normalidad **y/o** eliminar una cuenta que fue creada de forma erronea. | **Dado que** ya inicie sesión en la aplicación web de Propertunity **y** me encuentro en la página principal, **cuando** me dirija a la pestaña de perfil a través de la barra de navegación **y** presione el botón de "eliminar cuenta" al final de la página, **entonces** me aparecera un cuestionario de confirmación que al completar me permitira eliminar mi cuenta. | Epic 002 |
| US12 | Permitir la recuperación de una contraseña mediante una opción | **Como** usuario general de la aplicación web, **quiero** tener alguna opción con la que pueda recuperar la contraseña de mi cuenta de la aplicación web de Propertunity, **para** poder tener alguna opción de recuperar mi cuenta si olvido mi contraseña **y/o** si quiero cambiar la contraseña de forma rapida para garantizar la seguridad de mi cuenta. | **Dado que** que me encuentro en la sección de inicio de sesión de la aplicación web de Propertunity **y** me olvide mi contraseña, **cuando** presione el enlace de "Me olvide mi contraseña" en la parte inferior del cuestionario, **entonces** la aplicación me pedira mi nombre de usuario y correo **y** me mandara un correo electronico en menos de 2 minutos con las instrucciones necesarias para recuperar mi cuenta. | Epic 002 |
| US13 | Agregar una página que muestre los términos y condiciones | **Como** usuario de la aplicación web, **quiero** tener alguna forma de revisar los términos y condiciones referentes a las medidas de privacidad que mantendra la empresa con mis datos, **para** tener seguridad de que mis datos no serán manipulados de ninguna forma que me pueda perjudicar. | **Dado que** que me encuentro en la sección de inicio de sesión de la aplicación web de Propertunity, **cuando** presione el enlace de "Términos y condiciones de privacidad" en la parte inferior del cuestionario, **entonces** la aplicación me enviara a una pestaña donde estarán todos los términos y condiciones de privacidad. | Epic 002 |
| US14 | Agregar un menú principal de la aplicación web | **Como** usuario de la aplicación web, **quiero** que haya una página principal donde pueda revisar las principales ofertas de propiedades con información **y** desde la cual pueda acceder a todas las funcionalidades que ofrece la aplicación web, **para** poder tener una mayor facilidad de uso **y** verificar rapidamente las principales ofertas de inmobiliarias. | **Dado que** que me encuentro en la sección de inicio de sesión de la aplicación web de Propertunity, **cuando** inicie sesión adecuadamente al agregar toda la información necesaria, **entonces** podré revisar el menú principal de la aplicación junto a todas sus funciones. | Epic 003 |
| US15 | Implementar apartado de propiedades nuevas | **Como** usuario general de la aplicación web, **quiero** visualizar las propiedades recientemente ingresadas a la plataforma web **para** mantenerme informado de las nuevas ofertas y acceder rápidamente | **Dado que** que me encuentro en el menú principal de la aplicación web de Propertunity, **cuando** interactue con el apartado de Propiedades Nuevas **y** le de click a una propiedad, **entonces** la aplicación mostrará la información detallada de la propiedad.  | Epic 003 |
| US16 | Implementar apartado de propiedades destacadas | **Como** usuario  de la aplicación web, **quiero** visualizar las propiedades destacadas de la plataforma web **para** conocer las tendencias de los usuarios y valorar las ofertas más atractivas disponibles | **Dado que** que me encuentro en el menú principal de la aplicación web de Propertunity, **cuando** interactue con el apartado de Propiedades Destacas **y** le de click a una propiedad, **entonces** la aplicación mostrará la información detallada de la propiedad.  | Epic 003 |
| US17 | Implementar una interfaz simple y consistente | **Como**usuario de la aplicación web **quiero** navegar por una interfaz simple consistente y coherente **para** completar mis objetivos con mucha más facilidad. | **Dado que**que me encuentro en el menú principal de la aplicación web de Propertunity, **cuando** visualize la interfaz **y** cambie de sección **entonces** el ambiente donde me encuentro y los demás apartados mantendrán la consistencia de la interfaz que tenía el menú principal| Epic 003|
| US18 | Agregar información relevante | **Como**usuario de la aplicación web **quiero** tener información relevante de cada proceso **para** entender las funcionalidades de la plataforma web. | **Dado que**que me encuentro en el menú principal de la aplicación web de Propertunity, **cuando** interactue con alguna herramienta o sección **entonces** se mostrará información concisa que respete la jerarquía visual que complemente mi entendimiento de alguna funcionalidad o me informe de algun error| Epic 003|
| US19 | Agregar una barra de navegación en la página web | **Como** usuario general de la aplicación web, **quiero** tener un acceso rápido al catálogo de propiedades que ofrezca la aplicación mediante una barra de búsqueda , **para** poder tener una mayor facilidad de uso **y** poder acceder rapidamente a cualquier propiedad que cumpla con mis intereses. | **Dado que** que me encuentro en el menú principal de la aplicación web de Propertunity, **cuando** interactue con la barra de navegación **y** ingrese un input, **entonces** la aplicación mostrará los resultados relacionados al input ingresado. <br> <br>**Dado que** que me encuentro en el menú principal de la aplicación web de Propertunity, **cuando** interactue con la barra de navegación **y** ingrese un input **y** un filtro, **entonces** la aplicación mostrará los resultados relacionados al input ingresado con el filtro aplicado. <br> <br> **Dado que** que me encuentro en el menú principal de la aplicación web de Propertunity, **cuando** interactue con la barra de navegación **y** ingrese un input, **entonces** la aplicación mostrará información en tiempo real con relación al input.  | Epic 004 |
| US20 | Agregar atajos en la página web | **Como** usuario general de la aplicación web, **quiero** tener un acceso en la aplicación mediante atajos que redirigen hacia secciones y funcionalidades, **para** poder tener una mayor facilidad de uso **y** poder acceder rapidamente a cualquier funcionalidad que necesite. | **Dado que** que me encuentro en el menú principal de la aplicación web de Propertunity, **cuando** interactue con un atajo, **entonces** la aplicación se redirigirá al apartado anexado.  | Epic 004 |
| US21 | Agregar íconos en la página web | **Como** usuario general de la aplicación web, **quiero** tener íconos que me redirijan a cada una de las funcionalidades que ofrezca la aplicación desde cualquier página en la que me encuentre, **para** poder tener una mayor facilidad de uso **y** poder acceder rapidamente a cualquier funcionalidad que necesite. | **Dado que** que me encuentro en el menú principal de la aplicación web de Propertunity, **cuando** interactue con un ícono, **entonces**  la aplicación se redirigirá al apartado anexado.  | Epic 004 |
| US22 | Agregar botones de reversión en la página web | **Como** usuario general de la aplicación web, **quiero** contar con un botón de reversión  **para** remediar de forma ágil cualquier error que cometa dentro de la plataforma | **Dado que** que me encuentro realizando cambios en alguna funcionalidad de la aplicación web de Propertunity, **cuando** vea que he cometido un error **y** aprete el botón de reversión, **entonces** la aplicación revertirá los cambios realizados.  | Epic 004 |
| US23 | Agregar un buzón de notificaciones en la página web | **Como** usuario general de la aplicación web, **quiero** tener un apartado de notificaciones **para** recibir información de mi interés y redirigirme a cualquier propiedad que cumpla con mis estándares al instante. | **Dado que** que me encuentro en el menú principal de la aplicación web de Propertunity, **cuando** ingrese al buzón de notificaciones **y** seleccione una notificación sobre una propiedad **entonces** la aplicación me redirigira a la propiedad. <br> <br> **Dado que** que me encuentro en el menú principal de la aplicación web de Propertunity, **cuando** ingrese al buzón de notificaciones **y** seleccione una notificación sobre mi cuenta **entonces** la aplicación me redirigira a los ajustes de usuario | Epic 004 |
| US24 | Crear publicación de propiedades donde pueda ingresar detalles del inmueble | **Como** usuario anunciante de propiedades **quiero** poder crear una publicación de mi producto donde pueda ingresar detalladamente todos los datos de mi inmueble disponible **para** brindar una información más precisa a las personas que observen mi publicación. | **Dado que** quiero agregar una publicación de un inmueble que tengo para rentar o vender **cuando** presione el botón '+ Nueva publicación' **entonces** me brindarán todos los campos necesarios donde pueda ingresar los datos de mi inmueble disponible| Epic 005 |
| US25 | Subida de imagenes de propiedades | **Como** usuario anunciante de propiedades **quiero** agregar imágenes a ls nueva publicación que estoy agregando **para** que los interesados en el inmueble puedan apreciar mejor las dimensiones del mismo. | **Dado que** quiero agregar imágenes referentes al inmueble en la publicación que estoy agregando **cuando** presione el botón 'Agregar imagen' **entonces** podré agregar las imagenes que crea necesarias referentes a la publicación| Epic 005 |
| US26 | Vista previa de la publicación | **Como** usuario anunciante de propiedades **quiero** poder previsualizar la publicación nueva que esté creando **para** asegurarme de que la información sea la correcta| **Dado que** quiero previsualizar mi nueva publicación antes de activarla **cuando** presione el botón 'previsualización' **entonces** se me mostrará la previsualización de mi publicación con los datos y las fotos que subí previamente| Epic 005 |
| US27 | Revisión y edición de la publicación de propiedades | **Como** usuario anunciante de propiedades **quiero** poder visualizar y tener la capacidad de editar mi publicación una vez subida **para** tener un mejor control sobre la misma| **Scenario 1: Visualización de publiaciones. Dado que** quiero visualizar y editar mi publicación **cuando** presione el botón 'Mis publicaciones' **entonces** se me mostrarán una previsualización de todas las publicaciones activas que tengo **Scenario 2: Edición de publicación. Dado que** estoy observando mi publicación y deseo agregar o cambiar algún dato **cuando** presione el botón 'Editar' **entonces** podré agregar o eliminar información de mi publicación | Epic 005 |
| US28 |Métricas de visualización de la publicación| **Como** usuario anunciante de propiedades **quiero** acceder y visualizar de manera sencilla las métricas de mi publicación **para** obtener datos de la misma y me ayude a conocer el alcance que logré generar con dicha publicación | **Dado que** quiero conocer el alcance de mi publicación de manera gráfica y sencilla **cuando** presione el botón 'Ánalisis' **entonces** se me brindará información detallada de la publicación en mención, datos como el número de clicks, el alcance, las veces que solicitaron más información, etc. | Epic 005 |
| US29 | Búsqueda personalizada de inmuebles | **Como** usuario interesado en comprar o alquilar un inmueble en Propertunity, **quiero** poder realizar búsquedas de los inmuebles disponibles en la plataforma **para** encontrar la que mejor se adapte a mis necesidades y preferencias. | **Scenario 1: Inicio de Búsqueda.** **Dado que** soy un usuario registrado y he iniciado sesión en mi cuenta, **cuando** accedo a la plataforma y quiero realizar una búsqueda de inmueble, **entonces** veo una opción clara de "Buscar Inmueble" en la página principal. **Scenario 2: Aplicar Filtros de Búsqueda.** **Dado que** he seleccionado la opción "Buscar Inmueble", **cuando** ingreso a la página de búsqueda de inmuebles, **entonces** tengo la capacidad de aplicar filtros personalizados. | Epic 006 |
| US30 | Visualización de perfiles de los inmuebles | **Como** usuario interesado en comprar o alquilar un inmueble en Propertunity, **quiero** poder ver perfiles detallados de los inmuebles disponibles en la plataforma, **para** obtener información completa sobre ellas antes de tomar una decisión. | **Scenario 1: Inicio de Visualización de Perfiles.** **Dado que** soy un usuario registrado y he iniciado sesión, **cuando** ingreso a la plataforma y selecciono la opción "Ver Inmuebles Disponibles", **entonces** se me redirige a una página donde se muestran perfiles de inmuebles disponibles. **Scenario 2: Visualización de Detalles del inmueble.** **Dado que** estoy en la página de visualización de perfiles, **cuando** hago clic en el perfil de un inmueble específico, **entonces** se me muestra una página con información detallada de ese inmueble, incluyendo la agencia que lo público. | Epic 006 |
| US31 | Localización de los inmuebles en la página web | **Como** usuario interesado en comprar o alquilar un inmueble en Propertunity, **quiero** que la página web me brinde la ubicación de los inmuebles, **para** poder buscarlos personalmente. | **Scenario1: Búsqueda de ubicación.** **Dado que** estoy buscando la ubicación de un inmueble, **cuando** me encuentro en el perfil del inmueble, **entonces** encontrare un mapa mostrando la localización del inmueble. | Epic 006 |
| US32 | Contactar a agente inmobiliario respectivo | **Como** usuario interesado en comprar o alquilar un inmueble en Propertunity, **quiero** poder contactar directamente a los agentes inmobiliarios listados en la plataforma, **para** obtener más información o coordinar una cita. | **Scenario 1: Inicio de Contacto.** **Dado que** estoy interesado en una inmueble y deseo obtener información específica, **cuando** ingreso al perfil del inmueble, **entonces** encontrare la opción "Contactar al Agente". **Scenario 2: Formulario de contacto.** **Dado que** he ingresado a la opción de “Contactar al Agente” y me aparece el formulario de contacto, **cuando** lleno los datos requeridos en el formulario y hago click en “Enviar”, **entonces** el agente recibir mi mensaje en su perfil. | Epic 006 |
| US33 | Visualizar información del agente inmobiliario | **Como** usuario interesado en comprar o alquilar un inmueble en Propertunity, **quiero** ver información detallada sobre los agentes inmobiliarios disponibles en la plataforma, incluyendo su ubicación, horarios de atención y reseñas, **para** tomar una decisión correcta al elegir una. | **Scenario1: Visualización del perfil.** **Dado que** quiero ver la información detallada de uno de los agentes inmobiliarios, **cuando**, me encuentre en el perfil de un inmueble, **entonces**, podré ver la opción “Agente Inmobiliario”. **Scenario2: Visualización de información detallada.** **Dado que** he dado click a la opción “Agente Inmobiliario”, **cuando** me aparezca el perfil del agente, **entonces** podré visualizar la información detallada publicada por el agente inmobiliario. | Epic 006 |
| US34 | Facilitar la comunicación entre usuario y el agente inmobiliario | **Como** usuario interesado en comprar o alquilar un inmueble en Propertunity, **quiero** tener diversos métodos de comunicación con el agente inmobiliario, **para** agilizar el proceso conexión entre las dos partes. | **Scenario1: Acceso a la información de contacto.** **Dado que** deseo comunicarme con un agente inmobiliario, **cuando** accedo al perfil del agente inmobiliario, **entonces** se mostrará su número telefónico, su direccione, correo electrónico y whatapp. | Epic 006 |


## 3.3. Impact Mapping

###### Figura 16.
*Impact Mapping de los dos user persona del proyecto.*

<img src="/assets/img/Impact Map.png" alt="Impact Map" width="1200" height="500">

---

## 3.4. Product Backlog

| #Orden | User<br>Story<br>ID | Título | Descripción | Story Points<br>(1/2/3/5/8)|
|--------|-----|---------|--------|-----|
| 1 | US01 | ... | 8 |
| 2 | US02 | ... | 8 |
| 3 | US03 | ... | 5 | 
|...| ....  | ... |...|

---
