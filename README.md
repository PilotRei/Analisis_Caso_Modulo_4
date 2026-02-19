# Analisis_Caso_Modulo_4
Comprender el propósito del EDA y diferenciarlo del análisis inicial.

Informe de Análisis de Datos: Proyecto ComercioYA 

Contexto del Proyecto: Este proyecto presenta un Análisis Exploratorio de Datos (EDA) y un desarrollo de Modelos Predictivos para la plataforma de e-commerce ComercioYA. 

El objetivo central fue entender la relación entre el comportamiento de los usuarios (visitas) y el rendimiento económico (gasto), permitiendo así optimizar la toma de decisiones estratégicas basadas en evidencia.

Metodología y Pasos:
Para garantizar la calidad y veracidad del informe, el trabajo se estructuró en las siguientes fases técnicas:
a) Limpieza y Normalización: Se procesó el dataset original para corregir tipos de datos, manejar valores nulos y asegurar que columnas críticas (como fechas y montos) fueran aptas para el cálculo matemático.
b) Identificación de Anomalías: Detectamos la presencia de un outlier significativo: un cliente con un volumen de 100 visitas y un gasto de $5000.
c) Análisis de Sensibilidad (Contraste de Modelos): Esta fue la etapa más importante. 
   Realizamos cálculos y visualizaciones en dos escenarios:
   - Con Outlier: El modelo inicial mostraba una correlación de 0.97, pero estaba fuertemente sesgado por el dato atípico.
   -  Sin Outlier (Modelo Refinado): Al filtrar este dato, obtuvimos una visión mucho más realista del comportamiento del 95% de los clientes, lo que permitió generar proyecciones de gasto más seguras y honestas para la empresa.
d) Visualización Estratégica: Utilizamos librerías como Seaborn y Matplotlib para crear una narrativa visual a través de Heatmaps, Pairplots y un tablero final de control con histogramas y gráficos de dispersión anotados.

Conclusiones:
a) Validación del Motor de Ventas: Se confirmó que las visitas mensuales son el principal motor del gasto, con una significancia estadística sólida ($p < 0.05$).
b) Impacto de la Limpieza de Datos: El contraste entre los modelos demostró que confiar en datos sin filtrar puede llevar a sobreestimar los ingresos. El Modelo Refinado es la herramienta recomendada para la planificación presupuestaria.
c) Experiencia del Usuario: El análisis cruzado reveló que las bajas calificaciones en reseñas suelen estar vinculadas a procesos de devolución, señalando un área de oportunidad para mejorar la retención de clientes.
