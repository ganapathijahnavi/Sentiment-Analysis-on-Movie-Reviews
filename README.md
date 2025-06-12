# Sentiment Analysis on Movie Reviews using IMDb Movie Review Dataset

### 📜Overview 
Sentiment Analysis is a key task in Natural Language Processing (NLP), aimed at classifying text based on its expressed sentiment—positive, negative, or neutral. This technique helps organizations to enhance customer satisfaction by understanding user feedback.

In this project, I conducted sentiment analysis on movie reviews using the IMDb Movie Review Dataset and developed a Gradio-based **Movie Review Sentiment Classifier**. The classifier predicts whether a review is positive or negative and provides a **word cloud** to visualize the most frequently used words.

## 🚀Project Workflow
### Step 1: Prepare the Dataset
- Used the IMDb Movie Review Dataset containing two fields: **Review** and **Sentiment** (Positive or Negative).
-       The IMDb Movie Review Dataset is sourced from Kaggle. You can access it [here](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).

### Step 2: Encode Labels
- Converted labels into numerical format (**Positive → 1, Negative → 0**).

### Step 3: Preprocess Reviews
- Applied **NLTK** for text cleaning, **stopword removal**, and **stemming & lemmatization**.

### Step 4: Train-Test Split
- Utilized **TfidfVectorizer** for feature extraction and **Logistic Regression** for classification.

### Step 5: TF-IDF Vectorization
- Transformed text data into numerical representation using **TF-IDF Vectorizer**.

### Step 6: Train Model & Evaluate
- Trained the classifier and evaluated its performance.

### Step 7: Save Model & Vectorizer
- Saved trained model and vectorizer using **joblib.dump()** for future reuse.

### Step 8: Creating the Gradio Interface
- Integrated a **Gradio-based GUI**, allowing users to input movie reviews and obtain predictions.
- Displayed a **word cloud** to highlight the most frequently occurring words in reviews.

## 🚀Installation & Usage
If you want to use and run it:
1. Clone the repository.
2. Open **"GUI.ipynb"**.
3. Run the notebook cells to execute the project.

## 📊Results 

## Output for positive review as shown
![image alt](https://github.com/ganapathijahnavi/Sentiment-Analysis-on-Movie-Reviews/blob/dd815ce0fa6812e3cfed305728f79cde5cba5021/output1.png)

##output for negative review as shown
![image alt](https://github.com/ganapathijahnavi/Sentiment-Analysis-on-Movie-Reviews/blob/dd815ce0fa6812e3cfed305728f79cde5cba5021/output2.png)

🙋‍♀️Author--> Jahnavi Durga Ganapathi, Feel free to connect or contribute!
