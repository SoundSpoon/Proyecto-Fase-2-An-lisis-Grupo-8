# Proyecto-Fase-2-Análisis-Grupo-8
Una cantidad significativa de niños menores de 10 años presenta síntomas de asma en el país de Guatemala. Como bien ha sido documentado, la mayoría de estos pacientes puede ser controlados si se detecta su caso específico antes de que adquiera severidad. 

Por medio de este proyecto, se pretende analizar por medio de Machine Learning una gran base de datos sintética, y lograr predecir:
- Severidad de las crisis
- Predicción de hospitalización según evolución
- Apoyo en toma de decisiones clínicas en emergencia


# Decisión clínica
Un paciente que no cuenta con su historial clínico es propenso a tener dificultades que podrían ser evitadas si tan solo el médico que lo examina tuviera más información de este, principalmente cuando el paciente sufre de una enfermedad como el asma ya que tiene un fuerte componente hereditario a pesar de no ser una herencia directa. 
Todo esto es aún más importante cuando el paciente es un niño de 0 a 9 años, ya que ellos son más propensos a tener complicaciones asmaticas si no se tratan de manera correcta por lo que es importante para el médico saber si el paciente que están tratando padece o no de asma en su familia.
En Guatemala se cuenta con una gran parte de la población la cual no conoce mucho sobre el tema por lo que es más fácil que un paciente pase años de su vida sin saber si padece de asma o no lo cual es peligroso ya que algunas medicinas pueden llegar a causar efectos adversos si son tomadas por pacientes que tienen asma.
Por ello es importante considerar maneras de detectar si el paciente tiene asma o no a pesar de no tener el historial médico de los pacientes ya que si se tiene una forma de detectar si puede tener asma o no permite mejorar la experiencia del paciente y facilitar el trabajo del médico al limitar el médicamento y los tratamientos que se le pueden aplicar al paciente.

# Estructura del repositorio
En este repositorio podrá encontrar los siguientes documentos:
 - Datos utilizados para el machine learning.
 - Calendario de trabajo del proyecto.
 - Presentación utilizada para presentar los hallazgos del machine learning.
 - Instrucciones de uso de Jupyternotebook
 - Instrucciones para levantar docker para permitir el uso del programa utilizado.
 - README.md que cumple la función de guía general del proyecto.

# Resultados Principales

El entranamiento que se utilizó para poder hacer un algoritmo predictor de asma se basó en los síntomas principales que se pueden observar en un paciente con asma el cual utilizó los sintomas de cansancio, malestar de garganta, dificultad para respirar, tos seca y congestión nasal como los sintomás que debe de detectar el algoritmo para poder predecir si el paciente puede padecer de asma o no. La idea principal es que si el sistema detecta dichos sintomas, pueda llegar a detectar un patrón matemático que pueda predecir si un paciente presenta asma o no y así reducir los riesgos que podrían afectar a la salud del paciente.
Sin embargo, al realizar las pruebas necesarias para poder generar el algoritmo de predicción de asma se encontró que....{

# Acceso al data set

El algoritmo idealmente debería de ser entrenado con data real de pacientes reales para evitar que la variabilidad del mundo real afecte en el algoritmo y así este ya esté entrenado con datos veridicos y no simulados, sin embargo, debido a la falta de datos como los mencionados previamente, se optó por el uso de datos simulados encontrados en Kaggle los cuales presentan datos de pacientes con y sin asma separados en rangos de edades que entran justamente en los parametros establecidos por el proyecto. 
Estos datos se pueden encontrar dentro de este repositorio, al igual que se pueden encontrar en el siguiente link:
https://www.kaggle.com/datasets/deepayanthakur/asthma-disease-prediction/data

# Set up del entorno

Dentro de este mismo repositorio se puede encontrar un archivo de nombre SETUP_ALH.md en el cual se detalla cada uno de los pasos a seguir para poder abrir y preparar el sistema para poder correr el algoritmo preparado.


# Consideraciones éticas

Debido a que es un sistema que busca predecir enfermedades en pacientes y especialmente en niños, el fin en mente de este algoritmo es que funcione como una herramienta para facilitar el trabajo del médico sin tratar de reemplazar el trabajo de este, ya que siempre se debe de tener el pensamiento crítico de un médico para corroborar los resultados de este.
Por ello, el proposito real de este algoritmo es predecir si un paciente tiene posibilidades de presentar asma o no, y si se detecta que puede llegar a tener asma, que se muestre una alarma para que el médico pueda dar un diagnóstico final.
Por ello, se podría implementar como una extensión que pueda coexistir dentro del HIS del hospital o instalación en la que se está trabajando.

# Presentación de resultados

En el siguiente link se puede observar el link en el que se encuentra la presentación de canva utilizada durante la presentación final del proyecto:
https://canva.link/wbb5cnudmw37smg
