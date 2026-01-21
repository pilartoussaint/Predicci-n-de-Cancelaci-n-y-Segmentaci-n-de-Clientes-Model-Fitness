# Predicci-n-de-Cancelaci-n-y-Segmentaci-n-de-Clientes-Model-Fitness
Proyecto de Machine Learning | Clasificación Binaria y Clustering K-Means

##🏋️ Contexto del Proyecto
La cadena de gimnasios Model Fitness busca combatir la tasa de cancelación (churn) mediante una estrategia basada en datos. El objetivo principal es analizar los perfiles de los clientes, predecir la probabilidad de pérdida para el próximo mes y segmentar a los usuarios para diseñar campañas de retención personalizadas.

##📊 Objetivos Estratégicos
Predicción de Churn: Implementación de modelos de Regresión Logística y Random Forest para identificar usuarios en riesgo de abandono.

Perfilamiento de Usuarios: Creación de grupos (clústeres) basados en el comportamiento de uso y características demográficas.

Factores de Impacto: Identificación de variables críticas (como el tiempo de vida del cliente y frecuencia de visitas) que influyen en la lealtad.

##🛠️ Stack Tecnológico
Lenguaje: Python.

Librerías de ML: Scikit-learn (Logistic Regression, Random Forest, K-Means).

Análisis de Datos: Pandas, Numpy.

Visualización: Matplotlib, Seaborn (Dendrogramas y Mapas de Calor).

##📈 Hallazgos Clave
Segmentación: Se identificaron 5 clústeres de clientes diferenciados por su tasa de cancelación y frecuencia de asistencia.

Indicadores de Riesgo: Los clientes con contratos de corta duración (1 mes) y baja frecuencia de visitas semanales en el último mes presentan el mayor riesgo de abandono.

Efecto Comunidad: Los usuarios que participan en sesiones grupales y se inscribieron mediante promociones de amigos muestran una lealtad significativamente mayor.

##🚀 Recomendaciones Propuestas
Fomento de la Comunidad: Incentivar la participación en clases grupales para los clústeres con mayor riesgo.

Conversión de Contratos: Estrategias de marketing para migrar a usuarios de contratos mensuales a planes semestrales o anuales.

Monitoreo Predictivo: Utilizar el modelo desarrollado para lanzar alertas tempranas cuando la frecuencia de asistencia de un cliente disminuya.
