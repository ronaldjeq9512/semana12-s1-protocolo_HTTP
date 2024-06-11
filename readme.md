# 1. CRUD
CRUD es un acrónimo que representa las cuatro operaciones básicas de persistencia de datos en una base de datos o un sistema de almacenamiento:

## A. Crear (Create): 
Se utiliza para crear un nuevo recurso. En HTTP, generalmente se asocia con el método POST.

## B. Leer (Read): 
Se utiliza para leer o recuperar recursos. En HTTP, generalmente se asocia con el método GET.

## C. Actualizar (Update): 
Se utiliza para actualizar un recurso existente. En HTTP, generalmente se asocia con el método PUT o PATCH.

## D. Eliminar (Delete): 
Se utiliza para eliminar un recurso. En HTTP, generalmente se asocia con el método DELETE.


# 2. Verbos HTTP
## GET:
Recupera datos de un servidor en función de un identificador determinado.
## POST: 
Envía datos al servidor para crear o actualizar un recurso.
## PUT: 
Envía datos al servidor para crear o reemplazar un recurso.
## DELETE: 
Elimina un recurso en el servidor basado en un identificador determinado.

# 3. Códigos de Respuesta HTTP
Los códigos de respuesta HTTP indican el resultado de una solicitud HTTP. Algunos de los códigos más comunes incluyen:
## 200 OK: 
La solicitud ha tenido éxito.
## 201 Created: 
La solicitud ha tenido éxito y se ha creado un nuevo recurso.
## 400 Bad Request: 
La solicitud no pudo ser entendida o fue malformada.
## 401 Unauthorized: 
La autenticación es necesaria y ha fallado o no se ha proporcionado.
## 403 Forbidden: 
El servidor entendió la solicitud, pero se niega a autorizarla.
## 404 Not Found: 
El recurso solicitado no pudo ser encontrado.
## 500 Internal Server Error: 
El servidor encontró una condición inesperada que le impidió completar la solicitud.

# 4. API
Una API (Interfaz de Programación de Aplicaciones) es un conjunto de reglas y definiciones que permiten que diferentes aplicaciones se comuniquen entre sí. Las APIs definen cómo se realizan las solicitudes y respuestas entre las aplicaciones.

# 5. API REST
REST (Transferencia de Estado Representacional) es un estilo arquitectónico para diseñar APIs en formato json.

# 6. Endpoint
Un endpoint es una URL que expone una API y permite que las aplicaciones se comuniquen con ella. Cada endpoint es un punto de acceso único para un recurso específico en una API.

# 7. CORS
CORS (Compartición de Recursos de Origen Cruzado) es un mecanismo de seguridad que permite que los recursos en una página web se soliciten desde un dominio diferente al dominio desde el cual se sirvió el recurso. Esto es importante para habilitar aplicaciones web que dependen de recursos alojados en diferentes dominios.

# 8. Cabecera (Header)
Las cabeceras HTTP son componentes de una solicitud y respuesta HTTP que transportan información adicional, un ejemplo de ello puede ser el token.