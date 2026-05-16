# 📊 ING Hubs Datathon Project

## 🧠 About the Project

This project was developed as part of the **ING Hubs Datathon** and aims to predict **customer churn** using customer data.

The goal is to improve model performance through **data analysis** and **feature engineering techniques**.

---

## 📁 Dataset

The project uses the following datasets:

* `customers.csv` → Customer demographic information
* `customer_history.csv` → Customer transaction history
* `referance_data.csv` → Training labels
* `referance_data_test.csv` → Test dataset
* `sample_submission.csv` → Sample submission format

### ⚠️ Notes on Data

* `work_sector`:

  * Missing values are **intentionally left as is**
  * Reason: Students and unemployed customers do not have sector information

* `churn`:

  * It is normal for this column to be empty in the test dataset (no labels provided)

---

## ⚙️ Technologies Used

* Python 🐍
* NumPy
* Pandas
* LightGBM ⚡
* Scikit-learn

---

## 🔍 Project Workflow

1. **Data Loading**
2. **Exploratory Data Analysis (EDA)**
3. **Missing Value Analysis**
4. **Feature Engineering**
5. **Model Training (LightGBM)**
6. **Cross Validation (StratifiedKFold)**
7. **Prediction & Submission Generation**

---

## 🚀 Installation

To run this project locally:

```bash
git clone https://github.com/your-username/project-name.git
cd project-name
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the notebook to execute the full pipeline:

```bash
jupyter notebook ing-hubs-datathon.ipynb
```

---

## 📈 Model

The model used in this project is **LightGBM**.

### Advantages:

* Fast training ⚡
* High performance
* Scales well with large datasets

---

## 📤 Output

* Feature engineered dataset:

  * `customers_with_features.csv`

* Submission file:

  * `submission.csv` (can be generated)

---

## 📌 Notes

This project was developed for educational and competition purposes.
