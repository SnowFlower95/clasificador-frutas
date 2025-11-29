# CC235 – Trabajo Final 2025-1  
## Clasificación de frutas mediante imágenes para aplicaciones agrícolas automatizadas

### Objetivo del trabajo
Desarrollar un sistema de clasificación automática de frutas a partir de imágenes, utilizando redes neuronales convolucionales y transfer learning (MobileNetV3).  
El objetivo es comparar el rendimiento del modelo sobre un dataset de frutas y construir una interfaz sencilla para que un usuario final pueda cargar una imagen y obtener la predicción.

### Integrantes
- Huamán Cortez, Anabella Karina (U202216171)
- Montenegro López, Valentina Étoile (U202312021)

### Descripción del dataset
- **Fuente:** Fruits-360 (Kaggle), puede ser descargada mediante el siguiente enlace: https://www.kaggle.com/moltean/fruits
- **Número de clases:** 225  
- **Formato:** imágenes RGB, resolución de 100×100 px.  

### Programas en Python
- Carpeta `code/`
  - `TF_grupo4_CNN_.ipynb`: notebook con el preprocesamiento, entrenamiento, evaluación y métricas del modelo.
  - `app.py`: aplicación en Streamlit que carga el modelo entrenado y permite clasificar las imagenes.
  - `modelo_frutas.keras`: modelo final entrenado que se utiliza en la aplicación.

### Conclusiones
- El modelo alcanzó una **accuracy de 84.81 %** sobre el conjunto de prueba.
- El uso de **transfer learning con MobileNetV3** permitió entrenar un modelo con buen desempeño en un tiempo de entrenamiento razonable.
- La interfaz en **Streamlit** facilita que un usuario pueda probar el modelo subiendo imágenes.


### Licencia

El código de este repositorio se distribuye bajo la licencia MIT.  
Para más detalles, revisar el archivo `LICENSE` incluido en el repositorio.

El dataset Fruits-360 es propiedad de sus autores originales y se utiliza únicamente con fines académicos, según las condiciones indicadas en su fuente oficial.
