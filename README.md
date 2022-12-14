# Multiple Linear Regression on King County Housing Data Set

## Business Problem

In this project, we are analyzing the data to answer a critical question in the world of real estate. What factors should a housing development company consider while building a property so that it may sell for its highest price?
### The Data

This project uses the King County House Sales dataset, which can be found in  `kc_house_data.csv` in the data folder in this repo. The description of the column names can be found in `column_names.md` in the same folder. 

### Methods

![download](https://user-images.githubusercontent.com/113707140/207612428-d2c5c66c-e150-495f-ad8b-efd26f382a86.png)
The visualization above shows that there seems to be a relatively strong linear relationship between square feet of living space and the price of a house.

![download (2)](https://user-images.githubusercontent.com/113707140/207612710-d1fbcbe6-56e8-4598-8fd6-bcfb46791609.png)
The visualization above shows that when the building grade improves, the house price rise as well. We can see in the boxplot above that the mean house price for a home with a grade of 13 is far above other grades. While the building grade of 3 falls short of minimum building standards based on King County grading system.

![blob (1)](https://user-images.githubusercontent.com/113707140/207613951-e200528c-db08-4d1e-aaf0-ace4aa6d193c.jpg)

## Conclusion & Recommendations
The results of the analysis were as follows: After running the second model with an R-squared value of 0.743, telling us that the model fit the data with an accuracy of 74%, We can confidently say that zipcode is one of the strongest influencers on the value of homes in king county. other features that were positively correlated with price included: Square-footage of living space, which was positively correlated with house prices. Building grade, which was positively correlated with house prices The square footage of interior housing living space for the nearest 15 neighbors which was positively correlated with house price.

The recommendations below will enable a housing development company in King County to increase their chances of selling higher-priced homes:

1.)Make sure your home is in an upscale zipcodes

2.)Increase square-footage of living space

3.)Attain highest possible building grade by using high-quality materials so that it is graded well by the King County Grading System

4.)Choose land/lots where the nearest 15 neighbors have a large amount of interior square footage.

### Future Work

In the future, the next steps would be reducing noise in the data to improve the accuracy of our model. Additionally, i would like to investigate certain features like proximity to good schools, other facilities like hospital, gyms, restaurants and play grounds.

