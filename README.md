# Autism-Prediction-using-Machine-Learning
Autism Spectrum Disorder (ASD) is a developmental condition that affects communication, behavior, and social interaction. Early detection is crucial for improving outcomes, but diagnosis is often delayed due to limited resources and awareness. This project aims to develop a machine learning-based system to predict the likelihood of autism in individuals using questionnaire data.

The model uses responses from the Q-CHAT questionnaire, along with demographic information such as age, gender, and family history, to train various classification algorithms. The dataset is preprocessed through encoding, normalization, and handling of missing values before being applied to algorithms like Logistic Regression, Decision Tree, SVM, k-NN, and Random Forest.

After evaluating the models using metrics like accuracy, precision, recall, and F1-score, the Random Forest classifier performed best. It was selected for deployment due to its high accuracy and robustness. The system takes user input via a questionnaire and outputs a prediction indicating whether the individual is likely to be autistic.

This tool can serve as an early screening aid, helping parents, educators, and healthcare providers make informed decisions. It is not a replacement for clinical diagnosis but supports faster and broader preliminary assessments using data-driven techniques.
