

# 🧬 ML_Cancer_Predict

Predicción de cáncer de utilizando algoritmos de Machine Learning con el conjunto de datos de diagnóstico de cáncer de Wisconsin (WDBC). Este proyecto demuestra un flujo completo de aprendizaje automático, desde el análisis exploratorio hasta la evaluación de modelos, con especial enfoque en la clasificación de tumores como **benignos** o **malignos**.

---

## 📌 Tabla de Contenidos

- [🧠 Objetivo del Proyecto](#-objetivo-del-proyecto)
- [📊 Dataset](#-dataset)
- [⚙️ Tecnologías Usadas](#️-tecnologías-usadas)
- [🧪 Resultados](#-resultados)
- [▶️ Cómo Ejecutarlo](#️-cómo-ejecutarlo)
- [📄 Licencia](#-licencia)
- [✨ Contribuciones](#-contribuciones)
- [📬 Contacto](#-contacto)

---

## 🧠 Objetivo del Proyecto

Desarrollar y evaluar modelos de Machine Learning capaces de clasificar correctamente células tumorales como **malignas** o **benignas**, facilitando así diagnósticos tempranos y más precisos.

---

## 📊 Dataset

Se utiliza el dataset **Breast Cancer Wisconsin Diagnostic** disponible en `sklearn.datasets`. Contiene 569 instancias con 30 características numéricas calculadas a partir de imágenes digitalizadas de núcleos celulares.

- **Características**: radio, textura, perímetro, área, suavidad, simetría, etc.
- **Clase objetivo**: `diagnosis` → *M* (Maligno), *B* (Benigno)

---

## ⚙️ Tecnologías Usadas

- Python 3.10+
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost
- CatBoost
- Jupyter Notebooks

---

## 🧪 Resultados

Los modelos muestran un alto desempeño, destacando en particular:

| Modelo        | Accuracy | F1-Score |
|---------------|----------|----------|
| XGBoost       | 97.37%   | 96.30    |
| Random Forest | 97.34%   | 96.30    |
| CatBoost      | 96.49%   | 95.00    |

**Mejor resultado - XGBoost:**

```
              precision    recall  f1-score   support

           B       0.96      1.00      0.98        72
           M       1.00      0.93      0.96        42

    accuracy                           0.97       114
   macro avg       0.98      0.96      0.97       114
weighted avg       0.97      0.97      0.97       114
```

> ⚠️ *Los resultados pueden variar ligeramente dependiendo del random state y los hiperparámetros utilizados.*

---

## ▶️ Cómo Ejecutarlo

1. Clona el repositorio:

   ```bash
   git clone https://github.com/borjabarber/ML_Cancer_Predict.git
   cd ML_Cancer_Predict
   ```

2. Instala las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

3. Ejecuta el notebook principal:

   ```bash
   jupyter notebook cancer_prediction.ipynb
   ```

---

## 📄 Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).

---

## ✨ Contribuciones

¡Las contribuciones son bienvenidas! Puedes abrir un *Issue* o enviar un *Pull Request* con mejoras.

---

## 📬 Contacto

📧 borjagbarber@gmail.com 

