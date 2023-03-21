# UVG-IA-LAB6

# PCA

PCA (Principal Component Analysis) es una técnica de análisis de datos que se utiliza para reducir la dimensión de un conjunto de datos mediante la extracción de características importantes y la eliminación de características redundantes o irrelevantes.

La técnica de PCA se utiliza comúnmente en el análisis de datos y la minería de datos para reducir la complejidad del modelo y mejorar la precisión del análisis. PCA se basa en la idea de que las variables originales están altamente correlacionadas entre sí, y que es posible expresarlas en términos de unas pocas variables independientes, llamadas componentes principales.

Al reducir la dimensionalidad de los datos mediante PCA, se eliminan las características que no son relevantes o que pueden causar ruido en los datos. Como resultado, se puede mejorar la calidad de los clusters obtenidos mediante técnicas de clustering, como K-Means.


# Clusters

elegimos 2 clusters debido a que la información está mejor esparcida dentro de dos clusters. Una de las variables que más influye es el género por lo que de esto también podemos inferir dos grupos diferentes.


# Métrica de desempeño

elegimos la inercia debido a que muestra de forma intuitiva y sencilla el desempeño del sistema. La inercia es una medida de la suma de las distancias al cuadrado entre cada muestra y su centroide más cercano. En otras palabras, representa la suma total de las distancias cuadráticas intra-cluster, es decir, la suma total de las distancias entre los puntos y el centro de su cluster asignado.

En el contexto del clustering, se utiliza la inercia como medida para evaluar qué tan bien están agrupados los datos. Un valor bajo de inercia indica que los puntos en cada cluster están cercanos entre sí y el centroide representa bien al cluster. Por lo tanto, una inercia más baja es generalmente deseable.


# Implementación

la mejor implementación, luego de analizar la métrica de desempeño seleccionada es la que tiene librerías pues el valor de la inercia es menor significando que los puntos de los clusters están cercanos entre sí.