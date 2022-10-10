# Predicting Better Movies
 This project is about using several dataframes from IMDB to make my own sql database and use what I've learned to discover what makes a successful movie. The project is broken into 5 parts: getting the ratings, titles and revenue data and compressing them into csv.gz files Performing api calls to extract data between the years 2000 and 2020. Creating an SQL database using all the extracted data. Performing hypothesis testing to discover what makes a successful movie, and lastly developing a linear regression model that can predict successful movies.

### DATA 
Source: https://datasets.imdbws.com/
I also perfomed api calls to extract additional data.

### Methods

* I preclean the data to make data extraction easier and less messy in the following steps. 
* Perfrom api calls to get movie data between the years 2000 and 2020
* Create an SQL data base to analyze the hordes of information efficiently
* Conduct hypothesis testing to discover what makes a movie successful
* Create a linear regression model to predict successful movies

### Visuals

![Screenshot (98)](https://user-images.githubusercontent.com/107956865/194787086-ce943a0c-b82b-430c-8ff8-c2ae39e676e2.png)

( I wish I could take credit for this masterpiece of a loop extraction, the for loop was provided by the education team from coding dojo. I just had to figure out how to get it to work and still needed a little extra help from my instructor Purvi Kansara :P )

![Screenshot (99)](https://user-images.githubusercontent.com/107956865/194787095-a928721c-ca91-4275-945a-24685c8faadc.png)

![Screenshot (100)](https://user-images.githubusercontent.com/107956865/194787101-3098dfe6-3450-4b6d-9241-1a4c1d7840df.png)

This plot demonstrates which movie genres generated the most revenue. Some generes were less common than others but earned more income by 'weight'.
For example in my data set I had 455 sci-fi movies and 4846 dramas. Sci-fi movies generated apx 79 billion ($78,959,170,000) and dramas apx 158 billion (158,780,200,000) in revenue during that 20 year period. By weight (count) sci-fi movies generated more money but dramas are more popular.

### Outcomes

We've examined three aspects that contribute to a successful movie: rating, genre, and runtime. Movies rated PG or PG-13 out sold other movies with different ratings. Adventure, Action, Comedy, Drama, and Animation movies were also more successful than any other genre. Lastly movies that were 2.5 hours or longer generated more revenue than movies that were 90 minutes or less.

* All in all, if you want a movie to have a higher chance of succeeding, follow these guidelines.

1. Keep it PG or PG-13.
2. Utilize 2-3 of the above genres.
3. Don't rush the story.

* Obviously there are other factors involved in a successful movie that I didn't examine, and I'm not claiming you're guaranteed to make a banger of a movie if you do these things, reality can be pretty chaotic and sometimes your timing has to be lucky. I'm not an expert, I just looked at a lot of data to see what worked and am showing you what I've found. Having said all that, I think these results make sense and I'm sure you can think of some pretty successful movies that have the above traits in common. Good luck out there and may the Shwartz be with you!

### Limitations and Next Steps
I didn't examine every possible feature that goes into making a movie, I chose three aspects that seemed the most useful and had the data for. I still need to develop my machine learning model. There are some parts of the data that could've been cleaned a little bit better in my opinion, but due to the nature of the questions I had to answer I couldnt just drop all my missing rows or I wouldn't have access to the data necessary to answer those questions! So some imputations and replacements for missing values were made and I had to ignore a lot of rows with 0's in them as they just wouldn't give me an accurate representation of the data.

### For further information


For any additional questions, please contact **seanrommes@gmail.com**
