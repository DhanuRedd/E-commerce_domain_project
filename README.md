# E-commerce shopping data :  EDA & Hypothesis testing with Python

🎯 Problem statement

To conduct a thorough exploratory data analysis (EDA) and hypothesis testing on two comprehensive datasets one containing information on customers visiting the shopping site for purchase and another that has demographic, purchase, and marketing information about the group of people.

## Dataset

| **Feature**                | **Description**                                                                 |
|----------------------------|---------------------------------------------------------------------------------|
| **Administrative**          | Number of administrative pages visited (e.g., account, cart, orders).            |
| **Administrative_Duration** | Time spent on administrative pages.                                              |
| **Informational**           | Number of informational pages visited.                                           |
| **Informational_Duration**  | Time spent on informational pages.                                               |
| **ProductRelated**          | Number of product-related pages visited.                                         |
| **ProductRelated_Duration** | Time spent on product-related pages.                                             |
| **BounceRates**             | % of visitors who exit without further interaction.                              |
| **ExitRates**               | % of pageviews ending on a specific page.                                         |
| **PageValues**              | Average value of the page relative to transaction completion.                    |
| **SpecialDay**              | Proximity of browsing date to special days, e.g., holidays.                      |
| **Month**                   | Month of the pageview (string format).                                           |
| **OperatingSystems**        | Integer representing the user's operating system.                                |
| **Browser**                 | Integer representing the user's browser.                                         |
| **Region**                  | Integer representing the user's location region.                                 |
| **TrafficType**             | Integer categorizing the traffic type.                                           |
| **VisitorType**             | Visitor status: New, Returning, or Other.                                        |
| **Weekend**                 | Boolean indicating if the session occurred on a weekend.                         |
| **Revenue**                 | Boolean indicating if the user completed a purchase.                             |

# steps performed

1. **Data Preprocessing**: Handled missing values, formatted data types, and ensured all necessary transformations were made for consistency in the dataset.

2. **Univariate Analysis**: Plotted histograms and box plots for each numerical feature to identify distribution shapes and detect outliers in features like `PageValues`, `BounceRates`, and `ExitRates`.

3. **Correlation Analysis**: Calculated correlations between numerical features to detect potential relationships, focusing on features like `PageValues`, `Revenue`, and `Duration`.

4. **Visualizations**: Created scatter plots, pair plots, and heatmaps to visualize relationships between key numerical variables, such as `PageViews`, `Duration`, and `Revenue`.

5. **Class Distribution**: Examined the distribution of the target variable (`Revenue`) to assess class balance and evaluate potential bias in the dataset.

6. **Page Category Analysis**: Summarized page views, session durations, and bounce/exit rates for different page categories to identify user behavior patterns on each page type.

7. **SpecialDay Analysis**: Investigated the distribution of the `SpecialDay` feature and analyzed its correlation with `Revenue` to understand how special events influence conversions.

8. **Binary Feature Creation**: Generated a binary feature indicating whether a user visited all three page categories (`Informational`, `ProductRelated`, `Administrative`) during their session.

9. **PageValues and Behavior Analysis**: Explored the relationship between `PageValues` and factors like `TrafficType`, `VisitorType`, and `Region`, highlighting engagement and purchase behavior differences.

10. **User Session Length Impact**: Analyzed user session lengths to determine their influence on conversion rates, identifying any trends between longer sessions and higher purchase likelihood.

11. **User Grouping by Behavior**: Grouped users based on `VisitorType`, `OperatingSystems`, and `Region` to identify behavioral differences and their impact on conversion rates.

12. **Traffic Type Segmentation**: Segmented users by `TrafficType` and analyzed engagement patterns, exploring the impact of different traffic sources on purchase probability and session behaviors.

This comprehensive approach prepared the data for in-depth analysis and built the foundation for actionable insights.
