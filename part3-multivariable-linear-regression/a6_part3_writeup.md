# Part 3 - Multivariable Linear Regression Writeup

After completing `a6_part3.py` answer the following questions

## Questions to answer

1. What is the R Squared coefficient for your model? What does that mean about the model in relation to your data?
My model's highest R squared output is 0.94, meaning that the relationship between the regression and the data is quite high.

2. Is your model accurate? Why or why not?
While it is more accurate than previous models, there is still much room for improvement, as the margin for error is still quite high, especially when trying to predict car prices.

3. What does the model predict a 10-year-old car with 89000 miles is worth? What about a car that is 20 years old with 150000 miles?
10 year old car w/ 89k miles: $8588
20 year old car w/ 150k miles: $660

4. You may notice that some of your predicted results are negative. This is occurring when the value of age and the mileage of the car are very high. Why do you think this is happening?
Negative predictions occur because the function extrapolates beyond the logical bounds of age and mileage, amplifying depreciation factors without constraints, leading to unrealistic outputs like negative results.