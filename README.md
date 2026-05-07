# 🏏 Cricket Match Score Prediction System 🚀

A machine learning-powered web application to **predict final cricket scores** based on real-time match situations.

---

## 📌 Overview
This project uses machine learning to predict the final score of a cricket match (specifically IPL) based on:
- Current runs, overs played, and wickets lost.
- Venue of the match.
- Batting and Bowling teams.
- Advanced features like Current Run Rate (CRR), Projected Score, and Pressure Factor.

Built using **Python**, **scikit-learn**, and **Streamlit**.

---

## ✨ Features
✅ Predicts realistic final cricket scores (Average, Minimum, and Maximum).  
✅ Visualizes upcoming overs prediction as a bar graph.  
✅ Modern, responsive, and mobile-friendly user interface.  
✅ Dataset sample viewing capability.  
✅ Lightweight and easy to deploy.

---

## 📂 Project Structure
```
📂 data/
   ├── ipl.csv               # IPL match dataset
   ├── best_model.pkl        # Trained ML model
   └── preprocessor.pkl      # Data preprocessor
Cricket-Score-Prediction.py  # Main Streamlit application
train_model.py               # Model training script
requirements.txt             # Required dependencies
LICENSE                      # MIT License
```

---

## ⚙ Installation & Usage

### 1. Install Dependencies
Make sure you have Python installed, then run:
```bash
pip install -r requirements.txt
```

### 2. Train the Model (Optional)
If you want to re-train the model on the dataset:
```bash
python train_model.py
```

### 3. Run the Application
Start the Streamlit web server:
```bash
streamlit run Cricket-Score-Prediction.py
```

### 4. Access the Web App
Open your browser and go to:
[http://localhost:8501](http://localhost:8501)

---

## 🤖 Model Details
- **Algorithm:** Gradient Boosting Regressor
- **Features Used:**
  - `current_run_rate`
  - `projected_score`
  - `pressure_factor`
  - `is_death_overs`
  - Team and Venue encoding

---

## 📄 License
This project is licensed under the **MIT License**.

---

## ✏ Contact
**Created by:** Jay, Shivam and Nikhil
