# TrabajoP5
Refactorizar la aplicación del Ejercicio 2 - practico 3 (3 capas) para convertirla en una API REST.

las caracteristicas que definen a una API REST son:

el uso de metodos HTTP estandar: Se utilizan los metodos GET, POST, PUT y DELETE

donde cada producto se considera un recurso que puede ser manipulado mediante su URL

las URLs claras y uniformes

la separación de cliente y servidor: La API no depende de como el cliente (frontend) maneja los datos; simplemente expone los recursos

un formato estandar de respuesta: Las respuestas se envian en formato JSON, siguiendo buenas practicas de interoperabilidad.
------------

la diferencia de la de 3 capas, es una aplicacion cliente local (browser + localStorage), la acutal, API REST que expone recursos por HTTP

es su comunicacion anterior es directa en el navegador, la actual se comunica atravez de peticiones HTTP

en las 3 capas el aAlmacenamiento de datos	esta en un LocalStorage en navegador, ahora es	base de datos simulada (json-server)

la enterior su escabilidad es limitada, la actual esta mas preparada para crecer
