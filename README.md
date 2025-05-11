# League-of-Legends-Match-Predictor
A final project developed as part of the "Introduction to Neural Networks and PyTorch" course by IBM on Coursera. This project applies logistic regression using PyTorch to predict League of Legends match outcomes based on in-game statistics, focusing on hyperparameter tuning, feature importance analysis, and optimization techniques.

# Project Overview
This predictive model classifies match outcomes (win or loss for the blue team) using structured gameplay data. Key aspects of the project include:
- Logistic Regression using PyTorch
- Feature Engineering & Selection
- Hyperparameter Tuning
- Model Optimization & Evaluation
>Additionally, L2 regularization (Ridge Regression) was incorporated to prevent overfitting and improve generalization.

# Technologies Used
- Python 3.10+
- PyTorch
- Pandas & NumPy
- Matplotlib & Seaborn (for visualization)
- Scikit-learn (for performance evaluation)

# Dataset
The dataset consists of match statistics from League of Legends, including key features such as:
- Kills, deaths, and assists
- Objective control: dragon and baron kills
- Gold earned and vision score
- Damage dealt and wards placed
>The dataset was preprocessed to remove outliers, normalize features, and encode labels for binary classification.

# Model Development
The logistic regression model was implemented in PyTorch, training over 1000 epochs to refine predictive performance.
## Training Details:
- Optimizer: Adam (with L2 regularization for improved generalization)
- Criterion: Binary Cross Entropy Loss
- Best hyperparameter tuning: Learning rate 0.05
- Model evaluation with accuracy, precision, recall, and confusion matrix

# Results
The model demonstrated promising predictive capability:

| Metric            | Value  |
|------------------|--------|
| Training Accuracy | 49.99% |
| Test Accuracy    | 50.20% |
>(Further optimization strategies are planned to enhance performance.)

# Course Context
This project was the final graded assignment of the IBM course:
> **[Introduction to Neural Networks and PyTorch – IBM (Coursera)](https://coursera.org/verify/SDO0357ZFEHG)**

# Future Enhancements
- Applying deep learning architectures for better predictive accuracy
- Exploring time-series gameplay data for improved modeling
- Developing a web-based prediction app using Streamlit

# Contact
**Navya Kannan**  
LinkedIn: [www.linkedin.com/in/navya-kannan-vadakoote](https://www.linkedin.com/in/navya-kannan-vadakoote)  
Email: navyakannanvadakoote@gmail.com  
Certificate ID: SDO0357ZFEHG  
