# Práctica IA (RA4 · a) — Automatización y optimización

## 1) Proceso elegido
## Extracción de Datos de Documentos — Proceso “ANTES” (Manual)

### ¿Quién lo hace?
- Auxiliares administrativos (data entry)
- Equipo de operaciones
- Supervisor para validación

### Pasos del proceso
1. Recepción del documento (email, escaneo o carga manual).
2. Clasificación manual por tipo.
3. Lectura e identificación de campos clave.
4. Transcripción manual al sistema (ERP/CRM/Excel).
5. Revisión y validación.
6. Corrección y archivo.

### Tiempo estimado
- 5–10 minutos por documento simple.
- 15–30 minutos por documento complejo.
- 100 documentos ≈ 8–12 horas de trabajo.

### Errores y cuellos de botella
**Errores frecuentes:**
- Digitación incorrecta.
- Campos omitidos.
- Formatos inconsistentes.

**Cuellos de botella:**
- Alta carga manual.
- Retrabajo por errores.
- Acumulación en picos de demanda.

## 2) ANTES (sin IA)

- Pasos (5–7):
  1. Recepción del documento (email, escaneo o carga manual).
  2. Clasificación manual según tipo de documento.
  3. Revisión visual e identificación de campos relevantes.
  4. Transcripción manual de datos al sistema (ERP/CRM/Excel).
  5. Validación y corrección de errores.
  6. Archivo y registro como procesado.

- Tiempo aproximado por caso:
  - 5–10 minutos (documento simple).
  - 15–30 minutos (documento complejo).

- Problemas / cuellos de botella:
  - Errores de digitación.
  - Omisión de campos.
  - Formatos inconsistentes.
  - Retrabajo por validaciones manuales.
  - Acumulación de documentos en picos de demanda.

## 3) DESPUÉS (con IA)

- **¿Qué automatiza la IA?**
  - Clasificación de documentos.
  - Extracción de campos clave (fechas, montos, nombres).
  - Validación de datos (formato, coherencia).
  - Integración y carga de datos en sistemas (ERP/CRM).

- **¿Qué queda para humanos?**
  - Supervisión de excepciones (errores no detectados por IA).
  - Verificación final de datos cuando la IA no está segura.
  - Decisiones complejas que requieran interpretación humana.

- **Datos necesarios (tipos de datos, sin datos personales):**
  - Tipos de documentos (factura, contrato, recibo).
  - Campos clave (fecha, monto, ID de transacción, nombre).
  - Estructura y formato de documentos (PDF, imagen, Word).

- **Modelo/técnica (NLP, clasificación, recomendación, visión, etc.):**
  - **NLP** (Procesamiento de Lenguaje Natural) para extracción de texto.
  - **Clasificación de documentos** con técnicas de aprendizaje supervisado.
  - **Visión por computadora** (OCR) para reconocer y extraer texto de imágenes o documentos escaneados.

---

## 4) Optimización (mejora medible)

Define 3 métricas con valores antes/después:

- **Tiempo:**
  - Antes: 5–30 minutos por documento.
  - Después: 1–2 minutos por documento.
  
- **Coste:**
  - Antes: Alto coste laboral (trabajo manual intensivo).
  - Después: Reducción de costes operativos gracias a la automatización.
  
- **Calidad:**
  - Antes: Errores frecuentes de digitación y omisión de datos.
  - Después: Mejora en precisión con menos errores y mayor consistencia.

---

## 5) Diagrama del flujo (ASCII)

```plaintext
+--------------------------+
| Recepción del Documento  |
+------------+-------------+
             |
             v
+------------+-------------+
| Clasificación del        |
| Documento                |
+------------+-------------+
             |
             v
+------------+-------------+
| Extracción de Datos      |
| con IA                   |
+------------+-------------+
             |
             v
+------------+-------------+
| Validación Automática    |
+------------+-------------+
             |
             v
+------------+-------------+
| Verificación Humana      |
| (si es necesario)        |
+------------+-------------+
             |
             v
+------------+-------------+
| Integración en el        |
| Sistema                  |
+------------+-------------+
             |
             v
+------------+-------------+
| Archivo del Documento    |
+--------------------------+
## 6) Riesgos y mitigación

- **Riesgo 1:**  
  La IA no puede extraer correctamente datos complejos o mal estructurados.  
  **Mitigación 1:**  
  Implementar una capa de revisión humana en casos donde la IA no esté suficientemente confiable o cuando se detecten errores. Mejorar continuamente el modelo con datos etiquetados.

- **Riesgo 2:**  
  Dependencia excesiva de la tecnología y fallos de integración en sistemas existentes.  
  **Mitigación 2:**  
  Realizar pruebas de integración constantes y mantener redundancias manuales para casos críticos. Además, garantizar que los sistemas de respaldo estén actualizados y operativos.

- **Riesgo 3:**  
  Falta de capacitación continua del personal humano para supervisar la IA.  
  **Mitigación 3:**  
  Establecer un programa de formación periódica para el equipo, enfocándose en el uso efectivo de la IA y en cómo intervenir correctamente en situaciones de error o ambigüedad.

---

## 7) Fuente oficial

- Enlace: [Automatización de procesos con IA - IBM](https://www.ibm.com/topics/ai-automation)
