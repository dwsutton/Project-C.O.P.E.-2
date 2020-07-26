# Project_3
Seinfeld: A project about nothing...or the Costanza Occupation Prediction Engine(C.O.P.E.)

Read Me: Project_3

Description: 
The goal for this project is to demonstrate an understanding of webscraping, APIs, and Natural Language Processing (NLP). I leveraged my knowledge of the television program Seinfeld by programming a prediction engine that can accurately predict whether a post came from the architecture subreddit or the marine biology subreddit. The purpose of such a prediction engine is to inform George Costanza which Reddit a post came from based solely on the headline and inform his decision which occupation to choose. (Side-note: two of George’s favorite pretend occupations are architect and marine biologist.)

Data:
I used Pushshift’s API to scrape 2000 posts from Reddit, 1000 from each the architecture and marine biology subreddits. 

My Approach:
After obtaining the data, I set up a model using Jupyter Notebooks to train, test, split the data. Then I fit both the training set and the testing set. Determined the baseline score and away I went with the ultimate goal of comparing both a linear regression and multinomial Naïve Bayes models. Unfortunately I came up short on time and was unable to complete the entire process.

Conclusions:
Unsurprisingly the linear regression model had no trouble predicting which subreddit a post was from. This is at least partially due to the differing natures of the subreddits. And reinforced by the visualization included showing the top and bottom five words, as the dataframes were merged and stacked so that one end was architecture and the other marine biology.

Next Steps:
There is much to be done with these data sets. First, complete the multinomial Naïve Bayes model and compare it with the linear regression. Next, generate more visualizations that would provide further evidence for the conclusions I reached. Finally, expand my exploration into the words used and headline length to see if any further insights or telling characteristics could be revealed. 

