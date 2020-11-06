
####   EJEMPLO 1
#Tipos de datos y Vectores

``` R
var.hola <- "Hola Mundo"
var.number <- 5
var.double <- 2.7076
var.logical <- T
vector <- c(1,2)

class(var.number)
class(var.hola)
class(var.double)
class(var.logical)

typeof(vector)
typeof(var.number)
``` 
#### Crear vectores 

``` R
a <- c(4, 6, 8, 10,12)
b <- c(3, 5, 7, 9)
```

#### Para saber la dimensión del vector 
```R
length(a)
length(b)
```

#### Se puede acceder a las coordenadas de un vector haciendo uso de [] y su posición
```R
a[1]
b[4]
```

#### Juntar 2 vectores 
```R 
c(a,b)
```

#### Organizarlos con el comando sort(), cambia la F por T y observa que ocurre
```R
sort( c(a,b), decreasing = F)
```
#### Otra forma de generar el vector es de la siguiente manera, utilizando ":"
```R
3:12  #así de sencillo es
```

#### Intenta los siguientes y prueba con otras que se te vengan a la imaginación
```R
10:1
1:1000
0:10
```

#### También se pueden generar vectores que no sean sucesivos con el comando **seq()**
####intenta cambiar los parametros y observa el comportamiento de los vectores
```R
vector.by2 <- seq(from = 1, to = 10, by =2)
vector.by2

vector.by3 <- seq(1, 10, 3)
vector.by3
```
#### Para repetir un número o un vector un determinado número de ocasiones utilizamos rep()
```R
rep(5, times = 6)
```
#### Observa que hace el siguiente comando con los vectores **a** y **b**
```R
rep(a, 2)
rep(b, 3)
```

####Reciclaje, al hacer operaciones entre vectores, R repetirá los valores del vector, 
#### hasta alcanzar la dimensión requerida
``` R
c(1, 2) + c(7, 8, 9, 10)
```

#### Operaciones entre vectores
```R
a + b     
a - b     
a*b
a/b
a^2
a1 <- a*0.5 + b^2
a1[1]
```
