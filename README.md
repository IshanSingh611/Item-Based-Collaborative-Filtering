# Item-Based-Collaborative-Filtering
There is one famous quote about customer relationship. The summary of the quote like this <b>"Customers don't know what they want until we show them."</b> So Recommendation Systems will help customers to find information, product & services they might not have thought of.

Music, T.V., Retail are one of the examples in Recommendation Systems.

There are many types of Recommendation Systems exists but in this particular Jupyter file i created - ITEM BASED COLLABORATIVE FILTERING.

This algorithm filtering the items but instead of taking weighted sum of ratings of <b>"Nearest Neighbors"</b>, we take the weighted sum of <b>"Item Neighbors"</b>.

#Steps for Item Based Collaborative Filtering
- Create a sample dictionary of users with web series and their ratings
- Create a function to print the unique set of web series
- Create a function to implement cosine similarity between two items 
- Item Based Collaborative consists of two phases:

  #1st phase
  
  *Find Similarity between the target item with all other remaining items.
  
  #2nd phase
  
  *Recommending web series to the target user which are most similar to the items which has already seen by the user.
- Create a function to find seen web series and unseen web series to the target user.
- Create a function to give recommendations.
