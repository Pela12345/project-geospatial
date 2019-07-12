# Project GeoSpatial

## Objective: To obtain the best location for a new video-gaming company subject to a set of preferences of the company´s employees. I will analyse a set of companies from the companies.csv dataset and will select the company I believe has the ideal location, then locating our company in such place.


# About:

## I decide to focus on meeting the criteria I deem most important. First, I want our company to be located in radius of 2km of the technology industry companies, thus I only focus on keeping companies in the top 5 most popular tech categories acording to the category-code, disregarding any non-tech companies. Second, I also want our company to be close to new companies. For this I calculate a ratio of New to Old companies in the Area based on the year founded. I disregard any companies with no new companies close and prefer those with a higher ratio. Third, I want our company to be located in an area with as many employees of other companies close as possible in order to boost networking and synergies. For this I calculated the number of tech employees in the radius of 2km. 

## With these 3 conditions I create a ranking, sorted first by the NewOld Ratio and then by the number of employees near. I decide to keep the highest ranking companies only and proceed to look at their locations in a map. I use Tableu to zoom in and add my final criteria to select the winner: Being as close as possible to a Starbucks Coffee. 

# Final Result:

## After drilling down to a selection of the top 10 companies, I use Tableu to obtain the ideal location. The final result is to locate the company as close as possible to DotCom Infoway (40.812933, -73.958633) in the city of New York. When contrasting with the required criteria I can say that this location, it clearly meets being surrounded by tech companies, by startups (given New/Old ratio is significantly higher than 1), by a Starbucks very close. Also, the vibrant city of New York is known for having plenty of places to party and a wide range of vegan restaurants.

## Included:

### Document 1: Project-Query-Clean

#### In this jupyter notebook I guide you step by step (with more detailed comments inside) through making the initial query from mongo DB, cleaning the data, getting geolocations and then exporting the desired dataframe. 

### Document 2: Geo-Queries-Near

#### Here I guide you through the steps I take to get the GeoQueries and filter which companies meet my desired criteria. 

### Document3: Tableu Public (Link inside Geo-Queries-Near)

