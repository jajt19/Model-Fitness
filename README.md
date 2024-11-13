# 📊 Estrategia de Retención de Clientes en Model Fitness

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Status](https://img.shields.io/badge/Status-Completado-success)
![Libraries](https://img.shields.io/badge/Libraries-Pandas%2C%20NumPy%2C%20Scikit--learn%2C%20Matplotlib%2C%20Seaborn-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

## 📋 Descripción del Proyecto

Model Fitness es una cadena de gimnasios que enfrenta desafíos en la retención de clientes. Este proyecto tiene como objetivo desarrollar un modelo predictivo para anticipar la cancelación de membresías, identificar los factores clave que influyen en esta decisión y proponer estrategias de retención para mejorar la fidelización de los clientes.

## 🎯 Objetivos del Proyecto

- *Predecir la Pérdida de Clientes*: Desarrollar un modelo de clasificación para identificar clientes con alto riesgo de cancelar su membresía.
- *Segmentación de Clientes*: Analizar y clasificar clientes en grupos basados en características y comportamientos.
- *Factores de Pérdida*: Evaluar qué variables impactan más en la cancelación.
- *Estrategias de Retención*: Proporcionar recomendaciones personalizadas para reducir el churn.

## 🗂️ Descripción de los Datos

El dataset incluye información de 4,000 clientes con las siguientes características:

- *Demografía*: Género, edad, proximidad al gimnasio.
- *Uso y Compras*: Periodo de contrato, meses restantes, frecuencia de visitas, gastos adicionales.
- *Membresías Promocionales*: Promociones y descuentos aplicados.
- *Variable Objetivo*: Churn (1 si canceló, 0 si no canceló).

## 📈 Análisis Exploratorio de Datos (EDA)

- *Frecuencia de Uso*: Los clientes con menor frecuencia de visitas tienen mayor riesgo de cancelar.
- *Duración del Contrato*: Contratos más cortos están correlacionados con una mayor tasa de cancelación.
- *Gastos Adicionales*: Los clientes que invierten menos en servicios adicionales son más propensos a cancelar.
- *Segmento de Edad*: Clientes jóvenes muestran una mayor propensión a la cancelación.

## 📊 Modelos de Clasificación Utilizados

| Modelo                   | Exactitud | F1-Score (Churn) |
|--------------------------|-----------|------------------|
| Regresión Logística      | *91.6%* | *83%*          |
| Árbol de Decisión        | 87.6%     | 75%              |
| Bosque Aleatorio         | 91%       | 81%              |
| Máquinas de Soporte Vectorial (SVM) | 90.8% | 81%      |

🔍 *Conclusión: El modelo de **Regresión Logística* fue seleccionado por su mayor exactitud y balance entre precisión y sensibilidad.

## 💡 Recomendaciones de Retención

- *Aumentar la Frecuencia de Visitas*:
  - Implementar desafíos de asistencia y programas de recompensas.
  - Crear programas de lealtad que motiven a los clientes a visitar el gimnasio con mayor frecuencia.

- *Extender Contratos*:
  - Ofrecer descuentos a clientes que renueven anticipadamente, especialmente en contratos largos.
  - Enviar campañas de marketing dirigidas a clientes con contratos próximos a expirar.

- *Incentivos para Clientes Jóvenes*:
  - Potenciar las promociones "trae a un amigo".
  - Introducir clases temáticas y eventos sociales para atraer al segmento más joven.

- *Incrementar Ingresos por Servicios Adicionales*:
  - Fomentar el cross-selling de productos y servicios adicionales.
  - Ofrecer membresías con beneficios exclusivos para incrementar el compromiso del cliente.

## 🛠️ Tecnologías Utilizadas

![Python](https://img.shields.io/badge/Code-Python-blue)
- *Lenguaje*: Python 3.8+
- *Librerías*: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## 🚀 Cómo Ejecutar el Proyecto

1. *Clonar el Repositorio*:
   
bash
   git clone https://github.com/usuario/model-fit
