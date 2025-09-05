Traffic Analysis and Prediction System 🚦
Overview

This project is a Traffic Analysis and Prediction System that uses Machine Learning (Random Forest Classifier) to identify traffic patterns, predict congestion, and visualize data. The system includes exploratory data analysis (EDA), feature importance insights, PCA and t-SNE visualizations, partial dependence plots, and a web-based interface for user interaction.

📁 Repository Contents
File	Description
TrafficTwoMonth.csv	Dataset containing traffic data over two months.
traffic.ipynb	Jupyter Notebook with full data preprocessing, analysis, and ML model training.
traffic_model.pkl	Pre-trained Random Forest model saved using pickle.
label_encoder.pkl	Label encoder used for categorical features in the model.
app.py	Flask web application to interact with the trained model.
index.html	Web interface for user inputs and displaying predictions.
data_visualization.html	Interactive visualizations of traffic data.
decision_boundary.png	Visualization of decision boundaries of the ML model.
feature_importance.png	Plot showing feature importance from the Random Forest model.
pca_visualization.png	PCA-based dimensionality reduction visualization of traffic data.
tsne_visualization.png	t-SNE visualization for high-dimensional traffic features.
partial_dependence_class_0.png – partial_dependence_class_3.png	Partial dependence plots for understanding feature influence on model predictions.
Report-format.docx	Detailed report covering methodology, results, and insights.
🧰 Technologies Used

Python 3.10+

Pandas, NumPy – Data manipulation

Matplotlib, Seaborn, Plotly – Data visualization

Scikit-learn – ML model training (Random Forest Classifier)

Flask – Web application framework

Pickle – Model serialization

HTML/CSS – Front-end for user interface

⚙️ Features

Data Preprocessing – Handles missing values, encoding, and scaling.

Exploratory Data Analysis (EDA) – Includes interactive visualizations (data_visualization.html).

Machine Learning Model – Random Forest Classifier trained for traffic congestion prediction.

Model Insights:

Feature importance (feature_importance.png)

Partial dependence plots (partial_dependence_class_*.png)

Decision boundary visualization (decision_boundary.png)

Dimensionality Reduction – PCA and t-SNE for visualizing high-dimensional traffic data.

Web Interface – Predict traffic patterns interactively using app.py and index.html.

📊 Usage
1. Clone Repository
git clone https://github.com/codewith127yash/traffic-analysis.git
cd traffic-analysis

2. Install Dependencies
pip install -r requirements.txt


Example dependencies: Flask, scikit-learn, pandas, numpy, matplotlib, seaborn, plotly

3. Run the Web App
python app.py


Open your browser at http://127.0.0.1:5000 to use the interface.

4. Jupyter Notebook

Open traffic.ipynb to explore data, run ML training, or generate visualizations.

📈 Visualizations

Feature Importance – Which traffic parameters affect congestion the most.

PCA / t-SNE – High-dimensional data visualization.

Decision Boundaries – How the model separates traffic conditions.

Partial Dependence Plots – Effect of each feature on predictions.

📑 Report

The detailed methodology, analysis, and conclusions are included in Report-format.docx.

⚡ Future Work

Deploy the Flask app on Heroku or AWS.

Include real-time traffic data integration.

Extend the model to predict congestion levels at different times of the day.

📝 License

This project is licensed under the MIT License – see LICENSE file for details.

🙌 Contribution

Contributions, suggestions, and feedback are welcome! Feel free to fork the repo, create a branch, and submit a pull request.
