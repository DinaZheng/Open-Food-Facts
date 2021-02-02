# Open-Food-Facts
A data analysis group project analyzing open source dataset, Open Food Facts, with over 350,000 and our key findings

# Dataset Overview: 
Open Food Facts is an database of food products, with ingredients, allergens, nutrition facts, and other information from product labels. Data is contributed by individual volunteers

Columns Used: average nutrition score, brand, country, numerous different nutrition facts, and more

Main Goal:
- Identify health concerns and make recommendations to businesses in terms of nutrition
- Analyze the business impact of food nutrition and choice of food products to sell
- Find discrepancies in data and nutritional facts reporting

# Cleaning Process:
- Removed columns where a majority of data is NaN, or where there are only values for an unevenly distributed sample
  Ex: Glycemic index reported in high proportions for healthy foods
- Dropped unnecessary and repetitive columns
  Ex: ‘Countries’ and ‘Country-tag’
- Removed fabricated or unrealistic data
  Ex: Food reported from a video game
- Create valuable new columns based on existing ones
  Ex: Average nutrition score

# Findings:
## Finding 1: Health Concerns for Consumers
Organic products typically have 9 fewer addictives than non-organic products. The most produced products exceed the daily saturdated fat intake of 13g/day. 

## Finding 2: Business Implications
In Switzerland, the food retail industry has heavily dominated by a single company, Coop, which connote to a high barrier to entry. https://www.statista.com/statistics/787298/switzerland-market-share-of-food-retailers/

Within US and France, there is a fairly equal distribution of the industry among the top five brands that produce the most products. 
US has the smallest distribution, which could be attributed to the federal control over monopolistic competition in US markets. 
The leading food brand is Coop, with a massive market share of 49.9% compared to the smallest brand with the least products, Knorr, with only 6.5%. The spread between Coop and Migros Bio is 43.4%, a huge spread in industry share that is greater than the spread in the US and France food retail industry.

With Coop as the leading brand, there is a monopolistic distribution in the food retail industry in Switzerland.

## Finding 3: Limitations in Dataset
Average nutrition score score calculations are not consistent with data. Lots of NaN values contain foods that would seem healthier. 

## Finding 4: Business Analysis
New food brands should expand into food categories of ice cream, extra virgin olive oil, and potato chips because they are the most produced food items in the US. Looking deeper, these top three food categories also had similar food nutrition numbers, where almost 99% of all products contained additives and were over the recommended daily intake of saturated fat. Overall, the significance of these findings relate to the obesity of the average American citizen and its low overall nutrition scores, which was a new metric I created based on existing nutrition values.

# Conclusion: 
It is in a manager's best interest to keep sugar and saturated fat content in mind when producing food products that consumers intake given the recommended daily intake values. Most food products are over the recommended amounts in both sugar and saturated fats regardless of whether they are organic or not.
Each country’s food industry industry is distributed differently with Switzerland having the most monopolistic distribution.
The dataset’s nutrition score should not be used as a standard for identifying healthy foods.

# Improvements: 
- Relate business implications back to the food nutrition facts itself
- Develop France analysis more with other countries
  - Why are top brands successful?
  - What foods do the top brands produced in comparison with each other?
    - Do top brands have a higher nutrition value or interesting nutrition values?
  - Is there a correlation
- Keep in mind to normalize the dataset
- Machine learning if possible using different methods to find findings
- Use plotly and mapbox if possible
- Format: Each finding + Managerial Insight


