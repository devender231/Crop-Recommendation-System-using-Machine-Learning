The Crop Recommendation Project is an AI-driven web application designed to assist farmers and agricultural planners in choosing the most suitable crop to cultivate based on specific soil and climate conditions. 
This solution integrates machine learning algorithms into a user-friendly web interface, making advanced agricultural decision-making accessible and efficient. At its core, the project utilizes a supervised 
learning model—specifically a Random Forest Classifier—that has been trained on a dataset containing essential agricultural features such as nitrogen, phosphorus, potassium levels, temperature, humidity, pH, 
and rainfall. Based on these inputs, the AI model predicts the best crop to grow, offering insights grounded in historical agricultural data patterns.

The application is built using Python and Flask for the backend, and it provides a web interface that allows users to enter environmental parameters and receive instant crop recommendations. 
The model is stored in a serialized format (model.pkl) and loaded dynamically during runtime. The system also includes a MongoDB integration to store user input data for analysis or improvement of the model in 
the future. The project features clean HTML templates and static assets for a simple and responsive user experience, supported by data visualization and supplementary farming resources.A Jupyter Notebook is 
included to demonstrate exploratory data analysis (EDA), model training, and evaluation steps. The entire project is modular and easy to run locally; it just requires Python 3.7 or above, with dependencies 
like Flask, Pandas, Scikit-learn, Joblib, and PyMongo. This tool represents a practical application of artificial intelligence in precision agriculture, helping improve crop yield and resource efficiency through 
data-driven insights.
