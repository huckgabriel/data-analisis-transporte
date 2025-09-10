# Análisis de movilidad urbana y transporte público

Este proyecto analiza datos abiertos de transporte urbano para identificar **patrones de uso**, **horarios pico** y **tendencias de movilidad**.  
El objetivo es mostrar habilidades en **limpieza de datos**, **análisis exploratorio (EDA)** y **visualización**, aplicables al rol de **Analista de Datos**.

---

## Contenido del repositorio
transporte-urbano-analisis/
│── data/ # datasets (CSV o scripts de descarga)
│── notebooks/ # Jupyter Notebooks con EDA y análisis
│── src/ # funciones de limpieza, ETL y visualización
│── outputs/ # gráficos y tablas finales
│── README.md # este archivo


---

## Dataset

- **Fuente:** https://www.datos.gob.ar/dataset/transporte-sube---cantidad-transacciones-usos-por-fecha  
- **Descripción:** Registros de viajes por línea/estación con fecha y hora.  
- **Variables principales:**
  - 'fecha' → fecha del viaje
  - 'hora' → hora del viaje
  - 'linea' → línea de transporte (ej. colectivo/subte/tren)
  - 'estacion' → estación/parada
  - 'viajes' → cantidad de validaciones o pasajeros

---

## Instalación y requisitos

Clonar este repositorio:

'''bash
git clone https://github.com/usuario/data-analisis-transporte.git
cd transporte-urbano-analisis

Instalar dependencias (usar un entorno virtual es recomendable):
pip install -r requirements.txt

Requisitos principales
Python 3.9+
pandas
numpy
matplotlib / seaborn / plotly
jupyter



