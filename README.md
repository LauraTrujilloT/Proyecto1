## Proyecto 1
### Clase 1:  Github  
#### Comandos básicos
1. **git init** Usado para inicializar un repositiorio vacio.
2. **git status** Es útil para conocer el estado del archivo, y tener certeza de si hay cambios efectuados en el documento que no han sido actualizados a la versión en línea del mismo.
3. **git add** Se utiliza para agregar cambios
4. **git commit -m** Su función es agregar comentarios sobre los cambios a realizar.

### Clase 2: Herramientas básicas de python
#### Comandos básicos y Shorcuts
1. **a** Es usado para agregar una celda antes del cursor.
2. **d** Se utiliza para borrar la celda seleccionada por el cursor.
3. ```print()``` Es usado para imprimir, numeros, palabras y variables
    Ejemplo:
      Se define una variable
        k=5
        print(5)
        5
    Nota 1: En caso de declarar una variable que corresponda a una cadena de caracteres usar comillas.
    Nota 2: Para imprimir una palabra tambien hacer uso de comillas dentro del paréntesis.

4. ```type(" ")``` Esta función indica el tipo de objeto que corresponde a determinada variable
    Ejemplo:
      Haciando uso de la misma variable k se tiene lo siguiente
      type(k)
      int
      Es decir que k es una variable entera.

#### Tipos de objetos
1. **int** : integer; **99**
2. **float** : float; **9.9**
3. **str** :  string; **Hallo**

##### NOTA:
Evitar errores semánticos, errores de lógica. Ejemplo: definir una variable de tipo string e intentar convertirla en una de tipo entero.
a="bcd"
f=int(a)
