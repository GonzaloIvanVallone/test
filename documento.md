## Introducción a los Microservicios
Cuando hablamos de microservicios nos estamos refiriendo a una forma de construir nuestro sistema de software de forma que sea mas escalable y ordenada, pero ¿De que forma logramos esto y por que esta arquitectura tiene estas caracteristicas?  
Para ello es importante entender la arquitectura monolitica, sus puntos debiles y por que la arquitectura de microservicios nace como una propuesta a solucionar dichas debilidades.

## Arquitectura Monolitica
Hace referencia a una forma de desarrollar software en donde este está construido como una sola unidad, todos los componentes y funcionalidades se encuentran unificados y dependen estrechamente uno del otro. Todas las partes de una aplicacion monolitica usan el mismo lenguaje, framework y version, lo cual puede ser una ventaja en ciertas situaciones pero mayormente una limitacion.   
Entre las desventajas mas notables se encuentran la baja resistencia a los fallos (un fallo en un componente afecta a la aplicacion en su totalidad) y la interdependencia (el cambio en un componente puede requerir cambios en clases adyacentes colateralamente).  
Estas desventajas, entre otras, dieron raiz al nacimiento de la arquitectura de Microservicios.

## Arquitectura de Microservicios
Es un enfoque modular en el cual se busca dividir el software a desarrollar en pequeños modulos llamados servicios. Tendremos el mismo contenido que una aplicacion monolitica con la diferencia de que cada tarea o rol especifico sera realizado por un microservicio particular, reduciendo asi la complejidad y los conflictos.  
Estos microservicios cumplen una funcion unica y son independientes, esto no quiere decir que no se necesiten entre ellos sino que pueden desarrollarse y desplegarse sin depender entre si, pueden utilizar un lenguaje o framework distinto y, en caso de fallar, no afectan a los demas modulos. De esta forma se evitan los dos problemas mas notables de la arquitectura monolitica mensionados previamente, la baja resistencia a fallos y la interdependencia y se suman algunas fortalezas, como la capacidad de usar un stack tecnologico a conveniencia.  
Este tipo de arquitectura es recomendada cuando se busca construir software complejo y grande manteniendo escalabilidad.  
Entonces, repasemos algunas caracteristicas importantes de los microservicios:
  - Cada servicio se concentra en una tarea o rol puntual
  - Cada servicio es autonomo 
  - Cada servicio usa su propia DB
  - Se comunican entre si y el fallo de alguno de ellos no afecta a los demas

