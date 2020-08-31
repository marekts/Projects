As a fan of literature I decided to discover recommendation systems for myself with books dataset.

I use dataset goodbooks10k (https://github.com/zygmuntz/goodbooks-10k) which include data about authors, titles, genres and ratings. 

The first technique I am going to use is **Collaborative Filtering (user-based filtering)**. This method uses other users to recommend items to the input user. 
It attempts to find users that have similar preferences and opinions as the input and then recommends items that they have liked to the input. 
I will use simple method based on **Pearson correlation** and python's library **pandas** for building this system.    

The process for creating a User Based recommendation system is as follows:
- Select a new user 
- Find the top neighbours based on new user's books ratings
- Calculate a similarity score using Pearson correlation
- Find average score for each book
- Recommend books with the highest score

I will be using only dataset with ratings and dataset with books information. 

This is the simple method and it doesn't cover many topic and there are many ways to improve system, but I think it's a good way for get acquainted with recommendation systems.

**I will be complementing this repository while I will dig deeper into recommender systems...**





