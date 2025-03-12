# Predicting Vomitoxin Levels in Crops

## Installation & Setup

To set up and run this project, follow these steps:

### **1. Clone the Repository**
```bash
git clone (https://github.com/knight22-21/ImagoAI)
cd ImagoAI
```

### **2. Create a Virtual Environment (Recommended)**
```bash
python -m venv venv  # Create a virtual environment
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### **3. Install Dependencies**
```bash
pip install -r requirements.txt
```

If `requirements.txt` is not provided, manually install key dependencies:
```bash
pip install numpy pandas scikit-learn tensorflow matplotlib
```

### **4. Run the Jupyter Notebook**
Ensure Jupyter Notebook is installed:
```bash
pip install notebook
```
Launch the notebook:
```bash
jupyter notebook
```
Open `code.ipynb` and execute the cells.

---
## Repository Structure

- **`code.ipynb`** – Main notebook for training and evaluating the MLP model.
- **`TASK-ML-INTERN.csv`** – Dataset used for model training.
- **`Short Report_Predicting Vomitoxin Levels in Crops.pdf`** – Summary of findings, methodology, and results.
- **`README.md`** – Instructions for setting up and running the project.

---
## Notes
- Ensure that all dependencies are installed before running the notebook.
- Modify the data preprocessing steps in `code.ipynb` if working with a different dataset.

For any issues, feel free to raise an issue on GitHub or contact the repository owner.

