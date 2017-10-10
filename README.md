
# Emotional Influence in Social Networks

## Project Description
Social Media emerged in the late 90’s, it was during this time that it took various forms over the internet. The various social media platforms have gained popularity over the years and attracted many people towards them. Even while most of them vary in functionality, the primary cause for their existence remains the same. The main reason why these platforms have attracted many humans is because they help in portraying the social characteristic that exists within us. It is in the nature of human beings to communicate or express ones thoughts. While humans express different thoughts through the social media platform, we believe that there are lot of emotions flowing within them. It is true that not all forms of expressions hold emotions, but majority of them certainly do. It can be seen that throughout all forms of social media that people post or comment with emotions like happiness, sadness, angry, fear. Our project is based on this underlying assumption that emotions that people hold drive social networks.
Quora is a platform where humans tend to express emotions indirectly. Due to the question and answer method of communication that Quora uses, there is a lot of open space for constructive discussions. We believe that it is a platform where one shares his opinions in an honest way or expresses ones ideas related to a certain topic. These opinions that people hold can be based on facts and we consider this factor during our project. Even though facts do play a role in opinions there are some topics where emotions seem to play the important role. That is one of the reasons why we have picked the topic - ‘Kashmir Conflict’. This topic deals with the territorial dispute of the Kashmir region between the Indian and Pakistan government. It dates back to the days of India and Pakistan separation. While there may be some facts related to governments involved in this, we feel that emotions of individuals play a vital role in this discussion forum. In this project, we wish to explore the depth of emotions held within individuals in this forum.
As emotional analysis is the most researched topic in recent times, there are many algorithms that have been developed to evaluate the emotions behind writings of humans. Among the many that exist, we will be using the VADER Sentiment analysis algorithm to scrutinize the responses given by individuals on this topic. Also, as our project focuses on the depth of emotions or a variety of emotions, this factor will be evaluated by clustering the users. By keeping our assumption in mind, we will be analyzing our results with known factors. In Quora, every topic has a section called the ‘most viewed writers’. The results that we obtain in our project will be compared with this factor and this will help us evaluate the emotions that users hold within this forum. As we believe that emotions drive social networks, our project will be giving these individuals an emotional metric. This metric will be based on the emotions their writings hold and it will be estimated based on the language that they use, the emphasis of punctuations and considering all the factors related to writings that showcase emotions. As the topic that we have chosen has a wide range of emotions like support, anger, fear within it, we are confident that the dataset that we will extract from this topic will provide us interesting information.

### Qoura-Kashmir-Conflict-Dataset
The CSV files include the questions and answers for the topic- Kashmir Conflict on Quora. The sentiments of these questions and answers was analyzed. The sentiment analysis was calculated based on 3 metrics (positive,neutral,negative).
The following is the list of files that are contained in this project-
1. Questions-Answers-Map.csv- This file maps the list of questions to their respective answers.
2. Questions-Profiles-Map.csv- This file maps the list of users who have commented on the questions.
3. Users-Sentiment.csv- This maps users with an average sentiment value depending on the way they have answered the questions.
4. SentimentQuora.csv- This file consists of the sentimental analysis results of each user's answer for a particular question.

### Sentiment Analysis-
Sentiment analysis is extensively performed on social media websites to understand the opinions of users under various contexts. Even though most of the analysis is subjective, logical objectives have been deduced from these analyses.To perform sentiment analysis on the crawled data the following algorithms/packages have been used-
1. Hutto, C.J. & Gilbert, E.E. (2014). VADER: A Parsimonious Rule-based Model for Sentiment Analysis of Social Media Text. Eighth International Conference on Weblogs and Social Media (ICWSM-14). Ann Arbor, MI, June 2014.
2. Natural Language Toolkit

## Conclusion
After performing various experiments and analyzing our dataset from various aspects, the following conclusions are drawn-
1. The centroid values of the clusters when the cluster size is 2 portrays that the emotions are extreme. As, the size of the clusters is increased these centroid values seem to come closer for the negative and positive cluster. The reason behind this is that there is a lot of variation of emotions held in the topic.
2. When we compared the density of the emotions in each cluster, it was observed that each cluster was equally dense when compared to other cluster. There was no cluster of emotion which was extremely dense.
3. Overlapping of clusters emotions is observed by increasing the size of the clusters. Initially for cluster size 2, there was high overlap of clusters. However, as the cluster size increased, the overlap of the clusters also decreased. This also shows the existence of variation of emotions.
4. Most viewed writers didn't belong to a single cluster, instead it could be seen that they belonged to two different clusters. However, the majority of them belonged to negative cluster and it can be said that emotion they hold in their writings is more closer to the negative side.
Therefore, based on all the conclusions drawn, it can be asserted that emotions do play an essential role in social media and our belief that emotions drive social networks is true.

