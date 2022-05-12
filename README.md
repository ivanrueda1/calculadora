 # CALCULADORA BASICA CON MENÚ

 Una calculadora básica se puede realizar con condiciones. Se desea realizar alguna de las operaciones basicas con dos números `x, y`. Además se desea calcular la potencia y el logaritmo. Se deben considerar los casos donde  `y = 0`donde la división `x/y` NO sepuede realizar y cuando `x <= 0` donde NO se puede calcular el `log(X)`.  Se desea generar un menú para que el usuario pueda seleccionar la operación a realizar. Una manera de hacerlo es lo siguiente:

 1. Se reciben dos números `x, y` para realizar la operacion.
 2. Se recibe la operación a realizar mediante la variable `opcion` la que selecciona el menú que operación ejecuta el algoritmo.
 3. Se inicializa la variable lógica `bandera = False`. Si la división o el logaritmo no se puede calcular, se hace `bandera = true`. 
 4. Mediante condiciones se realiza la operación deseada.
    * En el caso de la división, si `y = 0`, NO se puede realizar la división, se muestra un mensaje y se hace `bandera = True`.
    * En el caso de logaritmo, si `x <= 0`, NO se puede calcular el logaritmo, se muestra un mensaje y se hace `bandera = True`.
5. Se muestra el resultado en el caso en que `bandera = False`. 

*Tomado de: Python con aplicacion a las matematicas, ingenieria y finanzas. Cervantes O, Baez D.*