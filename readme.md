Title : Sms Spam Detection

Author : Ayush Paigude

Dataset : The dataset consists of 2 columns : Class and Message. The size of the dataset is 5574 x 2.

Description : Your SMS spam detection code performs a complete machine learning pipeline to classify messages as spam or ham (non-spam). It begins with label encoding and data balancing to ensure fair model learning. Then, it extracts key features like word count, presence of numbers, and currency symbols, followed by text preprocessing using regex, stopword removal, and lemmatization. The cleaned text is transformed into numerical vectors using TF-IDF, and models like Multinomial Naive Bayes and Decision Tree are trained and evaluated using metrics like accuracy, F1-score, and confusion matrix. Finally, the model is tested on custom input to simulate real-time spam detection.