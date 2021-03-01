# T de Student para muestras independientes
***
Esta prueba de tipo paramétrica es considerada para comparar la media entre dos grupos, para la cual se deben cumplir algunos requisitos. En caso de no cumplirse (por ejemplo, cuando la homogeneidad de varianzas es significativa `p<0,05`; se usa la prueba no paramétrica equivalente: U de Mann-Whitney. En el programa SPSS se sigue la secuencia: `Analizar/Comparar medias/Prueba T para muestras independientes`. Allí solo se selecciona la variable independiente, y la referida a los grupos de control y experimental.

* Requisitos:
1) La variable continua debe tener distribución normal en cada grupo, o ser superiores a 30 casos
2) Las varianzas deben ser homogéneas en todos los grupos (criterio de homocedasticidad). En este sentido el test de Levene no significativo implica asumir que las varianzas no son significativas (o que son homogéneas).
3) Requiere conocer datos descriptivos como `N, M, DS` para ambas muestras.

La prueba t de Student compara dos medias, sea la media de dos categorías dentro de una misma variable. También se usa para muestras grandes. cuantos más grados de libertad se obtenga, la distribución t de student se acerca más a ser una distribución normal `(gl >120 es normal)`.
***
**Ejercicio práctico:**

1. Un supermercado tiene dos formas diferentes de venta: tradicional o con caja rápida. En la tradicional, un operario registra cada artículo, lo pone en bolsas y efectúa el cobro. En la caja rápida, el cliente registra cada artículo, lo introduce en bolsas y paga en una máquina con tarjeta de crédito. La dirección del supermercado desea saber si el tiempo medio que un cliente se encuentra en la fila del proceso con el método tradicional es mayor que con la caja rápida, reuniendo la información adjunta:

`BD-Comparación_medias.sav` **-> Trabaje con las variables Venta y tiempo**

Suponiendo que el tiempo en espera en el proceso sigue una ley normal, con un nivel de confianza del 95%, ¿Qué decisión debería adoptar el supermercado para agilizar las ventas?
