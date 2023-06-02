# Smarter Farming Maps
This project seeks to visualise data in the way of a collection of articles covering studies in smarter farming. The articles was collected throughout the spring of 2023, and covers a number of different experiments, literary reviews, and studies pertaining to how farmers and other actors in the industry view the growing possibilities in precision agriculture technologies. 

As mentioned in the paper of this project, the `articles` file will be pulled from a Google sheet, but please notice that a chunk of code, where the articles are read in as an Excel file, has been added for offline work, and can be uncommented for this purpose.   

The `articles` data contains 10 columns:

| First Header  | Second Header |
| ------------- | ------------- |
| Author | The author(s) of the article  |
| Year | The year the article was published |
| Title | The title of the article  |
| Journal | The literary journal that published the article |
| Abstract | A short abstract of the article  |
| Keywords | A number of keywords to describe the articles  |
| Country | The country of origin of the article  |
| Questionnaire/Interview | A binary variable for whether or not the article has a questionnaire or interview included in its study |
| Citations |  The number of times the article has been cited |
| URL | The URL of the article  |


* Author  
  + The author(s) of the article  
* Year
  + The year the article was published
* Title
  + The title of the article
* Journal
  + The literary journal that published the article
* Abstract
  + A short abstract of the article
* Keywords
  + A number of keywords to describe the articles
* Country
  + The country of origin of the article
* Questionnaire/Interview
  + A binary variable for whether or not the article has a questionnaire or interview included in its study
* URL
  + The URL of the article

Besides the `articles` data the project also makes use of a GeoJSON file containing polygons for all the worlds countries. This file is essential for visualising the `articles` data, as the aim is to show the country of origin of all articles in an easy to view format. The file was pulled from the following GitHub repository:

https://github.com/datasets/geo-countries

The `countries` data contains three columns:

* ADMIN
  + The common name of the country
* ISO_A3
  + A three letter ISO code for the country
* geometry
  + Multipolygon geometry of the country

For further description of the data I refer to the XXX section in the project paper. 