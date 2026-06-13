# Credit Card Fraud Detection

## Objetivo

Crear una landing page profesional de una sola página (One Page) para presentar un proyecto de Inteligencia Artificial enfocado en detección de fraude con tarjetas de crédito.

La página será desplegada en GitHub Pages.

El diseño debe parecer un producto SaaS moderno similar a OpenAI, Stripe o Vercel.

---

## Información del Proyecto

### Dataset

* Dataset original: 21.000.000 transacciones
* Dataset de trabajo: 164.820 transacciones
* Fraudes: 27.470
* No fraude: 137.350
* Ratio utilizado: 5:1

### Variables

* step
* type
* amount
* oldbalanceOrg
* newbalanceOrig
* oldbalanceDest
* newbalanceDest

### Modelos Evaluados

1. Logistic Regression
2. Random Forest
3. XGBoost
4. Red Neuronal

### Modelo Ganador

Red Neuronal

Métricas:

* Recall: 83.16%
* Precision: 16.76%
* F1 Score: 0.2790
* Accuracy: 28.35%

Resultados:

* Fraudes detectados: 4569
* Fraudes perdidos: 925
* Clientes afectados: 22695
* Business Score: -1190.75

### Business Score

TP − (FP × 0.05) − (FN × 5)

El costo de perder un fraude es 100 veces mayor que generar una falsa alarma.

### Hallazgos

Las variables más importantes fueron:

1. oldbalanceDest
2. newbalanceOrig
3. oldbalanceOrg
4. newbalanceDest
5. amount

### Conclusiones

* La Red Neuronal fue el mejor modelo técnico y de negocio.
* Detectó más del 83% de los fraudes.
* No presentó overfitting.
* Los balances de cuenta fueron los factores más importantes.
* Detectar un fraude es más importante que evitar una falsa alarma.

---

## Requerimientos Frontend

Generar un único archivo index.html.

No utilizar React.

No utilizar Angular.

No utilizar Vue.

Solo:

* HTML
* CSS
* Vanilla JavaScript
* Chart.js

---

## Secciones

1. Hero
2. Dataset
3. Pipeline
4. Comparativa de Modelos
5. Modelo Ganador
6. Impacto de Negocio
7. Conclusiones
8. Chat IA

---

## Diseño

Tema oscuro.

Inspiración:

* OpenAI
* Stripe
* Vercel

Colores:

* Fondo oscuro
* Morado principal
* Tarjetas modernas
* Responsive móvil y escritorio

---

## Chat IA

Agregar una sección al final.

Preparar integración con backend FastAPI.

Endpoint:

POST /chat

Ejemplo:

{
"question": "¿Por qué ganó la Red Neuronal?"
}

Respuesta:

{
"answer": "..."
}

La URL del backend debe quedar configurable mediante una constante JavaScript.
