En estadística, suele ser de mucha utilidad representar la información a través de gráficos, ya que permiten condensar la información en una sola visualización, relacionar los conceptos y darle cierta interpretabilidad en algunos casos.

<br>
**BOXPLOT**<br>
El **_boxplot_** o **diagrama de caja con bigotes** nos da una idea de la distribución de los datos y nos indica los cortes de los **cuartiles** y la **mediana**, e incluso permite visualizar **casos atípicos**.

<br>
<img src="https://raw.githubusercontent.com/dh-mumuki/mumuki-guia-text-estadistica-1-estadistica-descriptiva/master/assets/boxplot_1541006118610.jpg" alt="boxplot_1541006118610.jpg" width="auto" height="auto">

<br>
**Percentiles y Cuartiles**<br>
El percentil es una medida de posición que indica, una vez ordenados los datos de menor a mayor, el porcentaje de observaciones que se acumulan hasta ese valor. Veámoslo con un ejemplo simple:<br>

Supongamos que tenemos una muestra de las alturas de 100 alumnos y alumnas de una universidad y las ordenamos de menor a mayor; el percentil 75 incluye las 75 primeras observaciones, independientemente de cuál sea su valor.<br>

Si nosotros quisiéramos separar nuestras observaciones en **cuatro grupos de igual tamaño**, podríamos definir tres **puntos de corte: el percentil 25, el percentil 50 y el percentil 75**. Estos puntos de corte, justamente, reciben el nombre de **cuartiles**, y son representados en un **boxplot** por la línea inferior, la línea central y la línea superior de la caja, respectivamente. De esta forma, vemos que la caja representa los valores propios del 50% central de nuestros datos.

<img src="https://raw.githubusercontent.com/dh-mumuki/mumuki-guia-text-estadistica-1-estadistica-descriptiva/master/assets/ejemplo_gr%C3%A1fico_percentil-640x535_1541087498987.png" alt="ejemplo_gráfico_percentil-640x535_1541087498987.png" width="auto" height="auto">

<br>
> Ya dimos la definición de la mediana, aquel valor que divide en dos partes iguales una muestra. ¿A qué percentil corresponde?

<br>
**Rango intercuartílico, bigotes y casos atípicos**<br>
Ya hemos visto que los límites de la caja vienen dados por los valores del primer cuartil (percentil 25) y del tercer cuartil (percentil 75). A la diferencia entre ambos se la llama comúnmente **rango intercuartílico**:<br>
**RIC = Q3 (75%) - Q1 (25%)**
<br>
Los **bigotes** (o **whiskers**, en inglés) son las líneas que se extienden por fuera de la caja. Para definir su largo, debemos **multiplicar al RIC por algún valor** arbitrario, **típicamente** 1,5 (más adelante veremos que este valor tiene estrecha relación con las características propias de la **distribución normal**). Restando y sumando este valor a los valores de los bordes inferior y superior de la caja, respectivamente, obtenemos los límites inferior y superior de nuestro **boxplot**:<br>
1. Límite inferior = Q1 - 1,5 x RIC
2. Límite superior = Q3 + 1,5 x RIC

<br>
Todas las observaciones que queden por fuera de los bigotes serán considerados **casos atípicos** (o **outliers**, en inglés), es decir, aquellos registros que presentan valores muy por encima o por debajo de la mayor parte de nuestros datos. Estas observaciones deberán ser tratadas con especial atención, ya que van a tener suma influencia sobre los cálculos de las medidas de tendencia central y dispersión más frecuentes (¿por qué?). Por otra parte, veremos que los outliers, lejos de representar valores de la realidad, muchas veces son el resultado de errores de registro típicos de cualquier proceso de recolección de datos (ya sea manual o automática).
