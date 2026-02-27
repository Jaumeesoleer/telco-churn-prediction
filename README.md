# 📉 Exploratory Data Analysis to identify churn drivers and retention opportunities - Telecom

## Contexto

El churn impacta directamente en ingresos recurrentes de una empresa telecom ficticia con un aproximado de 7000 clientes en el dataset. El enfoque principal es un EDA orientado a negocio.

## Objetivo del proyecto

El objetivo principal del proyecto es analizar la tasa general de churn priorizando factores con mayor impacto y detectando segmentos de alto riesgo para poder extraer insights accionables.

## Dataset

El dataset cuenta con 7042 registros de diferentes clientes. Las principales variables analizadas son:

- gender, seniorCitizen, tenure, phoneService, internetService, monthlyCharges, totalCharges, churn
  Con la variable objetivo es el churn
  No existen valores nulos significativos tras limpieza

## Metodologia

La metodologia a seguir es la siguiente:

1. Data cleaning and preprocessing
2. Univariate analysis
3. Segmentation by key variables
4. Interaction analysis (Contract + MonthlyCharges, Contract + Tenure, etc.)
5. Business interpretation

## Insights

- Churn general del 26.5%
- El contrato mensual multiplica por 6 la tasa de abandono frente al anual
- El churn es especialmente alto en los primeros meses de tenure
- Los clientes con autopay presentan menor tasa de abandono
- El alto churn en seniors está condicionado por el tipo de contrato
- Monthly Charges altos en contratos mensuales disparan la tasa de churn

## Key metrics snapshot

- Clientes: 7042
- Churn rate: 26.5%
- Segmentación de riesgo: Monthly contract + High monthly charges
- Senior month rate: 54.6%

## Recomendaciones de negocio

- Diseñar incentivos económicos para migrar clientes mensuales a contratos anuales
- Implementar seguimiento activo durante el primer mes
- Ofrecer descuentos condicionados a activación de autopay
- Segmentación específica para seniors

## Tecnologías utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter notebook
- Git/GitHub
