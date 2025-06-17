COMPANY NAME : CODETECH IT SOLUTIONS

NAME : MOGANA HARINI U

INTERN ID : CT04DF29

DOMAIN : DATA ANALYTICS

DURATION : 4 WEEKS

MENTOR : NEELA SANTHOSH

DESCRIPTION OF MY TASK 4 : Task 4 focuses on building a complete sentiment analysis pipeline using Python by integrating natural language processing (NLP) techniques with machine learning. The task begins with loading and exploring a dataset that contains text entries such as tweets or reviews, along with their corresponding sentiment labels. An initial exploration of the data helps identify patterns, missing values, and class distribution, which is important for understanding the structure and balance of the dataset. The next step involves comprehensive text preprocessing to clean and normalize the data. This includes converting all text to lowercase, removing URLs and punctuation, eliminating common stopwords using NLTK, and lemmatizing words using WordNetLemmatizer to reduce them to their base forms. These steps are essential for reducing noise and improving model accuracy.

After preprocessing, the cleaned text is transformed into numerical features using the TF-IDF (Term Frequency–Inverse Document Frequency) vectorizer, which captures the importance of words and word combinations across the dataset. To address the issue of class imbalance, where some sentiment categories may be underrepresented, SMOTE (Synthetic Minority Over-sampling Technique) is applied. SMOTE generates synthetic examples of the minority classes to ensure the model trains on a more balanced dataset. Once the data is balanced, it is split into training and testing sets. Machine learning models such as Logistic Regression or Support Vector Machines are then trained on the processed data to classify sentiments. The model's performance is evaluated using metrics like accuracy, precision, recall, F1-score, and confusion matrices, providing insights into how well the classifier is performing across different sentiment categories.

To visualize results and gain further insights, various plots are included. Sentiment distribution charts help display class balance before and after oversampling. Word clouds are created to show the most frequently used words in each sentiment category, offering better interpretability and understanding of language patterns. Confusion matrices and performance bar charts visually communicate how accurately the model is predicting each class. Additionally, the pipeline is designed to allow a user to input a new command or sentence and receive a predicted sentiment label in response. The model classifies the input into one of the sentiment categories such as empty, sadness, enthusiasm, neutral, worry, surprise, love, fun, hate, happiness, boredom, relief, or anger. For example, if a user enters a sentence like “I just got a new puppy,” the model may return a sentiment such as happiness or love. This interactive capability adds practical value to the sentiment analysis system, making it suitable for real-time applications and user feedback systems.
