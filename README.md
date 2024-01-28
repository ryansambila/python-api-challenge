for this challenge we had to connect to 2 api sites and bring in data to graph. 

1. WheatherPy is the Jupyter Lab file that will pull from OpenWheather to get latitudes and longitudes of cities to graph; temp, humidity, cloudiness and wind speed.
     -API key is in the api_keys file
     -Gitignore was cretaed to hide the keys
     -graphs were exported to the output_data folder

3. VacationPy is the Jupyter Lab file that will pull from geoapify to get hotel information from the cities.csv file that was created in the WheatherPy code and put in the output file.  
    -API key is in the api_keys file
    -Gitignore was cretaed to hide the keys
    -Cities were filtered down to the final list by temps, wind speed, and cloudiness. 
