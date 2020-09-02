# unqui-po2-Medici Leonardo Roberto TP1 Repaso.

1-Evaluación de protocolos de una clase.
•Yo creo que la opción 2 es la correcta ya que con la opción 1 se pueden dibujar varias figuras que no son un rectangulo.

2-Delegación.
•Creo que la opción correcta es la 2 ya que el secretario es el encargado de ir a buscar el fichero.

3-Polimorfismo.
•Defecto opción 1: No se debería poner un metodo con nombre "clase" y no tiene return o else.
•Defecto opción 2: Los if no tienen else y no hay un return.
•Defecto opción 3: El metodo extraer no existe, la clase CajaDeAhorro y CuentaCorriente no tiene un return o un else.
•Defecto opción 4: El if no posee un return o un else.

Actividad de lectura #1

1. ¿Qué significa el acceso directo a las variables? De un ejemplo.
•-Significa que vamos a poder usar y modificar la variable en todo momento gracias a getter y setter.
ej:
   object pepita{
      var energia = 100

      method getEnergia(){
        return energia
      }
      method setEnergia(valor){
        energia = valor
      }
    }

2. ¿Qué significa el acceso indirecto a las variables? De un ejemplo.
•-Significa que se puede acceder a las variables sin hacer referencia a ellas.
ej:
   int *pl;
   float valor, *pvalor;
   double *p, *q;

3. Qué ventajas y desventajas presenta cada estrategia referida a los getters y setters.
•-Las ventajas que presenta la estrategia de getter y setters es que aporta una gran flexibilidad al código, 
y las desventajas son que para cambiar ese método se debe sobre escribir o cambiar el supery varios setters y getters,
 además que varios getters y setters pueden que nunca se los usen. 

Actividad de lectura #2

¿en qué situación es conveniente utilizar el "Creation Parameter Method"?
•-Es conveniente utilizar la creación de metodos cuando sabemos que se utlizaran y así no repetir código.

Actividad de lectura #3

¿cómo se debe proporcionar acceso a variables que referencian a una colección?
•-La solución más simple es comlocando un metodo getter a la variable de la colección, pero siemrpe hay que tener en cuanta que el
usuario podría cambiar lo que sea en todo momento, por eso hay que poner los getters a coleciones sean privados.

Actividad de lectura #4

¿por qué son necesarios dos métodos para asignar el estado a una propiedad booleana?
•-Se necesitan dos métodos para asignar el estado de una propiedad booleana ya que un método se encesita para crear la acción y otro 
para negarla.

