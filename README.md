
# Twitter Sentiment Analysis

## Overview

This project is a Twitter sentiment analysis application built using Flask. The application allows users to analyze the sentiment of tweets based on a specific keyword or hashtag provided in a CSV file. It leverages Natural Language Processing (NLP) techniques to classify tweets as positive, negative, or neutral.

## Features

- **Sentiment Analysis**: Analyzes the sentiment of each tweet and categorizes it as positive, negative, or neutral.
- **Data Visualization**: Provides visual representations of the sentiment distribution using charts.

## Technologies Used

- **Flask**: A micro web framework for Python to build the web application.
- **Pandas**: For data manipulation and analysis.
- **NLTK**: Natural Language Toolkit for performing sentiment analysis.
- **Matplotlib/Plotly**: For data visualization of sentiment analysis results.
- **HTML/CSS/JavaScript**: For frontend development.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/twitter-sentiment-analysis.git
   cd twitter-sentiment-analysis
   ```

2. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

4. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask application:

   ```bash
   python app.py
   ```

2. Open your web browser and go to `http://127.0.0.1:5000`.



## Acknowledgments

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NLTK Documentation](https://www.nltk.org/)
- [Flask Documentation](https://flask.palletsprojects.com/)
