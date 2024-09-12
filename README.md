# Sentiment Analysis on Social Media Data

This repository contains a project that performs sentiment analysis and visualization of social media data to understand public opinion and attitudes towards specific topics or brands.

## Table of Contents
1. [Project Description](#project-description)
2. [Installation](#installation)
3. [Dataset](#dataset)
4. [Code and Analysis](#code-and-analysis)
5. [Results](#results)
6. [How to Run](#how-to-run)
7. [License](#license)

## Project Description
The project involves:
- Cleaning and preprocessing social media text data.
- Performing sentiment analysis to categorize sentiments as Positive, Negative, or Neutral.
- Visualizing sentiment distribution and generating a word cloud to understand common themes.

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/sentiment-analysis-social-media.git
    ```
2. Navigate into the project directory:
    ```bash
    cd sentiment-analysis-social-media
    ```
3. Install the required Python libraries using:
    ```bash
    pip install -r requirements.txt
    ```

## Dataset
The dataset used for this project is the Twitter sentiment analysis dataset. It can be downloaded from [Kaggle](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis). If included, the dataset file is `twitter_validation.csv`.

## Code and Analysis
The notebook (`.ipynb`) and Python script (`.py`) files include the code for:
- Data Cleaning:
  - Removing punctuation and stopwords.
- Sentiment Analysis:
  - Categorizing sentiments using TextBlob.
- Visualizations:
  - Sentiment Distribution Bar Plot.
  - Word Cloud of Tweets.

## Results
Key visualizations from the analysis include:
- **Sentiment Distribution**:
  ![Sentiment Distribution](sentiment_distribution.png)
- **Word Cloud**:
  ![Word Cloud](wordcloud.png)

## How to Run
1. To run the project, open the `sentiment_analysis.ipynb` file in Google Colab or Jupyter Notebook and execute the cells step-by-step.
2. If using the Python script:
    ```bash
    python sentiment_analysis.py
    ```

## License
This project is licensed under the MIT License.
