# Capstone-Project
In this paper, we will focus on addressing the challenge of customer retention through data analysis and the development of predictive models. We will explore different techniques and approaches, evaluate their effectiveness, and discuss their application in a business context. To overcome these challenges, Big Data tools are used, such as Apache Spark, which has become a popular and trusted choice in the field of large-scale data processing and analysis. Apache Spark is known for its ability to handle large volumes of data and its exceptional processing speed in distributed environments.

# Project Motivation
Many companies have adopted business models based on monthly or annual subscriptions instead of one-time fees. However, this transition has introduced the challenge of retaining customers and avoiding the loss of subscriptions. The ability to predict and detect customer churn before it occurs has become critical for businesses that want to keep their customers paying.

# Libraries used:
- pySpark
- Pandas
- Seaborn
- Numpy
- Matplotlib

# File Description
- user_dataset_definitive.CSV: Copied Data defined and extracted for the machine learning stage in CSV
- mini_sparkify_event_data.json: only 128 MB portion of the original data set (It is not related in this repository but it is in the Udacity workspace)
- Sparkify.ipynb: The main coding file in jupyter notebook format developed in Udacity workspace, where you can identify the step by step of the CRISP methodology applied in this project.
  
# Summary of Analysis Results
Data exploration in this machine learning models project is a crucial stage that involves understanding and analyzing the available data before building and training the models. Obtain relevant information, identify patterns, understand the distribution of the data and detect possible problems or peculiarities that may affect the performance of the model.
An initial exploratory analysis was performed to obtain an overview of the data. This involves reviewing the structure of the data, examining the type of variables (numeric, categorical, etc.), identifying relevant columns, checking for missing or duplicate data, and determining the overall quality of the data.
Data visualization techniques are used to graphically represent different aspects of the data, for example, we determine the number of users who are active and those who canceled the subscription, then we group by user gender, then we add the component if the subscription is paid or the free one and later we determine from the set of active and canceled data what activity you have within 'Sparkify'.
En general, se busca un alto valor de accuracy para tener un modelo preciso en general. Sin embargo, en casos de desequilibrio de clases, es importante considerar precision, recall y F1-score para evaluar cómo el modelo maneja correctamente las instancias positivas y negativas, teniendo en cuenta todo lo anterior y los resultados obtenidos el modelo que mejor medidas tiene es el clasificador de Arboles Potenciados por Gradiente (GBT). 
Una oportunidad para profundizar en el proyecto es el ajuste y optimización de los modelos, por ejemplo, para la Regresión Logística puede implicar la búsqueda de los mejores hiperparámetros mediante técnicas como la validación cruzada o la búsqueda en cuadrícula. Para el modelo de árbol de decisión puede incluir la limitación de la profundidad del árbol, la configuración de los criterios de división y la poda del árbol para evitar el sobreajuste. Para el modelo GBT esto puede implicar la selección de hiperparámetros como la profundidad máxima de los árboles, el número de árboles en el conjunto y la tasa de aprendizaje, también se puede aplicar la técnica de regularización para evitar el sobreajuste y para el modelo de bosque aleatorio esto puede implicar la selección de hiperparámetros como el número de árboles en el bosque, la profundidad máxima de los árboles y el número de características consideradas en cada división del árbol.

# Acknowledgements
https://stackoverflow.com/questions/tagged/capstone?tab=Votes
https://www.kaggle.com/discussions/general/185307
Please refer to: https://medium.com/@fabian.perez.arevalo/dont-let-the-music-stop-at-sparkify-ff51dd9db3e5
