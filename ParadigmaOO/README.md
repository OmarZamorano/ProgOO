# Paradigma OO

# 1. Definición de Paradigma en el contexto de lenguajes de programación

Un paradigma en el área de la programaión es una forma de programas, siguiendo un modelo o ejemplo de estructura de código.
   
   
# 2. Definición de Programación Orientada a Objetos, ¿Cuál fue el primer lenguaje orientado a objetos, quienes y en dónde lo propusieron?

Es un paradigma o estilo de la programación que se basa en programar por medio de clases y objetos, es decir, se van construyendo clases las cuales cuentan con atributos y métodos que al ejecutar un objeto adquieren todo lo que se encuentra dentro de esta. Es así que la programación orientada a objetos es más efectiva ya que se crea un software solo con la manipulación e interacción de objetos entre si. 

El primer lenguaje de programación que se utilizó para seguir este paradigma fue SmallTalk. Los orígenes de este lenguaje se encuentran en las investigaciones realizadas por Alan Kay, Dan Ingalls, Ted Kaehler, Adele Goldberg y otros durante los años setenta en el Palo Alto Research Center de Xerox (conocido como Xerox PARC), para la creación de un sistema informático orientado a la educación. Xerox PARC es una compañia creada con el fin de la investigación tecnológica.  

En Smalltalk se interactúa entre objetos mediante el envío de mensajes Es multiplataforma y puede compilar en tiempo de ejecución o interpretado. Smalltalk tuvo gran influencia en la creación de otros lenguajes como Java o Ruby.

Todo en smalltalk es un objeto que puede hacer 3 cosas:
+ Mantener un estado.
+ Recibir mensajes de si mismo o de otros objetos.
+ En el curso de procesar un mensaje, enviarse un mensaje el mismo o a los demás objetos.

Características de los objetos en smalltalk:
+ Tienen una memoria propia.
+ Poseen capacidad para comunicarse con otros objetos.
+ Poseen la capacidad de heredar características de objetos ancestros.
+ Tienen capacidad de procesamiento.


# 3. Define con tus palabras el concepto de abstracción, ¿Por qué se considera fundamental en programación?

La abstracción son aquellas características de un objeto que lo diferencian de los demás.
Para la porgramación, este concepto es fundamental ya que antes de porgramar se necesita analizar el dominio del programa, es decir, lo que va a hacer, como  va a funcionar y como se va a programar, lo que da resultado a un código muy largo, es por eso que se ve de una manera general, separada por clases y objetos, con el fin de que cada objeto interactue con otros por medio de métodos y características específicas.
   
   
# 4. Explica el concepto de encapsulamiento, busca dos imágenes que te ayuden a describir el concepto, una que tenga algún sistema sin encapsulamiento y otra donde sí lo tenga. Menciona porque es importante y qué problemas puede evitar.

El encapsulamiento es la propiedad que permite ocultar la información de atributos y métodos al resto del código. Existen 3 niveles de acceso:
+ Publico: Todos pueden acceder a los datos o métodos de una clase que se definen con este nivel.
+ privado: En este nivel los miembros son accesibles sólo para la propia clase.
+ Protegido: Este no es de acceso público pero solamente son accesibles dentro de su clase y por subclases.

El encapsulamiento es muy importante a la hora de programar ya que con forme se avanza en el código se declaran atributos y métodos que se utilizan en distintas partes del código, que al momento de utilizarlas en otras partes probablemente se modifiquen sus valores, lo cual nos perjudica ya que será difícil volver a sus valores anteriores cuando no se sabe cuando, ni como se modificaron.

![image](https://user-images.githubusercontent.com/126824615/224860281-d417a138-e978-40c3-969c-3a868b35f43e.png) 

(En esta imagen se observa que las variables o atributos no estan encapsuladas ya que se declaran directamente con su tipo de dato).

![image](https://user-images.githubusercontent.com/126824615/224860427-38182626-905d-42d4-a0eb-4584c2720d97.png) 

(En esta imagen los métodos y atributos estan declarados públicos y el acceso público es un nivel de acceso del encapsulamiento).


# 5. Describe con tus palabras el concepto de herencia e ilustra el concepto con imágenes.
La herencia en la programación es basicamente el compratir o pasar atributos de una clase a otra, siempre y cuando se esté partiendo de lo general a lo específico.

![image](https://user-images.githubusercontent.com/126824615/224861813-cd9af43c-9412-479c-b603-f7031132c582.png) 

(En la imagen se observa observa una clase PADRE o clase General llamada VEHICULO la cual contiene ciertos atributos y por debajo de esta clase se encuentran otras dos con un atributo distinto de que las diferencia. A simple viste no se ve pero por medio de esas flechas se indica que las clases MOTO y COCHE están heredando los atribujtos de la clase VEHICULO, es decir, que también cuentan con los atributos de esta).



# UML: Diagrama de clases

# 1. Investiga la historia y haz un resumen del Lenguaje de Modelado Unificado, donde se mencione: quienes son sus principales autores (Booch, Rumbaugh, Jacobson), en que tipo de sistemas se utiliza, que tan utilizado es en años recientes, en particular el Diagrama de Clases. Menciona algunas de las herramientas para el modelado en UML. ¿Sabes de alguna empresa local que utilice este lenguaje?

UML que sus siglas significan Lenguaje Unificado de Modelado, es un modelo que se utiliza para representar, visualizar, construir y documentar el funcionamiento de un programa por medio de clases y sus interacciones entre si. Dicho modelo fue creado por Booch, Rumbaugh y Jacobson. UML se enfoca en tres modelos de sistemas:

+ El modelo funcional, representado en UML, con diagramas de caso de uso, describe la funcionalidad del sistema desde el punto de vista del usuario.

+ El modelo de objetos, representado en UML con diagramas de clase, describe la estructura de un sistema desde el punto de vista de objetos, atributos, asociaciones y operaciones.

+El modelo dinámico, representado en UML con diagramas de secuencia, diagramas de estado y diagramas de actividad, describen el comportamiento interno del sistema. Los diagramas de secuencia describen el comportamiento como una secuencia de mensajes intercambiados entre un conjunto de objetos, mientras que los diagramas de gráfica de estado describen el comportamiento desde el punto de vista de estados de un objeto individual y las transiciones posibles entre estados.

Actualmente el UML es muy utilizado por empresas grandes que se dedican o utilizan algun software por la gran facilidad de entender el objetivo de los programas por medio de un recurso visual, más que nada para darlo a entender a las personas que no estan familiarizadas con el tema de la programación. Por ejemplo APPLE, AMAZON, SPACE X, TESLA MOTORS, NVIDIA, etc.

Ya que el UML es un modelo a seguir, consta de herramientas con significados especiales como lo son sus conexiones o conectores. Dentro de estas herramientas, los conectores más comúnes son:

+ Las Asociaciones representan relaciones generales entre clases, y puede haber cardinalidad entre estas, es decir, tal clase puede tener un número de clases pero otra clase solo puede tener tal número de clases. Esta propiedad de represanta por rango, por ejemplo: #..# o #..* (el numero mínimo, luego se separa con dos puntos y luego el número máximo. En caso de que sea un límite infinito se pone *).

![image](https://user-images.githubusercontent.com/126824615/224872095-17c99660-4733-4fef-9426-8218927606be.png)

-La Composición indica que una clase solo puede estar compuesta por la clase indicada, y si se destruye la clase PADRE, se destruye también su composición.

![image](https://user-images.githubusercontent.com/126824615/224872566-508c3912-cee1-44df-9f85-8dfa7c76af5c.png)

-La Agregación es muy parecida a la composición, sin embargo no es tan fuerte o tan pura ya que si la clase PADRE no tiene una agregación no pierde mucho sentido.

![image](https://user-images.githubusercontent.com/126824615/224872917-0c969c73-1846-45cd-b821-de4abf1abad7.png)

-La Generalización es como se representa la herencia, la cual va de los mas general a lo específico. Puede haber una generalización o generalización múltiple.

![image](https://user-images.githubusercontent.com/126824615/224873313-bcc08489-9bcc-474b-bdb1-1068f8023aff.png)


# 2. Escribe una propuesta de una máquina que venda distintos artículos y haz el diagrama de clases del sistema que propones. Recuerda que puede haber composición (un teclado se compone de botones) y generalización (tipo de productos, tipo de pago).

## Maquina Expendedora

![Maquina Expendedora](https://user-images.githubusercontent.com/126824615/225427705-50373661-4d39-4ee2-8179-0eb03e5f88f2.png)
