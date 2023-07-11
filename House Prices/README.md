# Competition Description
![image](housesbanner.png)
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home

# Acknowledgments
The [Ames Housing](http://www.amstat.org/publications/jse/v19n3/decock.pdf) dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset. 

Photo by [Tom Thain](https://unsplash.com/@tthfilms) on Unsplash.

# Metric
Submissions are evaluated on [Root-Mean-Squared-Error (RMSE)](https://en.wikipedia.org/wiki/Root-mean-square_deviation) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

# Submission File Format
The file should contain a header and have the following format:
| Id | SalePrice |
| :----- | :---------- |  
| 1461 | 169000.1 |  
| 1462 | 187724.1233 |  
| 1463 | 175221 |    
| etc ...
