# 🏏 IPL Score Prediction

This project predicts the **total score of an IPL match** based on match conditions using **Machine Learning and Deep Learning** techniques.  
It uses historical IPL match data and a **Neural Network regression model** to estimate the final score during an ongoing match.

## 📌 Features
- Exploratory Data Analysis (EDA) with visualizations
- Label encoding of categorical features (teams, venue, players)
- Neural Network model built using **Keras & TensorFlow**
- Score prediction based on live match inputs
- Interactive prediction using widgets (Google Colab / Jupyter)


## 🧠 Tech Stack
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn  
- **Deep Learning:** TensorFlow, Keras  
- **Tools:** Jupyter Notebook / Google Colab  

## 📂 Project Structure

## 📊 Dataset
- The dataset contains IPL match details such as:
  - Batting team
  - Bowling team
  - Venue
  - Runs
  - Wickets
  - Overs
  - Batsman & Bowler
  - Total score (target variable)

## ⚙️ Model Workflow
1. Data loading and preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Label Encoding of categorical features  
4. Feature scaling using MinMaxScaler  
5. Neural Network model training  
6. Model evaluation using Mean Absolute Error (MAE)  
7. Score prediction using user inputs  

## 🧪 Model Architecture
- Input Layer
- Dense Layer (512 units, ReLU)
- Dense Layer (216 units, ReLU)
- Output Layer (Linear activation)
- Loss Function: **Huber Loss**
- Optimizer: **Adam**

## ▶️ How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/Pradip8390/IPL-Score-Prediction.git





