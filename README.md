# Proyecto
Repositorio para el proyecto conjunto entre primero y segundo.

## ¿De qué va este proyecto?

Este proyecto hará de intermediario entre dos proyectos. Consiste en que los alumnos de primer curso tienen que hacer un repositorio donde pondrán un documento .json con el schema proporcionado por su mentor de segundo curso.

Después cada uno usará el json para su respectivo proyecto.

## ¿Cómo hemos hecho el proyecto?

Empezamos este proyecto haciendo el sitio web, el html principal con sus respectivos links dentro de este. Una vez acabado el sitio web, decidimos empezar con el programa, que sin duda ha sido lo más complicado, estuvimos programando juntos varias veces y otras lo haciamos desde casa cada uno,
y entre los dos conseguimos sacar el código para que funcionara correctamente, con esto fuimos haciendo los casos test, que se nos puso dificil porque no sabíamos muy bien como hacerlo, pero conseguimos sacar algunos y finalmente hemos podido entregar el documento JSON al alumno de segundo.

## ¿Cómo funciona el programa?

El programa está dividido en tres partes, la primera parte es la que convertimos el index.html a string, después buscamos todos los links que tiene esa página y una vez más, convirtiendo esos links encontrados a strings y los guardamos en un array.
A continuación tenemos una función que recorre ese array en busca de la información que necesitamos, busca el nombre del país de los menús, los platos que tiene cada menú, el stock, el precio y finalmente la valoración. Esto lo hace con todos los menús que tiene cada una de las páginas
y toda esta información la guarda en un diccionario bien estructurado que finalmente, mediante una conexión a la base de datos, es insertado en una colección de una base de datos. 

## ¿Qué librerías?

Nosotros hemos usado dos librerías, Requests_html para conectarse al sitio web y después convertir los html a strings para poder examinarlos y sacar la información
Y también hemos usado, Pymongo, para conectarse a la base de datos y guardar la información extraida en ella.

## Metodología de desarrollo

...

## ¿Cuánto tiempo hemos estado, posibles mejoras y principales dificultades encontradas?

Pues primero de todo, tenemos que decir que no tenemos todas las horas contabilizadas, porque nos enteramos tarde que teníamos que usar clockify, entonces al enterarnos lo empezamos a usar.

Hemos hecho un total de X horas de proyecto, donde la mayoría de las horas ha sido haciendo el programa.
La parte de la creación del sitio web, no estuvimos mucho tiempo, porque nuestro objetivo era sacar el código antes de tener un sitio web bonito o tal, le dimos mucha preferencia al código.
Estuvimos varias horas para entender como funcionaba GitFlow y todo el tema de las ramas.
El programa, como es lógico, es lo que más tiempo nos ha llevado ya que tampoco somos unos cracks programando, pero gracias a informarse, ver la documentación del panel y demás lo hemos conseguido sacar.

Posiblemente se podría mejorar alguna función y los nombres de las variables.

A lo largo del proyecto hemos tenido varias dificultades, como no saber si se podían importar librerías e intentar hacer las cosas sin librerías, no saber usar correctamente el gitflow y tener errores con el entorno virtual porque uno tiene linux y otro microsoft.

## Experiencia sobre el proyecto - Carlos

A mi este proyecto me ha gustado mucho porque he podido aprender muchísimas cosas, por ejemplo, ni sabía que existía el Scrapping y de no saber que era, he hecho un programa scrappeando una sitio web. 
He aprendido mucho sobre programación en este proyecto, me he buscado la vida en casi todas las ocasiones buscando información o el funcionamiento de alguna cosa. Me ha gustado hacerlo en pareja porque algunas cosas
que yo no sabía la otra persona a lo mejor me podía ayudar y también tengo que dar las gracias a los demás, que siempre que se les ha pedido alguna duda, han intentado ayudar.
Este proyecto puede que esté mejor o peor, pero yo me siento bastante satisfecho de haber conseguido el objetivo, de haber aprendido y saber que me falta por aprender mucho más.

