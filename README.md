# SparkSQL Home Sales Data Analysis

In this project, I utilized SparkSQL to analyze home sales data. 

# Skills:
- Creating temporary views
- Partitioning data
- Caching and uncaching tables
- Executing specific SQL queries to extract insights from the dataset


## Key Metrics Analysis
### Average Price for a Four-Bedroom House Sold Each Year

The table below shows the average price (rounded to two decimal places) for a four-bedroom house sold for each year:

| Year | Average Price |
|------|---------------|
| 2022 | 296363.88     |
| 2019 | 300263.70     |
| 2020 | 298353.78     |
| 2021 | 301819.44     |

### Average Price of Homes Based on Specific Criteria

1. **Three Bedrooms and Three Bathrooms**
   
   Year-wise average price for homes with three bedrooms and three bathrooms:

   | Year | Average Price |
   |------|---------------|
   | 2017 | 292676.79     |
   | 2016 | 290555.07     |
   | 2015 | 288770.30     |
   | 2014 | 290852.27     |
   | 2013 | 295962.27     |
   | 2012 | 293683.19     |
   | 2011 | 291117.47     |
   | 2010 | 292859.62     |

2. **Specific Features (Three Bedrooms, Three Bathrooms, Two Floors, >= 2000 sqft)**

   Year-wise average price for homes with three bedrooms, three bathrooms, two floors, and at least 2000 square feet:

   | Year | Average Price |
   |------|---------------|
   | 2017 | 280317.58     |
   | 2016 | 293965.10     |
   | 2015 | 297609.97     |
   | 2014 | 298264.72     |
   | 2013 | 303676.79     |
   | 2012 | 307539.97     |
   | 2011 | 276553.81     |
   | 2010 | 285010.22     |

3. **Average Price per "View" Rating (Avg. Price >= $350,000)**

   Average price per "view" rating where the average home price is $350,000 or more:

   | View Rating | Average Price |
   |-------------|---------------|
   | 99          | 1061201.42    |
   | 98          | 1053739.33    |
   | 97          | 1129040.15    |
   | ...         | ...           |
   | 83          | 1033965.93    |
   | 82          | 1063498.00    |
   | 81          | 1053472.79    |
   | 80          | 991767.38     |

   **Runtime for this Query:** 0.59 seconds.

## Conclusion
The SparkSQL analysis provided valuable insights into home sales data, these metrics can aid in decision-making processes related to home sales and market trends.