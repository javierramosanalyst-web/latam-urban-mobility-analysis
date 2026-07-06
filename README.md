# 🏙️ Análisis de Movilidad Urbana LATAM

**🎯 Objetivo**
Integrar y analizar datos de TomTom (tráfico urbano) y OECD (indicadores socioeconómicos) para identificar patrones de movilidad y su relación con factores urbanos en las principales ciudades de América Latina.

**🔍 Problema de negocio**
¿Cómo se mueven las personas en las principales ciudades de LATAM y qué factores socioeconómicos influyen en esa movilidad? Los datos estaban en dos fuentes con formatos completamente distintos — había que integrarlos, limpiarlos y analizarlos para extraer patrones útiles.

**🗄️ Dataset**
- **Fuente 1:** TomTom Traffic Index — congestión y tráfico urbano por ciudad
- **Fuente 2:** OECD Urban Mobility Indicators — indicadores socioeconómicos
- **Cobertura:** Colombia, México, Argentina y otros países de LATAM
- Ambos datasets son públicos y de libre acceso

**🛠️ Herramientas**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

**⚙️ Proceso**
1. Carga y exploración de datasets TomTom y OECD con Pandas
2. Limpieza: manejo de nulos, normalización de ciudades, conversión de tipos
3. Integración de ambos datasets con merge por ciudad y año
4. Análisis exploratorio (EDA): distribuciones, correlaciones, outliers
5. Visualizaciones con Seaborn y Matplotlib: scatter plots, heatmaps, bar plots
6. Comparación de patrones entre ciudades colombianas, mexicanas y argentinas

**📊 Principales hallazgos**
- 🚗 Ciudad de México lidera en congestión (jams_delay más alto de LATAM)
- 📈 Bogotá presenta el mayor jams_delay con PIB per cápita sin explotar
- 💡 Ciudades con mayor congestión no siempre corresponden a las de mayor población
- 🔗 Correlaciones documentadas entre indicadores OECD y niveles de tráfico TomTom

**💡 Conclusión**
El 70% del trabajo de un Data Analyst es entender y limpiar los datos antes de analizarlos. Integrar dos fuentes con formatos distintos fue el mayor reto técnico — y la lección más valiosa del proyecto.

**📁 Archivos**
- `mobility_analysis.ipynb` — Notebook completo con todo el análisis

**👤 Autor**
**Javier Eduardo Ramos Rivera**
Junior Data Analyst | SQL · Python · Power BI
📧 javierramos.analyst@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/javier-ramos-rivera/)
📁 [Portafolio Notion](https://app.notion.com/p/Portafolio-Javier-Eduardo-Ramos-Rivera-Data-Analyst-Junior-31cade63135a80ce969acccf829d1b89)
