# MAIS202

## Description 

This project analyzes Youtube comments given a link and gives the overall sentiment towards the specified video. Since Youtube removed their disliked button, it will allow people see if it is a good video or a bad video quickly using this project.

## Dataset

This dataset used for this application consists of IMDB reviews with labels classified in 5 different classes:
 
 - Very negative 
 - Negative
 - Neutral
 - Positive
 - Very positive
 
 
## The model 

For this project, I used the pre-trained BERT, which I fine-tuned. To evaluate the result the results, I used the categorical accuracy metric. As for the loss, I used the categorical cross entropy loss.
