# Robert Moses and Parks & Rec

# What is this?

This is a story telling project showing Robert Moses' influence to the New York City through [historical signs](https://www.nycgovparks.org/about/history/historical-signs) made by the NYC Department of Parks and Recreation. Through working on this project, I hope to improve my skill in string comprehension, mapping, scrollytelling, as well as other data visualization abilities.

# Gather the data

This project used [Directory Historical Signs](https://data.cityofnewyork.us/Recreation/Directory-Historical-Signs/xdkk-pvdv) provided by NYC Department of Parks and Recreation. Raw json file can be downloaded directly from NYC Open Data.

# Analyze Data

1. Identify the most mentioned person within the historical signs

I had a question in mind in finding out which person have been mentioned in the most numbers of these historical signs. Each of these historical signs were made to introduce the history of the park or structure where they stands, hence the person it mentions must have influenced the place in some way. Hence, the person who have more wider spread influence on the city will be mentioned in more of these signs.

To extract these names, I turned all the signs' introduction into sentence strings, and used [DeepPavlov](https://github.com/deeppavlov/DeepPavlov) to identify all the names included in each signs. Each name was counted once no matter how many times it was mentioned in one single time.








2. Analyze the relationships between snowfall and salt use

Using separate bar plots, I showed the total tons of salt deployed and the inches of snow fall in each season. Then, I created a separate plot of the tons of salt for each inches of snow.

# What can be improved?

The analysis is no where scientific nor comprehensive, as there are only two years of the salinity data included. I tried to look for other adjacent sites instead, but could not find another good matches. I also hope to directly compare the tons of salt deployed with the river salinity, especially the tons of salt deployed approximate to the river.
