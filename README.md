# Practica TP

### Ejercicio 2: HTTP

**1.** Un servidor HTTP es un software que tiene la capacidad de administrar las URLs y el protocolo HTTP. Se accede a este mediante los nombres de dominio de los sitios web que aloja, y despliega el contenido comprendido en los sitios web hacia el dispositivo del usuario.

**2.** Los verbos HTTP son unconjunto de métodos de petición que indican que acción realizar sobre un recurso determinado.

ALgunos ejemplos: 

Verbo  | Acción a realizar
------------- | -------------
GET | Recupera información desde un recurso
PUT  | Reemplaza la información de un recurso. Tambien puede actualizarlo
POST  | Se usa mayormente para crear un recurso.
DELETE | Suprime un recurso identificado en el URL

**3.** La comunicación HTTP usa un modelo de solicitud y respuesta. Siendo estos dos tipos de mensajes:
 - Request como solicitud al servidor;
 - Response como la respuesta que este otorga;

Los headers son la parte central de la comunicación http, contiene metadatos que se utilizan para la función del servidor.

**4.** Un queryString es una sección de la URL que nos permite enviar información al servidor.

**5.** El responseCode es el codigo que se envia al usuario como resultado de una respuesta del servidor. El significado de cada resultado varía en razón del accionar del servidor. Estos resultados se clasifican en cinco clases:

 - 1. Respuestas informativas
 
 - 2. Respuestas satisfactorias
 
 - 3. Redirecciones
 
 - 4. Errores de los clientes
 
 - 5. Errores de los servidores
 
**6.** La data en un GET se manda de una manera visible, mientras que en un POST es de una forma que no se puede observar.

**7.** El navegador usa un request GET al acceder a la página.

**8.** Las estructuras de datos JSON son dos tipos de estructuras:
 - Una estructura nombre/valor:
 ```json
{
 "ejemplo" : "valor"
}
```
 
 - Una lista ordenada de valores:
 ```json
{
 "ejemplo" : ["valor1" ,
              "valor2" ,
              "valor3" ]
}
```
 
 Y las estructuras de datos XML se llaman estructuras de árbol de XML, donde existen elementos que poseen otros elementos anidados, y cada uno de estos tiene sus propios atributos. Ejemplo de esta estructura: 
 ```xml
<persona>
	<nombre>Juan</nombre>
	<apellido>Garcia</apellido>
	<fecha-de-nacimiento>
		<dia>18</dia>
		<mes>octubre</mes>
	</fecha-de-nacimiento>
</persona>
```

**9.** SOAP es un protocolo estándar que se basa en XML y tiene la capacidad de transmitir mensajes en HTTP, como en otros protocolos de la web.

**10.** RESTful es un estandar que se encarga de compartir información mediante el canal de doble via request/response.

**11**  Los headers en el request llevan información necesaria para la comunicación y pueden incluir diferentes aspectos como: tipo de navegador que realiza la petición, dirección de la página solicitada, etc. 
Content-type indica alcliente cual es el tipo del dato que se retorna.

### Ejercicio 3: Request

![Screenshot_2044](https://user-images.githubusercontent.com/118482653/202579009-9442d682-0f35-4188-805c-922308671b15.png)
 > Punto 1.
 
 
![image](https://user-images.githubusercontent.com/118482653/202579101-b83d3bef-1e69-4043-881a-858fc3f39b39.png)
 > Punto 2.
 
 
![image](https://user-images.githubusercontent.com/118482653/202579354-2f5c8ea1-910b-495c-8d28-64630f3709a2.png)
 > Punto 3.
 
 
La diferencia entre el punto 1 y el 3 fue que el request POST cumplio su función y actualizó el recurso con los datos que incluí.

### Ejercicio 4: Traillhead

[Mi perfil de Trailhead](https://trailblazer.me/id/cotazu)

### Ejercicio 5: Diagrama

**Lead:** Se llama Lead al cliente potencial.

**Account:** Es donde se encuentran las cuentas de las empresas con las que se tiene relacion.

**Contact:** Es donde se guardan los contactos de los empleados que trabajan en las empresas con las que se tiene relacion.

**Opportunity:** Es donde se encuentran las oportunidades de ventas.

**Product:** Es donde se encuentran los detalles de los productos.

**PriceBook:** Es donde se encuentran los detallados los precios de los productos.

**Asset:** Es donde se encuentran los datos de un activo.

**Case:** Es donde se encuentan todos los casos de los contactos que se deben resolver.

###### Diagrama: 
![Diagrama](https://github.com/OtazuCiro/Practica-TP/blob/main/Diagrama%20Diagram.drawio.png)

### Ejercicio 6: Salesforce

###### Soluciones de Salesforce

**A. ¿Qué es Salesforce?** Salesforce es una plataforma de gestión de las relaciones con los clientes (CRM) basada en la nube que proporciona a todos los departamentos de su organización, incluidos los de marketing, ventas, servicio de atención al cliente y ecommerce, una visión unificada de sus clientes en una plataforma integrada.

**B. ¿Qué es Sales Cloud?** Sales Cloud es una herramienta de ventas todo en uno y CRM que combina la mayoría de las mismas capacidades que encontrarás en otras herramientas. Sin embargo, con Sales Cloud, obtienes las funciones de automatización de ventas que necesitas en un solo lugar.

**C. ¿Qué es Service Cloud?** Service Cloud es una solución completa de atención al cliente creada especialmente para dar soporte a los clientes a cualquier hora y en cualquier lugar, por teléfono, correo electrónico, redes sociales, chats y páginas o comunidades de auto ayuda.

**D. ¿Qué es Health Cloud?** Health Cloud es una plataforma especialmente diseñada para la gestión clínica de pacientes por medio de tecnologías on-cloud, la cual ofrece: una comunicación más personalizado entre pacientes, miembros, proveedores y prestadores de servicios de salud, y un mejor ajuste a los procesos, servicios y datos médicos según el perfil de cuidado de cada paciente.

**E. ¿Qué es Marketing Cloud?** Como parte de los servicios Salesforce, Marketing Cloud es un módulo de Salesforce que contiene múltiples herramientas para mejorar la interacción de las marcas con sus clientes y potenciales a través de todo tipo de canales.

###### Funcionalidades de Salesforce 
**A. ¿Qué es un RecordType?** Los Record Types en Salesforce nos permiten definir diferentes Business Process, Pages Layouts y Picklist Values en un determinado objeto. Así mismo, los Record Types nos ayudan a mostrar distintos tipos de información según el perfil del usuario.

**B. ¿Qué es un ReportType?**Un reporte es una lista de registros que cumplen los criterios que define. Se muestra en Salesforce en filas y columnas, y se puede filtrar, agrupar o mostrar en un diagrama gráfico. Cada reporte se almacena en una carpeta.

**C. ¿Qué es un Page Layout?**Los diseños de página controlan el diseño y la organización de botones, campos, s-controls, Visualforce, enlaces personalizados y listas relacionadas en páginas de registros de objetos.

**D. ¿Qué es un Compact Layout?** Un diseño compacto muestra los campos clave de un registro de un vistazo en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.

**E. ¿Qué es un Perfil?** Los perfiles definen cómo acceden los usuarios a objetos y datos y qué pueden hacer en la aplicación.

**F. ¿Qué es un Rol?** Los roles controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización. Usuarios en cualquier función dada pueden ver, editar, e informar sobre todos los datos para funciones por debajo de ellos en la jerarquía de roles.

**G. ¿Qué es un Validation Rule?** Las reglas de validación verifican que los datos que un usuario introduce en un registro cumplen con las normas que especifica antes de que el usuario guarde el registro. Una regla de validación puede contener una fórmula o expresión que evalúa los datos en uno o más campos y ofrece un valor “Verdadero” o “Falso”.

**H. ¿Qué diferencia hay entre una relación Master Detail y Lookup?** En las relaciones de búsqueda se usan cuando los objetos están relacionados solo en ciertos casos. Los objetos de las relaciones de búsqueda suelen funcionar como objetos independientes que tienen sus propias fichas en la interfaz de usuario. En las relaciones del tipo principal-detalle, el objeto de detalle no funciona de manera independiente. En realidad, este objeto depende del objeto principal. Por lo tanto, si se elimina un registro del objeto principal, también se eliminarán todos los registros relacionados del objeto de detalle. A la hora de crear relaciones principal-detalle, siempre se crea el campo de relación en el objeto de detalle.

**I. ¿Qué es un Sandbox?** Un Sandbox es una copia de su organización en un entorno aislado que puede usar para distintos fines, como pruebas y capacitación. Los sandbox están completamente aislados de su organización de producción de Salesforce.

**J. ¿Qué es un ChangeSet?** Un conjunto de cambios entrantes es un conjunto de cambios que se ha enviado desde otra organización de Salesforce a la organización en la que ha iniciado sesión. Un conjunto de cambios se debe implementar para que los cambios surtan efecto.

**K. ¿Para qué sirve el import Wizard de Salesforce?** Data Import Wizard es una herramienta de carga de datos integrada en Salesforce para todas las ediciones.

**L. ¿Para qué sirve la funcionalidad Web to Lead?** Puede utilizar los formularios Web-to-Lead para definir una campaña o fuente de clientes potenciales colocando valores dentro de los campos ocultos. Estos valores jugarán un papel clave en el respaldo de las acciones automatizadas una vez que los clientes potenciales lleguen a Salesforce.

**M. ¿Para qué sirve la funcionalidad Web to Case?** Recopile las solicitudes de servicio de atención al cliente directamente del sitio web de su empresa y genere automáticamente casos nuevos con Caso Web.

**N. ¿Para qué sirve la funcionalidad Omnichannel?** Omni- canal es una función personalizable y flexible que se puede configurar de forma declarativa en Salesforce, es decir, sin necesidad de escribir código. OmniCanal ayuda al enrutamiento automático de diferentes tipos de elementos de trabajo (como casos y clientes potenciales) a los agentes.

**O. ¿Para qué sirve la funcionalidad Chatter?** Chatter es una aplicación de colaboración en tiempo real de Salesforce que permite a sus usuarios trabajar juntos, comunicarse y compartir información.

###### Conceptos generales

**A. ¿Qué significa SaaS?** El software como servicio (SaaS) es un modelo de entrega de software basado en la nube en el que el proveedor de la nube desarrolla y mantiene el software de las aplicaciones en la nube, proporciona actualizaciones automáticas del mismo y lo pone a disposición de sus clientes a través de Internet con un sistema de pago por uso.

**B. ¿Salesforce es Saas?** No, Salesforce es una compañia de PaaS

**C. ¿Qué significa que una solución sea Cloud?** Cloud computing es la disponibilidad bajo demanda de recursos de computación como servicios a través de Internet. Esta tecnología evita que las empresas tengan que encargarse de aprovisionar, configurar o gestionar los recursos y permite que paguen únicamente por los que usen.

**D. ¿Qué significa que una solución sea On-Premise?** El termino on-premises se refiere al hecho que los titulares de la licencia instalan el software en su propio entorno informático, sin recurrir a la nube o necesitar acceso a internet.

**E. ¿Qué es un pipeline de ventas?** El pipeline de ventas se refiere a cada uno de los pasos de su proceso de ventas que sigue un representante de ventas para llevar una venta desde el principio hasta el final.

**F. ¿Qué es un funnel de ventas?** El embudo de ventas es una forma de medir y conocer mucho mejor a tus clientes potenciales o buyer persona. Abarca todas las actividades, desde atraer nuevos visitantes hasta la generación de ventas con una estrategia de Inbound Marketing incrementando así la facturación mensual de tu negocio.

**G. ¿Qué significa Customer Experience?** La experiencia del cliente es cómo se relaciona una empresa con sus clientes en todos los aspectos del recorrido de compra, desde el marketing hasta las ventas y el servicio al cliente pasando por cada punto intermedio. En gran parte, es la suma total de todas las interacciones que un cliente tiene con tu marca.

**H. ¿Qué significa omnicanalidad?** La omnicanalidad es una estrategia de marketing que crea experiencias valiosas entre una empresa o negocio y sus clientes, a través de todos los medios de contacto que tiene vigentes, ya sean físicos o digitales.

**I. ¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea B2C?¿Qué es un KPI?** El B2B (business to business) es el modelo de negocio en el que se realizan transacciones comerciales entre empresas. En cambio, en el modelo B2C (business to consumer) esas transacciones se efectúan entre negocios y los consumidores. El KPI (Key Performance Indicator o, en Español, Indicador Clave de Rendimiento) es un sistema de medición que, expresado normalmente en un porcentaje, nos dice el grado de progreso o cumplimiento de un objetivo de la empresa.

**J. ¿Qué es una API y en qué se diferencia de una Rest API?** Por lo general, la API sigue el formato de aplicación a aplicación, mientras que REST sigue una estructura diferente: Cliente-Servidor. El cliente y el servidor están evolucionando de forma independiente, proporcionando más flexibilidad en el trabajo.

**K. ¿Qué es un Proceso Batch?**  El modo de lotes ejecuta una serie de procesos de Cargador de datos en un orden concreto utilizando un archivo por lotes. Puede volver a ejecutar la misma secuencia de procesos utilizando un archivo.

**L. ¿Qué es Kanban?** La metodología Kanban se implementa por medio de tableros Kanban. Se trata de un método visual de gestión de proyectos que permite a los equipos visualizar sus flujos de trabajo y la carga de trabajo. En un tablero Kanban, el trabajo se muestra en un proyecto en forma de tablero organizado por columnas.

**M. ¿Qué es un ERP?** La planificación de recursos empresariales, también conocida como ERP, es un sistema que ayuda a automatizar y administrar los procesos empresariales de distintas áreas: finanzas, fabricación, venta al por menor, cadena de suministro, recursos humanos y operaciones.

**N. ¿Salesforce es un ERP?** Salesforce es un CRM ya que se involucra en la gestion en las relaciones con los clientes, mientras que el ERP se ocupa de la planificacion de los recursos empresariales.

