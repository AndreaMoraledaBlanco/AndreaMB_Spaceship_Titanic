# 🛸 **Spaceship Titanic Survival Prediction** 🚀

![Spaceship Titanic](https://www.kaggle.com/static/images/site-logo.png)

Este repositorio contiene mi solución al desafío de Kaggle [**Spaceship Titanic**](https://www.kaggle.com/competitions/spaceship-titanic), donde se predice si los pasajeros de una nave espacial serán transportados a otra dimensión.

## 📁 **Descripción del proyecto**

El objetivo del proyecto es predecir si un pasajero fue transportado en función de varios factores, como su edad, costo de servicios y otras características. Para lograrlo, utilicé técnicas de **Machine Learning** y optimización de hiperparámetros con las siguientes herramientas:

- **Random Forest** para el modelado predictivo.
- **Optuna** para la optimización de hiperparámetros.
- **Pandas** para el manejo y análisis de datos.
- **Scikit-learn** para la implementación del modelo y las métricas de evaluación.

## 📊 **Estructura del proyecto**

```
├── datasets/                   # Datos utilizados (entrenamiento y prueba)
├── notebooks/                  # Jupyter Notebooks con el análisis y modelos
├── src/                        # Código fuente
│   ├── data_preprocessing.py   # Scripts de preprocesamiento de datos
│   ├── model_training.py       # Entrenamiento del modelo Random Forest
│   └── hyperparameter_tuning.py# Optimización con Optuna
└── README.md                   # Documentación del proyecto
```

## 🔧 **Tecnologías Utilizadas**

- **Python 3.8+**
- **Pandas**: Para manipulación y análisis de datos.
- **Scikit-learn**: Para construir y evaluar el modelo de **Random Forest**.
- **Optuna**: Para la optimización de los hiperparámetros del modelo.
- **Matplotlib y Seaborn**: Para la visualización de datos.

## 🚀 **Cómo ejecutar el proyecto**

1. Clona el repositorio:
   ```bash
   git clone https://github.com/AndreaMoraledaBlanco/AndreaMB_Spaceship_Titanic.git
   ```

2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

3. Descarga el conjunto de datos desde [Kaggle](https://www.kaggle.com/competitions/spaceship-titanic/data) y colócalo en la carpeta `datasets/`.

4. Ejecuta el preprocesamiento de datos:
   ```bash
   python src/data_preprocessing.py
   ```

5. Entrena el modelo:
   ```bash
   python src/model_training.py
   ```

6. Ejecuta la optimización de hiperparámetros (opcional):
   ```bash
   python src/hyperparameter_tuning.py
   ```

## 🎯 **Resultados**

El modelo entrenado con **Random Forest** ha sido evaluado utilizando el conjunto de prueba y ha alcanzado un buen rendimiento en términos de precisión y capacidad de generalización. Además, **Optuna** ha ayudado a ajustar los hiperparámetros, mejorando significativamente el desempeño del modelo.
Probamos otros algoritmos como XGBoost y Logistic Regression, pero los resultados obtenidos tuvieron peor rendimiento.

## 📈 **Próximos pasos**

- Probar otros algoritmos de clasificación, como **LightGBM**.
- Implementar técnicas más avanzadas de **Feature Engineering**.
- Visualizar la importancia de las características para entender mejor el impacto de cada variable.
