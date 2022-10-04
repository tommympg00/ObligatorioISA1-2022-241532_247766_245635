# Sprint 1

### Identifiacion del Problema a Resolver
Ayudar al usuario con el transporte público en el día a día.

### Definicion de Interesados
Al tratarse de una aplicacion de transporte publico, está dirigida principalmente a personas de cualquier edad que utilicen este medio como transporte, como usuarios finales.

Aun asi, existen otros interesados como las entidades municipales que ofrecen los datos publicos de sus transportes y a traves de esta aplicacion un mayor porcentaje de gente podria acceder a esa informacion y asi aumentar su ganancia.

Tambien, otro posible interesado (dependiendo del modelo de negocio de la aplicacion) seria el Anunciante. El interes de esta entidad se da ya que necesita disponer de un espacio para anunciar sus productos y promocionarse. Por medio de anuncios, esta aplicacion podria proveer ese espacio.

En las user stories podremos identificar distintas variables demográficas, psicográficas y conductuales que diferenciará el fin el cual el usuario hará uso de la aplicación.

### Comparacion con otras herramientas

A través del uso cotidiano de las aplicaciones competidoras podemos extraer algunas críticas que pueden mejorar la experiencia de usuario.

##### Moovit:
Una aplicacion de transporte publico gratuita, disponible para IOS, Android y Windows Phone. Moovit permite al usuario obtener toda la informacion que necesita sobre el transporte publico en mas de 112 paises. 

Esta aplicacion incluye las siguientes funcionalidades:
* Planificar un viaje: La aplicacion calcula el mejor trayecto en tiempo real para que el usuario tome ese camino para dirigirse desde un determinado origen a un determinado destino.
* Buscar Horarios: Moovit permite buscar los horarios de una linea especifica. El usuario busca una linea y una parada por la que esa linea pase y puede ver cuanto demora en llegar el siguiente transporte. Tambien, puede ver todos los horarios en los que pasa ese movil.
 

##### STM:

En resumen:

Hemos notado que a veces los horarios marcados por la aplicación no son los correctos, esto puede marcar una gran diferencia a la hora de elegir una aplicación sobre la otra, ya que, con esa fidelidad podemos asegurar a los usuarios un menor tiempo de espera en la parada, y a su vez, lograr una mejor aproximación en la hora de llegada.

También, investigando encontramos que muchos usuarios se quejan de que la aplicación funciona lento si el teléfono móvil no tiene una buena conexión a internet lo cual interfiere en la experiencia de usuario. 
src: https://www.capterra.es/reviews/186029/moovit-maas-solution

Por otro lado, se nos ocurrió la idea de una _boletera digital_ la cual nos permite  realizar el pago del boleto por medio de la aplicación con solo acercar el teléfono móvil al aparato NFC del ómnibus, la misma se podrá recargar por medio de una tarjeta de crédito/débito. Esto, entre otros beneficios, ahorraría el cargar con la boletera.

## Lista de funcionalidades por interesado

Por medio del estudio de la competencia y nuestro mercado objetivo podemos interpretar esta información e implementar algunas funcionalidades las cuales consideramos claves. Estas nos pueden distinguir de la competencia y a su vez son útiles al momento de hacer uso de la aplicación.

1. De manera tal de obtener la fidelidad del usuario y obtener una mayor retención de los mismos a lo largo del tiempo interponemos como funcionalidad más importante mejorar, de manera efectiva, la aproximación de los horarios al momento de moverse en ómnibus; con el fin de que la aplicación le diga al usuario a que hora salir de su ubicación, caminar a la parada, subirse al ómnibus y llegar a destino con un error de uno/dos minutos.

2. Aunque es verdad que con el paso del tiempo cada vez es más fácil conseguir acceso a internet y planes con mayor número de gigas por mes a menor costo; con un sentido de ahorro decidimos implementar la opción de que la aplicación pueda ser utilizada sin tener acceso al mismo. Esto si, a un costo, el error de aproximación aumenta ya que se necesitan datos en tiempo real para que se lleve a cabo una mejor.
