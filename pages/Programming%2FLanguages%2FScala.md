title:: Programming/Languages/Scala

- Todo lo referente a Scala y más.
	- ## Conceptos importantes. 
	  1. Scala es meramente programación funcional #FP . 
	  2. Scala usa `lazy val`.
-
- ## Notas que pueden servir.
- ˆˆˆThunkˆˆˆ.  Un _thunk_ es una **función** que no recibe parámetros pero regresa algo de tipo A. En código, se puede usar el identificador `type`así.
  ```scala
  type Thunk[A] = () => A
  ```
-