
# ▶️ **Pasos para ejecutar el sistema mejorado**

## Crear Entorno Virtual
python -m venv venv
venv\Scripts\activate


## Instalar Librerias
pip install pandas numpy scikit-learn joblib streamlit plotly


## Ejecutar Proyecto
1. **Genera el nuevo dataset**  
   `python 1.Crear_Dataset.py`

2. **Entrena el modelo ampliado**  
   `python 2.Entrenar_modelo.py`

3. **Lanza la nueva app**  
   `streamlit run 3.Predecir_enfermedad.py` (nombra el archivo como quieras)
