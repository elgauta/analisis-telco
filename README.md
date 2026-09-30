# Análisis de Cancelación de Clientes (Customer Churn) - Telco

## Objetivo
Identificar los principales factores asociados a la cancelación de clientes 
en una empresa de telecomunicaciones, para proponer recomendaciones de 
retención basadas en datos.

## Dataset
- Fuente: [Telco Customer Churn](https://www.kaggle.com/datasets/alfathterry/telco-customer-churn-11-1-3)
- 7043 clientes, 50 variables

## Herramientas
- Python (Pandas, Matplotlib)
- Google Colab

## Principales hallazgos
- La tasa general de cancelación es de (26.5 %), por encima del benchmark de la industria (15-25%).
- Los clientes con contrato Month-to-Month cancelan (45 % vs 2.5% y 10.7) de los contratos de dos años y un año respectivamente. Y quienes cancelan pagan más (73.02  vs59.29  al mes).
- Los que cancelan tienen una satisfacción promedio de 1.74 vs 3.79 de los que se quedan.
- La antigüedad promedio de quienes cancelan es de 17.98 meses vs 37.59 de quienes permanecen.
- Los clientes con (Internet Fiber Optic) tienen la mayor tasa de cancelación (40.7%).
## Recomendaciones
- Investigar los precios de la competencia para el segmento Month-to-Month y ajustar tarifas donde haga falta. Además, diseñar promociones que incentiven la migración a contratos de 1 o 2 años, que cancelan mucho menos (10.7% y 2.55%).

## Cómo ver el análisis
El notebook completo con el paso a paso está en [proyecto_a.ipynb](https://github.com/elgauta/analisis-telco/blob/main/proyecto_a.ipynb)
