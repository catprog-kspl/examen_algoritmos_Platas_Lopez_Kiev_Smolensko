# examen_algoritmos_Platas_Lopez_Kiev_Smolensko

#Respuestas a la seccion patrones de diseño

  Problema 1: Un cliente requiere utilizar sendgrid para envíos de email, pero otro cliente
  requiere enviarlos por mandril. Se quiere evitar el uso de IF, y realizar un diseño en donde
  podamos utilizar más servicios en caso de que un cliente requiera alguno en específico ¿Qué
  patrón de diseño utilizarías y por qué?
              Opción 1: Strategy
              Opción 2: Factory Method
              Opción 3: Adapter
  
Respuesta 1: El patron de diseño que utilizaría es Strategy ya que por medio de este patron de diseno se puede utilizar distintas variantes de un algoritmo en un solo objeto lo que permite en este caso enviar informacion por medio de dos plataformas diferentes, se puede programar de distintas maneras el comportamiento o la manera en la que se envia la informacion lo cual nos permite tener un sistema con mayor eficiencia permitiendo que se puedan realizar distintas subtareas de distintas maneras especificas.
              
              
Problema 2: Explica en tus propias palabras la diferencia entre Factory Method y Abstract
Factory. Y proporciona un caso de uso.
Respuesta 2
La principal diferencia que existe entre Factory Method y Abstract Factory es que el primer patron de diseño tiene una curva de aprendizaje más baja a diferencia de abstract Factory ya que son más complicados pero a diferencia de Factory Method  es más flexible de utilizar, con abstract Factory se tiene la seguridad de que no habrá algun acoplamiento entre los productos que se crean además de  son compatibles entre si.

En el caso de Abstract Factory la literatura nos informa que este patron de diseño permite producir familias de objetos sin especificar sus clases concretas por ello un ejemplo es el de una aplicación que vende muebles que pasa cuando en un paquete que compra una familia no posee muebles distribuidos de forma equitativa es decir el paquete que compra solo posee dos sillas del mismo tipo o dos sofas del mismo tipo cuando la familia deseaba una variedad en su compra es decir que los muebles no se repitan.

La solución para ello es utilizar este patron de diseño implementando una interfas para  producto haciendo que cada variante de producto siga a las interfaces para que asi sean diferenciadas pero sigan teniendo las caracteristicas del producto siendo variantes del mismo.

Nota: para poder ejecutar los codigos se pueden ejecutar desde colab. 
