# MICROSOFT-PROJECT# MOVIES ANALYSIS
BY ODHIAMBO MUMBI
BUSINESS UNDERSTANDING

Currently most big companies have began creating original video content allover. Microsoft has seen this and wants to invest in the same and as such I hae been tasked with getting information that will help them break into that sector. They have decided to create a newmovie studio, but have no idea on anything to do with creating movies. I have therefore been charged with finding out the types of movies currently doing well in the box office, translate these findings and into actual insights that will help Microsoft make a more informed decision. I therefore chose to come up with prompts to help me analyse the data set and put out relevant information to them.They include:

1. Currently what genre/s of movies are doing well when it comes to ratings?
2. Which films are currently rated the highest at the box office?
3. What was the production budget for these films and what is their current return revenue? 
4. Which production companies have produces some of the movies currently ranked the highest?
5. Which is the release dates of some of the movies doing well when it comes to ranking?
DATA UNDERSTANDING

For me to be able to source the data  want to work with and get clear insights on my prompts, i sourced the data from a highly credible dataset:
bom.movie_gross.csv.gz

This is a csv file,where each record represents the movie,its genre, the release data,,production_budget amongsth a lot of ther columns.From this dataset I selected the following columns:

1. popularity -which gave me information on the general ratings of different movies
2. budget - amount that was spent on the filming projects and other costs incurred during the movie production
3. revenue - the amount that the movies was able to generate after its release
4. release data - the year and month that the movie was released
5. genre - the exact type of movie that is popular in theatres currently
6. vote count - how many people voted for the movie in terms of ranking
7.production companies - the company tasked with producing the movies
DATA PREPARATION

1. Loading the data with thevarious libraries i was to use.

 I loaded the data with the pandas ibrary then proceeded to carry on with the data cleaning process.
 DATA VISUALIZATION
 I opted to make use of majorly bag graphs as they are easie to comprehend and understand in order to show the various relationships between budget and revenues, and alse check if there was a definite connection between the production company and the movie ratings.
 ![image](https://github.com/Mumbsss/MICROSOFT-PROJECT/assets/133156815/e6610cf1-862f-4257-b58c-535d94060cd6)
 From this bar graph, i was able to conclude that Drama/Science fiction was least budgetted for when it came to the production stage as compared to Action/Adventure/Science fiction.
 ![image](https://github.com/Mumbsss/MICROSOFT-PROJECT/assets/133156815/159eeeb1-e80e-497a-b95e-0efdff143dd6)
 Across the different genres of movies, i was able to clearly conclude that Action/Adventure/Science Fiction/Fantasy yielded the most amount of revenue with Action/ Adventure/ Science ficton and Thriller coming in at a close second. So the production companies that focused onthese two genres generated a lot of revenue after the production stage. Drama/Science fiction yielded the least amount of revenue.
 ![image](https://github.com/Mumbsss/MICROSOFT-PROJECT/assets/133156815/38c89961-8d6d-4d68-a9a1-2ef704e8e189)
 Here, we are able to see that the production company whose movie got the best vote count was Village roadshow picture/Kennedy Miller productions wit close to 6000 vote count. Universal studios/Amblin statements came in at a close second with its movie getting aslightly lower vote count.
 # CONCLUSION

I was able to draw a few conclusions from my analysis. They include:

a. The genre with the highest ranings in terms of vote counts was comedy.

b. For most companies, their revenues or incomes directly matched the amount they had invested in their production plan and thus i was able to conclude that the revenues and budgets had a close relationship. This would only mean that the amount invested in making the movie had a direct inflence on that which the movie generated after it was released.

c. Action/Adventure movies are the most expensive to produce.

d. Drama/Science fiction are the least expensive to produce and cosequenntly tend to yield a less amount of revenue.
# RECOMMENDATIONS

Based on the conclusions i was able to draw from my analysis, I have thre main recommendations to make to the Microsoft production team:

1. They should avoid investing in the Dama/Science fiction genre as it has very minimal demand meaning that they would spend a lot of time in production and yield very minimal revenues at the end of it all.

2. They should work with the top five production companies based on my bar graph if they want to see better results,

3. Microsoft should focus more on producing comedy films if they want to break into the film industry and ensure they saty there.


