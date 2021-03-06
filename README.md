## NLP Twitter

### ¿Qué es este proyecto?

Este proyecto muestra diferentes usos del Natural Language Processing (NLP) aplicados con datos de la red social Twitter. Realizamos una gráfica en la que se puede ver el sentimiento de las personas acerca de un tema en especial en tiempo real.

### ¿Cómo funciona?

Seguimos el tutorial de Sentdex sobre cómo hacer sentiment analysis sobre tweets que se estén publicando que incluyan una palabra o frase que nosotros podemos especificar, utilizando NLTK y Tweepy.
El código entrenaba varios clasificadores que utilizan distintos algoritmos, donde cada uno de ellos dictamina si un tweet es positivo o negativo, y al final se utiliza un sistema de “votos” para determinar la certeza de las predicciones del sentimiento, dependiendo de cuántos de los clasificadores coincidieran con el mismo resultado.

### ¿Quién puede usar este repositorio?

Quien sea que esté interesado en ver los patrones de sentimiento de los usuarios de Twitter acerca de una cuenta o un tema en especial.

### ¿Cuál es el objetivo de este proyecto?

Usar herramientas modernas como NLP para entender el comportamiento humano y los sentimientos de las personas en redes sociales como Twitter

### ¿Cómo corro este proyecto?

- Correr el notebook "Combined Algorithms" para generar featuresets.pickle
- Crear un archivo twitterkeys.py con tus API keys de Twitter
- Correr primero TwitterStream.ipynb y después Graphs.ipynb mientras TwitterStream sigue ejecutándose para visualizar la grafica en tiempo real.