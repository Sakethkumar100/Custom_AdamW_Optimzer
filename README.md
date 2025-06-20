
# 🎓 Student Depression Prediction with Custom AdamW Optimizer

This project is a **Neural Network** model that predicts the likelihood of student depression using a custom implementation of the **AdamW optimizer**. It also explores baseline optimizers like Adam, FTRL, and Adagrad for comparison.

---

## 📂 Files in this Repository
- [**NNFLPROJECT.ipynb**](https://github.com/Sakethkumar100/Custom_AdamW_Optimzer/blob/main/NNFLPROJECT.ipynb) — Jupyter Notebook with:
  - Data exploration & preprocessing
  - Model training with different optimizers
  - Custom AdamW implementation
- [**student_depression_dataset.csv**](https://github.com/Sakethkumar100/Custom_AdamW_Optimzer/blob/main/student_depression_dataset.csv) — Dataset of **27,901 students** and 18 features related to academics, lifestyle, and mental health.
- [**ADAMW_1.docx**](https://github.com/Sakethkumar100/Custom_AdamW_Optimzer/blob/main/ADAMW_1.docx) — Project report detailing:
  - Dataset overview
  - Model architecture
  - Performance metrics and comparisons

---

## 🧠 Model Architecture
- Input Layer — 18 normalized & encoded features
- Hidden Layers — Two hidden layers (32, 16 neurons, ReLU activations)
- Output Layer — Sigmoid activation for binary classification
- Optimizers — Adam, FTRL, Adagrad, Deep ANN, and **Custom AdamW**

---

## 🏆 Model Performance
| Model               | Loss    | Accuracy |
|---------------------|---------|----------|
| Basic ANN           | 0.3611  | 0.8450   |
| ANN with Adam       | 0.4028  | 0.8323   |
| ANN with FTRL       | 0.6807  | 0.5792   |
| ANN with Adagrad    | 0.3546  | 0.8425   |
| Deep ANN            | 0.3732  | 0.8400   |
| **Custom AdamW**    | **0.0773** | **0.9767** |

---

## ⚙️ Getting Started
1. Clone this repo:
   ```bash
   git clone https://github.com/Sakethkumar100/Custom_AdamW_Optimzer.git
Open NNFLPROJECT.ipynb in Google Colab or Jupyter Notebook.

Run all cells to reproduce the model results.

📜 License
This project is for educational purposes only. See LICENSE if you want to add one.

📧 Contact
GitHub: @Sakethkumar100

If you found this project helpful — ⭐ Star the repo and feel free to contribute!
