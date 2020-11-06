# Ejemplo 3. Listas y data frames
#### Listas 
```R
milista <- list(nombre = "Pepe", no.hijos = 3, edades.hijos = c(4, 7, 9))
```

#propiedades de la lista
```R
str(milista)
```
#### Extrayendo elementos de la lista
```
milista$nombre
```

###DATA FRAMES
```R
x <- 6:8
y <- c("A", "B", "C")
mifile <- data.frame(edad = x, grupo = y)
mifile

str(mifile)
```

#### Extrayendo información del df, se hace igual que con las matrices
```R
mifile[1]
mifile[,1]
mifile$edad
```
#### Calculando algunos estadísticos básicos
```R
mean(mifile$edad)
```

#### Podemos hacer uso de la función paste() para agregar un mensaje
```R
paste("La media de la edad es:", mean(mifile$edad))
```

#### Podemos inspeccionar a detalle el df utilizando summary()
```R
summary(mifile)
```
#### También se puede conocer su dimensión 
```R
dim(mifile)
```
#### Podemos agregar una columna extra con datos 
```RR
mifile$sexo <- c("H", "M", "H")
mifile
```

#### Si fuera el caso, se puede eliminar una columna 
```R
mifile$sexo <- NULL
mifile
```
