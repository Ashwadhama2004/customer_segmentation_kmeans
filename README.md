# customer_segmentation_kmeans

```markdown
# Customer Segmentation using K-Means Clustering

This project focuses on customer segmentation using the K-Means clustering algorithm. It analyzes customer data and groups them into clusters based on their annual income and spending score. The model helps in identifying distinct customer segments which can be useful for targeted marketing strategies.

## Dataset
The dataset used for this project is the "Mall_Customers.csv" file. It contains information about customers' annual income and spending scores.

- **Annual Income (k$)**: Customers' annual income in thousands of dollars.
- **Spending Score (1-100)**: Score assigned by the mall, based on customer behavior and spending nature.

## K-Means Clustering
The K-Means clustering algorithm divides customers into clusters based on their similarities. In this project, the elbow method is used to determine the optimal number of clusters, which was found to be 5.

## Visualization
The project visualizes the customer clusters on a scatter plot, with each cluster represented by a distinct color and the centroids marked in black.

## Repository Structure
- `Mall_Customers.csv`: Dataset used for clustering.
- `customer_segmentation.py`: Python script containing the implementation of the K-Means clustering algorithm.
- `README.md`: Project documentation.
- `LICENSE`: MIT License for the repository.

## Requirements
To run this project, you need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install the required libraries using:
```bash
pip install -r requirements.txt
```

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/Ashwadhama2004/customer_segmentation_kmeans.git
    ```
2. Navigate to the project directory:
    ```bash
    cd customer_segmentation_kmeans
    ```
3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Python script to perform customer segmentation:
    ```bash
    python customer_segmentation.py
    ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Repository Link
[GitHub Repository](https://github.com/Ashwadhama2004/customer_segmentation_kmeans)
```

You can modify it as needed, and add additional details specific to your project if necessary!
