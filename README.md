# Project 3 - Sentiment Analysis of Fan and Stakeholder Perception on VAR Decisions Across Different Football Leagues  

## 📖 Overview  
This project explores how football fans and stakeholders perceive Video Assistant Referee (VAR) decisions across different leagues using sentiment analysis on public data available online. By analyzing fan and stakeholder reactions from platforms like Twitter, Reddit, and Web pages, the research aims to identify trends, biases, and patterns in sentiment towards VAR as a macth official.  

## 🎯 Objectives  
- Collect and preprocess football-related social media data discussing VAR decisions.  
- Perform sentiment analysis using NLP techniques to classify fan opinions as positive, neutral, or negative.  
- Compare sentiment trends across major football leagues (e.g., EPL, La Liga, Serie A, Bundesliga).   
- Provide insights that could help football governing bodies, clubs, and analysts understand how VAR impacts fan sentiment.

## Installation Guide for Running the Jupyter Notebook 
## 🚀 Accessing the Notebook  

1. **Clone the Repository:**  
   - Download the project by cloning the GitHub repository.  
   - Open the repository folder and navigate to:
     VAR Sentiment Analysis → models → finalProject3.ipynb

2. **Running the Notebook:**  
You can run the notebook on platforms that support Jupyter notebooks, such as:  

- **Google Colab:**  
  - Go to [Google Colab](https://colab.research.google.com).  
  - Click **"File" → "Upload notebook"**.  
  - Select the `finalProject3.ipynb` file and run it.  

- **Kaggle:**  
  - Go to [Kaggle](https://www.kaggle.com/).  
  - Create a new notebook.  
  - Click **"Add Data" → "Upload a file"**.  
  - Select the `finalProject3.ipynb` file and run the cells.  

- **Local Jupyter Notebook:**  
  - Open your terminal or command prompt.  
  - Navigate to the project folder.  
  - Launch the notebook and run the cells.  

---

## ⚙️ Required Libraries  
Ensure you have the following Python libraries installed before running the notebook:  
- **pandas**  
- **numpy**  
- **matplotlib**  
- **seaborn**  
- **scikit-learn**  
- **nltk**  
- **snscrape**  

## 🗝️ Key Features  
- **Multi-League Sentiment Comparison**: Examines how VAR-related sentiment differs between football leagues.  
- **NLP-Driven Sentiment Classification**: Uses natural language processing techniques to assess fan reactions.  
- **Data Visualization**: Generates insightful graphs, word clouds, and trend analyses for better interpretation.  

## 💡 Expected Outcomes  
- Identification of leagues where VAR is more controversial among fans, hence greater negative sentiment.  
- Comparative statistics highlighting major differences in how VAR is received in different football cultures.
- Provide insights on user engagement and potential areas for improving VAR implementation.

## ✅ Actual Outcomes
The sentiment analysis on Video Assistant Referee (VAR) decisions across different football leagues revealed a similarity in fan perception. Below are key findings from our analysis:

### 1. Confusion Matrix for Sentiment Classification
![Confusion Matrix](path/to/your/image1.jpg)  

- The model performed well in classifying negative, neutral, and positive sentiments.
- Negative sentiment was most accurately classified, while neutral and positive sentiments also showed strong classification performance.

### 2. Sentiment Label Distribution by League
![Sentiment Label Distribution](path/to/your/image2.jpg)  

- The Premier League had the highest number of negative sentiments compared to other leagues.
- Bundesliga, La Liga, and Serie A had a more balanced distribution, with neutral and positive sentiments present but less frequent.

### 3. Average Sentiment Score by League
![Average Sentiment Score](path/to/your/image3.jpg)  

- The overall sentiment scores were:
  - **Bundesliga:** -0.25  
  - **La Liga:** -0.27  
  - **Premier League:** -0.11  
  - **Serie A:** -0.11  
- La Liga had the most negative sentiment, while the Premier League and Serie A had the least negativity.
- Bundesliga and La Liga exhibited more dissatisfaction with VAR decisions compared to other leagues.

These findings provide valuable insights into how different leagues perceive VAR decisions, which can help governing bodies improve decision-making transparency and fan communication.

## 🪪 Licences 
N/A
