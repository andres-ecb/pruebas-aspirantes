# Contenido
Este repositorio contiene un proyecto que consiste en el **análisis exploratorio de datos (EDA)** de los resultados de pruebas aplicadas a aspirantes a aprendiz del **Servicio Nacional de Aprendizaje (SENA)** en Colombia. El dataset original contenía información de más de 5,000 aspirantes, con sus puntajes en tres áreas de conocimiento (Razonamiento Cuantitativo, Comprensión Lectora e Inglés) y variables demográficas (sexo, ciudad de origen, fecha de nacimiento).

# Tecnologías Utilizadas
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
  
# Objetivos
- **Limpiar y preparar los datos** para garantizar su calidad y confiabilidad.
- **Caracterizar la población** aspirante en términos de sexo, edad y distribución geográfica.
- **Analizar el rendimiento académico** en las tres áreas evaluadas, identificando brechas por sexo, ciudad y región de origen y edad.
- **Identificar perfiles de aspirantes** según sus fortalezas académicas.

# Estructura
pruebas-aspirantes/
│
├── datos/
│ ├── datos_analisis.csv # datos limpios
│ ├── datos_en_bruto.csv # datos originales
│ └── datos_informe_final.csv # datos para storytelling
│
├── notebooks/
│ ├── 01_proceso_de_limpieza.ipynb # proceso completo de limpieza y validación
│ ├── 02_analisis_exploratorio.ipynb # análisis general
│ └── 03_storytelling.ipynb
│
└── Read.me # este archivo

# Ejecución
- Tener Python 3.9 o superior instalado
- Tener instaladas las librerías Pandas, Numpy, Seaborn y Matplotlib
