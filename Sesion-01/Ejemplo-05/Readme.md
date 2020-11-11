## Ejemplo 5. Instalar packages y leerlos. 
Esto es útil ya que agrega funcionalidades a R, ya sea para graficar o generar análisis con diversas técnicas.

Se instalan de la siguiente manera

```R
install.packages("ggplot2")    #siempre lleva  comillas
```
Una vez que se instalo, se debe de cargar 
```R
library(ggplot2)                # Se omite el uso de las comillas
```
Otro ejemplo
```R
install.packages("dplyr")
library(dplyr)
```

Algo útil es revisar la versión que se tiene de R, ya que en ocasiones no se instalan ciertos paquetes por la incompatibilidad de R, el siguiente comando nos indicará la versión que estamos trabajando.

```R
version
```

También se puede realizar esta acción en la pestaña de Packages, intentalo.
