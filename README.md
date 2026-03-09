📊 Telecom X – Análisis de Evasión de Clientes (Churn)
📌 Descripción

Este proyecto analiza la evasión de clientes (Churn) en una empresa ficticia de telecomunicaciones llamada Telecom X.
El objetivo es aplicar el proceso ETL (Extract, Transform, Load) utilizando Python, extrayendo datos desde una API en formato JSON, limpiándolos, transformándolos y preparándolos para realizar análisis exploratorio de datos (EDA).

El análisis permite identificar patrones que pueden explicar por qué los clientes cancelan sus servicios, información que posteriormente puede utilizarse para construir modelos predictivos de churn.

🎯 Objetivos del Proyecto

Extraer datos desde una API en formato JSON
Limpiar y transformar los datos utilizando Pandas
Estructurar los datos para análisis exploratorio
Analizar variables relacionadas con la evasión de clientes
Generar visualizaciones que ayuden a entender el comportamiento de los clientes

📂 Dataset

Los datos contienen información sobre clientes de Telecom X, incluyendo:

Información demográfica
Tipo de contrato
Servicios contratados
Métodos de pago
Costos mensuales y totales
Estado de cancelación del cliente
Algunas variables importantes del dataset incluyen:
customerID → Identificador único del cliente
Churn → Indica si el cliente canceló el servicio
tenure → Meses que el cliente ha permanecido en la empresa
Contract → Tipo de contrato
PaymentMethod → Método de pago

Charges.Monthly → Cargo mensual del servicio

Charges.Total → Total gastado por el cliente

Según el diccionario de datos del proyecto

TelecomX_diccionario

.

🧰 Tecnologías Utilizadas

Python
Pandas
Matplotlib
JSON
Jupyter Notebook / Google Colab
Git y GitHub


📁 Estructura del Proyecto
TelecomX-Churn-Analysis/
│
├── TelecomX_Data.json
├── TelecomX_diccionario.md
├── TelecomX_LATAM.ipynb
├── README.md
📈 Resultados Esperados

El análisis permitirá:
Identificar patrones de comportamiento de clientes
Detectar variables relacionadas con el Churn
Preparar los datos para futuros modelos de Machine Learning


📚 Contexto del Proyecto

Este desafío forma parte del programa Oracle Next Education (ONE) en colaboración con Alura Latam, donde se desarrollan habilidades en:

ETL
Análisis de datos
Ciencia de datos
Python para Data Science


👨‍💻 Autor

José Carlos Castillo Villa
Data Analyst en formación
Python | Pandas | ETL | Data Analysis
