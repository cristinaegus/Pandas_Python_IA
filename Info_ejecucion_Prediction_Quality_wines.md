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

----------------------------------------------------------------
Modificaciones en el Grafico sns.heatmap para que se vean los numeros mejor y 
no tan apelotonados 

``
¡Perfecto! He mejorado el heatmap para que los números se vean mucho mejor y no aparezcan tan juntos. Los cambios implementados incluyen:

### 🎨 **Mejoras aplicadas:**

1. **Tamaño de figura aumentado**: `plt.figure(figsize=(12, 10))` - Hace el gráfico más grande
2. **Formato de números**: `fmt='.2f'` - Muestra solo 2 decimales para mayor claridad
3. **Tamaño de fuente optimizado**: `annot_kws={'size': 8}` - Ajusta el tamaño de los números
4. **Celdas cuadradas**: `square=True` - Hace que todas las celdas tengan la misma forma
5. **Líneas separadoras**: `linewidths=0.5` - Añade líneas entre celdas para mejor separación
6. **Título descriptivo**: Añadido con buen espaciado
7. **Layout automático**: `plt.tight_layout()` - Optimiza el espacio automáticamente

### 📊 **Resultado:**
- ✅ Los números ahora tienen más espacio y se leen claramente
- ✅ Mejor separación visual entre las celdas
- ✅ Formato más profesional y limpio
- ✅ Tamaño optimizado para pantalla
- ✅ Números con precisión adecuada (2 decimales)

Ahora cuando ejecutes esta celda, tendrás un heatmap mucho más legible donde podrás ver claramente las correlaciones entre todas las variables del dataset de vinos sin que los números se superpongan o se vean apretujados.
