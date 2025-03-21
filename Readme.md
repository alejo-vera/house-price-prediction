# House Price Prediction

Este repositorio contiene un proyecto de predicción de precios de casas utilizando Python y Jupyter Notebook. El análisis y el modelo se encuentran en el archivo `.ipynb`.

## Contenido

- `house-price-prediction.ipynb`: Contiene el análisis exploratorio de datos, la preparación de datos y el modelo de predicción.
- `data/`: Carpeta donde se almacenan los datos utilizados en el proyecto.
- `requirements.txt`: Lista de dependencias necesarias para ejecutar el proyecto.

## Explicación
En este notebook tratamos una base de kaggle sobre el mercado inmobiliario. En este realizaremos los siguientes pasos:
* Análsis Exploratorio de Datos (EDA) para comprender en profundidad con qué estamos tratando
* Limpieza de Datos
* Técnicas de Imputación, escalamiento y recorte de Outliers
* Progresión de modelos de ML simples a más complejos para predecir nuestra variable a determinar: "Precio"
* Evaluación y Scoring de nuestro modelo con distintas técnicas.
Siempre todo en un modelo iterativo, donde al hacer el modelo y análisis de residuales volvemos a la limpieza y tranformación de los datos varias veces.

## Requisitos

1. Python 3.8 o superior.
2. Instalar las dependencias ejecutando:

    ```bash
    pip install -r requirements.txt
    ```

## Uso

1. Clona este repositorio:

    ```bash
    git clone https://github.com/tu-usuario/house-price-prediction.git
    cd house-price-prediction
    ```

2. Abre el archivo `.ipynb` en Jupyter Notebook o JupyterLab:

    ```bash
    jupyter notebook notebook.ipynb
    ```

3. Sigue las instrucciones en el notebook para ejecutar el análisis y el modelo.
