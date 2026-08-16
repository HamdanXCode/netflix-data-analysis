# Netflix Data Analysis

This is one of my first data analysis projects, where I explored a dataset containing Netflix Movies and TV Shows.
I used Python to clean the data, look for patterns, and create visualizations to better understand the content available on Netflix.

## What I Used
* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## What I Explored
While working on the dataset, I looked at things like:
* Movies vs TV Shows
* Netflix ratings
* Popular genres
* Countries with the most titles
* Directors and actors with the most titles
* Content released over the years
* Number of seasons in TV Shows
* Movie durations
* How many titles were added to Netflix each year

## Some Interesting Findings
A few things I found during the analysis:
* Movies make up around **69%** of the dataset, while TV Shows make up around **31%**.
* **TV-MA** was the most common rating, making up about **36.77%** of the titles.
* Around **66.72%** of the TV Shows had only one season.
* The median movie runtime was **98 minutes**.
* Around **90.82%** of the titles were added between **2017 and 2020**.

## Data Cleaning
Before starting the analysis, I checked the dataset for missing values and duplicates.
I also converted the `date_added` column into a proper datetime format and created a separate year column from it. 
Columns containing multiple values, such as genres, countries, and cast members, were split so they could be analyzed more easily.

## Author
**HamdanXCode**
GitHub: https://github.com/HamdanXCode
