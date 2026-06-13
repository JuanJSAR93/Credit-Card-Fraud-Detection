## Project

Credit Card Fraud Detection

Este repositorio contiene una presentación web y un asistente IA para un proyecto académico de detección de fraude financiero mediante Machine Learning y Deep Learning.

---

# Scope

IMPORTANTE:

Trabaja ÚNICAMENTE con archivos contenidos dentro de este repositorio.

NO buscar archivos fuera del directorio raíz.

NO inspeccionar carpetas padre.

NO asumir información externa.

Toda la información necesaria se encuentra dentro de:

* PROJECT_CONTEXT.md
* training_report.json
* FraudDetection_v3_Notebook.pdf

Estos archivos son la única fuente de verdad.

---

# Source of Truth Priority

Cuando exista conflicto entre archivos:

1. PROJECT_CONTEXT.md
2. training_report.json
3. FraudDetection_v3_Notebook.pdf

---

# Frontend Requirements

Generar una landing page profesional.

Tecnologías permitidas:

* HTML
* CSS
* Vanilla JavaScript
* Chart.js

No utilizar:

* React
* Angular
* Vue
* NextJS
* Nuxt
* Svelte

Debe funcionar directamente en GitHub Pages.

---

# Design Requirements

Inspiración visual:

* OpenAI
* Stripe
* Vercel

Características:

* Tema oscuro
* Responsive
* Mobile First
* Animaciones suaves
* Apariencia SaaS moderna

---

# Project Metrics

Dataset original:
21,000,000 transacciones

Dataset trabajo:
164,820 transacciones

Fraudes:
27,470

Modelo ganador:
Red Neuronal

Recall:
83.16%

Fraudes detectados:
4569

Business Score:
-1190.75

---

# AI Chat Section

La landing page debe incluir una sección llamada:

"Pregúntale al Proyecto"

El frontend debe consumir un endpoint configurable:

POST /chat

Variable esperada:

const API_URL = "...";

No implementar backend dentro de este repositorio.

---

# Coding Rules

* Código limpio
* Comentarios mínimos
* HTML semántico
* CSS moderno
* JavaScript modular
* Evitar dependencias innecesarias

---

# Expected Deliverable

Archivo principal:

index.html

Opcional:

styles.css
script.js

Compatible con GitHub Pages sin proceso de build.
