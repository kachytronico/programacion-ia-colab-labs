# Programación de IA — Colab Labs

> Portfolio curado de notebooks de Programación de IA: Python, preprocesamiento de datos, aprendizaje automático y visión por computador.

---

## Sobre este repositorio

Este repositorio es un portfolio de aprendizaje construido a partir de notebooks seleccionados, creados durante mi formación en el **Curso de Especialización en Inteligencia Artificial y Big Data**.

**Qué es este repositorio:**
- Una colección curada de trabajos prácticos de la asignatura de Programación de IA.
- Notebooks limpios, contextualizados y documentados para mostrar proceso de aprendizaje, razonamiento técnico y toma de decisiones.
- Evidencia técnica de mi progreso en Python aplicado a IA.

**Qué NO es este repositorio:**
- No es un repositorio oficial del curso ni de ningún centro educativo.
- No es un volcado sin editar de tareas o entregas de examen.
- No contiene materiales del profesorado, enunciados privados ni contenido protegido.

Los notebooks se limpian, renombran y documentan antes de publicarse, para que sean comprensibles tanto para lectores técnicos como no técnicos.

---

## Qué muestra

- Flujo de trabajo con Python y Google Colab.
- Análisis exploratorio de datos y preprocesamiento.
- Reducción de dimensionalidad y clustering.
- Aprendizaje supervisado y pseudo-etiquetado.
- Visión por computador con deep learning.
- Evaluación e interpretación de modelos.
- Explicación clara de decisiones y limitaciones.

---

## Notebooks destacados

<!-- Actualiza los enlaces "Open in Colab" una vez que los notebooks estén subidos a GitHub -->

| Notebook | Área | Técnicas | Estado | Open in Colab |
|---|---|---|---|---|
| [Energy Economics Clustering](notebooks/01_energy_economics_clustering/) | Clustering / ML no supervisado | Preprocesamiento, validación temporal, correlación, PCA, KMeans, clustering aglomerativo, pseudo-etiquetado, modelo supervisado | Pendiente — notebook por añadir | *(badge disponible al subir el notebook)* |
| [Neumon-IA Image Classification](notebooks/02_neumon_ia_image_classification/) | Visión por computador | Inspección y limpieza de dataset, split estratificado, DataBlock, modelo base, optimización, comparación de arquitecturas, matriz de confusión, análisis de errores críticos | Pendiente — notebook por añadir | *(badge disponible al subir el notebook)* |
| [Retinal Fundus Image Classification](notebooks/03_retinal_fundus_image_classification/) | Visión por computador | Modelo baseline, búsqueda de learning rate, early stopping, data augmentation, matriz de confusión, métrica personalizada para falsos positivos | Pendiente — notebook por añadir | *(badge disponible al subir el notebook)* |

> **Cómo añadir el badge Open in Colab:** Una vez que el notebook esté en GitHub, usa este patrón:
>
> ```markdown
> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kachytronico/programacion-ia-colab-labs/blob/main/notebooks/<carpeta>/<nombre>.ipynb)
> ```

---

## Cómo leer cada notebook

Cada notebook sigue esta estructura de lectura recomendada:

1. **Objetivo** — Qué problema se aborda y por qué.
2. **Dataset / fuente** — Origen y características principales de los datos.
3. **Preprocesamiento** — Limpieza, transformaciones y decisiones sobre los datos.
4. **Modelo o técnica** — Justificación de la elección y configuración.
5. **Evaluación** — Métricas, visualizaciones y comparaciones.
6. **Interpretación** — Qué significan los resultados en contexto.
7. **Limitaciones** — Qué no resuelve este enfoque y por qué.
8. **Qué aprendí** — Reflexión honesta sobre el proceso.

---

## Cómo ejecutar

Los notebooks están diseñados para abrirse en **Google Colab**.

Para abrir cualquier notebook directamente desde GitHub:

```
https://colab.research.google.com/github/kachytronico/programacion-ia-colab-labs/blob/main/<ruta-al-notebook>.ipynb
```

**Patrón del badge "Open in Colab"** (adaptar para cada notebook):

```markdown
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kachytronico/programacion-ia-colab-labs/blob/main/notebooks/<carpeta>/<nombre>.ipynb)
```

GitHub renderiza los notebooks de forma estática. Para ejecutarlos, Google Colab es la opción recomendada.

Consulta [`docs/COLAB_GUIDE.md`](docs/COLAB_GUIDE.md) para más detalles.

---

## Ética, privacidad y límites

- No se publican datos personales ni sensibles.
- No se incluyen materiales privados del curso.
- Los notebooks relacionados con salud son herramientas educativas, no herramientas médicas.
- Los resultados son ejercicios de aprendizaje, no modelos de producción.
- Los datasets utilizados son públicos, sintéticos o de uso claramente permitido.

Consulta [`docs/ETHICS_AND_PRIVACY.md`](docs/ETHICS_AND_PRIVACY.md) para más información.

---

## Relación con mi perfil profesional

Este repositorio apoya mi posicionamiento profesional en las siguientes áreas:

- Formación en IA y Big Data.
- Python y ML aplicado.
- Capacidad para documentar y explicar trabajo técnico con claridad.
- Interés en educación, salud e impacto social.
- Formación como futuro formador en IA aplicada.

El objetivo es mostrar no solo que puedo implementar técnicas, sino que entiendo el proceso, las limitaciones y el contexto de aplicación.

---

## English summary

This repository is a curated learning portfolio built from selected notebooks created during an official AI & Big Data specialization. It focuses on the Programming of AI track: Python, Google Colab, data preprocessing, unsupervised and supervised learning, computer vision, and model evaluation. The notebooks are cleaned, documented and contextualized to show learning process and technical reasoning — not raw assignment submissions. This is not an official course repository. It supports my professional positioning as a future applied AI trainer, with a focus on clarity, honest documentation and responsible use of data.

---

## Estructura del repositorio

```
programacion-ia-colab-labs/
├── README.md
├── LICENSE
├── .gitignore
├── notebooks/
│   ├── README.md
│   ├── 01_energy_economics_clustering/
│   ├── 02_neumon_ia_image_classification/
│   └── 03_retinal_fundus_image_classification/
├── docs/
│   ├── COURSE_CONTEXT.md
│   ├── NOTEBOOK_TEMPLATE.md
│   ├── PUBLISHING_CHECKLIST.md
│   ├── ETHICS_AND_PRIVACY.md
│   └── COLAB_GUIDE.md
└── assets/
    └── screenshots/
```

---

*Portfolio de aprendizaje personal — no es un repositorio oficial del curso.*
