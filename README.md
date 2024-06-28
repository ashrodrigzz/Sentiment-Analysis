**Sentiment Analysis**
I am introducing a sentiment analysis model that I have developed. This model is designed to assess the sentiments of candidates during interviews. By analyzing the text responses provided by the candidates, the model can determine whether the sentiment expressed is positive or negative.  This tool aims to enhance the interview process by providing valuable insights into the candidates' emotions and attitudes as reflected in their responses.
**Dataset:** A total of 12,743 labeled datasets were used in training this model, with each dataset labeled as either positive or negative. This extensive dataset ensures the model's accuracy and reliability. Dataset is stored in **concatenated.csv** file.
**Model Used:** I have used a Logistic Regression model for the sentiment analysis of candidate interview responses, achieving an accuracy of 99.93%.
**Approach Used:** I began by collecting and labeling data as positive or negative. The preprocessing steps included removing stopwords, punctuation, and null values. To enhance visualization, I used the wordcloud package. For feature extraction, I used TF-IDF vectorization. The data was then split into training and testing sets. A Logistic Regression model was trained on this data. Finally, within the VSCode workspace, I provided candidate responses as input and obtained the corresponding sentiment output.
**Set-up Instruction:**
•	Install the Visual Studio Code application for windows.
    o	https://code.visualstudio.com/download
•	**Python version** : Python 3.12.4
•	Run **sentiment.ipynb** file.
