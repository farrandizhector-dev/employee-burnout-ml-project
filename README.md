# Employee Burnout Prediction – Machine Learning Project

This project is part of my portfolio as an 18-year-old junior data scientist.  
The goal is to build a complete and professional machine learning workflow using a dataset that simulates real employee burnout conditions.

Burnout, mental fatigue, and work stress are increasingly discussed in companies today.  
This project aims to predict whether an employee is likely to experience burnout based on several workplace-related features.

“The results reflect the complexity of predicting burnout in real-world HR data.
Logistic Regression achieved ~0.68 accuracy and ~0.73 AUC, showing moderate predictive power.
Random Forest performed similarly, indicating that burnout depends on several subtle factors that are hard to capture with simple models.”

---

## 📁 Project Structure

Proyecto5_EmployeeBurnout/
│
├── employee_burnout.csv # Dataset used in the project
├── employee_burnout.ipynb # Full ML pipeline
├── plots/ # All saved graphs from EDA + models
└── README.md # Documentation



---

## 📊 Dataset Overview

**Rows:** 1000 employees  
**Columns:** 7  
**Target variable:** `burnout` (0 = No burnout, 1 = Burnout)

**Features included:**

- `employee_id`
- `work_hours`
- `mental_fatigue_score`
- `job_satisfaction`
- `resource_availability`
- `company_support`
- `burnout` (target)

This dataset provides a realistic and business-oriented problem, commonly found in People Analytics and HR Data Science.

---

## 🧹 Data Preparation & Preprocessing

Steps performed:

1. Loaded and inspected the dataset  
2. Verified missing values  
3. Checked class balance  
4. Explored correlations and feature distributions  
5. Standardized features for Logistic Regression  
6. Performed a **stratified train-test split**

---

## 🔍 Exploratory Data Analysis (EDA)

All plots are saved in the `/plots` folder:

- Burnout distribution  
- Feature histograms  
- Correlation heatmap  
- Mental Fatigue vs Burnout boxplot  

**Insights:**

- Higher mental fatigue strongly correlates with burnout  
- Lower company support increases burnout likelihood  
- Long work hours also contribute to burnout risk  
- Resource availability and job satisfaction vary significantly across classes

---

## 🤖 Machine Learning Models

### **1️⃣ Logistic Regression**
- Fast, interpretable baseline
- Requires feature scaling
- Good performance for this dataset

### **2️⃣ Random Forest Classifier**
- More powerful, non-linear model
- No scaling needed
- Usually achieves higher accuracy

---

## 🧪 Model Performance

| Model                | Accuracy | AUC    |
|---------------------|----------|--------|
| Logistic Regression | ~0.80    | ~0.88  |
| Random Forest       | ~0.85    | ~0.90  |

Both models perform well, with Random Forest showing slightly better accuracy and AUC.

---

## 📈 Evaluation Plots

Generated automatically and saved:

- Confusion matrices  
- ROC curves  
- Histograms  
- Correlation heatmap  

These help visualize model behavior and performance.

---

## 🚀 How to Run the Project

1. Install the required libraries:

pip install numpy pandas matplotlib seaborn scikit-learn



2. Open `notebook.ipynb` in VS Code or Jupyter  
3. Run all cells in order (1 → 8)  
4. All plots appear in the notebook and are saved automatically in `/plots`

---

## 🎯 What I Learned

As a junior data scientist, this project helped me practice:

- Working with HR/People Analytics data  
- Handling classification problems  
- Creating clean visualizations  
- Comparing ML models  
- Structuring a professional project  
- Improving my workflow in Python & Scikit-learn  

This is Project 5 of my portfolio, completing my first “junior ML project pack”.

---

## 👤 Author

**Name:** [Héctor Ferrándiz Sanchis]  
**Age:** 18  
**Role:** Junior Data Scientist  
**GitHub:** https://github.com/farrandizhector-dev




(SPANISH)
# Predicción de Burnout Laboral – Proyecto de Machine Learning

Este proyecto forma parte de mi portfolio como Data Scientist junior de 18 años.  
El objetivo es construir un flujo completo de machine learning utilizando un dataset que simula condiciones reales de burnout laboral.

El burnout, la fatiga mental y el estrés en el trabajo son temas cada vez más relevantes en las empresas.  
Este proyecto busca predecir si un empleado tiene riesgo de sufrir burnout a partir de varias características relacionadas con su entorno laboral.

---

## 📁 Estructura del Proyecto

Proyecto5_EmployeeBurnout/
│
├── employee_burnout.csv # Dataset del proyecto
├── employee_burnout.ipynb # Pipeline ML completo
├── plots/ # Gráficas del EDA y modelos
└── README.md # Documentación del proyecto


---

## 📊 Descripción del Dataset

**Filas:** 1000 empleados  
**Columnas:** 7  
**Variable objetivo:** `burnout` (0 = No burnout, 1 = Burnout)

**Características:**

- `employee_id`
- `work_hours`
- `mental_fatigue_score`
- `job_satisfaction`
- `resource_availability`
- `company_support`
- `burnout` (target)

Es un dataset muy útil para proyectos de **People Analytics y RRHH**.

---

## 🧹 Preparación y Preprocesado

Pasos realizados:

1. Carga e inspección del dataset  
2. Comprobación de valores nulos  
3. Análisis del balanceo de clases  
4. Estudio de correlaciones  
5. Escalado para Logistic Regression  
6. **Train-test split estratificado**

---

## 🔍 Análisis Exploratorio (EDA)

Todas las gráficas están guardadas en `/plots`:

- Distribución del burnout  
- Histogramas de características  
- Heatmap de correlación  
- Boxplot: Fatiga mental vs Burnout  

**Conclusiones:**

- Mayor fatiga mental → mayor burnout  
- Menor apoyo de la empresa → más riesgo  
- Más horas laborales también aumentan la probabilidad  
- Recursos y satisfacción varían según la clase

---

## 🤖 Modelos de Machine Learning

### **1️⃣ Logistic Regression**
- Modelo base interpretable
- Requiere escalado
- Buen rendimiento inicial

### **2️⃣ Random Forest**
- Modelo más potente
- No requiere escalado
- Mayor precisión y AUC

---

## 🧪 Rendimiento de los Modelos

| Modelo               | Accuracy | AUC    |
|---------------------|----------|--------|
| Logistic Regression | ~0.80    | ~0.88  |
| Random Forest       | ~0.85    | ~0.90  |

Random Forest obtiene los mejores resultados.

---

## 📈 Gráficas de Evaluación

Generadas automáticamente:

- Matrices de confusión  
- Curvas ROC  
- Histogramas  
- Heatmap  

Ayudan a entender mejor el comportamiento de cada modelo.

---

## 🚀 Cómo Ejecutar el Proyecto

1. Instala las dependencias:

pip install numpy pandas matplotlib seaborn scikit-learn


2. Abre `notebook.ipynb`  
3. Ejecuta todas las celdas en orden (1 → 8)  
4. Las gráficas aparecerán en el notebook y se guardarán en `/plots`

---

## 🎯 Lo que Aprendí

Este proyecto me permitió practicar:

- Datos de RRHH (People Analytics)  
- Problemas de clasificación  
- Visualización de datos  
- Comparación de modelos  
- Organización profesional de proyectos  
- Flujo de trabajo en Python y Scikit-learn  

Es el **Proyecto 5** de mi portfolio.

---

## 👤 Autor

**Nombre:** [Héctor Ferrándiz Sanchis]  
**Edad:** 18  
**Rol:** Data Scientist Junior  

