#Taller de Machine Learning ICIF1041

https://tinyurl.com/8tpzx9c8

    • Prueba Solemne 1
    • Modalidad: Individual
    • Entrega a traves de classroom en su sección de laboratorio
    • Fecha de entrega: 6 Septiembre 2024 23:59

En esta prueba solemne, usted debe demostrar sus conocimientos adquiridos. Cumplir con lo mínimo solicitado no le garantiza la nota máxima, ya que se espera proactividad y curiosidad de su parte.
Usted cuenta con el apoyo de su profesor en caso de que requiera clarificar algún requerimiento o guía en esta tarea, por lo que si se ve estancado o no entiende alguna parte del proyecto, escriba un correo o pida una reunión con su profesor. En las clases de la semana del 2 de Octubre se resolverán dudas y responderán preguntas  referentes a la prueba.

Se entrega el jupyter notebook. Use celdas con texto para justificar y explicar cada paso. Se esperan al menos 2000 palabras de justificación y explicación de los pasos seguidos y resultados obtenidos.
Rúbrica:
# Solemne 1: Sistema recomendador de canciones

Usted ha sido recientemente contratado como científico de datos en Spotify. En la empresa consideran que una de las características que mas valoran de su producto es que tiene una gran biblioteca de canciones, pero los usuarios indican que el sistema carece de recomendaciones acordes a las votaciones o canciones que hayan escuchado. Spotify ha tomado esto seriamente y se ha dedicado a recolectar datos de sus usuarios, por lo que le han solicitado a usted ayudarlos en la creación de un sistema recomendador basado en los gustos de cada personas.

# Descripción de los datos:

Para este propósito, usted cuenta con los siguientes conjuntos de datos:

* El archivo **spotify_dataset.csv** contiene un dataset con 42305 canciones Spotify, descritas con 23 características, como el "*danceability*", el "*accousticness*" o el "*loudness*".

* El archivo **labeled_songs.csv** contiene las 23 carácterísticas y el genero correspondiente de 150 canciones.

* El archivo **user_preferences.csv** contiene por cada uno de los 6 usuarios (con indices del 0 al 5), el índice de las canciones del archivo spotify_dataset que le han gustado.

# Tarea y actividades a realizar:

Aprovechando la gran cantidad de datos existentes en el dataset de canciones y la valiosa información contenida en labeled_songs.csv, construya un sistema que para cada uno de los 6 usuarios, le recomiende otras 10 canciones. El sistema puede ser construido utilizando técnicas de agrupamiento o asociación.

El procedimiento a seguir debe ser el siguiente:


1. Cree una copia de este notebook a su collab personal o uselo para trabajar en su computador con Jupyter Notebook

2. Utilice al menos 2 algoritmos de los explicados en la unidad 1 (clusterización o asociación) para completar las etiquetas de género de los 42305 ejemplos del archivo "spotify_dataset.csv". Asigne el genero de las canciones en función de la etiqueta mas frecuente del subconjunto "labeled songs" en cada grupo después de definir el número optimo de grupos para cada uno de los algoritmos utilizados.

3. Recomiende 10 canciones a cada uno de los usuarios del archivo "users_preferences.csv". Detalle el criterio que usó para recomendar las canciones y por que lo eligió. ¿Cambian las recomendaciones según el algoritmo usado?, explique porque cambian o porque no cambian

4. Cambie la metodología usada para determinar el numero óptimo de clusters. Razone porque hay cambios (o porque no los hay)

Se entrega el jupyter notebook. Use celdas con texto para justificar y explicar cada paso.