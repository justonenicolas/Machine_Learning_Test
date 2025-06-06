# 🎯 Modelo Predictivo para medir la deserción de usuarios en un gimnasio
Este proyecto está dedicado a entrenar y comparar una serie de modelos de aprendizaje supervisado cuyo principal objetivo es determinar la tasa de cancelación de los usuarios de un gimnasio y de esta manera establecer las características más importantes sobre las cuales pueda tomar decisiones el equipo de marketing para aumentar la retención mediante sus campañas. Adicionalmente, se desarrolló un segundo modelo de aprendizaje no supervisado utilizado para obtener una serie de grupos clasificados con los cuales se pudieran segmentar de manera más efectiva las campañas

![Regressor](https://github.com/justonenicolas/Machine_Learning_Test/blob/main/LogisticRegressor.png)
![Characteristics](https://github.com/justonenicolas/Machine_Learning_Test/blob/main/ML%20Characteristics.png)

## 💡 Habilidades destacadas
* Análisis preparatorio de datos
* Análisis estadístico de datos
* Modelos de aprendizaje supervisado

## 🔧 Herramientas y librerías utilizadas
* Pandas
* ScikitLearn
* Scipy
* Seaborn

## 📊 Conclusiones generales
* Con base en el análisis, se recomienda evaluar el aumento de convenios y promociones, puesto que se evidencia una mayor tendencia a permanecer si el usuario cuenta con alguno de estos beneficios
* La edad y tiempo de actividad del usuario se consideran 2 de las caracteristicas más importantes para los modelos de predicción, por lo que se considera importante el poder desarrollar campañas de marketing enfocadas en los diferentes rangos que componen estas categorías, de manera que se pueda maximizar el interés de los usuarios con base en sus caracteristicas particulares
* Relacionado con lo anterior, los resultados del agrupamiento (clustering) reflejaron que aunque la edad puede ser un factor importante, el más relevante de todos continúa siendo el tiempo de actividad (lifetime), el cual se puede comenzar a analizar en etapas tempranas a partir del periodo de contrato solicitado por el usuario (contract_period)
* En general se considera importante desarrollar estrategias que incentiven la participación en clases grupales, bien sea a través de llamar la atención de la audiencia o de diseñar estos espacios con base en las preferencias de los distintos segmentos que asisten al gimnasio
* Dado que el volumen de gastos adicionales dentro del gimnasio está bastante asociado con el nivel de fidelidad de los usuarios, se recomienda evaluar estrategias que comiencen a captar la atención de aquellos usuarios propensos a abandonar, con el objetivo de generar en ellos una sensación de valor agregado que pueda contribuir a su posible fidelización
