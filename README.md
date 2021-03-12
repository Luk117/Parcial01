# Parcial01


#Conceptos

1.**Encapsulamiento**

El encapsulamiento como tal se basa en que hay algo que rodea el codigo para proteger contenidos y mantenerlo agrupado. En la POO se refiere a tomar los atributos y conductas y agruparlos en una misma unidad. Se almacena en una clase la funcionalidad y caracteristicas de los objetos representandolas por medio de los atributos y metodos, esto garantiza la integridad de los datos que contiene un objeto y evita el acceso a datos por medio de cualquier otro medio diferente al que nosotros asignemos en la clase. 

El encapsulamiento hace posible lidiar con la complejidad de los objetos ya que podemos manipular la informacion de cada objeto de forma independiente donde solo se conocen las caracteristicas y funcionalidades de cada uno pero sin revelar detalles internos. 


**Ocultamiento**

El Encapsulamiento hace uso del ocultamiento el cual tiene como proposito no revelar nada sobre si mismo excepto lo necesario para que las otras partes de la aplicacion funcionen. ES impotante usar estp ya que hay atributos los cuales pueden ser delicados a causa de la informacion que contienen, por ejemplo, si el programa creado es de un banco y la clase "persona" contiene los datos personales de un usuario hay atributos que pueden comprometer la seguridad, se le expone a que a causa de la falta de ocultamiento se efectuen posibles ataques de seguridad. 

Aqui entran en juego los **Modificadores de Acceso**


public: Si un elemento de una clase es public tendremos acceso a este desde cualquier clase o instancia del proyecto sin importar el paquete

Private: Solo se puede acceder desde la misma clase, ninguna otra clase puede acceder

Protected: Este permite el acceso a elementos de la misma clase, clases que esten en el mismo paquete y se puede acceder desde las clases que hereden de ella



EJ: cualquiera sea capaz de acceder a el color de un automovil - Se utiliza publico

EJ:  el color se puede acceder no solo desde el color del automovil si no desde una moto (que es un vehiculo) - se usa protegido

Ej: El color solo se puede acceder solomente para vehiculo - Se utiliza privado


Si no se puede acceder a elementos privados desde otra clase este se consigue con los get() y set()


**Mapa de memoria**

-**Mapa de memoria**

![WhatsApp Image 2021-03-05 at 7 25 31 PM](https://user-images.githubusercontent.com/78616272/110188243-13532480-7de9-11eb-86df-614a3972df8e.jpeg)


**Mapa Conceptual**

![Screenshot 2021-03-12 184027](https://user-images.githubusercontent.com/78616272/111009727-6d606680-8362-11eb-8e84-9ffe29fe9633.png)

