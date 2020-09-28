# Weather Services 
RESTful Web Service using public API to read current weather information from data point values using JSON to create a daily/weekly forecast web page 


Reads the current weather information from data point values [https://darksky.net/dev/docs#data-point] to update the webpage for today's weather:

1. image_today : Displays an image for today's weather. Uses the icon data point and pairs it with an appropriate .png file (located in the img directory.)
2. icon_today : Displays the current icon value.
3. temp_today : Matches the current temperature.
4. thermometer_inner : Modifies the height of the thermometer to match the current temperature (i.e. if the current temperature is 32 F, then the thermometer will have a height of 32%)
5. precip_today : Matches the current probability for precipitation
6. humidity_today : Matches the current humidity percentage
7. wind_today : Matches the current wind speed.
8. summary_today: Matches the current summary for the day's weather
9. Processes the daily forecast for the next six days
