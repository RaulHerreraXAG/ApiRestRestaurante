
API REST de Restaurantes
Esta API proporciona endpoints para realizar operaciones relacionadas con la gestión de restaurantes.

Obtener todos los restaurantes
http
Copy code
GET /api/restaurante/
Este endpoint devuelve una lista con todos los restaurantes disponibles en la base de datos.

Obtener restaurante por ID
http
Copy code
GET /api/restaurante/id/{id}
Este endpoint permite obtener un restaurante específico mediante su identificador único (id).

Obtener restaurante por nombre
http
Copy code
GET /api/restaurante/nombre/{nombre}
Este endpoint devuelve un restaurante buscándolo por su nombre.

Obtener restaurantes por estrellas
http
Copy code
GET /api/restaurante/estrellas/{estrellas}
Devuelve una lista de restaurantes que tienen la cantidad de estrellas especificada.

Obtener restaurante por ubicación
http
Copy code
GET /api/restaurante/ubicacion/{ubicacion}
Obtiene un restaurante por su ubicación.

Obtener restaurante por tipo de comida
http
Copy code
GET /api/restaurante/gastronomia/{gastronomia}
Devuelve una lista de restaurantes que ofrecen el tipo de comida especificado.

Obtener restaurantes con menú del día
http
Copy code
GET /api/restaurante/menuDia/{menuDelDia}
Obtiene una lista de restaurantes que ofrecen menú del día o no, según el parámetro menuDelDia.

Obtener restaurantes con menú infantil
http
Copy code
GET /api/restaurante/menuInfantil/{menuInfantil}
Devuelve una lista de restaurantes que ofrecen menú infantil o no, según el parámetro menuInfantil.

Obtener restaurantes por precio medio
http
Copy code
GET /api/restaurante/precioMedio/{precioMedio}
Este endpoint devuelve una lista de restaurantes con un precio medio igual al proporcionado.

Obtener nombres de todos los restaurantes
http
Copy code
GET /api/restaurante/listaNombres
Devuelve una lista con los nombres de todos los restaurantes disponibles.

Obtener cantidad total de restaurantes
http
Copy code
GET /api/restaurante/cantidad
Este endpoint devuelve la cantidad total de restaurantes registrados en la base de datos.

Obtener restaurantes con una puntuación igual o mayor
http
Copy code
GET /api/restaurante/estrellasMinima/{estrellasMinima}
Devuelve una lista de restaurantes con una puntuación igual o mayor a la proporcionada.

Obtener restaurantes con un precio máximo
http
Copy code
GET /api/restaurante/precioMaximo/{precioMax}
Obtiene una lista de restaurantes con un precio máximo indicado.

Obtener restaurantes con un precio mínimo
http
Copy code
GET /api/restaurante/precioMinimo/{precioMin}
Este endpoint devuelve una lista de restaurantes con un precio mínimo indicado.

Crear un nuevo restaurante
http
Copy code
POST /api/restaurante/post
Crea un nuevo restaurante y lo guarda en la base de datos.

Actualizar información de un restaurante
http
Copy code
PUT /api/restaurante/{id}
Actualiza la información de un restaurante existente.

Eliminar un restaurante
http
Copy code
DELETE /api/restaurante/{id}
Elimina un restaurante por su identificador único (id).
