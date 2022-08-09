# Project Name
>  Linear Regression - BoomBikes


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits

- The company wants to know : Which variables are significant in predicting the demand for shared bikes, How well those variables describe the bike demands
- Data set : Bike Sharing dataset

## Conclusions
- From the first model, P value for atemp is 0.658( highest of all other variables) also it has more VIF value which mean that 'atemp' which altogether means that 'atemp' is less significance and more correlated - hence dropped it
- From the second model, P value for mnth is 0.561( highest of all other variables) also it has more VIF value which mean that 'mnth' ie 13.25 which altogether means that 'mnth' is less significance and more correlated - hence dropped it
- From the thirs model, P value for workingday is 0.041( highest of all other variables) also it has more VIF value which mean that 'workingday' ie 3.23 which altogether means that 'workingday' is less significance and less correlated - hence dropped it
- From the fourth model, P value for hum is 0.001( lowest of all other variables) also it has more VIF value ie 23.73 which altogether means that 'workingday' is more significance and more correlated - hence dropped it
- The above built is the final model with the R square of 82.8
- The variables that are significant in predicting the demand for shared bikes are : clear, temp, cloudy, windspeed, spring, weekday, winter, summer, yr, holiday
- We saw that the R square on the training seet is 0.82 and R square on the test set is 0.79. Hence we can say that what the model has learnt from the training set it is also able to generalise well on the test set.


## Technologies Used
- Python 3.2
- library - pandas
- library - numpy
- library - matplotlib.pyplot
- library - seaborn
- library - warnings
- library - sklearn
- library - statsmodels.api


## Analysis done by Roshni Siddoju
The following file are added to the GIT

1. Data_Dictionary.txt
2. day.csv
3. Roshni Siddoju_Subjective Questions.pdf
4. Roshni_Siddoju.ipynb