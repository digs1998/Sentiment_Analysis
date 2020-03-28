# Sentiment_Analysis

Here i have done Sentiment Analysis of movie collected from imdb. Around 1000 datsets were collected with 10% used for validation of the datsets obtained
The basic approaches for doing a sentiment analysis of anything is done by
1) Separating out words from the sentences which can be done by Lexicon methods which takes data obtained as such and so is criticised for not being much efficient in setiment analysis.
2) Other approach involves using Machine learning with neural networks which is computationaly more expensive than lexicon.

Here we have taken the machine learning approach, whereby the library Tensorflow is accessed in python. We begin with importing tflearn and certain tflearn tools like to_categorical and pad_sequences for preprocessing of data and binary conversion of data respectively.
after these we train the data. regression technique of categorical-crossentrpy is used to find the difference between the highest point and lowest point of slope.
softmax activation function is used for pushing the data in range of 0 to 1.

References
1) https://www.youtube.com/watch?v=si8zZHkufRY
2) https://www.tensorflow.org/
