# TFM: Indicador Social en la niñez Colombiana usando Machine Learning
# Nombre Estudiante: Beatriz Elena Jaramillo Gallego

![indicador](https://github.com/betitajara0812/TFM/blob/main/indicador.jpg)


El código generado para la realización de este trabajo final de master esta divido en 8 partes:

__1. Data Set (ENCV-2018):__ El data set usado proviene de la Encuesta de Calidad de Vida (ECV) es una investigación que el DANE (Departamento Administrativo Nacional de Estadística) 

__2. Análisis exploratorio:__ Se hizo un análisis exploratorio descriptivo de la base de datos de las variables que se han seleccionado para continuar con el análisis que se ha propuesto para este trabajo de final de Master.

__3. Preprocesamiento:__ Se realizaron las transformaciones necesarias en la búsqueda de encontrar buenos resultados en el algoritmo de machine learning.

__4. Creacion de un Modelo Predictivo:__ Ajustaré un modelo basado en una máquina vector soporte lineal que prediga la exclusión social en Colombia por departamentos en función de los predictores disponibles.

__5. Predicción:__ Se ajustará el modelo usando la función predict() del paquete caret, con el que podremos predecir nuevos datos utilizando el objeto devuelto por train().

__6. Modelos:__ Se entrenan diferentes modelos de machine learning con el objetivo de compararlos e identificar cual de estos arroja el mejor resultado obtiene prediciendo la exclusión social en Colombia por departamentos. Se ha entrenado con K-Nearest Neighbor (kNN), Regresión Logistica, Modelo LDA, Arbol de Clasificación Simple y Random Forest

__7. Analisis Cluster:__ Continuamos nuestro Analisis con los Datos Test, y confirmar que han sido bien clasificados deacuerdo con la realidad del pais (seleccionamos las predicciones del arbol simple).

__8. Indicador de Exclusión Social:__ Resumen del escenario en donde se ve por departamentos cual es el porcentaje de hogares encuestados que cuentan o están en riesgo de exclusión social de acuerdo con las características del hogar encuestado.
