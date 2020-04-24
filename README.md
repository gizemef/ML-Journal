# ML in Architecture

Hello! I'm Gizem and This is my Journal which is about Machine Learning in Architecture 


## 25 Open Datasets for Deep Learning

[Link](https://www.analyticsvidhya.com/blog/2018/03/comprehensive-collection-deep-learning-datasets/) 

1. MNIST - handwritten digits - 30 MB
2. COCO - object detection - 25 GB
3. ImageNet - dataset of images - 150GB
4. Open Images - image URL dataset - 500 GB
etc...

## How to collect your deep learning dataset

- How to collect your deep learning dataset [Link](https://towardsdatascience.com/how-to-collect-your-deep-learning-dataset-2e0eefc0ba24)
- Collecting Movie Data [Link](https://towardsdatascience.com/collecting-movie-data-445ca1ead8e5)
- Movie Posters as a Deep Learning Dataset [Link](https://towardsdatascience.com/movie-posters-81af5707e69a)
- Movie genre classifier using a dataset created using Google Images [Link](https://towardsdatascience.com/building-a-movie-genre-classifier-using-a-dataset-created-using-google-images-4752f75a1d79)
- Wandora Imdb Exractor [Link](http://www.wandora.org/wandora/wiki/index.php?title=IMDB_extractor) 
![Image](/Images/Imdb_10.png)


## Movie Datasets

### Imdb datasets 
Documentation for these data files can be found on [Link](http://www.imdb.com/interfaces/)

**title.basics.tsv.gz** [Link](name.basics.tsv.gz)
Contains the following information for titles: *tconst (string), titleType (string), primaryTitle (string), originalTitle (string), isAdult (boolean), startYear (YYYY), endYear (YYYY), runtimeMinutes, genres (string array)*

 **title.akas.tsv.gz** [Link](title.akas.tsv.gz)
Contains the following information for titles: *titleId (string), ordering (integer), title (string), region (string), language (string), types (array), attributes (array), isOriginalTitle (boolean)*

**title.principals.tsv.gz** [Link](title.principals.tsv.gz) 
Contains the principal cast/crew for titles: *tconst (string), ordering (integer), nconst (string), category (string), job (string), characters (string)*


## Kaggle Datasets

**Movie Genre from its Poster** [Link](https://www.kaggle.com/neha1703/movie-genre-from-its-poster)

The movie posters are obtained from IMDB website. The collected dataset contains *IMDB Id, IMDB Link, Title, IMDB Score, Genre and link* to download movie posters. Each Movie poster can belong to at least one genre and can have at most 3 genre labels assigned to it. As the dataset also includes the IMDB score, it would be really interesting to see if movie poster is related to rating.

**IMDB data from 2006 to 2016** [Link](https://www.kaggle.com/PromptCloudHQ/imdb-data)

Here's a data set of 1,000 most popular movies on IMDB in the last 10 years. The data points included are:
*Title, Genre, Description, Director, Actors, Year, Runtime, Rating, Votes, Revenue, Metascrore*
