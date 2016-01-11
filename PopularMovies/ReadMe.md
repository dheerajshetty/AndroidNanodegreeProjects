# TMDB API Key

1. TMDB API key is not shared in the project.
2. Please change the below line in MovieListFragment.java to include your TMDB API key.

`private static final String TMDB_API_KEY = "<TMDB API KEY HERE>";`

# Stage 1 Deliverables

* Upon launch, present the user with an grid arrangement of movie posters.
* Allow your user to change sort order via a setting:
  * The sort order can be by most popular, or by highest-rated
* Allow the user to tap on a movie poster and transition to a details screen with additional information such as:
  * original title
  * movie poster image thumbnail
  * A plot synopsis (called overview in the api)
  * user rating (called vote_average in the api)
  * release date
  
# Note about sorting
  
* Sorting done by passing different sort order query parameters - popular.desc, vote_average.desc
  * Considered vote_count > 50 to get cleaner results when sort order is based on ratings.
* Another way to do it - sort the existing popular movie list based on user ratings. 
