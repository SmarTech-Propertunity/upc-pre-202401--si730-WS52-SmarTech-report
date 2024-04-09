# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

###### Tabla 7.
*Mapa de Escenario To-Be para nuestro primer user persona.*

|  Fases |  Búsqueda de Propiedades | Contacto con Vendedores/Agentes | Evaluación de Propiedades | Evaluación de Ofertas y Contrapropuestas |
|--------|----|----|----|----|
|  Doing | Los usuarios utilizan filtros avanzados y herramientas de búsqueda inteligente para encontrar propiedades que se ajusten a sus criterios específicos.| Los usuarios pueden comunicarse directamente con vendedores o agentes inmobiliarios a través de mensajería integrada o sistemas de contacto rápido.|Los usuarios exploran herramientas de visualización avanzada, como recorridos virtuales en 3D y videos interactivos, para evaluar propiedades de manera más detallada. | Los usuarios utilizan herramientas integradas para evaluar y comparar ofertas de manera eficiente, incluyendo análisis de precios históricos y tendencias del mercado.|
|Thinking|Los usuarios aprecian la facilidad y la precisión de la búsqueda, lo que les permite explorar una amplia gama de opciones de manera eficiente. |Los usuarios valoran la comunicación fluida y rápida, lo que les permite obtener información adicional y aclarar dudas sin demoras. | Los usuarios aprecian la calidad y la variedad de las herramientas de evaluación, lo que les permite tomar decisiones informadas sobre la idoneidad de una propiedad.| Los usuarios encuentran útil la capacidad de analizar ofertas de manera estructurada y transparente, lo que les ayuda a tomar decisiones estratégicas.|
|Feeling |Los usuarios se sienten satisfechos al encontrar rápidamente propiedades que coinciden con sus necesidades, lo que aumenta su confianza en la plataforma. | Los usuarios se sienten respaldados y confiados al tener una comunicación efectiva con los vendedores, lo que mejora su experiencia general.| Los usuarios se sienten impresionados y comprometidos al interactuar con herramientas visuales innovadoras, lo que mejora su percepción de la plataforma.|Los usuarios se sienten empoderados y seguros al contar con herramientas de evaluación objetiva, lo que reduce la incertidumbre en el proceso de negociación. |

###### Tabla 8.
*Mapa de Escenario To-Be para nuestro segundo user persona.*

|  Fases | Publicación de Propiedades | Gestión de Consultas y Visitas | Publicación y Promoción Efectiva | Mantenimiento y Actualización de Información |
|--------|----|----|----|----|
|  Doing |Los anunciantes utilizan herramientas intuitivas y de fácil uso para crear listados detallados de propiedades, incluyendo descripciones atractivas y fotos de alta calidad. | Los anunciantes utilizan herramientas de gestión de consultas y calendarios integrados para coordinar visitas a la propiedad y responder de manera rápida a las consultas de los interesados.| Los anunciantes utilizan herramientas de marketing y promoción integradas para aumentar la visibilidad de sus propiedades y atraer a más posibles compradores o inquilinos.|Los anunciantes actualizan regularmente la información de sus propiedades para mantenerla relevante y atractiva para los posibles compradores o inquilinos. |
|Thinking| Los anunciantes valoran la eficiencia y la capacidad de personalización de la plataforma, lo que les permite crear publicaciones profesionales de manera rápida y efectiva|Los anunciantes aprecian la organización y la capacidad de seguimiento de la plataforma, lo que les permite gestionar consultas y visitas de manera eficiente. |Los anunciantes encuentran útiles las estrategias de promoción efectivas de la plataforma, lo que les permite destacarse en un mercado competitivo. |Los anunciantes valoran la importancia de la información actualizada para mantener el interés de los interesados y asegurar una transacción exitosa. |
|Feeling |Los anunciantes se sienten confiados y satisfechos al ver sus propiedades publicadas de forma atractiva, aumentando su confianza en el éxito de la transacción. | Los anunciantes se sienten respaldados y en control al manejar consultas y visitas de forma efectiva, lo que mejora su experiencia como anunciante.| Los anunciantes se sienten entusiasmados y motivados al ver el impacto positivo de las estrategias de promoción, lo que aumenta su confianza en el éxito de la transacción.| Los anunciantes se sienten comprometidos y responsables al mantener la información actualizada, lo que mejora su reputación como anunciante confiable.|


## 3.2. User Stories
###### Tabla 9.

<table border="1" style="text-align: left;">
	<tbody>
		<tr>
			<td colspan="1">Código</td>
            <td colspan="1">Título</td>
            <td colspan="1">Epic</td>
		</tr>
		<tr>
            <td colspan="1">EP001</td>
            <td colspan="1"></td>
            <td colspan="1">
            <strong>Como</strong> usuario de la plataforma<strong> quiero</strong> acceder a la plataforma web <strong>para</strong> gestionar mi cuenta.
</td>
		</tr>
        <tr>
            <td colspan="1">EP002</td>
            <td colspan="1"></td>
            <td colspan="1">
            <strong>Como</strong> usuario de la plataforma <strong>quiero</strong> visualizar la interfaz del landing page y la plataforma <strong>para </strong>explorar sus diferentes funcionalidades. 
            </td>
		</tr>
        <tr>
            <td colspan="1">EP003</td>
            <td colspan="1"></td>
            <td colspan="1">
            <strong>Como</strong> usuario de la plataforma <strong>quiero</strong> interactuar con sus diferentes características <strong>para</strong> realizar diversas acciones y obtener resultados esperados. 
            </td>
		</tr>
        <tr>
            <td colspan="1">EP004</td>
            <td colspan="1"></td>
            <td colspan="1">
            <strong>Como</strong> usuario de la plataforma <strong>quiero</strong> explorar los diferentes videojuegos <strong>para</strong> poder apredender cada rama de las matemáticas
            </td>
		</tr>
        <tr>
            <td colspan="1">EP005</td>
            <td colspan="1"></td>
            <td colspan="1">
            <strong>Como</strong> usuario de la plataforma <strong>quiero</strong> acceder a un apartado donde se visualice el desempeño del usuario estudiante <strong>para</strong> analizar su rendimiento académico dentro de la plataforma.
            </td>
		</tr>
        <tr>
            <td colspan="1">EP006</td>
            <td colspan="1"></td>
            <td colspan="1">
            <strong>Como</strong> usuario de la plataforma <strong>quiero</strong> contar con un apartado técnico <strong>para</strong> reportar cualquier problema que pueda haber en el sistema.
            </td>
		</tr>
	</tbody>
</table>

---

###### Tabla 10.
*Tabla de épicas establecidas para las historias de usuarios.*

| User<br>Story<br>ID | Título | Descripción | Criterios de Aceptación | Relacionado<br>con Epic |
|---------------------|--------|-------------|-------------------------|-------------------------|
| US01 | Esquematización y programación de una landing page | **Como** usuario general de la aplicación web, **quiero** que haya una página sencilla y llamativa como presentación, **para** que pueda revisar varios detalles de la aplicación, como sus funcionalidades, las suscripciones, información sobre la startup, etc. | **Dado que** tengo el link de la página web copiado en mi portapapeles, **cuando** pegué el link en la barra de búsqueda y presione siguiente, **entonces** podré revisar la landing page de la aplicación web Propertunity y podre revisar sus funcionalidades, suscripciones y más información útil. | Epic 01 |
| US02 | Integración de búsqueda en un Web Browser | **Como** usuario general de la aplicación web, **quiero** ser capaz de buscar la landing page de la aplicación web directamente desde el browser con el uso de palabras clave, **para** que mi búsqueda sea más fácil y no tener que copiar y pegar el link de la página en todo momento que quiera acceder. | **Dado que** estoy en el navegador web de mi dispositivo, **cuando** ponga palabras clave relacionadas directamente con Propertunity o con el rubro inmobiliario peruano, **entonces** me saldra la landing page de Propertunity como resultado en cualquier sección de la primera página po segunda página de resultados. | Epic 01 |
| US03 | Integración de links para redes sociales en el Footer | **Como** usuario general de la aplicación web, **quiero** ser capaz de acceder a las principales redes sociales de la startup que diseña Propertunity, **para** poder revisar información actualizada sobre sus planes de negocio, eventos con su público o nuevas actualizaciones en Propertunity o en algún otro producto web que ofrezcan. | **Dado que** me encuentro dentro de landing page de Propertunity, **cuando** me dirija a la sección de la base o footer de la landing page y le de click a alguno de los simbolos de redes sociales que tiene la startup de SmarTech, los cuales son de Facebook, X, Instagram y LinkedIn, **entonces** podré acceder directamente al perfil de la startup en la red social que elegí. | Epic 01 |
| US04 | | | | |
| US05 | | | | |
| US06 | | | | |
| US07 | | | | |
| US08 | | | | |
| US09 | | | | |
| US010 | | | | |

## 3.3. Impact Mapping

###### Figura 11.
Impact Mapping de los dos user persona del proyecto.

---

## 3.4. Product Backlog

| #Orden | User<br>Story<br>ID | Título | Descripción | Story Points<br>(1/2/3/5/8)|
|--------|-----|---------|--------|-----|
| 1 | US01 | ... | 8 |
| 2 | US02 | ... | 8 |
| 3 | US03 | ... | 5 | 
|...| ....  | ... |...|

---
