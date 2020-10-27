# Universidad del Valle de Guatemala
## Autor: Jose Javier Jo Escobar
### Tesis: Deteccion de Fraude
 En este repositorio se encuentra el prototipo realizado para el trabajo de graduacion para la deteccion de posibles proveedores fraudulentos en reclamos de salud.
Actualmente el fraude es uno de los principales problemas que enfrentan los sistemas de seguros médicos y sanitarios, la RAE define fraude como: acción contraria a la verdad y a la rectitud, que perjudica a la persona contra quien se comete. Este es un problema al cual se enfrentan las aseguradoras debido a la falta de profesionalidad de médicos y proveedores, impacta en los costos de operación generados por los reclamos de los asegurados en el rubro de la salud. Las aseguradoras se han dado la tarea de analizar numerosos registros para encontrar conductas posiblemente sospechosas y fraudulentas, este proceso actualmente es ineficiente ya que se realiza de manera manual. 

Esta investigación tiene como objetivo desarrollar un modelo de machine learning que detecte de manera precisa el posible fraude realizado por proveedores en reclamos de salud. También busca utilizar la ingeniería de características ya que esta técnica mejora la precisión de predicción realizada por el modelo. Se busca desarrollar diferentes algoritmos de categorización realizando el preprocesamiento la información necesaria para su entrenamiento y evaluación, logrando mostrar su precisión en la detección de fraude. Finalmente se determinará el modelo que detectó con mayor precisión el posible fraude.

#Objetivos
Se presentan los objetivos que se buscan alcanzar en el desarrollo del trabajo.

##General
* Implementar el modelo de machine learning que detecte con mayor precisión el posible fraude por proveedores en reclamos de salud.

##Específicos 
* Implementar ingeniería de características para mejorar la precisión de la predicción y el reconocimiento de patrones de fraude en el conjunto de datos analizado.

* Desarrollar prototipos con diferentes modelos de machine learning identificando sus precisiones en la detección del posible fraude por proveedores en reclamos de salud.

* Identificar  el modelo de machine learning con la mejor precisión para la detección del posible fraude por proveedores de reclamos de salud en el conjunto de datos analizado.


#Metodologia
* Definición del Problema: Se definió el problema a resolver con machine learning.
* Investigación: Se investigaron los modelos de machine learning candidatos para solucionar el problema de categorización definido en el paso anterior.
* Minería de Datos: Se realizó limpieza y análisis exploratorio del conjunto de datos.
* Preprocesamiento de Datos: Se formatearon y estandarizaron los datos, también se realizaron conversión de variables y separados los conjuntos de entrenamiento y prueba.
* Implementación de Modelo: Se definieron las bibliotecas y modelos a utilizar en posteriores fases.
* Entrenamiento: Se realizó el entrenamiento de los modelos de regresión logística, random forest y autoencoder.
* Evaluación: Se evaluó el rendimiento de los modelos entrenados.
* Predicción: Se verificaron los verdaderos positivos y falsos positivos de la predicción realizada por cada modelo.


#Resultados 
El modelo de machine learning que detectó con mayor precisión el posible fraude por proveedores es el de regresión logística, ya que tuvo un accuracy de ~0.91 lo que nos indica que identificó con un 91% de precisión los casos positivos correctamente identificados de todos los casos predichos. También tuvo una puntuación F1 de ~0.59 la cual nos proporciona una mejor medida de los casos clasificados incorrectamente siendo crucial obtener una puntuación alta en un conjunto de datos desequilibrado. 