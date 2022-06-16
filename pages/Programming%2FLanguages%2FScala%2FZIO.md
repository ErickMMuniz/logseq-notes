title:: Programming/Languages/Scala/ZIO

- # ZIO
- Es una librería para programación **asíncrona** y **concurrente**
	- #ZIO effects are immutable data values that model a possibly complex series
	   of async, concurrent, resourceful, and contextual computations. _
		- En ZIO solo tenemo un tipo de dato 
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
		-
	-
-
-