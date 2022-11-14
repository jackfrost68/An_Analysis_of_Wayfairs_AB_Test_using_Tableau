
## An Analysis of Wayfair's AB Test


# Introduction
Wayfair is a leading e-commerce platform that has garnered market share over the last few years. It conducted an A/B testing campaign to learn more about its customers by showing some of them a guaranteed delivery banner. In this paper, I conduct exploratory data analysis to find insights of how some of the variables are distributed in the dataset. After that, I further analyze whether the campaign was successful or not based on some metrics. 



# Exploratory Data Analysis

*What’s the composition of users by platform?*

![This is an image](https://github.com/jackfrost68/Kickstarter-analysis/blob/7edd40c204fa336c1018b9e85d6f51bd40ce77f1/Screen%20Shot%202021-10-24%20at%202.51.33%20PM.png)


From this visualization, we can deduce that about 75% of Wayfair’s revenue comes from users who browsed or shopped from a desktop and 25% from a web-enabled mobile device. 

This visualization can help inform Wayfair management to prioritize the optimization of the desktop versions of their web pages. Additionally, the team is aware of which platform to use in future A/B tests in order to get a large sample of their customers to learn from. 


# Campaign Performance Analysis 

*What is the fraction of orders that arrived late and were shown the guaranteed delivery?*

![This is an image](https://github.com/jackfrost68/Kickstarter-analysis/blob/7edd40c204fa336c1018b9e85d6f51bd40ce77f1/Screen%20Shot%202021-10-24%20at%202.51.33%20PM.png)


The visualization above shows that generally, most orders were delivered on time, regardless of whether a customer was shown the guaranteed delivery or not. 

Based on the visualization, we can deduce that the campaign was successful because most of the customers that were shown the guarantee had their orders delivered a day or two early. Furthermore, the visualization indicates how a very small portion of customers that were shown the guarantee, had their orders delivered a day or two late. 




*How did the campaign affect different visitor types?*

![This is an image](https://github.com/jackfrost68/Kickstarter-analysis/blob/7edd40c204fa336c1018b9e85d6f51bd40ce77f1/Screen%20Shot%202021-10-24%20at%202.51.33%20PM.png)
The visualization above shows how the guaranteed delivery campaign was spread out across different visitor types by revenue. While the changes from the benchmark/baseline of 33% are not too drastic, the differences can let us know if the campaign was successful. I would argue that Wayfair could have gained more customers by showing returning visitors the guaranteed delivery banner and prioritizing having their orders delivered on time or even a bit earlier. 

Additionally, I would argue that for Wayfair to have a successful campaign, they needed to experiment more with acquired members, especially in this case where if they failed to deliver their promise on time, there could be fewer repercussions.



# Conclusion
According to the dataset, most of Wayfair’s customers logged into their websites using a desktop platform. Using the estimated delivery date and estimated actual delivery date, we deduced the number of days a package was delivered late. I argued that the campaign was successful in part due to most orders being delivered on time, and that customers who saw the guaranteed delivery banner had their orders delivered a day or two early. On the contrary, I argued the campaign was not successful in that the guaranteed delivery banner was rarely shown to acquired members and returning visitors. Doing so would have helped Wayfair acquire more customers, granted they delivered on time. 
