# Práctica IA (RA4 · f)

## 1) Caso de uso
- **Tipo de aplicación:** Web de comercio electrónico (tienda online)
- **Problema:** Los usuarios no encuentran fácilmente productos relevantes, lo que reduce las ventas.
- **Usuario:** Clientes que navegan y compran en la tienda online.

## 2) Datos
- **Datos:**  
  - Historial de compras  
  - Clics en productos  
  - Tiempo de navegación  
  - Búsquedas realizadas  
- **Tipo minería:**  
  - Recomendación (basada en clustering y predicción)  
  - Clasificación de usuarios según comportamiento  

## 3) Pipeline
- **Recogida:**  
  Se almacenan datos de interacción del usuario (logs de navegación, clics, compras).

- **Limpieza:**  
  Eliminación de datos duplicados, corrección de valores erróneos y filtrado de datos irrelevantes.

- **Transformación:**  
  Conversión de datos a formato útil (por ejemplo, vectores de características de usuario).

- **Entrenamiento:**  
  Se entrena un modelo de recomendación (ej. filtrado colaborativo o modelo de machine learning).

- **Predicción:**  
  El sistema predice productos que pueden interesar al usuario.

- **Uso:**  
  La app web muestra recomendaciones personalizadas en tiempo real.

## 4) Integración
- **Backend:**  
  API REST que conecta la app con el modelo de IA (por ejemplo, usando Python + Flask o Node.js).

- **Frontend:**  
  Interfaz web que muestra productos recomendados (React, Angular o HTML/CSS/JS).

- **Flujo:**  
  Usuario navega → se envían datos al backend → el modelo genera recomendaciones → se muestran en la web.

## 5) Valor
- **Mejora:**  
  Personalización de la experiencia de usuario y aumento de la satisfacción.

- **Sin IA:**  
  Recomendaciones genéricas iguales para todos los usuarios.

- **Rentabilidad:**  
  Incremento de ventas, mayor tiempo en la web y fidelización del cliente.

## 6) Diagrama

Usuario → App Web → Backend → Modelo IA → Recomendaciones → Usuario

## 7) Riesgos
- **Riesgo 1:**  
  Uso indebido de datos personales  
- **Mitigación 1:**  
  Cumplir con RGPD, anonimizar datos y pedir consentimiento.

- **Riesgo 2:**  
  Recomendaciones incorrectas o sesgadas  
- **Mitigación 2:**  
  Evaluación continua del modelo y ajuste con nuevos datos.

## 8) Fuente
- https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html
