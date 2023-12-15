Some ways to improve the dataset quality


The train_data dataset is a good starting point for sentiment analysis of tweets about tech products. However, there are a few ways to improve it further.
First, the dataset could be expanded to include more tweets. This could be done by crawling Twitter for more data, or by collecting data from other sources such as social media platforms or news websites.
Second, the dataset could be cleaned to remove duplicate tweets and tweets that are not relevant to tech products. This could be done using a combination of manual and automated techniques.






What do we currently Know About our Data:
	•	we know that there are nearly four type of opinions tweeted about any product that's positive, negative, no_emotion, and 'i can't say" last one has been tweeted by many few so we can ignore that type of example
	•	there were many null values in Product column so we dropped that example but we are keeping in mind that they still were a lot of data nearly 5000 examples.



 dropping those example could means two thing
	1	as we are considering that we are mainly focused on the opinions of people or reviews of peoplr towards any product and not their general opinion.
	2	the dropped data my contain opinion of people about something common that still need to be explored }
	•	we know that data is imbalanced as positive examples are naerly 81% and if we build any model taking this imbalance data that may be biased towards one class.
	•	we surly need augmentation of our data or look back to dropped example but need to fill some product value as those examples were having null value in product column


Observation2:- People are talking about the battery of iPhone in their tweet.


