![Gas](https://github.com/user-attachments/assets/191ee540-9b02-43f1-9dd9-8c7f95c6ca0d)

![banner_flat1](https://github.com/user-attachments/assets/81259883-b2bd-4db5-bf90-547c8d3d96af)

## MATERIA: APRENDIZAJE AUTOMÁTICO
## DOCENTE: LIC. MARTIN MIRABETE
## ALUMNO: DIEGO ORONÁ
## TÍTULO DEL PROYECTO: CONSUMO DE GAS NATURAL POR RED SEGÚN TIPO DE USUARIO EN TIERRA DEL FUEGO.

## Descripción del Proyecto:
El proyecto “Consumo de Gas Natural por red según tipo de usuario en Tierra del Fuego” tiene como propósito analizar cómo se consume el gas natural en la provincia, dividiendo los datos según el tipo de usuario, que incluye hogares, comercios e industrias. Se recogerán datos sobre el consumo, la facturación y estadísticas de uso, los cuales serán limpiados y transformados para facilitar su análisis. Mediante técnicas de aprendizaje automático, se buscarán patrones en estos datos y se realizarán proyecciones sobre el consumo futuro, teniendo en cuenta factores como el clima y el crecimiento de la población.

## Objetivo del Proyecto:
El objetivo del proyecto es abordar el problema de cómo consumir gas natural de manera eficiente en la provincia de Tierra del Fuego, ya que la demanda varía mucho entre los diferentes tipos de usuarios, como hogares, comercios e industrias. Mediante un modelo de aprendizaje automático, se buscará identificar patrones en el consumo de gas, lo que permitirá anticipar la demanda futura y mejorar la gestión de la red de distribución. Este enfoque es fundamental para enfrentar retos como la planificación de la infraestructura, la asignación adecuada de recursos y asegurar un suministro constante y sostenible, lo que ayuda a reducir el riesgo de desabastecimiento y a mejorar la calidad del servicio.

## Contexto:
El proyecto sobre el consumo de gas natural en Tierra del Fuego se sitúa en una provincia que ha visto un notable crecimiento en su población y economía en los últimos años. Este incremento en la demanda de gas natural, impulsado por el aumento de hogares, comercios e industrias, presenta importantes desafíos para la gestión de la red de distribución. La variabilidad en el consumo entre los diferentes tipos de usuarios hace que la planificación y el suministro sean aún más complicados.

## Relevancia:
Es fundamental abordar este problema para garantizar un suministro de gas que sea adecuado y sostenible. Si la demanda sigue creciendo sin control, podría haber escasez de recursos, lo que afectaría la calidad del servicio y tensaría la infraestructura existente. Además, con el cambio climático y la evolución en los patrones de consumo, es vital contar con datos precisos y proyecciones que permitan anticipar la demanda futura.

## Preguntas de Investigación:
¿Cómo varía el consumo de gas natural entre los diferentes sectores (Comercial, Residencial, Industrial)?

¿Existen patrones estacionales en el consumo de gas natural?

¿Cómo impacta la población de cada sector en el consumo de gas natural?

¿Se pueden predecir los patrones de consumo futuro en función de los datos históricos?

¿Cómo afecta la implementación de políticas de eficiencia energética al consumo de gas natural?


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
