# 2020_2021_NBA_PTS_Regressor
Using linear regression, I have predicted NBA points per game for the 2020-2021 season. The independent variables include age, games played and started, rebounds, assists, turnovers, and more. Data was scraped from https://www.basketball-reference.com/leagues/NBA_2021_per_game.html using urlopen and BeautifulSoup.

I then implemented linear regression manually by using gradient descent to minimize the cost function. After the manual implementation, I compared the results from the built in regression method with the manual regression.
