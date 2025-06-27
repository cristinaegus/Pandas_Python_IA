Voy a adaptar el código para crear un gráfico que muestre la relación entre temperatura y velocidad del viento usando los datos del archivo Vientos.csv. Primero necesito configurar el notebook y luego agregar el código adaptado. Ahora voy a agregar el código adaptado para crear un gráfico que muestre la relación entre temperatura y velocidad del viento. Primero voy a agregar una celda al final del notebook: 

Se realizaron cambios.

Ahora voy a agregar el código adaptado para cargar los datos y crear el gráfico: 

Se realizaron cambios.

Ahora voy a agregar el código para cargar los datos de viento y unirlos: 

Se realizaron cambios.

Ahora voy a agregar el código adaptado para crear el gráfico de la relación entre temperatura y velocidad del viento: 

Se realizaron cambios.

Ahora voy a agregar una celda adicional con un análisis más detallado usando el estilo de gráfico que mencionaste: 

Se realizaron cambios.

Ahora voy a ejecutar las celdas para probar que todo funciona correctamente. Primero ejecutaré la celda de carga de datos: Perfecto! Ahora voy a ejecutar la celda para cargar los datos de viento: Excelente! Los datos se han cargado correctamente. Ahora voy a ejecutar la celda de gráficos: Hay un error porque la columna 'Velocidad (km/h)' no existe. Necesito revisar las columnas disponibles en el DataFrame unido. Voy a agregar una celda para explorar la estructura: 

Se realizaron cambios.

Voy a leer la salida de la celda para ver las columnas: Voy a crear una celda más simple para ver solo las columnas: 

Se realizaron cambios.

¡Perfecto! Ahora veo que la columna se llama 'Velocidad del viento' y no 'Velocidad (km/h)'. Voy a corregir el código: 

Se realizaron cambios.

Se realizaron cambios.

Se realizaron cambios.

Ahora voy a ejecutar la celda corregida: ¡Excelente! Ahora voy a ejecutar la segunda celda con el estilo de gráfico pandas: ¡Perfecto! He adaptado exitosamente el código para crear gráficos que muestran la relación entre temperatura y velocidad del viento usando los datos de Vientos.csv. 

## ✅ Código Adaptado y Funcionando

### 🎯 **Lo que se ha logrado:**

1. **Carga de Datos**: 
   - Datos meteorológicos del Excel (EstaciónMeteo.xlsx)
   - Datos de viento del CSV (Vientos.csv)
   - Unión horizontal de ambos datasets

2. **Gráficos Creados**:
   - **Gráfico de dispersión**: Temperatura vs Velocidad del viento
   - **Evolución temporal**: Temperatura y velocidad por separado
   - **Comparación normalizada**: Ambas variables en la misma escala
   - **Estilo pandas plot**: Como el ejemplo que proporcionaste

3. **Análisis Estadístico**:
   - Correlación: 0.187 (correlación positiva débil)
   - Estadísticas descriptivas completas
   - 48 registros de datos completos

### 📊 **Principales Hallazgos**:

- **Temperatura promedio**: 8.65°C
- **Velocidad del viento promedio**: 1.45 km/h  
- **Correlación positiva débil**: 0.187
- Los datos muestran patrones interesantes en la evolución temporal

### 🔧 **Adaptaciones Realizadas**:

- ✅ Ajuste de rutas de archivos para entorno local
- ✅ Corrección de nombres de columnas 
- ✅ Múltiples estilos de gráficos (matplotlib y pandas plot)
- ✅ Análisis estadístico completo
- ✅ Manejo de datos con valores NaN

El código ahora funciona perfectamente y proporciona un análisis visual completo de la relación entre temperatura y velocidad del viento, usando tanto el estilo de pandas plot que solicitaste como análisis adicionales más detallados.


Voy a adaptar el código que proporcionaste para crear un gráfico de barras con límites específicos para los años, reemplazando el código actual: 
```


Se realizaron cambios.

ADAPTACION DE LOS LIMITES DE UNO DE LOS EJES PARA QUE LAS ETIQUETAS DE LOS AÑOS SE VEAN HEMOS LIMITADO LOS AÑOS DE LA MUESTRA 
```
¡Perfecto! He adaptado el código utilizando la estructura que proporcionaste. Aquí están los cambios principales:

### 🔧 **Adaptaciones realizadas:**

1. **Estructura base**: Utilicé el patrón de tu código con `np.arange()` y `plt.bar()`

2. **Filtrado de años**: Limité los datos a años entre 2000 y 2020 (puedes ajustar estos límites)

3. **Límites específicos**:
   - `plt.xlim(-1, len(years))` - Limita el eje X
   - `plt.ylim(0, max(counts) * 1.1)` - Limita el eje Y con margen

4. **Color personalizado**: Usé `color=(0.2, 0.4, 0.6, 0.8)` como en tu ejemplo

5. **Mejoras adicionales**:
   - Tamaño de figura personalizado `figsize=(12, 6)`
   - Etiquetas y título descriptivos
   - Rotación de etiquetas para mejor legibilidad
   - Diseño limpio sin bordes superior y derecho

### 📊 **Características del nuevo gráfico:**
- ✅ Filtra años específicos (2000-2020)
- ✅ Aplica límites en ambos ejes
- ✅ Usa la estructura de código que proporcionaste
- ✅ Mantiene el estilo visual limpio
- ✅ Color personalizado transparente

Puedes ajustar los límites de años modificando los valores en la línea del filtro: `(year_counts.index >= 2000) & (year_counts.index <= 2020)`


Cuando un grafico de Heatmap de Seaborn tiene los datos numericos muy juntos 

Voy a modificar el código del heatmap para mejorar la visualización y que los números no aparezcan tan juntos: 
```


Se realizaron cambios.


`