# Análisis del Impacto del Trabajo Remoto en la Salud (2025)

Este proyecto analiza el impacto que ha tenido el trabajo remoto post-pandemia en la salud mental y física de los trabajadores, utilizando un conjunto de datos simulado titulado `post_pandemic_remote_work_health_impact_2025.csv`.

## Estructura del Proyecto

- Notebook con todo el análisis, limpieza y visualizaciones.
- Fuente de datos original, /post_pandemic_remote_work_health_impact_2025.csv.
- README.md: Este archivo con la documentación principal del proyecto.

## Limpieza y Transformación de Datos

- Se gestionaron valores nulos en Mental_Health_Status y Physical_Health_Issues.

## Visualizaciones Principales

- pairplot
- **Distribución por Género:** Gráfico de pastel.
- **Distribución de Edad:** Histograma con KDE.
- **Estado de Salud Mental:** Gráfico de barras.
- **Tipo de Trabajo (Remoto, Híbrido, Presencial):** Gráfico de barras.
- **Mapa de calor:** Matriz de correlación entre variables numéricas.

## Hallazgos Clave

- Una proporción considerable de empleados reportó burnout alto trabajando más de 45 horas por semana.
- Las mujeres reportaron más problemas de salud física que los hombres.
- El trabajo remoto mostró mejores niveles de Work_Life_Balance_Score en promedio.
- Personas con horarios más extensos tienden a reportar peor salud mental.

## Herramientas y Librerías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab

## Conclusiones

El trabajo remoto puede ofrecer beneficios para el balance vida-trabajo, pero también plantea riesgos serios relacionados con la salud mental y física. Se recomienda a las organizaciones:

- Promover horarios sostenibles.
- Implementar apoyo psicológico o programas de bienestar.
- Evaluar regularmente el estado de salud de sus empleados.
