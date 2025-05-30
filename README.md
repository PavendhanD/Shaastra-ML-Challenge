🌡️ Weather Forecasting with ML – Shaastra Techathon Challenge 2

🏆 1st Place Winner – Shaastra Techathon AI/ML Challenge 2 by IIT Madras

This project presents a machine learning solution developed to predict the average temperature of a target city (City D) using weather and geographic data from three other cities (A, B, and C). The solution was crafted as part of the Shaastra Techathon AI/ML Challenge 2, organized by IIT Madras. ￼

🚀 Problem Statement

The challenge involved building a predictive model to estimate the average temperature of City D based on features such as:
	•	Latitude, longitude, and elevation
	•	Precipitation levels
	•	Daily temperature metrics from Cities A, B, and C ￼ ￼

The dataset provided consisted of 812 rows, necessitating careful handling of missing values and feature engineering to ensure accurate predictions. ￼

🧠 Our Approach
	1.	Data Preprocessing:
	•	Handled missing values through imputation techniques.
	•	Performed feature scaling and normalization.
	•	Engineered new features to capture temporal and spatial patterns.
	2.	Model Development:
	•	Experimented with various models including Random Forest, Gradient Boosting, and XGBoost.
	•	Implemented neural network architectures like LSTM, GRU, and Bi-LSTM.
	•	Finalized a hybrid model combining LSTM, GRU, and Bi-LSTM layers for optimal performance. ￼
	3.	Model Evaluation:
	•	Utilized K-Fold Cross-Validation to assess model generalization.
	•	Achieved a Mean Absolute Error (MAE) of 1.49409 on the validation set. ￼

📁 Project Structure
	•	1.32.ipynb – Notebook containing exploratory data analysis and initial modeling.
	•	data_preproces.ipynb – Notebook detailing data preprocessing steps.
	•	train.csv – Training dataset.
	•	test.csv – Test dataset.
	•	transformed_train_2.csv – Preprocessed training data.
	•	transformed_test_2.csv – Preprocessed test data.

🏗️ Tech Stack
	•	Python
	•	Jupyter Notebook
	•	Pandas, NumPy
	•	Scikit-learn
	•	TensorFlow / Keras
	•	Matplotlib, Seaborn ￼

👥 Team Members
	•	Naveen Kumar
	•	Pavendhan
  •	Vendhan
	•	Paulin

📜 License

This project is open-source and available for use under the MIT License.
