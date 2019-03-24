# Have Streaming Services Killed Cinema?

## Project Description

Every month there seem to be less movies showing in theatres that are worth the time and effort to view. Genres have shifted to heavy handed drama and popcorn flicks, and overall quality has declined (based on viewer and critic ratings).This project is interested in the changes in aggregate quality of movies available across all platforms and if it is declining like expected, what is influencing the decline. Of particular interest is the rise in streaming services like Netflix and Hulu.

## Research Question to Answer

Primary Hypothesis
If the rise in streaming services has contributed to a decrease in cinema quality then mean movie ratings before the year 2011 will be higher than the mean movie ratings after the year 2011.

Primary Null Hypothesis
If the rise in streaming services has not contributed to a decrease in cinema quality then mean movie ratings before the year 2011 will not be higher than the mean movie ratings after the year 2011.

H0 = past mean ratings > current mean ratings
H1 = past mean ratings <= current mean ratings

Secondary Hypothesis
H0 = 

1. Is the increase in streaming services and offerings associated with a decrease in overall Cinema quality?
    a. Has movie quality declined since the year 2000? (this date is flexible based on available data)
    b. Has revenue for brick and mortar Theatres declined in the same time period?
        i. Is the decrease in quality and decrease in revenue (if found to be occurring) proportionate?
    c. Has production of tv series increased in the same time period?
        i. How does the quality of tv series compare to quality of movies. (based on ratings)
    
## Data sets to be Used

A series of API calls from OMBD was used to pull historical movie ratings and produced the below data points:

Title: Title of movie or series, the localized title
Year: represents the release year of a title
Released: represents the release date of a title
Runtime: primary runtime of the title, in min or hr and min
Genre: There are a total of 55 unique genres included in the raw data, between 1 and 10 for each title
Director: director(s) of the given title
Writer: writer(s) of the given title
Actors: Lead actors
Plot: Short synopsis of plot
Country: Country of origin
Awards: summary of awards if any
RT_Rating: rotten tomatoes rating
Metascore Metascore rating
imdbRating: weighted average of all the individual user ratings
imdbVotes: number of votes the title has received
imdbID: a tconst, an alphanumeric unique identifier of the title
Type: the type/format of the title (e.g. movie, short, tvseries, tvepisode, video, etc)
BoxOffice: Box Office earnings
Production: Production company associated with title

### Limitations of the data





