# TMDb-Movie-Data
This Project works on dataset from The Movie Database (TMDB) about ten thounsands of different movies.
The various properties associated with movies are visualized using multiple different plots to identify patterns in the data
and answer the key question.

## Key Question

_What properties are associated with highly rated movies?_

## Data Wrangling & Cleaning

The dataset exists in file called 'tmdb-movies.csv', i load the file in the dataframe, then assesst problems, cleaning and finally visualize it.

The first step in exploring the data and uncovering insightful conclusions related to the key question is to define the question. _Highly rated_ can be defined in many ways using this dataset since two columns can represent this: 'vote_average' and 'popularity'. To conduct further analyses on this metric, the more sufficient column must be chosen to define *highly rated*. In order to choose this, box plots for both are visualized which indicate that 'vote_average' is more evenly distributed and thus easier to decipher and work with. Moving forward, all analyses will be done against this column.  

## Tools

* Dataset (tmdb-movies.csv)
* Python and its libraries (Numpy, Pandas, Matplotlib)
* Jupyter notebook
