# Sentiment Analysis

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Model Performance](#model-performance)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project performs **Sentiment Analysis** on text data, classifying tweets or reviews as **positive, negative**, or **neutral**. Sentiment analysis helps businesses and researchers gain insights into public opinion, customer feedback, and social trends. The project leverages **PyTorch** to build a deep learning model that can efficiently process and analyze large volumes of text data.

## Features
- **Sentiment Classification**: Predicts if a given text is positive, negative, or neutral.
- **PyTorch Implementation**: Uses PyTorch to build a deep learning model for sentiment analysis.
- **Preprocessed Dataset**: Uses a Twitter dataset for training and testing the model.
- **Jupyter Notebooks**: Interactive notebooks for training, evaluation, and visualization.
- **Easy Customization**: Adaptable for other types of text data or sentiment scoring.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/rohanpashikanti/sentiment-analysis.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd sentiment-analysis
    ```

3. **Create a virtual environment** (optional but recommended):
    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows: env\Scripts\activate
    ```

4. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

5. **Download the dataset** (if not included):
    Place your dataset (e.g., `Twitter_Data.csv`) in the `/data` folder.

## Usage

Once the setup is complete, you can run the Jupyter notebooks for training and analysis:

1. **Open the notebooks**:
    ```bash
    jupyter notebook
    ```

2. **Train the model**:
    Open `pytorch_sentiment_analysis.ipynb` to train the model on the Twitter dataset.

3. **Evaluate the model**:
    After training, evaluate model performance using the provided evaluation scripts.

4. **Analyze new data**:
    Modify the input data in `sentiment_analysis.ipynb` to analyze new tweets or text data.

## Technologies
- **Python**: Programming language.
- **PyTorch**: Deep learning framework for building and training models.
- **Pandas & NumPy**: For data manipulation and preprocessing.
- **Jupyter Notebook**: For running interactive scripts.
- **Natural Language Toolkit (NLTK)**: For text preprocessing (optional).

## Model Performance
- **Accuracy**: 89%
- **Precision**: 87%
- **Recall**: 85%
- **F1 Score**: 86%

Model performance may vary based on the dataset and tuning parameters.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements, bug fixes, or new features.

