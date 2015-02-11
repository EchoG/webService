Developer¡¯s Name: Chenran Gong

In this lab, I called two kind of  webservice: weather and photo by using JSON and jQuery in JavaScript. 
In the weather webservice(http://openweathermap.org/api), I called two main methods. The first one returns the current weather conditions of cities that users input, including temperature, max temperature, min temperature, weather description, and icons to show weather clearly. 
The second method forecasts weather of cities that users input for 7 days in future and also includes date, temperature, max temperature, min temperature, weather description, and icons every day.
In the photo webservice (ie. Google images API), I called the method by AJAX, sending the parameter, which is the city name users input, and getting the photos related to the city as well as showing these photos. Sometimes, the returned url of photos is invalid, such as when searching mountain view, and I think it is the inner problem of the webservce that I called. So I just put a default photo in order to keep UI looking well. This kind of problem does not happen often, just few case.
The lab includes 2 files: design.html, design.css, both of which are in the WebContent directory.
When running the design.html file on tomcat, input the city name and click the button named ¡®search¡¯. Then all the data will be showed on the UI. 
