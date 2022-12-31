# Book-Rental-Recommendation
DESCRIPTION

Book Rent is the largest online and offline book rental chain in India. They provide books of various genres, such as thrillers, mysteries, romances, and science fiction. The company charges a fixed rental fee for a book per month. Lately, the company has been losing its user base. The main reason for this is that users are not able to choose the right books for themselves. The company wants to solve this problem and increase its revenue and profit. 

As an ML Engineer, I have focused on improving the user experience by personalizing recommendations for books to each user's needs. To achieve this, I have modeled a recommendation engine that uses the behavior of similar users to provide personalized recommendations to each user. This ensures that users are able to rent books that align with their tastes and preferences. As a result of these efforts, the user experience has been enhanced, as users are now able to easily find and rent books that they are interested in.

Dataset description:

BX-Users: It contains the information of users.
user_id - These have been anonymized and mapped to integers
Location - Demographic data is provided
Age - Demographic data is provided

BX-Books: 
isbn - Books are identified by their respective ISBNs. 
book_title
book_author
year_of_publication
publisher

BX-Book-Ratings: Contains the book rating information. 
user_id
isbn
rating - Ratings (`Book-Rating`) are either explicit, expressed on a scale from 1–10 (higher values denoting higher appreciation), or implicit, expressed by 0.

