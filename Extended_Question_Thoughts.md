# Extended Question (Comparison of Manhattan and Queens)

First we wanted to explore the distributions of each factor with regards to each county (New York County - Manhattan and Queens County - Queens).

We found many differences when comparing the different factors for each borough.
 + Medians of each factor in Manhattan:
   + Proportion of 18-64 year olds who are uninsured: **0.07404**
   + Median Income: **101,303**
   + Proportion self-identifying as White: **0.6599**
   + Proportion of households with 4 or more people: **0.09722**
   + Proportion of population that commutes by bus: **0.067622**
   + Proportion of elderly population (65+ years of age): **0.1295**
 + Medians of each factor in Queens:
   + Proportion of 18-64 year olds who are uninsured: **0.1424**
   + Median Income: **62,841**
   + Proportion self-identifying as White: **0.41673**
   + Proportion of households with 4 or more people: **0.2275**
   + Proportion of population that commutes by bus: **0.11297**
   + Proportion of elderly population (65+ years of age): **0.13538**

It was really interesting to observe that most if not all the median values of the above factors differed significantly (other than the proportion of the elderly population) in each county.

Then we wanted to test how each of these factors both individually and together interacted with the proportion of positive test results in each of the counties using linear models.

The linear model with the highest adjusted r-squared value for Manhattan included the following variables:
+ proportion of 18- to 64-years old who are uninsured
+ proportion of people who self-identified as white
+ median income

This linear model had an adjusted r-squared of roughly **0.4002**.

The linear model with the highest adjusted r-squared value for Queens included the following variables:
+ median income
+ proportion of population living in households with more than three inhabitants 
+ proportion of population using public transportation to commute to work that includes bus travel

This linear model had an adjusted r-squared of roughly **0.3887**.

We also added the change in mobility variable to these models, to see if its addition would increase the mdoel's r-squared value. 
 + The linear model with mobility for Manhattan had an adjusted r-squared of **0.3847**. 
 + The linear model with mobility for Queens has an adjusted r-squared of **0.3745**.

For both counties, adding the change in mobility to both models decreased the adjusted r-squared only slightly, and thus the linear model may be better off without the added mobility. However, perhaps there is a better combination of variables outside of the model we worked with that uses mobility to explain the positivity proportion of these NYC counties. Overall, it was interesting to explore the New York and Queens counties more in depth and how certain socioeconomic and mobility factors impacted the proportion of positive test results in these areas.
