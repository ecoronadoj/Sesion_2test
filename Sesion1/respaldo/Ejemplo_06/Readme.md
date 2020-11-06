# Ejemplo 6. Loops: For

#### Este ejemplo elevará al cuadrado las primeros 10 entradas de un vector generado aleatóriamente de 20 entradas 
```R
w <- rnorm(20)              
print("Este loop calcula el cuadrado de los 10 primeros elementos del vector w")
```
#### inicializando la varialbe `wsq`
```R
wsq <- 0

for(i in 1:10) {
  # i-th element of `u1` squared into `i`-th position of `usq`
  wsq[i] <- w[i]**2
  print(wsq[i])
}
```
