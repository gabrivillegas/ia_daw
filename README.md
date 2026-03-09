# Práctica IA (RA4 · d+e) — Sectores con implantación relevante y lenguajes de programación en IA

## 1) Introducción
- Objetivo de la práctica:  
Analizar en qué sectores se utiliza la inteligencia artificial actualmente, qué tipo de aplicaciones se desarrollan y qué lenguajes de programación se utilizan para construir esas soluciones.

- Relación con DAW/DAM:  
La inteligencia artificial está cada vez más integrada en aplicaciones web, móviles y sistemas empresariales. Para estudiantes de DAW y DAM es importante conocer cómo se integran servicios de IA en aplicaciones, qué tecnologías se utilizan y qué lenguajes son más habituales en este campo.

---

## 2) Sectores con implantación relevante de IA

### Sector 1
- Nombre del sector:  
Sanidad

- Tipo de empresa/servicio:  
Hospitales, clínicas, centros de investigación médica y empresas de tecnología sanitaria.

- Aplicación de IA:  
Análisis de imágenes médicas para ayudar en el diagnóstico.

- Qué tarea mejora o automatiza:  
La IA analiza radiografías, resonancias o escáneres para detectar posibles anomalías como tumores, fracturas o enfermedades pulmonares.

- Por qué la IA tiene implantación relevante en este sector:  
La sanidad genera grandes cantidades de datos médicos que requieren análisis rápido y preciso. La IA ayuda a procesar esa información y apoyar a los profesionales sanitarios.

- Beneficios que aporta:  
  - Diagnósticos más rápidos  
  - Mayor precisión en la detección de enfermedades  
  - Apoyo a los médicos en la toma de decisiones  
  - Reducción de errores humanos

---

### Sector 2
- Nombre del sector:  
Banca y servicios financieros

- Tipo de empresa/servicio:  
Bancos, fintech, plataformas de pago y empresas de servicios financieros.

- Aplicación de IA:  
Detección de fraude en transacciones bancarias.

- Qué tarea mejora o automatiza:  
Los sistemas de IA analizan patrones de comportamiento de los usuarios y detectan operaciones sospechosas o fraudulentas.

- Por qué la IA tiene implantación relevante en este sector:  
Las entidades financieras manejan millones de transacciones cada día y necesitan herramientas automáticas capaces de detectar anomalías en tiempo real.

- Beneficios que aporta:  
  - Mayor seguridad en las transacciones  
  - Reducción de fraudes  
  - Análisis automático de grandes volúmenes de datos  
  - Protección del cliente

---

### Sector 3
- Nombre del sector:  
Comercio electrónico

- Tipo de empresa/servicio:  
Tiendas online, marketplaces y plataformas de venta digital.

- Aplicación de IA:  
Sistemas de recomendación de productos.

- Qué tarea mejora o automatiza:  
La IA analiza el historial de navegación y compras de los usuarios para recomendar productos personalizados.

- Por qué la IA tiene implantación relevante en este sector:  
Las plataformas de comercio electrónico manejan grandes cantidades de datos de clientes y necesitan ofrecer experiencias personalizadas para mejorar las ventas.

- Beneficios que aporta:  
  - Mejora de la experiencia del usuario  
  - Incremento de las ventas  
  - Personalización del contenido  
  - Mayor fidelización de clientes

---

## 3) Lenguajes de programación en IA

### Lenguaje 1
- Nombre:  
Python

- Uso principal en IA:  
Desarrollo de modelos de aprendizaje automático, análisis de datos, procesamiento del lenguaje natural y visión artificial.

- Ventajas:  
  - Sintaxis sencilla  
  - Gran número de librerías especializadas (TensorFlow, PyTorch, Scikit-learn)  
  - Amplia comunidad de desarrolladores

- Ejemplos de uso:  
Sistemas de recomendación, análisis de datos médicos, chatbots o modelos predictivos.

---

### Lenguaje 2
- Nombre:  
R

- Uso principal en IA:  
Análisis estadístico y modelado predictivo.

- Ventajas:  
  - Herramientas muy potentes para estadística  
  - Gran capacidad de visualización de datos  
  - Muy usado en investigación y análisis de datos

- Ejemplos de uso:  
Investigación médica, análisis financiero o estudios estadísticos.

---

### Lenguaje 3
- Nombre:  
Java

- Uso principal en IA:  
Desarrollo de aplicaciones empresariales que integran sistemas de inteligencia artificial.

- Ventajas:  
  - Gran estabilidad  
  - Alto rendimiento  
  - Buena integración con sistemas empresariales

- Ejemplos de uso:  
Plataformas bancarias, sistemas de detección de fraude o aplicaciones corporativas.

---

### Lenguaje 4
- Nombre:  
C++

- Uso principal en IA:  
Desarrollo de sistemas que requieren alto rendimiento y procesamiento en tiempo real.

- Ventajas:  
  - Gran velocidad de ejecución  
  - Control detallado de la memoria  
  - Muy eficiente para cálculos complejos

- Ejemplos de uso:  
Robótica, procesamiento avanzado de imágenes o vehículos autónomos.

---

## 4) Relación entre sectores, tipo de IA y lenguaje

| Sector | Aplicación de IA | Tipo de IA/técnica | Lenguaje recomendado | Justificación |
|--------|------------------|--------------------|----------------------|---------------|
| Sanidad | Análisis de imágenes médicas | Visión artificial / Deep Learning | Python | Tiene librerías especializadas para análisis de imágenes y modelos de aprendizaje profundo |
| Banca | Detección de fraude | Machine Learning / detección de anomalías | Java / Python | Permiten analizar grandes volúmenes de transacciones y se integran bien con sistemas bancarios |
| Comercio electrónico | Recomendación de productos | Sistemas de recomendación / Machine Learning | Python | Facilita el análisis de comportamiento del usuario y el desarrollo de modelos predictivos |

---


## 5) Diagrama (Mermaid)

```mermaid
graph TD

A[Inteligencia Artificial] --> B[Sanidad]
A --> C[Banca]
A --> D[Comercio Electrónico]

B --> B1[Análisis de imágenes médicas]
B --> B2[Técnica: Visión artificial / Deep Learning]
B --> B3[Lenguaje: Python]

C --> C1[Detección de fraude]
C --> C2[Técnica: Machine Learning / Detección de anomalías]
C --> C3[Lenguaje: Java / Python]

D --> D1[Sistema de recomendación de productos]
D --> D2[Técnica: Machine Learning]
D --> D3[Lenguaje: Python]
---

## 6) Riesgos y mitigación

- Riesgo 1:  
Sesgos en los datos utilizados para entrenar los modelos de IA, lo que puede provocar decisiones incorrectas o injustas.

- Mitigación 1:  
Realizar revisión y limpieza de datos, además de auditorías periódicas del modelo.

- Riesgo 2:  
Problemas de privacidad al manejar datos sensibles de usuarios o pacientes.

- Mitigación 2:  
Aplicar técnicas de anonimización de datos y cumplir con las normativas de protección de datos.

---

## 7) Conclusión

- Qué sectores destacan más:  
Sectores como la sanidad, la banca y el comercio electrónico destacan por el uso intensivo de datos y la necesidad de analizarlos de forma rápida y eficiente.

- Qué lenguajes aparecen con más frecuencia:  
Python es el lenguaje más utilizado en inteligencia artificial, aunque también se utilizan Java, R y C++ dependiendo del tipo de aplicación.

- Qué importancia tiene esto para DAW/DAM:  
Conocer cómo funciona la inteligencia artificial y qué lenguajes se utilizan permite a los desarrolladores integrar servicios inteligentes en aplicaciones web y móviles, algo cada vez más demandado en el mercado laboral.

## 8) Fuentes oficiales (mín. 2)
- Fuente 1 (sectores / aplicación IA):
- Fuente 2 (lenguajes / ecosistema técnico):
