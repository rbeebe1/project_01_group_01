# UCB Bootcamp Project 01 - Group 1
---
# Conducting Analysis of data related to food allergens.

## Team Members 
Ryan Beebe - Raymond Darrough - Sophia Felix - Alex Bolinger - Ahmed Abusamra - Micah Galbadores - Sanjana Islam



## Google Slide Link
https://docs.google.com/presentation/d/1fp_bMJP9hUlN-NsGNYIihDWxOf1p1snYUQALyZLbsT4/edit#slide=id.p



# Project Description :
 This project aims to investigate the prevalence and severity of allergens in the US, and identify potential demographic biases that may exist. Specifically, we will analyze the impact of age, gender, and race on allergen severity, and compare severity grades across different demographics. Additionally, we will examine the break down of different food allergens per capita and identify the most common food allergens in the US. The insights gained from this study can help identify areas for improvement in allergy treatment and management, and ultimately improve the quality of life for individuals with allergies. 

# Hypothesis
There may be a correlation between demographic factors such as age, gender, and race and the severity of allergic reactions to different types of allergens. Additionally, the prevalence and severity of specific allergens may vary based on demographic factors.
To test these hypotheses, we will collect and analyze data on allergen severity grades, demographic factors such as age, gender, and race, and the prevalence of different food allergens in the US. We will use statistical methods such as bar chart and pie chart to tests and examine the relationships between these variables.

# Analysis And Graphs:

**What Are the Most Common Food Allergies in The United States?**
- In our analysis we found that peanuts are the most frequently reported food allergen in the United States, with milk and eggs being the second and third most common allergens, respectively.
![image](https://user-images.githubusercontent.com/126538596/233524264-685b720b-ce57-421f-ad7f-183170884d9b.png)

**Does certain food allergies may be more prevalent in certain gender?**
- Our analysis revealed that there is no gender-specific prevalence of food allergies, as both genders exhibit the same level of severity.
Does the year of birth affect the severity of allergens?
![image](https://user-images.githubusercontent.com/126538596/233524295-0e247941-2adb-4fd5-9102-7439ec9ae9c1.png)

**Does the year of birth affect the severity of allergens?**
- According to our analysis, the number of reported allergies among individuals born in the 1980s was notably low, but began to increase dramatically starting around 1990 and continued to do so until approximately 2005.
![image](https://user-images.githubusercontent.com/126538596/233524393-01206015-6ab5-4a7e-8ec6-c013eabde92c.png)

**Does being insured or uninsured result in higher counts of severe cases in food allergies?**
- Our analysis also shows that there is a correlation in the number of severe cases reported depending on whether the individual was on medicaid or not. Non-Medicaid individuals saw nearly three times the amount of severe cases.
![image](https://user-images.githubusercontent.com/126538596/233526751-91379916-d6e6-4bd0-807a-1c6fcd5b918b.png)

**What does the line on the graph signify regarding the relationship between birth year and peanut allergen levels, as determined by the linear regression analysis?**
- According to the linear regression analysis, the line on this graph indicates a negative linear relationship between birth year and peanut allergen levels. Our research findings suggest that individuals born between 1985 and 1995 had a higher prevalence of peanut allergies. However, we lack sufficient information to determine the underlying cause of this trend.
![image](https://user-images.githubusercontent.com/126538596/233811071-69c00b20-6091-4254-bc4c-71184c715fcc.png)


# API Overview :

 - The following is the data from our API, which can be utilized to search for a particular food item. In this instance, we have entered          "meatloaf" as the search query, and the resulting output prompts the user to select the type of meatloaf they wish to evaluate from the         available options.
![image](https://user-images.githubusercontent.com/126538596/233516549-c0f33a71-b5e6-4fb4-8174-c3acc947b8f6.png)

-  Upon selecting the type of meatloaf, in this case, homemade meatloaf, it will display the corresponding ingredients for that   particular meatloaf recipe.
![image](https://user-images.githubusercontent.com/126538596/233516732-72e5ffc0-4231-4692-907b-acb0e3e0b41e.png)

- Once the ingredients for the selected meatloaf recipe are displayed, it will also provide information on any potential food allergens that may be present in those ingredients. This can help individuals with food allergies or intolerances make informed decisions about whether or not the recipe is safe for them to consume.
![image](https://user-images.githubusercontent.com/126538596/233516881-968e997c-1436-49e8-bfad-60dee0f58a9e.png)


# Conclusion: 
In conclusion, our analysis suggests that demographic factors such as age, gender, and race may have an impact on the severity of allergic reactions to different types of allergens, and that certain food allergens may be more prevalent than others. We found that peanuts are the most commonly reported food allergen in the United States, and that there is no gender-specific prevalence of food allergies. We also observed a correlation between the year of birth and the severity of allergens, with individuals born in the 1980s exhibiting lower reported allergies than those born in the following years. Finally, our analysis suggests that being insured or uninsured may have an impact on the severity of food allergies, with non-Medicaid individuals experiencing a higher number of severe cases. Further research is needed to fully understand the complex relationships between these variables and their impact on allergic reactions.


# Data Sources:

- https://www.kaggle.com/datasets/boltcutters/food-allergens-and-allergies
- https://spoonacular.com/food-api/docs 
- https://www.statista.com/statistics/1243167/common-allergies-us/

