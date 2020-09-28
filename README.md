## Recommend Movies ##  

dataset https://www.kaggle.com/grouplens/movielens-20m-dataset  
The code of this nootbook is referenced from https://www.datacamp.com/community/tutorials/recommender-systems-python
    
Recommender systems are among the most popular applications of data science today. They are used to predict the "rating" or "preference" that a user would give to an item. Almost every major tech company has applied them in some form. Amazon uses it to suggest products to customers, YouTube uses it to decide which video to play next on autoplay, and Facebook uses it to recommend pages to like and people to follow.  

What's more, for some companies like Netflix, Amazon Prime, Hulu, and Hotstar, the business model and its success revolves around the potency of their recommendations. Netflix even offered a million dollars in 2009 to anyone who could improve its system by 10%.  

There are also popular recommender systems for domains like restaurants, movies, and online dating. Recommender systems have also been developed to explore research articles and experts, collaborators, and financial services. YouTube uses the recommendation system at a large scale to suggest you videos based on your history. For example, if you watch a lot of educational videos, it would suggest those types of videos.  


- **Simple recommenders**: offer generalized recommendations to every user, based on movie popularity and/or genre. The basic idea behind this system is that movies that are more popular and critically acclaimed will have a higher probability of being liked by the average audience. An example could be IMDB Top 250.  
    
- **Content-based recommenders**: suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person likes a particular item, he or she wil  l also like an item that is similar to it. And to recommend that, it will make use of the user's past item metadata. A good example could be YouTube, where based on your history, it suggests you new videos that you could potentially watch.
    
- **Collaborative filtering engines**: these systems are widely used, and they try to predict the rating or preference that a user would give an item-based on past ratings and preferences of other users. Collaborative filters do not require item metadata like its content-based counterparts.  
    
    
### Simple Recommenders ###   

As described in the previous section, simple recommenders are basic systems that recommend the top items based on a certain metric or score. In this section, you will build a simplified clone of IMDB Top 250 Movies using metadata collected from IMDB.  

The following are the steps involved:  

Decide on the metric or score to rate movies on.  

Calculate the score for every movie.  

Sort the movies based on the score and output the top results.  

### Recommender Systems: ###
1. User Based Recommender Systems
2. Item Based Recommender Systems

A recommender system is a subclass of information filtering system that seeks to predict the "rating" a user would give to an item. 
Mainly three types of recommendation systems in machine learning.

1. Content Filtering: In this algorithm, we try finding items look alike.
2. Collaborative Filtering: we try to search for look alike customers and offer products based on what his/her lookalike has chosen. This algorithm is very effective but takes a lot of time and resources.
3. Hybrid Filtering: 


