#  Clima

## Description

This is a dark-mode enabled weather app. You'll be able to check the weather for the current location based on the GPS data from the iPhone as well as by searching for a city manually.

## What I Learned

* How to create a dark-mode enabled app.
* How to use vector images as image assets.
* How to use the UITextField to get user input. 
* Delegate pattern.
* Swift protocols and extensions. 
* Swift guard keyword. 
* Swift computed properties.
* Swift closures and completion handlers.
* How to use URLSession to network and make HTTP requests.
* Parse JSON with the native Encodable and Decodable protocols. 
* How to use Grand Central Dispatch to fetch the main thread.
* How to use Core Location to get the current location from the phone GPS. 

### API Used

* [Open Weather Map](https://openweathermap.org/api)


### Condition Codes
```
switch conditionID {
        case 200...232:
            return "cloud.bolt"
        case 300...321:
            return "cloud.drizzle"
        case 500...531:
            return "cloud.rain"
        case 600...622:
            return "cloud.snow"
        case 701...781:
            return "cloud.fog"
        case 800:
            return "sun.max"
        case 801...804:
            return "cloud.sun"
        default:
            return "cloud"
        }
```

>This is a companion project to The App Brewery's Complete App Development Bootcamp.
