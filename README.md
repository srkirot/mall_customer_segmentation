# Exploring Mall Customer Behavior: Data Visualizations" 
## Charts with plotly
The task involves creating plots using the Plotly library in Python, which includes both Plotly Express and Plotly Graph Objects.

   
### Charts by Visits
- The task involves creating plots using the Plotly library in Python, which includes both Plotly Express and Plotly Graph Objects.

Explore gender, age, and annual income distributions in our mall customer dataset.

- Histograms
<img src="https://github.com/srkirot/mall_customer_segmentation/assets/166246544/2d88366f-be76-4c9e-8854-f27ba5db836b" width="800"/>

- CDFs with marginal histogram

<img src="https://github.com/srkirot/mall_customer_segmentation/assets/166246544/7a0a0713-5978-4f81-8caf-6e0ba23b6717" width="400" />


<img src="https://github.com/srkirot/mall_customer_segmentation/assets/166246544/4a01205a-95db-48b4-b8b5-2e457586242f" width="400" />


### Scatter plot of Age vs. Spending Score:

- This plot illustrates the relationship between customers' age and their spending score. Each point on the plot represents a customer, with the horizontal position (x-axis) indicating their age and the vertical position (y-axis) indicating their spending score. The dispersion of points on the plot reveals how spending scores are distributed across different age groups, providing insights into how spending behavior varies with customers' age.

<img src="https://github.com/srkirot/mall_customer_segmentation/assets/166246544/56644d73-f6d4-49dc-a8ff-844598eeb02e" width="700"/>

### Scatter plot of Age vs. Annual Income:

- This plot represents the relationship between customers' age and their annual income, segmented by gender. Each point on the plot represents a customer, with the horizontal position (x-axis) indicating their age and the vertical position (y-axis) indicating their annual income. The dispersion of points on the plot shows how annual incomes are distributed across different age and gender groups, providing information about the relationship between age, gender, and customers' income levels.

<img src="https://github.com/srkirot/mall_customer_segmentation/assets/166246544/eb730e62-cd12-4757-a4d8-418e9b40f321" width="700"/>


## Multi-factor Percentage Analysis Summary
- using PySpark and SQL Queries

Based on the provided data, it's evident that there are distinct segments of visitors at the mall, characterized by their age, income, and spending habits. Here's a comprehensive conclusion:

The analysis reveals significant differences in the behavior of young and adult customers at the mall.

#### Young Customers:

- High Income, High Spending (9%): A small percentage of young customers exhibit high income and high spending behavior. These individuals are likely to be affluent young professionals or dependents with considerable disposable income.
- Low Income, Low Spending (22%): A relatively large proportion of young customers have low income and low spending. These individuals may be students or young adults with limited financial resources, who prioritize essential purchases.
- Low Income, High Spending (18%): A notable percentage of young customers with low income display high spending behavior. This group may engage in discretionary spending despite limited financial means, possibly through the use of credit or by reallocating funds from other areas.
- High Income, Low Spending (75%): The majority of young customers with high income exhibit low spending patterns. This segment may prioritize savings or investments over immediate consumption, or they may be conservative in their spending habits despite their financial capacity.

  
#### Adult Customers:

- High Income, High Spending (14%): A small percentage of adult customers have both high income and high spending tendencies, similar to the corresponding segment of young customers. These individuals likely prioritize luxury purchases or premium experiences.
- Low Income, Low Spending (7%): A minority of adult customers exhibit low income and low spending behavior. This segment may include individuals on fixed incomes or those who are budget-conscious in their shopping habits.
- Low Income, High Spending (3%): A small percentage of adult customers with low income demonstrate high spending behavior. These individuals may engage in discretionary spending despite financial constraints, similar to the corresponding segment of young customers.
- High Income, Low Spending (54%): The majority of adult customers with high income display low spending behavior, mirroring the predominant pattern observed among young customers with high income.

  
#### Average Income and Spending:

- Young Customers (44%): Nearly half of the young customer segment exhibits average income and spending patterns. These individuals likely adhere to a balanced approach to consumption, neither overspending nor underspending relative to their income.
- Adult Customers (41%): A similar proportion of adult customers also demonstrates average income and spending behavior, suggesting a comparable level of financial prudence or discretionary spending.


 
In summary, the analysis highlights the diverse demographics and spending behaviors among mall visitors. While certain segments exhibit high income and spending, others show varying degrees of frugality or financial constraints. Understanding these distinct segments can inform targeted marketing strategies and personalized experiences to meet the specific needs and preferences of different customer groups. It's worth noting that among both young and adult consumers, women are the predominant shoppers.













