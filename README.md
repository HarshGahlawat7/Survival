# 🌊 SafeVoyage AI: Smart Survival Predictor for Maritime Emergencies

**Created by Harsh Gahlawat**  
**Powered by Random Forest & Real-World Data**

---

> **SafeVoyage AI** is a machine learning-based decision support tool designed to assist in real-time **survivability analysis** during maritime emergencies such as cruise ship evacuations or ferry accidents.  
> Leveraging historical passenger data and a Random Forest Classifier, the tool can estimate the likelihood of survival based on key personal and situational attributes.

---

## 📌 Overview

- **📁 Dataset:** Simulated maritime passenger manifest (`tested.csv`)
- **🤖 Model:** Random Forest Classifier
- **🌐 Interface:** Gradio-based Web UI
- **🛠 Tech Stack:** Python, Pandas, Scikit-learn, Gradio

---

## 🚀 Features

✅ Cleaned and preprocessed passenger data  
✅ Encoded categorical variables for ML compatibility  
✅ Trained and saved a robust Random Forest model  
✅ Gradio web interface for real-time prediction  
✅ Modular, maintainable code structure (training + UI)  
✅ Real-life applicability for marine rescue strategy planning  

---

## 🧠 Model Insights

- **Algorithm:** Random Forest Classifier
- **Target Variable:** `Survived` (0 = No, 1 = Yes)
- **Input Features:**
  - `Pclass` — Passenger Class (1st, 2nd, 3rd)
  - `Sex` — Gender
  - `Age` — Passenger Age
  - `SibSp` — Siblings/Spouses Aboard
  - `Parch` — Parents/Children Aboard
  - `Fare` — Ticket Fare
  - `Embarked` — Port of Embarkation  
    (C = Cherbourg, Q = Queenstown, S = Southampton)

---

## 🌍 Real-World Relevance

While based on Titanic-era data, this project demonstrates how AI can enhance **disaster response systems**. Emergency responders and maritime authorities could use similar models to:

- Optimize rescue strategies
- Simulate emergency scenarios
- Understand demographic vulnerabilities in disasters

---



## 📎 Tags

`Machine Learning` `Random Forest` `Disaster Prediction` `Gradio` `Python` `Maritime Safety`

---

> ⚓ _“Because every second counts in a crisis. SafeVoyage AI helps make smarter, faster decisions when it matters most.”_

