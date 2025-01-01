# **TwiPipeline - Twitter/X Data Analysis Pipeline**  

## **Project Description**  
TwiPipeline is a comprehensive Python-based project designed to perform data retrieval, preprocessing, and analysis of tweets using the **Twitter/X API**. It focuses on cybersecurity-related tweets, leveraging Natural Language Processing (NLP) techniques, sentiment analysis, entity recognition, and visualization to derive insights.  

---

## **Key Features**  

1. **Twitter API Integration**  
   - Retrieves tweets based on keywords like **#cybersecurity** using the Twitter/X API.  
   - Supports Bearer Token authentication.  

2. **Data Preprocessing**  
   - Cleans raw tweets by removing URLs, special characters, and stopwords.  
   - Performs tokenization, lemmatization, and text normalization.  

3. **Exploratory Data Analysis (EDA)**  
   - Analyzes hashtags and mentions.  
   - Generates word clouds and frequency distributions for insights.  

4. **Natural Language Processing (NLP)**  
   - Sentiment Analysis to classify tweets as **Positive**, **Neutral**, or **Negative**.  
   - Named Entity Recognition (NER) to identify people, organizations, and locations.  
   - Text augmentation to generate more training data.  

5. **Data Transformation and Export**  
   - Saves processed data in **CSV** format.  
   - Loads structured data into **SQLite databases** for scalability and integrity checks.  

6. **Visualization**  
   - Generates visual representations such as word clouds, bar charts, and network graphs to analyze relationships between entities.  

7. **Unit Testing and Validation**  
   - Includes unit tests for validating text transformations and database integrity.  

---

## **Technologies and Libraries Used**  

- **Python** - Core programming language.  
- **Libraries**:  
  - **Data Handling**: `pandas`, `numpy`.  
  - **API Requests**: `requests`, `yaml`.  
  - **Visualization**: `matplotlib`, `seaborn`, `wordcloud`, `networkx`.  
  - **Natural Language Processing (NLP)**: `nltk`, `spacy`, `textblob`.  
  - **Database Management**: `sqlite3`.  
  - **Testing**: Built-in `assert` statements.  

---

## **Workflow**  

### **1. Data Retrieval**  
- Uses Twitter/X API to fetch recent tweets based on a keyword.  
- Processes and stores tweets in JSON format.  

### **2. Data Preprocessing**  
- Cleans raw text data by removing stopwords, special characters, and URLs.  
- Applies lemmatization and tokenization techniques.  

### **3. Exploratory Data Analysis**  
- Analyzes hashtags and mentions using frequency distributions.  
- Visualizes patterns with bar plots and word clouds.  

### **4. NLP Techniques**  
- Sentiment Analysis: Classifies text polarity as Positive, Neutral, or Negative.  
- Named Entity Recognition: Identifies entities (names, organizations, etc.) using SpaCy.  
- Text Augmentation: Generates synthetic data to improve NLP model performance.  

### **5. Data Export**  
- Saves processed data as **CSV files**.  
- Loads data into an **SQLite Database** with integrity checks.  

---

## **Installation and Setup**  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/athulrj02/TwiPipeline.git
   cd TwiPipeline
   ```

2. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Configuration**  
   - Update your Bearer Token in the `config.yaml` file for API authentication.  

4. **Run the Notebook**  
   - Access the notebook using the following Google Colab link:  
     [TwiPipeline Notebook](https://colab.research.google.com/drive/1j1GtFxS3OhppPh96lXqM7SPVCU60L98V?authuser=2)  

---

## **Outputs and Visualizations**  

1. **Descriptive Statistics**  
   - Summarizes data columns, missing values, and distribution.  

2. **Hashtag and Mention Analysis**  
   - Lists the most frequent hashtags and mentions in tweets.  

3. **Word Clouds**  
   - Graphical visualization of common words in tweets.  

4. **Sentiment Distribution**  
   - Plots sentiment scores (positive, neutral, negative).  

5. **Named Entity Visualization**  
   - Displays entity relationships using network graphs.  

6. **Database Integration**  
   - Stores processed data in an SQLite database for scalability.  

---

## **Limitations**  

- Twitter API has a **100 pulls/month** cap for free-tier access.  
- Data analysis focuses on **cybersecurity**, but can be extended to other topics.  
- Sentiment analysis relies on **TextBlob**, which may not capture nuanced sentiments.  

---

## **Applications**  

- Cybersecurity Trend Analysis.  
- Social Media Monitoring.  
- Sentiment Analysis for Public Opinion.  
- Entity Recognition for Organizational Insights.  

---

## **Contributors**  
- **Athul Raj** - Developer  
- GitHub: [athulrj02](https://github.com/athulrj02)  
