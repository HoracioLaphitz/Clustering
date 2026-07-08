# Clustering — Segmentación de Viviendas en California

Proceso de clusterización sobre datos de viviendas de la ciudad de California, Estados Unidos, a partir de un dataset en formato CSV con variables geográficas (latitud/longitud), estructurales (habitaciones, dormitorios, antigüedad) y socioeconómicas (ingreso medio, valor medio de la vivienda).

El notebook carga los datos con `pandas` y genera visualizaciones geográficas con `seaborn` (dispersión de latitud/longitud coloreada por valor medio de la vivienda) como paso exploratorio previo a la segmentación.

## Contenido

- `Clustering.ipynb` — notebook con la carga de datos, exploración visual y proceso de clusterización.

## Tecnologías

Python · Jupyter Notebook · pandas · seaborn

## Cómo ejecutar

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Clustering.ipynb
```

## Autor

Horacio Laphitz — [GitHub](https://github.com/HoracioLaphitz) · [LinkedIn](https://www.linkedin.com/in/horacio-laphitz)
