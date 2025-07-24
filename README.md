# Financial-Sentiment-Analysis
# Financial Sentiment Analysis is a specialized field of Natural Language Processing (NLP) that focuses on extracting insights and sentiments from financial texts. It helps investors and financial institutions make informed decisions by analyzing how news, social media, and other textual data influence market sentiment and asset prices. This analysis is vital for understanding market trends, risks, and opportunities in real-time.


### **Step-by-Step Sentiment Analysis Pipeline**

1. **Data Collection**

   * Downloaded a financial text dataset from **Kaggle** containing labeled statements as **positive**, **negative**, or **neutral**.

2. **Data Preprocessing**

   * Cleaned the text by removing punctuation, converting to lowercase, removing numbers, and filtering out **stopwords**.

3. **Data Loading**

   * Loaded the cleaned dataset into a pandas DataFrame for analysis and modeling.

4. **Exploratory Data Analysis (EDA)**

   * Analyzed the class distribution, word frequencies, and sample text lengths to understand data patterns.

5. **Word Cloud Visualization**

   * Created separate **word clouds** for positive, negative, and neutral classes to highlight frequently occurring words.

6. **Feature Extraction using CountVectorizer**

   * Converted textual data into numerical format using **`CountVectorizer`**, transforming words into a matrix of token counts.

7. **Model Training and Evaluation**

   * Trained multiple models:

     * `LogisticRegression(C=1e-9, solver='liblinear', max_iter=200)`
     * `KNeighborsClassifier(n_neighbors=3)`
     * `DecisionTreeClassifier()`
     * `RandomForestClassifier()`
   * Compared their accuracies, which ranged between **55–60%**, and analyzed their performance on classification tasks.


