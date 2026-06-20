# actividad_prog_avanzada

## Ejercicio 1: Investigar y documentar críticas a los patrones de diseño. Mencione ejemplos concretos: 
## Una de las críticas mas realizadas a los patrones de diseño es su uso injustificado, este es el problema de muchos principiantes que acaban de familiarizarse con los patrones. Una vez que los aprenden, intentan aplicarlos en todas partes, incluso en situaciones en las que un código más simple funcionaría verdaderamente bien sin ellos. También, en ciertos casos, el uso excesivo de abstracciones (interfaces, clases intermedias, delegaciones) hace que el código sea más difícil de seguir. El objetivo de los patrones es mejorar la estructura, pero si se abusa, se pierde claridad.

## Ejercicio 2: https://colab.research.google.com/drive/1ApzhgVoQ2NDHVHrfTOGmYt54Kswwshwo

## Ejercicio 3: Piense en 3 problemas habituales de su vida diaria en los cuales podría aplicar patrones de diseño: 
## El patrón singleton podría utilizarse para la organización de una casa, por ejemplo, solo puede haber un control central de la calefacción. En este caso, este patrón asegura que exista una sola instancia que controle la temperatura. 
## Otra situación podría ser usar el patrón Strategy a la hora de ir al gimnasio. Según el objetivo, uno elige distintas rutinas de entrenamiento, entonces strategy permite cambiar las rutinas, sin tener que dejar de ir al gimnasio, es decir, hoy aplicas la estrategia "Cardio", mañana "pesas, etc. 
## Por último, con patrón Observer, a la hora de estudiar cuando un profesor sube un aviso a la plataforma virtual, todos los estudiantes recibimos la notificación. Po ejemplo, cambio de fecha de examen, todos nos enteramos al mismo tiempo. 

## Ejercicio 4: Los patrones de diseño suelen poseer distintos nombres o denominaciones. Busque y arme una tabla con los posibles distintos nombres usados.
## 
| Patrón                 | Nombre en Español 
|------------------------|-------------------
| Singleton              | Único / Instancia única 
| Factory Method         | Método fábrica    
| Observer               | Observador       
| Strategy               | Estrategia        
| Builder                | Constructor 
| Prototype              | Prototipo
| Adapter                | Adaptador
| ecorator               | Decorador 
|Facade                  | Fachada 
| Composite              | Compuesto 
|Bridge                  |Puente 
| Flyweight              | Peso mosca
| Iterator               | Iterador 
| Command                | Comando 
| State                  | Estado

## Ejercicio 5: ¿Qué son los antipatrones de diseño? Ejemplifique algunos casos.
## Un antipatrón es una práctica de diseño o programación que se repite en muchos proyectos, pero que conduce a una mala solución. Se documentan para que los desarrolladores puedan reconocerlos y evitarlos. Son lo contrario de los patrones de diseño: mientras los patrones ofrecen soluciones probadas y eficientes, los antipatrones representan errores recurrentes. Son soluciones que parecen correctas al principio, pero que generan poroblemas de mantenimiento, escalabilidad y calidad de software. 

## Ejercicio 6: 
## SOLID es un conjunto de cinco principios de diseño orientado a objetos que ayudan a crear software más mantenible, extensible y fácil de entender.
## S - Principio de Responsabilidad Única (SRP), O - Principio de Abierto/Cerrado (OCP), L - Principio de Sustitución de Liskov (LSP), I - Principio de Segregación de Interfaces (ISP) y D - Principio de Inversión de Dependencias (DIP). Si no se aplican, pueden haber riesgos como Clases con demasiadas responsabilidades (violación del SRP), código difícil de extender porque requiere modificar lo existente (violación del OCP), subclases que rompen el comportamiento esperado (violación del LSP), interfaces demasiado grandes que fuerzan a implementar métodos innecesarios (violación del ISP), etc. 
