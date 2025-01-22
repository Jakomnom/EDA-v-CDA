# Exploratory vs Confirmatory Data Analysis

In this project, we are going to learn about two important data analysis methods EDA (Exploratory Data Analysis) and CDA (Confirmatory Data Analysis).

This project aims to emphasize the core skill of a data analyst: the ability to extract meaningful insights from data regardless of the specific business domain.

Here's why this is crucial:

Adaptability: In the real world, you'll encounter a wide variety of clients and industries. The ability to quickly adapt to new business contexts is essential.
Focus on Data Patterns: The core of data analysis lies in identifying patterns, trends, and relationships within the data itself.
Data-Driven Approach: By focusing on the data and its inherent characteristics, you can uncover valuable insights that might not be immediately apparent to someone with only business domain knowledge.

However:

Business Context Enhances Analysis: While it's possible to extract some insights without deep business knowledge, understanding the context significantly enhances the analysis. It allows you to:
Frame questions more effectively:
Interpret findings more accurately:
Provide more relevant and actionable recommendations.

Hence, EDA and CDA goes hand in hand.

The dataset we're going to work with is a dataset containing information about product sales in the U.S. The only thing we know about this dataset is that it's cleaned and ready to go.

Let's start with the usual loading of the datasets. 

![image](https://github.com/user-attachments/assets/c3b946b3-33e5-4485-8f76-6bc2103bc7ca)

Once loaded up, let's come up with some questions on how to start our exploration:

- Different column data types
- How are the columns related
- What are the different information in our data
- Make a list of the information and start from the first row

![image](https://github.com/user-attachments/assets/f2714d96-d319-4fe1-b737-253eb87186f4)

Here are some key insights we can gather from the above:

* There's a mix of profitable and unprofitable sales (notice the negative profit of -383.0310 for the Bretford table)
* Some customers appear multiple times (e.g., Claire Gute, Sean O'Donnell) suggesting repeat business
* The data spans multiple states and product categories, indicating a nationwide business with diverse product offerings
* Order quantities are relatively small (2-5 units), suggesting this might be a B2C or small B2B business
* The sales values vary significantly, from around $22 to $731, showing a wide price range in the product catalog

Time Analysis is always a good idea whenever we want to see trends, so let's do that next.

![image](https://github.com/user-attachments/assets/bc7e9edb-c78f-464e-987e-27e0b214314a)

Key Insights:

* The dataset covers a substantial period (4 years), making it suitable for trend analysis
* Early 2014 data shows a focus on office supplies with varying profitability
* Some customers (like Phillina Ober) made multiple purchases on the same day
* The chronological sort reveals that the original data wasn't time-ordered
* Breaking out date components will facilitate various types of temporal analysis

![image](https://github.com/user-attachments/assets/1058df5a-f580-449a-ae7c-27c530658c09)

Analyze the monthly profits gained from sales of different product categories. Use a linechart to visualize results.

![image](https://github.com/user-attachments/assets/a3a80caa-a2ca-40df-b05a-c5f2c4962dd2)

Here are the key insights from the sales and profit data analysis:

Now let's move on to the Customer Aspect of the data.
* Technology is the star performer with consistent upward growth (20k to 50k)
* Furniture is underperforming with flat or declining profits (stagnant around 5-10k)
* Significant monthly volatility across all categories
* Technology should likely be a focus area for future investment given its growth trajectory
* Monthly volatility suggests need for better inventory or pricing management
* Good diversification across categories, though with varying success

### Now let's move to Data Exploration: Customer Aspect

#### Let's see how many unique costumers we have

![image](https://github.com/user-attachments/assets/286aa6a6-81f6-4c96-a692-6071563ed94c)

Looking at the customer data and visualization, here are the key insights:

Overall Growth in Customer Base:
  * Started with 595 customers in 2014
  * Ended with 693 customers in 2017
  * Total net growth of 98 customers (+16.5%) over 4 years

Business Implications:
  2015 was a turning point, possibly indicating:

    * Implementation of new customer acquisition strategies
    * Improved retention programs
    * Expansion into new markets or product lines

Areas for Investigation:

  * What caused the initial decline in 2014-2015?
  * What changes were implemented in 2015 that led to the turnaround?
  * Is the current growth rate sustainable?

#### Top 10 customers who brought the highest profit

![image](https://github.com/user-attachments/assets/2a56d4f7-c475-4fcb-90ba-e6eefcccbcea)

### Key Insights:

 * There's a significant gap between top and bottom customers
 * Heavy reliance on top customers
 * Possible opportunity to grow mid-tier customers
 * Need for VIP retention strategy for top performers
