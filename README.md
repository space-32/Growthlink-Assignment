# Growthlink-Assignment
his project focuses on building a machine learning model to classify SMS messages as spam or non-spam. It uses deep learning techniques, specifically an LSTM (Long Short-Term Memory) network, to learn patterns from the text data and make accurate predictions.


SMS Spam Detection using LSTM
Task Objectives
Develop a classification model that accurately identifies spam and non-spam SMS messages.
Apply proper data preprocessing techniques for textual data.
Build a deep learning model (LSTM) for binary classification.
Evaluate model performance using accuracy.
Ensure clean, well-documented, and efficient implementation.

Project Steps and How to Run
1. Clone the Repository
git clone https://github.com/space-32/Growthlink-Assignment.git
cd sms-spam-detection
2. Install Required Packages
Make sure you have the following installed:
pip install tensorflow scikit-learn numpy pandas
3. Prepare the Dataset
Place your Spam SMS dataset (CSV file) in the project folder.
Ensure the dataset has two columns:
label → spam or ham (non-spam)
message → the SMS text
4. Run the Model
Simply execute the notebook or script:
python sms_spam_detection.py
The model will:
Preprocess the text.
Tokenize and pad sequences.


Build and train an LSTM model.
Output training and evaluation results.
Code Structure and Cleanliness
Code is divided into logical blocks:
Data Loading
Data Preprocessing
Tokenization and Padding
Model Building
Training and Evaluation
Every major step is clearly commented for easy understanding.
Variables and function names are meaningful and follow clean coding practices.
No unnecessary prints or random codes included — focus is on clarity.

Model Summary
Model Used: LSTM-based Sequential Model
Training Epochs: 5
Batch Size: 64
Test Set Accuracy: 86.5%

Possible Future Improvements
Using Bidirectional LSTM to capture context better.
Integrating Pretrained Embeddings (like GloVe, Word2Vec).
Trying more advanced architectures like GRU or Transformer models.
Hyperparameter tuning for further boosting performance.

