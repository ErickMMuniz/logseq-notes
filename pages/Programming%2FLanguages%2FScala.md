title:: Programming/Languages/Scala

- Todo lo referente a Scala y más.
	- ## Conceptos importantes. 
	  1. Scala es meramente programación funcional #FP . 
	  2. Scala usa `lazy val`.
-
- ## Notas que pueden servir.
- ^^Thunk^^.  Un _thunk_ es una **función** que no recibe parámetros pero regresa algo de tipo A. En código, se puede usar el identificador `type`así.
  ```scala
  type Thunk[A] = () => A
  ```
- ^^Type^^. Es un alias para varios objetos. Es funcional para leer de manera más sencilla diversas combinaciones de objetos. Cabe recalcar que no es un objeto; entonces, no podemos inicializarlo.
  
  ```scala
  //Definamos una simple combinación de cosas
  type SomeBeautyMap = Map[String, (Int, String)]
  
  //Esto no es cool. 
  def someFunctionThatReturnUglyObject(): Map[String, (Int, String)]
  
  // Esto sí es cool.
  def someFunctionThatReturnBeautyObject(): SomeBeautyMap 
  ```
-
-