🧠 Análisis de Salud Mental en Estudiantes

Este proyecto tiene como objetivo explorar los factores que afectan la salud mental de estudiantes, utilizando herramientas como Python para el análisis de datos y Power BI para la visualización interactiva.

🎯 Objetivo del Proyecto
Comprender cómo distintos aspectos de la vida de los estudiantes (como la presión académica, el estrés financiero, la calidad del sueño o la satisfacción con los estudios) pueden influir en su bienestar emocional, haciendo foco en la presencia o ausencia de síntomas de depresión.

🧰 Herramientas Utilizadas
Python (Jupyter Notebook): para la limpieza de datos, análisis estadístico y generación de gráficos.

Power BI: para crear visualizaciones dinámicas e interactivas que permiten explorar el dataset de forma visual e intuitiva.

🔍 Qué se analiza en este proyecto
Con Python:
Revisión de la calidad de los datos: valores nulos, tipos de datos, etc.

Limpieza y transformación del dataset.

Estadísticas descriptivas generales.

Análisis de variables como:

Horas de sueño por día.


Estrés financiero y antecedentes familiares de enfermedades mentales.

Distribución de estudiantes con y sin depresión por edad, género .


Con Power BI:
Dashboards con filtros interactivos para:

Visualizar la cantidad de estudiantes con síntomas de depresión según género, edad, ciudad o profesión.

Relacionar presión académica y laboral con la salud mental.

Analizar el impacto de la calidad del sueño y los hábitos alimenticios.

Comparar la satisfacción académica y laboral entre estudiantes con y sin síntomas de depresión.

Explorar el efecto del estrés financiero en la salud mental.

📌 Conclusiones esperadas
Este proyecto busca generar insights que ayuden a entender mejor cómo distintos factores afectan la salud mental en el ámbito estudiantil. Si bien no se realizan predicciones ni se construyen modelos, se obtiene una visión clara y fundamentada de las principales problemáticas a través del análisis descriptivo y visual.


## 📊 Dataset Field Descriptions

| Campo                             | Descripción |
|----------------------------------|-------------|
| **id**                           | Identificador único asignado a cada registro de estudiante en el conjunto de datos. |
| **Gender**                       | Género del estudiante (ej.: Male, Female, Other). Ayuda a analizar tendencias específicas por género en la salud mental. |
| **Age**                          | Edad del estudiante en años. |
| **City**                         | Ciudad o región de residencia del estudiante, brinda contexto geográfico al análisis. |
| **Profession**                   | Campo de trabajo o estudio del estudiante, puede dar pistas sobre factores de estrés ocupacional o académico. |
| **Academic Pressure**            | Nivel de presión académica percibido (exámenes, tareas, expectativas, etc.). |
| **Work Pressure**                | Nivel de presión relacionada al trabajo, útil para estudiantes que trabajan además de estudiar. |
| **CGPA**                         | Promedio general acumulado del estudiante, refleja el rendimiento académico. |
| **Study Satisfaction**           | Indicador de cuán satisfecho está el estudiante con sus estudios. Se puede relacionar con el bienestar mental. |
| **Job Satisfaction**             | Medida de satisfacción del estudiante con su empleo, si aplica. |
| **Sleep Duration**               | Promedio de horas de sueño diario. Factor clave para la salud mental. |
| **Dietary Habits**               | Evaluación de los hábitos alimenticios del estudiante, que pueden afectar el estado de ánimo y la salud general. |
| **Degree**                       | Carrera o programa académico que cursa el estudiante. |
| **Have you ever had suicidal thoughts ?** | Indicador binario (Sí/No) sobre si el estudiante ha tenido pensamientos suicidas. |
| **Work/Study Hours**            | Horas promedio por día dedicadas al estudio o trabajo. Pueden influir en los niveles de estrés. |
| **Financial Stress**             | Nivel de estrés financiero percibido, posible desencadenante de problemas de salud mental. |
| **Family History of Mental Illness** | Indica si hay antecedentes familiares de enfermedades mentales (Sí/No). Factor de predisposición importante. |
| **Depression**                   | Variable objetivo: indica si el estudiante está atravesando depresión (Sí/No). |
