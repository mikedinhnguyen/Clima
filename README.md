
#  Clima

>This is a companion project to The App Brewery's Complete App Development Bootcamp, check out the full course at [www.appbrewery.co](https://www.appbrewery.co/)


Created a weather app using Application Programming Interfaces (APIs) to grab live data from the internet! I also learned how to implement dark mode into my apps and how to check a user's current location by tapping into GPS data from iPhone.   

To test out this application, you're going to need to acquire your own OpenWeather API key and insert it into WeatherManager.swift where *\(K.app_id)* is:

``` swift
let weatherURL = "https://api.openweathermap.org/data/2.5/weather?appid=\(K.app_id)&units=metric"
```

## What I learned

* How to create a dark-mode enabled app
* How to use vector images as image assets
* Learned to use the UITextField to get user input
* Learned about the delegate pattern
* Swift protocols and extensions  
* Swift guard keyword  
* Swift computed properties  
* Swift closures and completion handlers
* Learned to use URLSession to network and make HTTP requests
* Parsed JSON with the native Encodable and Decodable protocols 
* Learned to use Grand Central Dispatch to fetch the main thread
* Learned to use Core Location to get the current location from the phone GPS

![light mode](https://github.com/mikedinhnguyen/Clima/blob/master/Documentation/light_mode.png)
![dark mode](https://github.com/mikedinhnguyen/Clima/blob/master/Documentation/dark_mode.png)
