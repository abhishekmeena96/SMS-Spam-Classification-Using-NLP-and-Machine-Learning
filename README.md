# SMS-Spam-Classification-Using-NLP-and-Machine-Learning

# SMS Spam Classification using NLP and Machine Learning

### 1. Data Collection
- Use a dataset containing SMS messages labeled as "ham" (not spam) or "spam" (unwanted messages).
- Example: **SMS Spam Collection dataset**.

### 2. Data Preprocessing
- **Text Cleaning**: Remove unnecessary characters, punctuation, and stop words.
- **Tokenization**: Split the text into individual words (tokens).
- **Vectorization**: Convert text into numerical form using:
  - **Bag of Words (BoW)**, or
  - **TF-IDF (Term Frequency-Inverse Document Frequency)**.

### 3. Exploratory Data Analysis (EDA)
- Analyze and visualize the distribution of spam and ham messages.
- Tools: **Word clouds**, **frequency charts**.

### 4. Model Building
- Use machine learning classifiers like:
  - **Naive Bayes** (common for text classification),
  - **Logistic Regression**, or
  - **Support Vector Machines (SVM)**.
- Split data into training and test sets (e.g., 80/20 split).

### 5. Model Training
- Train the model using vectorized SMS data.
- Tune hyperparameters for better performance.

### 6. Model Evaluation
- Evaluate using metrics like:
  - **Accuracy**: Correctness of predictions.
  - **Precision**: Spam detection accuracy.
  - **Recall**: How well actual spam is detected.
  - **F1-Score**: Balance between precision and recall.

### 7. Fine-Tuning and Optimization
- Experiment with different algorithms, feature extraction techniques, and use **cross-validation**.

### 8. Final Results
- Well-performing models can achieve:
  - **Accuracy**: ~98%
  - **Precision**: ~99%
  - **Recall**: ~98%
