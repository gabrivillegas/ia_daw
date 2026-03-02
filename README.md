# Práctica IA (RA4 · b+c) — Big Data, análisis, rentabilidad y valoración IA

## 1) Caso y objetivo de negocio
- **Empresa/sector (real o ficticia):** Netflix (plataforma de streaming)
- **Problema a resolver:** Reducir la cancelación de suscripciones (churn) y aumentar el tiempo de visualización.
- **Objetivo de negocio (rentabilidad):** Aumentar ingresos recurrentes y maximizar el LTV (lifetime value) reduciendo bajas y mejorando la retención.

---

## 2) Big Data: recogida masiva de datos

**Por qué es Big Data:**  
- **Volumen:** cientos de millones de usuarios globales.  
- **Velocidad:** eventos en tiempo real (clics, pausas, búsquedas).  
- **Variedad:** datos estructurados y no estructurados.

- **Fuente 1:** Historial de visualización (qué ve, cuánto tiempo, abandono de episodio).
- **Fuente 2:** Interacciones en la app (búsquedas, clics, valoraciones).
- **Fuente 3:** Datos contextuales (dispositivo, ubicación aproximada, franja horaria).
- **Volumen/velocidad (estimación):** Miles de millones de eventos diarios generados en tiempo real.
- **Formatos:** Logs de eventos, series temporales, texto (búsquedas), metadatos audiovisuales.

---

## 3) Tratamiento/análisis: pipeline de datos

- **Ingesta (captura/eventos):** Recolección de logs en tiempo real desde apps móviles, Smart TV y web.
- **Limpieza/normalización:** Eliminación de duplicados, corrección de timestamps, anonimización.
- **Almacenamiento (data lake/warehouse):** Data lake distribuido (cloud) para datos crudos; data warehouse para análisis estructurado.
- **Preparación de variables (features):**
  - Frecuencia de uso semanal.
  - Ratio de abandono de series.
  - Tiempo medio por sesión.
  - Diversidad de géneros consumidos.
- **Análisis/BI (opcional):** Dashboards de retención por cohorte y segmento.

---

## 4) IA aplicada: modelo y decisión

- **Tipo de IA/técnica:**  
  - Sistemas de recomendación (filtrado colaborativo + deep learning).  
  - Modelo de clasificación para predicción de churn.

- **Entrada del modelo:**  
  Historial de consumo, patrones de uso, interacción con recomendaciones, antigüedad del cliente.

- **Salida del modelo:**  
  - Ranking personalizado de contenidos.  
  - Probabilidad de cancelación (score de churn).

- **Decisión que habilita:**  
  - Personalizar portada y recomendaciones en tiempo real.  
  - Ofrecer promociones o notificaciones personalizadas a usuarios con alto riesgo de baja.

---

## 5) Rentabilidad: KPIs antes/después (mínimo 3)

### KPI 1 (Tasa de churn mensual)
- **Antes:** 4,5% mensual  
- **Después:** 3,8% mensual  
- **Por qué mejora la rentabilidad:** Cada décima de reducción implica millones en ingresos retenidos sin coste de adquisición adicional.

### KPI 2 (Tiempo medio de visualización por usuario/mes)
- **Antes:** 20 horas  
- **Después:** 24 horas  
- **Por qué mejora la rentabilidad:** Mayor engagement → mayor fidelidad → menor probabilidad de cancelación.

### KPI 3 (Coste de adquisición vs LTV)
- **Antes:** LTV/CAC = 2,8  
- **Después:** LTV/CAC = 3,5  
- **Por qué mejora la rentabilidad:** Mayor permanencia del usuario incrementa el valor total generado por cliente.

---

## 6) Diagrama del pipeline (ASCII)

```mermaid
flowchart LR
    A[Usuarios App / Web] --> B[Eventos en tiempo real (clics, vistas, busquedas)]
    B --> C[Ingesta Big Data (streaming / batch)]
    C --> D[Data Lake (datos crudos)]
    D --> E[Feature Engineering (variables del modelo)]
    E --> F[Modelo de IA]
    F --> G[Recomendador]
    F --> H[Modelo de Churn]
    G --> I[Personalizacion]
    H --> J[Acciones de Retencion]
    I --> K[Mejora de KPIs (retencion, LTV, engagement)]
    J --> K
```
      
## 7) Riesgos y mitigación

**Riesgo 1: Sesgos algorítmicos**
- **Mitigación 1:** Auditorías periódicas de equidad y diversidad en recomendaciones.

**Riesgo 2: Privacidad y protección de datos**
- **Mitigación 2:** Anonimización, cumplimiento del RGPD, cifrado y control de acceso.

---

## 8) Valoración (criterio c): importancia presente y futura de la IA

- **Importancia actual (hoy):**  
La IA es un elemento central del modelo de negocio digital. En plataformas como Netflix, la mayoría del contenido consumido proviene de recomendaciones automáticas. Sin IA, la experiencia sería genérica y la tasa de cancelación mayor. La ventaja competitiva ya no es solo el catálogo, sino la capacidad de personalizarlo a escala global.

- **Importancia futura (3–5 años):**  
La IA evolucionará hacia sistemas más predictivos y generativos: creación de trailers personalizados, ajuste dinámico de precios, optimización automática de inversión en producción según demanda prevista. La hiperpersonalización será el estándar competitivo.

- **Condiciones/limitaciones:**  
Dependencia de datos de calidad, altos costes de infraestructura, regulación creciente en privacidad, riesgos éticos y posible impacto laboral en áreas creativas y analíticas.

- **Conclusión razonada:**  
La IA no es solo una herramienta de eficiencia, sino un activo estratégico que redefine la rentabilidad y la propuesta de valor. Su peso competitivo aumentará, pero exigirá gobernanza sólida, transparencia y responsabilidad.

---

## 9) Fuentes oficiales (mín. 2)

- **Big Data/analítica (enlace oficial):**  
Netflix Tech Blog — https://netflixtechblog.com/

- **IA/técnica/modelo (enlace oficial):**  
TensorFlow — https://www.tensorflow.org/
