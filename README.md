# <div align="center"> What-Movies-Would-a-Programmer-Watch? </div>

[Access notebook here for accurate display of visualizations](https://nbviewer.jupyter.org/github/dania6789/What-Movie-Would-a-Programmer-Watch/blob/main/movie-reccomender-system.ipynb)

If you were a programmer, what movie genres would you most likely watch? What about if you were a doctor, or artist?      
In this three person group project completed over seven weeks, we initially set out to explore one main hypothesis: does occupation have an influence on the type of movie genres a person watches? Using the MovieLens dataset, we performed data wrangling through combining information from several files and reformatting the information in the desired layout in the dataframes. We created visualizations to further explore trends and relationships to see what stands out to explore further. In the final stage of the process, we ended up with insufficient amount of data points to create a reccomendation system based solely on peoples' occupations, and considered run-time, age, geographic location, and other factors could serve as confounding variables, we instead decided to build several machine learning models to predict genres based on the avilable information: users' occupation, age, gender, and past user ratings.      

**Libraries used:**
- Pandas
- NumPy
- Regex
- Matplotlib
- Seaborn
- SciPy
- Scikit-Learn
