title:: Programming/Languages/Scala/ZIO

- # ZIO
- Es una librería para programación **asíncrona** y **concurrente**
	- Solo existe un tipo que se llama #ZIO
	- Los tipos de types  son efectos inmutables y #lazy que modelan, posiblemente compleja (es decir, un efecto dependiente de otro) de async, concurrent, resourceful, and contextual computations.
		- En ZIO solo tenemo un tipo de dato 
		  collapsed:: true
		  ```scala
		  trait ZIO[R,E,A]
		  ```
			- Una buena forma de ver a ZIO type es verlo como una función
			  ```scala
			  R => Either[E,A]
			  ```
			- Por lo tanto, podemos leer este types como
			- ```scala
			  R <- Im a context
			  E <- Im a possible Error
			  A <- Im a deseable data type
			  ```
		- ```scala
		  sealed trait ZIO[-R, +E, +A] extends Serializable with ZIOPlatformSpecific[R, E, A] with ZIOVersionSpecific[R, E, A]
		  ```
		- ```scala
		  R -> Either[E,A]
		  ```
	-
-
-