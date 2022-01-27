# Cryptocurrencies
## Overview:
Martha is a senior manager for the Advisory Services Team at Accountability Accounting, one of your most important clients. Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data Martha will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what Martha is looking for, she has decided to use unsupervised learning. To group the cryptocurrencies, Martha decided on a clustering algorithm. She’ll use data visualizations to share her findings with the board.

## Results
Previewed DataFrame of tradable Crptocurrencies
![TradableCurrencies](https://user-images.githubusercontent.com/83085800/150888544-a975dc5e-f817-4adb-8508-71b7fcf519ae.png)

Here we had to Standardize the data so we can run our model
![ScalingData](https://user-images.githubusercontent.com/83085800/150888680-71d3874d-eca9-4c66-855d-696dda68c382.png)

Finding the best value for K using the elbow curve
![ElbowCurve](https://user-images.githubusercontent.com/83085800/150888776-ac1b6972-be89-4c66-a1b9-99bd3bbea06a.png)

Using a 3D chart to visualize the results of the K-means clustering
![3D-Chart](https://user-images.githubusercontent.com/83085800/150888904-15bb8b6e-bf09-4090-b111-335ff2e8e021.png)

## Summary
We were able to successfully group each tradable currency into 4 different classes using K-means so the investment banks can wisely inform their customers.
