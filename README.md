#  Proyecto MLOps - Predicción de Accidentes en Minería

Este repositorio documenta el desarrollo de un modelo de **Machine Learning** para predecir la ocurrencia de accidentes en la industria minera, implementando las mejores prácticas de **MLOps** en **Databricks** con **Azure**.

## 📌 Estructura del Proyecto

El proyecto está organizado en notebooks de **Databricks**, cada uno representando una fase clave del pipeline **MLOps**:

1. **01_Ingesta_y_Almacenamiento**  
   - Carga y almacenamiento de datos en **Delta Lake** usando **Unity Catalog**.
2. **02_EDA_Mining_Data**  
   - Análisis exploratorio de datos (**EDA**) para detectar patrones y tendencias.
3. **03_Modelado_Mining_Data**  
   - Entrenamiento de un **Random Forest** en **PySpark MLlib**.  
   - Registro del modelo en **MLflow Model Registry**.
4. **04_Despliegue_Modelo**  
   - Implementación del modelo en **Databricks Serving** como una API REST.
5. **05_Prueba_API_Accident_Prediction**  
   - Pruebas del endpoint de la API con solicitudes POST en **Python**.
6. **06_Monitoreo_Producción**  
   - Evaluación de métricas en producción con **MLflow**.  
   - Validación del rendimiento del modelo.
---

## ⚙️ **Tecnologías Utilizadas**
✅ **Databricks**  
✅ **MLflow** para experimentación y gestión del modelo  
✅ **PySpark MLlib** para entrenamiento y evaluación  
✅ **Unity Catalog** para gobernanza de datos  
✅ **Delta Lake** para almacenamiento eficiente  
✅ **Azure Databricks Serving** para el despliegue como API REST  

---

##  **Ejecución del Proyecto en Databricks**
Para correr este pipeline en **Databricks**, sigue estos pasos:

1️⃣ **Configura un cluster** con **PySpark 3.5+** y habilita MLflow.  
2️⃣ **Carga los notebooks** en Databricks y ejecuta en orden.  
3️⃣ **Revisa el API Endpoint** desde **05_Prueba_API_Accident_Prediction**.  



