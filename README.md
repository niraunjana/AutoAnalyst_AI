🚀 AutoAnalyst_AI
An Autonomous, Cross-Modal Data Analysis & Intelligent Model Selection System

AutoAnalyst_AI is an end-to-end autonomous data intelligence framework designed to automate Exploratory Data Analysis (EDA), dataset profiling, statistical diagnostics, outlier detection, and machine learning model selection through a unified interactive interface.

The system minimizes manual analytical effort by automatically understanding the structure, quality, and predictive potential of datasets, enabling users to move from raw data to actionable insights efficiently.

📌 Motivation

Traditional data analysis requires:

Manual inspection of datasets

Separate scripts for EDA, cleaning, and modeling

Prior domain knowledge to choose appropriate models

AutoAnalyst_AI addresses these challenges by:

Automatically profiling datasets

Detecting anomalies and data issues

Identifying ML problem types

Selecting optimal baseline models

Presenting insights visually and interactively

🧠 Core Capabilities
🔹 Automated Dataset Understanding

Structural analysis (rows, columns)

Data type inference

Missing value analysis

Feature categorization (numerical vs categorical)

🔹 Intelligent Exploratory Data Analysis (EDA)

Sample record preview

Statistical summaries

Distribution-level insights

Feature-wise diagnostics

🔹 Outlier Detection Engine

Column-wise anomaly identification

Statistical thresholding

Visual representation of outlier counts

🔹 Autonomous Machine Learning

Target column selection

Automatic problem detection:

Regression

Classification

Model training and evaluation

Best model selection based on performance metrics

🏗️ System Architecture
                ┌────────────────────┐
                │   Dataset Upload   │
                └─────────┬──────────┘
                          │
                ┌─────────▼──────────┐
                │ Data Profiling Unit │
                └─────────┬──────────┘
                          │
                ┌─────────▼──────────┐
                │   EDA Engine        │
                └─────────┬──────────┘
                          │
                ┌─────────▼──────────┐
                │ Outlier Detection   │
                └─────────┬──────────┘
                          │
                ┌─────────▼──────────┐
                │ Target Selection    │
                └─────────┬──────────┘
                          │
                ┌─────────▼──────────┐
                │ Model Selection     │
                └─────────┬──────────┘
                          │
                ┌─────────▼──────────┐
                │ Insights Dashboard  │
                └────────────────────┘

📊 Dataset Profiling Module

This module generates a machine-readable and human-readable dataset summary, including:

Total number of rows and columns

Missing value percentages per feature

Feature-level data types

✔ Example Output Characteristics

Dataset Size: 150 rows × 6 columns

Mixed numerical and categorical features

Automatic detection of missing values

Ready-to-model dataset assessment

This profiling step ensures early detection of data quality issues, reducing downstream errors.

📈 Exploratory Data Analysis (EDA)

AutoAnalyst_AI performs lightweight yet effective EDA by:

Displaying the first few records

Highlighting feature distributions

Exposing patterns and irregularities

This helps users quickly assess:

Feature relevance

Data consistency

Potential modeling challenges

🚨 Outlier Detection Strategy

Outliers are detected per numerical feature using statistical deviation techniques.

Generated Insights:

Identifies columns with abnormal data points

Quantifies outlier frequency

Helps determine whether cleaning or transformation is required

This is critical for:

Improving model robustness

Preventing skewed predictions

Maintaining statistical validity

🤖 Automatic Model Selection Engine

After selecting a target variable, the system:

Determines the machine learning problem type

Selects suitable baseline models

Trains models on the processed dataset

Evaluates performance using standard metrics

Automatically selects the best-performing model

✔ Sample Result

Problem Type: Regression

Selected Model: Linear Regression

Performance Metric: R² Score = 0.7728

This removes the need for manual experimentation during early modeling stages.

📊 Visualization & Interpretability

The system provides visual outputs for:

Feature-level insights

Outlier distributions

Model evaluation summaries

These visuals ensure:

Transparency

Interpretability

Ease of decision-making

🛠️ Technology Stack
Category	Tools
Language	Python
Frontend	Streamlit
Data Handling	Pandas, NumPy
Machine Learning	Scikit-learn
Visualization	Matplotlib, Plotly
📂 Project Structure
AutoAnalyst_AI/
│
├── app.py                  # Streamlit application
├── data/                   # Input datasets
├── models/                 # ML utilities
├── utils/                  # Helper functions
├── requirements.txt        # Dependencies
└── README.md               # Documentation

⚙️ Installation & Execution
Step 1: Clone Repository
git clone https://github.com/niraunjana/AutoAnalyst_AI.git
cd AutoAnalyst_AI

Step 2: Install Dependencies
pip install -r requirements.txt

Step 3: Launch Application
streamlit run app.py

🎯 Applications

Automated exploratory data analysis

Academic research assistance

ML baseline model generation

Dataset quality auditing

Data science education

⚠️ Current Limitations

Limited to baseline ML models

Requires structured datasets

Does not yet include feature engineering automation

Deep learning models not integrated

🔮 Future Scope

RAG-based natural language explanations

Automated PDF/HTML report generation

Advanced ensemble model selection

Time-series and NLP dataset support

Cloud deployment and scalability
