![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

# **Estudio de atención en salud para un hospital**

## **Introducción**

¡Bienvenidos a mi proyecto integrador! El proyecto aborda habilidades en el campo del aprendizaje automático. Tambien entender la problemática y comprender los datos, realizar el análisis exploratorio de datos, preparar los datos, para luego experimentar con los modelos de machine learning. Finalmente, se usan las métricas correspondientes para medir el performance de los modelos y seleccionar el mejor. 

Este proyecto constará de tres fases: `Análisis exploratorio de datos`, `Preparación de datos` y `Modelamiento y evaluación`.

### 1. Análisis exploratorio de datos

Machine Learning en Medicina: Al aplicar Machine Learning en Medicina, se pueden usar las herramientas informáticas con el fin de conseguir información a partir de los datos, por ejemplo, de historias clínicas o registros de prestadores de servicios de salud. De esta manera, se pueden emitir diagnósticos predictivos, evaluar la efectividad de estrategias de intervención y anticipar comportamientos en escenarios relacionados con la atención.

## **Planteamiento de la problemática**

El proyecto se trata del estudio de atención en salud para un hospital. **El cliente desea saber las características más importantes que tienen los pacientes de cierto tipo de enfermedad que terminan en hospitalización.** Fue definido como caso aquel paciente que fue sometido a biopsia prostática y que en un periodo máximo de 30 días posteriores al procedimiento presentó fiebre, infección urinaria o sepsis; requiriendo manejo médico ambulatorio u hospitalizado para la resolución de la complicación y como control al paciente que fue sometido a biopsia prostática y que no presentó complicaciones infecciosas en el período de 30 días posteriores al procedimiento. La base de datos posee algunos datos referentes a los pacientes y resultados de exámenes diagnósticos, de pacientes hospitalizados y no hospitalizados, nos han entregado esta información.  

Para ello, el departamento de datos ha recopilado `Antecedentes del paciente`, `Morbilidad asociada al paciente` y `Antecedentes relacionados con la toma de la biopsia`y `Complicaciones infecciosas`. En la siguiente tabla, se encuentra un diccionario de datos asociado:

![image](https://user-images.githubusercontent.com/118769777/220240501-8c21461d-2de5-495b-954e-10fb9bf38014.png)

El departamente de datos advierte que hay algunos problemas de calidad de datos en la información suministrada por lo que el primer reto es realizar un análisis exploratorio de los datos con el fin de transformar y preparar las datos adecuadamente. 


## **Objetivo**

Implementar y evaluar modelos de aprendizaje automatico para saber las características más importantes que tienen los pacientes de cierto tipo de enfermedad que terminan en hospitalización y crear un modelo predictivo de clasificación para la variable objetivo: Hospitalización.
