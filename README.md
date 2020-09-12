# Microsoft x PiE Datathon @ UC Berkeley
Team: James Jung, Anurag Aiyer, and Ritvik Iyer

This is our work for the Microsoft x PiE Datathon hosted at UC Berkeley on 9/12/2020. 


## Some notes from James
- Try out the sentAnal_opMap function that I created to get the aspects/entities and their corresponding sentiments and explore around with that


## Model notes
### Text --> Escalated
- sentiment analysis
	- weight the sentiments --> linear regression model?
	- if aspect of that sentiment is regarding delivery/replacement, more likely to be escalated? (NEED TO EXPLORE THIS)
- Keyword Extraction / Named Entity Recognition (These might be redundant as Aspect-based sentiment analysis already provides this somewhat ^^^)
	- check for certain words --> is the focus of the text around a word that has to do with a product? Delivery? 
- K means clustering 



### Text & escalated --> Processing Time
- escalated
	- explore escalated and Process time correlation (linear? logarithmic?)
- sentiment analysis
- checking for similar text and averaging their processing time


### Similar texts
- we can see if we still want to use this, but this on its own is a rly big question. U can reference this gaggle post on what we can do for this: https://www.kaggle.com/c/quora-question-pairs/discussion/34355