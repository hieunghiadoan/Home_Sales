#  SparkSQL Analysis of Home Sales Data: Uncovering Key Metrics

In this project, we employ SparkSQL to conduct an in-depth analysis of home sales data with the primary objective of extracting essential metrics related to home sales, including average prices and view ratings. The project encompasses a series of crucial tasks, such as the creation of temporary views, data partitioning, caching, uncaching of temporary tables, and verification of the uncaching process. Furthermore, we leverage SparkSQL queries to address pertinent questions about the dataset, notably focusing on computing the average price of four-bedroom houses for each year and determining the average price of homes featuring three bedrooms, three bathrooms, two floors, and a minimum square footage of 2,000 for each year of construction.

**Project Components and Evaluation Criteria:**

1. **Creation of Spark DataFrame**: Successful completion of the project begins with the creation of a Spark DataFrame that encapsulates the home sales dataset.

2. **Creation of Temporary Table**: Next, a temporary table is generated from the original DataFrame, providing a structured foundation for subsequent queries.

3. **Partitioned Data**: Data partitioning is employed to optimize query performance, ensuring that specific subsets of data are readily accessible.

4. **Caching and Uncaching**: Temporary tables are cached and subsequently uncached to manage data retrieval efficiency. Successful execution of these operations is critical.

5. **SparkSQL Queries**: A series of SparkSQL queries are formulated and executed to derive key insights from the data. These queries include calculating the average price for four-bedroom houses by year and determining the average price of homes meeting specific criteria for each year of construction.

**Evaluation Criteria**:
- Successful creation of a Spark DataFrame.
- Effective generation of a temporary table derived from the original DataFrame.
- Implementation of data partitioning techniques.
- Proper caching and uncaching of temporary tables to optimize performance.
- Accurate execution of SparkSQL queries to answer critical questions regarding home sales data.

This project represents a comprehensive exploration of home sales data using SparkSQL, enabling us to extract valuable insights and metrics to inform decision-making processes within the real estate domain.
