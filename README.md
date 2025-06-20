# Predicción de la Contaminación del Aire con Machine Learning

## Introducción

La contaminación atmosférica es uno de los principales problemas medioambientales y de salud pública a nivel global. Según la Organización Mundial de la Salud (OMS), más del 90% de la población mundial respira aire contaminado, lo que contribuye a más de 7 millones de muertes prematuras cada año. En Estados Unidos, pese a las regulaciones como la Clean Air Act, aún existen regiones que superan los límites permitidos de calidad del aire, especialmente en zonas urbanas e industriales.

La exposición prolongada a contaminantes como el dióxido de nitrógeno (NO₂), ozono (O₃), dióxido de azufre (SO₂) y monóxido de carbono (CO) se asocia a enfermedades respiratorias y cardiovasculares, así como al aumento de hospitalizaciones. Ante este panorama, resulta fundamental desarrollar modelos predictivos que anticipen los niveles de contaminación del aire, permitiendo:

- Emitir alertas tempranas ante episodios críticos de contaminación.
- Apoyar la planificación de políticas públicas y estrategias de mitigación.
- Informar a la población más vulnerable.

Este proyecto tiene como objetivo principal construir un modelo de predicción de la calidad del aire basado en datos reales recopilados en Estados Unidos. Se analiza la evolución temporal de los contaminantes y se aplican técnicas de machine learning para estimar su comportamiento futuro e identificar los factores que más influyen en su variación.

## Objetivos

- Predecir los niveles futuros de contaminantes atmosféricos (NO₂, O₃, SO₂, CO).
- Identificar tendencias y patrones a lo largo del tiempo.
- Evaluar el impacto potencial de condiciones ambientales actuales en el futuro.
- Utilizar modelos de machine learning como complemento a métodos estadísticos tradicionales.

## Dataset

El conjunto de datos utilizado incluye:

- Mediciones de calidad del aire por ubicación y fecha.
- Concentraciones de los contaminantes principales.
- Variables ambientales complementarias (si aplica).

Fuente: [EPA Air Quality Data](https://www.epa.gov/outdoor-air-quality-data)

## Tecnologías utilizadas

- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (modelos clásicos)
- XGBoost / LightGBM (boosting)
- TensorFlow / Keras (opcional para modelos más complejos)
