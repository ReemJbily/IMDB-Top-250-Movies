# IMDB-Top-250-Movies

#### Data set is about movies from year 1921 to 2022.

#### It containes 250 rows and 13 columns.

####-**Columns are**:
####rank - Rank of the movie.
####name - Name of the movie.
####year - Release year.
####rating - Rating of the movie.
####genre - Genre of the movie.
####certificate - Certificate of the movie.
####run_time - Total movie run time.
####tagline - Tagline of the movie.
####budget - Budget of the movie.
####box_office - Total box office collection across the world.
####casts - All casts of the movie.
####directors - Director of the movie.
####writers - Writer of the movie.
####-There are **no null values** in any cloumn but there are **Not Available** values.
####-Numerical columns are **year**, **rank** and **rating**.
####-**In preprocessing section**
####I convert budget/box_office columns to numerical and fixed some data, so I can find correlations without affecting the over all results.
####-**In Statistical operation section**
##Insights on the data:
####1-Correlation between budget and box_office(earnings).
####2-Correlation between budget and rating.
####3-The most appearing actor/actress in movies.
##-**Results:**
####-No correlation between budget and box_office==> the earnings of a movie does not relate to amount of money spent.
####-Nocorrelation between budget and rating==> amount of money spent does not affect the movie rating. 
####-No correlation between box_office and rating==> highy rating does not mean more earnings.
####-A weak correlation between year and box_office==> movies reached more regions so more people watched them.
####-The most appearing actor/actress in movies is **Robert De Niro** which was 9 times.
##-**EDA Section:**
###what I did:
####1-find outliers in **rating/box_office** using **box plot**.
####2-relation between **rank** and **rating** using **scatter plot**.
####3-relation between **genre** and **rating** using **scatter plot**.
####4-show data as percentige of a whole for the first ten **genres** using **pie plot**.
####5-distribution of certificate appearings in years using **histogram**.
####6-**certificate** categories using **bar plot**.
####7-top ten directors using **bar plot**.
##-**results**:
####-the most appearing genre is **Drame**.
####-the director with most movies is **Christopher Nolan**.
####-the most appearing certificate is **R** with more tahn 120 appearings in all years.
