Go Ubiquitous

Built a watch face for Android Wear so users can access Sunshine's weather information at a glance.
Implementations

App works on both round and square face watches.
App displays the current time.
App displays the high and low temperatures.
App displays a graphic that summarizes the day’s weather (e.g., a sunny image, rainy image, cloudy image, etc.).
Installation

Simply download or fork this repository and import into Android Studio. Add a OpenWeatherMap API key to the app's build.gradle file within the project.

it.buildConfigField 'String', 'OPEN_WEATHER_MAP_API_KEY', '"ApiKeyHere"'

Screenshots

![Watch Square FaceWatch](https://github.com/akshatgoel20/Sunshine_Watch_goUbiquitous/blob/master/wear/src/main/res/drawable-nodpi/preview_digital.png)

![Watch Round FaceWatch](https://github.com/akshatgoel20/Sunshine_Watch_goUbiquitous/blob/master/wear/src/main/res/drawable-nodpi/preview_digital_circular.png)
