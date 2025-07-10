## Introducción a los Microservicios
Cuando hablamos de microservicios nos estamos refiriendo a una forma de construir nuestro sistema de software de forma que sea mas escalable y ordenada, pero ¿De que forma logramos esto y por que esta arquitectura tiene estas caracteristicas?  
Para ello es importante entender la arquitectura monolitica, sus puntos debiles y por que la arquitectura de microservicios nace como una propuesta a solucionar dichas debilidades.

## Arquitectura Monolitica
Hace referencia a una forma de desarrollar software en donde este está construido como una sola unidad, todos los componentes y funcionalidades se encuentran unificados y dependen estrechamente uno del otro. Todas las partes de una aplicacion monolitica usan el mismo lenguaje, framework y version, lo cual puede ser una ventaja en ciertas situaciones pero mayormente una limitacion.   
Entre las desventajas mas notables se encuentran la baja resistencia a los fallos (un fallo en un componente afecta a la aplicacion en su totalidad) y la interdependencia (el cambio en un componente puede requerir cambios en clases adyacentes colateralamente).  
Estas desventajas, entre otras, dieron raiz al nacimiento de la arquitectura de Microservicios.

## Arquitectura de Microservicios

