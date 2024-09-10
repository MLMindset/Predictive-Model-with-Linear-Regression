🏠 Predictive Modeling of California Housing Prices with Ridge and Lasso Regression

In this project, I developed a predictive model to estimate housing prices 🏘️ using the California Housing dataset. The key steps and findings of this project were:

🗂️ Data Collection and Feature Engineering:

📚 Utilized the California Housing dataset from scikit-learn.
🔍 Selected key features (MedInc, HouseAge, AveRooms, AveOccup) that significantly influence housing prices.
📈 Applied polynomial features transformation to capture non-linear relationships.
⚙️ Feature Scaling and Data Preparation:

📏 Standardized the features using StandardScaler to normalize the data.
🔄 Created polynomial features of degree 2 to account for interactions between the variables.
✂️ Split the dataset into training and testing sets with an 80-20 split for model evaluation.
🧠 Model Development and Hyperparameter Tuning:

🧮 Implemented Ridge Regression and Lasso Regression to minimize overfitting and enhance the model's performance.
🎯 Used GridSearchCV for hyperparameter tuning:
Ridge Regression: Best alpha = 20.0 with an MSE of 0.62 and R² score of 0.52.
Lasso Regression: Best alpha = 0.05 with an MSE of 0.66 and R² score of 0.50.
📊 Model Evaluation and Visualization:

📉 Visualized the model performance to compare the predictions of Ridge and Lasso regressions against the actual housing prices.
🔍 Used scatter plots to highlight the differences and assess the prediction accuracy.
This project provided hands-on experience in regression modeling, feature engineering, and hyperparameter optimization using Python libraries such as pandas, scikit-learn, and matplotlib. 📊💻✨
