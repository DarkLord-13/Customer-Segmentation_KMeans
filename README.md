# Customer Segmentation

This project aims to classify customers into different groups based on their annual income and spending score using the K-Means clustering algorithm. This segmentation helps in making informed and targeted business decisions in a retail context.

## Project Overview

The project follows these main steps:
1. **Data Collection and Analysis**:
    - Load the dataset.
    - Perform exploratory data analysis.
2. **Data Preprocessing**:
    - Handle missing values.
    - Select relevant features for clustering.
3. **Model Training**:
    - Use the Elbow method to determine the optimal number of clusters.
    - Train the K-Means clustering model with the optimal number of clusters.
4. **Model Evaluation**:
    - Visualize the clusters and their centroids.

## Dependencies

The project requires the following dependencies:
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/DarkLord-13/Machine-Learning-01.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Machine-Learning-01
    ```

3. Install the required packages:
    ```sh
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

4. Open the Jupyter Notebook `CustomerSegmentation.ipynb` and run the cells to execute the project steps:
    ```sh
    jupyter notebook CustomerSegmentation.ipynb
    ```

## Usage

1. **Data Collection and Analysis**:
    - Load the dataset using Pandas.
    - Perform exploratory data analysis to understand the data distribution.

2. **Data Preprocessing**:
    - Handle missing values if any.
    - Select relevant features (`Annual Income` and `Spending Score`) for clustering.

3. **Model Training**:
    - Use the Elbow method to determine the optimal number of clusters.
    - Train a K-Means clustering model on the selected features.

4. **Model Evaluation**:
    - Visualize the clusters and their centroids using scatter plots.

## Results

The trained K-Means model will classify customers into different clusters based on their annual income and spending score. These clusters are visualized using scatter plots, showing the distinct groups and their centroids.

## License

This project is licensed under the MIT License.
