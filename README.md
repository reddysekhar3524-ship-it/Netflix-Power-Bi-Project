# Netflix-Power-Bi-Project
## About Dataset
### Context
Dataset contains the list and metadata of all TV Shows and Movies available on Netflix currently about 7000 taken from the IMDB website.
Upvote if you liked it.

#### Content
netflix_list.csv

1. imdb_id : Unique show identifier.
2. title : Title of the show.
3. popular_rank : Ranking as given by IMDB when filtered by popularity.
4. certificate : Contains the age certifications received by the show. Many null values.
5. startYear : When the show was first broadcasted.
6. endYear : Year of show ending
7. episodes : Number of episodes in the show. 1 for movies.
8. type : Movie or Series
9. orign_country : Country of origin of the show
10. language : Language of the show.
11. plot : Synopsis of the show.
12. summary : Summary of the story of the show.
13. rating : Average rating given to the show.
14. numVotes : Number of votes received by the show.
15. genres : Genre the show belongs to.
16. isAdult : 1 If adult content present. 0 if not.
17. cast : Main cast of the show in list format.
18. image_url : Link to poster image.
    
### Acknowledgements
This is collected from IMDB website
Data collected by web scrapping through the shows ranking pages with filtered to show Netflix related content(16000+ entries) and noting down the imdb_id, followed by single page search for each collected ID and unique title name.
