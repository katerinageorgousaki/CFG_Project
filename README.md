# CFG_Project

## Predicting Film Success: Insights and Recommendations for the Film Industry
### Required Libraries
To run this project and all its associated files in full, you will need to import the following libraries:
json, requests, pprint, pandas, matplotlib, seaborn, numpy and IPython.display.

### Other notes:
When loading datasets, take care to edit the file path to load each file correctly and save all images where the main file is saved to be able to view them in the jupyter notebook. 

### In this repo you can find:
- In the Scripts folder:
 Two files that can be used to call the TMDb API and to clean the IMDb dataset.

Running the TMDB_API.py file will call the TMDB API - uncomment the sections individually to run them.
In order to call the TMDb API an authentication token is required, which is provided in the file. However, further information, including how to source your own authentication token, is available at https://developer.themoviedb.org/reference/intro/getting-started.

- In the Data/Clean folder: 
If the TMDb file is run in full, it will write a number of files including a list of genres and their ids (TMDB_reference.json), the most popular films with original language in English and watch region GB for 2014-2024 (first 5 pages only) (all_test.json) and the top 200 most popular people (people_test.json). These files are included in the Data folder of this repo.

To access the original IMDb dataset without cleaning, please follow this link: https://www.kaggle.com/datasets/omarhanyy/imdb-top-1000 (it is too large to access via github). 



- In the Notebooks folder:
The team JUPYTER notebook (file_project_main.ipynb) including our data loading, cleaning, transformation, analysis, visualisation and results was authored by Beccy, Felicia and Tanvi. 
To run this, run all cells once, in order.


- In the Reports folder:
Our final report detailing our aims, methodology and conclusions.
