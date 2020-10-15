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
•-Significa que las variables serán usadas directamente en todos los métodos que necesitan usar sus valores.
ej: class Colores{
   private int color = 0;
   public int Color;
   {
      getColor{
         return this.color;
      }
      setColor{
         this.color = value;
      }
   }
}

2. ¿Qué significa el acceso indirecto a las variables? De un ejemplo.
•-Significa que se puede acceder a las variables sin hacer referencia a ellas y vamos a tener que usar metodos para acceder a las mismas.
ej:
   class Numero{
      private int numeroSecreto = 4;
      
      public Numero(){
        this.numeroSecreto = numeroSecreto;
      }
      
      public void Numero(){
         this.numeroSecreto = numeroSecreto;
      }
      
      public void setNumeroSecreto(int numeroSecreto){
         this.numeroSecreto = numeroSecreto;
      }
      public int getNumeroSecreto(){
         return = numeroSecreto;
      }
   }
   
   Se puede acceder a las variables indirectamente gracias a los getters y setters.

3. Qué ventajas y desventajas presenta cada estrategia referida a los getters y setters.
•-Las ventajas que presenta la estrategia de getter y setters es que aporta una gran flexibilidad al código ya que con ellos se pueden utilizar las variables privadas fuera del código sin darle acceso directo al usuario, 
y las desventajas son que para cambiar ese método se debe sobre escribir o cambiar el super y varios setters y getters,
 además que varios getters y setters pueden que nunca se los usen. 

Actividad de lectura #2

¿en qué situación es conveniente utilizar el "Creation Parameter Method"?
•-Es conveniente utilizar la creación de metodos cuando necesitamos utilizar la información de los parámetros, o introducir datos para que que se ejecute el método y también para modificar datos tras su ejecución.

Actividad de lectura #3

¿cómo se debe proporcionar acceso a variables que referencian a una colección?
•-La solución más simple es colocando un metodo getter a la variable de la colección, pero siempre hay que tener en cuanta que el
usuario podría cambiar lo que sea en todo momento, por eso hay que poner los getters a coleciones sean privados y para acceder a ellos se debe crear un metodo getter mencionando el tipo de la colección, que será dependiendo del tipo del objeto o colección de objetos que posea dentro, y este metodo regresará la información de manera indirecta.

Actividad de lectura #4

¿por qué son necesarios dos métodos para asignar el estado a una propiedad booleana?
•-Se necesitan dos métodos para asignar el estado de una propiedad booleana ya que un método se encesita para crear la acción y otro 
para negarla.

