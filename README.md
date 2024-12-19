# Movie-Recommendation-System

This repository contains a Movie Recommendation System that utilizes various machine learning algorithms to categorize movie ratings and predict user preferences. The project demonstrates the use of Python libraries such as pandas, sklearn, seaborn, and matplotlib for data analysis and visualization.

## Features

- **Data Preprocessing**: Cleans and encodes the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Includes heatmaps and bar charts to visualize correlations and distributions.
- **Model Training**: Implements multiple classifiers:
  - Gaussian Naive Bayes
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
- **Hyperparameter Tuning**: Utilizes GridSearchCV for optimizing hyperparameters.
- **Model Evaluation**: Measures accuracy and F1 scores for model comparisons.
- **Visualization**: Compares model performance using bar graphs.

## Prerequisites

- Python 3.7 or above
- Required libraries:
  - pandas
  - seaborn
  - matplotlib
  - scikit-learn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Movie-Recommendation-System.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Movie-Recommendation-System
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset

The project uses two datasets:
- `movies.csv`: Contains movie details.
- `ratings.csv`: Contains user ratings for movies.

Place these files in the project directory before running the code.

## Usage

1. Open the `Movie_Recommendation1.ipynb` file in Jupyter Notebook or Google Colab.
2. Update the file paths for `movies.csv` and `ratings.csv` to their respective locations.
3. Run the notebook cells to:
   - Load and preprocess the data
   - Train and evaluate models
   - Visualize results

## Results

- The project compares four classifiers based on accuracy and F1 scores.
- Visualizations display the distribution of ratings and model performances.

## Key Files

- `Movie_Recommendation1.ipynb`: Main notebook containing the implementation.
- `movies.csv` and `ratings.csv`: Datasets used for the project.

## Future Enhancements

- Integrate advanced recommendation algorithms like collaborative filtering.
- Add a user-friendly interface for real-time recommendations.
- Incorporate additional features such as genre and metadata for improved predictions.
