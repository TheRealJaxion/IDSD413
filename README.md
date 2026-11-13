# Deteccion y Analisis Estadistico de Fraude en Transacciones Financieras

Proyecto 1 - Fundamentos de Big Data (IDSD413)
Escuela Politecnica Nacional (EPN) - GR1CD
Autor: Jordy Cartagena

## Estructura del Proyecto
- `data/raw/`: Dataset original comprimido (`data-card-detection.zip`).
- `data/processed/`: Datos depurados (`transactions_cleaned.parquet`) y con ingenieria de caracteristicas (`transactions_features.parquet`).
- `notebooks/`:
  - `01_inspeccion_eda_transacciones.ipynb`: Extraccion, auditoria de calidad y limpieza estructural.
  - `02_eda_y_analisis_transacciones.ipynb`: Estadistica descriptiva, 4 pruebas inferenciales y transformaciones.
- `figures/`: Visualizaciones de alta resolucion generadas automaticamente.
- `environment.yml` / `requirements.txt`: Especificacion de dependencias del entorno `IDSD413`.

## Reproducibilidad
1. Crear entorno: `mamba env create -f environment.yml && mamba activate IDSD413`
2. Ejecutar los cuadernos en orden numerico (`01` y luego `02`).
