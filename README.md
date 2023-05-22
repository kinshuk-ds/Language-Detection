# Language-Detection-

In this project, I built a language detection model using NLP techniques. 
The dataset for this project was sourced from Kaggle, which contained examples of text in 18 different languages.

To train the model, I used a combination of vectorization and pipeline. 
Vectorization is a process where text data is transformed into numerical data, so that it can be used in machine learning algorithms. 
I used the TF-IDF vectorization method, which calculates the importance of each word in a document based on how frequently it appears in 
the document and how often it appears across all documents in the dataset.

Next, I used a pipeline to implement the Logistic Regression algorithm, which was used to classify the text into different languages. 
The pipeline allowed me to easily preprocess the data and apply the vectorization and classification steps in a single step.

To improve the accuracy of the model, I also performed some text preprocessing, which involved removing punctuation, numbers, 
and stop words from the text.

Finally, I used Gradio to create a user interface for the model, allowing users to enter text and get an immediate prediction of 
the language of the text. This makes the model accessible to a wider audience and makes it easier to test its accuracy in real-world situations.

Overall, this project was a great learning experience in the field of NLP and machine learning, and I am proud to have built a language 
detection model that can accurately identify text in 18 different languages which are mentioned below:

1) English
2) Malayalam
3) Hindi
4) Tamil
5) Kannada
6) French
7) Spanish
8) Portuguese
9) Italian
10) Russian
11) Sweedish
12) Dutch
13) Arabic
14) Turkish
15) German
16) Danish
17) Greek
18) Hindi

