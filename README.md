# Book-Recommendation-System
We need to create a recommender system for the books readers on the basis of given data sets. Dataset Description we have 3 files in our dataset which is extracted from some books selling websites.
web site for data:
1.Books – first are about books which contain all the information related to books like an author, title, publication year, etc. 
2.Users – The second file contains registered user’s information like user id, location. 
3.ratings –  Ratings contain information like which user has given how much rating to which book. So based on all these three files we can build a powerful collaborative filtering model. 

Approach to a problem statement
We do not want to find a similarity between users or books. we want to do that If there is user A who has read and liked x and y books, And user B has also liked this two books and now user A has read and liked some z book which is not read by B so we have to recommend z book to user B. This is what collaborative filtering is.

So this is achieved using Matrix Factorization, we will create one matrix where columns will be users and indexes will be books and value will be rating. Like we have to create a Pivot table.

