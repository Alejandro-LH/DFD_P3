# Presentacion 
## Problemas resueltos en clase con DFD
### Ejercicio 1. 
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
### Ejercicio 2. 
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
### Ejercicio 3. 
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
### Ejercicio 4. 
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
### Ejercicio 5. 
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
### Ejercicio 6.
#### 1.1 Análisis.  
En un proceso delimitaremos la matriz, luego pediremos el tamaño de la matriz y validaremos que ester dentro de los límites, luego en un ciclo for estableceremos otro ciclo for, en el cual la columna será igual al renglon y se almacenara en una matriz, y si no se le sumará 1 al numero que esta en la fila.
#### 1.2 DFD
![6](https://user-images.githubusercontent.com/113395327/205507418-e0d579bf-97bc-4aa0-8600-7c08dc95a926.jpg)
#### 1.3 Prueba de escritorio
|corridas|i|j|M|j=m?|
|-|-|-|-|-|
|1|0|1|M[0,0]=0|no|
|2|0|2|M[0,0]=0|no|
|3|0|3|M[0,0]=0|no|
|4|0|4|0|0|M[0,0]=0|si, entonces i+1 y j=0|

|0|0|0|0|
|-|-|-|-|
|0|0|0|0|
|0|0|0|0|
|0|0|0|0|

Ahora hacemos la secuencia y en cada ciclo acabado le sumamos 1 a j

|Corridas|i|M|
|-|-|-|
|1|0|M[i,i=i+1]|
|2|1|M[i,i=i+1]|
|3|2|M[i,i=i+1]|
|4|3|M[i,i=i+1]|
#### 1.4 Entradas.
n
#### 1.5 Salidas.
Noi tiene salidas.
### Ejercicio 7. 
#### 1.1 Análisis.  
en un proceso se determinarán los límites de la matriz, luego pediremos el tamaño de la matriz y verificaremos que este dentro de los límites, ahora en un ciclo for estableceremos otro ciclo for, en el cual sera M[i.j]=n hasta llenar la matriz, luego al finalizar será num= num * num, luego en un ciclo for estableceremos otro ciclo for en el cual se debera rellenar A[c]= M[i,j] y se agregara +1 al contador hastaa llenar la matriz.
#### 1.2 DFD
![7](https://user-images.githubusercontent.com/113395327/205507459-84927824-8e63-4b36-90fc-23e735b36242.jpg)
#### 1.3 Prueba de escritorio
|corridas|Matriz|Vector|j+1|
|-|-|-|-|
|1|M 0,0|M 0,0=V 0|j+1|
|2|M 0,1|M 0,1=V 1|j+1|
|3|M 0,2|M 0,2=V 2|j+1|

If j=M, i+1 and j=0 y regresa el ciclo hasta que i=M

|1|2|3|
|-|-|-|
|4|5|6|
|7|8|9|
#### 1.4 Entradas.
num.
#### 1.5 Salidas.
A.
### Ejercicio 8. 
#### 1.1 Análisis.  
En un proceso almacenaremos las variables (CR=0, MM=0, R1=0, AR=0, CA[50,70], NM[7], PM[7], PA[50]), después preguntaremos el número de alumnos y validaremos que esten dentro de los límites, despues en un ciclo for, pediremos el nombre de la materia y validaremos que este dentro de los límites y se almacenara en NM[i]=nma, luego validaremos que no sea la misma materia para que inserte una nueva, una vez terminado el ciclo, abriremos otro ciclo for en el cual estableceremos un ciclo for, donde se introducirá el alumno y su calificación y se almacenara en M[i,j]=cal, una vez llenado el ciclo se abrirá uno nuevo donde se establecerá un ciclo for en el cual PA=PA+C[i,j] para despues llenarse en PA[i]=PA[i]+C[i,j] y luego PA[i]=PA/7, ahora se abrirá uno nuevo el cual se deteminara cual de todos es el mayor hasta llenar la matriz.
#### 1.2 DFD
![8](https://user-images.githubusercontent.com/113395327/205507474-c6e63589-0df7-4203-995a-925b5008524d.jpg)
#### 1.3 Prueba de escritorio
|corridas|i|j|M|j+1|
|-|-|-|-|-|
|1|0|0|M 0,0=Materia|j+1|
|2|0|1|M 0,1=Materia|j+1|
|3|0|2|M 0,2=Materia|j+1|
|4|0|3|M 0,3=Materia|j+1|

|Español|Matematicas|Historia|Geografia|
|-|-|-|-|
|5|4|3|9|
|8|6|4|7|
|9|7|7|6|
|7|9|8|7|
#### 1.4 Entradas.
na; nma; RE; cal. 
#### 1.5 Salidas.
No tiene salidas.
### Ejercicio 9. 
#### 1.1 Análisis.  
en un proceso delimitaremos la matriz, luego pediremos el limite, y validaremos que sea mayor a 1, despues en un ciclo for estableceremos otro ciclo for, en el cual se llenara la matriz y se sumarán los números.
#### 1.2 DFD
![9](https://user-images.githubusercontent.com/113395327/205507482-1b151083-e6f1-4ef6-b202-40633f42bee5.jpg)
#### 1.3 Prueba de escritorio
|i|vector|i=V?|
|-|-|-|
|1|0|V[i]=V[i-1]+i+1|
|2|1|V[i]=V[i-1]+i+1|
|3|2|V[i]=V[i-1]+i+1|

|1|
|-|
|3|
|6|
#### 1.4 Entradas.
n.
#### 1.5 Salidas.
A.
### Ejercicio 10. 
#### 1.1 Análisis.  
En un proceso vamos a determinar los limites de la matriz despues pediremos el tamaño de la matri y validaremos que este dentro de los límites, después pediremos m y en validaremos que este dentro de los límites, luego em un ciclo for estableceremos otro ciclo for en el cual iingresaremos el número y se almacenara en la matriz, y se repite todo hasta qque se llene.
#### 1.2 DFD
![10](https://user-images.githubusercontent.com/113395327/205507511-111fd6d1-676c-447b-b1f0-526a486f2683.jpg)
#### 1.3 Prueba de escritorio
|i|j|M|Suma|
|-|-|-|-|
|0|0|M [i,j]>mayor?-->si, M[i,j]=V [c] and C=c+1|j+1|
|0|1|M [i,j]>mayor?-->si, M[i,j]=V [c] and C=c+1|j+1|
|0|2|M [i,j]>mayor?-->si, M[i,j]=V [c] and C=c+1|j+1|
|0|3|M [i,j]>mayor?-->si, M[i,j]=V [c] and C=c+1|j+1|

If J=M, J=0 and I+1 y vuelve a iniciar
#### 1.4 Entradas.
n;m.
#### 1.5 Salidas.
No hay salidas
