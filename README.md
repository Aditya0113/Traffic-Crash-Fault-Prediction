# 🚗 Traffic-Crash-Fault-Prediction

Dataset Used: Crash Reporting - Drivers Data

    Tools Used: Python, Pandas, Scikit-Learn, Matplotlib, Seaborn

🔧 Project Features Implemented: 

    ✅ Conducted extensive Data Preprocessing & Exploratory Data Analysis (EDA) on over 160,000 crash records. 
    ✅ Built multiple Supervised Machine Learning models (Logistic Regression, KNN, Decision Tree) to predict driver fault. 
    ✅ Implemented Unsupervised Learning (K-Means Clustering) to discover natural patterns in accident data. 
    ✅ Evaluated and compared model performance using standard metrics like Accuracy, Precision, Recall, and F1-Score.

📊 Visuals Created:

    ✅ Correlation Heatmap: Visualizes relationships between key features like Weather, Light, and Collision Type to identify strong predictors of fault.
    
    ✅ Feature Distribution Histograms: Displays the frequency distribution of crash conditions (e.g., most accidents occur in 'Clear' weather).
    
    ✅ Confusion Matrices (x3): Separate matrices for Logistic Regression, KNN, and Decision Tree models to visualize true vs. false predictions.
    
    ✅ ROC Curves (x2): Receiver Operating Characteristic curves for Logistic Regression and Decision Tree to assess classification capability.

    ✅ Performance Metrics Bar Chart: A comparative bar chart breaking down Precision, Recall, and F1-Scores for each class ('Fault' vs 'No Fault').

    ✅ Cluster vs. Actual Heatmap: A unique visualization comparing unsupervised K-Means clusters against actual 'At Fault' labels to test for natural groupings.

🧠 Analytics & Insights:

    Best Model Performance: The Decision Tree Classifier achieved the highest accuracy (~73%), outperforming KNN and Logistic Regression.

    Key Predictors: Analysis revealed that Collision Type and Vehicle Movement are significant indicators of driver fault.

    Cluster Analysis: K-Means clustering showed that accident data naturally separates into two distinct groups, partially aligning with liability.

    Actionable Insight: The model successfully identifies complex non-linear patterns in crash scenarios, suggesting that fault is often determined by a combination of factors rather than a single condition like      weather.
