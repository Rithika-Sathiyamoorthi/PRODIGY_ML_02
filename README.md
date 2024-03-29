## Customer Segmentation using K-means Clustering

This project demonstrates how to use K-means clustering algorithm to group customers of a retail store based on their purchase history. The dataset contains information about customers including their gender, age, annual income, and spending score. In this project, we focus on clustering customers based on their annual income and spending score.

## Dataset

The dataset used in this project contains the following columns:

- CustomerID: Unique identifier for each customer
- Gender: Gender of the customer
- Age: Age of the customer
- Annual Income (k$): Annual income of the customer in thousands of dollars
- Spending Score (1-100): Spending score assigned to the customer based on their purchasing behavior and past interactions

## Installation

1. Clone the repository: git@github.com:praveenkumaroo2/PRODIGY_ML_02.git

   ## Usage

1. Place your dataset file (e.g., Mall_Customer.csv) inside the project directory.
2. Update the `data = pd.read_csv('Mall_Customer.csv')` line in the Python script with the correct path to your dataset file.
3. Run the Python script:
## Results

The script will perform K-means clustering on the dataset and visualize the resulting clusters based on annual income and spending score. You can adjust the number of clusters based on the Elbow method plot generated by the script.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.

