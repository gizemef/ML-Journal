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

## Url's for Movie Data

- imdb - movies by genre [Link](https://www.imdb.com/feature/genre/?ref_=nv_ch_gr)
- rottentomatoes - top 100 movies by genre  [Link](https://www.rottentomatoes.com/top/bestofrt/top_100_western_movies/)

# Movie Datasets

## Imdb datasets 
Documentation for these data files can be found on [Link](http://www.imdb.com/interfaces/)

[Link](name.basics.tsv.gz) *title.basics.tsv.gz* - Contains the following information for titles:
tconst (string) - alphanumeric unique identifier of the title
titleType (string) – the type/format of the title (e.g. movie, short, tvseries, tvepisode, video, etc)
primaryTitle (string) – the more popular title / the title used by the filmmakers on promotional materials at the point of release
originalTitle (string) - original title, in the original language
isAdult (boolean) - 0: non-adult title; 1: adult title
startYear (YYYY) – represents the release year of a title. In the case of TV Series, it is the series start year
endYear (YYYY) – TV Series end year. ‘\N’ for all other title types
runtimeMinutes – primary runtime of the title, in minutes
genres (string array) – includes up to three genres associated with the title

[Link](title.akas.tsv.gz) *title.akas.tsv.gz* - Contains the following information for titles:
titleId (string) - a tconst, an alphanumeric unique identifier of the title
ordering (integer) – a number to uniquely identify rows for a given titleId
title (string) – the localized title
region (string) - the region for this version of the title
language (string) - the language of the title
types (array) - Enumerated set of attributes for this alternative title. One or more of the following: "alternative", "dvd", "festival",      "tv", "video", "working", "original", "imdbDisplay". New values may be added in the future without warning
attributes (array) - Additional terms to describe this alternative title, not enumerated
isOriginalTitle (boolean) – 0: not original title; 1: original title

[Link](title.basics.tsv.gz) *name.basics.tsv.gz* – Contains the following information for names:
nconst (string) - alphanumeric unique identifier of the name/person
primaryName (string)– name by which the person is most often credited
birthYear – in YYYY format
deathYear – in YYYY format if applicable, else '\N'
primaryProfession (array of strings)– the top-3 professions of the person
knownForTitles (array of tconsts) – titles the person is known for

[Link](title.crew.tsv.gz) *title.crew.tsv.gz* – Contains the director and writer information for all the titles in IMDb. Fields include:
tconst (string) - alphanumeric unique identifier of the title
directors (array of nconsts) - director(s) of the given title
writers (array of nconsts) – writer(s) of the given title

[Link](title.episode.tsv.gz) *title.episode.tsv.gz* – Contains the tv episode information. Fields include:
tconst (string) - alphanumeric identifier of episode
parentTconst (string) - alphanumeric identifier of the parent TV Series
seasonNumber (integer) – season number the episode belongs to
episodeNumber (integer) – episode number of the tconst in the TV series

[Link](title.principals.tsv.gz) *title.principals.tsv.gz* – Contains the principal cast/crew for titles
tconst (string) - alphanumeric unique identifier of the title
ordering (integer) – a number to uniquely identify rows for a given titleId
nconst (string) - alphanumeric unique identifier of the name/person
category (string) - the category of job that person was in
job (string) - the specific job title if applicable, else '\N'
characters (string) - the name of the character played if applicable, else '\N'

[Link](title.ratings.tsv.gz) *title.ratings.tsv.gz* – Contains the IMDb rating and votes information for titles
tconst (string) - alphanumeric unique identifier of the title
averageRating – weighted average of all the individual user ratings
numVotes - number of votes the title has received

