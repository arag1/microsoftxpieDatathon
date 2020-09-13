# Microsoft x PiE Datathon @ UC Berkeley

### Project Members
Ritvik Iyer, James Jung, and Anurag Aiyer

### Purpose
This is our work for the Microsoft x PiE Datathon hosted at UC Berkeley on 9/12/2020. Our task was to analyze the given dataset on customer service reports (accessible in the Data folder) and perform exploratory data analysis (EDA) and generate prediction models. We attempted to answer the following question: Can we accurately predict the time it takes to respond to a customer service request, based on the request text and theme of request? 

### What did we accomplish?
In a 5-hour span, we were able to not only generate meaningful visualizations from the dataset, but also produce interesting prediction models to inform real-world business decisions. Using Microsoft's Azure Text Analytics API we extracted the sentiment and key phrases from our text data, which drove prediction algorithms. Ultimately, using fundamental tools like Regression Analysis and Feature Engineering with word vectors, we transformed messy text data into concete insights. 

### What challenges did we run into?
From the beginning, a major challenge we faced was the limited size of the dataset. There were only around 320 entries, limiting the effectiveness of our prediction models. In addition, we noticed erroneous data entries, particularly in the `Date Created` and `Date Completed` columns. We attempted to fix those issued by imputing average values of similar data points. 

### What accomplishments are we most proud of?
While our challenges did somewhat limit the effectiveness of our modelling, interesting insights were still drawn. For example, we noticed sharp trends between the theme of a customer's service request and the processing time of the ticket. Namely, service tickets related to sercurity and reliability took the longest to resolve. Additionally, we noticed that service tickets with negative sentiment scores which were escalated took the longest time to process, perhaps related to the difficulty of the problem.

### If we had more time, what features would we add to this project?
If we had more time, we would use additional NLP techniques to further mine the text. We would expand on the breadth of the prediction portion to further account for the chance of a given customer input needing escalation. 

### What did we learn?
Overall, we learned a great deal about data cleaning, exploratory analysis, and predictive modeling. We hope to continue to apply these skills in the future to address real world issues. 
