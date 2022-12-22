# Customer Segmentation :family: :family: :family:
__Cluster analysis__ to segment customers in an American shopping mall.

The following paper is divided into three parts:
1. preliminary exploratory analysis
2. cluster hierarchical analysis
3. cluster analysis of non-hierarchical type

### Dataset :bar_chart:
The dataset consists of 200 records and 5 variables:
Variable | Description
-|-
Customer ID | mall customer ID code
Gender | gender of the client
Age | Age of the client
Annual_Income | annual income received by the customer in thousands of dollars $
Spending_Score | score given to each customer based on his or her purchasing behaviors(0-100)

### Preliminary exploratory Analysis :mag:
Exploratory analysis allows you to identify whether there are null values and plot some graphs to identify relationships between variables.
In detail, we plotted the frequency distributions of annual income and spending score. In addition, the ratio of males to females confirms that 56% of the observations are females, the remainder males.
Finally, a bar graph shows the age density distribution.

### Cluster Analysis :bulb:
Cluster Analysis aims to group customers in order to identify which among them can potentially be influenced by marketing policies.
We used both hierarchical and non hierarchical algorithms, like K-means.

We evaluated the performance of the analysis through metrics such as Silhouette score and Pseudo-F index.
