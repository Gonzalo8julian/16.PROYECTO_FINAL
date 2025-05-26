# Análisis Marathon Six Majors

## 📖 Descripción

Este proyecto analiza los resultados de las principales maratones del mundo, conocidas como las Abbott World Marathon Majors, con el fin de identificar oportunidades de patrocinio basadas en datos reales y actuales. Se han recopilado y tratado los resultados de las ediciones 2024 de las maratones de Londres, Boston, Berlín y Chicago, con más de 200.000 corredores de 192 países diferentes.

Gracias a este análisis, se ha desarrollado un dashboard interactivo que permite explorar la participación por género, edad, nacionalidad, tiempos y nivel de élite, así como la cobertura de patrocinadores. Esto permite construir propuestas de patrocinio adaptadas al perfil de cada carrera.

## 🗂️ Estructura del Proyecto

├── data/
│   └── datos_limpios/
│       ├── resultados_berlin_2024_completo.csv
│       ├── resultados_boston_2024_completo.csv
│       ├── resultados_chicago_2024_completo.csv
│       └── resultados_london_2024_completo.csv


├── jupyters/
│   ├── carga_datos.ipynb               # Carga y preview de los datos
│   ├── Concat_datos_limpios.ipynb      # Unión de datasets individuales
│   ├── scrap_berlinmarathon.ipynb      # Scraping Berlín
│   ├── Scrap_BostonMarathon.ipynb      # Scraping Boston
│   ├── scrap_chicagomarathon.ipynb     # Scraping Chicago
│   ├── scrap_londonmarathon.ipynb      # Scraping Londres
│   └── scrap_nycmarathon.ipynb         # Scraping Nueva York (pendiente)


├── Presentación/                        # Carpeta para presentación final (vacía o en progreso)


├── src/                                 # (Opcional) Scripts Python reutilizables
│   └── (puede incluir funciones ETL, utils, etc.)


├── six_majors.pbix                      # Dashboard en Power BI


├── README.md                            # Este archivo


├── 1. DEFINICIÓN DEL PROYECTO Y ADQUISICIÓN DE DATOS.docx
├── 1. DEFINICIÓN DEL PROYECTO Y ADQUISICIÓN DE DATOS.pdf
└── .gitignore                           # Exclusiones para control de versiones

## 🛠️ Instalación y Requisitos
Este proyecto se ha desarrollado con:

	•	Python 3.9
	•	Librerías:
	•	Pandas
	•	NumPy
	•	Requests
	•	BeautifulSoup
	•	Matplotlib
	•	Seaborn
	•	Base de Datos: PostgreSQL
	•	Visualización: Power BI

## 📊 Resultados y Conclusiones

> Resumen de hallazgos:

	•	Género: Entre el 53% y el 65% de los corredores son hombres, según la maratón.
	•	Edad: Mayor concentración entre los 30 y 45 años.
	•	Internacionalidad: Berlín es la maratón con mayor variedad de nacionalidades.
	•	Rendimiento:
	•	Top tiempos hombres: entre 2:02:44 y 2:06:15.
	•	Top tiempos mujeres: entre 2:09:56 y 2:22:37.
	•	Nivel élite: Berlín destaca con más de 60 atletas élite en 2024.
	•	Sponsors:
	•	Chicago y Londres lideran en número de patrocinadores.
	•	Berlín tiene potencial de crecimiento en este aspecto.

## 💡 Recomendaciones

	•	Dirigir propuestas de patrocinio personalizadas según edad, género e internacionalidad de los participantes.
	•	Enfocar oportunidades para marcas tecnológicas y financieras en eventos con mayor diversidad internacional.
	•	Proponer paquetes de patrocinio en pruebas menos saturadas como Berlín.

## 🔄 Próximos Pasos

    •   Completar datos de Tokio y Nueva York.
	•	Incorporar datos económicos (ingresos por carrera y contratos de patrocinio).
	•	Analizar tendencias históricas.
	•	Diseñar paquetes de patrocinio por tipo de público y exposición.

## ✒️ Autor
- **Gonzalo Julián** - [@gonzalo8julian](https://github.com/Gonzalo8julian)