# Tarea_2_Intro_IA
Estudiante: Sebastián Acevedo Ulloa
El objetivo de esta tarea es utilizar redes neuronales en un problema de clasificación de dígitos. Se utilizará el conjunto de datos Optical Recognition of Handwritten Digits Data Set. Este conjunto tiene 64 características, con 10 clases y 5620 muestras en total. La base de datos estará disponible en U-Campus.

Las redes a ser entrenadas tienen la siguiente estructura: capa de entrada de dimensionalidad 64 (correspondiente a los datos de entrada), capas ocultas (una o dos) y capa de salida con 10 neuronas y función de activación softmax. La función de loss (pérdida) es entropía cruzada. El optimizador que se debe usar es Adam. La función softmax está implícita al usar la función de pérdida CrossEntropyLoss de PyTorch (no se debe agregar softmax a la salida de la red).

Se usará PyTorch para entrenar y validar la red neuronal que implementa el clasificador de dígitos. Se analizará los efectos de cambiar el tamaño de la red (número de capas ocultas y de neuronas en estas capas) y la función de activación.

Instrucciones de ejecucion: Ejecutar código secuencialmente, primero importar librerias, cargar datasets de digitos, leer datasets de digitos, seleccionar modelo a utilizar (segun lo que se quiera ver, seleccionar uno de los modelos), crear datasets para pytorch, entrenar modelo, la siguiente parte del código puede ser ejecutada segun lo que se requiera ver.

El mejor modelo para el punto 3 (el con mejor accuracy en la etapa de validación) es: modelo con dos capas ocultas, 40 neuronas en cada una, funcion de activacion ReLu
