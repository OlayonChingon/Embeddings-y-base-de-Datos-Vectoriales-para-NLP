# Embeddings y base de Datos Vectoriales para NLP

## Clase 1 - Como una maquina entiende el lenguaje humano

![image](src/4.JPG)

![image](src/1.JPG)

![image](src/5.JPG)

![image](src/6.JPG)

![image](src/7.JPG)

En este caso, el resultado del cómputo de los embeddings es una matriz de tipo float32, donde cada fila representa el embedding de una frase en la lista sentences. Cada embedding es un vector numérico de alta dimensionalidad.

La dimensionalidad específica de los embeddings depende del modelo pre-entrenado utilizado. En este caso, el modelo "all-MiniLM-L6-v2"

Cada valor numérico en el embedding representa la fuerza o importancia de una cierta característica o atributo de la frase en el espacio vectorial. 

### Base de datos Vectoriales
![image](src/2.JPG)


Una base de datos vectorial es un tipo de base de datos que se utiliza para almacenar y buscar información basada en características o atributos vectoriales. En lugar de almacenar datos en forma de registros 
y campos como en una base de datos relacional tradicional, una base de datos vectorial almacena los datos en forma de vectores.

En una base de datos vectorial, cada registro o entidad se representa como un vector multidimensional, donde cada dimensión o atributo del vector corresponde a una característica específica. Estos atributos pueden ser numéricos,
como coordenadas geográficas, o pueden ser atributos categóricos, como palabras clave o etiquetas.

La base de datos vectorial permite realizar operaciones de búsqueda y recuperación de información utilizando técnicas de similitud y distancia vectorial. Por ejemplo, se pueden buscar registros similares basados en la similitud
de sus vectores, utilizando algoritmos como la similitud del coseno o la distancia euclidiana.

Las bases de datos vectoriales se utilizan en diversas aplicaciones, como sistemas de recomendación, búsqueda de información, análisis de datos científicos y minería de datos. Son especialmente útiles cuando se trata de 
datos que tienen una estructura vectorial inherente y cuando se requiere realizar consultas basadas en similitud o proximidad.

### Proyecto del curso

![image](src/3.JPG)
