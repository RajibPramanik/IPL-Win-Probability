# IPL Win Probability Predictor  

This project predicts the win probability of IPL matches based on historical match data using machine learning. It processes match and delivery data to calculate key metrics like current run rate (CRR), required run rate (RRR), and remaining wickets, and applies a classification model to predict match outcomes.  

## 📂 **Project Structure**  
- `matches.csv` – Contains match-level data (e.g., team names, scores, venue).  
- `deliveries.csv` – Contains ball-by-ball data (e.g., runs scored, wickets).  
- `IPL_win.ipynb` – Jupyter Notebook with the code and model implementation.  

## 🚀 **How It Works**  
1. Load and clean data from CSV files.  
2. Standardize team names and filter out rain-affected matches.  
3. Calculate key metrics:  
   - Runs left, wickets left, balls left  
   - Current Run Rate (CRR), Required Run Rate (RRR)  
4. Apply one-hot encoding to categorical features.  
5. Train a machine learning model (e.g., Logistic Regression).  
6. Evaluate model accuracy using test data.  
7. Generate visualization for match progression.  

## 🛠️ **Technologies Used**  
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

## 📊 **Output Example**  
- Predicted win probability after every over.  
- Line and bar plot for match progression.  

## 🏆 **Results**  
- Accuracy: ~80% on test data.  
- Model predicts win/loss based on real-time match progression.  

