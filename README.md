# Source Code Documentation

## Project: LocoFind: A GPS-Enabled Platform For Local Food, Culture, Safety, and Heritage Exploration
### Overview
Tourism is one of India’s fastest-growing industries, contributing to economic growth and cultural exchange. However, travelers face challenges like unpredictable weather, safety issues, transport delays, and language barriers. Most existing apps address only specific aspects, forcing tourists to use multiple platforms for accommodation, food, and transport.

LocoFind is an ML-based, GPS-enabled tourism platform that unifies essential travel components into a single system. It features five key modules:

Season Predictor: Identifies the best time to visit a location.
Cuisine Recommender: Suggests authentic local dishes and restaurants.
Safety & Feedback Classifier: Detects risky areas using review and accident data.
Transport & Weather Analyzer: Predicts delays and weather conditions.
Regional Language Module: Assists users in understanding and communicating in local languages.

Using Gradient Boosting, Random Forest, Logistic Regression, Naïve Bayes, and Decision Trees, LocoFind provides accurate predictions and personalized recommendations, enhancing convenience, safety, and cultural engagement for travelers.

### Modules Implemented

#### 1️⃣ Season Predictor (Regression)
- **Goal:** Predict tourist arrivals and ideal travel seasons.
- **Algorithm Used:** Gradient Boosting Regressor  
- **Performance (R²):** 98.2%  
- **Output:** Suggests the best month or season for travel.

#### 2️⃣ Cuisine Recommender (Classification)
- **Goal:** Recommend local dishes based on region, occasion, and dietary preference.
- **Algorithm Used:** Naive Bayes Classifier  
- **Accuracy:** 92.5%  
- **Output:** Displays a list of regionally popular dishes.

#### 3️⃣ Transport & Weather Analyzer (Classification)
- **Goal:** Predict chances of transport delays using weather conditions.
- **Algorithm Used:** Random Forest Classifier  
- **Accuracy:** 97.0%  
- **Output:** Displays whether a delay is likely or not.

#### 4️⃣ Safety & Feedback Classifier (Classification)
- **Goal:** Classify accident severity and evaluate road safety.
- **Algorithm Used:** Logistic Regression  
- **Accuracy:** 99.8%  
- **Output:** Categorizes severity into Low, Medium, or High.

#### 5️⃣ Regional Language Module (Classification)
- **Goal:** Identify the dominant regional language based on city and state.
- **Algorithm Used:** Decision Tree Classifier  
- **Accuracy:** 100.0%  
- **Output:** Displays the most commonly spoken regional language.


### How to Execute

1. **Navigate to Source Code Folder:**
   ```bash
   cd Source_Code
   ```
2. **Install all required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the main project:**
   ```bash
   python mini_india_ml_model_final_demo.py
   ```
4. **OR use the executable notebook:**
   Open `/Executable/LocoFind_Executable.ipynb` in Google Colab or Jupyter Notebook for full output and visualizations.

---

### Dependencies

```
pandas
numpy
scikit-learn
matplotlib
seaborn

### Output
Each module provides:
- Model accuracy and performance metrics (R² / Accuracy, Precision, Recall, F1-Score)
- Visual bar and line graphs comparing module performances
- Final summary table showing the best algorithms and metrics.


### Developed By
Team ID:A17
Team Members: R. Chandria — Register No: 211422104099  
              Aruna G — Register No: 211422104056   
Project Title: LocoFind: A GPS-Enabled Platform For Local Food, Culture, Safety, and Heritage Exploration  
Department: Computer Science & Engineering  
Institution: Panimalar Engineering College  
Guide:Mrs. Alima Beevi A, M.E.  
  Assistant Professor,  
  Department of Computer Science and Engineering,  
  Panimalar Engineering College  
