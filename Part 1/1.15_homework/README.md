# Getting started
The image can be found at https://hub.docker.com/r/constantz/1.15_homework-countries 

1. Pull the image with ``` docker pull constantz/1.15_homework-countries ```
2. Start the image on port 3000 with ``` docker run -p 3000:3000 constantz/1.15_homework-countries ```. This may take a few seconds.
3. Open the application at http://localhost:3000 

# About 
This application provides certain basic information, such as population and capital, of a given country by searching for the country at the top of the page. Data about the countries are extracted from https://studies.cs.helsinki.fi/restcountries, and the orginal version of this application is done as part of the course Full Stack Open held by the University of Helsinki.

Note: weather of the country capital is currently not available since I haven't yet figured out a way to safely place the needed API key into the image.