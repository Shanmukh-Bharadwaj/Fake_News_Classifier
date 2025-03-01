
📰 Fake News Detection Using Machine Learning

Project Brief
The project aims to detect fake news in this era of misinformation using Machine Learning. We use the Logistic regression algorithm to classify any news articles as either Fake or Real while ensuring a data-driven way of verifying any truth.

📂 Dataset Description
The entitled information consists of:
Fake.csv: which contains the news articles which are fake.
True.csv: consists of legitimate news articles.

Each entry has been labeled (`1=Fake`, `0=Real`) and both datasets have then been combined to create a joint training set for the model.

Main Features:

Advanced Text Preprocessing: Removal of stop words, conversion to lowercase, and filtering out of the special characters.  

TF-IDF Vectorization: Aims to pass text data into a numerical vector form facilitating model training.  

Machine Learning Model: Implementation done based on a Logistic Regression classifier providing a higher accuracy in predicting.  

Performance Evaluation: Utilizing accuracy, precision, recall, and F1 score.  

Custom Prediction Function: Collects input from the user and identifies the authenticity of given news.  

📊 Performance of the Model
🚀 Logistic Regression model is showing scoring a  good accuracy in discriminating fake vs real news. A more graded breakdown of performance metrics is provided in the notebook.

🔮 Future Scope
🔹 Explore the implementation of deep learning models such as **LSTM** and **Transformers**.  
🔹 Now deploying the method as a web application.  
🔹 Bring on the dataset diversification for better generalization.  

🤝 Contribute to Project
We love to contribute! Do feel free to fork this repo, raise an issue, and make a pull request. Let us build a better fake news detector together! 

📜 License
The project is licensed under the MIT License. It is also open for everyone to use and make contributions!
