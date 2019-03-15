# Dataset for reputation

This dataset represents a set of submissions sent by authors (identified by handle column) in Codeforces platform, which were analyzed and then a set of 423 features were extracted.

## Relevant Columns

First column represent the submission unique ID. From second column to column 424th are the values of the features. Last columns are: contest unique identifier, datetime of submission delivery, programming language used for the submission, problem index (along with contest ID allows to unique identify the problem), author identification (handle), the rating of the author just after the contest finishes, and the type of contestant (it means if the author was a beginner or advanced depending of his/her ranking).

## How the type was determined?

Using the ranking each type is determined. If ranking is less than or equals to 1650 points, the submission is considered as made by a beginner. On the other hand, if submission has a ranking great than or equals to 2150 it is considered as sent by an advancer programmer. 
