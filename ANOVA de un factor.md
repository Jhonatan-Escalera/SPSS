# ANOVA de un factor
***
Esta prueba paramétrica se utiliza para comparar tres o más grupos mediante un análisis de varianza. Este tipo de análisis permite determinar si diferentes grupos muestran diferencias significativas, o por el contrario, que sus medias poblacionales no difieren. En caso de no cumplirse algunos
requisitos para llevar adelante la prueba, su equivalente no paramétrico es la prueba Kruskal-Wallis para comparar tres o más grupos.

El Anova es similar a la prueba T de student, pero no compara los grupos a través de las medias sino a través de la varianza (análisis de varianza). La variabilidad o varianza total que podemos tener en los datos implica la sumatoria de: 

a) Una varianza entre grupos, que refleja la variabilidad entre las medias de cada grupo respecto a la media total de las observaciones (varianza inter-grupos). 

b) Una varianza dentro de los grupos, que mide la variabilidad de cada observación respecto a la media de su grupo (varianza intra-grupos).

_El equivalente en el análisis de varianza multivariado es el MANOVA._

## Requisitos:
1. La distribución debe ser normal.
2. Con grupos independientes y homogeneidad de varianza (varianza similar).
3. Relación lineal entre la variable y el factor. Si la varianza es muy desigual, se salva con un N igual para cada grupo (o emplear el post-hoc para varianza desigual como el de Games-Howell).

Luego de verificadas las condiciones para llevar a cabo un análisis de varianza con Anova, procedemos a su ejecución. Cuando la diferencia explorada entre los tres o más grupos es estadísticamente significativa, interesa explorar ahora la diferencia entre pares de grupos. Para ello empleamos pruebas Post hoc. Los más utilizados son:
1. Test de Tukey _(Se puede utilizar la prueba cuando existe homocedasticidad y los tamaños de los grupos son iguales)_
2. Test de Bonferroni 
3. Test de Duncan

Si los tamaños de los grupos son ligeramente distintos se debería usar la prueba de Gabriel, dada su potencia; pero si son muy diferentes los tamaños se debe usar la prueba GT2 de Hochberg. En el caso de que las varianzas sean muy diferentes (heterocedasticidad) se recomienda utilizar la prueba de Games-Howell.

En el programa SPSS, para llevar a cabo la prueba Anova una vez que hemos verificado sus requisitos, debemos seguir la siguiente secuencia: `Análisis/Comparación de medias/Anova de un factor`. Allí podemos seleccionar las variables independientes, y el factor o los grupos que se pretender comparar.
***
## Ejercicio:
1. El gerente de una sucursal de una cadena de tiendas renuncio. Tres vendedores pueden ocupar su puesto, tienen la misma antigüedad, educación, etc. Para tomar una decisión se tomó un registro de sus ventas mensuales de cada uno. En la siguiente tabla se muestran los resultados muéstrales de las ventas en miles de dólares.

`BD_Comparación_medias.sav` **-> Utilice las variables Vendedores y Ventas**

¿Existe al menos un vendedor que tenga un registro de ventas altas?, desde un el punto de vista del contratante, ¿Qué vendedor debería ocupar el puesto de gerente?
