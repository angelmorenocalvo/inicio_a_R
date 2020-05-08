# Objetos en R
## tipos basicos
- character
- numeric, integer, complex
- logical: TRUE/FALSE

## Objetos
- Vectores
- Factores
- Matricesm, arrays 
- data.frame
- Listas.
- Funciones
- Objetos ad-hoc

### Vectores
La estructura más simple es el vector numérico, consiste en un conjunt0 ordenados de números.

``` R
x <- c(1.3, 2.4, 0, 4, 9.7, 8.3)
s <- c(x, 0 , x)
```

Un número por si solo es un vector.
``` R
n <- -5
```

Si el objeto es vacío entonces sera __NULL__

__Vectores de caracteres__ 
``` R
x <- c("España", "Francia", "Portugal")
```
__letters__
nos permite crear un vector de la "a" a la "z"
si escribimos __LETTERS__ tendremos lo mismo pero las letras en mayuscula.
__Vectores lógicos__ 
``` R
x <- c(FALSE, FALSE, TRUE, FALSE)
```

