# Prueba_Tecnica_WCF


prueba tecnica arquitectura 3 capas.


# Capa presentación
- En esta capa se presentan dos paginas principales Usuario, Usuario gestiona y otra pagina de login para iuntegrar el modulo de autenticación de la capa negocio.
- Se crea el script para la descarga de los registros en formato xlsx y txt.
- En la segunda pagina se traen los datos del registro seleccionado de la anterior y se cambia el titulo segun la accion selecciona.

# Capa negocio
Se crean todos los metodos para realizar la conexion con los procedimientos almacenados en base de datos(bd) y se adiciona un metodo con su respectiva conexion a bd que inserta logs de todas las operaciones que se hagan.

# Capa de datos
Se crea la base de datos en Sql Server con dos tablas dbo.Usuarios con los procedimientos almacenados para un CRUD basico
