# SQL_poblacion_salario_paro
# 💼 Análisis Salarial por Comunidad Autónoma en España (2023)

Este proyecto explora las diferencias salariales por comunidades autónomas y sexo en España durante el año 2023. Utilizando Python, pandas y SQL en entorno Jupyter, se analiza la evolución de los salarios y la brecha de género en distintas regiones del país.

## 📌 Objetivos

- Analizar la evolución de los salarios en España por CCAA.
- Comparar salarios entre mujeres y hombres.
- Detectar posibles brechas salariales.
- Consultar y transformar datos usando SQL embebido (`ipython-sql`).

---
## Limitaciones y Consideraciones
Las consultas realizadas se basan en los datos disponibles de las tablas de salarios, paro y población.

Debido a que los datos no están completamente alineados entre sí — por ejemplo, diferencias en los nombres de comunidades, provincias, períodos o niveles de agregación — no ha sido posible realizar consultas complejas que combinen todas las tablas de forma óptima.

Esto limita el análisis a consultas sencillas o a aquellas uniones en las que hay coincidencias directas y limpias entre las tablas.

Para futuros análisis, se recomienda realizar una limpieza y normalización más exhaustiva de los datos para permitir relaciones más robustas entre tablas y facilitar consultas más complejas y completas.

---

## 📁 Estructura del repositorio

SQL_poblacion_salario_paro/

├── Notebooks/

│ └── Empleo_España_2025_Análisis_WebScrapin_&_DataScience.ipynb

│

├── sql/

│ ├── crear_tabla_salarios.sql 

│ ├── crear_tabla_poblacion.sql 

│ ├── crear_tabla_paro.sql 

│ └── Consultas

│

├── README.md 
