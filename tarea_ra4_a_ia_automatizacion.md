# Práctica IA (RA4 · a) — Automatización y optimización

## 1) Proceso elegido
- Nombre del proceso: extracción automática de facturas PDF
- Contexto (empresa/servicio web/IT): empresa administrativa que recibe facturas por correo electrónico
- Rol/es implicados: auxiliar administrativo

## 2) ANTES (sin IA)
- Pasos (5–7):
  1. Recibir el email con la factura en PDF.
  2. Descarga y abrir el PDF.
  3. Lectura de los datos importantes (proveedor, fecha, importe, IVA...).
  4. Corregir manualmente si hay algún fallo.
  5. Archivarlo en su sitio.
- Tiempo aproximado por caso: 10 min por factura.
- Problemas / cuellos de botella: retrasos cuando hay muchas facturas y riesgo de algún fallo.

## 3) DESPUÉS (con IA)
- ¿Qué automatiza la IA?
La lectura automática del PDF y la extracción de campos clave para poder ver más fácilmente los fallos.
- ¿Qué queda para humanos?
Gestión de alguna factura por excepción y únicamente validar los campos claves para que no haya fallos.
- Datos necesarios (tipos de datos, sin datos personales):
PDF de facturas y las plantillas de facturas que sigue.
- Modelo/técnica (NLP, clasificación, recomendación, visión, etc.):
Modelos de análisis de documentos como los descritos en la documentación oficial.

## 4) Optimización (mejora medible)
Define 3 métricas con valores antes/después:
- Tiempo: de 10 min por factura a 2 min por factura.
- Coste: una persona que se dedique a comprobar lo que hace la IA.
- Calidad: se reduce la posibilidad de que haya fallos.

## 5) Diagrama del flujo (ASCII o Mermaid)

    A[Email con factura PDF] --> B[IA]
    B --> C[Extracción de datos]
    C --> D{¿Confianza alta?}
    D -- Sí --> E[Factura comprobada y archivada]
    D -- No --> F[Revisión humana]

## 6) Riesgos y mitigación
- Riesgo 1:
- Mitigación 1:
- Riesgo 2:
- Mitigación 2:

## 7) Fuente oficial
- Enlace: 
