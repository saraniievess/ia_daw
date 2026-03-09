# Práctica IA (RA4 · d+e) — Sectores con implantación relevante y lenguajes de programación en IA

## 1) Introducción
- Objetivo de la práctica: analizar sectores donde la Inteligencia Artificial tiene una implantación relevante, identificar aplicaciones reales en esos sectores y estudiar qué lenguajes de programación se utilizan habitualmente para desarrollar soluciones basadas en IA.
- Relación con DAW/DAM: en el desarrollo de aplicaciones web y multiplataforma es cada vez más común integrar sistemas de inteligencia artificial, como motores de recomendación, análisis de datos o chatbots. Conocer los sectores donde se usa la IA y los lenguajes utilizados permite a los desarrolladores elegir tecnologías adecuadas y comprender cómo integrar servicios de IA en aplicaciones reales.

## 2) Sectores con implantación relevante de IA

### Sector 1
- Nombre del sector: sanidad.
- Tipo de empresa/servicio: hospitales, clínicas, laboratorios médicos...
- Aplicación de IA: análisis automático de imágenes médicas.
- Qué tarea mejora o automatiza: la IA puede analizar imágenes médicas para detectar enfermedades como tumores, fracturas o anomalías con mayor rapidez que un análisis manual inicial.
- Por qué la IA tiene implantación relevante en este sector: el sector sanitario genera grandes cantidades de datos médicos e imágenes, lo que permite entrenar modelos de aprendizaje automático para apoyar el diagnóstico.
- Beneficios que aporta: 
	Diagnósticos más rápidos.
	Reducción de errores humanos.
	Apoyo a los médicos en la toma de decisiones.
	Mejora en la detección temprana de enfermedades.

### Sector 2
- Nombre del sector: banca y finanzas.
- Tipo de empresa/servicio: bancos y empresas de servicios financieros.
- Aplicación de IA: detección de fraude en transacciones financieras.
- Qué tarea mejora o automatiza: los sistemas de IA analizan patrones en miles de transacciones para detectar comportamientos sospechosos o anómalos que podrían indicar fraude.
- Por qué la IA tiene implantación relevante en este sector: las entidades financieras manejan millones de transacciones diarias, por lo que la IA es necesaria para analizar datos en tiempo real y detectar amenazas.
- Beneficios que aporta: 
	Reducción de fraudes.
	Mayor seguridad para los clientes.
	Automatización del análisis de riesgos.
	Mejora en la eficiencia de los sistemas de seguridad.

### Sector 3
- Nombre del sector: comercio electrónico.
- Tipo de empresa/servicio: tiendas online, marketplaces, plataformas de venta digital...
- Aplicación de IA: sistema de recomendación de productos.
- Qué tarea mejora o automatiza: la IA analiza el comportamiento de los usuarios (búsquedas, compras anteriores, productos vistos) para recomendar productos personalizados.
- Por qué la IA tiene implantación relevante en este sector: las plataformas de comercio electrónico manejan enormes volúmenes de datos de usuarios y productos, lo que permite crear sistemas de recomendación muy precisos.
- Beneficios que aporta: 
	Experiencia de usuario personalizada.
	Incremento de ventas.
	Mayor fidelización de clientes.
	Mejora en la eficiencia del marketing digital.

## 3) Lenguajes de programación en IA

### Lenguaje 1
- Nombre: python.
- Uso principal en IA: desarrollo de modelos de aprendizaje automático y procesamiento de datos.
- Ventajas: 
	Gran cantidad de librerías especializadas (TensorFlow, PyTorch, Scikit-learn).
	Sintaxis sencilla y fácil de aprender.
	Amplia comunidad y documentación.
	
- Ejemplos de uso:
	Análisis de imágenes médicas.
	Sistemas de recomendación.
	Procesamiento de lenguaje natural.

### Lenguaje 2
- Nombre: java.
- Uso principal en IA: desarrollo de aplicaciones empresariales que integran sistemas de IA.
- Ventajas: 
	Alta escalabilidad.
	Buen rendimiento en aplicaciones grandes.
	Amplio uso en entornos corporativos.
	
- Ejemplos de uso: 
	Sistemas de detección de fraude en banca.
	Aplicaciones empresariales con análisis de datos.

### Lenguaje 3
- Nombre: C++.
- Uso principal en IA: desarrollo de sistemas de alto rendimiento y procesamiento intensivo.
- Ventajas:
	Alto rendimiento y eficiencia.
	Control detallado de memoria.
	Muy usado en motores de IA y bibliotecas base.
	
- Ejemplos de uso:
	Sistemas de visión por computadora.
	Desarrollo de motores de aprendizaje profundo.

### Lenguaje 4
- Nombre: JavaScript.
- Uso principal en IA: se utiliza para integrar modelos de inteligencia artificial en aplicaciones web y en el navegador.
- Ventajas: 
	Permite ejecutar modelos de IA directamente en el navegador.
	Muy útil para aplicaciones web interactivas.
	Gran integración con frameworks web modernos.
	
- Ejemplos de uso:
	Chatbots en páginas web.
	Sistemas de recomendación en tiendas online.
	Reconocimiento de imágenes o voz en aplicaciones web.

## 4) Relación entre sectores, tipo de IA y lenguaje
| Sector | Aplicación de IA | Tipo de IA/técnica | Lenguaje recomendado | Justificación |
|--------|------------------|--------------------|----------------------|---------------|
| Sanidad | Análisis de imágenes médicas | Deep learning | Python | Gran ecosistema de librerías para visión artificial |
| Banca | Detección de fraude | Machine learning | Java/Python | Análisis de datos en tiempo real |
| Comercio electrónico | Recomendación de productos | Machine learning | Python | Amplias librerías de análisis de datos |

## 5) Diagrama (ASCII o Mermaid)

A[Datos de usuarios o clientes] --> B[Procesamiento con IA]
B --> C[Modelo de Machine Learning]

C --> D1[Diagnóstico médico]
C --> D2[Detección de fraude]
C --> D3[Recomendación de productos]

D1 --> E[Sector Sanidad]
D2 --> F[Sector Banca]
D3 --> G[Sector Comercio electrónico]

## 6) Riesgos y mitigación
- Riesgo 1: sesgos en los datos utilizados para entrenar los modelos de IA.
- Mitigación 1: auditorías de datos y revisión humana para detectar posibles sesgos.
- Riesgo 2: falta de transparencia en los modelos de IA (opacidad o "caja negra").
- Mitigación 2: uso de técnicas de explicabilidad de IA y validación continua de los modelos.

## 7) Conclusión
- Qué sectores destacan más: sanidad, banca y comercio electrónico destacan por la gran cantidad de datos que generan y por los beneficios que aporta la automatización mediante IA.
- Qué lenguajes aparecen con más frecuencia: python es el lenguaje más utilizado debido a su gran ecosistema de librerías para inteligencia artificial y análisis de datos.
- Qué importancia tiene esto para DAW/DAM: los desarrolladores de aplicaciones web y multiplataforma deben comprender cómo integrar servicios de IA en sus aplicaciones, por ejemplo mediante APIs, análisis de datos o sistemas de recomendación.

## 8) Fuentes oficiales (mín. 2)
- Fuente 1 (sectores / aplicación IA):
Comisión Europea – Artificial Intelligence: Applications and Opportunities
https://digital-strategy.ec.europa.eu/en/policies/artificial-intelligence
- Fuente 2 (lenguajes / ecosistema técnico):
TensorFlow Documentation – AI Development Ecosystem
https://www.tensorflow.org/

