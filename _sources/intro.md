# Predicción del Caudal del Río Misisipi: Evaluación de Modelos y Validación de Resultados

El análisis y modelación de los sistemas hídricos es crucial para la gestión sostenible de los recursos hídricos y la mitigación de impactos asociados al cambio climático y las actividades antrópicas. El río Misisipi, el segundo más largo de Estados Unidos, desempeña un papel fundamental en la economía, el transporte y el ecosistema de ese país. Sin embargo, su dinámica hidrológica se ha visto afectada por diversos factores, como el cambio climático y las modificaciones antrópicas en su cuenca, lo que subraya la necesidad de mejorar los métodos de modelación y predicción de su caudal.

Este estudio presenta un análisis de la modelación y predicción del caudal del río Misisipi en Thebes, Illinois, utilizando datos históricos proporcionados por el United States Geological Survey (USGS) en el periodo 1995-2025. La base de datos utilizada en este trabajo está disponible en el siguiente enlace: https://bit.ly/4kU2AVR.

Se aplicaron técnicas de análisis exploratorio de datos (EDA) para identificar patrones y tendencias en la serie temporal del caudal, evaluando su estacionariedad y aplicando transformaciones para estabilizar la varianza y reducir la autocorrelación. Para la predicción, se compararon modelos clásicos de series temporales, como Suavizado Exponencial (ES), ARIMA y GARCH, con enfoques más avanzados de aprendizaje profundo, incluyendo Redes Neuronales Recurrentes (RNN) y un modelo híbrido original basado en Generative Adversarial Networks (CGAN) y Bidirectional Long Short-Term Memory (Bi-LSTM).

Los resultados muestran que los modelos tradicionales presentan limitaciones al capturar dinámicas no lineales y variaciones a largo plazo. En contraste, el modelo híbrido CGAN-Bi-LSTM superó ampliamente a los demás en términos de ajuste y precisión, proporcionando una herramienta más robusta para la predicción del caudal. Estos hallazgos resaltan la importancia de combinar métodos estadísticos y computacionales para mejorar la precisión predictiva y optimizar la toma de decisiones en la gestión del agua.

Palabras clave: caudal, modelado hidrológico, series de tiempo, ARIMA, Holt-Winters, GARCH, RNN, CGAN-Bi-LSTM, predicción, Río Misisipi.



```{tableofcontents}
```
