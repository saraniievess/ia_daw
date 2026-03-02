# Práctica IA (RA4 · b+c) — Big Data, análisis, rentabilidad y valoración IA

## 1) Caso y objetivo de negocio
- Empresa/sector (real o ficticia): Supermercado físico
- Problema a resolver: Pérdidas por productos que caducan y se tiran
- Objetivo de negocio (rentabilidad): Reducir desperdicio de alimentos y aumentar beneficios

## 2) Big Data: recogida masiva de datos
Describe por qué es Big Data (volumen, velocidad, variedad). Es Big Data porque se generan miles de ventas diarias en cada tienda, se generan datos cada minuto en caja y existe variedades como los tickets de compra, las fechas de caducidad, promociones...
- Fuente 1: Datos de ventas diarias en caja
- Fuente 2: Fechas de caducidad del inventario
- Fuente 3: Datos del clima (temperatura influye en venta de bebidas, helados, etc.)
- Volumen/velocidad (estimación): 20.000 transacciones diarias y actualizaciones cada pocos minutos.
- Formatos (texto, eventos, series temporales, imágenes, etc.): Registros de ventas, fechas, datos externos...

## 3) Tratamiento/análisis: pipeline de datos
Explica el flujo de forma ordenada:
- Ingesta (captura/eventos): Los datos se recogen automáticamente desde las cajas registradoras y el sistema de inventario
- Limpieza/normalización: Se corrigen errores, se eliminan datos duplicados y se unifican formatos de fechas
- Almacenamiento (data lake/warehouse): Base de datos central
- Preparación de variables (features): Ventas promedio por día, ventas según temperatura, productos que más caducan...

## 4) IA aplicada: modelo y decisión
- Tipo de IA/técnica (clasificación, predicción, recomendación, anomalías, NLP...): Modelo de predicción (regresión)
- Entrada del modelo (qué datos usa): Ventas pasadas, clima, promociones, día de la semana...
- Salida del modelo (qué produce): Predicción de cuántas unidades se venderán cada día
- Decisión que habilita (qué hace la empresa con esa salida): El supermercado compra solo la cantidad necesaria para evitar exceso de stock

## 5) Rentabilidad: KPIs antes/después (mínimo 3)
KPI 1 (ingresos/coste/eficiencia):
- Antes: 12% del stock se tiraba
- Después: 5%
- Por qué mejora la rentabilidad: menos producto perdido, es decir, menos dinero perdido

KPI 2:
- Antes: 80.000€
- Después: 95.000€
- Por qué mejora la rentabilidad: reducción de costes por desperdicio

KPI 3:
- Antes: reposición cada 10 días
- Después: reposición optimizada cada 7 días
- Por qué mejora la rentabilidad: mejor uso del almacén y menos sobrestock

## 6) Diagrama del pipeline (ASCII o Mermaid)
Ventas + Inventario + Clima --> Ingesta
Ingesta --> Limpieza de datos
Limpieza de datos --> Base de datos
Base de datos --> Modelo predictivo (IA)
Modelo predictivo (IA) --> Decisión de compra de stock
Decisión de compra de stock --> Menos desperdicio = Más beneficio

## 7) Riesgos y mitigación
Riesgo 1: Si el modelo falla, puede faltar producto o sobrar
- Mitigación 1: Supervisión humana y revisión semanal de resultados

Riesgo 2: Errores en inventario afectan la predicción
- Mitigación 2: Validación automática de datos y auditorías periódicas

## 8) Valoración (criterio c): importancia presente y futura de la IA (10–15 líneas)
- Importancia actual (hoy): La IA ayuda hoy a las empresas a tomar decisiones basadas en datos reales y no en intuiciones. Permite ahorrar costes, reducir desperdicios, mejorar la eficiencia y aumentar beneficios.
- Importancia futura (3–5 años): En los próximos años la IA será más automática y precisa. Los sistemas podrán tomar decisiones casi en tiempo real y adaptarse solos a cambios del mercado. También veremos asistentes inteligentes en empresas.
- Condiciones/limitaciones (datos, costes, regulación, ética, seguridad, empleo): La IA necesita datos de calidad, inversión económica y mantenimiento continuo. Existen riesgos como errores, dependencia tecnológica y problemas éticos si no se controla adecuadamente.
- Conclusión razonada: La IA es una herramienta clave para mejorar la rentabilidad empresarial. Sin embargo, debe usarse con supervisión humana y buena gestión de datos para garantizar resultados fiables y sostenibles.

## 9) Fuentes oficiales (mín. 2)
- Big Data/analítica (enlace oficial): https://www.ibm.com/topics/big-data
- IA/técnica/modelo (enlace oficial): https://oecd.ai/en/ai-principles
