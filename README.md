# Spam-mail-detection

This project aims to automatically detect spam emails using a machine learning model. The core of the project is a Logistic Regression model that has been trained on a dataset of emails, each labeled as either spam or not spam. The text content of these emails is converted into numerical features using TfidfVectorizer, which captures the importance of words in each email relative to the entire dataset. Once trained, the model can predict whether new emails are spam, helping to filter and manage inboxes more efficiently.

