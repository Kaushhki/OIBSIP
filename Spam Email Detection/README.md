# Email Spam Detection using Machine Learning

## Project Overview
This project focuses on building a machine learning model to classify emails as spam or not spam. The model is trained on text data and uses natural language processing techniques to identify patterns in messages.

## Objectives
- Analyze email dataset
- Perform text preprocessing and cleaning
- Convert text data into numerical format
- Train machine learning models for classification
- Evaluate model performance

## Dataset Information
The dataset contains:
- Email messages
- Labels indicating whether the message is spam or not spam

## Workflow
- Imported dataset using pandas
- Cleaned and preprocessed text data
- Removed unnecessary characters and noise
- Converted text into numerical features using CountVectorizer
- Split dataset into training and testing sets
- Trained classification model
- Evaluated model performance

## Model Used
- Multinomial Naive Bayes

## Model Evaluation
The model was evaluated using:
- Accuracy score
- Confusion matrix
- Classification report

## Data Visualization
- Bar chart showing distribution of spam vs non-spam emails
- Word-based analysis for understanding common spam terms

## Results
The model was able to classify emails with high accuracy and effectively distinguish between spam and non-spam messages.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## How to Run
1. Clone the repository
2. Install dependencies using:
   pip install -r requirements.txt
3. Open the Jupyter Notebook
4. Run all cells step by step

## Future Improvements
- Use advanced NLP techniques such as TF-IDF or word embeddings
- Try different classification algorithms
- Deploy the model as a web application

## Conclusion
This project demonstrates how machine learning and NLP techniques can be used to automatically classify emails and improve communication efficiency.
