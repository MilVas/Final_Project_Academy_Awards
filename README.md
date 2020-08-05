# Academy Awards: Best Pictures

## Content
* [Project Description](#project-description)
* [Dataset](#dataset)
* [File Structure](#file-structure)


## [Project Description]

This project explores the Oscars award for best picture. I started building a supervised machine learning model using Logistic Regression that will predict the winners in this category. As nominations for 2021 are not finalized, the aim was to see if the model would predict the suprising victory of Parasite in 2020. 

Genre is always an important component, but so is the cultural capital, or the pool of talent needed in order to win. Ideally, this model would include all film awards, individual achievements of each member of the film crew and so on. At this moment, the model is built on  directors, such as total number of projects, previous oscar nominations and awards, as well as the the accomplishment of the films, such as Cannes festival or the Golden Globes. 

The model unfortunately did not predict accurately,and showed that 1917 has the highest probability of winning. This model will be expanded in the future by adding information on other memebers of the film crew(most notably producers, screewriters, directors of photography) and other events (Venice, Berlinale, Sundance and Toronto film festivals).  

## [Dataset]

Oscar and Golden Globes data was obtained from Kaggle, and awards, numbers of projects and other information was obtained from Wikipedia and IMDB.

The final dataset contains 51 categories:

Year of Film Release, Year of Academy Awards, Running Number of Academy Awards, Oscar Category, Title of the Film, Information if the Film won the Best Picture Category, 
Film Unique Identifier on IMDB, Genre, Duration of Film, Country of Origin, Language, Writer, Actors, Plot, Name of the Director, Director Unique Identifier on IMDB, Number of Films (and Other Projects) the Director Made, Information on Whether the Director also Produced the Film, Count of Categories the Film was Nominated for, Information on Whether the Director was also Nominated for Best Directing Category and if They Won, How Many Nominations for Best Directing the Director had and how many previous oscars, how Many Films by the Same Director were Nominated for Best Picture, Information on Whether the Director won the Best Director Award at Golden Globes (for the Same Film) and Directors Guild Award, and the Information on Whether the Nominated Film won the Golden Globes, Bafta and Cannes.


## [File Structure]
The repository consists of this readme file, a folder with data, and Jupyter notebooks with data cleaning, web scraping, preliminary analysis and preliminary model.
