# 🟡 Predicción de Recuperación de Oro - Planta Zyfra
Modelos de regresión y análisis industrial con Python

## 📌 Introducción
Zyfra, una empresa del sector minero, busca mejorar el control y la eficiencia del proceso de recuperación de oro. Para ello, se dispone de datos de sensores sobre el flujo de entrada, salida y procesos intermedios en la planta.

Este proyecto se enfoca en predecir dos indicadores clave:
- `rougher.output.recovery` (recuperación intermedia)
- `final.output.recovery` (recuperación final de oro)

## 🎯 Problema de negocio
El proceso de extracción y purificación del oro es complejo. Las decisiones basadas en datos permiten ajustar parámetros del sistema y optimizar el rendimiento, reduciendo pérdidas y aumentando la eficiencia.

## 🔍 Objetivos del proyecto
✔ Limpiar y preparar datos industriales  
✔ Validar la consistencia físico-química del proceso  
✔ Aplicar modelos de regresión para predecir recuperación  
✔ Evaluar el desempeño del modelo con la métrica sMAPE  
✔ Comparar contra un modelo base (dummy)

## ❓ Preguntas clave
- ¿Qué parámetros influyen más en la recuperación de oro?  
- ¿Se pueden identificar valores atípicos o inconsistentes?  
- ¿Qué modelo ofrece las predicciones más precisas?  

## 📊 Métricas clave
- **sMAPE**: Error porcentual simétrico medio  
- Comparación entre recuperación real y estimada  
- Validación cruzada con métricas separadas para rougher y final  

## 🗂 Descripción del conjunto de datos
📁 Archivos:
- `gold_recovery_full.csv`: fuente completa de datos
- `gold_recovery_train.csv`: datos de entrenamiento
- `gold_recovery_test.csv`: datos de prueba

Columnas clave:
- Variables de entrada: concentración, cantidad, tamaño de partículas  
- Variables de salida: `rougher.output.recovery`, `final.output.recovery`  

## ⚙️ Proceso de análisis
📌 Herramientas: Python, Pandas, NumPy, Scikit-Learn, Matplotlib

### Paso 1: Carga y limpieza
✔ Manejo de valores nulos  
✔ Coincidencia entre datasets  
✔ Conversión de tipos y formatos

### Paso 2: Exploración y consistencia
✔ Revisión físico-química de concentraciones  
✔ Visualización de distribución y correlaciones

### Paso 3: Modelado
✔ Entrenamiento de RandomForestRegressor  
✔ Validación cruzada con scoring sMAPE  
✔ Comparación contra modelo dummy

## 📁 Estructura del repositorio
📂 data  
 └── gold_recovery_full.csv  
 └── gold_recovery_train.csv  
 └── gold_recovery_test.csv  

📂 notebooks  
 └── Proyecto_Zyfra_FINAL.ipynb  

📂 insights  
 └── resumen.md  

## 📬 Contacto
📧 Correo: jessica.elizondo.t@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/jessica-elizondo-t
