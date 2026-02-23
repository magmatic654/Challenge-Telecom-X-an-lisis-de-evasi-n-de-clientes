# Telecom X - Análisis de Evasión de Clientes

## 📌 Propósito del Proyecto
Este proyecto tiene como objetivo analizar el abandono de clientes (churn) en la empresa ficticia Telecom X. A través de técnicas de extracción, limpieza y análisis de datos, se busca identificar patrones de comportamiento que permitan diseñar estrategias de retención más efectivas.

## 📂 Estructura del Proyecto
TelecomX/
│
├── data/
│   └── TelecomX_Data.json        # Datos originales en formato JSON
│
├── notebooks/
│   └── TelecomX_LATAM.ipynb      # Notebook principal con el análisis
│
├── results/
│   ├── churn_charges_bins.png    # Gráfico de churn por cargos totales
│   └── churn_tenure_bins.png     # Gráfico de churn por antigüedad
│
└── README.md                     # Documentación del proyecto

## 📊 Ejemplos de Gráficos e Insights
### 1. Churn por Cargos Totales
- Los clientes con gastos más bajos (Bin 0) presentan una tasa de abandono cercana al 46%.
- Los clientes con gastos más altos (Bin 4) muestran una tasa de abandono mucho menor, alrededor del 14.1%.
- Insight: A mayor inversión en servicios, menor propensión al abandono.

### 2. Churn por Antigüedad (Tenure)
- Los clientes más nuevos (Bin 0) tienen una tasa de abandono alarmante de 52.9%.
- Los clientes más antiguos (Bin 4) apenas alcanzan un 6.6% de abandono.
- Insight: La antigüedad es un factor crítico en la retención; los clientes nuevos requieren mayor atención.

## ⚙️ Instrucciones para Ejecutar el Notebook
1. Clonar el repositorio:
   git clone https://github.com/magmatic654/Challenge-Telecom-X-an-lisis-de-evasi-n-de-clientes.git
   cd Challenge-Telecom-X-an-lisis-de-evasi-n-de-clientes


2. Abrir el notebook en Google Colab o Jupyter:
   - En Colab: subir el archivo TelecomX_LATAM.ipynb y el dataset TelecomX_Data.json.
   - En Jupyter: ejecutar directamente desde la carpeta notebooks/.

3. Instalar dependencias necesarias:
   pip install pandas numpy matplotlib seaborn

4. Ejecutar las celdas paso a paso:
   - Extracción y limpieza de datos
   - Preparación para el análisis de churn
   - Visualización y conclusiones

## ✅ Conclusiones Clave
- Existe una correlación inversa entre cargos totales y antigüedad con la tasa de abandono.
- Los clientes nuevos y de bajo gasto son los segmentos más vulnerables.
- Se recomienda:
  - Programas de onboarding y retención temprana.
  - Paquetes de valor añadido para clientes de bajo gasto.
  - Programas de lealtad para clientes antiguos y de alto gasto.
  - Campañas segmentadas basadas en bins de gasto y antigüedad.
