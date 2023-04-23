# predicciones-de-ventas1
**Visión general**
Este proyecto escudriña la siguiente base de datos para ser objeto de estudio de un análisis predectivo en pro de sus ventas: aplicando técnicas, habilidades de la ciencia de datos y comparando modelos de aprendizaje automático como recomendaciones.

**Datos**
El dataset propuesto denominado "sales_predictions" proviene del sitio web "Analytics Vidhya" en el que informa la cantidad, el tipo, la visibilidad, identificador del producto, su peso, planificación de requerimientos de material, la tienda y locación, el tamaño y tipo de ésta, sus años de establecimiento y ventas.

**Visualización**
Exploración de datos para la inferencia estadística. - Se empleó gráficos como **histogramas**, **caja de bigotes** y un **mapa de calor** .
Datos explicativos. - Diagramas como **scatter plot** con seaborn, entre otros parámetros.

**Resultados y recomendaciones**

* Al estudiar la columna "Item_MRP" realizando un histograma podemos estimar que se necesita organizar una cantidad entre 80% y 200% de materiales para la producción y respectivo sistema de inventario.

* Al establecer un mapa de calor se observa en la "Predicción de ventas" la correlación positiva de las columnas "Item_MRP" e "Item_Outlet_Sales".

* Creando un gráfico de dispersión con las variables "Outlet_Establishment_Year", "Item_Identifier" se analiza la relación de productos a través de los años: siendo el año de 1985 con la mayor cantidad de artículos.

* El modelo Regression tree es el más sensato para este tipo de base de datos: sus resultados están apegados a la realidad (más que nada el conjunto de prueba), evaluando en R2. 
