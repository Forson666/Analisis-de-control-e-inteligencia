# Análisis de Control e Inteligencia sobre twitter

## Contexto  

Se requiere **controlar** cuáles usuarios pueden ver los tuits de otros, controlar quienes pueden **retwittear** tuits , quién los puede **observar**, cuántas veces se han visto y la fecha en que se han observado. Además, se necesita saber la frecuencia del último mes o algunas estadísticas. 

## Problemática

1. Control Quién ve mis tuit, quién puede retwittear?
2. Dashboard Twitter y quien los abre, quién retwitea? Frecuencia último mes.
 
## Levantamiento de requerimientos Funcionales
- Modificar acceso a un Tuit
  - Descripcion:
  El administrador de la publicación podrá decidir según un criterio determinado quién puede ver el tuit (Si es seguidor, si es seguido por el usuario, cuentas específicas, etc.)
  - Actores:
  Administrador de publicación
  - Accion del actor:
  Solicitar al sistema, que cambie la configuracion de los permisos de acceso a un determinado tuit o a los tuits en general que haga en su cuenta
  - Respuesta del sistema:
  El sistema solicitara los datos de la configuración deseada, dando opciones como son seguidores o seguidos, las dos opciones anteriores se podrán seleccionar de manera simultánea, así como se dará la opción de permitir acceso a cualquiera o a usuarios específicos; en caso de que se escoja la opción de usuarios específicos se procederá a pedir los identificadores de las cuentas que se desea tengan acceso, una vez se proporcionen los datos requeridos el sistema mostrara un mensaje de éxito y regulara el acceso al tuit según los parámetros indicados.
- Observar Tuit Ajeno
  - Descripcion:
  El usuario que desee observar un tuit debera cumplir con las especificaciones del administrador de la publicacion
  - Actores:
  Usuario
  - Accion del actor:
  Solicitar al sistema acceso a una determinada publicación
  - Respuesta del sistema:
  El sistema verificara si el usuario cumple con las caracteristicas requeridas para acceder al tuit y procedera a bloquear o permitir el acceso
- Retwittear publicación ajena
  - Descripcion:
  El usuario que desee retuitear debera cumplir con las especificaciones del administrador de la publicacion
  - Actores:
  Usuario
  - Accion del actor:
  Solicitar al sistema permisos para retuitear la publicación
  - Respuesta del sistema:
  El sistema verificara si el usuario cumple con las caracteristicas requeridas para acceder al tuit y permitira o no que el usuario realice el retuit
- Contar tuits : Observados y retuits
  - Descripcion:
  
  - Actores:
  
  - Accion del actor:
  
  - Respuesta del sistema:
## Levantamiento de requerimientos NO  Funcionales
- Visualización Dashboard de frecuencia de tuits
- Visualizacion de Tuits más retuiteados.
- Visualización de las personas que realizaron el retuit.



## Jheisson Enrique Fortich Suarez 20172020049 
## Santiago Gómez Almeyda 20161020503
## Kevin Malaver Cobos 20171020001
