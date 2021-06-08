# Virtual-Dreams---Nogueira-Ignacio



EJERCICIO 1:

-Item 1:
![Visual Studio Code:](https://user-images.githubusercontent.com/85534808/121243570-3a037a00-c874-11eb-9b3b-c6720ff4b36e.png)

-Item 2:
![GIT y GIT Bash:](https://user-images.githubusercontent.com/85534808/121243795-851d8d00-c874-11eb-8794-477401c4fbae.png)





EJERCICIO 2:

Las siguientes preguntas están orientadas a la comprensión del protocolo HTTP. Son agnósticas al lenguaje de programación, la idea es comprender los conceptos del estándar:

1.	¿Qué es un servidor HTTP? 

Un servidor HTTP es un software, que tiene como tarea devolver información que permite a los usuarios que recurren a él, la visualización de una página web en su navegador.


2.	¿Qué son los verbos HTTP? Mencionar los más conocidos

Los verbos HTTP son un conjunto de métodos de petición, para indicar una acción que quiere ser implementada por el usuario, a un recurso en específico, en donde cada uno de ellos aplica una semántica diferente, a pesar de que algunos compartan características similares. Los más conocidos son: GET, HEAD, POST, PUT, PATCH, entre otros.

3.	¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 

Son dos conceptos que están ligados a la comunicación por internet que permiten intercambiar datos básicos, en el que todo empieza con un request enviado por el cliente, y termina con un response del servidor web. Un ejemplo que podría dar sería que, un usuario con su navegador web quiera acceder a un sitio web, en donde envía un request hospeado en un servidor, y el mismo devuelve un response mostrando la interfaz de una web para poder interactuar en ella. Para responder la última pregunta, los headers son los encargados centrales de transmitir la información acerca de la página solicitada, del servidor, etcétera. 

4.	¿Qué es un queryString? (En el contexto de una url)

En el contexto de una URL, un queryString es el parámetro de cadena de consulta URL para obtener la localización de la web y sus recursos.

5.	¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?

Un responseCode, como hace referencia su nombre, nos devuelve una respuesta que fue solicitada en el software de HTTP, el cual arroja diferentes resoluciones como respuestas informativas, satisfactorias, redirecciones y errores de los clientes, y de los servidores.

6.	¿Cómo se envía data en un Get y cómo en un POST? 

Los datos se envían de dos maneras, en el que con el método Get se pasan usando una dirección URL que se guardan en conjunto con su dirección para, si es que desea, consultarla nuevamente, y el método POST se envía por un formulario donde los parámetros de solicitud HTTP no puedan ser visibles para “ofrecer discreción”.


7.	¿Qué verbo http utiliza el navegador cuando accedemos a una página?

El verbo que se utiliza es el GET, ya que nos conecta a un proxy para obtener su dirección URL completa y acceder al contenido de la página web.

8.	Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.

-JSON: es un formato de intercambio de datos, basado en texto estándar, para representar una jerarquía estructurada de los mismos que permite compartir información a través de diversas aplicaciones.
-XML: también es un formato de intercambio de datos, con la diferencia que en esta estructura es más complicada de entender, y tiene un formato más estricto que conlleva más tiempo procesar. 
Un ejemplo de estructuras podría ser: La información que posee un individuo como su DNI, nacionalidad, sexo, etc.

9.	Explicar brevemente el estándar SOAP

SOAP deriva de las siglas Simple Object Access Protocol. Es un protocolo simple y esencial para los servicios web, que permite intercambiar información en diversos entornos entre remitentes y destinatarios.  Es utilizado, por ejemplo, en tiendas online y otros muchos servicios que sin él no sería posible establecer comunicación entre el cliente y el servicio.

10.	Explicar brevemente el estándar REST Full

Un estándar REST (Representational State Transfer) es una técnica de arquitectura de software, que permite construir un conjunto de principios y patrones de comunicación para ayudar a crear APIs RESTful, que son traductores para conectar sistemas, softwares y aplicaciones. En pocas palabras, funciona como estándar para compartir información de manera que se pueda consultar y responder.

11.	¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?

Los headers son los encargados de mostrar la información que no se encuentra en el body de la request, el idioma, el navegador del cliente, entre otros. El key content-type es la propiedad del header para indicar el tipo de contenido que va a retornar el navegador para interpretar los contenidos devueltos.




EJERCICIO 3:

Recomendamos previamente entender los conceptos de la sintaxis “json” antes de arrancar con los ejercicios.
Descargar el POSTMAN (aplicación para realizar request como cliente), adjuntando un screen de resolución para cada ítem:


1.	Realizar un request GET a la URL: 
https://vdfactory-234311.firebaseio.com/contacts.json

![Ejercicio 3 - Item 1](https://user-images.githubusercontent.com/85534808/121247591-cca61800-c878-11eb-8dc4-ef64848a2d68.png)


2.	Realizar un request POST a la URL anterior, y con body:
{
	"firstname":"Pablo",
	"email":"pablo.perez@virtualdreams.io"
}
Tip: (Marcar la opción “raw” como body)


![Ejercicio 3 - Item 2](https://user-images.githubusercontent.com/85534808/121247608-d29bf900-c878-11eb-8006-6e66329b884f.png)


3.	Realizar nuevamente un request GET a la URL: 
https://vdfactory-234311.firebaseio.com/contacts.json
¿Qué diferencias se observan entre las llamadas el punto 1 y 3?

- La diferencia que encuentro es que ahora se pasan mis datos a la estructura.

![Ejercicio 3 - Item 3](https://user-images.githubusercontent.com/85534808/121247641-dd568e00-c878-11eb-8d9b-83c1f6fd0a1a.png)


EJERCICIO 4:

Solicitar usuario de Trailhead enviando un email a ariel.tarsitano@virtualdreams.io

Cambiar el idioma de Trailhead a inglés.
Realizar los siguientes módulos de Trailhead:

●	Fundamento de la plataforma Salesforce
●	Fundamentos de Apex y .NET
●	Modelado de datos
●	Fundamentos y base de datos de Apex
●	Desencadenadores de Apex
●	Apex Integration Services

Se recomienda usar el mismo Playground para todos módulos solicitados. Excepto que se solicite crear uno nuevo en el enunciado del Módulo.
Para revisar la resolución de los módulos, compartir la URL del perfil público de Trailhead en una url dentro del Readme.

- Link perfil trailhead: https://trailblazer.me/id/ignogueira





EJERCICIO 5:

Explicar que son conceptualmente, qué datos almacenan en forma estándar y cómo se relacionan el resto (algunos no se relacionan entre sí) cada uno de los siguientes objetos de Salesforce:

1.	Lead:

Representa un prospecto que se puede convertir en oportunidad, contacto y cuenta. En resumen, son las personas que están interesadas en comprar nuestro producto o servicio. Como se puede convertir en registros de oportunidad, contacto y cuenta, se relaciona con ellos. Datos que almacena: Adress, Annual Revenue, Campaign, Clean Status, Company, Company D-U-N-S Number, Created By, Current Generator(s), D&B Company, Data.com Key, Description, Do Not Call, Email, Email Opt Out, Fax, Fax Opt Out, Individual, Industry, Last Modified By, Last Transfer Date, Lead Owner, Lead Source, Lead Status, Mobile, Name, No. Of Empleoyees, Number of Locations, Phone, Primary, Product interest, Rating, Sic Code, Title y Website.

2.	Account:

Account representa una cuenta individual, donde es una persona o una organización que está relacionada con los negocios del consumidor, las oportunidades, los contactos, en donde se encuentran competidores, socios y clientes. Almacena los siguientes datos de forma estándar: Account Name, Account Number, Account Owner, Account Site, Account Source, Active, Annual Revenue, Billing Address, Clean Status, Created By, Customer Priorty, D&B Company, Data.com Key, Description, D-U-N-S Number, Empleoyes, Fax, Industry, Last Modified By, Match Billing Address, NAICS Code, NAICS Description, Number of Locations, Ownership, Parent Account, Phone, Rating, Shipping Address, SIC Code, SIC Description, SLA, SLA Expiration Date, SLA Serial Number, Ticker Symbol, Tradestyle, Type, Upsell Opportunity, Website y Year Started.

3.	Contact:

Representa un contacto, donde es una persona que se asocia a la cuenta. Por ejemplo, una cuenta puede ser una empresa como Samsung, y el contacto es la persona con la que te comunicaste. Se relaciona directamente con Asset y Case. Almacena los siguientes datos de forma estándar: Account Name, Assistant, Asst. Phone, Birthdate, Clean Status, Contact Owner, Created By, Data.com Key, Department, Description, Do Not Call, Email. Email Opt Out, Fax, Fax Opt Out, Home Phone, Individual, Languages, Last Modified By, Last Stay-in-Touch Request Date, Last Stay-in-Touch Save Date, Lead Source, Level, Loan Amount, Mailing Address, Mobile, Name, Other Address, Other Phone, Phone, ¿Prequalified?, Reports To y Title. 

4.	Opportunity:

Hace referencia a una venta o un trato pendiente con el cliente. Está vinculada al Case. Los datos estándar que posee son Account Name, Amount, Close Date, Contract, Created By, Current Generator(s), Delivery/Installation Status, Description, Expected Revenue, Forecast Category, Last Modified By, Lead Source, Main Competitor(s), Next Step, Opportunity Name, Opportunity Owner, Opportunity Score, Order Number, Price Book, Primary Campaign Source, Private, Probability (%), Quantity, Stage, Tracking Number y Type. 

5.	Product:

Como hace referencia el nombre, básicamente es el producto o servicio que ofrece la empresa al cliente. Son aquellos que podés agregar en oportunidades. Se relaciona con Case y Asset. Los datos que almacenan son Active, Created By, Display URL, External Data Source, External ID, Last modified By, Product Code, Product Description, Product Family, Product Name, Product SKU y Quantity Unit Of Measure.


6.	PriceBook:

Representa una lista de precios que tu empresa pone a la venta de los productos que ofreces. En el que, con tal del cliente con el que te relaciones, pueden existir descuentos, beneficios, etc. Está unido a las oportunidades. Los datos que almacena PriceBook son Active, Created By, Description, Is Standard Price Book, Last Modified By y Price Book Name.


7.	Quote:

Es un presupuesto en el cual te detalla los precios de los productos y servicios que van quedando registrados en la empresa. Este objeto se relaciona con la oportunidad. Almacena de forma estándar a AccountId, Additional Address, Additional City, Additional Country, Additional Country Code, Additional Latitude, Additional Longitude, Additional Name, Additional Postal Code, Additional State, Additional State Code, Additional Street, Billing Address, Billing City, Billing Country, Billing Country Code, Billing Latitude, Billing Longitude, Billing Name, Billing Postal Code, Billing State, Billing State Code, Billing Street, can Create Quote Line Items, Contact Id, Contract Id, Currency Iso Code, Description, Discount, Email, Expiration Date, Fax, Grand Total, Is Syncing, Last Reference Date, Last Viewed Date, Line Item Count, Name, Opportunity Id, Phone, Pricebook 2 Id, Quote Number, Quote To Address, Quote To City, Quote To Country, Quote to Latitude, Quote To Longitude, Quote To Name, Quote To Postal Code, Quote To State, Quote To Street, Record Type Id, Shipping Address, Shipping City, Shipping Country, Shipping Country Code, Shipping Handling, Shipping Latitude, Shipping Longitude, Shipping Name, Shipping Postal Code, Shipping State, Shipping State Code, Shipping Street, Status, Subtotal, Tax y Total price.


8.	Asset:

Este término simboliza un objeto de valor comercial, tanto como un producto vendido por tu compañía o competidor, u otros activos. Se relaciona con productos. Contiene de forma estándar datos como Account, Asset Level, Asset Name, Asset Owner, Asset Provided By, Asset Serviced By, Competitor Asset, Contact, Created Bym Current Amount, Current Lifecycle End Date, Current Monthly Recurring Revenue, Current Quantity, Description, Digital Asset Status, External Id, Has Lifecycle Management, Install Date, Infernal Asset, Last Modified By, Lifecycle End Date, Lifecycle Start Date, Manufacture Date, Parent Asset, Price, Product, Product Code, Product Description, Product Family, Product SKU, Purchase Date, Quantity, Root Asset, Serial Number, Status, Status Reason, Total Lifecycle Amount, Unique Identifier, Usage y End Date.

9.	Case:

Representa las preguntas, feedbacks o problemas del cliente. Está conectado con Asset. Los objetos que se relacionan de forma estándar con Case son Account Name, Asset, Business Hours, Case Number, Case Origin, Case Owner, Case Reason, Closed When Created, Contact Email, Contact Fax, Contact Mobile, Contact Name, Contact Phone, Created By, Date/Time Closed, Date/Time Opened, Description, Engineering Req Number, Entitlement Name, Entitlement Process End Time, Entitlement Process Start Time, Escalated, Internal Comments, Last Modified By, Milestone Status Icon, Parent Case, Potential Liability, Priority, Product (tanto Lookup, como Picklist), Service Contract, SLA Violation, Status, Stopped, Stopped Since, Subject, Type, Web Company, Web Email, Web Name y Web Phone.
 
10.	Article:

Por último, esta definición alude a una categoría de datos que se clasifica como un artículo que puede ser usado para asociar a un grupo de categorías o consultas de las mismas. Este objeto no se relaciona con ningún otro. Los objetos que contiene de forma estándar son Data Category Group Name, Data Category Name y Parent Id.

Link Diagrama - Ejercicio 5
![Link Diagrama:](https://github.com/IgnacioNogueira/Virtual-Dreams---Nogueira-Ignacio/blob/50c7a57792a9b5ffe14112c2ee6ae1ba14c3dd8f/Diagrama%20-%20Ejercicio%205.png)





EJERCICIO 6
Realizar las siguientes actividades sobre el Playground 1 del ejercicio 4:

A.	Consultar tu ID haciendo un GET con POSTMAN a este WS:
https://vdfactory-234311.firebaseio.com/contacts.json

![Ejercicio 6 - item A](https://user-images.githubusercontent.com/85534808/121247860-1abb1b80-c879-11eb-8c5a-64b013c80b58.png)


B.	Agregar un campo al objeto Contact llamado idvirtualdreams de tipo texto de 255 caracteres:

![Ejercicio 6 - Item B](https://user-images.githubusercontent.com/85534808/121247234-5f928280-c878-11eb-8eff-71f0c51538cc.png)


C.	Desarrollar un trigger para que cuando un usuario Modifica o Crea un contacto de Salesforce completando el campo generado el punto B con el ID del punto A, se invoque al Web Service con el idvirtualdreams obtenga los datos del nombre y el email de la respuesta y actualice el campo email del contacto. Usar Playground 1.

Traté de resolver el punto c haciendo un trigger de la siguiente forma:

trigger WhenModifyorCreate on Contact (after insert, after update) {
    
    if(Trigger.isInsert || Trigger.isUpdate)
     {
            
    Http http = new Http();
    HttpRequest request = new HttpRequest();
    request.setEndpoint('https://vdfactory-234311.firebaseio.com/contacts.json');
    request.setMethod('GET');
    request.setHeader('Content-Type', 'application/json;charset=UTF-8');
        request.setBody('{"firstname":"Ignacio","email":"ignacio.nogueira@hotmail.com","-MbBsOGPVvnq4Q_f6rVO"}');
    
    HttpResponse response = http.send(request);
       if (response.getStatusCode() != 201) {
        System.debug('The status code returned was not expected: ' +
            response.getStatusCode() + ' ' + response.getStatus());
    } else {
        System.debug(response.getBody());
    	}
    }
}


En donde traté de hacer un llamado a la request para obtener el mail con la ID, pero no pude avanzar en asignarlo al campo de Salesforce los datos. 


EJERCICIO 7

Responder las siguientes preguntas brevemente sobre:
Soluciones de Salesforce

A.	¿Qué es Salesforce?

Es una plataforma de gestión de relación con los clientes, basada en una nube que habilita a todos los departamentos y sectores de una organización de trabajo, una visión unificada en una plataforma integrada.

B.	¿Qué es Sales Cloud?

Sales Cloud es un módulo de Salesforce que permite gestionar de forma rápida e inteligente las relaciones con clientes y colaboraciones que se presentan entre equipos comerciales.


C.	¿Qué es Service Cloud?

Es un software de servicio al cliente, creada para dar soporte a cualquier hora y lugar, ya sea tanto por teléfono, correo electrónico, redes sociales, chats y páginas o comunidades de auto ayuda.

D.	¿Qué es Health Cloud?

Es una plataforma desarrollada para la gestión clínica de pacientes por medio de tecnologías on-cloud. Esto permite ofrecer una comunicación más personalizada entre pacientes, miembros y prestadores de servicio de la salud para optimizar servicios médicos, según el perfil de cada paciente.

E.	¿Qué es Marketing Cloud?

Es también una plataforma de CRM (Customer Relationship Management) que recoge múltiples datos que habilitan a los clientes a generar herramientas para la obtención de experiencias personalizadas y automatizadas para medir resultados estratégicos de marketing en una organización.
Funcionalidades de Salesforce
A.	¿Qué es un RecordType?

Es un registro que permite definir diferentes conjuntos de valores de lista de selección, para listas estándar y personalizadas. Esto alude al soporte de implementación de procesos empresariales personalizados.

B.	¿Qué es un ReportType?

Un ReportType es un reporte donde se incluyen objetos, que permiten obtener informes a respuestas como, por ejemplo, las palabras claves que buscan los usuarios para encontrar oportunidades empresariales.

C.	¿Qué es un Page Layout?

El Page Layout es el encargado de controlar los diseños de página, la organización de botones, campos, etiquetas, enlaces personalizados, entre otros. En síntesis, es la personalización del entorno de la página.

D.	¿Qué es un Compact Layout? 

Es un formato compacto que muestra los campos clave de un registro en la aplicación de Salesforce como el nombre de la cuenta, el sitio web de una empresa, números de teléfono para contacto, etc. 

E.	¿Qué es un Perfil?

Se define un perfil a la información que se le asigna a un usuario, donde contiene sus objetos y datos para otorgarle una identidad, así poder ser visualizado por otros usuarios.

F.	¿Qué es un Rol?

Un rol es una asignación donde se jerarquiza a los usuarios para controlar su nivel de visibilidad y edición sobre los datos de una organización.

G.	¿Qué es un Validation Rule?

Son reglas que verifican que los datos ingresados por usuarios cumplan los estándares que especifica antes de poder guardarlos. Pueden ser fórmulas o expresiones que evalúan los datos de uno o más campos y hasta ofrecer un valor.

H.	¿Qué diferencia hay entre una relación Master Detail y Lookup?

La principal diferencia se encuentra en su comportamiento y el intercambio de registros sobre los que se necesita leer, cada uno aporta sus beneficios y no están muy ligados. El tema está en si se desea crea un campo de resumen en el objeto principal. Si es así, se crea un Master Detail, de lo contrario se crea un Lookup. Un master Detail te vincula automáticamente con otro objeto, mientras que un Lookup también es un vínculo con otro objeto, en el que se puede elegir el registro que deseas de ese objeto.

I.	¿Qué es un Sandbox?

Son entornos que simulan una réplica de una organización de producción, donde se incluyen sus datos como registros de objetos, datos adjuntos y metadatos, en donde los desarrolladores pueden modificar la interfaz de lo mencionado previamente, debido a que es un ambiente para realizar pruebas.

J.	¿Qué es un ChangeSet?

Es un conjunto de cambios que se establecen para enviar personalizaciones de una organización Salesforce a otra. Por ejemplo, se puede probar un nuevo tipo de objeto en una organización para analizarlo y luego hacerle cambios e implementarlo para sus diversos metadatos, mediante funciones de API de metadatos.  

K.	¿Para qué sirve el import Wizard de Salesforce?

Básicamente es un apartado visual, que sirve para mostrar información clave que necesita visualizar el usuario de manera sencilla, en un cuadro gráfico en forma de tablero.

L.	¿Para qué sirve la funcionalidad Web to Lead?

Permite diseñar un formulario que incluye las preguntas más adecuadas para cada tipo de negocio, con el objetivo de insertarlo en un blog o una web corporativa, automatizando la captación de usuarios y su integración de datos.

M.	¿Para qué sirve la funcionalidad Web to Case?

La funcionalidad del Web to Case permite, ya obtenido un formulario de Salesforce, confirmar y corroborar en la ficha de casos la información almacenada, es decir revisar los sus detalles.

N.	¿Para qué sirve la funcionalidad Omnichannel?

Omnichannel es un servicio de atención al cliente, donde tiene como objetivo proporcionar una experiencia al cliente a través de múltiples canales (páginas web, chat en vivo, aplicaciones para celulares, etc.) para integrarlo al sistema de Salesforce, y así poder brindarle una mejor experiencia que esté en constante contacto con el usuario.

O.	¿Para qué sirve la funcionalidad Chatter?

Es una herramienta de comunicación que está diseñada, especialmente en celulares, para la interacción y retroalimentación instantánea, el intercambio de archivos y la utilización de encuestas entre los miembros de tu departamento comercial.
Conceptos generales
A.	¿Qué significa SaaS? ¿Salesforce es Saas?

SaaS, significa “Software as a Service”, en donde se les ofrece a los usuarios la posibilidad de conectarse a las aplicaciones alojadas en una nube a través de internet. Salesforce es una empresa de PaaS (Plataforma como Servicio), que es un concepto que nace como resultado de la aplicación al desarrollo de Software del modelo SaaS (Software como Servicio).

B.	¿Qué significa que una solución sea Cloud?

La solución Cloud hace referencia a una tecnología que permite acceso remoto a softwares, almacenamiento de archivos y procesamiento de datos por medio de Internet, siendo así, una alternativa a la ejecución en una computadora personal o servidor local.

C.	¿Qué significa que una solución sea On-Premise?

Solución On-Premise hace referencia a un tipo de instalación de una solución de software que se lleva a cabo dentro de un servidor y la infraestructura de la empresa. Este modelo hace responsable de su seguridad, disponibilidad y gestión de software.

D.	¿Qué es un pipeline de ventas?

Es una representación visual que abarca todos los pasos del proceso de ventas. El proceso de ventas difiere de negocio en negocio, por lo que el pipeline de ventas debe ser único y reflejar el trayecto de un cliente en específico.

E.	¿Qué es un funnel de ventas?

Es un sistema diseñado para atraer a posibles usuarios para transformarlos en potenciales clientes, y por ende aumentar la frecuencia de compra en una empresa. 

F.	¿Qué significa Customer Experience?

Es una disciplina estratégica que le da valor a una compañía, ya que puede elevar los datos de sus ventas y captar consumidores. No se trata tanto de convencer a una persona de que compre un producto o adquiera un servicio, sino de generar una relación con el consumidor y la marca. 

G.	¿Qué significa omnicanalidad?

Omnicanalidad significa que los canales de comunicación están integrados y son sincrónicos. Un ejemplo, sería que un usuario mantiene la comunicación con una empresa a través de llamadas telefónicas o videollamadas, pero al mismo tiempo tiene la disponibilidad de enviar un correo electrónico y también de visitar una sucursal física.


H.	¿Qué significa que un negocio sea B2B?

B2B (Business to Business) significa que el modelo del negocio en las transacciones de bienes o prestación de servicios se producen entre dos empresas que pueden ser particulares o no. Es decir, es una forma de funcionar entre empresas directamente (“negocio a negocio”), que se debe a que engloba las operaciones de carácter comercial que las firmas realizan entre ellas y sin depender del cliente final (Las compañías tienen como objetivo otras empresas, en lugar de un consumidor).

I.	¿Qué significa que un negocio sea B2C?

B2C (Business to Consumer) significa que, dentro de los negocios, suelen enfocarse a situaciones en las que el número de clientes potenciales es alto. Normalmente crean un tráfico de este público y logran fidelizar a los consumidores, lo que deja en claro la diferencia que tiene con B2B, que se enfoca en el comercio entre empresas.

J.	¿Qué es un KPI?

Los KPI (Key Performance Indicators) son todas las variables, factores y unidades de medida para generar una estrategia de marketing que te permiten medir el rendimiento de un proceso y representar un valor relacionado con una meta que se fijó previamente para definir una línea de acción futura.

K.	¿Qué es una API y en qué se diferencia de una Rest API?

La diferencia que existe es que, la API especifica cómo los componentes de software deben interactuar entre sí utilizando el protocolo web (HTTP) como intermediario y las REST APIs suelen utilizar el protocolo de comunicación de la web (nuevamente, HTTP), pero estas no están limitadas de la misma manera que lo es un servicio web

L.	¿Qué es un Proceso Batch?

Un proceso Batch, es un conjunto de registros que garantizan la integridad de los datos y la trazabilidad en los procesos productivos. Son por ejemplo valores del proceso (directos y/o calculados), mensajes de eventos, alarmas, notas del operador, etc.

M.	¿Qué es Kanban?

Se define como un sistema de producción altamente efectivo y eficiente, que ha contribuido a generar un panorama manufacturero óptimo y competitivo, cuyo objetivo es gestionar de manera general cómo se van completando las tareas.

N.	¿Qué es un ERP? ¿Salesforce es un ERP?

Un ERP (Enterprise Resource Planning) es un software que recopila los datos de las transacciones compartidos por las diversas fuentes de una organización, elimina la duplicación de los datos y proporciona una integridad de datos con una única fuente de confianza. SÍ, es un ERP ya que trata las necesidades los usuarios en diferentes campos con tecnología innovadora en un software unificado, mediante una plataforma integrada para todos los sectores de una organización.

