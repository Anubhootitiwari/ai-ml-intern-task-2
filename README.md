
# Titanic Data Cleaning Task

## ✅ Project Overview
This project performs **data preprocessing** on the Titanic dataset to prepare it for machine learning. The steps include:
- Handling missing values
- Removing unnecessary columns
- Encoding categorical variables
- Saving the cleaned dataset as `titanic_cleaned.csv`

---

## 📂 Files Included
- `titanic_preprocessing.ipynb` → Jupyter Notebook with the data cleaning code
- `requirements.txt` → List of Python dependencies
- `README.md` → Project documentation (this file)

---

## ▶️ Step-by-Step Instructions

### **Step 1: Download the ZIP**
Download and extract the provided `titanic_task_final.zip` file.

---

### **Step 2: Add the Titanic Dataset**
- Place the original dataset file `titanic.csv` in the same folder as the notebook.
- You can download it from [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data) (or use your own copy).

---

### **Step 3: Install Dependencies**
Open a terminal/command prompt in the extracted folder and run:
```bash
pip install -r requirements.txt
```

---

### **Step 4: Open the Notebook**
- Launch Jupyter Notebook or open the file in VS Code.
- Open `titanic_preprocessing.ipynb`.

---

### **Step 5: Run the Notebook**
- Execute all cells in the notebook.
- The code will:
  - Fill missing values in `Age` and `Embarked`
  - Drop the `Cabin` column
  - Encode `Sex` and `Embarked` using one-hot encoding
  - Save the cleaned dataset as `titanic_cleaned.csv`

---

### **Step 6: Verify the Output**
- After running the notebook, check for `titanic_cleaned.csv` in the same folder.
- Use this cleaned dataset for your machine learning tasks.

---

## ✅ Requirements
- Python 3.x
- Jupyter Notebook
- pandas
- numpy

Install them using:
```bash
pip install -r requirements.txt
```

---
