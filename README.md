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
<li> Removed columns where a majority of data is NaN, or where there are only values for an unevenly distributed sample
  Ex: Glycemic index reported in high proportions for healthy foods
- Dropped unnecessary and repetitive columns
  Ex: ‘Countries’ and ‘Country-tag’
- Removed fabricated or unrealistic data
  Ex: Food reported from a video game
- Create valuable new columns based on existing ones
  Ex: Average nutrition score
  </li> 
