#Importing required packages.
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.ensemble import RandomForestClassifier
from sklearn.svm import SVC
from sklearn.linear_model import SGDClassifier
from sklearn.metrics import confusion_matrix, classification_report
from sklearn.preprocessing import StandardScaler, LabelEncoder
from sklearn.model_selection import train_test_split, GridSearchCV, cross_val_score
%matplotlib inline

Para el Machine Learning de esta Archivo es necesario hacer las siguientes importaciones : Pandas , Seaborn; Matplotlib y Sklearn

Veo que necesitas instalar scikit-learn. Voy a agregar una celda antes de las importaciones para instalar las librerías necesarias: 

Se realizaron cambios.

Ahora voy a configurar el notebook para usar el entorno correcto: Ahora voy a instalar scikit-learn usando las herramientas de Python del notebook: ¡Perfecto! Ahora voy a ejecutar la celda de instalación y luego la celda de importaciones: Ahora voy a ejecutar la celda de importaciones para verificar que todo funciona: ¡Excelente! 🎉 El problema está resuelto. 

### ✅ **Solución aplicada:**

1. **Instalé scikit-learn**: Agregué una celda con `!pip install scikit-learn ipywidgets`
2. **Configuré el notebook**: Establecí el kernel correcto (.venv)
3. **Instalé vía notebook**: Usé las herramientas específicas del notebook
4. **Verifiqué el funcionamiento**: Ejecuté las importaciones exitosamente

### 📚 **Librerías ahora disponibles:**

- ✅ **pandas**: Para manipulación de datos
- ✅ **seaborn & matplotlib**: Para visualización
- ✅ **scikit-learn**: Para machine learning
  - RandomForestClassifier
  - SVC (Support Vector Classifier)
  - SGDClassifier
  - Métricas de evaluación
  - Preprocesamiento de datos
- ✅ **ipywidgets**: Para widgets interactivos

### 🚀 **Estado actual:**
- El notebook está configurado correctamente
- Todas las librerías se importaron sin errores
- Estás listo para comenzar el análisis de calidad de vinos con machine learning

¡Ahora puedes continuar con tu proyecto de predicción de calidad de vinos sin problemas!
