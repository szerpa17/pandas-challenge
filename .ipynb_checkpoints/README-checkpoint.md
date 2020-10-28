# Pandas Challenge

Challenge to analyze and report on Heroes of Pymoli player demographics and purchasing data to provide meaningful insights.

![Fantasy](HeroesOfPymoli/images/Fantasy.png)

## Expected Output

### Player Count

* Total Number of Players

### Purchasing Analysis (Total)

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

### Gender Demographics

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)

* The below each broken by gender
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Gender

### Age Demographics

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group

### Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

### Most Popular Items

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

### Most Profitable Items

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

## Results:
Dataframe outputs may be found in the [HeroesOfPymoli.ipynb](https://github.com/szerpa17/pandas-challenge/blob/master/HeroesOfPymoli/HeroesOfPymoli.ipynb) file.

## Findings:
* Males made up the majority of players (at approximately 84 percent) and also made up the majority of purchases (652 out of the 780 purchases, or 84 percent of purchases). This suggests that the game appeals more to male players.
* Female players spent 18 cents more on average per purchase when compared to male players. The average total purchase per person for females was also higher than males by 40 cents, suggesting that they may purchase more expensive in-game items.
* The largest group of players by age are in the 20-24 age group (approximately 45 percent of all players). This is also the same group that has contributed the most to the game's total revenue. The game and in-game items therefore appeal the most to this age group.
* There may be more earning potential within the 35-39 age group that has the highest average purchase price (3.60) as well as the highest average total purchase per person (4.76).



