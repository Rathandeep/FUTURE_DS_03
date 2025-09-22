# Future Interns - Data Science Task 3

## College Event Feedback Analysis

### Project Objective
This project is the solution for Task 3 of the Future Interns Data Science & Analytics internship. The primary goal is to perform Natural Language Processing (NLP) and Sentiment Analysis on feedback collected from a college event. By analyzing the text data, we aim to uncover satisfaction trends, gauge overall student sentiment, and identify key themes present in the feedback.

---

### Tools and Libraries
* **Language:** Python
* **Core Libraries:**
    * `pandas` for data manipulation and analysis.
    * `nltk` & `TextBlob` for text preprocessing and sentiment analysis.
    * `matplotlib` & `seaborn` for data visualization.
    * `wordcloud` for creating a word cloud visualization.

---

### Project Workflow
1.  **Data Loading & Cleaning:** The feedback dataset was loaded into a pandas DataFrame, and initial checks for null values were performed.
2.  **Text Preprocessing:** The raw feedback text was thoroughly cleaned and prepared for analysis through a series of standard NLP steps:
    * Conversion to lowercase
    * Removal of punctuation
    * Tokenization (splitting text into individual words)
    * Removal of common English stopwords (e.g., "the", "a", "is")
    * Lemmatization (reducing words to their base or root form)
3.  **Sentiment Analysis:** The `TextBlob` library was utilized to calculate a sentiment polarity score for each piece of feedback. Based on this score, the feedback was classified into **Positive**, **Negative**, or **Neutral** categories.
4.  **Data Visualization:** Several charts were created to visually represent the findings and provide clear, actionable insights from the feedback data.

---

### Key Visualizations and Findings

**1. Sentiment Distribution**
A count plot was generated to show the distribution of Positive, Negative, and Neutral feedback, providing a quick overview of general student sentiment.
![Sentiment Distribution Chart](Task%203%20Img%201.jpeg)

**2. Word Cloud**
A word cloud was created from the processed text to highlight the most frequently mentioned words and themes in the feedback, offering insight into what was most memorable for the attendees.
![Feedback Word Cloud](Task%203%20Img%202.jpeg)

**3. Rating Distribution**
A bar chart was used to visualize the distribution of numerical ratings provided by the students, showing the frequency of each rating score.
![Rating Distribution Chart](Task%203%20Img%203.jpeg)