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

 1 Respuestas informativas
 2 Respuestas satisfactorias
 3 Redirecciones
 4 Errores de los clientes
 5 Errores de los servidores
 
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
**Account:** Se refiere a una 
