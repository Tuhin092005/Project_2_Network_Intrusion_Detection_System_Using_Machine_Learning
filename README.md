# 🛡️ Network Intrusion Detection System (NIDS)

A Machine Learning-based **Network Intrusion Detection System (NIDS)** that detects whether network traffic is **Normal** or an **Attack** using classification algorithms.

---

## 📌 Project Overview

This project uses Machine Learning techniques to identify malicious network traffic. It is trained on the **NSL-KDD** dataset and compares multiple classification algorithms to determine the best-performing model.

---

## ✨ Features

- 📂 Load and preprocess NSL-KDD dataset
- 🏷️ Encode categorical features
- 📏 Scale numerical features
- 🤖 Train multiple Machine Learning models
- 📊 Compare model performance
- 📈 Display Feature Importance
- 🔥 Plot Confusion Matrix
- 🎯 Predict whether a network connection is Normal or an Attack

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📂 Dataset

Dataset Used: **NSL-KDD**

Files:

- `KDDTrain+.txt`
- `KDDTest+.txt`

Target Classes:

- ✅ Normal
- 🚨 Attack

---

## 🤖 Machine Learning Models

- Logistic Regression Classifier
- Decision Tree Classifier
- Random Forest Classifier

---

## 📊 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **75.39%** |
| Decision Tree | **76.34%** |
| Random Forest | **76.70% ⭐ Best Model** |

---

## 📈 Project Workflow

```text
NSL-KDD Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
Label Encoding
      │
      ▼
Feature Scaling
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Network Intrusion Prediction
```

---

## 📁 Project Structure

```text
Project_2_Network_Intrusion_Detection_System_Using_Machine_Learning/
│
├── Network_Intrusion_Detection_System.ipynb 
├── Network_Intrusion_Detection_System.py
├── Dataset/
│   ├── KDDTrain+.txt
│   └── KDDTest+.txt
├── images/
│   ├── confusion_matrix.png
│   ├── model_accuracy_comparison.png
│   └── top_15_feature_importance.png
├── requirements.txt
├── README.md
└── LICENSE

```

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/Tuhin092005/Project_2_Network_Intrusion_Detection_System_Using_Machine_Learning.git
```

### Navigate to the project

```bash
cd Project_2_Network_Intrusion_Detection_System_Using_Machine_Learning
```

### Install required libraries

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

### Using Python

```bash
python Network_Intrusion_Detection_System.py
```

### Using Google Colab

Open

```text
Network_Intrusion_Detection_System.ipynb
```

Upload:

- KDDTrain+.txt
- KDDTest+.txt

Run all cells.

---

## 🔍 Prediction Example

```python
result = predict_intrusion([X_test[0]])

print("Prediction:", result)
```

Example Output

```text
Prediction: Attack
```

or

```text
Prediction: Normal
```

---

## 📊 Visualizations

- 📊 Attack Distribution
- 🌳 Feature Importance
- 🔥 Confusion Matrix
- 📈 Model Accuracy Comparison

---

## 🎯 Applications

- Network Security
- Enterprise Networks
- Cloud Computing
- Banking Systems
- Healthcare
- Educational Institutions
- Government Organizations

---

## 🔮 Future Enhancements

- Real-time Intrusion Detection
- Deep Learning Models
- Web-Based Dashboard
- Live Packet Monitoring
- Explainable AI (XAI)
- Email Alert System

---

## 👨‍💻 Author

**Tuhin Maji**

B.Tech in Computer Science & Engineering (AI & ML)

Meghnad Saha Institute of Technology (MSIT), Kolkata

---

## 📄 License

This project is licensed under the **MIT License**.

---

## ⭐ Support

If you like this project,

⭐ Star this repository

🍴 Fork this repository

📢 Share it with others

Happy Coding! 🚀
