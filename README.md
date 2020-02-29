# Predicting Social Mobility with Income Data 
The demographics are individuals of all ehtnicities and genders whos families are of a lower income. Individual income (excluding spouse) is the indicator for social mobility as the higher the individual income, the more the individual has climbed the social ladder coming from a less well off background.

## Predicting Individual Income with Hours Worked
![Picture1](https://user-images.githubusercontent.com/60996310/75592698-f99e3500-5a50-11ea-993b-8b40542e9458.png)
There's a high correlation between the two variables. The rsq value is 71% indicating that the model is able to account for 71% of the data. This makes sense because as people work more, they should earn more as well especially if they have higher incomes. 

## Predicting Individual Income with Household Income
![Picture1](https://user-images.githubusercontent.com/60996310/75593069-15560b00-5a52-11ea-94f4-c895acfc143f.png)
The rsq value is 96%. 96% of the 

### Excel Manipulations
1. Import data from Opportunity Atlas for Individual Income (excluding spouse), Household Income, Hours Worked from New York, New York. 
2. Use a VLOOKUP to match each variable to the corresponding area. (ie. =VLOOKUP(County Name, HouseHold Income table array, column 3, FALSE)) 
3. Create scatterplots with HouseHold Income and Hours Worked as x-variables and County Name as y-variable. Input a trendline, and obtain slope, yint, and rsq value for both graphs.
4. Click on Data Analysis and Regression. Use Individual Income as y-variable and Household Income and Hours Worked both as x-variables. Output range is a blank cell. 
