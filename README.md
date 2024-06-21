# Proyecto Final

Esta aplicación utiliza un modelo de aprendizaje profundo para ayudar en la detección de cáncer de colon  a partir de imágenes histopatológicas. El modelo se basa en InceptionV3, pre-entrenado en el conjunto de datos ImageNet, y se ha afinado utilizando técnicas de aprendizaje por transferencia para adaptarse a las especificidades de la clasificación del tejido del colon. El conjunto de datos utilizado para el entrenamiento comprende imágenes etiquetadas como benignas o malignas, proporcionando al modelo los ejemplos necesarios para distinguir entre células sanas y cancerosas. Además, la aplicación ofrece información detallada sobre el rendimiento del modelo, incluyendo precisión, métricas de pérdida y matriz de confusión, que ayudan a entender la eficacia y fiabilidad del modelo.

## Instrucciones de ejecucion

- Contar con un entorno de ejecucion adecuado, como un **cuaderno de jupyter** o **google colab**, para poder hacer la ejecucion del archivo .ipynb
- Ejecutar todas las secciones de codigo en orden que se encuentran dentro del cuaderno.
- Una vez se ejecuto todo dirigirse hacia la carpeta donde se encuentra el archivo **Dashboard.py** en la terminal.
- Instalar todas las dependencias que se encuentran en el archivo **requirements.txt**.
- Una vez instaladas las dependencias, ejecutar el **Dashboard** usando el comando ```streamlit run Dashboard.py```
- Abrir la direccion local en su navegador de preferencia y visualizar los resultados.
