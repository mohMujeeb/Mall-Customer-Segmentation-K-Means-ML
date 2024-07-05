# Mall Customer Segmentation using K-means

Welcome to the Mall Customer Segmentation project repository. This project aims to segment customers of a mall using the K-means clustering algorithm. The segmentation will help in understanding customer behaviors and patterns, allowing for better marketing strategies and customer service improvements.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

Customer segmentation is the practice of dividing a customer base into groups of individuals that are similar in specific ways relevant to marketing, such as age, gender, interests, and spending habits. In this project, we use the K-means clustering algorithm to segment customers based on their annual income and spending score.

## Dataset

The dataset used in this project is provided in the repository. It includes information on customer IDs, age, gender, annual income, and spending score. The dataset file is named `Mall_Customers.csv`.

## Installation

To run this project, you need to have Python installed on your machine. You can install the necessary libraries using the following command:

```bash
pip install -r requirements.txt
```

The `requirements.txt` file contains all the required packages, including:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

## Usage

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/mall-customer-segmentation.git
    ```

2. Navigate to the project directory:
    ```bash
    cd mall-customer-segmentation
    ```

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

5. Open and run the `mall-customer-segmentation-k-means-ml.ipynb` notebook to see the data preprocessing, K-means clustering, and visualization steps.

## Project Structure

The repository contains the following files:

- `mall-customer-segmentation-k-means-ml.ipynb`: The Jupyter Notebook containing the code for data preprocessing, model training, and visualization.
- `Mall_Customers.csv`: The dataset file.
- `requirements.txt`: The file containing the list of required libraries.

## Results

The results of the customer segmentation will be displayed in the Jupyter Notebook. You will see visualizations of the clustered data, which will help in understanding the different customer segments based on their annual income and spending score.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.

