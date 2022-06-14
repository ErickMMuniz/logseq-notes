title:: Programming/Git

- **Git** es un controlador de versiones.
- Se basa, como LogSeq, en **pequeños cambios**. Los grandes archivos (como scripts) solo son índices.
-
-
- ---
- Algunos comando útiles.
	- `git stash push -m "SOME AWESOME ID"`
	  
	  Este comando sirve para _almacenar_ tus cambios de forma temporal. **Nota:** Aquí se guarda todo lo que esté en stagged.
	- `git stash -p`
	  
	  Sirve para guardar los cambios que uno desee. Es similar a la bandera `-i` de `git rebase` porque se vuelve interactivo. Este comando resuelve el problema de `git stash push`.