# Weather Channel (the app)


![Steve Carrell in Anchorman](http://cdn.collider.com/wp-content/uploads/anchorman-2-the-legend-continues-steve-carell.jpg)


For a world without windows... An app that tells you if it's raining outside!

## Getting Started

In order to use Weather Report (the app), you'll need to register for a free API key. It's actually not too complicated.

#### API Key

1) Register for a free API key at Dark Skies website (https://darksky.net/dev)  
2) Open Visual Studio
3) Make a new file in the Models folder called https://darksky.net/dev  
4) Put your API Key in the following code where the Xs are:

```
using System;

 namespace WeatherChannel.Models
 {     
  public class EnvironmentVariables     
  {         
    public static string AccountSid = "XXXXXXXXXXXXXXXXXXX";     
  }
 }
```

5) Save and quit.  

#### Clone & Start App

1) Clone the repository: `https://github.com/jamescosborn/weather-report`  
2) Navigate to project directory  
3) Type `dotnet restore` into the console  
4) Type `dotnet run` into the console  
5) Navigate to localhost:5000 in a web browser (Chrome recommended)  


### Technologies Used

Git  
github  
Atom  
Visual Studio  
Dark Sky API  

## Scheduled Updates

* Display Weather Reports on Home page

## Known Bugs

* No Known Bugs

## Contributors

James Carl Osborn  
jamescarlosborn@gmail.com    

## Project Specs

| Description        | Input           | Output  |
| ------------- |:-------------:| -----:|
| The user can enter the longitude and latitude for a geographical location to get that location's rain summary       | XX, XX       | Drizzling    |
| The user will get the following info: __Summary__, __Temperature__, __Precipitation Probability__ and __Cloud Coverage__        | XX, XX       | Drizzing, 47 Degrees, .6,  .3    |

## License

This project is licensed under the MIT License.

## Acknowledgments

* Thank you to my teachers, fellow students, friends, family and pets for your continued support and inspiration.  

![Weather Report's 1971 self-titled album](http://www.connollyco.com/discography/weather_report/weather82_hi.jpg)

*Album cover for Weather Report's self-titled album (1971).*
