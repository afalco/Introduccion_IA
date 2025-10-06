# Introducción a la Inteligencia Artificial — Proyecto de Curso

Este directorio contiene los materiales del módulo **"Introducción a la IA"** del  
Máster en Inteligencia Artificial y Fabricación Aditiva (ESET–CEU UCH).

---

## 📂 Contenido

| Archivo | Descripción |
|----------|--------------|
| `Presentacion_revisada.tex` | Presentación Beamer del curso, versión adaptada a nivel inicial. |
| `IA_intro_colab.ipynb` | Cuaderno Jupyter/Colab para los estudiantes. Incluye prácticas guiadas sin código prellenado. |
| `IA_intro_colab_SOLUCIONES.ipynb` | Versión con soluciones comentadas, para docentes. |
| `muestra.png` | Imagen de ejemplo empleada en los notebooks. |
| `README_Proyecto_IA.md` | Este documento. |

---

## 🎯 Objetivo del curso

Aprender los fundamentos de la Inteligencia Artificial mediante ejemplos visuales y prácticos,
sin requerir conocimientos previos avanzados de matemáticas o programación.

El curso se centra en:
- Procesamiento de imágenes y visión artificial.
- Principios básicos del aprendizaje automático (Machine Learning).
- Redes neuronales sencillas (Perceptrón, MLP).
- Proyecto final de clasificación o detección visual aplicada a fabricación aditiva.

---

## 🧩 Estructura del proyecto final

1. **Definición del problema**  
   Ejemplo: clasificación de piezas con o sin defectos en impresión 3D.

2. **Preparación de datos**  
   - Carpeta `ok/` → imágenes sin defecto  
   - Carpeta `defecto/` → imágenes con defecto  

3. **Entrenamiento y evaluación**  
   - Modelos sugeridos: `LogisticRegression`, `MLPClassifier`.  
   - Métricas: *accuracy*, *confusion matrix*, *precision/recall*.  

4. **Informe y entrega**  
   Documento breve (2–4 páginas) con:
   - Descripción del problema.  
   - Metodología y resultados.  
   - Visualizaciones.  
   - Conclusiones y posibles mejoras.

---

## 🧮 Evaluación

Ver la **rúbrica incluida al final de los notebooks** (`IA_intro_colab*.ipynb`):

| Criterio | Peso |
|-----------|------|
| Comprensión del problema | 20 % |
| Metodología y proceso | 30 % |
| Resultados y métricas | 30 % |
| Comunicación y trabajo en equipo | 20 % |

---

## ⚙️ Ejecución en Google Colab

1. Sube los ficheros a tu propio repositorio o Drive.  
2. Abre el cuaderno en Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)  
3. Ejecuta celda por celda (usa las instrucciones incluidas en el notebook).  
4. Guarda tus resultados y gráficas en un nuevo notebook “Proyecto_final_IA.ipynb”.

---

## 🧠 Créditos

**Autores:**  
Antonio Falcó Montesinos, Juan Pardo  
Departamento de Matemáticas, Física y Ciencias Tecnológicas  
Universidad CEU Cardenal Herrera (ESET–CEU UCH)
