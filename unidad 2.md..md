
act,2.1
 1. Aplicación de Uber

- **Tarea (T):** Solicitar un viaje desde una ubicación hasta un destino.
- **Experiencia (E):** La aplicación muestra el mapa, tiempo estimado de llegada, datos del conductor y permite seguir el viaje en tiempo real.
- **Medición (P):** Tiempo que tarda en solicitarse el viaje, tiempo de espera del conductor, duración del viaje y calificación del servicio.

 2. Aplicación de Netflix

- **Tarea (T):** Buscar y reproducir una película o serie.
- **Experiencia (E):** La aplicación ofrece recomendaciones, categorías, avances y una interfaz sencilla para encontrar contenido.
- **Medición (P):** Tiempo necesario para encontrar una película, tiempo de carga/reproducción, cantidad de contenido visto y calificación o interacción con las recomendaciones.

act 2.2
Aprendizaje supervisado

El aprendizaje supervisado funciona cuando la computadora aprende usando datos que ya tienen una respuesta. Por ejemplo, si le mostramos varios correos que ya están marcados como spam y otros que son normales, la computadora aprende a distinguir las características de cada uno. Después, cuando recibe un correo nuevo, puede identificar si es spam o si es un correo normal.

Aprendizaje no supervisado

El aprendizaje no supervisado es diferente porque la computadora recibe muchos datos, pero estos no tienen una respuesta o categoría indicada. Entonces, el sistema analiza la información por su cuenta y busca cosas que tengan en común para poder formar grupos. Por ejemplo, puede juntar a personas que tengan gustos o características similares sin que nosotros le indiquemos exactamente cómo debe separarlas.

Aprendizaje por refuerzo

El aprendizaje por refuerzo se basa en aprender mediante prueba y error. La computadora realiza una acción y, dependiendo de si el resultado es bueno o malo, recibe una recompensa o una penalización. Con el tiempo, va aprendiendo qué acciones le convienen más para conseguir su objetivo. Un ejemplo podría ser un robot que intenta encontrar el camino para llegar a una meta y aprende cuáles caminos debe tomar y cuáles debe evitar.

act 2.3 
glosario (todo con base en machine learning)
Glosario de Machine Learning

Pandas  
Es una biblioteca de Python que se utiliza para organizar, limpiar y analizar datos. En Machine Learning se puede utilizar para cargar conjuntos de datos, eliminar información que no sea necesaria, trabajar con datos faltantes y preparar los datos antes de entrenar un modelo.

Matplotlib  
Es una biblioteca de Python que permite crear gráficas y visualizar datos. En Machine Learning sirve para observar patrones, comparar resultados y representar de manera gráfica los datos o el comportamiento de un modelo.

Scikit-learn (sklearn)  
Es una biblioteca de Python enfocada en Machine Learning. Cuenta con herramientas para preparar datos, entrenar modelos, realizar predicciones y evaluar sus resultados.

Scikit-learn también incluye algunos conjuntos de datos que se pueden utilizar para practicar y probar modelos, como Iris, Digits, Wine, Breast Cancer y Diabetes. Por ejemplo, el conjunto de datos Iris tiene 150 registros de flores, con cuatro características: longitud y ancho del sépalo y longitud y ancho del pétalo. Los registros pertenecen a tres especies diferentes: Setosa, Versicolor y Virginica. Una forma común de trabajar con estos datos es utilizar el 80% para entrenar el modelo y el 20% restante para probarlo, es decir, 120 datos para entrenamiento y 30 para prueba.

Google Colab  
Es una plataforma de Google que permite escribir y ejecutar código de Python desde un navegador, sin tener que instalar Python y las bibliotecas necesarias directamente en la computadora. En Machine Learning se puede utilizar para cargar datos, entrenar modelos, realizar pruebas y crear gráficas.

Árbol de decisión  
Es un algoritmo de Machine Learning que utiliza una estructura parecida a un árbol para tomar decisiones. Cada parte del árbol representa una condición o pregunta sobre los datos y, dependiendo de la respuesta, se sigue una rama hasta llegar a una predicción. Puede utilizarse para clasificación y también para regresión.

Matriz de confusión  
Es una herramienta que sirve para evaluar modelos de clasificación. Compara las predicciones que hace el modelo con los resultados reales y permite identificar los verdaderos positivos, verdaderos negativos, falsos positivos y falsos negativos.

Sobreajuste (Overfitting)  
Sucede cuando un modelo aprende demasiado los datos utilizados durante el entrenamiento, incluso detalles o errores que no son importantes. Esto provoca que el modelo tenga buenos resultados con los datos de entrenamiento, pero que tenga dificultades cuando recibe datos nuevos. Para identificarlo se pueden comparar los resultados obtenidos con los datos de entrenamiento y con los datos de prueba.


act 2.4
1. Árbol de decisión 

Definición: Es un algoritmo de aprendizaje supervisado que utiliza una estructura de árbol para tomar decisiones a partir de condiciones y características de los datos. Divide la información en ramas hasta llegar a una predicción o clasificación.

Caso de uso: En un banco, se puede utilizar para determinar si una persona puede recibir un préstamo, considerando sus ingresos, historial crediticio, deudas y capacidad de pago.


Géron, A. (2022). Hands-on machine learning with Scikit-Learn, Keras, and TensorFlow (3.ª ed.). O'Reilly Media. [https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/) 

 2. Regresión logística 

Definición: Es un algoritmo de aprendizaje supervisado que se utiliza principalmente para clasificar datos en categorías. Calcula la probabilidad de que un dato pertenezca a una clase, por ejemplo, determinar si un correo electrónico es spam o no.

Caso de uso: Una empresa de telecomunicaciones puede utilizarlo para predecir si un cliente tiene probabilidad de cancelar su servicio, considerando su antigüedad, uso y número de quejas.


James, G., Witten, D., Hastie, T., Tibshirani, R., & Taylor, J. (2023). An introduction to statistical learning: With applications in Python. Springer. [https://www.statlearning.com/](https://www.statlearning.com/) 

3. K vecinos más cercanos (K-NN)

Definición: Es un algoritmo de aprendizaje supervisado que clasifica un dato nuevo según las categorías de sus K vecinos más cercanos. Utiliza la distancia entre los datos para identificar cuáles son los más similares.

Caso de uso: Una aplicación de reconocimiento puede clasificar una fruta como manzana, naranja o plátano comparando sus características, como tamaño, peso y color, con las de frutas previamente identificadas.


James, G., Witten, D., Hastie, T., Tibshirani, R., & Taylor, J. (2023). An introduction to statistical learning: With applications in Python. Springer. [https://www.statlearning.com/](https://www.statlearning.com/) 

 4. Naive Bayes 

Definición: Es un algoritmo de clasificación basado en el teorema de Bayes que calcula la probabilidad de que un dato pertenezca a una categoría. Se llama ingenuo porque asume que las características son independientes entre sí, dada la clase.

Caso de uso: Un sistema de correo electrónico puede utilizarlo para identificar mensajes como spam o no spam, analizando palabras, enlaces y otras características del mensaje.


Murphy, K. P. (2012). Machine learning: A probabilistic perspective. MIT Press. [https://mitpress.mit.edu/9780262018029/machine-learning/](https://mitpress.mit.edu/9780262018029/machine-learning/) 

 5. Máquinas de vectores de soporte (SVM)

Definición: Es un algoritmo de aprendizaje supervisado que se utiliza para clasificación y regresión. Busca encontrar el hiperplano que mejor separa las categorías de datos, maximizando el margen entre ellas.

Caso de uso: En el sector médico, puede utilizarse para clasificar tumores como benignos o malignos a partir de características obtenidas de estudios clínicos, como tamaño, textura y forma.


Cortes, C., & Vapnik, V. (1995). Support-vector networks. Machine Learning, 20, 273–297. [https://doi.org/10.1007/BF00994018](https://doi.org/10.1007/BF00994018) 

6. Bosque aleatorio (Random Forest)

Definición: Es un algoritmo de aprendizaje supervisado que combina múltiples árboles de decisión para realizar predicciones. Cada árbol se entrena con muestras y características seleccionadas aleatoriamente, y sus resultados se combinan para obtener una predicción final, lo que ayuda a reducir el sobreajuste.

Caso de uso: Una empresa puede utilizarlo para predecir qué clientes podrían abandonar sus servicios, analizando datos como antigüedad, frecuencia de uso, pagos y quejas.


Géron, A. (2022). Hands-on machine learning with Scikit-Learn, Keras, and TensorFlow (3.ª ed.). O'Reilly Media. [https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/) 

7. Red neuronal 

Definición: Es un modelo de aprendizaje automático inspirado en la estructura del cerebro humano, compuesto por neuronas artificiales organizadas en capas. Aprende patrones a partir de los datos ajustando conexiones y pesos, y se utiliza en tareas como reconocimiento de imágenes, procesamiento del lenguaje y predicción.

Caso de uso: Una aplicación de reconocimiento facial puede utilizar una red neuronal para identificar características de un rostro y compararlas con patrones aprendidos para reconocer a una persona.


Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep learning. MIT Press. [https://www.deeplearningbook.org/](https://www.deeplearningbook.org/)





![[Captura de pantalla 2026-10-08 a las 18.10.19.png]]

el breadth-first- search busca del punto verde al rojo mediante un cuadrante de busqueda.![[Captura de pantalla 2026-10-08 a las 18.15.06.png]]

en dijkstra se buscan entre si con todo el cuadrante rojo y verde al mismo tiempo.