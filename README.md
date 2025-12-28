# Customer-Churn-Prediction-in-Telecom
Analyzed customer data from Interconnect telecom company to predict client churn and develop retention strategies. Examined contract patterns, service usage, payment methods, and demographic factors to identify at-risk customers and optimize retention efforts. Provided actionable insights for reducing customer attrition and maximizing lifetime value.

## 1. Objectives 🎯
- Clean and prepare multiple telecom datasets for comprehensive analysis
- Identify key patterns and characteristics of customers who cancel services
- Understand the relationship between service types, contract terms, and churn rates
- Build predictive models to identify customers at high risk of churn
- Determine optimal balance between recall and precision for business implementation
- Provide data-driven recommendations for customer retention strategies

## 2. Key Findings 🏆
- Identified monthly contracts as having the highest churn rates (most cancellations)
- Discovered fiber optic service customers cancel more frequently than DSL customers
- Found that customers who churned typically had higher monthly charges than retained customers
- Determined that Electronic Check is the most common payment method among churned customers
- Revealed four specific months with unusually high cancellation spikes
- Established that customers with more services (bundles) are less likely to churn
- Demonstrated that churned customers were often more profitable (higher monthly charges)

## 3. Visualizations Included 🎨
- Customer acquisition trends over time with seasonal patterns
- Churn distribution across contract types (monthly, annual, biennial)
- Payment method comparisons between active and churned customers
- Monthly charges distribution for churned vs. retained customers
- Service type analysis (Internet, phone lines) by churn status
- Demographic breakdown (age, family status) of churning customers
- Feature importance plots from machine learning models

## 4. Skills Demonstrated 🛠️
- Data Integration: Merging multiple related datasets into a unified structure
- Data Cleaning: Handling missing values, type conversions, and data standardization
- Exploratory Analysis: Deep dive into customer behavior patterns and churn triggers
- Feature Engineering: Creating derived variables like total_services per customer
- Machine Learning: Training and comparing multiple classification models (Random Forest, Decision Tree, LGBM)
- Model Evaluation: AUC-ROC analysis, recall-precision trade-off assessment
- Business Communication: Translating technical results into strategic recommendations
- Hyperparameter Tuning: Optimizing model performance for business objectives

## 5. Technical Details 💻
- Programming Language: Python
- Main Libraries: pandas, matplotlib, seaborn, scikit-learn, lightgbm, numpy
- Dataset: Four integrated tables with customer, contract, service, and payment data
- Models Implemented: RandomForestClassifier, DecisionTreeClassifier, LGBMClassifier
- Key Metrics: AUC-ROC, Recall, Precision, F1-Score
- Best Model: Random Forest with AUC-ROC of 0.838
- Optimal Threshold: 0.3 achieving 90.1% recall and 45.2% precision
- Validation Approach: Train-test split with class imbalance handling

## 6. Installation and Usage
```bash
# Clone the repository
git clone https://github.com/yourusername/telecom-churn-analysis.git

# Navigate to project directory
cd telecom-churn-analysis

# Install required dependencies
pip install -r requirements.txt

# Run the analysis notebooks in order:
jupyter notebook Final_project_Data_Processing_and_Feature_Engineering.ipynb
jupyter notebook Final_project_EDA.ipynb
jupyter notebook Final_project_Informe_de_solucion.ipynb
