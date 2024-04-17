# Amazon Prime Videos- Movies and TV Shows

###### Tools used: PowerBI

## About Dataset
Amazon Prime is another one of the most popular media and video streaming platforms. They have close to 10000 movies or tv shows available on their platform, as of mid-2021, they have over 200M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Amazon Prime, along with details such as - cast, directors, ratings, release year, duration, etc.

## Dataset Overview
The Amazon Primes Titles dataset is a comprehensive compilation of movies and TV shows available on Amazon Prime, covering various aspects such as the title type, director, cast, release year, duration, country, rating, genres (listed in), and a brief description. This dataset is instrumental for analyzing trends in Amazon Prime content, understanding genre popularity, and examining the distribution of content across different regions.

### Key Details
###### Total Entries: The dataset contains 9,668 entries, each representing a unique movie or TV show.

###### Columns: There are 12 columns in the dataset:
1. show_id: A unique identifier for each title.
2.type: The category of the title, which is either 'Movie' or 'TV Show'.
3. title: The name of the movie or TV show.
4. director: The director(s) of the movie or TV show. (Contains null values for some entries, especially TV shows where this information might not be applicable.)
5. cast: The list of main actors/actresses in the title. (Some entries might not have this information.)
6. country: The country or countries where the movie or TV show was produced.
7. date_added: The date the title was added to Netflix.
8. release_year: The year the movie or TV show was originally released.
9. rating: The age rating of the title.
10. duration: The duration of the title, in minutes for movies and seasons for TV shows.
11. listed_in: The genres the title falls under.
12. description: A brief summary of the title.


Potential Use Cases:
Content Analysis: This dataset can be used to perform detailed content analysis, such as genre popularity over time, distribution of content production across different countries, and trends in movie versus TV show production.
Market Analysis: Market researchers can utilize this dataset to analyze Netflix's content strategy, including their focus on international markets, genre diversification, and investment in original content.