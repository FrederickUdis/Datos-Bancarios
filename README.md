# Datos-Bancarios
es un script de Python diseñado para analizar y modelar datos bancarios, específicamente para predecir la "fuga" de clientes (churn) en un banco. El script utiliza varias bibliotecas de Python, incluyendo pandas, seaborn, matplotlib, scikit-learn y xgboost, y sigue varios pasos clave en el análisis de datos y modelado predictivo:

# Montaje de Google Drive: Se monta Google Drive para acceder a los datos almacenados en él.

# Carga y Exploración de Datos: Se carga un conjunto de datos desde un archivo CSV y se realizan varias operaciones de exploración de datos, como visualizar las primeras filas, imprimir nombres de columnas, y verificar datos nulos.

# Análisis Exploratorio de Datos (EDA): Se realiza un análisis exploratorio, incluyendo la creación de una matriz de correlación, visualización de histogramas y boxplots para diferentes variables, y gráficos de barras para variables categóricas.

# Preprocesamiento de Datos: Se eliminan algunas columnas que no son necesarias para el análisis. Luego, se divide el conjunto de datos en características (X) y etiquetas (y), y se realiza una división en conjuntos de entrenamiento y prueba.

# Transformación de Datos: Se aplica un preprocesamiento a los datos, utilizando StandardScaler para las características numéricas y OneHotEncoder para las categóricas.

# Modelado y Evaluación: Se entrena y evalúa una variedad de modelos de machine learning, incluyendo regresión logística, árboles de decisión, bosques aleatorios, máquinas de soporte vectorial (SVM), XGBoost, y redes neuronales. Cada modelo se evalúa utilizando métricas como precisión, recall, F1-score y matriz de confusión.

# Mejora del Modelo de Redes Neuronales: Se realiza un preprocesamiento adicional específico para mejorar el modelo de redes neuronales, incluyendo codificación one-hot de variables categóricas y escalado de características continuas.

# Evaluación de Diversos Clasificadores: Se entrena y evalúa una serie de clasificadores adicionales, incluyendo KNN y Naive Bayes, utilizando validación cruzada y técnicas de balanceo de clases como SMOTE.
