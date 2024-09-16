# Analysing-Portuguese-Real-Estate-Market
Leveraging web scraping expertise to analyze the differences in property prices and current market demand across the six major cities in Portugal.

The image bellow shows the city choosen for this project with their average house prices: 

![Screenshot 2024-09-16 163216](https://github.com/user-attachments/assets/0010522b-bbab-4530-80c1-7c81ceda67f6)
## Data Collection 
In order to gather data we choose the renowned marketplace OLX Portugal. Both buyer and seller can meet throgh this platform. We colleceted the data for those ads which took place on last 48 hours. 
Through web scrapping method We could fetch the property title, price, size, date of advertisement.

## Data Wrnagling
- For each cities we collect data until 40 pages and store them in a csv file
- Added a new column name with the city
- Concat all the city data to work with a final dataset.

## Data Cleaning
- Property type & typology was separated from the title of the add
- Remove all letters and spaces in the price column, then convert to float
- Extract numeric part from size column, convert to integer
- Removing duplicated and small house areas

## Analysing and gathering insights
- Calculating and then plotting average house prices for each city
- Faro has lower average house prices compared to coastal cities like Porto and Lisboa
- Cities with higher tourism influx (e.g., Lisboa and Porto) have higher house prices due to increased demand for short-term rentals
- T0 and T1 apartments are less available in cities with high tourist demand
- Plotting the number of apartments by typology per city
- Looking at the distribution of typologies across cities


### Project link: https://colab.research.google.com/drive/1fJDI_r9ta36xfKduBU3Engbgicw8Folc?usp=sharing
### Presentation link: https://docs.google.com/presentation/d/1mzBr1SNqoUZUItdgL09xP636jQ6JJfvYUCIS91Co3_I/edit?usp=sharing
