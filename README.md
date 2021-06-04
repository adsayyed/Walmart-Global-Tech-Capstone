# Capstone Project Summary

Walmarts Global Tech Team came to us and asked the question: "How can you help optimize our global employee tech support team" as with the pandemic, there had been a serious influx in tech related issues associated to work from home employees.

There were 2 areas that the team discovered that could be improved upon significantly: SLA and ticket reassignment.

The dataset provided contained 141,032 tickets, 193 attributes, pertained to US only, and was from January 2020 through February 2021.

As far as technical analyses are concerned, the team began with exploratory analyses within python using the Pandas library. Next NLP was used for classifying tickets via there textual content. Moving on XGBoost and CatBoost were utilized for predictive models built to predict what categories tickets fell under. Time Series was also applied in order to preduct ticket volume per day. Lastly the capstone team also used Tableau to visualize the findings in a clear succinct manner.

To give a quick summary of the reccomendations, the team found that nearly 70% of the tickets fell under the low priority (the lowest of the 5 priority categories), which means that walmart should look into automating these simpler tickets to help improve time taken to complete tickets. Next as far as SLA is concerned, from the data the discovered that tickets were not being handled in the proposed order. We suggested utilizing a  time series model so that the tech support team can predict the ticket volume, and handle tickets accordingly. Lastly we discovered that around 50% of the tickets were reassigned at least once. Our solution was building a predictive XGBoost/Catboost model that was able to interpret ticket categories (by assessing ticket content) and forwarding tickets to there respective sectors. This model we believe can also be used as a framework for a chatbot. 

All in all it was a great experience with a lovely team!

Teammates:
[Amber Chen](https://www.linkedin.com/in/ambercxx/), 
[Shuming Chen](https://www.linkedin.com/in/shuming-chen/), 
[Tairan Deng](https://www.linkedin.com/in/tairan-deng-857396149/), 
[Kaiwen Zhang](https://www.linkedin.com/in/kaiwen-zhang-a802b5121/), 
