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

### Métodos tradicionales: One-Hot Encoding y TF-IDF

![image](src/9.JPG)

Mapea cada palabra a un vector, no tengo forma de comparacion de palabras y es muy extenso el mapeo

![image](src/8.JPG)

![image](src/10.JPG)

### TF-IDF

![image](src/12.JPG)

 Busca las palabras mas revelantes o inusuales en varios corpus
 
 TF-IDF se basa en dos conceptos principales:

Frecuencia de término (TF - Term Frequency): Mide la frecuencia con la que aparece una palabra en un documento específico. Cuanto más frecuente es una palabra en un documento, mayor será su puntuación de TF.

Frecuencia inversa de documento (IDF - Inverse Document Frequency): Mide la importancia de una palabra en el contexto de una colección de documentos. Se calcula como el logaritmo del número total de documentos dividido por el número de documentos que contienen la palabra en cuestión. Una palabra común que aparece en muchos documentos tendrá un IDF más bajo, mientras que una palabra menos común tendrá un IDF más alto.


![image](src/13.JPG)

![image](src/14.JPG)

![image](src/15.JPG)

![image](src/16.JPG)

![image](src/19.JPG)

![image](src/20.JPG)

![image](src/21.JPG)

La puntuación TF-IDF se calcula multiplicando la puntuación de TF de una palabra por su puntuación de IDF. 

La idea es determinar las palbras que menos se repiten y menos frecuencia tienen que tiene mas relevancia en el texto comparadas con palabras que se repiten mucho y tienen menos relevancia


![image](src/22.JPG)

La comparación de palabras utilizando TF-IDF implica calcular las puntuaciones TF-IDF para cada palabra en una colección de documentos y luego comparar las puntuaciones para determinar la relevancia de las palabras en diferentes contextos o documentos.

Desventjas de TF-IDF:
1- No hay orden de aparicion de palbras

2 - no permite compara palabras con otras

3 - dificil de calcular
