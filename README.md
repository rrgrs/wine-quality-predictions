# Predicting Wine Quality with Machine Learning

This is a machine learning project aimed at predicting wine quality from various wine attributes. Using a dataset that details characteristics like acidity, sugar levels, and alcohol content, we employ supervised learning models to forecast wine scores. This project is designed for anyone interested in the intersection of data science and wine, offering tools to assess wine quality scientifically.

## Requirements

This project requires:
- Python 3.9
- [Poetry package installer](https://python-poetry.org/docs/#installation)

Ensure you have these installed before proceeding with the setup.

## Setup

To set up this project, follow these steps:

1. **Install Dependencies and Create .env File**: Run `make install`
2. **Kaggle API Key**: Go to the [Kaggle settings page](https://www.kaggle.com/settings), generate an API token, and copy the token valyes into the `.env` file. This step is necessary for accessing the Kaggle dataset.

## Run

To run the project, simply execute the following command: `make run`
This will start a Jupyter notebook server, allowing you to open and run the notebook files in your project.