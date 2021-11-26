# Reconocimiento_Reto_3

## Goal

El objetivo de esta práctica es construir un clasificador multiclase capaz de predecir correctamente
hasta 7 tipos distintos de terrenos a partir de medidas tomadas con teledetección.
Las medidas son: altitud, azimut, inclinación, DH_agua (distancia horizontal a una fuente de
agua), DV_agua (distancia vertical a una fuente de agua), DH_camino (distancia horizontal a
un camino), sombra_9am, sombra_12pm, sombra_3pm, DH_fuego (distancia horizontal a una
fuente de fuego potencial), reserva_1, reserva_2, reserva_3, reserva_4, t1, t2, t3, t4, t5, t6, t7,
t8, t9, t10, t11, t12, t13, t14, t15, t16, t17, t18, t19, t20, t21, t22, t23, t24, t25, t26, t27, t28,
t29, t30, t31, t32, t33, t34, t35, t36, t37, t38, t39, t40.
Las características reserva_1 a reserva_4 hacen referencia a si el terreno está en una reserva
nativa americana. Las características t1 a t40 indican la presencia en el terreno de hasta 40 tipos
de compuestos diferentes.

## Requirements

* Python 3.7+

* APackage >= 2.0.0

How to install all the requirements :
```bash
$ pip install -r requirements.txt
```

## Usage

```bash
$ python main.py
```

## Structure

    .
    ├── main.ipynb
    ├── reto3.pdf                       # Course
    │
    ├── Datasets                        # All the datasets
    │   ├── reto3_testX.csv             # Test dataset (need to be solved)
    │   ├── reto3_trainX.csv            # Features dataset
    │   └── reto3_trainY.csv            # Labels dataset
    │
    ├── Other methods tested (Bonus)    # Bonus documents
    │   ├── other_methods.ipynb         # All methods tested
    │   └── ...                         # Images, Graphs ...
    │
    ├── .gitignore
    └── README.md

## Authors

* **GILABERT MAÑO, VICENTE** - *Member 1* - [Vicent](https://github.com/vgilabert94)
* **Luis Rosario** - *Member 2* - [Luisrosario2604](https://github.com/Luisrosario2604)
