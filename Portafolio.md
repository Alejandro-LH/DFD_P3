# Presentacion 
## Problemas resueltos en clase con DFD
### Ejercicio 1. Utilizando dos vectores capture edad y semestres de n estudiantes.
#### 1.1 Análisis.  
Almacenamos en un proceso los dos vectores donde se guardaran los datos de los estudiantes, después preguntaremos los estudiantes y validaremos que este dentro del rango, luego en un ciclo for, la edad y semestre, y validaremos que esten dentro de los limites establecidos, luego se almacenara en los vectores el semestre y la edad de cada alumno.
#### 1.2 DFD
![1](https://user-images.githubusercontent.com/113395327/204663736-e6f883c0-f59e-4ba9-a59c-df0a8cdbb106.png)
#### 1.3 Prueba de escritorio
corrida|valor i|V E|V S|i=n?|
|-|-|-|-|-|
|1|0|VE[0]=16|VS[0]=3|no|
|2|1|VE[1]=17|VS[1]=5|no|
|3|2|VE[2]=18|VS[2]=7|no|
|4|3|VE[3]=17|VS[3]=5|Si, impr VE y VS|
#### 1.4 Entradas.
ne; ed; se.
#### 1.5 Salidas.
Ae; As.
### Ejercicio 2. Utilizando una matriz, capture edad y semestre de n estudiantes
#### 1.1 Análisis.  
Utilizaremos un proceso para almacenar la matriz, después preguntaremos el núero de estudiantes, validaremos que esten dentro del rango establecido, después en un ciclo for almacenaremos la edad y el semestre donde se validara que estos esten dentro de los limites establecidos, para al final ser almacenados en la matriz que les corresponda.
#### 1.2 DFD
![2](https://user-images.githubusercontent.com/113395327/204663763-fdd3992f-a043-4aa1-a85e-acd679b33d6b.png)
#### 1.3 Prueba de escritorio
|corrida|valor i|valor j|matriz|i=n?|
|-|-|-|-|-|
|1|0|0|M[0,0]=16|no|
|2|1|0|M[1,0]=17|no|
|3|2|0|M[2,0]=17|no|
|4|3|0|M[3,0]=16|Si, entonces sig contador|
|1|0|0|M[0,1]=3|no|
|2|1|0|M[1,1]=5|no|
|3|2|0|M[2,1]=5|no|
|4|3|0|M[3,1]=3|Si, entonces impr [M]|
#### 1.4 Entradas.
ne; ed; se.
#### 1.5 Salidas.
M.
### Ejercicio 3. Rellenar una matriz cuadrada de nxn con un núero leido del teclado.
#### 1.1 Análisis.  
Determinaremos el tamaño de la matriz, después verificaremos que este dentro de los límites, luego pediremos un núero leído del teclado, validaremos que estén dentro de los limites establecidos, ahora en un ciclo for estableceremos otro ciclo for para guardar el número leído del teclado en la matriz.
#### 1.2 DFD
![3](https://user-images.githubusercontent.com/113395327/204666246-5ee27669-1c3e-46f4-824d-ae79fbdd68df.png)
#### 1.3 Prueba de escritorio
|i|j|Matriz|num|i = M ?|
|-|-|-|-|-|
|0|0|M [0,0]|5|no|
|0|1|M [0,0]|7|no |
|0|2|M[0,2]| 8| si, entonces J+1 y vuelve a empezar|

#### 1.4 Entradas.
n; num.
#### 1.5 Salidas.
No hay salidas.
### Ejercicio 4. Rellenar una matriz con números consecutivos hasta nxn.
#### 1.1 Análisis.  
En un proceso estará los limites de la matriz y el contador que se igualará a 0, despues pediremos el tamaño de la matriz, para despues validar que esté dentro de los limites establecidos, luego en un ciclo for estableceremos otro ciclo for en el cual el el numero se ira sontando y sumando al mismo tiempo que se rtellena la matriz para así terminar el ciclo.
#### 1.2 DFD
![4](https://user-images.githubusercontent.com/113395327/204667281-8a31699f-50ab-4142-a69b-733c0f398d35.png)
#### 1.3 Prueba de escritorio
|i|j|Matriz|C|i=M?|
|-|-|-|-|-|
|0|0|M[0,0]|0|no|
|0|1|M[0,1]|0|no|
|0|2|M[0,2]|0|si, entonces vuelve a empezar|
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
no tiene salidas.
### Ejercicio 5. Rellenar una matriz con los numeros 1,2,3...n.
#### 1.1 Análisis.  
En un proceso determinamos los limites de la matriz, ahora preguntamos el tamaño de la matriz y verificamos que esta se encuentre dentro de los límites, después en un ciclo for estableceremos otro ciclo for en el cual sumaremos +1 en cada columna de la fila, hasta rellenar la matriz.
#### 1.2 DFD
![5](https://user-images.githubusercontent.com/113395327/204667646-a9d9b9bf-4f61-4eca-aa3a-23e8b5bc8b35.png)
#### 1.3 Prueba de escritorio
|i|j|Matriz|C|i=M?|
|-|-|-|-|-|
|0|0|M[0,0]|1|no|
|0|1|M[0,1]|1|no|
|0|2|M[0,2]|1|si, entonces C+1 y vuelve a empezar|
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
No tiene salidas.
### Ejercicio 6. Generar una matriz cuadrada
#### 1.1 Análisis.  

#### 1.2 DFD
![6](https://user-images.githubusercontent.com/113395327/205507418-e0d579bf-97bc-4aa0-8600-7c08dc95a926.jpg)
#### 1.3 Prueba de escritorio

#### 1.4 Entradas.

#### 1.5 Salidas.

### Ejercicio 7. 
#### 1.1 Análisis.  

#### 1.2 DFD
![7](https://user-images.githubusercontent.com/113395327/205507459-84927824-8e63-4b36-90fc-23e735b36242.jpg)
#### 1.3 Prueba de escritorio

#### 1.4 Entradas.

#### 1.5 Salidas.

### Ejercicio 8. 
#### 1.1 Análisis.  

#### 1.2 DFD
![8](https://user-images.githubusercontent.com/113395327/205507474-c6e63589-0df7-4203-995a-925b5008524d.jpg)
#### 1.3 Prueba de escritorio

#### 1.4 Entradas.

#### 1.5 Salidas.

### Ejercicio 9. 
#### 1.1 Análisis.  

#### 1.2 DFD
![9](https://user-images.githubusercontent.com/113395327/205507482-1b151083-e6f1-4ef6-b202-40633f42bee5.jpg)
#### 1.3 Prueba de escritorio

#### 1.4 Entradas.

#### 1.5 Salidas.

### Ejercicio 10. 
#### 1.1 Análisis.  

#### 1.2 DFD
![10](https://user-images.githubusercontent.com/113395327/205507511-111fd6d1-676c-447b-b1f0-526a486f2683.jpg)

#### 1.3 Prueba de escritorio

#### 1.4 Entradas.

#### 1.5 Salidas.

