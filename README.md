Análisis de Churn de Clientes de Telecom X
Este proyecto realiza un análisis exploratorio de datos (EDA) sobre un conjunto de datos de clientes de Telecom X para comprender los factores que contribuyen a la pérdida de clientes (churn).

Contenido del Repositorio
El codigo está organizado en las siguientes secciones:

Extracción de datos: Carga el conjunto de datos desde una URL y muestra las primeras filas y la información general del DataFrame.
Transformación de datos:
Normaliza las columnas anidadas ('customer', 'phone', 'internet', 'account') en nuevas columnas.
Concatena las nuevas columnas al DataFrame principal.
Elimina las columnas anidadas originales.
Renombra las columnas de cargos para mayor claridad.
Convierte la columna 'TotalCharges' a tipo numérico, manejando errores.
Convierte varias columnas categóricas al tipo 'category' para optimizar la memoria y el rendimiento.
Maneja valores inesperados en la columna 'Churn' reemplazando cadenas vacías con NaN y eliminando las filas correspondientes.
Análisis de churn:
Examina la distribución de la variable 'Churn'.
Analiza las características de los clientes que han abandonado el servicio (churned customers) mediante el cálculo de recuentos de valores para características categóricas y estadísticas descriptivas para características numéricas.
Visualiza la relación entre 'Churn' y otras variables categóricas utilizando gráficos de barras (count plots).

Cómo usar el codigo:
Abre el notebook en Google Colab.
Ejecuta cada celda de código secuencialmente.
Examina las salidas de cada celda para comprender los pasos del análisis y los resultados.
Dependencias
El notebook utiliza las siguientes bibliotecas de Python, que están preinstaladas en el entorno de Google Colab:

pandas
numpy
seaborn
matplotlib

Fuente de datos
El conjunto de datos utilizado en este análisis se obtiene de la siguiente URL: https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/refs/heads/main/TelecomX_Data.json

