📡 Telecom X: Predicción de Churn y Retención de Clientes

Este proyecto aplica técnicas de Ciencia de Datos y Machine Learning para identificar factores críticos que influyen en la cancelación de clientes (Churn) en una empresa de telecomunicaciones, proponiendo estrategias basadas en evidencia para mejorar la retención.

📋 Resumen del Proyecto

El objetivo principal fue construir un modelo predictivo capaz de clasificar a los clientes con alta probabilidad de fuga. Se realizó un análisis exhaustivo desde la limpieza de datos hasta la evaluación de modelos de clasificación.

🛠️ Tecnologías Utilizadas
Lenguaje: Python

Bibliotecas: Pandas, Scikit-learn, Seaborn (Paleta Magma), Matplotlib

Modelado: Regresión Logística y Random Forest

📊 Hallazgos Clave (Insights)
Tras el Análisis Exploratorio de Datos (EDA) y el estudio de importancia de variables, se determinó:

Factor de Riesgo: Los clientes con servicios de Fibra Óptica y métodos de pago manuales (Electronic Check) presentan la mayor tasa de cancelación.

Factor de Lealtad: La antigüedad (tenure) y los contratos a largo plazo (1 y 2 años) son los predictores más fuertes de permanencia.

🤖 Rendimiento del Modelo
Se seleccionó la Regresión Logística como el modelo final debido a su estabilidad y capacidad de generalización:

Exactitud (Accuracy): 79.2%

AUC (Curva ROC): 0.84

Recall: 52% (Capacidad para detectar fugas reales)

💡 Estrategias de Retención Propuestas
Fidelización Temprana: Implementar campañas de seguimiento para clientes de fibra óptica durante sus primeros 6 meses.

Incentivos de Pago: Promover la migración a métodos de pago automáticos para reducir la fricción mensual.

Conversión de Contratos: Ofrecer beneficios exclusivos para clientes que migren de planes mensuales a contratos anuales.



Autor : Julian Andres Preciado 
Fecha : Marzo del 2026 
Cliente : Telecom X ( ALURA LATAM) 
