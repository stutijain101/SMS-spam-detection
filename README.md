# SMS Spam Detection

This project focuses on building a robust machine learning model to classify SMS messages as either spam or ham (not spam). The project follows a structured approach involving data cleaning, exploratory data analysis (EDA), text preprocessing, model building, evaluation, improvement, and deployment.

### Dataset
Source: SMS Spam Collection Data Set
- Original Size: 5572 rows and 5 columns
- After Cleaning: 5169 rows and 2 columns

### Project Steps
1. Data Cleaning
Removed unnecessary columns and handled missing values.
Mapped the labels to binary values: ham to 0 and spam to 1.
Resulted in a cleaned dataset of shape (5169, 2).
2. Exploratory Data Analysis (EDA)
Analyzed the distribution of messages:
87.37% ham messages
12.63% spam messages
3. Text Preprocessing
Converted text to lowercase.
Tokenized the text.
Removed special characters.
Removed stop words and punctuation.
Applied stemming to reduce words to their root form.

4. Model Building

- Gaussian Naive Bayes:
Accuracy: 0.87
Precision Score: 0.564 (indicating low performance)


- Multinomial Naive Bayes:
Accuracy: 0.972
Confusion Matrix:
[[896   0]
 [ 29 109]]
Precision Score: 1.0 (indicating high performance)

- Bernoulli Naive Bayes:
Accuracy: 0.984
Confusion Matrix:[[895   1]
 [ 16 122]]
Precision Score: 0.992

#### Best Performing Model: Multinomial Naive Bayes
- Accuracy: 0.972
- Precision: 1.0

5. Evaluation
Multinomial Naive Bayes outperformed other models in terms of both accuracy and precision.
#### Final accuracy achieved: 0.972
6. Improved the model performance through hyperparameter tuning and advanced preprocessing techniques.
#### Increased accuracy from 0.959 to 0.972.





## Technologies Use
#### Programming Language
- Python: Used for all data processing  analysis, and machine learning tasks.
#### Libraries and Frameworks
- pandas: Data manipulation and analysis.
- numpy: Numerical computing.
- scikit-learn: Machine learning library used for model building, training, and evaluation.
- nltk: Natural Language Toolkit for text preprocessing tasks like tokenization, removing stop words, and stemming.

#### Tools
- Jupyter Notebook: Interactive environment for running Python code and visualizing results.

## Screenshots
#### percentage of spam and ham messages
![WhatsApp Image 2024-07-19 at 6 06 27 PM](https://github.com/user-attachments/assets/80b0f2aa-dddd-4167-a7ee-6afb40f8d603)

![WhatsApp Image 2024-07-19 at 6 06 27 PM (1)](https://github.com/user-attachments/assets/05f9e45e-bd8e-49eb-9304-de2d42bbc2e1)


![WhatsApp Image 2024-07-19 at 6 06 26 PM](https://github.com/user-attachments/assets/a2a8a2cf-0fbe-4f07-a24f-0b1efb1901c0)

#### top 30 words used in spam messages
![WhatsApp Image 2024-07-19 at 6 17 30 PM](https://github.com/user-attachments/assets/b9724b89-5f96-4b47-a0bf-d5ad7e9f99c1)


#### Top 30 words used in normal sms
![WhatsApp Image 2024-07-19 at 6 06 25 PM](https://github.com/user-attachments/assets/561c0d3c-6b33-40d9-9f8a-3ca58be81c87)

#### comparison graph for all the data models on the basis of precision and accuracy
![WhatsApp Image 2024-07-19 at 6 06 25 PM (1)](https://github.com/user-attachments/assets/f73c45a9-7146-48ac-9684-72eb0192e426)



## Installation

  Clone the repository:
  git clone https://github.com/yourusername/sms-spam-detection.git


  cd sms-spam-detection

- Install the required packages:
  pip install -r requirements.txt

- Start Jupyter Notebook:
  jupyter notebook (and run it)
## Feedback

If you have any feedback, please reach out to us at stutijain2705@gmail.com

