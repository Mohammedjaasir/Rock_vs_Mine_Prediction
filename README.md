
# 🌊 Rock vs Mine Prediction using Sonar Data

What if machines could detect hidden underwater dangers just by analyzing sound?  
This project uses **Machine Learning** to classify sonar signals as either **rocks** or **mines**, helping to automate underwater threat detection.

---

## 🚀 What is This?

**Rock vs Mine Prediction** is a Python-based ML project that analyzes 60-dimensional sonar signal readings to determine whether an object is a rock or a mine.  
It’s a great demonstration of real-world AI in defense and marine safety.

- 🎯 Binary classification using real sonar data  
- 📊 Feature analysis + model evaluation  
- 🔍 Clean, explainable pipeline  
- ⚙️ Built with scikit-learn & pandas  

---

## ✨ Why I Built This

As an engineering student diving into AI, I wanted to work on a project with **real-world impact**.  
This dataset from UCI helped me explore how machine learning can help with safety in high-risk environments like oceans and warzones.

---

## 🖼️ Preview

Here’s a quick look at what the model does:

| Signal Sample | Prediction |
|---------------|------------|
| [0.03, 0.04, ..., 0.22] | Mine 🧨 |
| [0.10, 0.09, ..., 0.14] | Rock 🪨 |

And here's a banner I designed for it:

![ChatGPT Image Jun 20, 2025, 12_42_16 AM](https://github.com/user-attachments/assets/296bece3-288c-488b-aeb1-628674975114)


---

## 🔧 Features at a Glance

| Feature              | Description                                     |
|----------------------|-------------------------------------------------|
| 📁 CSV Input          | Uses sonar data with 60 features per sample     |
| 🤖 ML Model           | Logistic Regression / KNN / Random Forest       |
| 📉 Accuracy Report    | Model evaluation and accuracy comparison        |
| 📊 Visual Plots       | Confusion Matrix, Heatmaps, Accuracy Graphs     |
| 🧼 Data Processing     | Label encoding + train-test split + scaling     |

---

## 🛠️ Tech Stack

- **Language:** Python 🐍  
- **Libraries:** scikit-learn, pandas, seaborn, matplotlib  
- **Notebook:** Googlecolab (`.ipynb`)  
- **Dataset:** [UCI Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))

---

## 📂 Folder Structure

```bash
rock-vs-mine-prediction/
├── Rock_vs_Mine_Prediction.ipynb   # Main notebook
├── sonar_data.csv                  # Raw sonar dataset
├── assets/
│   └── banner.png                  # Project banner image
└── README.md                       # You're reading it!
