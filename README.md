# Email Spam Detection

A machine learning project that classifies email and SMS messages as Spam or Not Spam using Natural Language Processing (NLP) and the Multinomial Naive Bayes algorithm.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- CountVectorizer
- Multinomial Naive Bayes

## Project Workflow
1. Load and explore the dataset.
2. Handle duplicate records.
3. Convert categorical labels into numerical values.
4. Split the dataset into training and testing sets.
5. Convert text messages into numerical features using CountVectorizer.
6. Train a Multinomial Naive Bayes classifier using an ML Pipeline.
7. Evaluate model performance using accuracy and a confusion matrix.
8. Test the model on new messages.

## Dataset
The dataset contains two columns:
- `Category`: Spam or Ham classification.
- `Message`: Email/SMS message content.

## How to Run

```bash
git clone YOUR_REPOSITORY_URL
cd Email-Spam-Detection

pip install -r requirements.txt

jupyter notebook
```

Open `Email_spam_detection.ipynb` and run the cells.

## Algorithm
Multinomial Naive Bayes with CountVectorizer for text classification.
