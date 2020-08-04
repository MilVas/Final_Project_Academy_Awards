# Academy Awards: Best Pictures

## Content
* [Project Description](#project-description)
* [Dataset](#dataset)
* [File Structure](#file-structure)


## [Project Description]

This project explores the Oscars award for best picture. I started building a supervised machine learning model using Logistic Regression that will predict the winners in this category. As nominations for 2021 are not finalized, the aim was to see if the model would predict Parasite winning the awards in 2020, which was quite a surprise. 

Genre is always an important component, but so is the cultural capital, or the pool of talent needed in order to win. Ideally, this model would include all film awards, individual achievements of each member of the film crew and so on. At this moment, the model is built on  director`s data, such as total number of projects, previous oscar nominations and awards, as well as the film`s accomplishment in few ceremonies such as Cannes festival or the Golden Globes. 

The model unfortunately did not predict accurately,and showed that 1917 has the highest probability of winning. This model will be expanded in the future by adding information on other memebers of the film crew(most notably producers, screewriters, directors of photography) and other events (Venice, Berlinale, Sundance and Toronto film festivals).  

## [Dataset]

Data was obtained from the main Çatalhöyük database, available at www.catalhoyuk.com. 
It contains records from 308 samples from building 77 with contextual information and density (weight/litre) for each material type

## [File Structure]
The repository consists of this readme file, a folder with data, and Jupyter notebooks with data cleaning, web scraping, preliminary analysis and preliminary model.
