# Pandas-Challenge
Corbin and I worked collaboratively on this project. We had to use a lot of class activites, google, office hours and instructors for help on this. 

Honestly, we ran into some real roadblocks when it came to taking the mean of our data frames. We found that formatting the data frame automatically turned everything into objects which created aggregate errors when running for mean. While there seem to be some conversion tools, potentially .astype or others, our workaround was copying the dataframe before formatting it so that when we called it for the mean it was able to calculate.

I would be interested to know if this is what was intended, since the starter code asked us to format and then find the mean. This indicates to me that maybe we were supposed to convert these objects back to int/floats after formatting, but that did not seem very efficient to me. 

Thankfully, it's done and working correctly now. Looking forward to your feedback.
