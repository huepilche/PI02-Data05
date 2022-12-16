# PI02-Data05

BREVE DESCRIPCION:
Se realiza un Análisis Exploratorio de Datos e Ingeniería de Características para la posterior implementación de modelos de Machine Learning en un problema de Clasificación. El dataset trabajado contiene información de pacientes de un determinado hospital y se propone una predicción binaria del tiempo de permanencia al interior del centro hospitalario.

CONTENIDO DEL REPOSITORIO:
En la carpeta principal se encuentra el archivo principal .ipynb, el cual contiene explicaciones detalladas del Preprocesamiento, Análisis Exploratorio de Datos y la ingeniería de características, además de la licencia de uso y el archivo readme. En la carpeta Datasets se encuentran los archivos .csv que contienen información de los pacientes, notar que un archivo es usado para el entrenamiento de los modelos y otro para las pruebas de predicción.

MODELOS IMPLEMENTADOS: 
Para la clasificación y predicción se utilizó un arbol de decisiones y la maquina de soporte vectorial con kernel Gaussiano, ambos implementados desde la libreria SCIKIT-LEARN de Python. Para la ingeniería de características se incluye un estudio de las correlaciones de las caracteristicas, entre ellas y con la columna objetivo, también un breve análisis de las componentes principales del modelo. Para la optimización de los hiperparámetros se utilizó la función GrSearchCV, la cual realiza una validación cruzada para el ajuste de los hiperparámetros de profundidad en el arbol de decisiones y los coeficientes 'C' y 'gamma' en la maquina de soporte vectorial.
