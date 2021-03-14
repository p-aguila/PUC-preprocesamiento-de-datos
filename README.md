# PUC-preprocesamiento-de-datos
Foro 1 del curso Modelamiento Estadístico y Sistemas Recomendadores

I. Considere los datos ‘hours_peer_week.csv’, que contiene las horas que trabaja un grupo de trabajadores de EE.UU. a la semana.
  1) Cargue el conjunto de datos en la sesión de trabajo de R usando la función read.table.
  2) Calcule en forma manual el puntaje Z para las horas de trabajo semanal.
  3) Construya un histograma de los datos originales y los datos estandarizados. Describa las características principales de los datos, comentando en el foro sobre la simetría y uni- o multi-modalidad de la distribución de los datos.
  4) Construya un boxplot de los datos originales y los datos estandarizados. Comente sus resultados en el foro. ¿Existe evidencia de la presencia de “outliers”? Justifique su respuesta en el foro.
  5) Repita los pasos 3) y 4) usando la función scale.

II. Considere los datos ‘titanic.csv’, sobre la tragedia del Titanic, cuya descripción se muestra en la siguiente tabla.
| **Variable**|**Descripción** |
|:--|:------------|
|passengerId|Identificador de pasajero|
|Survived|Variable que indica 1 si el pasajero sobrevivió y 0 si no.|
|Pclass|Clase del pasajero (1=primera clase, 2=segunda clase, 3=tercera clase)|
|Name|Nombre del pasajero|
|Sex|Género del pasajero|
|Age|Edad del pasajero|
|Sibsp|Número de hermanos o cónyuges a bordo|
|Parch|Número de padres o hermanos a bordo|
|Ticket|Número de ticket|
|Fare|Precio del ticket (en moneda local)|
|embarked|Puerto de embarque (C = Cherbourg; Q = Queenstown; S = Southampton)|
  
Realice las siguientes actividades:
  1) Cargue el conjunto de datos en la sesión de trabajo de R usando la función read.table.
  2) Usando la función summary(), obtenga estadísticos descriptivos de las variables y discuta los resultados en el foro.
  3) Cree una variable que indique el tamaño total de la familia del pasajero (incluyéndose él mismo).
  4) Grafique la relación entre la tasa de sobrevivientes y el tamaño de la familia.
  5) En base a lo observado en el punto anterior, proponga e implemente la discretización del tamaño de la familia. Justifique su decisión en el foro.
  6) Identifique los pasajeros con datos faltantes para la variable embarked y age usando la función is.na(). ¿Qué tipo de mecanismo de generación de datos faltantes podría ser válido en cada caso? Justifique su respuesta en el foro.
  7) Genere un conjunto de datos completos al imputar los valores faltantes de la variable embarked por la del puerto “C” y los valores faltantes de la variable edad por el promedio de edad de los datos observados.
