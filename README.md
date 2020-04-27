# R_Analysis
## Module 15
### Module 15 Challenge includes "MechaCarChallenge.R" and "MechaCarWriteUp.md"

#### Technical report

AutosRUs' Mechacar is still a distance away from making productions due to having much troubles. There are issues with the vehicle's manufacturing process which is blocking the team to continue on the entire process. By having different types of statistical tests, the data indicates that it needs whole other decision making before the production.

We combined our understanding of R and statistics with the manufacturing datasets provided:
By using two given datasets, we have performed tests showing different results which can impact the decision making.

By using the (MechaCar_mpg.csv) dataset - The result of mpg tests over 50 potentional prototypes showed that they were produced in multiple different design specifications to identify which is their masterpiece including measuring lengh of the vehicle, weight, drivetrain, spoiler angle, ground clearance, etc.

By using the (Suspension_coil.csv) - Suspension coil tests resulted in multiple different production categories such as weight capacity of different suspension coils were tested to make sure the process for manufacturing is consistent and neat.

A robust technical report was generated which can be used to determine which design choice would be ideal by thinking about both qualitative and quantitative outcomes.

MPG Regression
By using the four different values that were given in the dataset;

I found out that there is a relationship between and and also between and

After the findings, it was clear that the linear model doesn't predict mpg of the prototypes effectively. I would not include any non-substancial metrics in the statistical test anymore.

Suspension Coil Summary
The design specifications for the MechaCar suspension coils tell us that all kind of suspension coils must not exceed 100 pounds per inch. Our coil_summary_table shows that the current manufacturing data meets this design specification with a variance of 62.29.

Suspension Coil T-Test
With the same data and the R script, it was determined that the suspension coil’s pound per inch results are not different from the mean population of 1,500 pounds per inch.

Design Our Own Study
First of all, I thought about my own expereience. I owned multiple vehicles in my life and they were dealt in many different ways. Buying a used car, buying a brand new car, getting gifted car from a family member, etc. And I came up with the follwoing :

What would a consumer be interested when buying a car?
What statstical tests can be done to answer the question above?
What kind of data will I need to fulfill those tests?
Many of the manufactureres are currently in action to find out more about their current and future customers. What would they seek? What is the trend? What are the aspects that consumers look into before buying a car?

What metrics would be of interest to a consumer (cost, fuel efficiency, color options, etc.)?
Since there are so many, I found out the following aspects that were ranked high in different surveys and websites on the internet.

Color
Interior(including the design, performance level of each equipment)
Value(MSRP)
Color
When it comes to color, I think most of people care for that. Thats whtat they see all the time when they approach their car to do anything. It will be seen to other people and that is very important. Some people like common colors because they do not want to be recognized often. Some people want flashy colors just to satisfy themselves of even show off to others.

I would need to collect dataset of color preference. They can be found easily because it has been a decision maker from the past for a long time. I would test it out by using a regression model after I collect what color of cars were sold the most in different years, what is the cost difference among different colors of cars, how colors of cars were changed and created.

Interior
Now as technology advances as we go, people expect more advanced and different gadgets inside their cars which can fulfill their convenience. Bluetooth, advanced sound system, auto features, moderand and trendy designs, and safety for their family. If you look at the trim system that most of the car models have and most of the company value at, it is obvious that what people care for and willing to pay more money for. We would need to collect the data including top selling cars and their trim levels. To visualize such tests, I think either a scatter plot or a box plot will be a better fit.

Value(MSRP)
When buying a car, people think of its value first. Can they afford such vehicle? is it worth the investment?

To fulfil that unavoidable question, we would need to run a test by comparing different modles and different manufactures. Comparison will be need to show the data in more obvious way so running t-test is proper for this matter. Also, to visulaize and make the large data more visible, Heatmap plots also will help.
