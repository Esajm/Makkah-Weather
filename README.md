# Makkah-Weather

## Source of Data
- Kaggle (https://www.kaggle.com/maramsofyan94/saudiarabiaweather/data)

## Installation
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## Project Motivation
For this project, I was interestested by using saudiarabiaweather/data between 2008-2017 to answer below questions:

1- Could we forecast weather temperature degree based on different factors (Wind direction, Date, and Humidity)?

2- What is the most suitable time to visit Makkah to perform Hajj or Umrah without experiencing too hot weather?

3- Does air pressure level has an impact on the temperature?:

As a programmer who aware about ML programming skilld I intended t obuild a model to predict Makkah weather to facilitae the visitor to select the right date that make thie trip a wonderfol memories.

## Steps Of Works
  - Download the data from kaggle
  - Discover Nan, text values.
  - Filling the Nan valus by using forward-fill propagates method.
  - Delete dupliced columns.
  - text values were converted to numric values.
  - Buildin ML model by using LinearRegression  algorithm.
  - Achived accuracy around 96%.
  - Explore the trends of weather features and plot them by using matplotlib library.

## Results
The main findings of the code can be found at the post available on this link (https://data-science-blog.blogspot.com/2020/02/makkah-weather.html).




