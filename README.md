# <div align="center"> What-Movies-Would-a-Programmer-Watch? </div>

[Access notebook here for accurate display of visualizations](https://nbviewer.jupyter.org/github/dania6789/What-Movie-Would-a-Programmer-Watch/blob/main/movie-reccomender-system.ipynb)

## Abstract

If you were a programmer, what movie genres would you most likely watch? What about if you were a doctor, or an artist? Would your occuptation have any influence on your Saturday night movie decisions? <br>
In this three person project completed over the course of seven weeks, we initially set out to explore one hypothesis: does occupation have an influence on the type of movie genres a person watches? 

## Approach
Using the MovieLens dataset, we performed data wrangling through merging information from several data files and reformatting the information in the desired layout using pandas and numpy. We created visualizations to explore trends and variable relationships using seaborn and matplotlib. In the final stage, we concluded we needed a greater amount of data to create a reccomendation system based solely on peoples' occupations, realising that run-time, age, geographic location, etc could serve as confounding variables. We instead decided to test a few select machine learning models on the data to predict genres based on: users' occupation, age, gender, and past user ratings.   

**Libraries used:**
- Pandas
- NumPy
- Regex
- Matplotlib
- Seaborn
- SciPy
- Scikit-Learn

## Areas of Improvement
Looking back, there is much improvement that could have been done in this project such as applying dimensionality reduction techniques to get insight on which variables are contributing most to user's movie genre choice, as well as not viewing the data before deciding on the ML models as this increases the VC dimensions and can be the result of the low accuracy scores on out of sample data. Finally, the MovieLense dataset could have been used in conjunction with other available datasets that can offer more useful variables that can potentially be helpful for building the recommendation system.


