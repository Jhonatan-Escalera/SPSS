# T de Student para muestras relacionadas
***
Esta técnica paramétrica permite comparar 2 medias para una misma unidad de análisis, es decir que en muchos casos tenemos observaciones pareadas o datos interdependientes. Esto es muy típico de investigaciones experimentales en los que medimos la variable dependiente antes y después de cambiar la variable independiente. Si, por ejemplo, queremos investigar el efecto de la cafeína sobre el pulso sanguíneo podríamos obtener una muestra de personas y tomarles el pulso **antes y después** de hacerles tomar una taza de café. En caso de no cumplirse con los requisitos (por ejemplo, la normalidad es significativa `p<0,05`; se usa la prueba no paramétrica equivalente: **Wilcoxon**. En el programa SPSS se sigue la secuencia: `Analizar/Comparar medias/Prueba T para muestras relacionadas`. Allí solo se ingresan las variables sujetas a experimentación.
Lo que nos va a decir la prueba t en este caso es si la diferencia es significativamente diferente a cero: Si la variable independiente no tiene efecto entonces debería dar lo mismo medir antes o después.

* Requisitos:
1) La variable continua debe tener distribución normal en cada grupo, o ser superiores a 30 casos
2) Requiere conocer datos descriptivos como `N, M, DS` para ambas muestras.
***
**Ejercicio práctico:**

1. Tenemos un grupo de 20 estudiantes pertenecientes a la materia de álgebra y queremos investigar el efecto del uso de un recurso didáctico, (un video en YouTube), en su destreza para resolver cierto tipo de problemas matemáticos. Les tomamos un test inicial calculando los puntajes de cada estudiante, luego pedimos que miren el video y cuando terminen tomamos otro test. Ahora tenemos dos observaciones de cada estudiante. 

`BD-Comparación_medias.sav` **-> Trabaje con las variables Estudiantes, Antes y Después**

Se pide calcular la diferencia entre ellos, ¿A un nivel de confianza del 95% es significativa?, ¿Se podría decir que el recurso tiene efectos positivos?.
