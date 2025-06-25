Customer Churn Prediction Web App


◾Overview:-

This project presents a web application designed to predict customer churn using a machine learning model. The application provides an intuitive interface for users to input customer-related features and receive a prediction on whether that customer is likely to churn. This tool can assist businesses in proactively identifying at-risk customers and implementing retention strategies.

◾Features:-

Interactive Input: User-friendly interface to input various customer features.

Real-time Prediction: Get instant predictions on customer churn probability.

Model Insights: Built using a robust machine learning model.

MLflow Integration: Tracks model experiments and lifecycle for better management (backend focus).

◾Technologies Used :-
This project leverages the following key libraries and tools:

Streamlit: For building the interactive web application interface.

PyTorch (torch): Potentially used for the underlying machine learning model's development or specific components (e.g., neural networks).

scikit-learn: For machine learning model development, evaluation, and data preprocessing.

Pandas: For efficient data manipulation and analysis.

NumPy: For numerical operations, especially with arrays.

Matplotlib: For data visualization (e.g., displaying model performance or feature distributions, though not directly exposed in the UI).

MLflow: For managing the machine learning lifecycle, including experiment tracking, model packaging, and model deployment (backend infrastructure).


🌐 Deployed Website
You can access the live version of this web application directly on Streamlit at:

https://ann-classification-churn-rdaxhy8yjrxta9jnalhkhd.streamlit.app

◾ Model Details
The core of this application is a machine learning model trained to predict customer churn. It takes various customer attributes as input and outputs a probability or a binary classification (churn/not churn). The model was developed using a combination of PyTorch (if a deep learning model) and/or scikit-learn (for traditional ML models). MLflow was instrumental in tracking different model versions and experiments during development.

📄 License
This project is licensed under the GPL-3.0 License.
