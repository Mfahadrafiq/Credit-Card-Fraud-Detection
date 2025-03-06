# 🔍 Credit Card Fraud Detection  

## 📌 Overview  
This project implements a **Credit Card Fraud Detection System** using **Machine Learning and AI**. The system is designed to classify transactions as **fraudulent or legitimate** based on transaction attributes, user demographics, and spending behavior. The trained model is deployed using a **Flask API** to provide real-time fraud detection.  

## 📂 Project Structure  
```
|-- app.py                                   # Flask API for fraud detection
|-- model.py                                 # Machine learning model (Random Forest & XGBoost)
|-- Notebook (Including Analysis and Visualizations).ipynb  # Data analysis & visualization
|-- requirements.txt                          # List of dependencies
|-- README.md                                # Project documentation
|-- report.docx                              # Detailed report on dataset & model evaluation (optional)
```

## 🚀 Installation  
Clone the repository and install dependencies:  
```sh
git clone https://github.com/mfahadrafiq/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
pip install -r requirements.txt
```

## 🛠️ Usage  
1. **Run the Flask API**:  
   ```sh
   python app.py
   ```
2. **Train the model (if needed)**:  
   ```sh
   python model.py
   ```
3. **Access the API for predictions**:  
   - Open `http://127.0.0.1:5000/` in your browser.  
   - Send a **POST request** to `/predict_api` with transaction details in JSON format.  

## 🔍 Model Pipeline  
- **Data Processing**: Cleans & encodes transaction attributes.  
- **Feature Engineering**: Extracts useful features (transaction time, category, user behavior).  
- **Model Training**:  
  - **Random Forest Classifier**  
  - **XGBoost Classifier**  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score.  
- **Deployment**: Flask API for real-time fraud detection.  

## 📊 Results  
The model was evaluated using various metrics. The **Random Forest classifier** performed best with:  

| Metric       | Value  |
|-------------|--------|
| **Accuracy**  | 96.8%  |
| **Recall**    | 95.2%  |
| **Precision** | 94.7%  |
| **F1 Score**  | 94.9%  |

## 📈 Visualization  
✔️ **Fraudulent vs. Legitimate Transactions**  
✔️ **Transaction Trends by Category & Time**  
✔️ **Feature Importance in Fraud Detection**  
