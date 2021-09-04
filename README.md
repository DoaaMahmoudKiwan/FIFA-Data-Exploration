This project was part of the data analysis nanodegree program offered by udacity.

# FIFA19 Exploration
## by Doaa Mahmoud Kiwan

## Dataset

The data consisted of values and attributes of approximately 18,200 football players.The attributes included the player's name, age, nationality, club, position, preferred foot, value, wage, in addition to many other attributes describing the player's skills and abilities. The dataset can be found in the [here]https://www.kaggle.com/karangadiya/fifa19.



## Summary of Findings

In the exploration, We can see that there is a strong relationship between the value of the player and his overall score. As the overall score of the palyer increases, his value in the market increases. There is also an interesting relationship between the wage and value of players. All players with high wages have high value in the market, which makes sense. However, many players of high market value (> €10M) recieve low wages 
(< €100K), this may be because they have strong abilities and skills but they play for clubs with limited financial resources or maybe because some clubs overpay their players in comparison to other clubs. This is clear from the plot of the clubs paying the highest wages versus the plot of the clubs with the highest overall rating of players.

Data analysis also show that there are interesting relationships between players value and the categorical features. 
Some positions have on average higher values than others. When it come to the preferred foot, although leftfooted players are rare, they are on average of higher value than rightfooted players.

## Key Insights for Presentation

For the presentation, I focus on the influence of player's age, overall rating, club, preferred Foot and position. I start by introducing the the distributions of the main variable (Value), followed by the distributions of palyer's age, Overall rating and preferred foot.

Afterwards, I introduce the relationship between the player's value and the following variables: Age, Overall rating, weekly wage.
I use the scatterplots of illustrate these relationships. Finally, I show how the player's value and wage are related for two speciifc clubs( Barcelona and Juventus) using scatterplots and how the player's value is related to both player's position and preferred foot for the previously stated clubs using Heatmap.

