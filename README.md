# Proyecto-8-Bootcamp

•	Objetivo: Análisis de un conjunto de datos de plataformas de viajes en taxi para determinar frecuencias, costos y comportamientos de demanda.

•	Librerías habituales: pandas, numpy, matplotlib/seaborn, scipy.stats y/o statsmodels.

•	Carga y preprocesado:
o	Lectura de uno o varios CSV/TSV, renombrado de columnas y cast de tipos (IDs a str, timestamps a datetime).
o	Creación de columnas derivadas: event_date, event_hour, flags binarios y agregados por usuario.
o	Filtrado por fecha/condiciones de negocio y limpieza básica (duplicados/nulos).

•	Análisis Exploratorio de Datos:
o	Conteos totales de eventos y usuarios únicos; tasas por usuario.
o	Distribuciones temporales (por día/hora) y visualizaciones tipo barplot/histograma.
o	Identificación de eventos clave y construcción de embudo con cálculo de tasas de conversión entre etapas.

•	Experimentación:
o	Agrupación por variante/exp_id y conteo de usuarios por grupo.
o	Implementación de tests de proporciones (z-test / proportions_ztest) para comparar conversiones entre grupos.
o	Generación de tablas de p-values por evento y decisión con alpha (probablemente 0.05).

•	Salidas: tablas resumen (usuarios por evento, conversion rates) y gráficos del embudo y comparaciones entre variantes.

