# Detección de Anomalías en Tráfico Web con Isolation Forest

Este proyecto implementa un sistema de detección de anomalías en tráfico web utilizando el algoritmo Isolation Forest. El objetivo es identificar patrones anómalos en los datos de tráfico web y enviar alertas automáticas cuando se detecten posibles amenazas cibernéticas.

## Contenido

- [Introducción](#introducción)
- [Objetivos](#objetivos)
- [Metodología](#metodología)


## Introducción

En el panorama actual de la ciberseguridad, las amenazas cibernéticas evolucionan constantemente, presentando desafíos cada vez más sofisticados para la protección de los sistemas de información. La detección proactiva de estas amenazas se ha vuelto crucial para las organizaciones, ya que permite anticipar y mitigar posibles riesgos antes de que se materialicen en incidentes graves.

## Objetivos

- Detectar patrones anómalos en el tráfico web.
- Enviar alertas automáticas a los administradores de seguridad.
- Mejorar la capacidad de respuesta ante amenazas cibernéticas.

## Metodología

1. **Carga y Preprocesamiento de Datos:**
   - Transformación de logs en un dataset estructurado.
   - Codificación de variables categóricas.
   - Normalización de datos.

2. **Entrenamiento del Modelo:**
   - Uso del algoritmo Isolation Forest con las siguientes variables:
     - Real Agent ID
     - Entity GUID
     - Container ID
     - External Call Count
     - Host
     - Timestamp
     - Request.URI
     - Request.Method

3. **Detección de Anomalías:**
   - Predicción de anomalías en los datos de tráfico web.
   - Filtrado y análisis de resultados.

4. **Alertas Automáticas:**
   - Envío de alertas por correo electrónico cuando se detectan anomalías.
   - Almacenamiento de resultados en un archivo CSV.

