# 🤖 Introducción a la Inteligencia Artificial

Materiales del curso **Introducción a la IA**, impartido dentro del  
**Máster de Formación Permanente en Inteligencia Artificial y Fabricación Aditiva para el Desarrollo de Producto**  
(Universidad CEU Cardenal Herrera, ESET).

---

## 🎯 Objetivos del curso
- Comprender los fundamentos del **aprendizaje automático** y sus principales algoritmos.  
- Adquirir destrezas en el **preprocesado, análisis y visualización** de datos.  
- Implementar modelos supervisados y no supervisados con **scikit-learn** y **Keras**.  
- Evaluar y comparar modelos mediante **métricas de rendimiento**.  
- Aplicar técnicas de IA a **casos reales de ingeniería y fabricación aditiva**.  

---

## 🧰 Requisitos

Instala las dependencias con **pip**:
```bash
pip install -r requirements.txt
```

O crea el entorno con **conda**:
```bash
conda env create -f environment.yml
conda activate introIA
```

---

## 📘 Estructura del repositorio
```
Lectura1/             Material teórico inicial
Lectura2/             Aplicaciones y ética
Presentacion/         Diapositivas del curso
notebooks/            Cuadernos prácticos (Python / Colab)
projects/00_template/ Guía y rúbrica del proyecto final
requirements.txt
environment.yml
README.md
```

---

## 🚀 Cuadernos prácticos (Jupyter / Colab)

| Tema | Descripción | Abrir en Colab |
|------|--------------|----------------|
| 01. Introducción a ML | Primer contacto con datasets, entrenamiento y predicción | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/afalco/Introduccion_IA/blob/main/notebooks/01_intro_ml.ipynb) |
| 02. Preprocesado y *feature engineering* | Limpieza, normalización y selección de variables | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/afalco/Introduccion_IA/blob/main/notebooks/02_preprocesado_feature_engineering.ipynb) |
| 03. Modelos lineales | Regresión lineal, logística y regularización | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/afalco/Introduccion_IA/blob/main/notebooks/03_modelos_lineales.ipynb) |
| 04. Árboles y *ensembles* | Árboles de decisión, Random Forest, Gradient Boosting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/afalco/Introduccion_IA/blob/main/notebooks/04_arboles_y_ensambles.ipynb) |
| 05. Selección de modelo y métricas | Validación cruzada, curvas de aprendizaje, ROC/AUC | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/afalco/Introduccion_IA/blob/main/notebooks/05_model_selection_metricas.ipynb) |
| 06. Redes neuronales con Keras | Perceptrón multicapa y clasificación supervisada | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/afalco/Introduccion_IA/blob/main/notebooks/06_redes_neuronales_keras.ipynb) |

> 💡 Los enlaces abren directamente los notebooks en Google Colab.  
> También puedes ejecutarlos localmente con `jupyter lab`.

---

## 🧪 Evaluación

El curso se evalúa mediante:
- **Ejercicios guiados (50%)**  
- **Proyecto final (50%)**, basado en un caso real de ingeniería o fabricación aditiva.  

---

## 🧩 Proyecto final

Consulta la carpeta [`projects/00_template/`](./projects/00_template/)  
donde encontrarás la **guía del proyecto final** y la **rúbrica de evaluación**.

Incluye:
- Estructura recomendada del trabajo  
- Checklist de reproducibilidad  
- Criterios de evaluación  
- Consideraciones éticas  

---

## ⚖️ Ética y uso responsable

Se anima a reflexionar sobre:
- el posible **sesgo de los datos**;  
- la **interpretabilidad de los modelos**;  
- el cumplimiento del **AI Act europeo** y la trazabilidad de los sistemas de IA.

---

## 🧑‍🏫 Autor

**Antonio Falcó Montesinos**  
Departamento de Matemáticas, Física y Ciencias Tecnológicas  
Universidad CEU Cardenal Herrera  
📧 [antonio.falco@uchceu.es](mailto:antonio.falco@uchceu.es)  
🔗 [Repositorio GitHub](https://github.com/afalco/Introduccion_IA)

---

## 🪪 Licencia

Este proyecto se distribuye bajo licencia **MIT**.  
Puedes reutilizar y adaptar los materiales siempre que cites la fuente original.
