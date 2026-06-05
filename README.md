# Air Quality AI Predictor
La calidad del aire es un factor clave para la salud pública y el bienestar de la población.
En los últimos años, el aumento de la contaminación en entornos urbanos ha
impulsado el desarrollo de sistemas capaces de monitorizar y predecir la evolución de
los niveles de contaminación atmosférica.

En este contexto, el presente proyecto tiene como objetivo el desarrollo de un sistema
de predicción de la calidad del aire urbano utilizando técnicas de Machine Learning.
Para ello, se integran datos meteorológicos y de contaminantes obtenidos mediante
APIs externas, permitiendo estimar el índice de calidad del aire (AQI) a corto plazo.

Además del modelo predictivo, se ha implementado una arquitectura completa que
simula un entorno real de producción, compuesta por:
- **Un modelo de predicción basado en XGBoost**.
- **Una API REST desarrollada con FastAPI**.
- **Un dashboard interactivo mediante Streamlit**.
- **Un sistema de alertas basado en niveles de AQI**.

Este enfoque permite no solo obtener predicciones precisas, sino también visualizar los
resultados y facilitar su interpretación por parte de los usuarios.
