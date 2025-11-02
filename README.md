# Machine Learning Course Repository

This repository contains comprehensive learning materials, practical exercises, and datasets for a Machine Learning course. The content is organized into 6 sessions (Pertemuan/Pert) covering fundamental to advanced machine learning concepts.

## 📚 Course Structure

### Session 1: Introduction to Machine Learning
**Directory:** `Pert1/`

- **Topics:** Introduction to Machine Learning concepts and fundamentals
- **Materials:** 
  - Lecture slides (`01_ML_pengantar_ml.pdf`)
  - Practical guide (`praktikum01_ml.pdf`)
  - Report template (`template_laporan.docx`)
- **Dataset:** Bike Sharing Dataset
  - `day.csv` - Daily aggregated bike sharing data (731 days)
  - `hour.csv` - Hourly aggregated bike sharing data (17,379 hours)
  - Source: Capital Bikeshare system, Washington D.C. (2011-2012)
- **Applications:** Regression analysis, event detection, anomaly detection

### Session 2: Statistics and Probability
**Directory:** `Pert2/`

- **Topics:** Statistical foundations and probability theory for ML
- **Materials:** 
  - Lecture slides (`02_ML_statprob3.pdf`)
  - Practical guide (`praktikum02_ml.pdf`)
- **Dataset:** 
  - `500_Person_Gender_Height_Weight_Index.csv` - Demographic and health data

### Session 3: Linear Regression
**Directory:** `Pert3/`

- **Topics:** Linear regression models and analysis
- **Materials:** 
  - Lecture slides (`03_ML_regresi_linear.pdf`)
  - Practical guide (`praktikum03_ml_fix.pdf`)
- **Datasets:**
  - `hbat_customer.xlsx` - Customer behavior analysis data
  - `socr.csv` - Statistical analysis dataset
  - `stunting_wasting_dataset.csv` - Health and nutrition data

### Session 4: Logistic Regression
**Directory:** `Pert4/`

- **Topics:** Classification using logistic regression
- **Materials:** 
  - Lecture slides (`04_ML_regresi_logistik.pdf`)
  - Practical guide (`praktikum04_ml.pdf`)
- **Dataset:**
  - `calonpembelimobil.csv` - Car purchase prediction dataset

### Session 5: Decision Trees
**Directory:** `Pert5/`

- **Topics:** Decision tree algorithms and classification
- **Materials:** 
  - Lecture slides (`05_ML_decision_tree.pdf`)
  - Practical guide (`praktikum05_ml.pdf`)
  - Jupyter notebook (`decision_tree.ipynb`)
- **Dataset:**
  - `Iris.csv` - Classic Iris flower classification dataset
- **Implementation:** Hands-on implementation using scikit-learn

### Session 6: Support Vector Machines (SVM)
**Directory:** `Pert6/`

- **Topics:** Support Vector Machines for classification and regression
- **Materials:** 
  - Lecture slides (`06_ML_svm.pdf`)
  - Practical guide (`praktikum06.pdf`)

## 💻 Practical Exercises

### Praktikum (Practical Sessions)
**Directory:** `Praktek/`

#### Pertemuan 1
- **Location:** `Praktek/Pertemuan1/`
- **Notebooks:** `notebooks/praktikum01.ipynb`
- **Data:** Bike sharing datasets (day.csv, hour.csv, latihan01.csv)

#### Pertemuan 2
- **Location:** `Praktek/Pertemuan2/`
- **Notebooks:** `notebooks/praktikum02.ipynb`
- **Data:** Gender, height, weight, and BMI index dataset

## 🗂️ Repository Structure

```
Machine-Learning/
├── Pert1/                      # Session 1: ML Introduction
│   ├── 01_ML_pengantar_ml.pdf
│   ├── praktikum01_ml.pdf
│   ├── day.csv
│   ├── hour.csv
│   ├── Readme.txt
│   └── template_laporan.docx
├── Pert2/                      # Session 2: Statistics & Probability
│   ├── 02_ML_statprob3.pdf
│   ├── praktikum02_ml.pdf
│   └── 500_Person_Gender_Height_Weight_Index.csv
├── Pert3/                      # Session 3: Linear Regression
│   ├── 03_ML_regresi_linear.pdf
│   ├── praktikum03_ml_fix.pdf
│   ├── hbat_customer.xlsx
│   ├── socr.csv
│   └── stunting_wasting_dataset.csv
├── Pert4/                      # Session 4: Logistic Regression
│   ├── 04_ML_regresi_logistik.pdf
│   ├── praktikum04_ml.pdf
│   └── calonpembelimobil.csv
├── Pert5/                      # Session 5: Decision Trees
│   ├── 05_ML_decision_tree.pdf
│   ├── praktikum05_ml.pdf
│   ├── decision_tree.ipynb
│   └── Iris.csv
├── Pert6/                      # Session 6: Support Vector Machines
│   ├── 06_ML_svm.pdf
│   └── praktikum06.pdf
└── Praktek/                    # Practical Exercises
    ├── Pertemuan1/
    │   ├── notebooks/
    │   │   └── praktikum01.ipynb
    │   └── data/
    │       ├── day.csv
    │       ├── hour.csv
    │       └── latihan01.csv
    └── Pertemuan2/
        ├── notebooks/
        │   └── praktikum02.ipynb
        └── data/
            └── 500_Person_Gender_Height_Weight_Index.csv
```

## 📊 Datasets Overview

### 1. Bike Sharing Dataset
- **Files:** `day.csv`, `hour.csv`
- **Source:** Capital Bikeshare, Washington D.C.
- **Period:** 2011-2012
- **Features:** Weather conditions, season, temperature, humidity, wind speed, user counts
- **Use Cases:** Regression, time series analysis, anomaly detection

### 2. Health and Demographics
- **Files:** `500_Person_Gender_Height_Weight_Index.csv`, `stunting_wasting_dataset.csv`
- **Features:** Gender, height, weight, BMI, health indicators
- **Use Cases:** Classification, health analytics

### 3. Iris Dataset
- **File:** `Iris.csv`
- **Description:** Classic multi-class classification dataset
- **Features:** Sepal length, sepal width, petal length, petal width
- **Classes:** 3 species of Iris flowers

### 4. Business Datasets
- **Files:** `calonpembelimobil.csv`, `hbat_customer.xlsx`
- **Use Cases:** Customer behavior analysis, purchase prediction

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Key Libraries:**
  - pandas - Data manipulation and analysis
  - numpy - Numerical computing
  - scikit-learn - Machine learning algorithms
  - matplotlib - Data visualization
- **Tools:**
  - Jupyter Notebook - Interactive development environment

## 📖 Learning Objectives

By completing this course, students will:

1. ✅ Understand fundamental machine learning concepts and terminology
2. ✅ Apply statistical methods for data analysis
3. ✅ Implement linear and logistic regression models
4. ✅ Build and evaluate decision tree classifiers
5. ✅ Utilize Support Vector Machines for classification
6. ✅ Work with real-world datasets and practical problems
7. ✅ Use Python and scikit-learn for machine learning tasks

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- Required libraries: pandas, numpy, scikit-learn, matplotlib

### Installation

```bash
# Clone the repository (replace with your repository URL)
git clone <your-repository-url>
cd Machine-Learning

# Install required packages
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Running the Notebooks

```bash
# Launch Jupyter Notebook
jupyter notebook

# Navigate to the desired session folder and open the .ipynb files
```

## 📝 Course Workflow

1. **Study Materials:** Review the PDF lecture slides for each session
2. **Understand Theory:** Read the practical guides (`praktikum*.pdf`)
3. **Hands-on Practice:** Work through the Jupyter notebooks
4. **Apply Knowledge:** Experiment with the provided datasets
5. **Document Learning:** Use the report template for assignments

## 🤝 Contributing

This is an educational repository. If you find any issues or have suggestions for improvements, feel free to:
- Open an issue
- Submit a pull request
- Contact the repository maintainer

## 📧 Contact

For questions or additional information, please refer to the course instructor or open an issue in this repository.

## 📜 License

Please refer to individual dataset licenses. The Bike Sharing Dataset requires citation:

```
Hadi Fanaee-T and João Gama, "Event labeling combining ensemble detectors and background knowledge", 
Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, 
doi:10.1007/s13748-013-0040-3.
```

---

**Note:** This repository is part of a Machine Learning course and is intended for educational purposes.
