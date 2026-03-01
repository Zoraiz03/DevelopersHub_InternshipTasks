
# DevelopersHub Internship Tasks

**Intern:** Muhammad Zoraiz Khan 
**Organization:** DevelopersHub  

This repository contains selected machine learning and AI-based projects completed during the DevelopersHub Internship Program.  

Each project focuses on solving a real-world problem using structured data analysis, predictive modeling, or intelligent conversational systems. The implementation emphasizes clean code, proper preprocessing, evaluation metrics, and professional documentation.

---

# Completed Tasks

## Task 2: Stock Price Prediction

### Objective
Develop a predictive model to forecast stock prices using historical market data.

### Problem Overview
Stock prices are time-series data influenced by trends, seasonality, and volatility. The goal of this task was to apply machine learning/deep learning techniques to predict future price movements based on historical patterns.

### Approach

1. Data Collection
   - Historical stock data including Open, High, Low, Close, and Volume.
   - Time-based indexing for sequential modeling.

2. Data Preprocessing
   - Handling missing values
   - Feature scaling using MinMaxScaler
   - Converting time-series data into supervised learning format

3. Model Development
   - LSTM (Long Short-Term Memory) network for time-series prediction
   - Sequential modeling using TensorFlow/Keras

4. Model Evaluation
   - Loss monitoring during training
   - Visualization of predicted vs actual prices

### Visualizations
- Historical price trend
- Training loss curve
- Actual vs predicted stock prices comparison

### Skills Demonstrated
- Time-series forecasting
- Deep learning with LSTM
- Feature scaling for sequential data
- Model performance visualization

---

## Task 3: Heart Disease Prediction

### Objective
Build a classification model to predict the likelihood of heart disease using patient health indicators.

### Problem Overview
Heart disease prediction is a binary classification problem where medical attributes are used to determine risk.

### Dataset Features
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol
- Maximum heart rate
- Fasting blood sugar
- ECG results

### Approach

1. Data Preprocessing
   - Handling categorical and numerical variables
   - Feature scaling
   - Train-test split

2. Model Training
   - Logistic Regression
   - Random Forest Classifier
   - Comparison of model performance

3. Model Evaluation
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

### Visualizations
- Correlation heatmap
- Feature importance graph
- Confusion matrix visualization

### Skills Demonstrated
- Binary classification
- Model comparison
- Healthcare data interpretation
- Evaluation using classification metrics

---

## Task 4: General Health Query Chatbot

### Objective
Develop an AI-powered chatbot capable of answering general health-related questions using prompt engineering and Large Language Models (LLMs).

### Problem Overview
The chatbot is designed to provide safe, friendly, and structured responses to general health queries while preventing harmful or dangerous advice.

### Implementation

1. LLM Integration
   - API-based integration with a large language model
   - Prompt engineering to guide tone and structure

2. Prompt Design
   - System role: Helpful medical assistant
   - Clear, structured answers
   - General information only disclaimer

3. Safety Filters
   - Detection of harmful or crisis-related queries
   - Blocking unsafe responses
   - Crisis guidance message for sensitive queries

4. Interactive Mode
   - Continuous user input
   - Graceful exit command
   - Clear response formatting

### Example Queries
- What causes a sore throat?
- Is paracetamol safe for children?
- How can I lower blood pressure naturally?

### Skills Demonstrated
- Prompt engineering
- API-based LLM integration
- Conversational AI design
- Safety-aware chatbot implementation

---

## Task 6: House Price Prediction

### Objective
Predict house prices using property features such as size, number of bedrooms, and location.

### Problem Overview
House price prediction is a regression problem where property attributes are used to estimate market value.

### Approach

1. Data Loading
   - Publicly available dataset link
   - Structured tabular data

2. Data Preprocessing
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
   - Train-test split

3. Model Training
   - Linear Regression
   - Gradient Boosting Regressor

4. Model Evaluation
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)

### Visualizations
- Price distribution histogram
- Correlation heatmap
- Actual vs predicted scatter plot
- Residual distribution plot

### Skills Demonstrated
- Regression modeling
- Feature engineering
- Model evaluation metrics
- Real estate data interpretation

---

# Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Core programming language |
| Pandas, NumPy | Data manipulation |
| Matplotlib, Seaborn | Data visualization |
| Scikit-learn | Machine learning models |
| TensorFlow / Keras | Deep learning (LSTM) |
| Hugging Face / OpenAI API | LLM integration |
| Jupyter Notebook | Development environment |

---

# Repository Structure
DevelopersHub_InternshipTasks/
│
├── Task2_StockPricePrediction.ipynb
├── Task3_HeartDiseasePrediction.ipynb
├── Task4_GeneralHealthQueryChatbot.ipynb
└── Task6_HousePricePrediction.ipynb


---

# Key Learning Outcomes

- Applied machine learning to structured datasets
- Built time-series and regression models
- Implemented classification systems for healthcare data
- Integrated large language models for conversational AI
- Designed safe AI systems with input filtering
- Strengthened data visualization and evaluation skills

---

# Conclusion

These projects demonstrate practical experience in machine learning, deep learning, and AI system development.  

The tasks collectively reflect the ability to:
- Understand real-world problems
- Preprocess and analyze datasets
- Select and evaluate appropriate models
- Build deployable AI applications

---

# Acknowledgements

Special thanks to DevelopersHub for providing structured, hands-on internship tasks that strengthened technical and analytical skills in machine learning and artificial intelligence.
