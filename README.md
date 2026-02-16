📞 Telecom Operator Efficiency Analysis – Python & Statistics

Proyecto Final · TripleTen Data Analysis

📌 Descripción

El objetivo de este proyecto es identificar a los operadores menos eficaces dentro del servicio de telefonía virtual CallMeMaybe.
Se analizan llamadas entrantes, salientes, internas, tiempos de espera y llamadas perdidas para determinar qué operadores presentan bajo rendimiento.
Además, se realiza una prueba estadística para verificar si ciertas condiciones afectan la duración promedio de las llamadas.

🎯 Objetivos del análisis

Realizar análisis exploratorio de datos (EDA) sobre las tablas de uso del servicio.

Identificar operadores ineficaces basado en:

llamadas entrantes perdidas

tiempos de espera largos

pocas llamadas salientes 

Evaluar hipótesis estadísticas relacionadas con el desempeño del servicio.

🗄️ Descripción de los datos
Dataset principal: telecom_dataset_us.csv

user_id: ID del cliente

date: fecha del registro

direction: tipo de llamada (in / out)

internal: llamada interna (sí/no)

operator_id: ID del operador

is_missed_call: llamada perdida

calls_count: número de llamadas

call_duration: duración sin tiempo de espera

total_call_duration: duración total con espera

Dataset de clientes: telecom_clients_us.csv

user_id: ID del cliente

tariff_plan: plan de tarifa

date_start: fecha de registro

🧪 Prueba de hipótesis

Se plantea una hipótesis para evaluar si ciertas condiciones afectan la eficiencia del servicio.


Incluye:

Hipótesis nula y alternativa

Método estadístico elegido

Nivel de significación (α)

Decisión final basada en el p-value

🛠 Tecnologías utilizadas

Python (Pandas, NumPy)

Matplotlib / Seaborn

Estadística (SciPy)

Jupyter Notebook

📊 Resultados principales

Causas principales: tasa de llamadas perdidas, tiempo de espera promedio y tasa de llamadas salientes.

Operadores identificados como ineficaces: 
Aplicando criterios claros de eficiencia, se clasificaron los operadores en Eficiente, Promedio e Ineficiente:

- 279 operadores Eficientes, con desempeño sobresaliente.

- 793 operadores Promedio, cumpliendo con estándares aceptables pero con margen de mejora.

- 6 operadores Ineficientes, quienes requieren atención para optimizar su desempeño.

Resultado de la prueba de hipótesis:

Se realizaron pruebas de Mann–Whitney U para identificar operadores con comportamiento atípico en tiempos de espera. Esto permitió detectar casos donde la diferencia respecto al promedio es significativa, reforzando las conclusiones sobre eficiencia.


🙋‍♀️ Autora

Jhoanny Alcocer Solano – Data Analyst Jr
